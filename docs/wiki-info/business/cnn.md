# CNN

<figure markdown="span">
  ![Harta CNN-urilor](/images/wiki/general/CNNs_mapp.png){ width="450" }
  <figcaption>Harta CNN-urilor</figcaption>
</figure>

<figure markdown="span">
  ![CNN Los Santos](/images/wiki/general/CNNLS_PLACE.jpg){ width="450" }
  <figcaption>CNN Los Santos</figcaption>
</figure>

<figure markdown="span">
  ![#1](/images/wiki/general/ICON_CNN_MAP.jpg){ width="100" }
  <figcaption>#1</figcaption>
</figure>

CNN (Cable News Network) reprezinta singura agentie de publicitate pe serverul B-Zone RPG. Din cele trei locatii ale acesteia, jucatorii pot scrie si trimite anunturi publicitare tuturor celorlalti jucatori conectati (cu exceptia celor care au dezactivat aceasta functie prin comanda /tog -> Anunturi).

Pentru a plasa anunturi aveti nevoie de minim nivel 3.

## Caracteristici

- Exista cate o cladire CNN in fiecare oras: Los Santos, Las Venturas si San Fierro.
- Acestea sunt marcate pe harta cu o iconita ca in imaginea #1.
- Pretul (fee) este valabil doar in acea locatie a CNN-ului si nu tine cont de numarul de caractere folosite.
- Numarul maxim de caractere care pot incapea intr-un anunt este de 124.
- Anunturile se vor publica in ordinea sosirii, iar durata de asteptare poate varia in functie de numarul acestora.
- Administratorii pot sterge anunturile inadecvate inainte ca acestea sa fie publicate.
- Locatiile CNN reprezinta SafeZone-uri.
- Publicarea unor anunturi jignitoare, vulgare, sau care nu respecta regulamentul serverului RPG este sanctionabila conform acestuia.

## Structura unui anunt publicitar

### Pe un singur rand

Atunci cand numarul de caractere din anunt nu depaseste 50.

**Exemplu:** Anunt publicat de Madalin (456): Cumpar BMX, Tampa, NRG-500 si Infernus.

### Pe doua randuri

Atunci cand numarul de caractere din anunt depaseste 50 (separatia se face in mod automat de catre server).

**Exemplu:**

- Linia 1: Anunt publicat de Kelton (128): Vand Monster B, Sparrow, stuntplane din wheel. Va ...
- Linia 2: ... nd casa 336 ieftin, Vand 6medkit, 2addict kit, vand biz 82...

## Comenzi specifice

### /ad

Cu aceasta comanda puteti scrie si publica un anunt. Textul trebuie sa aiba maxim 124 de caractere. Dupa executare, serverul va va afisa o previzualizare a anuntului si numarul de secunde pana la publicare.

Comanda este executata cu succes numai daca va aflati intr-o locatie CNN.

*Sintaxa: /ad [Anunt]*

### /ads

Aceasta comanda afiseaza o previzualizare tuturor anunturilor care sunt plasate pe server inainte de a aparea pe chatul global.

*Sintaxa: /ads*

### /cancel ad

Comanda va anuleaza anuntul, daca este nepublicat, in asteptare. Nu vi se vor inapoia banii.

Comanda este executata cu succes numai daca aveti un anunt nepublicat in asteptare.

*Sintaxa: /cancel ad*

### /myad

Aceasta comanda afiseaza o previzualizare a anuntului si numarul maxim de secunde pana la publicare.

Comanda este executata cu succes numai daca aveti un anunt in asteptare.

*Sintaxa: /myad*
