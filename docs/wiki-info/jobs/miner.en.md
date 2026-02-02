---
icon: material/pickaxe
---

# Miner

<figure markdown="span">
  ![Job location](/images/wiki/general/Miner_map.png){ width="450" }
  <figcaption>Job hiring location</figcaption>
</figure>

<figure markdown="span">
  ![Player at work](/images/wiki/general/1miner.jpg){ width="500" }
  <figcaption>Player working as miner</figcaption>
</figure>

## General Characteristics

* With the *Miner* job you will collect and deliver ores in exchange for a sum of money.
* The Miner job is a legal job.
* To become a miner, you need a minimum level of 1.
* For this job, you will use the Bobcat vehicle at skill 1-6 and the Yosemite vehicle for skill 6-10.
* The location of the hiring point can be found on the map in image #1.
* For a single delivery (delivery is made at the hiring point) you must collect a total of 5 ores.
* Players who own a premium account receive 50% more at the end of each run.
* You will lose the mission if you leave the vehicle and do not return to it within 20 seconds (exception when collecting ores).
* For each skill advancement, you will receive 10 Gold.

## Skill Advancement

* Skill 1 **>>** Skill 2: 30 runs. (30 total)
* Skill 2 **>>** Skill 3: 60 runs. (90 total)
* Skill 3 **>>** Skill 4: 120 runs. (210 total)
* Skill 4 **>>** Skill 5: 240 runs. (450 total)
* Skill 5 **>>** Skill 6: 200 runs. (650 total)
* *A new vehicle unlocks: Yosemite*
* Skill 6 **>>** Skill 7: 250 runs. (900 total)
* Skill 7 **>>** Skill 8: 300 runs. (1200 total)
* Skill 8 **>>** Skill 9: 350 runs. (1550 total)
* Skill 9 **>>** Skill 10: 350 runs. (1900 total)

## Earnings Calculation Formula

### Skill 1
[(743 + random(115)) * premium_coefficient] + job_bonus

### Skill 2
[(759 + random(115)) * premium_coefficient] + job_bonus

### Skill 3
[(820 + random(115)) * premium_coefficient] + job_bonus

### Skill 4
[(924 + random(115)) * premium_coefficient] + job_bonus

### Skill 5
[(1088 + random(115)) * premium_coefficient] + job_bonus

### Skill 6
[(1111 + random(115)) * premium_coefficient] + job_bonus

### Skill 7
[(1178 + random(115)) * premium_coefficient] + job_bonus

### Skill 8
[(1273 + random(115)) * premium_coefficient] + job_bonus

### Skill 9
[(1330 + random(115)) * premium_coefficient] + job_bonus

### Skill 10
[(1406 + random(115)) * premium_coefficient] + job_bonus

**Note:** The average time required to complete an ore delivery is 230 seconds.

* ***premium_coefficient*** has a value of 1 if you do not own a premium account, or a value of 1.5 if you own a premium account.
* ***random(115)*** represents a random number from 1 to 115.
* ***job_bonus*** represents a multiple of 5. When you use the /work command, ***job_bonus*** has a value of 5. Each time you successfully complete a run, the value increases by 5. If you leave the job vehicle, the value resets to 5. The ***job_bonus*** value will increase by 5 until a maximum of 50.

**Note:** The job bonus (/stats) and the bonus for the job of the day can also be added to earnings.

## Vehicles by skill

### Bobcat

<figure markdown="span">
  ![Bobcat](/images/wiki/vehicles/422.png){ width="250" }
  <figcaption>Bobcat</figcaption>
</figure>

- **DealerShip Price:** $7,500
- **DealerShip Return:** $4,500
- **Maximum Speed:** 140 KM/h
- **Based on:** GMC
- **Number of seats:** 2
- **Required Skill:** 1, 2, 3, 4, 5
- **Tunable:** TransFender

### Yosemite

<figure markdown="span">
  ![Yosemite](/images/wiki/vehicles/554.png){ width="250" }
  <figcaption>Yosemite</figcaption>
</figure>

- **DealerShip Price:** $172,500
- **DealerShip Return:** $103,500
- **Maximum Speed:** 144 KM/h
- **Based on:** Chevrolet Silverado 1998
- **Number of seats:** 2
- **Required Skill:** 6, 7, 8, 9, 10
- **Tunable:** TransFender

## Specific Commands

### /work

This command allows you to start working.

You need to be near the hiring location to execute the command. If this is not the case, the server will place a checkpoint on the map, marking the place where you need to go.
