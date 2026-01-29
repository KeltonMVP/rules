---
icon: material/robber
---

# Rob

<figure markdown="span">
  ![Politia la patrula](/images/wiki/general/bank_police_antirob.jpg){ width="400" }
  <figcaption>Politia la patrula</figcaption>
</figure>
<figure markdown="span">
  ![Meniul de rob](/images/wiki/general/rob_main.png){ width="400" }
  <figcaption>Meniul de rob</figcaption>
</figure>

Sistemul de rob permite jucatorilor sa jefuiasca case sau bizuri. Aceasta actiune este una ilegala care va fi sanctionata in mod automat cu wanted, drept urmare politia va fi pe urmele voastre.
Acesta cuprinde doua modalitati de-a face un jaf: **Solo sau pe Echipe**.


## Robul la ATM
Jefuirea unui ATM este o activitate de tip heist care implica armarea unei bombe, introducerea unui cod de activare, detonare, ridicarea unui sac personal cu bani si o secventa de extractie cu parapanta. Procesul combina un minigame de tip tastatura, conditii de acces pe contul jucatorului si o secventa finala de evadare, cu riscuri si penalizari in caz de esec.

### Cerinte pentru initiere
Pentru a incepe tentativa de jaf la un ATM, jucatorul trebuie sa indeplineasca toate conditiile urmatoare:

* Nivel minim 7.
* Minim 10 puncte de jaf (costul se scade la initiere; suma finala pierduta poate fi redusa de bonusurile de skin).
* Sa nu fie membru al politiei in acel moment.
* Sa nu aiba level de Wanted.
* Sa aiba o licenta de zbor valabila.
* Sa aiba cel putin o bomba creata in inventar.

### Declansarea jafului

* Jucatorul se apropie de orice ATM care nu a fost jefuit recent.
* Comerciantul de Explozibil trimite un SMS cu un cod de activare din 10 cifre.
* Pe ecran apare un element grafic (textdraw) cu bomba; jucatorul trebuie sa introduca exact cele 10 cifre pentru a arma bomba.
* Dupa initiere, tentativa este marcata ca intentie activa de jefuire.
* Interactiuni care anuleaza tentativa imediat: parasirea zonei ATM sau inchiderea interfetei inainte de finalizare → tentativa esueaza si se aplica un cooldown scurt.
* Daca jucatorul se deconecteaza sau moare in timp ce interfata cu bomba este activa, jaful esueaza automat si jucatorul primeste Wanted pentru tentativa.
* Daca se deconecteaza sau moare cand interfata nu este activa, jaful esueaza silentios fara aplicare de Wanted.

### Introducerea codului si rezultatele posibile

* Jucatorul tasteaza codul de 10 cifre primit prin SMS.
* Cod gresit sau incomplet → tentativa esueaza, are loc o explozie locala (daune/efecte locale) si jucatorul primeste Wanted pentru detonare esuata.
* Cod corect → bomba se armeaza, jucatorul o planteaza, iar dupa un scurt timer ATM-ul explodeaza. Bomba este consumata.
* Dupa detonare, ATM-ul intra in stare stricata; apare langa ATM un sac cu bani personal, care poate fi ridicat doar de jucatorul care a efectuat jaful.

<figure markdown="span">
  ![Sacul cu bani](/images/wiki/general/rob_bag.png){ width="400" }
  <figcaption>Sacul cu bani</figcaption>
</figure>

### Colectarea banilor

* Jucatorul are 90 de secunde pentru a ridica sacul de bani.
* Daca nu ridica sacul in acest interval → prada expira si jaful este considerat esuat.
* La colectare:
    * Jucatorul primeste Wanted pentru jaf.
    * ATM-ul devine dezactivat pentru un cooldown setat (implicit 180 s) — in aceasta perioada nu poate fi jefuit sau folosit pentru operatiuni bancare.
    * Dupa expirarea cooldown-ului, ATM-ul revine la starea normala.

### Stagiul de evadare

* Colectarea sacului initiaza procedura de evatare: este setat un checkpoint de evadare intr-un alt oras.
* Jucatorul trebuie sa se deplaseze la checkpoint cu un avion sau elicopter (daca nu are licenta de zbor valabila dupa ridicare, secventa nu porneste).
* La atingerea punctului de extractie, jucatorul este aruncat in aer si primeste o parapanta / parasuta automat.
* Exista un indicator de altitudine care ghideaza momentul deschiderii parasutei:
    * mai mare de 500 m - prea sus (deschiderea aici este considerata incorecta).
    * 350–500 m - BINE (fereastra sigura pentru deschidere).
    * mai mic de 350 m - prea jos (deschidere aici duce la esec).
* Deschiderea parasutei trebuie sa aiba loc in intervalul 350–500 m; deschiderea prea devreme sau prea tarziu duce la esec evadare.
* Daca parasuta este deschisa corect in intervalul indicat → evadarea reuseste, Wanted este eliminat, iar jaful este finalizat cu succes.

### Recompense la succes

* La colectarea sacului de bani si finalizarea cu succes a evadarii, jucatorul primeste:
* Recompensa financiara de baza, determinata de skill-ul la Rob (sume estimate):

    * Skill 1 → $12,500 – $17,500
    * Skill 2 → $17,500 – $22,500
    * Skill 3 → $22,500 – $27,500
    * Skill 4 → $27,500 – $32,500
    * Skill 5 → $32,500 – $37,500

* Recompensa poate fi marita de bonusuri active (maratoane), bonusuri de nivel si bonusuri provenite din skinuri posedate.
* 7 puncte de maraton pentru inceperea jafului (se acorda la succes):
    * 3 EXP de clan.
    * 1 punct de skill la Rob.
* Jucatorul pierde Rob Points la initiere (suma scazuta la final doar daca ridica sacul; reducere posibila prin bonusuri de skin).


## Comerciant Explozibil

Comerciantul de Explozibil este un NPC din San Fierro (accesibil prin /gps → Locatii Importante → Comerciant Explozibil) care permite jucatorilor sa produca bombe utilizabile la jafurile ATM.
Bombele se obtin prin comanda si colectare la un punct de pickup generat dupa confirmarea comenzii.

### Cerinte si costuri

Conditii pentru a plasa o comanda:

* Sa nu fie politist, sa nu aiba Wanted, sa nu fie intr-un job activ sau in grup de jaf, sa nu fie incatusat/freeze si sa nu fie intr-un vehicul.
* Sa nu detina deja 3 bombe in inventar (maximul e de 3).
* Sa aiba materiale suficiente pentru cost per bomba.

Cost materiale per bomba (scade cu skill Arms Dealer):

* Skill 1: 500.000
* Skill 2: 437.500
* Skill 3: 375.000
* Skill 4: 312.500
* Skill 5: 250.000

### Observatii si utilizare

* Jucatorul initiaza comanda la NPC (daca indeplineste conditiile).
* Dupa confirmare se genereaza un punct de ridicare (pickup).
* La colectare se consuma materialele si bombele sunt adaugate in inventar (pana la max 3).
* Materialele se scad la momentul colectarii, nu la confirmare.
* Bombele pot fi folosite pentru jefuirea ATM-urilor (conform regulilor jafului).
* Comenzile nu pot fi finalizate daca, intre confirmare si colectare, jucatorul isi pierde conditiile necesare (ex: devine Wanted sau intra in vehicul).
* Verifica nivelul skill Arms Dealer inainte de a comanda pentru a plati cat mai putine materiale.


## Robul de unul singur

<figure markdown="span">
  ![Circuit la solo rob](/images/wiki/general/Circuit.png){ width="400" }
  <figcaption>Circuit la solo rob</figcaption>
</figure>

<figure markdown="span">
  ![Spargerea seifului la solo rob](/images/wiki/general/Drill.png){ width="400" }
  <figcaption>Spargerea seifului la solo rob</figcaption>
</figure>

### Resurse necesare

Pentru a jefui o casa sau un biz aveti nevoie de:

* Cel putin nivel 7.
* Cel putin 15 puncte de jaf.
* Cazierul trebuie sa fie curat (fara wanted).
* Ora serverului sa fie intre 08:00 - 04:00.

### Procesul de jefuire

* Daca jucatorul indeplineste toate conditiile mentionate mai sus atunci acesta va putea initia comanda /rob in fata oricarei case sau biz de pe server.
* La folosirea comenzii se va deschide o fereastra de unde va trebui sa selecteze optiunea de **Solo Rob** (*imaginea ##2*).
* Dupa selectarea acestei optiuni jucatorul va intra automat intr-un interior special scazandu-i-se automat 10 puncte de jaf si va avea urmatoarele sarcini:
    * Sa sparga circuitul pentru a putea deschide usa de la incaperea seifului (*imaginea ##3*): cu ajutorul tastelor sus, jos, stanga, dreapta acesta trebuie sa directioneze sarma dintr-o parte a circuitului pana in cealalta fara a atinge peretii. Atingerea peretilor va rezulta in reinceperea din capatul initial al circuitului.
    * Sa sparga seiful cu ajutorul unui burghiu folosind tasta space (*imaginea ##4*). Burghiul se incalzeste cu cat este folosit mai mult, moment in care devine ineficient iar spargerea seifului dureaza mult mai mult. Pentru o spargere mai rapida este indicat sa pastrati burghiul cat mai rece. Aveti inclusiv un indice de temperatura pe burghiu ca sa vedeti cand se incalzeste prea tare.
* in incaperea speciala aveti la dispozitie cel mult 5 minute sa treceti prin aceste doua etape, in caz contrar robul va esua.
* Daca jucatorul se incadreaza in timpul necesar, acesta va fi scos in afara casei sau bizului jefuit cu un sac cu bani, primind totodata wanted 6 fara drept de predare pentru jaf.
* Urmatorul pas este ascunderea banilor furati la doua case diferite, jucatorul primind cate un checkpoint unde trebuie sa mearga. Asadar va recomandam sa aveti un vehicul in asteptare in momentul in care dati un astfel de jaf.
* Daca jucatorul reuseste sa duca banii la cele doua locatii atunci robul este finalizat cu succes, moment in care jucatorul primeste plata pe rob, i se mai scad inca 5 puncte de jaf si i se adauga un punct la skill.
* Daca jucatorul este omorat pe parcurs de catre politisti acesta va pierde robul si nu va mai primi plata, fiind inchis in puscarie.

### Castigul la Solo Rob

* Skill 1: intre $25.000 - $35.000
* Skill 2: intre $35.000 - $45.000
* Skill 3: intre $45.000 - $55.000
* Skill 4: intre $55.000 - $65.000
* Skill 5: intre $65.000 - $70.000


Aceste sume reprezinta castigul de baza, fara alte bonusuri oferite de alte sisteme de pe server.


## Robul in echipa
### Resurse necesare

Pentru a jefui o banca aveti nevoie de:

* O echipa formata din minim 4 si maxim 8 membrii.
* Fiecare membru trebuie sa detina cel putin nivel 7.
* Fiecare membru trebuie sa detina cel putin 10 puncte de jaf.
* Cel putin un membru al echipei este obligat sa aiba licenta de pilot.
* Cazierul fiecarui membru trebuie sa fie curat (fara wanted).

### Procesul de jefuire

* Daca exista cel putin 4 membri in echipa, creatorul echipei va vedea pe tabelul afisat prin tastarea comenzii /rob, o optiune numita "Next Step" ("Etapa Urmatoare").
* Aceasta optiune va trimite creatorul echipei catre o lista cu 21 locatii dintre care o poate alege pe cea care urmeaza a fi jefuita.
* Odata aleasa o locatie, toti membrii vor primi acces la chat-ul /rc, vizibil doar acelei echipe.


* Dupa alegerea locatiei jafului, liderul gruparii va trebui sa atribuie fiecarui membru al echipei cate un rol, folosind comanda /rob.

Roluri disponibile sunt:

- *Airplane Loaner* - are misiunea de a merge pe aeroport pentru a inchiria un avion cu care echipa urmeaza sa incerce sa evadeze dupa terminarea jafului.
- *Gold Melter* - are misiunea de a merge intr-o anumita locatie pentru a inchiria o locatie unde bijuteriile furate vor fi depozitate in vederea vinderii lor si obtinerii unei sume de bani. Locatia pe care o va alege cel cu rolul de Gold Melter va fi destinatia vehiculelor dupa plecarea de la magazinul jefuit.
- *Scout* - are misiunea de a merge intr-o anumita locatie pentru a inchiria armament, dupa care va trebui sa mearga la locatia jafului, sa urce pe un acoperis invecinat si sa distruga cele 4 camere de supraveghere.
- *Gas Man* - are misiunea de a merge intr-o anumita locatie pentru a inchiria fumigene. La momentul potrivit, va fi instiintat sa arunce aproximativ 10 fumigene in fata magazinului.

* Daca toti membrii au cate un rol stabilit, liderul echipei va avea optiunea de a trece la pasul urmator (prin tastarea comenzii /rob). Dupa trecerea la pasul urmator, fiecare membru isi va primi misiunea si se va indrepta catre locatia necesara. De asemenea, fiecarui membru i se vor consuma 3 Puncte de Jaf.

* Odata ce misiunile celor 4 roluri au fost indeplinite, toata echipa primeste permisiunea de a intra in magazin si de a incepe jaful. Un membru poate fura un anumit numar de bijuterii odata, in functie de skill:

    * Skill 1: 25 de bijuterii.
    * Skill 2: 30 de bijuterii.
    * Skill 3: 35 de bijuterii.
    * Skill 4: 40 de bijuterii.
    * Skill 5: 45 de bijuterii.

* in magazin exista 15 mese a cate 40 de bijuterii fiecare, pentru un total de 600 de bijuterii in intreg magazinul.
* Pentru a fura mai multe, membrul trebuie sa depoziteze mai intai ceea ce a furat intr-un vehicul. Vehiculele disponibile pentru jaf vor fi pregatite de membrii echipei inainte de inceperea jafului si pot fi doar masinile personale ale membrilor echipei, masini inchiriate de la bizurile de pe server sau masini simple gasite in diverse parcari de pe server.
* Nu se vor putea folosi avioane, elicoptere, biciclete, motociclete, barci, vehicule de factiune etc. O masina va putea transporta oricat de multe bijuterii. Daca un vehicul participant la jaf este distrus, despawnat etc., acesta va pierde orice cantitate de bijuterii din el. Daca un participant la jaf moare, acesta va pierde sacul cu bijuterii in cazul pe care il are.

* Toti participantii la jaf vor primi Wanted 6 si armura la 30 de secunde dupa ce prima bijuterie a fost ridicata de pe masa din magazin.
* Fiecare vehicul care ajunge la locatia aleasa de Gold Melter la un pas anterior va depozita la aceasta locatie cantitatea de bijuterii pe care o transporta.
* Din momentul in care primul vehicul ajunge, celelalte vehicule vor avea la dispozitie 5 minute pana ce se va distribui plata. Daca toti membrii echipei ajung la aceasta locatie, plata se va face fara a mai fi nevoie sa se astepte 5 minute.

* Plata se va face pe baza numarului total de bijuterii furate cu succes. O bijuterie valoreaza 626$. Din valoarea totala a bijuteriilor furate se va scadea un pret standard de 20,000$ care reprezinta pretul total al echipamentelor (avion, arme, grenade) necesare pentru jaf.
* Valoarea rezultata, profitul, se va imparti in mod egal tuturor membrilor ramasi in echipa la momentul platii. Daca nu exista profit (nu s-a furat suficient de mult), fiecare membru va primi 0$. Odata cu primirea banilor, indiferent de suma, membrilor echipei li se vor consuma inca 7 Puncte de Jaf si vor primi un punct pentru Skill.

* Dupa depozitarea bijuteriilor din vehicule, membrii vor primi un checkpoint catre aeroport. Primul membru al grupului care intra in checkpoint si care are o licenta de pilot va deveni automat pilotul avionului, iar orice alti membri care intra in checkpoint dupa aceea vor intra automat in interiorul avionului.
* Pilotul poate decola in orice moment si va primi un checkpoint in aer, la care, daca ajunge, el si toti membrii din interiorul avionului vor scapa de Wanted.

* Daca pilotul avionului moare, coboara din avion sau pierde avionul in orice alt mod, toti cei din interior vor fi teleportati afara si avionul nu va mai putea fi recuperat. Jucatorii vor fi teleportati in locul prabusirii avionului si vor ramane cu wanted.
* Daca unul din rolurile pentru jaf devine neocupat (membrii cu acel rol parasesc grupul din diverse motive) si obiectivele acelui rol nu au fost indeplinite, jaful va fi anulat automat.
* Un jaf poate dura cel mult o ora, dupa care se va anula automat.
* Un sunet de alarma se va auzi atunci cand jucatorii vor jefui magazine. Alarma porneste in momentul in care se fura prima bijuterie de pe masa si se termina dupa 3 minute.

### Castigul din urma jafului (formula de calcul)

<figure markdown="span">
  ![Castigul unui jaf la care au participat 4 jucatori](/images/wiki/general/castig_rob.png){ width="400" }
  <figcaption>Castigul unui jaf la care au participat 4 jucatori</figcaption>
</figure>

* castig = [* bijuterii_furate) - 20000]((626) / numar_membrii

**bijuterii_furate** reprezinta numarul de bijuterii adunate din magazin de catre toti membrii echipei.

**numar_membrii** reprezinta numarul de membrii aflati in echipa in momentul impartirii banilor de catre server.

## Avansare in skill
Pentru a avansa in skill, va trebui sa participati la jafuri de un anumit numar de ori dupa cum urmeaza:

* De 25 de ori pentru a trece de la skill 1 la skill 2
* De 50 de ori pentru a trece de la skill 2 la skill 3
* De 100 de ori pentru a trece de la skill 3 la skill 4
* De 200 de ori pentru a trece de la skill 4 la skill 5.

## Comenzi specifice

### /rob
Tastarea comenzii va afisa meniul cu optiuni pentru jaf. Este singura comanda principala a sistemului si toate actiunile specifice unui anumit pas al jafului sunt afisate in acest meniu. Creatorul echipei de jaf poate selecta un membru din lista pentru a il da afara din grup, actiune posibila doar in etapa de formare a grupului. Creatorul va putea invita maxim 8 jucatori in echipa.

### /robbers

Aceasta comanda poate fi folosita de jucatorii care doresc sa-si gaseasca mai usor o echipa de jaf:

* Pentru a va adauga pe lista, selectati "Adauga-ma pe lista...".
* Pentru a va sterge de pe lista selectati "sterge-ma de pe lista..." (sau selectati-va propriul nume din lista).
* Prin selectarea unui jucator din lista, se va initia automat un apel catre respectiva persoana.
* Politistii, jucatorii sub nivel 7, jucatorii cu wanted, jucatorii cu mai putin de 10 puncte de jaf si jucatorii aflati deja intr-o echipa *de rob nu vor putea folosi comanda respectiva.
* Jucatorii care se afla pe lista si devin inapti pentru a mai ramane acolo (de exemplu primesc jail), vor fi eliminati automat.
* Pot exista maxim 60 de jucatori pe lista in acelasi timp.
* Pe langa numele jucatorilor de pe lista, se vor mai afisa factiunea si nivelul.
* Jucatorii din lista vor fi eliminati automat dupa 10 minute de la adaugare si vor primi un mesaj specific.

### /accept rob id/nume jucator
Comanda poate fi utilizata pentru a accepta o invitatie de alaturare intr-un grup pentru jefuirea unui magazin.

### /cancel rob
Aceasta comanda va anula intregul jaf daca este executata de catre liderul (creatorul) grupului, sau va elimina din echipa jucatorul care o foloseste in cazul in care acest jucator nu este creatorul echipei.

### /grab
Aceasta comanda permite furtul bijuteriilor din interiorul magazinului jefuit. Pentru ca executia comenzii sa fie reusita, va trebui sa va aflati langa una dintre cele 15 mese cu bijuterii din magazin.

### /drop
Aceasta comanda depoziteaza bijuteriile furate in vehiculul langa care va aflati in momentul tastarii comenzii.

### /rc
Folosind aceasta comanda, membrii unei echipe vor putea comunica intre ei, oriunde s-ar afla.

### /enter, /goup, /godown
Aceste comenzi vor fi folosite pentru accesarea interiorului magazinului sau a acoperisurilor marcate in timpul jafului.

## Tutoriale

### Rob Solo

<iframe width="560" height="315" src="https://www.youtube.com/embed/rQRqIzvS3tM" frameborder="0" allowfullscreen></iframe>
