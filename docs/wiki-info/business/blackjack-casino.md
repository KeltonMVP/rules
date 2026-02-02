---
icon: material/cards-playing
---

# Blackjack Casino

<figure markdown="span">
  ![Blackjack Casino](/images/wiki/general/blackjack_casino.png){ width="450" }
  <figcaption>Blackjack Casino</figcaption>
</figure>

<figure markdown="span">
  ![Masa de blackjack](/images/wiki/general/blackjack_table.png){ width="450" }
  <figcaption>Masa de blackjack</figcaption>
</figure>

Pentru jucatorii cu adictie in jocuri de noroc, serverele B-Zone va pun la dispozitie un sistem de Blackjack in biz-ul Caligulas Casino din Las Venturas.

Mesele de blackjack sunt situate in capatul interiorului, in numar de 12.

## Caracteristici

- Puteti juca blackjack daca aveti minim nivel 3.
- Pot exista cel mult 7 jucatori simultan la o singura masa.
- Jocul va incepe doar cand exista minim 2 jucatori la o masa.
- Pentru a putea intra la o masa aveti nevoie de minim level 3 si de suma minima pentru intrare, care este afisata la fiecare masa.
- Exista un total de 12 mese, fiecare cu suma sa minima pentru intrare.
- Din pot-ul castigat la finalul unei runde, 95% din bani ii va primi jucatorul sau jucatorii castigatori, 4.9% din bani vor fi stersi de pe server iar 0.1% din bani vor intra in seiful bizului.
- Se vor acumula ore jucate reale in timpul jocului de blackjack.
- Jucatorii care nu aleg nicio optiune timp de 60 de secunde vor fi scosi de la masa pentru AFK.
- Acest biz detine interior.
- Parasirea mesei se poate face si prin butonul de LEAVE.

## Reguli generale de blackjack

- Jucatorii nu vor trebui sa invinga dealerul cum e in mod obisnuit, ci sa invinga toti jucatorii de la masa respectiva pentru a lua premiul.
- Sa atingeti un scor cat mai apropiat de 21 cu cartile pe care le aveti in mana FARA sa depasiti 21.
- In momentul depasisii scorului 21, ati facut BUST si veti pierde runda de joc.
- Cartile sunt amestecate aleatoriu.
- Cartile 2, 3, 4, ..., 10 ofera scorul scris pe carte.
- Cartile J, Q, K ofera scorul de 10.
- Cartea As va oferi ori un scor de 1, ori un scor de 11 in mod automat in functie de cum e mai benefic pentru jucator.
- La inceperea jocului se verifica daca exista un jucator care nu are suficienti bani incat sa mai continue sa joace; daca exista, acesta va fi scos. Daca dupa scoaterea acestuia nu exista cel putin doi jucatori care pot continua jocul, acesta nu va mai porni.
- Jocul va incepe cu primul jucator de la masa; jucatorii sunt ordonati de la stanga la dreapta la masa; o sageata rosie va aparea deasupra numelui jucatorului la care ii este randul.
- Jucatorii nu isi pot vedea cartile si scorurile unul altuia, exceptie fiind momentul in care un jucator face BUST (depaseste scorul de 21). Atunci cartile lui vor fi aratate tuturor jucatorilor, incluzand scorul sau.
- Pentru a simplifica jocul nu exista mecanica de SPLIT, cum exista intr-un joc de blackjack clasic.

## Decizii de joc

Jocul va consta in 2 decizii simple pe care va trebui sa le ia jucatorul:

### HIT

Va fi folosit in momentul in care jucatorul doreste sa primeasca inca o carte din pachet.

### STAND

Va fi folosit in momentul in care jucatorul nu mai doreste sa primeasca carti; jucatorul nu va mai putea cere carti in runda aceea daca a apasat STAND.

Pentru a da STAND va trebui sa aveti un scor al cartilor de minim 12.

Daca un jucator nu apasa pe nicio optiune timp de 30 de secunde, se va da STAND automat. Exceptie atunci cand scorul este sub 12, daca este sub 12, serverul va da automat HIT, iar dupa aceea va da STAND, cu conditia ca scorul sa nu fi depasit 21.

## Determinarea castigatorului

Castigatorul va fi calculat in momentul in care nu a mai ramas niciun jucator eligibil pentru a primi carti (toti au luat ori BUST, ori au dat STAND, ori a ramas un singur jucator care nu a facut BUST dintre toti jucatorii).

## Comenzi specifice

### /blackjack

Prin intermediul acestei comenzi veti putea intra sau iesi de la masa de blackjack.

Comanda este executata cu succes numai daca va aflati in interiorul bizului Caligulas Casino, langa una dintre mesele de blackjack.

*Sintaxa: /blackjack*
