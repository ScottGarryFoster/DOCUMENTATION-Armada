---
Owner: ScottGarryFoster
State: Development
Last Update: 2023-10-15
tags:
  - design
  - possession
  - overview
Epic: Possession
---
**Table of Contents**
- [Summary](#Summary)
- [Content](#Content)
- [Why](#Why)
	- [Design Risks](#Design%20Risks)
	- [Background Research](#Background%20Research)
- [Considerations](#Considerations)
	- [Game Rating](#Game%20Rating)
	- [Patents, Trademarks and Copyright](#Patents,%20Trademarks%20and%20Copyright)
	- [Build and Systems](#Build%20and%20Systems)
	- [Tools](#Tools)
	- [Save file implications](#Save%20file%20implications)
	- [Performance Implications](#Performance%20Implications)
	- [Effect on other systems](#Effect%20on%20other%20systems)

# Summary
Possession is the ability to take over another creature or empty vessel gaining it's abilities, movement style and other traits for your advantage in gameplay. Possessions may be used to solve puzzles, fighting enemies or communicating with the people of the world.

---
# Content
|1| There are two states of being, Possession and Actualisation. Possession is the state where the controls, abilities, movement and traits are that of the possessed vessel. Actualisation is your Wisp form which contains a separate set of these properties. |
|--|--|
|2|When near a potential possession the user interface indicates a button press may occur to move you into the vessel. Equally when in this state the user interface indicates the key to exit a vessel.|
|3|Vessels do not need to be non-alive. Vessels may not always present as possessable for instance you may require knocking out an enemy to possess them.|
|4|Some transformations interact with Vessels. Some will automatically switch mode to Actualisation.|
|5|Possessions are generally restricted by a property. For instance movement, ability or area of the given map. There purpose is to gain power, to unlock or to explore new areas.|
|6|  |
|7|  |
|8|  |
|9|  |
|10|  |
|11|  |
|12|  |
|13|  |
|14|  |
|15|  |
|16|  |
|17|  |
|18|  |
|19|  |
|20|  |
|21|  |
|22|  |
|23|  |
|24|  |
|25|  |
|26|  |
|27|  |
|28|  |

---
# Why
Possessions allow many new mechanics within the game but restricted by the properties we set. These are non-permanent power boosts which offer the ability for fun and intuitive moments of gameplay whilst reducing the risk of creating a less difficult game for other sections of the world.

## Design Risks
**Communication with the player**
This is the largest risk especially as it comes to possessions x transformations. This communication will need to be embedded into some of the puzzle rooms.
The mitigation for this should be the introduction of the Mini-Dungeons to expose the player to these mechanics in isolation before expecting them to use them in a larger puzzle. This should also be the case in larger dungeons.

**Too many combinations**
The agency pillar is one this is attempting to work toward but it does run the risk of providing too much agency such that we as a designer do not actually come up with the solutions or program in solutions which the player thinks of.
User testing and good telemetry along with feedback should help with this. We should have a good understanding of this mechanic and attempt to give the player agency on this.

**Technical and Art Scoping**
As the number of transformations and vessels increase the scope of adding a single one every time will multiply by the sum of the opposite type (new transformations by vessels and visa versa).
There is no mitigation for this other than to keep this in mind and ensure that the ones which are chosen are all complete valid, required and give the most value for our players. We should not add more for the sake of more.

## Background Research
*Why each game is selected*
**Mario Odyssey**
Possession is the core mechanic with abilities, movement and combat integral with the gameplay.

**Dishonored**
The ability to move between the Possessed is potentially a mechanic which we might want to explore.

**Messiah**
Abilities, combat and movement as all used during the possessions to solve the problems the game presents to you.

*Considered but rejected*
**Shadow Gambit: The Cursed Crew**
Might be a consideration in future but it is a tactical game which might not gel as well with the mechanics we might look for.

**Geist**
Heavily combat focused. Could be considered in future when considering the combat side to possessions.

**Kynseed**
Appears to be less of a Possession mechanic and more of an ancestral mechanic.

**Planet of Lana**
You switch between a human and a cat but nothing else it appears (could be wrong). Does not seem a good fit.

---

# Considerations

> **What other departments or sections of the game should be considered or might require additional technology to create this feature.**

## Game Rating
**ESRB, PEGI Rating System**
Blood (even unrealistic) during the possessions should be avoided as this could raise the rating.
Blood and Gore in general should be considered as the act of possession should not be gory as to raise this rating.
Possessions as they relate to a sexual nature should not be considered if we are to hit a lower age rating.
Violence, fear and Horror might come into the overall style and type of the possession from an artistic point of view. Mechanical additions such as possession and then causing the vessel to take it's own life could be considered extreme violence and raise the rating.
Possessions as they relate to a sexual nature should not be considered if we are to hit a lower age rating.

## Patents, Trademarks and Copyright
Copied whole cloth it could be an issue as it is the main mechanic of Mario Odyssey by a large publisher Nintendo. The use of this mechanic needs to be done creatively, adding to the space and without a carbon copy approach.

## Build and Systems

> **Is there any big data processing required to get this feature working.**

## Tools

> **Do we require more tools to make this work and allow designers to use this feature.**

## Save file implications

> **Will this affect how the game saves / loads data and what might that be.**

## Performance Implications

> **Will this affect performance in some way? Would we need to increase the target machines to play the game?**

## Effect on other systems

> **Might this affect other systems such as economical, battle or exploration.**