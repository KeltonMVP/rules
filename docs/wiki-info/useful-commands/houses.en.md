---
icon: material/home
---

# Houses

<img src="https://i.postimg.cc/62ssrzBQ/600px-House-SF.jpg" width="400px">

The houses on our servers are designed in RPG style, which means they closely mimic real houses.

B-Zone provides you with the possibility of buying a house, selling a house, the possibility of renting it and why not, offers you a perfect place to relax by sleeping, using the /sleep command.

**Permissions:**

- Only tenants and the house owner are allowed to use the /tenants and /sleep commands.
- Only the house owner is allowed to use the /open, /setrentable, /setrent, /evict, /evictall, /sellhousetostate, /houseprice, /housewithdraw, /houseupgrade commands.
- If the house door is not locked by its owner, absolutely any player is allowed to use the /heal, /enter and /exit commands. If the door is locked, the commands are only available to tenants and the owner.
- Furniture inside a house will become invisible to all players if the property owner receives wanted (wanted level).
- The owner of a property will not be allowed to use commands for adding or editing furniture elements if they have at least 1 wanted star.

## /enter

The /enter command is usually used to enter buildings, in this case, houses. The command is executed successfully (you will be able to enter the house) only if you are close enough to the door of that building.
For a faster execution, you can use the equivalent of this command, namely the **"F"** key on your keyboard.

## /exit

The /exit command is usually used to exit a building, in this case, a house. The command is executed successfully (you will be able to exit the house) only if you are close enough to the exit door.
For a faster execution, you can use the equivalent of this command, namely the **"F"** key on your keyboard.

## /open

With this command you can lock and unlock your own house.
If you choose to lock the house, the only players who will be able to continue entering the house are tenants and the owner.
You can benefit from this command only if you are the owner of a house.
For a successful execution of the command, you must be inside the house as close as possible to the exit door, or outside it, as close as possible to the entrance door.

## /setrentable

The command tells the server whether you want players to be able to become your tenants.
To offer the house for rent, use the command "/setrentable Yes", otherwise use "/setrentable No".

## /setrent

Using this command, you can set the house rental price.
Each tenant you have and who is online (connected to the server) at PayDay will be deducted the respective amount of dollars, the money will be deposited in the house safe.
The command is executed correctly and successfully only if you have chosen a price between $0 and $1000.

_Note: You are allowed to use the command only if the "/setrentable Yes" command function is activated._

## /tenants

The command will display both the number and names of all tenants online (on the server) at the time of typing the command.
Only tenants and the house owner have access to use this command.

## /evict

The command has the effect of breaking the house rental contract with a tenant and is at the disposal of any house owner.
For a correct and successful execution of the command, use it in the following two ways: /evict <tenant ID> or /evict <tenant name>.

_Example: Consider player Adi007 as a tenant of a house and having ID 12. Therefore, the house owner will break the rental contract with Adi007 using one of the following examples: /evict Adi007 or /evict 12._

## /evictall

The command has the effect of breaking the house rental contract with absolutely all tenants that the house hosts at the time of using it.

## /sellhousetostate

After using this command, you will sell the house to the state, the only money you will receive being that in the house safe, only if it is not empty.

## /houseprice

The correct use of the command will lead to the activation of the possibility for a server player to buy your house in exchange for the amount of money you have set.

_Example: "/houseprice 15000" will set the house price to $15,000._

The minimum price you can set for your own house is represented by the product between the house level and the number 1,000.
_Example: If you own a house that has level 15, the minimum price you can set is 15 multiplied by 1,000, i.e. $15,000_

The maximum price you can set for your own house is represented by the product between the house level and the number 200,000.
_Example: If you own a house that has level 15, the maximum price you can set is 15 multiplied by 200,000, i.e. $3,000,000_

This command gives you the chance for your home to be sold even if you are offline. The money will enter your bank account.

## /heal

To use the command you must be inside a house that you own or have been a tenant for at least 10 minutes. After executing it, you will have 100 health points (HP).
If the player typing the command is part of a department and at the same time the house benefits from "armour upgrade", they will have 100 health points and 100 armour points.

## /sleep

The command is designed to mimic sleeping, so by using the command your character will have a specific animation applied.
When you sleep, other players will see in certain situations, next to your name, the text "(AFK)".
Example of commands that suffer from the described situation: /id, /members, /clanmembers, etc.

If you sleep at PayDay time, you will receive the respect point necessary to advance in level, but the number of hours played will not increase.

The command does not work near the exit door of the house and not if you are wanted by the police or have committed an offense in the last 60 seconds from typing the command.

No player will be able to kill you while you sleep.

## /houseupgrade

The command will display a simple menu from where you can renovate the house. Currently, with this menu you will be able to add the possibility of increasing the health and armour reserve, adding decorative objects (furniture) and activating the possibility of playing a radio station inside the house.

The Heal and Armour functions are implemented when a player uses the "/heal" command in the house.

Each object selected from the menu will cost you $1,000.

Upgrades for houses will be lost when selling them.

Players will be able to add up to 170 objects maximum in the house.

## /removefurniture

By typing this command, all furniture elements added through the /houseupgrade command will be removed. Money spent on furniture to be removed will not be returned.

## /editfurniture

Using this command, the server will display a list of all furniture objects you have added to the house. By clicking on one of the objects in the list, you will be able to remove that object or edit its position. The order of displaying objects in the menu is made from the newest added to the oldest added.

## /defaultfurniture

By typing this command, you can choose between creating or destroying the decorative objects of the house (the initial ones, not those created by you).
For the change to take effect, you will have to leave the server and reconnect to it. It is possible that the initial objects of a house cannot be affected by this command (you cannot hide them).

## /housewithdraw

The command has the effect of withdrawing money from the house safe, money produced from the rent that tenants pay at each PayDay.

To find out what amount of money you have in the house safe, type the /housewithdraw command, without specifying the amount you want to withdraw from the safe.

If you want to withdraw a certain amount of money, type the command following the model:
_"/housewithdraw 500", will withdraw $500 from the house safe._

For a correct and successful execution of the command, you must be inside the house as close as possible to the exit door.

## /houseinfo

To use the command you do not have to be near the house or inside it, the command being usable anywhere you are if you are the owner of a house.

By typing the command, the server will show you some details about your house:

- House level.
- Number of tenants connected to the server.
- Whether the house is rentable or not. If it is rentable, the rent value you set using the /setrent command will appear.
- Whether that house is locked or not.
- The minimum value for which the house can be sold.
- The value of the tax charged by the state (the money you will not receive when someone buys your house, but they will be deducted from the buyer's account). The tax value is equal to the product between the house level and the number 100. _Example (house with level 15): 15 multiplied by 100, so the tax is $1,500._
- The house name, set by its owner.

## /houseradio

Using this command, the house owner will be able to play a radio station or a YouTube link in their own home. When a player enters that house, they will hear the radio station or YouTube soundtrack that have been set by the owner. By using the /houseradio command inside a house that does not belong to you, you will be able to control your ability to hear audio streams inside houses.

Also, sound playback can be stopped by the owner using this command.

## /housename

Using this command, the house owner will be able to set a house name that will be visible to all players who are around that house.

**Note: Using vulgar/offensive texts is punishable by admins.**

## /lift

<img src="https://i.postimg.cc/d7GFSgHR/600px-House-lift.png" width="400px">

_House lift_

- This system allows players to teleport between various areas of the house (roof, parking, depending on availability).
- Only the owner and tenants of a house that has a lift will be able to use the /lift command.
- Vehicles cannot be teleported through this system.
- The system is useful for reaching hard-to-reach places near the house (such as a roof of a tall building, where an airplane or helicopter can be parked).
- To have a lift at your house you can open a ticket [here](https://www.rpg.b-zone.ro/ticket/addSupportTicket) and you can purchase one in exchange for a sum of gold depending on the size of the house. The price starts from 2000 Gold ordered from the shop in the last 7 days for a lift with 1 floor.
