# Banca

Serverul B-Zone RPG dispune de 3 banci, cate una in fiecare oras (Las Venturas, Los Santos, San Fierro). Urmatoarele comenzi pot fi utilizate in oricare dintre cele 3 banci (exceptand comanda numarul 5, aceea putand sa fie folosita doar langa un bancomat):

<img src="https://i.postimg.cc/YSfpSgp5/LSBank.jpg" width="300px">  
_Banca din Los Santos_

<img src="https://i.postimg.cc/hGVCRQ5Z/LVBank.jpg" width="300px">  
_Banca din Las Venturas_

<img src="https://i.postimg.cc/fLZpTJWt/SFBank.jpg" width="300px">  
_Banca din San Fierro_

<img src="https://i.postimg.cc/QMnGYT7j/Atm.png" width="300px">  
_#1 Interfata ATM_

## /balance

In urma folosirii acestei comenzi, banca iti va afisa suma de bani pe care o detii in banca in momentul respectiv.  
Puteti sa folositi comanda numai daca va aflati intr-una dintre cele 3 banci.

## /withdraw

Cu ajutorul comenzii poti sustrage bani din propriul cont bancar.  
Sintaxa pe care trebuie s-o completati pentru a functiona cu succes comanda, este urmatoarea: /withdraw <suma de bani>  
Puteti sa folositi comanda numai daca va aflati intr-una dintre cele 3 banci.

_Exemplu: /withdraw 5000_  
_Efect: Prin folosirea exemplului, vei primi $5.000 in mana, bani ce sunt sustrasi din contul tau bancar._

## /deposit

Cu ajutorul comenzii poti adauga bani in propriul cont bancar.  
Sintaxa pe care trebuie s-o completati pentru a functiona cu succes comanda, este urmatoarea: /deposit <suma de bani>  
Puteti sa folositi comanda numai daca va aflati intr-una dintre cele 3 banci.

_Exemplu: /deposit 5000_  
_Efect: Iti va sustrage $5.000 din banii pe care ii ai cu tine si ii va depune la banca._

## /transfer

Cu ajutorul comenzii poti transfera bani din contul tau bancar, in contul bancar al altui jucator.  
Sintaxa pe care trebuie s-o completati pentru a functiona cu succes comanda, este urmatoarea: /transfer <ID sau nume player> <suma de bani>  
Puteti sa folositi comanda numai daca va aflati intr-una dintre cele 3 banci, exceptie facand organizatorii de evenimente.

_Exemplu: Presupunand un jucator online, cu numele "Adi007" si avand ID-ul 13:_  
_/transfer 13 5000 sau /transfer Adi007 5000_  
_Efect: Iti va sustrage $5.000 din banii pe care ii ai in contul tau bancar si ii va depozita in contul bancar al jucatorului Adi007._

_Nota: Pentru a transfera bani, ai nevoie de minim level 3._  
_Nota: Taxa perceputa la transfer este de 1%, poate fi calculata cu formula: **1/100 * suma_transferata**_

## /atmwithdraw | /atm

Prin folosirea comenzii [/atmwithdraw] sau [/atm] in fata unui ATM poti sustrage bani din contul tau bancar, in mana.  
De obicei, ajunsi in fata unui ATM o sa vi se deschida o interfata primitoare (imaginea #1), urmand de acolo sa selectati suma de bani dorita. Totusi, daca inchideti din greseala interfata, se poate folosi una dintre cele 2 comenzi mentionate mai sus pentru a o redeschide.  
Puteti sa folositi comanda numai daca va aflati langa un ATM (bancomat).

_Nota: Daca doriti sa gasiti un ATM puteti sa va folositi de comanda /gps, mai multe detalii puteti gasi [aici](/useful-commands/locations)._
