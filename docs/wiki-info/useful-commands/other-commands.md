# Alte Comenzi

In aceasta pagina veti gasi comenzi care odata tastate in joc, afiseaza si ele la randul lor un nou set de comenzi.

## /cellphonehelp

Aceasta comanda afiseaza urmatorul set de comenzi:

### /p(ickup)

Efectul acesteia este de a raspunde la telefon in cazul in care cineva va apeleaza. Se pot utiliza ambele variante: /p sau /pickup.

### /h(angup)

Efectul acesteia este de a inchide o convorbire telefonica. Se pot utiliza ambele variante: /h sau /hangup.

### /call

Se foloseste pentru a apela un jucator.  
Pentru a utiliza aceasta comanda aveti nevoie de ID-ul sau numele jucatorului pe care doriti sa-l apelati.

_Exemplu: /call Madalin_

### /turn

Aceasta comanda va inchide, respectiv deschide telefonul, in functie de parametrul specificat:
- **/turn on** - va deschide telefonul.
- **/turn off** - va inchide telefonul.

### /speaker

Atunci cand va aflati intr-o convorbire telefonica, nimeni altcineva din jur nu poate sa vada convorbirea din partea interlocutorului, insa dupa utilizarea comenzii /speaker, mesajele vor deveni vizibile.

### /sms

Este o comanda folosita pentru a trimite mesaje text altor jucatori pe server, catre ID sau nume specificat.

_Exemplu: /sms Madalin B-Zone!_

## /renthelp

Aceasta comanda afiseaza urmatorul set de comenzi:

### /enter

Comanda /enter se foloseste de obicei pentru a intra in cladiri, in cazul acesta, in case. Comanda este executata cu succes (veti reusi sa intrati in casa) numai daca va aflati destul de aproape de usa cladirii respective.  
Pentru o executie mai rapida, puteti sa folositi echivalentul aceste comenzi, si anume tasta **"F"** de pe tastatura voastra.

### /exit

Comanda /exit se foloseste de obicei pentru a iesi dintr-o cladire, in cazul acesta, dintr-o casa. Comanda este executata cu succes (veti reusi sa iesiti din casa) numai daca va aflati destul de aproape de usa pe care se iese. Pentru o executie mai rapida, puteti sa folositi echivalentul aceste comenzi, si anume tasta **"F"** de pe tastatura voastra.

### /tenants

Comanda va afisa atat numarul cat si numele tuturor chiariasilor online (de pe server) in momentul tastarii comenzii.  
Doar chiriasii si proprietarul casei au acces la utilizarea acestei comenzi.

### /unrentroom

Folosind aceasta comanda, contractul de chirie pentru actuala locuinta va fi reziliat.

## /rentcarhelp

Aceasta comanda afiseaza urmatorul set de comenzi:

### /unrentvehicle

Aceasta comanda se utilizeaza pentru a renunta la vehiculul inchiriat si la cheile acestuia. Dupa utilizarea acestei comenzi, nu veti mai dispune de un vehicul inchiriat.

### /locaterentedcar

In cazul in care detineti un vehicul inchiriat si ati uitat unde l-ati lasat, atunci comanda /locaterentedcar va este de folos. Utilizand aceasta comanda, serverul va va fixa pe harta un punct rosu reprezentand destinatia vehiculului inchiriat.

### /vehicles

Aceasta comanda va afiseaza toate vehiculele pe care le detineti, inclusiv cele inchiriate pentru a putea sa interactionati cu acestea.

### /givekey

Aceasta comanda ofera cheile vehicului dumneavoastra altui jucator pentru a-l putea incuia sau descuia.

### /changelock

Aceasta comanda ofera posibilitatea proprietarului vehiculului sa schimbe incuietoarea vehiculului pentru a nu mai putea fi folosita de jucatorii carora le-a dat cheile.

### /park

Aceasta comanda ofera posibilitatea proprietarului vehiculului sa parcheze vehiculul in locul dorit de acesta.
- Pentru a putea parca vehiculul acesta nu trebuie sa fie lovit sau avariat.

## /eventhelp

Aceasta comanda afiseaza comenzile pe care le poti folosi la un eveniment, iar daca esti organizatorul unui eveniment si folosesti comanda, in functie de ce tip de event organizezi, o sa primesti o lista cu comenzile pe care le poti folosi. Aceasta comanda afiseaza urmatorul set de comenzi cand nu esti organizatorul/ajutorul unui eveniment:

### /event

In cazul in care exista un eveniment in desfasurare in momentul tastarii comenzii veti primi urmatoarele informatii:
- Titlul evenimentului aflat in desfasurare.
- Premiul evenimentului.
- Tipul si locatia desfasurarii acestuia.
- Numele organizatorului si adjuvantilor sai.
- Nivelul necesar pentru participarea la eveniment.
- Numarul minim si maxim de participanti.

### /requestevent

Aceasta comanda reprezinta un formular de cerere pe care helperii de nivel 2 si administratorii serverului B-Zone RPG il pot citi, urmand sa va accepte sau nu cererea de organizare a unui eveniment. Pentru mai multe informatii despre aceasta comanda accesati [aceasta](/other-systems/events) pagina.

### /join

Te alături unui eveniment in desfasurare daca acesta beneficiaza de aceasta optiune.

### /leaveevent

Daca esti participantului unui eveniment in desfasurare, folosind aceasta comanda o sa parasesti evenimentul.

## /leaderhelp

Aceasta comanda afiseaza urmatorul set de comenzi:

### /members

Folosind aceasta comanda, deschideti un meniu interactiv cu lista membrilor factiunii si doua optiuni separate.  
In cadrul membrilor, puteti vedea numele acestora, ultima data cand s-au logat, rank-ul si FWarn-urile.  
Legat de cele 2 optiuni, prima optiune este **Aplicatii Factiune**, iar folosindu-va de aceasta optiune puteti deschide aplicatiile factiunii direct din joc.  
A doua optiune este **Testele factiunii**, iar folosindu-va de aceasta optiune puteti edita unul dintre cele 2 test-loguri ale factiunii.

### /factiontest

Folosind aceasta comanda orice rank 4+ cu functia de Tester in factiune poate sa porneasca un test cu un candidat al factiunii.

### /tog

Folosind aceasta comanda, puteti gasi optiunea _Membrii pot folosi chatul factiunii_, dezactivand-o nici un membru al factiunii nu o sa mai poata folosi comanda /f, doar liderul si adminii 4+.

### /fvr

Prin executarea comenzii, toate vehiculele neocupate ale factiunii vor fi respawnate. Comanda este accesibila de la rang 5.

### /lc

Aceasta comanda este utilizata de liderii factiunilor pentru a vorbi pe chatul destinat liderilor.

### /fwithdraw

Tastand comanda /fwithdraw fara a specifica vreun parametru, veti obtine informatii despre suma de bani detinuta in acel moment de seiful factiunii. Pentru a sustrage bani din seiful factiunii, se foloseste drept parametru suma de bani.

_Exemplu: /fwithdraw 15000_

### /fmotd

Tastand comanda /fmotd fara a specifica vreun parametru, serverul va va trimete un mesaj prestabilit de catre lider sau sublider, in cazul in care acesta exista. Pentru a schimba mesajul prestabilit (mesajul zilei), se foloseste drept parametru, mesajul dorit.

_Exemplu: /fmotd Toata lumea la HQ!_

### /fget & /fput

Comanda este folosita pentru a pune sau a lua droguri sau materiale din HQ.

_Exemplu: /fgetdrugs 100 si /fgetmaterials 100000_

### /setgc

Folosind aceasta comanda un lider de mafie poate seta rank-ul minim de care ai nevoie pentru a trimite un mesaj pe /gc, chatul din timpul warului pe aliante.

### /vehrank

Comanda seteaza un rang minim pentru a folosi vehiculul factiunii respective.

_Nota: Aveti nevoie de minim rang 6 pentru a folosi aceasta comanda._

## /clanhelp

Aceasta comanda afiseaza urmatorul set de comenzi:

### /claninvite

Comanda /claninvite este folosita de catre detinatorii de clanuri si membrii cu rang 6+ pentru a invita pe cineva in propriul clan.

_Nota: Membrii cu rang 6+ pot folosi comanda doar pe jucatorii care au o aplicatie acceptata._

### /c

Comanda transmite un mesaj pe chatul [clanului](https://www.rpg.b-zone.ro/shop) din care faceti parte (doar in cazul in care faceti parte din unul).

_Exemplu: "/c mesaj"_

### /clanmembers

Comanda deschide un dialog cu toti membrii clanului din care faceti parte (doar in cazul in care faceti parte din unul).

### /clanresign

Cu aceasta comanda puteti parasi clanul in care va aflati.

### /setclanowner

Cu aceasta comanda, liderii de clan pot sa seteze alt lider de clan.

### /spray

Comanda este folosita langa un clan turf pentru a-l desena in numele clanului vostru.

### /clanxp

Comanda afiseaza un textdraw cu XP-ul pe care il are clanul in total si cat XP mai are pana avanseza la nivelul urmator.

### /clanzones

Comanda deschide un dialog cu toate turfurile de clan.

### /clanturfs

Comanda afiseaza toate turfurile de clan.

### /clancolor

Aceasta comanda poate fi folosita doar de liderii clanului, pentru a seta culoarea clanului.

### /clangoldwithdraw

Cu aceasta comanda, liderii de clan pot sa extraga Gold din seiful clanului.

### /cmotd

Comanda este folosita de catre liderii de clan pentru a seta un motto al clanului.

### /clanrename

Cu aceasta comanda, liderii de clan pot schimba numele rangurilor.

### /clanduty

Aceasta comanda va va pune la datorie la clan.

### /clanleaders

Comanda afiseaza toti liderii de clan care sunt pe server in acel moment.

### /ctalkpower

Aceasta comanda pune interdictie din a mai folosi comanda /c pentru un anumit rang. (minim rang 5+)

### /topclan

<img src="https://i.postimg.cc/fRB6X9pX/clan-top.png" width="300px">

Comanda afiseaza topul clanurilor detinатoare de turfuri.

### /clanwithdraw

Cu aceasta comanda, orice membru cu rang 6+ poate lua bani din seiful clanului.

### /clandeposit

Cu aceasta comanda puteti depozita bani in seiful clanului.

### /clanput & /clanget

Cu aceasta comanda puteti pune sau prelua materiale sau droguri.

_Exemplu: /clanputmaterials 1000000_

### /cwithdrawpower

Comanda este disponibila doar pentru liderii de clan, acestia pot seta un rang care poate folosi comanda /clanwithdraw si /clanget(drugs/materials)

### /claimhq

Comanda este disponibila doar pentru liderii de clan, cu aceasta comanda acestia pot prelua un HQ de Clan disponibil.

### /leavehq

Cu aceasta comanda, liderii de clan pot abandona un HQ de Clan.

### /interiorhq

Comanda este folosita de catre liderii clanurilor pentru a-si seta un interior al HQ-ului de Clan.

### /claninfo

Afiseaza anumite informatii legate de clan. _(doar pentru lideri)_

### /cvs & /cvr

Cu /cvs membrii unui clan pot sa-si spawneze vehiculele clanului, cu ajutorul comenzii /cvr, un membru cu rang 5+ poate respawna toate vehiculele clanului.

### /buyclanvehicle

Comanda este folosita de catre liderii de clan pentru a cumpara vehicule la clan.

### /clanwar

Comanda este folosita de membrii cu rang 5+ sau membrii care li s-au oferit acces la aceasta pentru a adauga/elimina jucatori din razboiul clanurilor.

### /guns

Cu aceasta comanda puteti sa va alegeti setul de arme in timpul razboaielor dintre clanuri.

### /leavewar

Cu aceasta comanda puteti iesi din razboiul clanului vostru.
