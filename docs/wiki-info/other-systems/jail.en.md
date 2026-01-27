<figure markdown="span">
  ![Prizonier](/images/wiki/general/female_jail.png){ width="450" }
  <figcaption>Prizonier</figcaption>
</figure>
Jucătorii care încalcă regulamentul social al serverelor RPG și nu se conformază ordinelor justiției, sunt automat încarcerați. Pedeapsa unui jucător variază în funcție de gravitatea faptei comise.


# Caracteristici generale
*Există două tipuri de pedepse cu închisoarea:
# Pedeapsa cu închisoarea oferită de polițiștii serverelor datorită încălcării regulamentului și acumulării de wanted (grad de urmărire).
# Pedeapsa cu închisoarea oferită de administratorii serverelor, datorită încălcării succesive a anumitor reguli.
*Deținuții sunt în mare parte supravegheați de către reprezentanții închisorii (membrii facțiunii National Guard).
*Un deținut nu poate să părăsească închisoarea.
*Un deținut are dreptul să ceară unui gardian să-l elibereze din celulă pentru a putea ajunge la bar.
*În curtea închisorii, deținuții pot să încerce să evadeze. Mai multe informații găsiți pe pagina Escape.
*Timpul pe care un jucător trebuie să-l petreacă în închisoare se salvează și după părăsirea serverului.
*Dacă deținuții sunt violenți cu ceilalți colegi de celulă, aceștia primesc pedepse din partea gardienilor (/punish, imposibilitatea de a se misca pentru un anumit număr de secunde).
*Dacă un deținut a fost închis de către un administrator (AJail), acesta nu poate fi eliberat pe cauțiune (/bail) și nici de către un avocat.
*Toate celulele închisorii se vor deschide la fiecare oră fixă și se vor închide 10 minute mai târziu, respectiv la fiecare jumătate de oră și se vor închide 10 minute mai târziu. În tot acest timp deținuții au dreptul să iasă în curtea închisorii. Celulele se deschid doar în intervalul 08:00 - 02:00.
*După închiderea celulelor, membrii National Guard au dreptul de a trimite înapoi în celule pe deținuții aflați încă în exteriorul acestora.
*Jucătorii din închisoare vor primi 2 minute în plus la pedeapsa curentă de fiecare dată când omoară un alt prizonier.
*Un prizonier poate fi scos din inchisoare de către un avocat pe baza unui mandat de eliberare **odată la 30 de minute**.


# Durata de pedeapsă
În funcție de gravitatea faptelor comise, un jucător primește un anumit grad de urmărire. În funcție de gradul de urmărire deținut și ținând cont de cazurile în care un jucător are sau nu drept de predare, acesta poate să fie pedepsit după cum urmează:


## Cu drept de predare
*Wanted 1 (Grad de urmărire 1) - 240 de secunde în închisoare
*Wanted 2 (Grad de urmărire 3) - 480 de secunde în închisoare
*Wanted 3 (Grad de urmărire 3) - 600 de secunde în închisoare
*Wanted 4 (Grad de urmărire 4) - 840 de secunde în închisoare
*Wanted 5 (Grad de urmărire 5) - 960 de secunde în închisoare
*Wanted 6 (Grad de urmărire 6) - 1080 de secunde în închisoare


## Fără drept de predare
*Wanted 1 (Grad de urmărire 1) - 500 de secunde în închisoare
*Wanted 2 (Grad de urmărire 3) - 1000 de secunde în închisoare
*Wanted 3 (Grad de urmărire 3) - 1500 de secunde în închisoare
*Wanted 4 (Grad de urmărire 4) - 2000 de secunde în închisoare
*Wanted 5 (Grad de urmărire 5) - 2500 de secunde în închisoare
*Wanted 6 (Grad de urmărire 6) - 3000 de secunde în închisoare


## Sume reţinute de către guvern
După ce aţi fost arestat sau procesat de către un poliţist, veţi plăti o sumă de bani către guvern pentru infracţiunile pe care le-aţi comis în funcţie de lista următoare. *Banii pe care îi pierdeţi nu vor ajunge în seiful primăriei, vor fi şterşi de pe server.*  
*Dacă jucătorul este arestat:
**Wanted Level 1 - 800$
**Wanted Level 2 - 1500$
**Wanted Level 3 - 2500$
**Wanted Level 4 - 4000$
**Wanted Level 5 - 6000$
**Wanted Level 6 - 7000$
*Dacă jucătorul este omorât:
**Wanted Level 1 - 1340$
**Wanted Level 2 - 2640$
**Wanted Level 3 - 3940$
**Wanted Level 4 - 5240$
**Wanted Level 5 - 6540$
**Wanted Level 6 - 7840$​​​


Notă: Atunci când un jucător este ucis de un polițist, numărul de secunde este calculat conform categoriei *fără drept de predare*. Dacă un jucător este arestat, va primi o pedeapsă din categoria *cu drept de predare*, în funcție de gradul de urmărire (wanted) deținut.


# Comenzi specifice
## /drink
Închisoarea deține un bar special de unde jucătorii pot să bea anumite băuturi pentru a-și majora procentul de viață. Tastarea comenzii /drink va afișa o listă a băuturilor disponibile, cât și prețul acestora.

## /exit
Este comanda folosită pentru a părăsi interiorul închisorii și pentru a ajunge în curtea acesteia. Pentru a funcționa, trebuie să vă aflați lângă ușa ieșirii spre curtea închisorii. *Comanda nu este specifică jailului, ea putând să fie folosită și în cazul altor sisteme (case, bizuri, etc.).*

## /bail
Această comandă afișează jucătorului anumite informații despre eliberarea sa contra unei sume de bani. Dacă jucătorul este dispus să plătească suma de bani afișată de server, poate continua procesul de eliberare conform instrucțiunilor oferite.
**Cauțiunea în funcție de wanted level:**
*Wanted 1 - bail 4.000$
*Wanted 2 - bail 6.500$
*Wanted 3 - bail 8.000$
*Wanted 4 - bail 11.000$
*Wanted 5 - bail 13.500$
*Wanted 6 - bail 15.000$

## /surrender
Această comandă poate fi folosită de jucătorii cu wanted (**indiferent dacă au drept de predare sau nu**) pentru a se preda. Comanda poate fi folosită doar în interiorul jailului. Dacă nu există niciun poliţist la datorie vă veţi putea preda automat, dacă există măcar un poliţist la datorie, veţi avea de aşteptat 5 minute până vă va aresta automat, dacă între timp nu ajunge un ofiţer pentru a vă aresta.
