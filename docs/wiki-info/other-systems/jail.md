<figure markdown="span">
  ![Prizonier](/images/wiki/general/female_jail.png){ width="450" }
  <figcaption>Prizonier</figcaption>
</figure>
Jucatorii care incalca regulamentul social al serverelor RPG si nu se conformaza ordinelor justitiei, sunt automat incarcerati. Pedeapsa unui jucator variaza in functie de gravitatea faptei comise.


# Caracteristici generale
*Exista doua tipuri de pedepse cu inchisoarea:
# Pedeapsa cu inchisoarea oferita de politistii serverelor datorita incalcarii regulamentului si acumularii de wanted (grad de urmarire).
# Pedeapsa cu inchisoarea oferita de administratorii serverelor, datorita incalcarii succesive a anumitor reguli.
*Detinutii sunt in mare parte supravegheati de catre reprezentantii inchisorii (membrii factiunii National Guard).
*Un detinut nu poate sa paraseasca inchisoarea.
*Un detinut are dreptul sa ceara unui gardian sa-l elibereze din celula pentru a putea ajunge la bar.
*in curtea inchisorii, detinutii pot sa incerce sa evadeze. Mai multe informatii gasiti pe pagina Escape.
*Timpul pe care un jucator trebuie sa-l petreaca in inchisoare se salveaza si dupa parasirea serverului.
*Daca detinutii sunt violenti cu ceilalti colegi de celula, acestia primesc pedepse din partea gardienilor (/punish, imposibilitatea de a se misca pentru un anumit numar de secunde).
*Daca un detinut a fost inchis de catre un administrator (AJail), acesta nu poate fi eliberat pe cautiune (/bail) si nici de catre un avocat.
*Toate celulele inchisorii se vor deschide la fiecare ora fixa si se vor inchide 10 minute mai tarziu, respectiv la fiecare jumatate de ora si se vor inchide 10 minute mai tarziu. in tot acest timp detinutii au dreptul sa iasa in curtea inchisorii. Celulele se deschid doar in intervalul 08:00 - 02:00.
*Dupa inchiderea celulelor, membrii National Guard au dreptul de a trimite inapoi in celule pe detinutii aflati inca in exteriorul acestora.
*Jucatorii din inchisoare vor primi 2 minute in plus la pedeapsa curenta de fiecare data cand omoara un alt prizonier.
*Un prizonier poate fi scos din inchisoare de catre un avocat pe baza unui mandat de eliberare **odata la 30 de minute**.


# Durata de pedeapsa
in functie de gravitatea faptelor comise, un jucator primeste un anumit grad de urmarire. in functie de gradul de urmarire detinut si tinand cont de cazurile in care un jucator are sau nu drept de predare, acesta poate sa fie pedepsit dupa cum urmeaza:


## Cu drept de predare
*Wanted 1 (Grad de urmarire 1) - 240 de secunde in inchisoare
*Wanted 2 (Grad de urmarire 3) - 480 de secunde in inchisoare
*Wanted 3 (Grad de urmarire 3) - 600 de secunde in inchisoare
*Wanted 4 (Grad de urmarire 4) - 840 de secunde in inchisoare
*Wanted 5 (Grad de urmarire 5) - 960 de secunde in inchisoare
*Wanted 6 (Grad de urmarire 6) - 1080 de secunde in inchisoare


## Fara drept de predare
*Wanted 1 (Grad de urmarire 1) - 500 de secunde in inchisoare
*Wanted 2 (Grad de urmarire 3) - 1000 de secunde in inchisoare
*Wanted 3 (Grad de urmarire 3) - 1500 de secunde in inchisoare
*Wanted 4 (Grad de urmarire 4) - 2000 de secunde in inchisoare
*Wanted 5 (Grad de urmarire 5) - 2500 de secunde in inchisoare
*Wanted 6 (Grad de urmarire 6) - 3000 de secunde in inchisoare


## Sume reţinute de catre guvern
Dupa ce aţi fost arestat sau procesat de catre un poliţist, veţi plati o suma de bani catre guvern pentru infracţiunile pe care le-aţi comis in funcţie de lista urmatoare. *Banii pe care ii pierdeţi nu vor ajunge in seiful primariei, vor fi şterşi de pe server.*  
*Daca jucatorul este arestat:
**Wanted Level 1 - 800$
**Wanted Level 2 - 1500$
**Wanted Level 3 - 2500$
**Wanted Level 4 - 4000$
**Wanted Level 5 - 6000$
**Wanted Level 6 - 7000$
*Daca jucatorul este omorat:
**Wanted Level 1 - 1340$
**Wanted Level 2 - 2640$
**Wanted Level 3 - 3940$
**Wanted Level 4 - 5240$
**Wanted Level 5 - 6540$
**Wanted Level 6 - 7840$​​​


Nota: Atunci cand un jucator este ucis de un politist, numarul de secunde este calculat conform categoriei *fara drept de predare*. Daca un jucator este arestat, va primi o pedeapsa din categoria *cu drept de predare*, in functie de gradul de urmarire (wanted) detinut.


# Comenzi specifice
## /drink
inchisoarea detine un bar special de unde jucatorii pot sa bea anumite bauturi pentru a-si majora procentul de viata. Tastarea comenzii /drink va afisa o lista a bauturilor disponibile, cat si pretul acestora.

## /exit
Este comanda folosita pentru a parasi interiorul inchisorii si pentru a ajunge in curtea acesteia. Pentru a functiona, trebuie sa va aflati langa usa iesirii spre curtea inchisorii. *Comanda nu este specifica jailului, ea putand sa fie folosita si in cazul altor sisteme (case, bizuri, etc.).*

## /bail
Aceasta comanda afiseaza jucatorului anumite informatii despre eliberarea sa contra unei sume de bani. Daca jucatorul este dispus sa plateasca suma de bani afisata de server, poate continua procesul de eliberare conform instructiunilor oferite.
**Cautiunea in functie de wanted level:**
*Wanted 1 - bail 4.000$
*Wanted 2 - bail 6.500$
*Wanted 3 - bail 8.000$
*Wanted 4 - bail 11.000$
*Wanted 5 - bail 13.500$
*Wanted 6 - bail 15.000$

## /surrender
Aceasta comanda poate fi folosita de jucatorii cu wanted (**indiferent daca au drept de predare sau nu**) pentru a se preda. Comanda poate fi folosita doar in interiorul jailului. Daca nu exista niciun poliţist la datorie va veţi putea preda automat, daca exista macar un poliţist la datorie, veţi avea de aşteptat 5 minute pana va va aresta automat, daca intre timp nu ajunge un ofiţer pentru a va aresta.
