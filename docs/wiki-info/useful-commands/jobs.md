# Joburi

Pentru a putea lucra la unul dintre joburile disponibile pe servere, trebuie sa cunoasteti comenzile disponibile pentru acestea.

## /jobs

Aceasta comanda deschide o lista a tuturor joburilor. Lista cuprinde urmatoarele detalii despre fiecare job in parte:
- Numele jobului
- Orasul din care face parte
- Tipul jobului (legal/ilegal)
- Nivelul minim necesar angajarii la respectivul job

_Nota: Pentru a va ajuta imaginatia, puteti gasi o astfel de lista la imaginea #1._

<figure markdown="span">
  ![Jobs List](/images/wiki/general/Jobs_list.png){ width="400" }
  <figcaption>Lista Joburi</figcaption>
</figure>

## /jobhelp

Comanda afiseaza lista tuturor comenzilor disponibile in cadrul unui job.

_Exemplu: Avand jobul Farmer serverul va afisa comanda /work._

## /getjob

Cu ajutorul acestei comenzi orice jucator poate sa se angajeze, daca indeplineste urmatoarele conditii:
- Sa aiba nivelul minim necesar angajarii (vezi nivelul necesar tastand comanda /jobs).
- Sa se afle destul de aproape de marcajul special (i - vezi imaginea #2).

<figure markdown="span">
  ![Marcaj Job](/images/wiki/general/I_job.jpg){ width="250" }
  <figcaption>Marcaj Job</figcaption>
</figure>

## /work

Aceasta comanda este una dintre cele mai folosite comenzi in privinta joburilor. Cu ajutorul acestei comenzi un jucator poate sa-si inceapa munca. Comanda /work functioneaza pentru toate joburile, mai putin Detectiv, Mecanic Auto si Avocat.

## /skills

<img src="https://i.postimg.cc/BQCdDZ5Q/Skills-list.png" width="300px">
_#3 Lista skilluri_

Comanda /skills este una generala, jucatorii putand sa o acceseze chiar daca nu sunt angajati la vreun job. Prin tastarea comenzii, serverul va va afisa un dialog ce cuprinde informatii despre skillul detinut al fiecarui job.

_Nota: Pentru a va ajuta imaginatia, puteti gasi o astfel de lista la imaginea #3._

## /switchjob

Anumite factiuni permit detinerea unui job auxiliar specific acelei factiuni cat si un job normal la alegerea jucatorului, astfel ca membrii acestor factiuni pot detine simultan doua joburi si pot face schimbul intre acestea folosind aceasta comanda.

- Membrii departamentelor si membrii Hitmen Agency au ca job auxiliar jobul Detectiv.
- Membrii din ganguri au ca job auxiliar jobul Distribuitor de Arme.
- Membrii din TTC, Paramedics, News Reporters, Taxi LS/LV/SF, School Instructors LS/LV/SF au ca job auxiliar jobul Mecanic.

## /jobskillup

Comanda /jobskillup este una generala, ea poate fi folosita pentru a va creste skillul curent la anumite joburi.

- Trebuie sa aveti gratuitati de tip **JobSkill**.
- Jobul la care doriti sa va cresteti skill-ul trebuie sa aibe sistem de skill.
- Nu trebuie sa aveti deja skillul maxim la jobul la care doriti sa vi-l cresteti.
