# Vehicles

<img src="https://i.postimg.cc/7YRPjRD7/vehiccle.jpg" width="400px">

Everyone wants to have a beautiful, perfectly functional and fast personal car, but at the same time you must also know how you can control your own vehicles. Below you will find a list of all commands you can apply to a vehicle:

## /vehicles

<img src="https://i.postimg.cc/1Xyd6hpH/veh-menu.jpg" width="400px">

<img src="https://i.postimg.cc/ZqMcq7kV/veh-menu2.png" width="400px">

This command represents the control center of all personal vehicles of a player. The /vehicles command also has alternatives for accessing the control center such as commands: **/v**, **/garage** and **/g**. All these commands lead to a single place, the control center.

After using one of these commands, the server will display a list of all owned vehicles using the following model:
- ID of the slot occupied by the vehicle
- Vehicle name
- Its status (available, occupied, hidden)
- How long until the vehicle will be despawned.

Due to SA:MP server limitations, players with premium accounts can spawn up to 8 vehicles at the same time on the server, and those without premium accounts can spawn up to 2 vehicles at the same time on the server.

By selecting a vehicle from the list, the server provides you with several options with which you can control the vehicle.

**Control options:**
- **Information** - Information will be displayed such as: model, price, status (locked/unlocked), colors, kilometers, vehicle days, insurance, insurance cost, id, vip.
- **Locate** - A checkpoint will be set at the vehicle's position.
- **Tow** - Your vehicle will be respawned at the place where it was parked. The price of this service is $200.
- **Spawn/Despawn** - With this option you can make your vehicle appear/disappear temporarily from the server.
- **Unblock** - This option can be useful when your vehicle has been parked improperly and can no longer be used (example: in a wall, in water). The vehicle will be parked in a safe location. Then use the location service to find your vehicle.
- **Sell** - Through this option you can sell the vehicle at DealerShip, only if you are around it.
- **Convert to VIP vehicle** - Through this option you can convert a normal vehicle into a [VIP Vehicle](https://www.rpg.b-zone.ro/shop).
- **Spawn on login** - Through this option you can select which vehicles will spawn automatically when connecting to the server.
- **Buy insurance** - Through this option you can buy insurance for the vehicle.

By default, a player has 4 vehicle slots, these can be supplemented from the [Shop](https://www.rpg.b-zone.ro/shop).

## /engine

Using this command when you are in a vehicle has the effect of starting, or as the case may be, stopping the vehicle engine. As a shortcut to the command, you can also use key **2** on the keyboard.

## /lock

The command is used by vehicle owners to lock or unlock their own vehicle. As a shortcut to the command, key **N** can be used. The command can only be used from near the vehicle.

## /park

This command will fix the position in which the vehicle will be spawned when connecting to the server or when it explodes, sinks or when the towing service (tow) is used. The command can only be used if you are at the wheel of your vehicle.

## /vehswitch

By typing this command, you will be able to change the vehicle you are currently driving with another vehicle that is not spawned.

## /carcolor

A player can use this command only if they are in a personal vehicle and near the CarColor business. After typing the command, the player will be teleported with the vehicle inside a garage from where they can use the menu provided to select the desired colors. If a player is not near this business, a checkpoint will be set for them.

## /buyinsurance

By typing the command, the vehicle owner will buy insurance for the vehicle they are in. A vehicle can have a maximum of 5 insurances. A vehicle left without insurance can no longer be driven by anyone until its owner pays the necessary repairs.

## /buyvehicle

It only works if you are near one of the two dealership doors. Once the command is typed, the server will teleport you into a garage from where you can select the desired vehicle using the menu provided. The server also provides information such as the vehicle's price and speed, allows you to change its colors and most importantly, to do a test drive. For more details, access the [How to Buy](/vehicles/buy-vehicles) page.

## /givekey

To offer someone the keys to your own vehicle, use the /givekey command. The command uses a single parameter, the name or ID of the player to whom you want to lend the keys to your vehicle.

_Example: /givekey 135_

After offering the keys, the person who received them will be able to use the /lock command on the vehicle. This command can only be used near the vehicle.

## /changelock

The command has the effect of changing the lock of the personal vehicle so that the players to whom you offered its keys can no longer unlock or lock the vehicle.

## /throw

This command is used to throw certain objects in your possession, including the keys to a vehicle received from another player, either by renting a vehicle from specially arranged businesses (example: Bike rent). After using this command, you will no longer have a rented vehicle.

## /swapcolors

The servers provide you with two sets of colors for your vehicles, the first set being primary, and the second secondary. By using the /swapcolors command, the vehicle colors will be reversed, which means that the primary will become secondary and the secondary will become primary.

## /v -> Sell

To be able to sell a vehicle at Dealership you must be near it with the car you want to sell. From the /v menu you will select the desired vehicle and then choose the **Sell** option.

_Note: To be able to sell the tutorial car at Dealership you need at least level 5._

## /lights

Through this command you will be able to turn on the vehicle lights without activating the NOS system if it is installed.
