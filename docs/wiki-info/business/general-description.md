---
icon: material/store
---

# Descriere Generala - Bizuri

<figure markdown="span">
  ![#1 Gun Shop Los Santos](/images/wiki/general/Gsls.png){ width="650" }
  <figcaption>Gun Shop Los Santos</figcaption>
</figure>

<figure markdown="span">
  ![#2 Text informativ](/images/wiki/general/Shareholders.png){ width="300" }
  <figcaption>Text informativ</figcaption>
</figure>

<figure markdown="span">
  ![#3 Informatii pentru jucatori despre biz-ul respectiv](/images/wiki/businesses/biz_status.png){ width="700" }
  <figcaption>#3 Informatii pentru jucatori despre biz-ul respectiv</figcaption>
</figure>

Bizurile sunt locatii specifice vietii de zi cu zi, precum FastFood-urile sau magazinele de haine. Pe serverul B-Zone RPG acestea sunt cladiri pe care orice jucator poate sa le cumpere daca detine o anumita suma de bani ceruta si un anumit nivel stabilit pentru bizul respectiv.

Bizurile au si ele o anumita productie de bani precum casele, astfel, de fiecare data cand un jucator intra intr-un biz, acestuia ii va fi sustrasa o suma de bani, numita taxa de intrare. 

<p>Orice jucator ce detine cel putin nivel 9, poate sa-si achizitioneze un biz.</p>
- Fiecare biz dispune de un text informativ plasat langa usa de intrare. Privind textul informativ veti afla urmatoarele aspecte cu privire la bizul respectiv:
    - ID-ul bizului, situat pe primul rand al paragrafului.
    - Numele informativ al bizului.
    - Numele proprietarilor bizului (puteti vedea proprietarii folosind /shareholders).
    - Nivelul de care aveti nevoie pentru a putea cumpara bizul respectiv.
    - Taxa de intrare.

Bizurile de nivel 20 sau mai mare sunt comisionate in functie de nivelul avut si importanta bizului, unele avand multiple tipuri de comisioane.<br>
Comisionul este calculat in mod complex si automat de catre server, tinandu-se cont de mai multi factori specifici.

Afacerile vor distribui la PayDay banii colectati cand suma din seif ajunge la minim **$1.000**, acționarii primind 10% din sumă per actiune.

## Sistemul de actiuni

<figure markdown="span">
  ![#4 Informatii pentru proprietarii de actiuni la un biz](/images/wiki/businesses/biz_info.png){ width="800" }
  <figcaption>#4 Informatii pentru proprietarii de actiuni la un biz</figcaption>
</figure>
Sistemul de actiuni este un sistem bazat pe cumpararea, respectiv vanzarea de actiuni la un anumit biz. Puteti detine dintr-un biz minim 10% din profit si un maxim de 100%, puteti detine de asemenea actiuni la mai multe bizuri deodata. Spre exemplu, puteti detine 10% din CNN LS, 20% din Pizza Idlewood, 40% din Clothes Store LS, pana atingeti maximul de 100% pe care-l puteti detine. In functie de procentul pe care-l detineti dintr-un anumit biz veti primi si partea voastra de profit, un exemplu simplu este daca detineti 10% din CNN LS si acesta produce $1.000.000 zilnic, veti castiga $100.000 in acea zi detinand 10% din biz.

Puteti vinde actiunile unui biz altui jucator folosind comanda [/trade], pentru a vinde actiunile la stat pe 0$ puteti folosi comanda [/sellshares].

## Tipuri de bizuri

- Benzinarii
- 24/7
- FastFood-uri
- Magazine de haine
- Magazine de arme
- Cluburi & Baruri
- Restaurante
- PnS-uri
- Tuninguri
- Arene
- CNN
- Rent
- Magazine de arme albe
- Sex Shops
- Poker Casino
- Car Insurance
- PUBG Arena
- CarColor
- Alte biz-uri

## Comenzi Specifice
### /bizinfo
Cu ajutorul acestei comenzi puteti verifica ca detinatori de actiuni informatii despre productia actiunilor pe care le detineti. (*Vezi imaginea #4*).

### /bizstatus
Cu ajutorul acestei comenzi puteti verifica venitul actual din intreg biz-ul respectiv. (*Vezi imaginea #3*)

<figure markdown="span">
  ![#5 Interfata pentru extragerea banilor din seif in functie de actiunile detinute](/images/wiki/businesses/biz_withdraw.png){ width="600" }
  <figcaption>#5 Interfata pentru extragerea banilor din seif in functie de actiunile detinute</figcaption>
</figure>
### /bizwithdraw
Cu ajutorul acestei comenzi puteti extrage banii din actiunile pe care le detineti la biz-ul respectiv.<br>
Pentru a putea face acest lucru trebuie sa mergeti la fiecare biz unde detineti actiuni si sa folositi comanda pentru a putea extrage banii. (*Vezi imaginea #5*).

### /sellshare
Cu ajutorul acestei comenzi va puteti vinde un anumit numar de actiuni catre stat.<br>
<span style="color: #ff0000; font-weight: bold; letter-spacing: 1px;">ATENTIE!</span> Banii de la stat nu va revin voua, practic nu primiti nimic in schimb.