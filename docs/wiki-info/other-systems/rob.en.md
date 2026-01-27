<figure markdown="span">
  ![Poliția la patrulă](/images/wiki/general/bank_police_antirob.jpg){ width="400" }
  <figcaption>Poliția la patrulă</figcaption>
</figure>
<figure markdown="span">
  ![Meniul de rob](/images/wiki/general/rob_main.png){ width="400" }
  <figcaption>Meniul de rob</figcaption>
</figure>


Sistemul de rob permite jucătorilor să jefuiască case sau bizuri. Această acțiune este una ilegală care va fi sancționată în mod automat cu wanted, drept urmare poliția va fi pe urmele voastre.
Acesta cuprinde două modalități de-a face un jaf: **Solo sau pe Echipe**.


# Robul la ATM
Jefuirea unui ATM este o activitate de tip heist care implică armarea unei bombe, introducerea unui cod de activare, detonare, ridicarea unui sac personal cu bani și o secvență de extracție cu parapantă. Procesul combină un minigame de tip tastatură, condiții de acces pe contul jucătorului și o secvență finală de evadare, cu riscuri și penalizări în caz de eșec.

## Cerințe pentru inițiere
Pentru a începe tentativa de jaf la un ATM, jucătorul trebuie să îndeplinească toate condițiile următoare:
*Nivel minim 7.
*Minim 10 puncte de jaf (costul se scade la inițiere; suma finală pierdută poate fi redusă de bonusurile de skin).
*Să nu fie membru al poliției în acel moment.
*Să nu aibă level de Wanted.
*Să aibă o licență de zbor valabilă.
*Să aibă cel puțin o bombă creată în inventar.

## Declanșarea jafului
*Jucătorul se apropie de orice ATM care nu a fost jefuit recent.
*Comerciantul de Explozibil trimite un SMS cu un cod de activare din 10 cifre.
*Pe ecran apare un element grafic (textdraw) cu bomba; jucătorul trebuie să introducă exact cele 10 cifre pentru a arma bomba.
*După inițiere, tentativa este marcată ca intenție activă de jefuire.
*Interacțiuni care anulează tentativa imediat: părăsirea zonei ATM sau închiderea interfeței înainte de finalizare → tentativa eșuează și se aplică un cooldown scurt.
*Dacă jucătorul se deconectează sau moare în timp ce interfața cu bomba este activă, jaful eșuează automat și jucătorul primește Wanted pentru tentativă.
*Dacă se deconectează sau moare când interfața nu este activă, jaful eșuează silențios fără aplicare de Wanted.

## Introducerea codului și rezultatele posibile
*Jucătorul tastează codul de 10 cifre primit prin SMS.
*Cod greșit sau incomplet → tentativa eșuează, are loc o explozie locală (daune/efecte locale) și jucătorul primește Wanted pentru detonare eșuată.
*Cod corect → bomba se armează, jucătorul o plantează, iar după un scurt timer ATM-ul explodează. Bomba este consumată.
*După detonare, ATM-ul intră în stare stricată; apare lângă ATM un sac cu bani personal, care poate fi ridicat doar de jucătorul care a efectuat jaful.

<figure markdown="span">
  ![Sacul cu bani](/images/wiki/general/rob_bag.png){ width="400" }
  <figcaption>Sacul cu bani</figcaption>
</figure>
## Colectarea banilor
*Jucătorul are 90 de secunde pentru a ridica sacul de bani.
*Dacă nu ridică sacul în acest interval → prada expiră și jaful este considerat eșuat.
*La colectare:
**Jucătorul primește Wanted pentru jaf.
**ATM-ul devine dezactivat pentru un cooldown setat (implicit 180 s) — în această perioadă nu poate fi jefuit sau folosit pentru operațiuni bancare.
**După expirarea cooldown-ului, ATM-ul revine la starea normală.

## Stagiul de evadare
*Colectarea sacului inițiază procedura de evatare: este setat un checkpoint de evadare într-un alt oraș.
*Jucătorul trebuie să se deplaseze la checkpoint cu un avion sau elicopter (dacă nu are licență de zbor valabilă după ridicare, secvența nu pornește).
*La atingerea punctului de extracție, jucătorul este aruncat în aer și primește o parapantă / parașută automat.
*Există un indicator de altitudine care ghidează momentul deschiderii parașutei:
**> 500 m - prea sus (deschiderea aici este considerată incorectă).
**350–500 m - BINE (fereastra sigură pentru deschidere).
**< 350 m - prea jos (deschidere aici duce la eșec).
*Deschiderea parașutei trebuie să aibă loc în intervalul 350–500 m; deschiderea prea devreme sau prea târziu duce la eșec evadare.
*Dacă parașuta este deschisă corect în intervalul indicat → evadarea reușește, Wanted este eliminat, iar jaful este finalizat cu succes.

## Recompense la succes
*La colectarea sacului de bani și finalizarea cu succes a evadării, jucătorul primește:
*Recompensă financiară de bază, determinată de skill-ul la Rob (sume estimate):
**Skill 1 → $12,500 – $17,500
**Skill 2 → $17,500 – $22,500
**Skill 3 → $22,500 – $27,500
**Skill 4 → $27,500 – $32,500
**Skill 5 → $32,500 – $37,500
*Recompensa poate fi mărită de bonusuri active (maratoane), bonusuri de nivel și bonusuri provenite din skinuri posedate.
*7 puncte de maraton pentru începerea jafului (se acordă la succes):
**3 EXP de clan.
**1 punct de skill la Rob.
*Jucătorul pierde Rob Points la inițiere (suma scăzută la final doar dacă ridică sacul; reducere posibilă prin bonusuri de skin).


# Comerciant Explozibil
Comerciantul de Explozibil este un NPC din San Fierro (accesibil prin /gps → Locații Importante → Comerciant Explozibil) care permite jucătorilor să producă bombe utilizabile la jafurile ATM. 
Bombele se obțin prin comandă și colectare la un punct de pickup generat după confirmarea comenzii.

## Cerințe și costuri
Condiții pentru a plasa o comandă:
*Să nu fie polițist, să nu aibă Wanted, să nu fie într-un job activ sau în grup de jaf, să nu fie încătușat/freeze și să nu fie într-un vehicul.
*Să nu dețină deja 3 bombe în inventar (maximul e de 3).
*Să aibă materiale suficiente pentru cost per bombă.
Cost materiale per bombă (scade cu skill Arms Dealer):
*Skill 1: 500.000
*Skill 2: 437.500
*Skill 3: 375.000
*Skill 4: 312.500
*Skill 5: 250.000

## Observații și utilizare
*Jucătorul inițiază comanda la NPC (dacă îndeplinește condițiile).
*După confirmare se generează un punct de ridicare (pickup).
*La colectare se consumă materialele și bombele sunt adăugate în inventar (până la max 3).
*Materialele se scad la momentul colectării, nu la confirmare.
*Bombele pot fi folosite pentru jefuirea ATM-urilor (conform regulilor jafului).
*Comenzile nu pot fi finalizate dacă, între confirmare și colectare, jucătorul își pierde condițiile necesare (ex: devine Wanted sau intră în vehicul).
*Verifică nivelul skill Arms Dealer înainte de a comanda pentru a plăti cât mai puține materiale.


# Robul de unul singur
<figure markdown="span">
  ![Circuit la solo rob](/images/wiki/general/Circuit.png){ width="400" }
  <figcaption>Circuit la solo rob</figcaption>
</figure>
<figure markdown="span">
  ![Spargerea seifului la solo rob](/images/wiki/general/Drill.png){ width="400" }
  <figcaption>Spargerea seifului la solo rob</figcaption>
</figure>
## Resurse necesare
Pentru a jefui o casă sau un biz aveți nevoie de:
* Cel puțin nivel 7.
* Cel puțin 15 puncte de jaf.
* Cazierul trebuie să fie curat (fără wanted).
* Ora serverului să fie între 08:00 - 04:00.

## Procesul de jefuire
* Dacă jucătorul îndeplinește toate condițiile menționate mai sus atunci acesta va putea iniția comanda /rob în fața oricărei case sau biz de pe server.
* La folosirea comenzii se va deschide o fereastră de unde va trebui să selecteze opțiunea de **Solo Rob** (*imaginea #2*).
* După selectarea acestei opțiuni jucătorul va intra automat într-un interior special scăzându-i-se automat 10 puncte de jaf și va avea următoarele sarcini:
** Să spargă circuitul pentru a putea deschide ușa de la încăperea seifului (*imaginea #3*): cu ajutorul tastelor sus, jos, stânga, dreapta acesta trebuie să direcționeze sârma dintr-o parte a circuitului până în cealaltă fără a atinge pereții. Atingerea pereților va rezulta în reînceperea din capătul inițial al circuitului.
** Să spargă seiful cu ajutorul unui burghiu folosind tasta space (*imaginea #4*). Burghiul se încălzește cu cât este folosit mai mult, moment în care devine ineficient iar spargerea seifului durează mult mai mult. Pentru o spargere mai rapidă este indicat să păstrați burghiul cât mai rece. Aveți inclusiv un indice de temperatură pe burghiu ca să vedeți când se încălzește prea tare.
* În încăperea specială aveți la dispoziție cel mult 5 minute să treceți prin aceste două etape, în caz contrar robul va eșua.
* Dacă jucătorul se încadrează în timpul necesar, acesta va fi scos în afara casei sau bizului jefuit cu un sac cu bani, primind totodată wanted 6 fără drept de predare pentru jaf.
* Următorul pas este ascunderea banilor furați la două case diferite, jucătorul primind câte un checkpoint unde trebuie să meargă. Așadar vă recomandăm să aveți un vehicul în așteptare în momentul în care dați un astfel de jaf.
* Dacă jucătorul reușește să ducă banii la cele două locații atunci robul este finalizat cu succes, moment în care jucătorul primește plata pe rob, i se mai scad încă 5 puncte de jaf și i se adaugă un punct la skill.
* Dacă jucătorul este omorât pe parcurs de către polițiști acesta va pierde robul și nu va mai primi plata, fiind închis în pușcărie.

## Câștigul la Solo Rob
* Skill 1: Între $25.000 - $35.000
* Skill 2: Între $35.000 - $45.000
* Skill 3: Între $45.000 - $55.000
* Skill 4: Între $55.000 - $65.000
* Skill 5: Între $65.000 - $70.000


Aceste sume reprezintă câștigul de bază, fără alte bonusuri oferite de alte sisteme de pe server.


# Robul în echipă
## Resurse necesare
Pentru a jefui o bancă aveți nevoie de:
*O echipă formată din minim 4 și maxim 8 membrii.
*Fiecare membru trebuie să dețină cel puțin nivel 7.
*Fiecare membru trebuie să dețină cel puțin 10 puncte de jaf.
*Cel puţin un membru al echipei este obligat să aibă licenţă de pilot.
*Cazierul fiecarui membru trebuie să fie curat (fără wanted).

## Procesul de jefuire
*Dacă există cel puţin 4 membri în echipă, creatorul echipei va vedea pe tabelul afișat prin tastarea comenzii /rob, o opţiune numită "Next Step" ("Etapa Urmatoare"). Această opţiune va trimite creatorul echipei către o listă cu 21 locaţii dintre care o poate alege pe cea care urmează a fi jefuită. Odată aleasă o locaţie, toţi membrii vor primi acces la chat-ul /rc, vizibil doar acelei echipe.


*După alegerea locației jafului, liderul grupării va trebui să atribuie fiecărui membru al echipei cate un rol, folosind comanda /rob.
Roluri disponibile sunt:
# *Airplane Loaner* - are misiunea de a merge pe aeroport pentru a închiria un avion cu care echipa urmează să încerce să evadeze după terminarea jafului.
# *Gold Melter* - are misiunea de a merge într-o anumită locaţie pentru a închiria o locaţie unde bijuteriile furate vor fi depozitate în vederea vinderii lor şi obţinerii unei sume de bani. Locaţia pe care o va alege cel cu rolul de Gold Melter va fi destinaţia vehiculelor după plecarea de la magazinul jefuit.
# *Scout* - are misiunea de a merge într-o anumită locaţie pentru a închiria armament, după care va trebui să meargă la locaţia jafului, să urce pe un acoperiş învecinat şi să distrugă cele 4 camere de supraveghere.
# *Gas Man* - are misiunea de a merge într-o anumită locaţie pentru a închiria fumigene. La momentul potrivit, va fi înştiinţat să arunce aproximativ 10 fumigene în faţa magazinului.

*Dacă toţi membrii au câte un rol stabilit, liderul echipei va avea opţiunea de a trece la pasul următor (prin tastarea comenzii /rob). După trecerea la pasul următor, fiecare membru îşi va primi misiunea şi se va îndrepta către locaţia necesară. De asemenea, fiecarui membru i se vor consuma 3 Puncte de Jaf.
*Odată ce misiunile celor 4 roluri au fost îndeplinite, toată echipa primeşte permisiunea de a intra în magazin şi de a începe jaful. Un membru poate fura un anumit număr de bijuterii odată, în funcţie de skill:
# Skill 1: 25 de bijuterii.
# Skill 2: 30 de bijuterii.
# Skill 3: 35 de bijuterii.
# Skill 4: 40 de bijuterii.
# Skill 5: 45 de bijuterii.

*În magazin există 15 mese a câte 40 de bijuterii fiecare, pentru un total de 600 de bijuterii în întreg magazinul. 
*Pentru a fura mai multe, membrul trebuie să depoziteze mai întâi ceea ce a furat într-un vehicul. Vehiculele disponibile pentru jaf vor fi pregătite de membrii echipei înainte de începerea jafului şi pot fi doar maşinile personale ale membrilor echipei, maşini închiriate de la bizurile de pe server sau maşini simple găsite în diverse parcări de pe server. 
*Nu se vor putea folosi avioane, elicoptere, biciclete, motociclete, bărci, vehicule de facţiune etc. O maşină va putea transporta oricât de multe bijuterii. Dacă un vehicul participant la jaf este distrus, despawnat etc., acesta va pierde orice cantitate de bijuterii din el. Dacă un participant la jaf moare, acesta va pierde sacul cu bijuterii în cazul pe care îl are.

*Toţi participanţii la jaf vor primi Wanted 6 și armură la 30 de secunde după ce prima bijuterie a fost ridicată de pe masa din magazin. 
*Fiecare vehicul care ajunge la locaţia aleasă de Gold Melter la un pas anterior va depozita la această locaţie cantitatea de bijuterii pe care o transporta. 
*Din momentul în care primul vehicul ajunge, celelalte vehicule vor avea la dispoziţie 5 minute până ce se va distribui plata. Dacă toţi membrii echipei ajung la această locaţie, plata se va face fără a mai fi nevoie să se aştepte 5 minute.

*Plata se va face pe baza numărului total de bijuterii furate cu succes. O bijuterie valorează 626$. Din valoarea totală a bijuteriilor furate se va scădea un preţ standard de 20,000$ care reprezintă preţul total al echipamentelor (avion, arme, grenade) necesare pentru jaf. 
*Valoarea rezultată, profitul, se va împărţi în mod egal tuturor membrilor rămaşi în echipă la momentul plăţii. Dacă nu există profit (nu s-a furat suficient de mult), fiecare membru va primi 0$. Odată cu primirea banilor, indiferent de sumă, membrilor echipei li se vor consuma încă 7 Puncte de Jaf şi vor primi un punct pentru Skill.

*După depozitarea bijuteriilor din vehicule, membrii vor primi un checkpoint către aeroport. Primul membru al grupului care intră în checkpoint şi care are o licenţă de pilot va deveni automat pilotul avionului, iar orice alţi membri care intră în checkpoint după aceea vor intra automat în interiorul avionului. 
*Pilotul poate decola în orice moment şi va primi un checkpoint in aer, la care, dacă ajunge, el şi toţi membrii din interiorul avionului vor scăpa de Wanted. 

*Dacă pilotul avionului moare, coboară din avion sau pierde avionul în orice alt mod, toţi cei din interior vor fi teleportaţi afară şi avionul nu va mai putea fi recuperat. Jucătorii vor fi teleportați în locul prăbușirii avionului și vor rămâne cu wanted. 
*Dacă unul din rolurile pentru jaf devine neocupat (membrii cu acel rol părăsesc grupul din diverse motive) şi obiectivele acelui rol nu au fost îndeplinite, jaful va fi anulat automat.
*Un jaf poate dura cel mult o oră, după care se va anula automat.
*Un sunet de alarmă se va auzi atunci când jucatorii vor jefui magazine. Alarma pornește în momentul în care se fură prima bijuterie de pe masă și se termină după 3 minute.

## Câștigul din urma jafului (formulă de calcul)
<figure markdown="span">
  ![Câștigul unui jaf la care au participat 4 jucători](/images/wiki/general/castig_rob.png){ width="400" }
  <figcaption>Câștigul unui jaf la care au participat 4 jucători</figcaption>
</figure>
* câștig = [* bijuterii_furate) - 20000]((626) / număr_membrii
***bijuterii_furate** reprezintă numărul de bijuterii adunate din magazin de către toți membrii echipei.*
***număr_membrii** reprezintă numărul de membrii aflați în echipă în momentul împărțirii banilor de către server.*

# Avansare în skill
Pentru a avansa în skill, va trebui să participați la jafuri de un anumit număr de ori după cum urmează:
*De 25 de ori pentru a trece de la skill 1 la skill 2
*De 50 de ori pentru a trece de la skill 2 la skill 3
*De 100 de ori pentru a trece de la skill 3 la skill 4
*De 200 de ori pentru a trece de la skill 4 la skill 5.

# Comenzi specifice
## /rob
Tastarea comenzii va afișa meniul cu opţiuni pentru jaf. Este singura comandă principală a sistemului şi toate acţiunile specifice unui anumit pas al jafului sunt afişate în acest meniu. Creatorul echipei de jaf poate selecta un membru din listă pentru a îl da afară din grup, acţiune posibilă doar în etapa de formare a grupului. Creatorul va putea invita maxim 8 jucători în echipă.

## /robbers
Această comandă poate fi folosită de jucătorii care doresc să-și găsească mai ușor o echipă de jaf:
*Pentru a vă adăuga pe listă, selectați "Adauga-ma pe lista...".
*Pentru a vă șterge de pe listă selectați "Șterge-ma de pe listă..." (sau selectați-vă propriul nume din listă).
*Prin selectarea unui jucător din listă, se va iniția automat un apel către respectiva persoană.
*Polițiștii, jucătorii sub nivel 7, jucătorii cu wanted, jucătorii cu mai puțin de 10 puncte de jaf și jucătorii aflați deja într-o echipă *de rob nu vor putea folosi comanda respectivă.
*Jucătorii care se află pe listă și devin inapți pentru a mai rămâne acolo (de exemplu primesc jail), vor fi eliminați automat.
*Pot exista maxim 60 de jucători pe listă în același timp.
*Pe lângă numele jucătorilor de pe listă, se vor mai afișa facțiunea și nivelul.
*Jucătorii din listă vor fi eliminați automat după 10 minute de la adăugare și vor primi un mesaj specific.

## /accept rob <id/nume jucator>
Comanda poate fi utilizată pentru a accepta o invitație de alăturare într-un grup pentru jefuirea unui magazin.

## /cancel rob
Această comandă va anula întregul jaf dacă este executată de către liderul (creatorul) grupului, sau va elimina din echipă jucătorul care o foloseşte în cazul în care acest jucător nu este creatorul echipei.

## /grab
Această comandă permite furtul bijuteriilor din interiorul magazinului jefuit. Pentru ca execuția comenzii să fie reușită, va trebui să vă aflați lângă una dintre cele 15 mese cu bijuterii din magazin.

## /drop
Această comandă depozitează bijuteriile furate în vehiculul lângă care vă aflați în momentul tastării comenzii.

## /rc
Folosind această comandă, membrii unei echipe vor putea comunica între ei, oriunde s-ar afla.

## /enter, /goup, /godown
Aceste comenzi vor fi folosite pentru accesarea interiorului magazinului sau a acoperişurilor marcate în timpul jafului.

# Tutoriale
## Rob Solo
<html>
<iframe width="560" height="315" src="https://www.youtube.com/embed/rQRqIzvS3tM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</html>
