---
icon: material/handcuffs
---

# Jail

<figure markdown="span">
  ![jailer](/images/wiki/general/Female_jail.png){ width="450" }
  <figcaption>jailer</figcaption>
</figure>

Players who violate the social rules of RPG servers and do not comply with justice orders are automatically incarcerated. A player's punishment varies depending on the severity of the offense committed.


## General characteristics

* There are two types of jail sentences:
    * jail sentence given by server police officers due to rule violations and accumulation of wanted (pursuit level).
    * jail sentence given by server administrators, due to successive violations of certain rules.
* Inmates are largely supervised by jail representatives (National Guard faction members).
* An inmate cannot leave the jail.
* An inmate has the right to ask a guard to release them from the cell to be able to reach the bar.
* In the jail yard, inmates can try to escape. More information can be found on the Escape page.
* The time a player must spend in jail is saved even after leaving the server.
* If inmates are violent with other cellmates, they receive punishments from guards (/punish, inability to move for a certain number of seconds).
* If an inmate has been imjailed by an administrator (AJail), they cannot be released on bail (/bail) nor by a lawyer.
* All jail cells will open every hour on the hour and close 10 minutes later, and every half hour and close 10 minutes later. During all this time inmates have the right to go out into the jail yard. Cells only open between 08:00 - 02:00.
* After the cells close, National Guard members have the right to send inmates still outside back to their cells.
* Players in jail will receive 2 additional minutes to their current sentence each time they kill another jailer.
* A jailer can be released from jail by a lawyer based on a release warrant **once every 30 minutes**.


## Sentence duration

Depending on the severity of the offenses committed, a player receives a certain pursuit level. Depending on the pursuit level held and taking into account cases where a player has or does not have the right to surrender, they can be punished as follows:


### With right to surrender

* Wanted 1 (Pursuit level 1) - 240 seconds in jail
* Wanted 2 (Pursuit level 3) - 480 seconds in jail
* Wanted 3 (Pursuit level 3) - 600 seconds in jail
* Wanted 4 (Pursuit level 4) - 840 seconds in jail
* Wanted 5 (Pursuit level 5) - 960 seconds in jail
* Wanted 6 (Pursuit level 6) - 1080 seconds in jail


### Without right to surrender

* Wanted 1 (Pursuit level 1) - 500 seconds in jail
* Wanted 2 (Pursuit level 3) - 1000 seconds in jail
* Wanted 3 (Pursuit level 3) - 1500 seconds in jail
* Wanted 4 (Pursuit level 4) - 2000 seconds in jail
* Wanted 5 (Pursuit level 5) - 2500 seconds in jail
* Wanted 6 (Pursuit level 6) - 3000 seconds in jail


### Amounts withheld by the government

After being arrested or processed by a police officer, you will pay a sum of money to the government for the crimes you committed according to the following list. *The money you lose will not go to the city hall safe, it will be deleted from the server.*

* If the player is arrested:
    * Wanted Level 1 - $800
    * Wanted Level 2 - $1500
    * Wanted Level 3 - $2500
    * Wanted Level 4 - $4000
    * Wanted Level 5 - $6000
    * Wanted Level 6 - $7000

* If the player is killed:
    * Wanted Level 1 - $1340
    * Wanted Level 2 - $2640
    * Wanted Level 3 - $3940
    * Wanted Level 4 - $5240
    * Wanted Level 5 - $6540
    * Wanted Level 6 - $7840​​​


Note: When a player is killed by a police officer, the number of seconds is calculated according to the *without right to surrender* category. If a player is arrested, they will receive a punishment from the *with right to surrender* category, depending on the pursuit level (wanted) held.


## Specific commands

### /drink

The jail has a special bar where players can drink certain beverages to increase their health percentage. Typing the /drink command will display a list of available drinks, as well as their price.

### /exit

This is the command used to leave the jail interior and reach the jail yard. To work, you must be near the exit door to the jail yard. *The command is not specific to jail, it can be used in other systems (houses, businesses, etc.).*

### /bail

This command displays certain information to the player about their release for a sum of money. If the player is willing to pay the amount of money displayed by the server, they can continue the release process according to the instructions provided.

* Bail according to wanted level:
    * Wanted 1 - bail $4,000
    * Wanted 2 - bail $6,500
    * Wanted 3 - bail $8,000
    * Wanted 4 - bail $11,000
    * Wanted 5 - bail $13,500
    * Wanted 6 - bail $15,000

### /surrender

This command can be used by players with wanted (**regardless of whether they have the right to surrender or not**) to surrender. The command can only be used inside the jail. If there is no police officer on duty you can surrender automatically, if there is at least one police officer on duty, you will have to wait 5 minutes until you are automatically arrested, if in the meantime an officer does not arrive to arrest you.
