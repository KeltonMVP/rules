---
icon: material/cannabis
---

# Drugs

<figure markdown="span">
  ![Drug effects](/images/wiki/general/drugs_effect.png){ width="350" }
  <figcaption>Drug effects</figcaption>
</figure>


## Types of drugs, benefits and consequences

- Marijuana - using the command */usedrugs marijuana* will consume **12 grams** from the total drugs held. This drug gives the player **5 HP**, but also **2% addiction** or side effects such as dizziness.
- Cocaine - using the command */usedrugs cocaine* will consume **18 grams** from the total drugs held. This drug gives the player **20 HP**, but also **4% addiction** or side effects such as dizziness.
- Ecstasy - using the command */usedrugs ecstasy* will consume **26 grams** from the total drugs held. This drug gives the player **50 HP**, but also **10% addiction**, an unusual side effect and the inability to move for **10 seconds**.
- Meth or methamphetamine - using the command */usedrugs meth* will consume **38 grams** of drugs from the total held. This drug gives the player **100 HP**, but also **20% addiction** and the inability to move for **20 seconds**.

**Note: while the character is on the ground, the /stopanim command is not functional.**

## Enhanced Drugs

Enhanced versions of **Marijuana, Cocaine, Ecstasy and Methamphetamine** can be consumed with /useedrugs <type> (not to be confused with /usedrugs, which is for normal drugs).
Each type requires grams from the enhanced stock and offers higher health increases, stronger addiction levels and unique effects compared to normal drugs:

* **Marijuana** → **+10 HP** (12g, lower addiction, shorter cooldown).
* **Cocaine** → **+30 HP** (18g, lower addiction, faster recovery).
* **Ecstasy** → **+70 HP** (26g, lower addiction, shorter immobilization).
* **Methamphetamine** → Full health (38g, reduced addiction, 15s immobilization)

Only Sons of Anarchy members can sell enhanced drugs using /selledrugs Name/ID Amount Price (not to be confused with /selldrugs for normal drugs).

The price of enhanced drugs is different from that of normal drugs. Sons of Anarchy members can set the selling price anywhere between $1 and $10,000.

Buyers accept with /accept drugs, and enhanced drugs are always marked as "enhanced" in transaction messages.


## Addiction
* Every 15 minutes, players addicted to drugs who have not consumed drugs in the last 15 minutes will lose health as follows:

* *For an addiction level between **50%** and **69%** the player will lose **5 HP**.
* *For an addiction level between **70%** and **89%** the player will lose **15 HP**.
* *For an addiction level between **90%** and **100%** the player will lose **30 HP**.

* To get rid of addiction, players can use the /rehab command.


## Specific commands

### /usedrugs
This command can be used to consume a certain type of drugs, the amount used being automatically set by the server.

### /rehab
This command can be used by players addicted to drugs if they are near the Los Santos hospital.

Using this command, the drug-addicted player will lose **10 percent** from the current addiction percentage. The command can be used once per payday and costs **$1**. Also, paramedics can give you /rehab and you will lose **20%** of addiction.
