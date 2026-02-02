---
icon: material/newspaper
---

# CNN

<figure markdown="span">
  ![CNN Map](/images/wiki/general/CNNs_mapp.png){ width="450" }
  <figcaption>CNN Map</figcaption>
</figure>

<figure markdown="span">
  ![CNN Los Santos](/images/wiki/general/CNNLS_PLACE.jpg){ width="450" }
  <figcaption>CNN Los Santos</figcaption>
</figure>

<figure markdown="span">
  ![#1](/images/wiki/general/ICON_CNN_MAP.jpg){ width="100" }
  <figcaption>#1</figcaption>
</figure>

CNN (Cable News Network) represents the only advertising agency on the B-Zone RPG server. From its three locations, players can write and send advertisements to all other connected players (except those who have disabled this function through the /tog -> Announcements command).

To place announcements you need a minimum level of 3.

## Characteristics

- There is one CNN building in each city: Los Santos, Las Venturas and San Fierro.
- These are marked on the map with an icon as in image #1.
- The price (fee) is valid only in that CNN location and does not take into account the number of characters used.
- The maximum number of characters that can fit in an announcement is 124.
- Announcements will be published in the order of arrival, and the waiting time may vary depending on their number.
- Administrators can delete inappropriate announcements before they are published.
- CNN locations represent SafeZones.
- Publishing offensive, vulgar announcements, or those that do not comply with the RPG server regulations is punishable according to them.

## Structure of an Advertisement

### On a Single Line

When the number of characters in the announcement does not exceed 50.

**Example:** Announcement published by Madalin (456): Buying BMX, Tampa, NRG-500 and Infernus.

### On Two Lines

When the number of characters in the announcement exceeds 50 (the separation is done automatically by the server).

**Example:**

- Line 1: Announcement published by Kelton (128): Selling Monster B, Sparrow, stuntplane from wheel. Se ...
- Line 2: ... lling house 336 cheap, Selling 6medkit, 2addict kit, selling biz 82...

## Specific Commands

### /ad

With this command you can write and publish an announcement. The text must have a maximum of 124 characters. After execution, the server will display a preview of the announcement and the number of seconds until publication.

The command is executed successfully only if you are in a CNN location.

*Syntax: /ad [Announcement]*

### /ads

This command displays a preview of all announcements that are placed on the server before they appear on the global chat.

*Syntax: /ads*

### /cancel ad

The command cancels your announcement, if it is unpublished, waiting. You will not get your money back.

The command is executed successfully only if you have an unpublished announcement waiting.

*Syntax: /cancel ad*

### /myad

This command displays a preview of the announcement and the maximum number of seconds until publication.

The command is executed successfully only if you have an announcement waiting.

*Syntax: /myad*
