Evenimentele sunt activități interactive, de recreere, accesibile oricărui jucător de pe serverele B-Zone.

## Solicitarea unui eveniment
<figure markdown="span">
  ![Formular cerere eveniment](/images/wiki/general/requestevent.png){ width="600" }
  <figcaption>Formular cerere eveniment</figcaption>
</figure>
Pentru a solicita un eveniment se va folosi comanda */requestevent* de către orice jucător de minim level 10.
După executarea comenzii, un formular prin care veți seta modul de desfășurare a evenimentului vă va fi afișat după cum urmează:
* Event Title - determină titlul evenimentului ce urmează să se desfășoare.
* Minimum Level - nivelul minim necesar jucătorilor pentru a lua parte la eveniment.
* Maximum Level - nivelul maxim până la care se va putea accesa evenimentul.
* Minimum Participants - numărul minim de participanți necesari pentru a începe evenimentul.
* Maximum Participants - numărul maxim de jucători ce vor putea lua parte la eveniment.
* Event Type - tipul de eveniment ce va fi creat.
Tipurile de evenimente sunt prestabilite după cum urmează:
# Ultimul jucător rămas
# Ultimul vehicul rămas
# Dueluri
# Protejează VIP-ul
# X/O
# SMS
# Trivia
# Whisper
# Stunt
# Kill
# Găsește-l și adu-l
# Parkour
# Curse
# Simon spune
# Ruleta rusească
# Par/Impar
# Arenă de curse
# Paintball
# Gungame
# War Arena
# Slenderman
# Risky Squares
# PubG
* Interior/Location - determină interiorul sau locația în care se va desfășura evenimentul. Pentru fiecare tip de eveniment, sunt disponibile locații diferite pentru organizare, organizatorul având la dispoziție o listă prestabilită.
* Event Helpers - alocă evenimentului adjuvanți. Evenimentele pot avea maxim 3 adjuvanți.
* Prize - stabilește premiul evenimentului.
Modificarea formularului se face prin click pe câmpul ce urmează să fie modificat.
După editarea setărilor evenimentului, jucătorul va putea trimite evenimentul către aprobare prin acționarea butonului **Submit**, cererea rămânând activă 5 minute și anulându-se automat dacă nu este acceptată.


**Note:**
Toate datele introduse în tabelul "Request Event" vor fi salvate până la părăsirea serverului.
Pentru a putea reseta valorile introduse, se poate folosi butonul **Clear Details**.
Unele evenimente (ex: SMS, Trivia, Whisper) se vor putea desfășura numai în lumea disponibilă tuturor jucătorilor (Virtual World 0).

## Desfășurarea evenimentelor
* După aprobarea evenimentului de către echipa administrativă, organizatorul acestuia alături de adjuvanții selectați vor fi teleportați în locația aleasă pentru desfășurarea evenimentului (dacă este cazul).
* Evenimentul nu va fi deschis publicului până când organizatorul nu permite accesul jucătorilor în cadrul acestuia. Pentru a face asta, organizatorul va trebui să selecteze un punct de teleportare pentru jucătorii ce se alătura cu ajutorul comenzii */emark*, după care să pornească înscrierile cu ajutorul comenzii */startjoins*.
* Din acest moment, orice jucător care îndeplinește condițiile stabilite de către organizator se va putea alătura folosind comanda */join*.
* Organizatorul va putea incheia înscrierile la eveniment cu ajutorul comenzii */stopjoins*, moment în care evenimentul va începe.
*Organizatorului și adjuvanților acestuia li se vor pune la dispoziție un număr de comenzi cu caracter administrativ cu scopul facilitării unei desfășurări cât mai prielnice a evenimentului. Comenzile vor putea fi folosite doar pe jucătorii ce participă în prezent la eveniment. Pentru a vedea o listă cu aceste comenzi în orice moment, se poate accesa comanda */eventhelp*.
* Pe parcursul evenimentului, orice administrator sau helper de nivel 2+ se va putea alătura evenimentului ca adjuvant.
* Organizatorii au la dispoziție o oră să finalizeze evenimentul, în caz contrar acesta se va opri automat. Aceștia vor primi mesaje informative atunci când mai au 30, 15, respectiv 5 minute la dispoziție să finalizeze evenimentul.

## Comenzile disponibile și efectele acestora
* Atât organizatorul principal cât și cele 3 ajutoare vor avea la dispoziție multiple comenzi pentru a-și desfășura evenimentul, în funcție de tipul acestuia:
** Ultimul jucător rămas: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
** Ultimul vehicul rămas: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
** Dueluri: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /setrespawnpoint
** Protejează VIP-ul: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setrespawnpoint
** X/O: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /xoquestion
** SMS, Trivia, Whisper, Kill: /sethp
** Stunt: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
** Găsește-l si adu-l: /emark, /gotoemark, /setarmour, /disarm, /givegun, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
** Parkour: /emark, /gotoemark, /setarmour
** Curse: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setfinishpoint
** Simon spune, Ruleta rusească, Par/Impar, Slenderman: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
** Arena de curse, War Arena, Paintball, Gungame: /sethpall, /participants, /emark, /gotoemark, /openarena
* Toate tipurile de evenimente dispun de comenzile: */e*, */sethp*, */stopevent*, */goto*. De asemenea, jucătorii pot folosi în orice moment comanda */eventhelp* pentru a vizualiza lista comenzilor disponibile pentru tipul de eveniment în desfășurare.
* Efectele comenzilor:
**Note:**
***Se consideră adjuvant, orice jucător ales de către organizator pentru a face parte din structura evenimentului.**
*'*Se consideră participant, orice jucător afișat în lista */participants*.**
***Organizatorul/adjuvanții pot aplica comenzile de mai jos doar asupra participanților sau a adjuvanților.*'
** /sethp - setează viața unui anumit participant/adjuvant.
** /sethpall - setează viața tuturor participanților, mai puțin a adjuvanților.
** /ekick - înlătură un anumit participant de la eveniment.
** /stopevent - oprește evenimentul aflat în desfășurare.
** /startjoins - trimite mesaje specifice către toți jucătorii online cu detaliile despre organizarea evenimentului și le oferă abilitatea de a tasta comanda */join*.
** /stopjoins - blochează comanda */join*.
** /e - trimite un mesaj pe chat-ul evenimentului. Dacă evenimentul este unul în cadrul căruia se folosește comanda */join*, atunci mesajele vor fi văzute numai de către participanți, iar în caz contrar mesajele vor fi trimise către toți jucătorii serverului.
** /participants - afișează o listă cu participanții la eveniment (daca este un eveniment care acceptă comanda */join*). Organizatorii pot înlătura un participant sau să se teleporteze către acesta prin selectarea lui din listă.
** /emark - marchează punctul la care vă aflați, pentru a vă putea teleporta ulterior.
** /gotoemark - teleportează către punctul marcat prin */emark*.
** /goto - vă permite teleportarea către un participant la eveniment.
** /setarmour - setează armura unui anumit participant/adjuvant.
** /setarmourall - setează armura tuturor participanților, mai puțin a adjuvanților.
** /disarm - dezarmează un participant.
** /disarmall - dezarmează toți participanții, mai puțin pe adjuvanți.
** /givegun - oferă arme unui anumit participant.
** /givegunall - oferă arme tuturor participanților, mai puțin adjuvanților.
** /freeze - îngheață un anumit participant.
** /freezeall - îi îngheață pe toți participanții, mai puțin pe adjuvanți.
** /unfreeze - dezgheață un anumit participant.
** /unfreezeall - îi dezgheață pe toți participanții, mai puțin pe adjuvanți.
** /veh - spawnează un anumit vehicul (se pot spawna maxim 100 de vehicule).
** /destroyveh - înlătură un anumit vehicul (ID-ul unui vehicul se poate vizuliza tastând comanda */dl*).
** /destroyallveh - înlătură toate vehiculele spawnate la eveniment prin */veh*.
** /fixveh - repară un anumit vehicul de la eveniment.
** /fixallveh - repară toate vehiculele de la eveniment.
** /fuelcar - alimentează cu combustibil un anumit vehicul de la eveniment.
** /fuelallcars - alimenteaza cu combustibil toate vehiculele de la eveniment.
** /requestevent - deschide formularul pentru trimiterea unei cereri de organizare de eveniment catre STAFF.
** /join - teleportează către locația unde se organizează evenimentul (dacă evenimentul este unul care acceptă această comandă). De asemenea organizatorii pot folosi oricând comanda pentru a se teleporta la locația evenimentului.
** /leaveevent - părăsește evenimentul (doar participanții pot folosi comanda).
** /setrespawnpoint - setează un punct de respawn pentru participanți, unde vor fi teleportați în cazul în care aceștia vor muri. Comanda este disponibila numai pentru evenimentele Dueluri și Protect the VIP.
** /xoquestion - adresează o întrebare participanților în cadrul evenimentului X/O.
** /setfinishpoint - setează linia de sosire (checkpoint) pentru evenimentele de tip Race. Atunci când un jucător va intra în respectivul checkpoint, organizatorii vor fi informați prin mesaje pentru a se putea stabili câștigătorul unei curse.
** /openarena - deblochează arena în cazul în care evenimentul se desfășoară la una dintre cele 4 arene (Paintball, Gungame, War Arena, Race Arena). Este necesară deblocarea, deoarece atunci când un administrator/helper acceptă o cerere de organizare a unui eveniment intr-o arenă, arena respectivă se va încuia automat pentru a nu permite jucătorilor sa intre înainte.

## Detalii suplimentare
### Evenimentul X/O
*Se desfășoară într-o [locație special amenajată](http://imgur.com/a/JZv21) și reprezintă un tip de eveniment interactiv prin care organizatorii adresează întrebări jucătorilor, iar aceștia trebuie să se deplaseze în zona corespunzătoare răspunsului corect (X pentru NU și O pentru DA).
*Pentru adresarea unei întrebări se va folosi comanda */xoquestion* și se vor adresa întrebari la care se poate răspunde prin DA sau NU.
*Participanții vor avea la dispoziție 10 secunde să aleagă partea în care vor sta (zona X pentru NU sau zona O pentru DA).
*Participanții care se află în partea răspunsului greșit în momentul în care se scurg cele 10 secunde, vor cădea în apă deoarece [se vor deschide trapele zonei respective](http://imgur.com/a/Bh4JF) (si vor muri câteva secunde mai târziu).

### Evenimentul Pătrățele Riscante
*Se desfășoară într-o locație special amenajată și reprezintă un tip de eveniment interactiv prin care jucătorii vor trebui să doboare podeaua pentru a doboră ceilalți concurenți folosind un **SD-Pistol** și să rămână în viață.
*În momentul în care jucătorul trage mai multe gloanțe în același pătrățel acesta va începe să pice, iar dacă jucătorul se află pe acesta în momentul în care este doborât acesta va fi eliminat.
*Ultimii 3 participanți în viață sunt menționați pentru organizator și ajutoare.
*Ultimul jucător în viață este câștigător.
