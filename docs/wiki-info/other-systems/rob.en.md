---
icon: material/robber
---

# Rob

<figure markdown="span">
  ![Police on patrol](/images/wiki/general/bank_police_antirob.jpg){ width="400" }
  <figcaption>Police on patrol</figcaption>
</figure>
<figure markdown="span">
  ![Rob menu](/images/wiki/general/rob_main.png){ width="400" }
  <figcaption>Rob menu</figcaption>
</figure>

The rob system allows players to rob houses or businesses. This action is illegal and will be automatically sanctioned with wanted, as a result the police will be on your trail.
It includes two ways to do a robbery: **Solo or Teams**.


## ATM Robbery
ATM robbery is a heist-type activity that involves arming a bomb, entering an activation code, detonation, picking up a personal money bag and a parachute extraction sequence. The process combines a keyboard-type minigame, access conditions on the player's account and a final escape sequence, with risks and penalties in case of failure.

### Requirements for initiation
To start an ATM robbery attempt, the player must meet all of the following conditions:

* Minimum level 7.
* Minimum 10 robbery points (cost is deducted at initiation; final amount lost can be reduced by skin bonuses).
* Not be a member of the police at that time.
* Not have a Wanted level.
* Have a valid flight license.
* Have at least one bomb created in inventory.

### Triggering the robbery

* The player approaches any ATM that has not been recently robbed.
* The Explosive Merchant sends an SMS with a 10-digit activation code.
* A graphic element (textdraw) with the bomb appears on screen; the player must enter exactly the 10 digits to arm the bomb.
* After initiation, the attempt is marked as an active robbery intention.
* Interactions that cancel the attempt immediately: leaving the ATM area or closing the interface before completion → attempt fails and a short cooldown is applied.
* If the player disconnects or dies while the bomb interface is active, the robbery fails automatically and the player receives Wanted for the attempt.
* If they disconnect or die when the interface is not active, the robbery fails silently without applying Wanted.

### Code entry and possible results

* The player types the 10-digit code received by SMS.
* Wrong or incomplete code → attempt fails, a local explosion occurs (local damage/effects) and the player receives Wanted for failed detonation.
* Correct code → the bomb is armed, the player plants it, and after a short timer the ATM explodes. The bomb is consumed.
* After detonation, the ATM enters a broken state; a personal money bag appears next to the ATM, which can only be picked up by the player who performed the robbery.

<figure markdown="span">
  ![Money bag](/images/wiki/general/rob_bag.png){ width="400" }
  <figcaption>Money bag</figcaption>
</figure>

### Money collection

* The player has 90 seconds to pick up the money bag.
* If they don't pick up the bag in this interval → the loot expires and the robbery is considered failed.
* Upon collection:
    * The player receives Wanted for robbery.
    * The ATM becomes disabled for a set cooldown (default 180 s) — during this period it cannot be robbed or used for banking operations.
    * After the cooldown expires, the ATM returns to normal state.

### Escape stage

* Collecting the bag initiates the escape procedure: an escape checkpoint is set in another city.
* The player must travel to the checkpoint with a plane or helicopter (if they don't have a valid flight license after pickup, the sequence doesn't start).
* Upon reaching the extraction point, the player is thrown into the air and receives a parachute automatically.
* There is an altitude indicator that guides the moment of opening the parachute:
    * greater than 500 m - too high (opening here is considered incorrect).
    * 350–500 m - GOOD (safe window for opening).
    * less than 350 m - too low (opening here leads to failure).
* Opening the parachute must take place in the 350–500 m range; opening too early or too late leads to escape failure.
* If the parachute is opened correctly in the indicated range → the escape succeeds, Wanted is removed, and the robbery is completed successfully.

### Rewards on success

* Upon collecting the money bag and successfully completing the escape, the player receives:
* Basic financial reward, determined by Rob skill level (estimated amounts):

    * Skill 1 → $12,500 – $17,500
    * Skill 2 → $17,500 – $22,500
    * Skill 3 → $22,500 – $27,500
    * Skill 4 → $27,500 – $32,500
    * Skill 5 → $32,500 – $37,500

* The reward can be increased by active bonuses (marathons), level bonuses and bonuses from owned skins.
* 7 marathon points for starting the robbery (awarded on success):
    * 3 clan EXP.
    * 1 skill point for Rob.
* The player loses Rob Points at initiation (amount deducted at the end only if they pick up the bag; reduction possible through skin bonuses).


## Explosive Merchant

The Explosive Merchant is an NPC in San Fierro (accessible through /gps → Important Locations → Explosive Merchant) that allows players to produce bombs usable for ATM robberies.
Bombs are obtained through order and collection at a pickup point generated after order confirmation.

### Requirements and costs

Conditions to place an order:

* Not be a police officer, not have Wanted, not be in an active job or robbery group, not be handcuffed/frozen and not be in a vehicle.
* Not already own 3 bombs in inventory (maximum is 3).
* Have sufficient materials for the cost per bomb.

Material cost per bomb (decreases with Arms Dealer skill):

* Skill 1: 500,000
* Skill 2: 437,500
* Skill 3: 375,000
* Skill 4: 312,500
* Skill 5: 250,000

### Observations and usage

* The player initiates the order at the NPC (if they meet the conditions).
* After confirmation, a pickup point is generated.
* Upon collection, materials are consumed and bombs are added to inventory (up to max 3).
* Materials are deducted at the time of collection, not at confirmation.
* Bombs can be used for robbing ATMs (according to robbery rules).
* Orders cannot be completed if, between confirmation and collection, the player loses the necessary conditions (e.g., becomes Wanted or enters a vehicle).
* Check your Arms Dealer skill level before ordering to pay as few materials as possible.


## Solo Robbery

<figure markdown="span">
  ![Circuit in solo rob](/images/wiki/general/Circuit.png){ width="400" }
  <figcaption>Circuit in solo rob</figcaption>
</figure>

<figure markdown="span">
  ![Safe cracking in solo rob](/images/wiki/general/Drill.png){ width="400" }
  <figcaption>Safe cracking in solo rob</figcaption>
</figure>

### Required resources

To rob a house or business you need:

* At least level 7.
* At least 15 robbery points.
* The criminal record must be clean (no wanted).
* Server time must be between 08:00 - 04:00.

### Robbery process

* If the player meets all the conditions mentioned above, they will be able to initiate the /rob command in front of any house or business on the server.
* When using the command, a window will open from where they must select the **Solo Rob** option (*image ##2*).
* After selecting this option, the player will automatically enter a special interior, automatically losing 10 robbery points and will have the following tasks:
    * Break the circuit to be able to open the door to the safe room (*image ##3*): with the help of the up, down, left, right keys they must direct the wire from one part of the circuit to the other without touching the walls. Touching the walls will result in restarting from the initial end of the circuit.
    * Break the safe with the help of a drill using the space key (*image ##4*). The drill heats up the more it is used, at which point it becomes inefficient and breaking the safe takes much longer. For a faster break, it is recommended to keep the drill as cool as possible. You also have a temperature index on the drill so you can see when it gets too hot.
* In the special room you have at most 5 minutes to go through these two stages, otherwise the robbery will fail.
* If the player fits in the required time, they will be taken out of the robbed house or business with a money bag, also receiving wanted 6 without the right to surrender for robbery.
* The next step is to hide the stolen money at two different houses, the player receiving a checkpoint where they need to go. Therefore, we recommend having a vehicle waiting when you do such a robbery.
* If the player manages to take the money to the two locations, then the robbery is successfully completed, at which point the player receives payment for the robbery, another 5 robbery points are deducted and a skill point is added.
* If the player is killed along the way by police officers, they will lose the robbery and will not receive payment, being locked in prison.

### Earnings from Solo Rob

* Skill 1: between $25,000 - $35,000
* Skill 2: between $35,000 - $45,000
* Skill 3: between $45,000 - $55,000
* Skill 4: between $55,000 - $65,000
* Skill 5: between $65,000 - $70,000


These amounts represent the basic earnings, without other bonuses offered by other systems on the server.


## Team Robbery
### Required resources

To rob a bank you need:

* A team consisting of at least 4 and maximum 8 members.
* Each member must have at least level 7.
* Each member must have at least 10 robbery points.
* At least one team member is required to have a pilot license.
* Each member's criminal record must be clean (no wanted).

### Robbery process

* If there are at least 4 members in the team, the team creator will see on the table displayed by typing the /rob command, an option called "Next Step".
* This option will send the team creator to a list of 21 locations from which they can choose the one to be robbed.
* Once a location is chosen, all members will receive access to the /rc chat, visible only to that team.


* After choosing the robbery location, the group leader will have to assign each team member a role, using the /rob command.

Available roles are:

- *Airplane Loaner* - has the mission to go to the airport to rent a plane with which the team will try to escape after finishing the robbery.
- *Gold Melter* - has the mission to go to a certain location to rent a location where the stolen jewelry will be stored for their sale and obtaining a sum of money. The location chosen by the Gold Melter will be the destination of the vehicles after leaving the robbed store.
- *Scout* - has the mission to go to a certain location to rent weapons, after which they must go to the robbery location, climb on a neighboring roof and destroy the 4 surveillance cameras.
- *Gas Man* - has the mission to go to a certain location to rent smoke grenades. At the right time, they will be notified to throw approximately 10 smoke grenades in front of the store.

* If all members have a role assigned, the team leader will have the option to move to the next step (by typing the /rob command). After moving to the next step, each member will receive their mission and will head to the necessary location. Also, each member will consume 3 Robbery Points.

* Once the missions of the 4 roles have been completed, the entire team receives permission to enter the store and start the robbery. A member can steal a certain number of jewelry at once, depending on skill:

    * Skill 1: 25 jewelry pieces.
    * Skill 2: 30 jewelry pieces.
    * Skill 3: 35 jewelry pieces.
    * Skill 4: 40 jewelry pieces.
    * Skill 5: 45 jewelry pieces.

* In the store there are 15 tables with 40 jewelry pieces each, for a total of 600 jewelry pieces in the entire store.
* To steal more, the member must first deposit what they stole in a vehicle. The vehicles available for robbery will be prepared by team members before starting the robbery and can only be the personal cars of team members, cars rented from businesses on the server or simple cars found in various parking lots on the server.
* Airplanes, helicopters, bicycles, motorcycles, boats, faction vehicles, etc. cannot be used. A car can transport as many jewelry pieces as possible. If a vehicle participating in the robbery is destroyed, despawned, etc., it will lose any amount of jewelry from it. If a robbery participant dies, they will lose the bag of jewelry in the case they have.

* All robbery participants will receive Wanted 6 and armor 30 seconds after the first jewelry piece has been picked up from the table in the store.
* Each vehicle that reaches the location chosen by the Gold Melter in a previous step will deposit at that location the amount of jewelry it is transporting.
* From the moment the first vehicle arrives, the other vehicles will have 5 minutes until payment is distributed. If all team members arrive at this location, payment will be made without having to wait 5 minutes.

* Payment will be made based on the total number of jewelry pieces successfully stolen. One jewelry piece is worth $626. From the total value of the stolen jewelry, a standard price of $20,000 will be deducted, which represents the total price of the equipment (plane, weapons, grenades) needed for the robbery.
* The resulting value, the profit, will be divided equally among all members remaining in the team at the time of payment. If there is no profit (not enough was stolen), each member will receive $0. Upon receiving the money, regardless of the amount, team members will consume another 7 Robbery Points and will receive a point for Skill.

* After depositing the jewelry from vehicles, members will receive a checkpoint to the airport. The first member of the group who enters the checkpoint and has a pilot license will automatically become the pilot of the plane, and any other members who enter the checkpoint afterwards will automatically enter inside the plane.
* The pilot can take off at any time and will receive a checkpoint in the air, at which, if they reach it, they and all members inside the plane will escape from Wanted.

* If the pilot of the plane dies, gets out of the plane or loses the plane in any other way, all those inside will be teleported outside and the plane can no longer be recovered. Players will be teleported to the crash site of the plane and will remain with wanted.
* If one of the robbery roles becomes unoccupied (members with that role leave the group for various reasons) and the objectives of that role have not been completed, the robbery will be automatically canceled.
* A robbery can last at most one hour, after which it will be automatically canceled.
* An alarm sound will be heard when players rob stores. The alarm starts the moment the first jewelry piece is stolen from the table and ends after 3 minutes.

### Earnings from the robbery (calculation formula)

<figure markdown="span">
  ![Earnings from a robbery with 4 players participating](/images/wiki/general/castig_rob.png){ width="400" }
  <figcaption>Earnings from a robbery with 4 players participating</figcaption>
</figure>

* earnings = [(jewelry_stolen) - 20000](626) / number_members

**jewelry_stolen** represents the number of jewelry pieces collected from the store by all team members.

**number_members** represents the number of members in the team at the time of money distribution by the server.

## Skill advancement
To advance in skill, you must participate in robberies a certain number of times as follows:

* 25 times to go from skill 1 to skill 2
* 50 times to go from skill 2 to skill 3
* 100 times to go from skill 3 to skill 4
* 200 times to go from skill 4 to skill 5.

## Specific commands

### /rob
Typing the command will display the menu with robbery options. It is the only main command of the system and all actions specific to a certain step of the robbery are displayed in this menu. The robbery team creator can select a member from the list to kick them out of the group, an action only possible in the group formation stage. The creator can invite a maximum of 8 players to the team.

### /robbers

This command can be used by players who want to find a robbery team more easily:

* To add yourself to the list, select "Add me to the list...".
* To delete yourself from the list, select "Delete me from the list..." (or select your own name from the list).
* By selecting a player from the list, a call to that person will be automatically initiated.
* Police officers, players under level 7, players with wanted, players with less than 10 robbery points and players already in a robbery team will not be able to use this command.
* Players who are on the list and become unfit to remain there (for example they receive jail), will be automatically removed.
* There can be a maximum of 60 players on the list at the same time.
* In addition to the names of the players on the list, the faction and level will also be displayed.
* Players on the list will be automatically removed after 10 minutes from adding and will receive a specific message.

### /accept rob id/player name
The command can be used to accept an invitation to join a group for robbing a store.

### /cancel rob
This command will cancel the entire robbery if executed by the leader (creator) of the group, or will remove from the team the player who uses it if that player is not the team creator.

### /grab
This command allows the theft of jewelry from inside the robbed store. For the command execution to be successful, you must be near one of the 15 tables with jewelry in the store.

### /drop
This command deposits the stolen jewelry in the vehicle next to which you are at the time of typing the command.

### /rc
Using this command, team members will be able to communicate with each other, wherever they are.

### /enter, /goup, /godown
These commands will be used to access the interior of the store or the roofs marked during the robbery.

## Tutorials

### Solo Rob

<iframe width="560" height="315" src="https://www.youtube.com/embed/rQRqIzvS3tM" frameborder="0" allowfullscreen></iframe>
