---
icon: material/calendar
---

# Events

Evenimentele sunt activitati interactive, de recreere, accesibile oricarui jucator de pe serverele B-Zone.

## Solicitarea unui eveniment

<figure markdown="span">
  ![Formular cerere eveniment](/images/wiki/general/requestevent.png){ width="600" }
  <figcaption>Formular cerere eveniment</figcaption>
</figure>

Pentru a solicita un eveniment se va folosi comanda */requestevent* de catre orice jucator de minim level 10.

Dupa executarea comenzii, un formular prin care veti seta modul de desfasurare a evenimentului va va fi afisat dupa cum urmeaza:

* Event Title - determina titlul evenimentului ce urmeaza sa se desfasoare.
* Minimum Level - nivelul minim necesar jucatorilor pentru a lua parte la eveniment.
* Maximum Level - nivelul maxim pana la care se va putea accesa evenimentul.
* Minimum Participants - numarul minim de participanti necesari pentru a incepe evenimentul.
* Maximum Participants - numarul maxim de jucatori ce vor putea lua parte la eveniment.
* Event Type - tipul de eveniment ce va fi creat.

Tipurile de evenimente sunt prestabilite dupa cum urmeaza:

- Ultimul jucator ramas
- Ultimul vehicul ramas
- Dueluri
- Protejeaza VIP-ul
- X/O
- SMS
- Trivia
- Whisper
- Stunt
- Kill
- Gaseste-l si adu-l
- Parkour
- Curse
- Simon spune
- Ruleta ruseasca
- Par/Impar
- Arena de curse
- Paintball
- Gungame
- War Arena
- Slenderman
- Risky Squares
- PubG

* Interior/Location - determina interiorul sau locatia in care se va desfasura evenimentul. Pentru fiecare tip de eveniment, sunt disponibile locatii diferite pentru organizare, organizatorul avand la dispozitie o lista prestabilita.
* Event Helpers - aloca evenimentului adjuvanti. Evenimentele pot avea maxim 3 adjuvanti.
* Prize - stabileste premiul evenimentului.

Modificarea formularului se face prin click pe campul ce urmeaza sa fie modificat.

Dupa editarea setarilor evenimentului, jucatorul va putea trimite evenimentul catre aprobare prin actionarea butonului **Submit**, cererea ramanand activa 5 minute si anulandu-se automat daca nu este acceptata.


**Note:**
Toate datele introduse in tabelul "Request Event" vor fi salvate pana la parasirea serverului.

Pentru a putea reseta valorile introduse, se poate folosi butonul **Clear Details**.

Unele evenimente (ex: SMS, Trivia, Whisper) se vor putea desfasura numai in lumea disponibila tuturor jucatorilor (Virtual World 0).

## Desfasurarea evenimentelor

* Dupa aprobarea evenimentului de catre echipa administrativa, organizatorul acestuia alaturi de adjuvantii selectati vor fi teleportati in locatia aleasa pentru desfasurarea evenimentului (daca este cazul).
* Evenimentul nu va fi deschis publicului pana cand organizatorul nu permite accesul jucatorilor in cadrul acestuia. Pentru a face asta, organizatorul va trebui sa selecteze un punct de teleportare pentru jucatorii ce se alatura cu ajutorul comenzii */emark*, dupa care sa porneasca inscrierile cu ajutorul comenzii */startjoins*.
* Din acest moment, orice jucator care indeplineste conditiile stabilite de catre organizator se va putea alatura folosind comanda */join*.
* Organizatorul va putea incheia inscrierile la eveniment cu ajutorul comenzii */stopjoins*, moment in care evenimentul va incepe.
*Organizatorului si adjuvantilor acestuia li se vor pune la dispozitie un numar de comenzi cu caracter administrativ cu scopul facilitarii unei desfasurari cat mai prielnice a evenimentului. Comenzile vor putea fi folosite doar pe jucatorii ce participa in prezent la eveniment. Pentru a vedea o lista cu aceste comenzi in orice moment, se poate accesa comanda */eventhelp*.
* Pe parcursul evenimentului, orice administrator sau helper de nivel 2+ se va putea alatura evenimentului ca adjuvant.
* Organizatorii au la dispozitie o ora sa finalizeze evenimentul, in caz contrar acesta se va opri automat. Acestia vor primi mesaje informative atunci cand mai au 30, 15, respectiv 5 minute la dispozitie sa finalizeze evenimentul.

## Comenzile disponibile si efectele acestora
* Atat organizatorul principal cat si cele 3 ajutoare vor avea la dispozitie multiple comenzi pentru a-si desfasura evenimentul, in functie de tipul acestuia:
    * Ultimul jucator ramas: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
    * Ultimul vehicul ramas: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Dueluri: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /setrespawnpoint
    * Protejeaza VIP-ul: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setrespawnpoint
    * X/O: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /xoquestion
    * SMS, Trivia, Whisper, Kill: /sethp
    * Stunt: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Gaseste-l si adu-l: /emark, /gotoemark, /setarmour, /disarm, /givegun, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Parkour: /emark, /gotoemark, /setarmour
    * Curse: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setfinishpoint
    * Simon spune, Ruleta ruseasca, Par/Impar, Slenderman: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
    * Arena de curse, War Arena, Paintball, Gungame: /sethpall, /participants, /emark, /gotoemark, /openarena
* Toate tipurile de evenimente dispun de comenzile: */e*, */sethp*, */stopevent*, */goto*. De asemenea, jucatorii pot folosi in orice moment comanda */eventhelp* pentru a vizualiza lista comenzilor disponibile pentru tipul de eveniment in desfasurare.
* Efectele comenzilor:

**Note:**

* **Se considera adjuvant, orice jucator ales de catre organizator pentru a face parte din structura evenimentului.**
* **Se considera participant, orice jucator afisat in lista */participants*.**
* **Organizatorul/adjuvantii pot aplica comenzile de mai jos doar asupra participantilor sau a adjuvantilor.**
    * /sethp - seteaza viata unui anumit participant/adjuvant.
    * /sethpall - seteaza viata tuturor participantilor, mai putin a adjuvantilor.
    * /ekick - inlatura un anumit participant de la eveniment.
    * /stopevent - opreste evenimentul aflat in desfasurare.
    * /startjoins - trimite mesaje specifice catre toti jucatorii online cu detaliile despre organizarea evenimentului si le ofera abilitatea de a tasta comanda */join*.
    * /stopjoins - blocheaza comanda */join*.
    * /e - trimite un mesaj pe chat-ul evenimentului. Daca evenimentul este unul in cadrul caruia se foloseste comanda */join*, atunci mesajele vor fi vazute numai de catre participanti, iar in caz contrar mesajele vor fi trimise catre toti jucatorii serverului.
    * /participants - afiseaza o lista cu participantii la eveniment (daca este un eveniment care accepta comanda */join*). Organizatorii pot inlatura un participant sau sa se teleporteze catre acesta prin selectarea lui din lista.
    * /emark - marcheaza punctul la care va aflati, pentru a va putea teleporta ulterior.
    * /gotoemark - teleporteaza catre punctul marcat prin */emark*.
    * /goto - va permite teleportarea catre un participant la eveniment.
    * /setarmour - seteaza armura unui anumit participant/adjuvant.
    * /setarmourall - seteaza armura tuturor participantilor, mai putin a adjuvantilor.
    * /disarm - dezarmeaza un participant.
    * /disarmall - dezarmeaza toti participantii, mai putin pe adjuvanti.
    * /givegun - ofera arme unui anumit participant.
    * /givegunall - ofera arme tuturor participantilor, mai putin adjuvantilor.
    * /freeze - ingheata un anumit participant.
    * /freezeall - ii ingheata pe toti participantii, mai putin pe adjuvanti.
    * /unfreeze - dezgheata un anumit participant.
    * /unfreezeall - ii dezgheata pe toti participantii, mai putin pe adjuvanti.
    * /veh - spawneaza un anumit vehicul (se pot spawna maxim 100 de vehicule).
    * /destroyveh - inlatura un anumit vehicul (ID-ul unui vehicul se poate vizuliza tastand comanda */dl*).
    * /destroyallveh - inlatura toate vehiculele spawnate la eveniment prin */veh*.
    * /fixveh - repara un anumit vehicul de la eveniment.
    * /fixallveh - repara toate vehiculele de la eveniment.
    * /fuelcar - alimenteaza cu combustibil un anumit vehicul de la eveniment.
    * /fuelallcars - alimenteaza cu combustibil toate vehiculele de la eveniment.
    * /requestevent - deschide formularul pentru trimiterea unei cereri de organizare de eveniment catre STAFF.
    * /join - teleporteaza catre locatia unde se organizeaza evenimentul (daca evenimentul este unul care accepta aceasta comanda). De asemenea organizatorii pot folosi oricand comanda pentru a se teleporta la locatia evenimentului.
    * /leaveevent - paraseste evenimentul (doar participantii pot folosi comanda).
    * /setrespawnpoint - seteaza un punct de respawn pentru participanti, unde vor fi teleportati in cazul in care acestia vor muri. Comanda este disponibila numai pentru evenimentele Dueluri si Protect the VIP.
    * /xoquestion - adreseaza o intrebare participantilor in cadrul evenimentului X/O.
    * /setfinishpoint - seteaza linia de sosire (checkpoint) pentru evenimentele de tip Race. Atunci cand un jucator va intra in respectivul checkpoint, organizatorii vor fi informati prin mesaje pentru a se putea stabili castigatorul unei curse.
    * /openarena - deblocheaza arena in cazul in care evenimentul se desfasoara la una dintre cele 4 arene (Paintball, Gungame, War Arena, Race Arena). Este necesara deblocarea, deoarece atunci cand un administrator/helper accepta o cerere de organizare a unui eveniment intr-o arena, arena respectiva se va incuia automat pentru a nu permite jucatorilor sa intre inainte.

## Detalii suplimentare

### Evenimentul X/O

* Se desfasoara intr-o [locatie special amenajata](http://imgur.com/a/JZv21) si reprezinta un tip de eveniment interactiv prin care organizatorii adreseaza intrebari jucatorilor, iar acestia trebuie sa se deplaseze in zona corespunzatoare raspunsului corect (X pentru NU si O pentru DA).
* Pentru adresarea unei intrebari se va folosi comanda */xoquestion* si se vor adresa intrebari la care se poate raspunde prin DA sau NU.
* Participantii vor avea la dispozitie 10 secunde sa aleaga partea in care vor sta (zona X pentru NU sau zona O pentru DA).
* Participantii care se afla in partea raspunsului gresit in momentul in care se scurg cele 10 secunde, vor cadea in apa deoarece [se vor deschide trapele zonei respective](http://imgur.com/a/Bh4JF) (si vor muri cateva secunde mai tarziu).

### Evenimentul Patratele Riscante
* Se desfasoara intr-o locatie special amenajata si reprezinta un tip de eveniment interactiv prin care jucatorii vor trebui sa doboare podeaua pentru a dobora ceilalti concurenti folosind un **SD-Pistol** si sa ramana in viata.
* In momentul in care jucatorul trage mai multe gloante in acelasi patratel acesta va incepe sa pice, iar daca jucatorul se afla pe acesta in momentul in care este doborat acesta va fi eliminat.
* Ultimii 3 participanti in viata sunt mentionati pentru organizator si ajutoare.
* Ultimul jucator in viata este castigator.
