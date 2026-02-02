---
icon: material/calendar
---

# Events

Events are interactive, recreational activities accessible to any player on the B-Zone servers.

## Requesting an event

<figure markdown="span">
  ![Event request form](/images/wiki/general/requestevent.png){ width="600" }
  <figcaption>Event request form</figcaption>
</figure>

To request an event, the */requestevent* command will be used by any player of minimum level 10.

After executing the command, a form through which you will set the event's mode of operation will be displayed as follows:

* Event Title - determines the title of the upcoming event.
* Minimum Level - the minimum level required for players to participate in the event.
* Maximum Level - the maximum level up to which the event can be accessed.
* Minimum Participants - the minimum number of participants needed to start the event.
* Maximum Participants - the maximum number of players who can participate in the event.
* Event Type - the type of event that will be created.

The types of events are preset as follows:

- Last man standing
- Last vehicle standing
- Duels
- Protect the VIP
- X/O
- SMS
- Trivia
- Whisper
- Stunt
- Kill
- Find and bring
- Parkour
- Races
- Simon says
- Russian roulette
- Even/Odd
- Race Arena
- Paintball
- Gungame
- War Arena
- Slenderman
- Risky Squares
- PubG

* Interior/Location - determines the interior or location where the event will take place. For each type of event, different locations are available for organization, with the organizer having a preset list at their disposal.
* Event Helpers - assigns helpers to the event. Events can have a maximum of 3 helpers.
* Prize - sets the event prize.

Modifying the form is done by clicking on the field to be modified.

After editing the event settings, the player will be able to submit the event for approval by pressing the **Submit** button, with the request remaining active for 5 minutes and automatically canceling if not accepted.


**Note:**
All data entered in the "Request Event" table will be saved until leaving the server.

To reset the entered values, the **Clear Details** button can be used.

Some events (e.g., SMS, Trivia, Whisper) can only take place in the world available to all players (Virtual World 0).

## Event organization

* After the event is approved by the administrative team, the organizer along with the selected helpers will be teleported to the chosen location for the event (if applicable).
* The event will not be open to the public until the organizer allows player access to it. To do this, the organizer must select a teleportation point for joining players using the */emark* command, then start registrations using the */startjoins* command.
* From this moment, any player who meets the conditions set by the organizer can join using the */join* command.
* The organizer can close event registrations using the */stopjoins* command, at which point the event will begin.
* The organizer and their helpers will be provided with a number of administrative commands to facilitate the smoothest possible event organization. Commands can only be used on players currently participating in the event. To see a list of these commands at any time, the */eventhelp* command can be accessed.
* During the event, any administrator or level 2+ helper can join the event as a helper.
* Organizers have one hour to complete the event, otherwise it will stop automatically. They will receive informative messages when they have 30, 15, and 5 minutes remaining to complete the event.

## Available commands and their effects
* Both the main organizer and the 3 helpers will have multiple commands available to conduct their event, depending on its type:
    * Last man standing: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
    * Last vehicle standing: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Duels: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /setrespawnpoint
    * Protect the VIP: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setrespawnpoint
    * X/O: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /xoquestion
    * SMS, Trivia, Whisper, Kill: /sethp
    * Stunt: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Find and bring: /emark, /gotoemark, /setarmour, /disarm, /givegun, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars
    * Parkour: /emark, /gotoemark, /setarmour
    * Races: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall, /veh, /destroyveh, /destroyallveh, /fixveh, /fixallveh, /fuelcar, /fuelallcars, /setfinishpoint
    * Simon says, Russian roulette, Even/Odd, Slenderman: /sethpall, /ekick, /startjoins, /stopjoins, /participants, /emark, /gotoemark, /setarmour, /setarmourall, /disarm, /disarmall, /givegun, /givegunall, /freeze, /freezeall, /unfreeze, /unfreezeall
    * Race Arena, War Arena, Paintball, Gungame: /sethpall, /participants, /emark, /gotoemark, /openarena
* All types of events have the commands: */e*, */sethp*, */stopevent*, */goto*. Additionally, players can use the */eventhelp* command at any time to view the list of available commands for the event type in progress.
* Command effects:

**Note:**

* **A helper is considered any player chosen by the organizer to be part of the event structure.**
* **A participant is considered any player displayed in the */participants* list.**
* **The organizer/helpers can apply the commands below only to participants or helpers.**
    * /sethp - sets the health of a certain participant/helper.
    * /sethpall - sets the health of all participants, except helpers.
    * /ekick - removes a certain participant from the event.
    * /stopevent - stops the event in progress.
    * /startjoins - sends specific messages to all online players with details about the event organization and gives them the ability to type the */join* command.
    * /stopjoins - blocks the */join* command.
    * /e - sends a message on the event chat. If the event is one in which the */join* command is used, then messages will be seen only by participants, otherwise messages will be sent to all server players.
    * /participants - displays a list of event participants (if it is an event that accepts the */join* command). Organizers can remove a participant or teleport to them by selecting them from the list.
    * /emark - marks the point where you are located, to be able to teleport to it later.
    * /gotoemark - teleports to the point marked by */emark*.
    * /goto - allows teleportation to an event participant.
    * /setarmour - sets the armor of a certain participant/helper.
    * /setarmourall - sets the armor of all participants, except helpers.
    * /disarm - disarms a participant.
    * /disarmall - disarms all participants, except helpers.
    * /givegun - gives weapons to a certain participant.
    * /givegunall - gives weapons to all participants, except helpers.
    * /freeze - freezes a certain participant.
    * /freezeall - freezes all participants, except helpers.
    * /unfreeze - unfreezes a certain participant.
    * /unfreezeall - unfreezes all participants, except helpers.
    * /veh - spawns a certain vehicle (maximum 100 vehicles can be spawned).
    * /destroyveh - removes a certain vehicle (a vehicle's ID can be viewed by typing the */dl* command).
    * /destroyallveh - removes all vehicles spawned at the event through */veh*.
    * /fixveh - repairs a certain vehicle from the event.
    * /fixallveh - repairs all vehicles from the event.
    * /fuelcar - fuels a certain vehicle from the event.
    * /fuelallcars - fuels all vehicles from the event.
    * /requestevent - opens the form for submitting an event organization request to STAFF.
    * /join - teleports to the location where the event is organized (if the event is one that accepts this command). Also, organizers can use the command anytime to teleport to the event location.
    * /leaveevent - leaves the event (only participants can use the command).
    * /setrespawnpoint - sets a respawn point for participants, where they will be teleported if they die. The command is only available for Duels and Protect the VIP events.
    * /xoquestion - asks participants a question during the X/O event.
    * /setfinishpoint - sets the finish line (checkpoint) for Race type events. When a player enters that checkpoint, organizers will be informed through messages to determine the race winner.
    * /openarena - unlocks the arena if the event takes place at one of the 4 arenas (Paintball, Gungame, War Arena, Race Arena). Unlocking is necessary because when an administrator/helper accepts a request to organize an event in an arena, that arena will automatically lock to prevent players from entering beforehand.

## Additional details

### X/O Event

* It takes place in a [specially designed location](http://imgur.com/a/JZv21) and represents an interactive type of event where organizers ask players questions, and they must move to the area corresponding to the correct answer (X for NO and O for YES).
* To ask a question, the */xoquestion* command will be used and questions that can be answered with YES or NO will be asked.
* Participants will have 10 seconds to choose which side to stand on (zone X for NO or zone O for YES).
* Participants who are on the wrong answer side when the 10 seconds elapse will fall into the water because [the trapdoors of that zone will open](http://imgur.com/a/Bh4JF) (and they will die a few seconds later).

### Risky Squares Event
* It takes place in a specially designed location and represents an interactive type of event where players will have to knock down the floor to knock down other competitors using an **SD-Pistol** and stay alive.
* When the player shoots multiple bullets in the same square, it will start to fall, and if the player is on it when it is knocked down, they will be eliminated.
* The last 3 participants alive are mentioned to the organizer and helpers.
* The last player alive is the winner.
