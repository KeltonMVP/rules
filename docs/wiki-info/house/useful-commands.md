# Comenzi Uzuale - Case

<figure markdown="span">
  ![Exterior Casa](/images/wiki/general/House+SF.jpg){ width="400" }
  <figcaption>Exterior Casa</figcaption>
</figure>

<figure markdown="span">
  ![Text informativ](/images/wiki/general/HouseTextDraw.png){ width="400" }
  <figcaption>Text informativ</figcaption>
</figure>

<figure markdown="span">
  ![Lift la casa](/images/wiki/general/house_lift.png){ width="400" }
  <figcaption>Lift la casa</figcaption>
</figure>

Casele de pe serverele noastre sunt concepute in stil RPG, ceea ce inseamna ca imita in mare masura casele reale.

B-Zone va pune la dispozitie posibilitatea cumpararii unei case, vinderii unei case, posibilitatea inchirierii acesteia si de ce nu, va ofera un loc perfect pentru a va relaxa dormind, folosind comanda /sleep.

- Numai chiriasilor si proprietarului casei le este permisa utilizarea comenzilor /tenants si /sleep.
- Doar proprietarului casei ii este permisa utilizarea comenzilor /open, /setrentable, /setrent, /evict, /evictall, /sellhousetostate, /houseprice, /housewithdraw, /houseupgrade.
- In cazul in care usa casei nu este incuiata de catre proprietarul acesteia, absolut oricarui jucator ii este permisa folosirea comenzilor /heal, /enter si /exit. Daca usa este incuiata, comenzile stau doar la dispozitia chiriasilor si a proprietarului.
- Mobilierul din interiorul unei case va deveni invizibil pentru toti jucatorii daca proprietarul locuintei primeste wanted (nivel de urmarire).
- Proprietarului unei locuinte nu-i va fi permisa utilizarea comenzilor pentru adaugare sau editare de elemente de mobilier, in cazul in care acesta are cel putin 1 steluta de urmarire (wanted).

Mai jos puteti afla toate comenzile de control ale unei case.

## Comenzi

### /enter

Comanda /enter se foloseste de obicei pentru a intra in cladiri, in cazul acesta, in case. Daca comanda este executata cu succes (veti reusi sa intrati in casa) numai daca va aflati destul de aproape de usa cladirii respective. Pentru o executie mai rapida, puteti sa folositi echivalentul aceste comenzi, si anume tasta "F" de pe tastatura voastra.

### /exit

Comanda /exit se foloseste de obicei pentru a iesi dintr-o cladire, in cazul acesta, dintr-o casa. Daca comanda este executata cu succes (veti reusi sa iesiti din casa) numai daca va aflati destul de aproape de usa pe care se iese. Pentru o executie mai rapida, puteti sa folositi echivalentul aceste comenzi, si anume tasta "F" de pe tastatura voastra.

### /open

Cu ajutorul comenzii va puteti incuia si descuia propria casa. Daca alegeti sa incuiati casa, singurii jucatori care vor putea sa intre in continuare in interiorul casei sunt chiriasii si proprietarul.

Puteti beneficia de aceasta comanda numai in cazul in care sunteti detinatorul unei case. Pentru o executie cu succes a comenzii, trebuie sa va aflati in interiorul casei cat mai aproape de usa iesirii, sau in exteriorul acesteia, cat mai aproape de usa intrarii.

### /setrentable

Comanda ii comunica serverului daca doriti ca jucatorii sa poata deveni chiriasii vostri. Pentru a oferi casa spre inchiriere, folositi comanda "/setrentable Yes", in caz contrar folositi "/setrentable No".

### /setrent

Utilizand aceasta comanda, puteti seta pretul inchirierii casei. Fiecarui chiriasi pe care il detineti si care este online (conectat pe server) la PayDay i se va sustrage respectiva suma de dolari, banii urmand sa va fie depozitati in seiful casei. Comanda este executata corect si cu succes numai daca ati ales un pret cuprins intre $0 si $1000.

*Nota: Va este permisa folosirea comenzii numai in cazul in care este activata functia comenzii "/setrentable Yes".*

### /tenants

Comanda va afisa atat numarul cat si numele tuturor chiriasilor online (de pe server) in momentul tastarii comenzii. Doar chiriasii si proprietarul casei au acces la utilizarea acestei comenzi.

### /evict

Comanda are ca efect ruperea contractului de inchiriere a casei cu un chiriasi si sta la dispozitia oricarui proprietar de casa. Pentru o executie corecta si cu succes a comenzii, folositi-o in urmatoarele doua maniere: /evict <ID chiriasi> sau /evict <Nume chiriasi>.

*Exemplu: Se considera jucatorul Adi007 ca fiind chiriasul unei case si detinand ID-ul 12. Prin urmare, proprietarul casei va rupe contractul de inchiriere cu Adi007 folosind unul dintre urmatoarele exemple: /evict Adi007 sau /evict 12.*

### /evictall

Comanda are ca efect ruperea contractului de inchiriere a casei cu absolut toti chiriasii pe care casa ii gazduieste in momentul utilizarii acesteia.

### /sellhousetostate

In urma utilizarii acestei comenzi, veti vinde casa statului, singurii bani pe care ii veti incasa fiind cei aflati in seiful casei, numai in cazul in care acesta nu este gol.

### /houseprice

Utilizarea corecta a comenzii va duce la activarea posibilitatii ca un jucator al serverului sa va cumpere casa in schimbul sumei de bani pe care ati setat-o.

*Exemplu: "/houseprice 15000" va seta pretul casei la $15.000.*

Pretul minim pe care il puteti seta propriei case este reprezentat de produsul dintre nivelul casei si numarul 1.000.

*Exemplu: Daca detineti o casa ce are nivel 15, pretul minim pe care-l puteti seta este 15 inmultit cu 1.000, adica $15.000*

Pretul maxim pe care il puteti seta propriei case este reprezentat de produsul dintre nivelul casei si numarul 200.000.

*Exemplu: Daca detineti o casa ce are nivel 15, pretul maxim pe care-l puteti seta este 15 inmultit cu 200.000, adica $3.000.000*

Aceasta comanda va ofera sansa ca locuinta voastra sa fie vanduta chiar daca sunteti offline. Banii vor intra in contul vostru bancar.

### /heal

Pentru a utiliza comanda trebuie sa va aflati in interiorul unei case pe care o detineti sau sunteti chiriasi de cel putin 10 minute la aceasta. In urma executiei acesteia, veti avea 100 de unitati de viata (HP). Daca jucatorul ce tasteaza comanda face parte dintr-un departament si in acelasi timp casa beneficiaza de "armour upgrade", acesta va avea 100 de unitati de viata si 100 de unitati de armura.

### /sleep

Comanda este conceputa pentru a imita dormitul, astfel, prin folosirea comenzii caracterului vostru ii va fi aplicata o animatie specifica. Atunci cand dormiti, ceilalti jucatori vor vedea in anumite situatii, in dreptul numelui vostru, textul "(AFK)". Exemplu de comenzi ce sufera situatia descrisa: /id, /members, /clanmembers, etc.

Daca dormiti la ora PayDay-ului, veti primi punctul de respect necesar avansarii in nivel, insa numarul orelor jucate nu va creste.

Comanda nu functioneaza in apropierea usii de iesire din casa si nici in cazul in cazul in care sunteti urmarit de politie sau ati comis o infractiune in ultimele 60 de secunde de la tastarea comenzii. Niciun jucator nu va fi capabil sa va omoare in timp ce dormiti.

### /houseupgrade

Comanda va afisa un meniu simplu de unde va puteti renova casa. Actual, cu ajutorul acestui meniu veti putea adauga posibilitatea de majorare a rezervei de viata si armura, de a adauga obiecte decorative (mobila) si de a activa posibilitatea redarii unui post radio in interiorul casei.

Functiile Heal si Armour se pun in aplicare atunci cand un jucator foloseste comanda "/heal" in casa. Fiecare obiect selectat din meniu va costa $1.000. Upgradeurile pentru case se vor pierde in momentul vanzarii acesteia. Jucatorii vor putea adauga pana la 170 de obiecte maxim in casa.

### /removefurniture

Tastand aceasta comanda, toate elementele de mobila adaugate prin intermediul comenzii /houseupgrade, vor fi eliminate. Banii cheltuiti pe mobilierul ce urmeaza sa fie eliminat nu vor fi returnati.

### /editfurniture

Folosind aceasta comanda, serverul va va afisa o lista cu toate obiectele de mobilier pe care le-ati adaugat in casa. Apasand click pe unul dintre obiectele din lista, veti putea elimina respectivul obiect sau ii veti putea edita pozitia. Ordinea afisarii obiectelor in meniu este facuta de la cel mai nou adaugat, la cel mai vechi adaugat.

### /defaultfurniture

Prin tastarea acestei comenzi, puteti opta intre a crea sau distruge obiectele decorative ale locuintei (cele initiale, nu cele create de voi). Pentru a se efectua schimbarea, va trebui sa parasiti serverul si sa va conectati din nou la acesta. Este posibil ca obiectele initiale ale unei case sa nu poata fi afectate de aceasta comanda (sa nu puteti sa le ascundeti).

### /housewithdraw

Comanda are ca efect sustragerea banilor din seiful casei, bani produsi din chiria pe care chiriasii o platesc la fiecare PayDay.

Pentru a afla ce suma de bani detineti in seiful casei, tastati comanda /housewithdraw, fara a specifica suma pe care doriti sa o sustrasgeti din seif.

Daca doriti sa sustrageti o anumita suma de bani, tastati comanda dupa modelul urmator: *"/housewithdraw 500", va sustrage $500 din seiful casei.*

Pentru o executie corecta si cu succes a comenzii, trebuie sa va aflati in interiorul casei cat mai aproape de usa iesirii.

### /houseinfo

Pentru utilizarea comenzii nu trebuie sa va aflati langa casa sau in interiorul acesteia, comanda fiind utilizabila oriunde v-ati afla daca sunteti proprietarul unei case.

Prin tastarea comenzii, serverul va va arata cateva detalii despre casa voastra:

- Nivelul casei.
- Numarul de chiriasi conectati pe server.
- Daca este inchiriabila casa sau nu. Daca este inchiriabila, va aparea valoarea chiriei pe care ati setat-o folosind comanda /setrent.
- Daca respectiva casa este incuiata sau nu.
- Valoarea minima pentru care casa poate sa fie vanduta.
- Valoarea taxei percepute de stat (banii pe care nu-i vei primi atunci cand cineva iti va cumpara casa, insa acestia vor fi sustrasi din contul cumparatorului). Valoarea taxei este egala cu produsul dintre nivelul casei si numarul 100. *Exemplu (casa cu nivel 15): 15 inmultit cu 100, deci taxa este $1.500.*
- Numele casei, stabilit de proprietarul acesteia.

### /houseradio

Folosind aceasta comanda, proprietarul unei case va putea sa redea un post de radio sau un link YouTube in propria locuinta. Atunci cand un jucator va intra in respectiva casa, va auzi postul de radio sau coloana sonora de la YouTube, care au fost setate de catre proprietar. Prin folosirea comenzii /houseradio in interiorul unei locuinte care nu va apartine, veti putea controla abilitatea voastra de a auzi stream-urile audio din interiorul caselor. De asemenea, redarea sunetului poate fi oprita de catre proprietar folosind aceasta comanda.

### /housename

Folosind aceasta comanda, proprietarul unei case va putea sa isi seteze un nume al casei care va fi vizibil tuturor jucatorilor care se afla prin preajma casei respective.

<p style="color:rgb(200, 55,55);">Nota: Folosirea unor texte vulgare/jignitoare este sanctionabila de catre admini.</p>

### /lift

Acest sistem permite jucatorilor sa se teleporteze intre diverse zone ale casei (acoperis, parcare, in functie de disponibilitate). Doar proprietarul si chiriasii unei case care are lift vor putea folosi comanda /lift.
