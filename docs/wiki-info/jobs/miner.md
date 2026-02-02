---
icon: material/pickaxe
---

# Miner

<figure markdown="span">
  ![Locatie job](/images/wiki/general/Miner_map.png){ width="450" }
  <figcaption>Locatia punctului de angajare</figcaption>
</figure>

<figure markdown="span">
  ![Jucator la munca](/images/wiki/general/1miner.jpg){ width="500" }
  <figcaption>Jucator muncind ca miner</figcaption>
</figure>

## Caracteristici Generale

* Cu ajutorul jobului *Miner* veti aduna si livra minereuri in schimbul unei sume de bani.
* Jobul Miner este unul legal.
* Pentru a deveni un miner, aveti nevoie de minim nivel 1.
* Pentru acest job, veti folosi vehiculul Bobcat la skill 1-6 si vehiculul Yosemite pentru skill 6-10.
* Locatia punctului de angajare poate fi gasita pe harta in imaginea #1.
* Pentru o singura livrare (livrarea se face la punctul de angajare) trebuie sa adunati un total de 5 minereuri.
* Jucatorii care detin cont premium primesc cu 50% mai mult la sfarsitul fiecarei curse.
* Veti pierde misiunea daca parasiti vehiculul si nu reveniti in acesta in 20 de secunde (exceptie atunci cand adunati minereurile).
* Pentru fiecare avansare in skill, veti primi 10 Gold.

## Avansare in Skill

* Skill 1 **>>** Skill 2: 30 de curse. (30 total)
* Skill 2 **>>** Skill 3: 60 de curse. (90 total)
* Skill 3 **>>** Skill 4: 120 de curse. (210 total)
* Skill 4 **>>** Skill 5: 240 de curse. (450 total)
* Skill 5 **>>** Skill 6: 200 de curse. (650 total)
* *Se deblocheaza un nou vehicul: Yosemite*
* Skill 6 **>>** Skill 7: 250 de curse. (900 total)
* Skill 7 **>>** Skill 8: 300 de curse. (1200 total)
* Skill 8 **>>** Skill 9: 350 de curse. (1550 total)
* Skill 9 **>>** Skill 10: 350 de curse. (1900 total)

## Formula de calcul pentru castiguri

### Skill 1
[(743 + random(115)) * coeficient_premium] + job_bonus

### Skill 2
[(759 + random(115)) * coeficient_premium] + job_bonus

### Skill 3
[(820 + random(115)) * coeficient_premium] + job_bonus

### Skill 4
[(924 + random(115)) * coeficient_premium] + job_bonus

### Skill 5
[(1088 + random(115)) * coeficient_premium] + job_bonus

### Skill 6
[(1111 + random(115)) * coeficient_premium] + job_bonus

### Skill 7
[(1178 + random(115)) * coeficient_premium] + job_bonus

### Skill 8
[(1273 + random(115)) * coeficient_premium] + job_bonus

### Skill 9
[(1330 + random(115)) * coeficient_premium] + job_bonus

### Skill 10
[(1406 + random(115)) * coeficient_premium] + job_bonus

**Nota:** Timpul mediu necesar pentru efectuarea unei livrari de minereuri, este de 230 secunde.

* ***coeficient_premium*** are valoarea 1 daca nu detineti cont premium, sau valoarea 1,5 daca detineti cont premium.
* ***random(115)*** reprezinta un numar aleatoriu de la 1 la 115.
* ***job_bonus*** reprezinta un numar multiplu de 5. Cand folositi comanda /work, ***job_bonus*** are valoarea 5. De fiecare data cand terminati cu succes o cursa, valoarea se mareste cu 5. Daca parasiti vehiculul jobului, valoarea se reseteaza la 5. Valoarea ***job_bonus*** va creste din 5 in 5 pana la maxim 50.

**Nota:** La castig se mai poate adauga bonusul de job (/stats) si bonusul pentru jobul zilei.

## Vehicule in functie de skill

### Bobcat

<figure markdown="span">
  ![Bobcat](/images/wiki/vehicles/422.png){ width="250" }
  <figcaption>Bobcat</figcaption>
</figure>

- **Pret DealerShip:** $7.500
- **Returnare DealerShip:** $4.500
- **Viteza maxima:** 140 KM/h
- **Provenit din:** GMC
- **Numar de locuri:** 2
- **Skillul necesar:** 1, 2, 3, 4, 5
- **Tunabil:** TransFender

### Yosemite

<figure markdown="span">
  ![Yosemite](/images/wiki/vehicles/554.png){ width="250" }
  <figcaption>Yosemite</figcaption>
</figure>

- **Pret DealerShip:** $172.500
- **Returnare DealerShip:** $103.500
- **Viteza maxima:** 144 KM/h
- **Provenit din:** Chevrolet Silverado 1998
- **Numar de locuri:** 2
- **Skillul necesar:** 6, 7, 8, 9, 10
- **Tunabil:** TransFender

## Comenzi Specifice

### /work

Aceasta comanda va permite sa incepeti lucrul.

Este necesar sa va aflati in apropierea locului de angajare pentru a executa comanda. Daca acesta nu este cazul, serverul va va pune un checkpoint pe harta, marcand locul in care trebuie sa mergeti.
