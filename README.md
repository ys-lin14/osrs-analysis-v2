# OSRS-Analysis-V2

**Context**<br>
Remake of OSRS-Analysis where I set out to determine the differences between two weapons (shown below) in the game Old School RuneScape.
Data was collected over 6 hours (3 hours per weapon) with 10-minute intervals between observations.

Weapon Information
|                    | Iron Scimitar | Event RPG |
|        :-:         |      :-:      |    :-:    |
|   Relative Speed   |     slower    |   faster  |
| Has Attack Bonuses |      yes      |     no    |

**Goals**<br>
- determine which weapon is more accurate
- determine which weapon is more efficient
- obtain estimates of the time it would take to reach level 75 Defence using each weapon
<br><br>


**Methods**<br>
- linear regression
- hypothesis testing
<br><br>


**Results**<br>
|                               | Iron Scimitar | Event RPG |
|            :-:                |      :-:      |    :-:    |
| Probability of Successful Hit |     0.21      |   0.19    |
|      Efficiency (exp/hour)    |     1275      |   1519    |
|     Hours until level 75      |      844      |    709    |

The hypothesis testing results suggest that there are differences between the Iron Scimitar and Event RPG in terms of accuracy and mean 
experience gained every 10 minutes.

The sample proportions suggest that the Iron Scimitar is more accurate than the Event RPG while the slope and 
confidence intervals from linear regression suggest that the Event RPG was more efficient than the Iron Scimitar.
<br>

Key differences between this osrs-analysis-v2 and osrs-analysis include
- focusing on Defence experience alone for better clarity
- storing data within fewer files for better organization
- using modules to save time, improve code organization, efficiency and readability

**References**<br>
*Old School Runescape* [Game]. (2013). Cambridge: Jagex Ltd.
