---
icon: material/car
---

# Vehicule

<figure markdown="span">
  ![Imagine Vehicul](/images/wiki/general/bullet.jpg){ width="400" }
  <figcaption>Imagine Vehicul</figcaption>
</figure>

Oricine doreste sa aiba o masina personala frumoasa, perfect functionala si rapida, insa in aceeasi masura trebuie sa si cunoasteti cum va puteti controla propriile vehicule. Mai jos gasiti o lista cu toate comenzile pe care le puteti aplica unui vehicul:

## /vehicles

<figure markdown="span">
  ![Imagine Garaj](/images/wiki/general/veh_garage.jpg){ width="400" }
  <figcaption>Imagine Garaj</figcaption>
</figure>

<figure markdown="span">
  ![Optiuni Vehicul](/images/wiki/general/garage_options.png){ width="400" }
  <figcaption>Optiuni Vehicul</figcaption>
</figure>

Aceasta comanda reprezinta centrul de control al tuturor vehiculelor personale ale unui jucator. Comanda /vehicles are si alternative de accesare a centrului de control precum comenzile: **/v**, **/garage** si **/g**. Toate aceste comenzi va conduc intr-un singur loc, centrul de control.

In urma folosirii uneia dintre aceste comenzi, serverul va va afisa o lista a tuturor vehiculelor detinute folosind urmatorul model:

- ID-ul slotului ocupat de vehicul
- Numele vehiculului
- Statusul acestuia (disponibil, ocupat, ascuns)
- Dupa cat timp vehicului urmeaza sa fie despawnat.

Datorita limitarilor serverelor de SA:MP, jucatorii cu cont premium pot spawna pana la 8 vehicule in acelasi timp pe server, iar cei fara cont premium pot spawna pana la 2 vehicule in acelasi timp pe server.

Prin selectarea unui vehicul din lista serverul va pune la dispozitie cateva optiuni cu ajutorul carora va puteti controla vehiculul.

**Optiuni de control:**

- **Informatii** - Iti vor fi afisate informatii precum: model, pret, status (incuiat/descuiat), culori, kilometrii, zilele masinii, asigurari, cost asigurare, id, vip.
- **Localizeaza** - Iti va fi setat un checkpoint la pozitia vehiculului.
- **Remorcheaza** - Vehiculul tau va fi respawnat la locul unde a fost parcat. Pretul acestui serviciu este de $200.
- **Spawnează/Despawnează** - Cu aceasta optiune poti face ca vehiculul tau sa apara/dispara temporar de pe server.
- **Deblochează** - Aceasta optiune poate fi folositoare in momentul in care vehiculul tau a fost parcat necorespunzator si nu mai poate fi folosit (exemplu: intr-un perete, in apa). 
    - Vehiculul va fi parcat intr-o locatie sigura. Foloseste apoi serviciul de localizare pentru a-ti gasi vehiculul.
- **Convert to VIP Vehicle** - Prin aceasta optiune veti putea sa va convertiti vehiculul la VIP. Mai multe detalii [aici](../shop/vip-car-en.md).
- **Edit VIP Text** - Prin aceasta optiune poti edita text-ul VIP de pe vehiculul tau.
    - *<b>Nota</b>* - Aceasta optiune se va afisa doar daca vehiculul este upgradat la VIP.
- **Edit color for VIP Text** - Prin aceasta optiune poti edita culoarea text-ului VIP de pe vehiculul tau.
    - *<b>Nota</b>* - Aceasta optiune se va afisa doar daca vehiculul este upgradat la VIP.
- **Edit position for VIP Text** - Prin aceasta optiune poti edita pozitia (locatia) text-ului VIP de pe vehiculul tau.
    - *<b>Nota</b>* - Aceasta optiune se va afisa doar daca vehiculul este upgradat la VIP.
- **Add 30 Days to the vehicle's age** - Prin aceasta optiune veti putea sa va cumparati **30 de zile** in plus la zilele vehicului tau selectat pentru **400 Gold**.
- **Add 180 Days to the vehicle's age** - Prin aceasta optiune veti putea sa va cumparati **180 de zile** in plus la zilele vehicului tau selectat pentru **2000 Gold**.
- **Add 365 Days to the vehicle's age** - Prin aceasta optiune veti putea sa va cumparati **365 de zile** in plus la zilele vehicului tau selectat pentru **4000 Gold**.
- **Add 3D Label** - Prin aceasta optiune veti putea sa va cumparati **30 de zile** in plus la zilele vehicului tau selectat pentru **400 Gold**. Mai multe detalii [aici](../shop/vehicle-3d-text-en.md)
- **Add Vehicle to favorites** - Prin aceasta optiune veti putea sa adaugati vehiculul selectat in lista de vehicule favorite pentru a fi mai usor de gasit si de indentificat (utila pentru jucatorii cu foarte multe vehicule in garaj).
- **Remove Vehicle from favorites** - Prin aceasta optiune veti putea sa eliminati vehiculul selectat din lista de vehicule favorite.
- **Change Vehicle Plate** - Prin aceasta optiune va veti putea schimba numarul/placuta de inmatriculare a vehicului selectat cu altul ales de voi.
    - *<b>Nota:* alegerea unui text vulgar/indencent duce la sanctionarea voastra de catre admini conform regulamentului RPG.</b>
- **Change Vehicle Color** - Prin aceasta optiune daca aveti **minim skill 6 la jobul Car Mechanic** veti putea sa va schimbati culoarea permanenta a vehiculului fara sa fie necesar sa mergeti la Car Color. Veti putea schimba atat culorile Hidden cat si cele Non Hidden, preturile vor fi identice ca-n Car Color. Banii platiti de catre jucatori vor fi redirectionati in biz.
- **Tune The Vehicle** - Prin aceasta optiune daca aveti **minim skill 7 la jobul Car Mechanic** veti putea sa va tunati vehiculul fara sa fie necesar sa mergeti la un biz de Tuning. Banii platiti de catre jucatori vor fi redirectionati catre cel mai apropiat business de tip Tuning de acestia la momentul cumpararii componentelor.
    - Nu toate componentele vor fi disponibile la skill 7, ele se vor debloca treptat in avansarea in skill.
    - Se aplica o reducere pentru componentele vehiculelor dupa cum urmeaza:
        - **Skill 7:** Front Bumper, Rear Bumper, Sideskirts, Hydraulics - **Reducere 5%**.
        - **Skill 8:** Roof, Front Bullbar, Hood, Lamps, Vents - **Reducere 10%**.
        - **Skill 9:** Spoiler, Wheels, Exhaust - **Reducere 15%**.
        - **Skill 10:** NOS, Paintjob, Neons - **Reducere 20%**.
- **Vinde** - Prin aceasta optiune poti vinde vehiculul la DealerShip, doar daca te afli in jurul acestuia.
- **Spawnare la conectare** - Prin aceasta optiune poti selecta care sa fie vehiculele care se vor spawna automat la conectarea pe server.
- **Cumpara asigurare** - Prin aceasta optiune puteti cumpara asigurare la vehicul.
- **Adauga in Bazar** - Prin aceasta optiune iti poti adauga vehiculul in Bazarul Auto pentru vanzare. Mai multe detalii [aici](../other-systems/car-market-en.md)

In mod standard, un jucator are 4 sloturi de vehicule, acestea putand fi suplementate din [Shop](https://www.rpg.b-zone.ro/shop/shopProducts).

## /engine
Utilizarea acestei comenzi in momentul in care va aflati intr-un vehicul are ca efect pornirea, sau dupa caz, oprirea motorului vehiculului. Ca o scurtatura a comenzii, puteti sa folositi deasemenea tasta **2** de pe tastatura.

## /lock
Comanda este folosita de catre proprietarii vehiculelor pentru a-si incuia respectiv descuia propriul vehicul. Ca o scurtatura a comenzii, se poate utiliza tasta **N**. Comanda poate fi folosita doar din apropierea vehiculului.

## /park
Aceasta comanda va fixa pozitia in care vehiculul va fi spawnat la conectarea pe server sau cand acesta va exploda, se va scufunda sau cand va fi folosit serviciul de tractare(tow). Comanda poate fi folosita doar daca va aflati la volanul vehiculului vostru.

## /vehswitch
Prin tastarea acestei comenzi, vei putea schimba vehiculul pe care il conduci in momentul de fata, cu un alt vehicul care nu este spawnat.

## /carcolor
Un jucator poate utiliza aceasta comanda numai daca se afla intr-un vehicul personal si langa bizul CarColor. In urma tastarii comenzii, jucatorul urmeaza sa fie teleportat cu tot cu vehicul in interiorul unui garaj de unde poate sa foloseasca meniul pus la dispozitie pentru a-si selecta culorile dorite. In cazul in care un jucator nu se afla langa acest biz, ii va fi setat un checkpoint.

## /buyinsurance
Prin tastarea comenzii, proprietarul vehiculului va cumpara o asigurare pentru vehiculul in care se afla. Un vehicul poate dispune de maxim 5 asigurari. Un vehicul ramas fara asigurari nu mai poate fi condus de nimeni pana ce proprietarul acestuia nu va plati reparatiile necesare.

## /buyvehicle
Functioneaza numai daca va aflati langa una dintre cele doua usi ale dealershipului. Odata tastata comanda, serverul va va teleporta intr-un garaj de unde puteti selecta vehiculul dorit folosind meniul pus la dispozitie. De asemenea serverul va pune la dispozitie informatii precum pretul si viteza vehiculului, va permite sa-i schimbati culorile si cel mai important, sa efectuati un test drive.

## /givekey
Pentru a oferi cuiva cheile propriului vehicul, se foloseste comanda /givekey. Comanda utilizeaza un singur parametru, numele sau ID-ul jucatorului caruia doriti sa-i imprumutati cheile vehiculului vostru.

*Exemplu: /givekey 135*

Dupa oferirea cheilor, cel care a intrat in posesia acestora va putea sa foloseasca comanda /lock asupra vehiculului. Aceasta comanda poate sa fie folosita doar in apropierea vehiculului.

## /changelock
Comanda are ca efect schimbarea incuietorii vehiculului personal pentru ca jucatorii carora le-ati oferit cheile acestuia, sa nu mai poata sa descuie, respectiv sa incuie vehiculul.

## /throw
Aceasta comanda se utilizeaza pentru a arunca anumite obiecte aflate in posesia ta, inclusiv cheile unui vehicul primite din partea unui alt jucator, fie prin inchirierea unui vehicul de la bizurile special amenajate (exemplu: Bike rent). Dupa utilizarea acestei comenzi, nu veti mai dispune de un vehicul inchiriat.

## /swapcolors
Serverele va pun la dispozitie doua seturi de culori pentru vehiculele voastre, primul set fiind cel primar, iar cel de-al doilea secundar. Prin utilizarea comenzii /swapcolors, se vor inversa culorile vehiculului intre ele, ceea ce inseamna ca cea primara va deveni secundara si cea secundara va deveni primara.

## /v -> Sell
Pentru a putea vinde un vehicul la Dealership trebuie sa va aflati in apropierea acestuia cu masina pe care doriti sa o vindeti. Din meniul /v veti selecta vehiculul dorit iar apoi veti alege optiunea de **Sell**

*Nota: Pentru a putea vinde masina de tutorial la Dealership aveti nevoie de minim nivel 5.*

## /lights
Prin aceasta comanda se vor putea aprinde farurile vehiculelor fara a activa sistemul NOS in cazul in care acesta este instalat.
