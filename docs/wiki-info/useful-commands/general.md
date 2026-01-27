# Generale

In aceasta sectiune sunt prezentate comenzile generale ale serverului **B-Zone RPG**.

## /id

<img src="https://i.postimg.cc/WbxzxPfV/Idnic.png" width="400px" style="padding: 0px 0px 10px 0px">  
<img src="https://i.postimg.cc/MGW3f12W/idnewpng.png" width="400px" height="50px" style="padding: 0px 0px 10px 0px">  
<img src="https://i.postimg.cc/8PBVfSg2/diamond-Skin.png" width="400px" height="50px">

_Sintaxa: /id [PlayerID/PlayerName]_
- Comanda afiseaza informatii despre jucatorul respectiv:
  - ID-ul jucatorului.
  - Numele jucatorului.
  - Ping-ul dintre jucator si server.
  - FPS-urile jucatorului in timp real.
  - Nivelul curent al jucatorului.
  - Statusul jucatorului (**AFK**|**SLEEP**|**AFK & SLEEP**).
  - Numele factiunii din care face parte.
  - Tipul de skin pe care il detine (Daca acesta poarta un skin [Diamond sau Onyx](/other-systems/skin-upgrades)).
  - ID-ul skinului acestuia.

## /pay

_Sintaxa: /pay [PlayerID/PlayerName] [suma]_
- Aceasta comanda va trimite suma de bani in numerar specificata catre jucatorul respectiv.
- Jucatorii cu nivel mai mic ca 3 vor putea trimite maxim $10 per tranzactie.
- Limita pentru ceilalti jucatori este de $10.000. Tranzactiile se efectueaza cu o pauza de cateva secunde intre ele.
- Trebuie sa fiti langa jucatorul respectiv pentru a-i trimite bani.

## /buy

_Sintaxa: /buy_
- Cu ajutorul acestei comenzi, puteti cumpara obiecte din magazinele [24/7](/business/247).

## /givekey

_Sintaxa: /givekey [PlayerID/PlayerName]_
- Aceasta comanda va permite sa inmanati cheile vehiculului in care va aflati (trebuie sa-l detineti) altui jucator. Proprietarul nu-si pierde propriile chei. Respectivul va ramane in posesia cheilor pana se deconecteaza sau foloseste /throw.

## /drink

_Sintaxa: /drink [NumeleBauturii]_
- Cu aceasta comanda puteti cumpara bauturi din [cluburi si baruri](/business/clubs-bars).

## /turfs

<img src="https://i.postimg.cc/QMLGvwnK/turfs.png" width="300px">

_Sintaxa: /turfs_
- Comanda va suprapune zonele controlate de mafii, corespunzator culorii, peste harta din joc.
- Vizibil atat pe radar (minimap), cat si pe harta mare.
- Pentru a le scoate, folositi din nou comanda.

## /licenses

<img src="https://i.postimg.cc/vHYGYJzJ/Licenses.png" width="300px">

_Sintaxa: /licenses_
- Aceasta comanda afiseaza o lista cu toate licentele si informatii despre acestea: daca le aveti si pentru cat timp mai sunt valabile.

## /requestlicenses

_Sintaxa: /requestlicenses [PlayerID/PlayerName]_
- Comanda trimite o cerere jucatorului respectiv pentru a-i vedea licentele. Daca accepta, vi se va afisa o casuţa de dialog similara cu cea de la /licenses.

## /skills

<img src="https://i.postimg.cc/BQCdDZ5Q/Skills-list.png" width="200px">

_Sintaxa: /skills_
- Afiseaza skillurile pe care le aveti la joburi si de cate alte puncte mai aveti nevoie pentru a avansa.

## /sleep

_Sintaxa: /sleep_
- Intrati si iesiti din [modul AFK](/useful-commands/houses#sleep).

## /lotto

_Sintaxa: /lotto_
- Plasati bilete cu diferite numere la sistemul de [lotto](/other-systems/lotto).

## /cigarettes

_Sintaxa: /cigarettes_
- Afiseaza numarul de tigari pe care le aveti si daca detineti sau nu o bricheta.

## /spawnchange

<img src="https://i.postimg.cc/MKTDVYmn/Spawnchangenew.png" width="300px">

_Sintaxa: /spawnchange_
- Comanda va permite sa va schimbati locul de spawn. Aveti de ales intre a va spawna in casa (fie ca este inchiriata sau detinuta) sau in locul implicit de spawn.
  - In cazul jucatorilor care fac parte dintr-o factiune vor avea posibilitatea sa-si selecteze ca punct de spawn HQ-ul factiunii.
  - In cazul jucatorilor fara factiuni (civilii) acestia vor avea ca puncte de spawn cate o locatie din toate cele trei orase (Los Santos, Las Venturas, San Fierro) cat si spawn la casa detinuta sau la care au chirie.

**Nu veti putea folosi aceasta comanda daca sunteti urmariti de politie (cu wanted).**

## /eject

_Sintaxa: /eject [PlayerID/PlayerName]_
- Cu aceasta comanda puteti da jos fortat unul dintre pasagerii din masina pe care o conduceti. Doar soferii o pot folosi.

## /rob

_Sintaxa: /rob_
- [Jefuiti](/other-systems/rob) banca intr-un grup format din 4-8 persoane sau puteti selecta optiunea "Rob Solo" si veti putea jefui o casa/afacere singuri.

## /robhelp

_Sintaxa: /robhelp_
- Ofera informatii legate de [sistemul de jaf](/other-systems/rob).

## /service

_Sintaxa: /service [Taxi/Medic/Mechanic/Lawyer/Towtruck]_
- Trimite o cerere catre un taximetrist, medic, mecanic, lawyer sau towtruck de a se deplasa la voi. In aceasta cerere este specificat locul in care va aflati si poate fi acceptata sau nu de acestia.

## /report

<img src="https://i.postimg.cc/B6sTPbc0/report-Menu.png" width="300px" style="padding: 0px 0px 10px 0px;">  
<img src="https://i.postimg.cc/Wb2XdWpy/report-Other.png" width="300px">

_Sintaxa: /report_
- Comanda trimite o cerere de instiintare catre administratorii serverului. Daca vi se accepta cererea, un admin va va deschide reportul. Puteti sa vorbiti cu acesta prin comanda [/al](/useful-commands/chat#al).
- Maximul de cereri (reporturi) nedeschide in acelasi timp este de 1. Daca niciun admin nu va va inchide sau deschide reportul in 5 minute, acesta se va inchide singur.

**Atentie! Aceasta comanda trebuie folosita doar pentru a semnala probleme grave, jucatori care triseaza sau alte situatii asemanatoare. Folosirea unui limbaj licentios sau cererile fara sens nu vor fi tolerate si va vor aduce sanctiuni.**

## /helpme

_Sintaxa: /helpme [Text]_ **sau** _Sintaxa: /n [Text]_
- Comanda trimite o cerere de ajutor catre helperii serverului. Daca cel putin un helper este la datorie, intrebarea va va fi atribuita acestuia. Puteti primi un raspuns global, insemnand ca intrebarea si raspunsul vor aparea pe chat tuturor jucatorilor cu nivel cuprins intre 1 si 40. Aceasta optiune se poate dezactiva din comanda /tog -> Newbie Chat / Chat Incepatori. De asemenea, helperul va vor putea deschide o conversatie privata putand sa vorbiti cu acesta prin comanda [/hl](/useful-commands/chat#hl). Maximul de cereri de ajutor (helpme-uri) nedeschide in acelasi timp este de 1.

**Atentie! Aceasta comanda trebuie folosita doar pentru a pune intrebari sau pentru ajutor in legatura cu serverul B-Zone RPG. Folosirea unui limbaj licentios sau cererile fara sens nu vor fi tolerate si va vor aduce sanctiuni.**

## /speedlimit

_Sintaxa: /speedlimit [0 sau 90-230]_
- Cu ajutorul acestei comenzi, puteti seta o viteza maxima pentru masina in care va aflati. Aceasta viteza poate varia intre 90 km/h si 230 km/h. Pentru a inlatura aceasta restrictie, folositi "/speedlimit 0".

## /accept

<img src="https://i.postimg.cc/Fz2GDx84/accept.png" width="800px">

_Sintaxa: /accept [Serviciu] [PlayerID/PlayerName]_
- Puteti accepta unul dintre aceste servicii, daca va este oferit de un alt jucator sau de server: droguri (Drugs), reparatii (Repair), Job, interviu (Live), aprovizionarea combustibilului (Refill), amenda (Ticket), ziar (Paper), licente (Licenses), apartenenţa la un grup de evadare (Escape), negot (Trade), Taxi, Medic, avocat (Lawyer), mecanic (Mechanic), iesire din inchisoare (Free), arma (Gun), materiale (Materials), cerere /needlicense (Needlicense; pentru Instructori), Lawyercall, Lesson, Rob, Barbut (Dice), Alliance, Eventhelper, Pubg, Friend, Bunker.

## /cancel

<img src="https://i.postimg.cc/pV70W2T6/cancel.png" width="800px">

_Sintaxa: /cancel [Serviciu]_
- Puteti refuza oricare dintre serviciile de mai sus.

## /usedrugs

_Sintaxa: /usedrugs [Marijuana/Cocaine/Ecstasy/Meth]_
- Aveti posibilitatea de [a folosi drogurile detinute](/other-systems/drugs).

## /fill

_Sintaxa: /fill [procent]_
- Va [umpleti](/business/gas-stations#fill) rezervorul de combustibil cu procentul introdus.

## /fillgascan

_Sintaxa: /fillgascan_
- Va [umpleti](/business/gas-stations#fillgascan) canistra de combustibil.

## /needlicense

_Sintaxa: /needlicenses_
- Comanda trimite o cerere catre toti instructorii serverului, spunand ca aveti nevoie de o licenta. Acestia vor fi instiintati cu privire la nivelul dvs. si limba in care jucati (RO/EN). Daca cererea va este acceptata, instructorul respectiv va avea marcat pe harta locul in care va aflati, iar ceilalti vor vedea cine a acceptat.

## /buyweaplic

<img src="https://i.postimg.cc/PrS3N8fz/sa-mp-259.png" width="600px">
_NPC achizitionare licenta arme_

_Sintaxa: /buyweaplic_
- Prin aceasta comanda aveti posibilitatea sa cumparati **licenta de arme** direct de la un NPC fara a mai fi nevoie sa va o ofere un instructor daca aveti nivel 5+.
  - Exista cate un asemenea NPC la HQ-ul fiecarei factiuni de tip School Instructors cat si un punct info despre pret.
  - Instructorii **nu vor putea** sa isi achizitioneze sau sa isi reinnoiasca licenta de la aceste NPC-uri.
  - Jucatorii cu wanted **vor avea** posibilitatea doar sa isi reinnoiasca licenta.
  - Pentru a va putea lua licenta de la aceste NPC-uri mai intai trebuie sa solicitati un instructor pentru a vedea in prima faza daca este sau nu cineva la datorie pentru a va acorda licenta. Solicitarea va fi anulata automat dupa 5 minute de asteptare dupa care va veti putea lua licenta singuri.
- Pretul de achizitionare a licentei variaza in functie de nivel dupa cum urmeaza:
  - Pentru jucatorii cu nivel cuprins **intre 5 si 9** pretul de achizitie a licentei este de **$5.000**.
  - Pentru jucatorii cu nivel cuprins **intre 10 si 49** pretul de achizitie a licentei este de **$10.000**.
  - Pentru jucatorii cu nivel **50 sau mai mare** pretul de achizitie este de **$20.000**.

**Nota:** Banii platiti pe licenta se vor duce catre server, asadar nimeni nu intra in posesia lor.

## /lawyers

<img src="https://i.postimg.cc/MHy1hW2r/laweyers.png" width="300px">

_Sintaxa: /lawyers_
- Afiseaza o lista cu toti avocatii serverului, impreuna cu numarul de _accept points_ detinute. Puteti sa-i sunati, dand click pe unul dintre ei.

## /animlist

<img src="https://i.postimg.cc/q7cBqvvy/animList.png" width="800px">

_Sintaxa: /animlist_
- Afiseaza o lista cu toate animatiile disponibile pe serverul B-Zone RPG.

## /carradio

<img src="https://i.postimg.cc/RFNvtctm/Radio.png" width="300px">

_Sintaxa: /carradio_ **sau** _Tasta: R_
- Doar soferii pot folosi comanda. Aceasta deschide o casuţa de dialog de unde puteti alege radioul pe care doriti sa-l ascultati.

## /mp3

_Sintaxa: /mp3_
- Echivalentul comenzii "/carradio", cu deosebirea ca poate fi folosita oriunde, pe jos.

**Nota: Necesita un MP3 Player (achizitionabil dintr-un [24/7](/business/247)) si [cont premium](https://www.rpg.b-zone.ro/shop).**

## /throw

_Sintaxa: /throw [Keys/Guns/Drugs/Materials]_
- Folosind aceasta comanda, va puteti arunca pe jos cheile, armele, drogurile sau materialele pe care le aveti la dvs. Un mesaj corespunzator de tip _roleplay_ va aparea pe chat tuturor jucatorilor din apropiere. Comanda nu va putea fi utilizata timp de aproximativ 2 minute daca ati fost somat de un politist.

## /trade

<img src="https://i.postimg.cc/wjVQq54x/800px-Trade-with-Super-Soldier-NOOB.png" width="600px">

- Trimite o invitatie la negot unui alt jucator, folosind sistemul de [trading](/other-systems/trade).

## /givecigarette

- Folosind aceasta comanda, un jucator poate sa-i ofere o tigara unui alt jucator.

_Exemplu: /givecigarette Adi007 ii va oferi jucatorului Adi007 o tigara._

## /tog

<img src="https://i.postimg.cc/HL32W0x4/tog.png" width="300px">

- Folosind aceasta comanda, jucatorii vor putea sa isi activeze sau dezactiveze anumite functii, mesaje sau loguri, acestea fiind impartite pe categorii:

`News, Newbie Chat, Advertisments, Whisper Chat, Show Faction Chat, Clan Chat, Damage 'ding', Show HUD, Show Nametags, Event Chat, Spray Messages, Admin Punishments, Confidential Messages, Neons, Surfing, All vehicle neons`

## /clanleaders

- Aceasta comanda va afisa toti liderii de clan conectati pe server.

## /fps

- Acasta comanda va crea un text in coltul dreapta-sus sau stanga-jos al ecranului, afisand constant FPS-ul.
- Pozitia textului, activarea si dezactivarea acestuia se realizeaza prin tastarea comenzii succesiv.

_Nota: Comanda /fps nu va functiona pentru jucatorii care consuma bauturi (/drink), deoarece in acele cazuri FPS-ul afisat este eronat._

## /cheater

_Sintaxa: /cheater [ID/Jucator] [Cod]_
- Comanda trimite o cerere de instiintare catre administratorii serverului pentru a semnala un posibil jucator codat. Veti primi un mesaj pe chat atunci cand adminul se va ocupa de reportul vostru.

## /referrals

- Aceasta comanda va arata toti jucatorii online care sunt inregistrati pe ID-ul vostru de referal.
- In dialogul care va apare o sa puteti vedea si unele informatii despre acestia.

## /clanHQs

<img src="https://i.postimg.cc/054Cck9p/clanhqs.png" width="300px">

- Aceasta comanda va arata lista cu toate HQ-urile clanurilor de pe server cat si ID-ul acestora pentru a le putea localiza prin comanda **/gps**.

## /safeboxes

- Aceasta comanda va arata lista cu toate [safebox-urile](/other-systems/safebox) pe care le detineti pe cont, impreuna cu amplasarea acestuia pe harta si capacitatea ocupata din capacitatea totala al acestuia.

## /opensafe

- Aceasta comanda va permite sa deschideti [safebox-ul](/other-systems/safebox) pe care l-ati amplasat pe harta pentru a depozita/extrage/arunca arme/droguri/materiale din aceasta.

**Nota: Trebuie sa va aflati langa safebox in momentul in care doriti sa-l deschideti pentru a putea interactiona cu acesta.**

## /clearfp

- Aceasta comanda va permite sa va folositi gratuitatea de tip **ClearFP** prin care va scoateti tot Faction Punish-ul pe care il aveti in acel moment.

**Nota: Comanda poate fi folosita indiferent de cat FP aveti activ pe cont, acesta va fi setat de 0 dupa folosirea gratuitatii.**

## /goldaward

- Aceasta comanda va arata lista cu [cei mai activ 15 jucatori](/other-systems/gold-award) de pe server la orele reale jucate (fara sleep).

## /premiu

- Aceasta comanda va arata tier-ul curent de la [sistemul de cufar](/other-systems/rewards-chest-system) impreuna cu numarul de ore **reale** jucate pe ziua respectiva.

Tot de aici puteti vedea si informatii despre sansele fiecarui premiu pentru un anumit numar de ore jucate pe care il puteti debloca.

## /surrender

- Aceasta comanda va permite sa va predati in Jail daca aveti drept de predare. Trebuie sa asteptati circa 3 minute din moment in care ati folosit comanda, membrii departamentelor vor fi informati iar daca nu vine nimeni la voi sa va aresteze atunci o sa fiti automat arestati de catre server.

**Nota: Daca nu exista niciun membru de departament online pe server la acel moment o sa fiti direct arestati fara sa mai fie nevoie sa asteptati cele 3 minute.**
