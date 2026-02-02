---
icon: material/bank
---

# Bank

The B-Zone RPG server has 3 banks, one in each city (Las Venturas, Los Santos, San Fierro). The following commands can be used in any of the 3 banks (except command number 5, which can only be used near an ATM):

<img src="https://i.postimg.cc/0bkT0z17/450px-LSBank.jpg" width="300px">

_Los Santos Bank_

<img src="https://i.postimg.cc/yghGFHfG/450px-LVBank.jpg" width="300px">

_Las Venturas Bank_

<img src="https://i.postimg.cc/mcCps4Gf/450px-SFBank.jpg" width="300px">

_San Fierro Bank_

<img src="https://i.postimg.cc/z30t5p4x/Atm.png" width="300px">

_#1 ATM Interface_

## /balance

After using this command, the bank will display the amount of money you have in the bank at that moment.
You can only use the command if you are in one of the 3 banks.

## /withdraw

With this command you can withdraw money from your own bank account.
The syntax you must complete for the command to work successfully is: /withdraw <amount of money>
You can only use the command if you are in one of the 3 banks.

_Example: /withdraw 5000_
_Effect: By using the example, you will receive $5,000 in hand, money that is withdrawn from your bank account._

## /deposit

With this command you can add money to your own bank account.
The syntax you must complete for the command to work successfully is: /deposit <amount of money>
You can only use the command if you are in one of the 3 banks.

_Example: /deposit 5000_
_Effect: It will withdraw $5,000 from the money you have on you and deposit it in the bank._

## /transfer

With this command you can transfer money from your bank account to another player's bank account.
The syntax you must complete for the command to work successfully is: /transfer <ID or player name> <amount of money>
You can only use the command if you are in one of the 3 banks, with the exception of event organizers.

_Example: Assuming an online player, with the name "Adi007" and having ID 13:_
_/transfer 13 5000 or /transfer Adi007 5000_
_Effect: It will withdraw $5,000 from the money you have in your bank account and deposit it in player Adi007's bank account._

_Note: To transfer money, you need at least level 3._
_Note: The transfer fee is 1%, it can be calculated with the formula: **1/100 * transferred_amount**_

## /atmwithdraw | /atm

By using the [/atmwithdraw] or [/atm] command in front of an ATM you can withdraw money from your bank account, in hand.
Usually, when you reach an ATM, a welcoming interface will open (image #1), from where you will select the desired amount of money. However, if you accidentally close the interface, you can use one of the 2 commands mentioned above to reopen it.
You can only use the command if you are near an ATM.

_Note: If you want to find an ATM you can use the /gps command._
