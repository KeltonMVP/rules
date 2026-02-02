---
icon: material/console
---

﻿---
icon: material/car
---

﻿# Useful commands for vehicles

<figure markdown="span">
  ![Vehicle Representation](/images/wiki/general/vehiccle.jpg){ width="400" }
  <figcaption>Vehicle Representation</figcaption>
</figure>

Everyone wants to have a beautiful, perfectly functional and fast personal car, but you also need to know how you can control your own vehicles. Below you will find a list of all the commands you can apply to a vehicle:

## /vehicles

<figure markdown="span">
  ![Vehicle Garage](/images/wiki/general/veh_menu.jpg){ width="400" }
  <figcaption>Vehicle Garage</figcaption>
</figure>

This command represents the control center of all personal vehicles of a player. The /vehicles command also has alternatives to access the control center such as: **/v**, **/garage** and **/g**. All these commands lead you to one place, the control center.

After using one of these commands, the server will display a list of all owned vehicles using the following format:

- The ID of the slot occupied by the vehicle
- The vehicle name
- Its status (available, occupied, hidden)
- After how long the vehicle will be despawned.

Due to SA:MP server limitations, players with premium accounts can spawn up to 8 vehicles at the same time on the server, while those without premium accounts can spawn up to 2 vehicles at the same time on the server.

By selecting a vehicle from the list, the server will provide several options with which you can control the vehicle.

<figure markdown="span">
  ![Vehicle Options](/images/wiki/general/veh_menu2.png){ width="400" }
  <figcaption>Vehicle Options</figcaption>
</figure>

Control options:

- Information - You will be shown information such as: model, price, status (locked/unlocked), colors, kilometers, car age, insurance, insurance cost, id, vip.
- Locate - A checkpoint will be set at the vehicle position.
- Tow - Your vehicle will be respawned where it was parked. The price of this service is $200.
- Spawn/Despawn - With this option you can make your vehicle appear/disappear temporarily from the server.
- Unlock - This option can be useful when your vehicle has been parked incorrectly and can no longer be used (example: in a wall, in water). The vehicle will be parked in a safe location. Then use the locate service to find your vehicle.
- Sell - Through this option you can sell the vehicle to DealerShip, only if you are around it.
- Convert to VIP vehicle - Through this option you can convert a normal vehicle into a VIP Vehicle.
- Spawn on connect - Through this option you can select which vehicles will spawn automatically when connecting to the server.
- Buy insurance - Through this option you can buy vehicle insurance.

By default, a player has 4 vehicle slots, which can be supplemented from the Shop.

## /engine

Using this command when you are in a vehicle results in starting or, as the case may be, stopping the vehicle engine. As a shortcut for the command, you can also use the ***2*** key on the keyboard.

## /lock

The command is used by vehicle owners to lock or unlock their own vehicle. As a shortcut for the command, the ***N*** key can be used. The command can only be used near the vehicle.

## /park

This command will fix the position where the vehicle will be spawned when connecting to the server or when it explodes, sinks or when the towing service is used. The command can only be used if you are at the wheel of your vehicle.

## /vehswitch

By typing this command, you will be able to switch the vehicle you are currently driving with another vehicle that is not spawned.

## /carcolor

A player can use this command only if they are in a personal vehicle and near the CarColor business. After typing the command, the player will be teleported with the vehicle inside a garage from where they can use the menu provided to select the desired colors. If a player is not near this business, a checkpoint will be set for them.

## /buyinsurance

By typing the command, the vehicle owner will buy insurance for the vehicle they are in. A vehicle can have a maximum of 5 insurances. A vehicle without insurance can no longer be driven by anyone until its owner pays the necessary repairs.

## /buyvehicle

It only works if you are near one of the two doors of the dealership. Once the command is typed, the server will teleport you to a garage from where you can select the desired vehicle using the menu provided. The server will also provide information such as the price and speed of the vehicle, allow you to change its colors and most importantly, perform a test drive.

## /givekey

To give someone the keys to your own vehicle, use the /givekey command. The command uses a single parameter, the name or ID of the player to whom you want to lend the keys to your vehicle.
*Example: /givekey 135*

After giving the keys, the one who received them will be able to use the /lock command on the vehicle. This command can only be used near the vehicle.

## /changelock

The command has the effect of changing the lock of the personal vehicle so that the players to whom you gave the keys can no longer unlock or lock the vehicle.

## /throw

This command is used to throw certain objects in your possession, including keys to a vehicle received from another player, either by renting a vehicle from specially designed businesses (example: Bike rent). After using this command, you will no longer have a rented vehicle.

## /swapcolors

The servers provide two sets of colors for your vehicles, the first set being primary and the second secondary. By using the /swapcolors command, the vehicle colors will be swapped, which means that the primary will become secondary and the secondary will become primary.

## /v -> Sell

To be able to sell a vehicle to the Dealership you must be near it with the car you want to sell. From the /v menu you will select the desired vehicle and then choose the **Sell** option
*Note: To be able to sell the tutorial car to Dealership you need at least level 5.*

## /lights

Through this command you will be able to turn on the vehicle headlights without activating the NOS system if it is installed.
