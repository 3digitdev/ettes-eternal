# Armor
This system uses "Armor-as-Damage-Reduction (DR)" which is different from many other D&D-like systems..  Every piece of armor + material has a Damage Reduction (DR) value that reduces your damage from _each hit_ by that much, even down to taking 0 damage!  This means that Armor no longer represents an abstract chance to not take damage (like AC or THAC0), but simply a direct reduction of any damage you take.  This meshes better with the way combat works, rolling against your own stats rather than against enemies.
### Armor Categories & Properties
- **Light Armor**: 1 DR, no penalties
- **Medium Armor**: 2 DR, -10 to Agility, Thievery, Spellcasting, and Athletics
- **Heavy Armor**: 3 DR, -20 to Agility, Thievery, Spellcasting, and Athletics
### Armor Materials
Most armor will be created out of basic materials; Cloth, Leather, and Metal.  This system provides you some example "special materials" that you can craft any type of armor out of that lets you customize your armor in unique ways, as well as increasing the DR value of the Armor!

All armor materials can be used for any armor type (Light/Medium/Heavy); you can have Metal Light Armor just as easily as Cloth Heavy Armor (kind of weird, but it's high fantasy...)
#### Bring Your Own Materials
You are both welcome and encouraged to tinker with this system!  We would not suggest going above +2 on DR, but bring your own ideas for materials for armor, and give them a special property.  Scaling-wise, try to match power levels to the DR bonus, and anything that does damage should do `{Level÷2}` or `{Level}` damage for scaling and balance purposes.
#### Metal Materials

|   Material   | DR  | Special Property                                                                                                 |
| :----------: | :-: | ---------------------------------------------------------------------------------------------------------------- |
| Wrought Iron | +0  | **Heavy Impact** - your melee attacks knock enemies back 1 hex on critical hits                                  |
|    Steel     | +0  | **Spark Strike** - melee attackers take {Level÷2} fire damage when they hit you                                  |
|   Mithril    | +1  | **Phase Touch** - once per day, become incorporeal for 1 round                                                   |
|  Adamantine  | +2  | **Shockwave** - when you get crit, attacker must choose: be knocked prone, drop weapon, or suffer {Level} damage |
#### Leather Materials

|    Material     | DR  | Special Property                                                                       |
|:---------------:|:---:| -------------------------------------------------------------------------------------- |
|  Blood Leather  | +0  | **Blood Absorb** - heals {Level÷2} HP whenever you kill an enemy in melee              |
| Studded Leather | +0  | **Ricochet** - ranged attacks that miss you have 50% chance to hit random nearby enemy |
|   Hide Armor    | +1  | **Feral Scent** - animals must make Willpower checks to attack you                     |
|   Dragonhide    | +2  | **Breath Echo** - once per day, exhale damaging breath attack in 3-hex cone            |
#### Other Materials

|   Material    | DR  | Special Property                                                                                                        |
|:-------------:|:---:| ----------------------------------------------------------------------------------------------------------------------- |
|  Bone Armor   | +0  | **Bone Spikes** - grow temporary bone weapons from your armor                                                           |
|  Scale Mail   | +0  | **Mirror Scales** - redirect one targeted spell per day back at the caster                                              |
|    Chitin     | +1  | **Carapace Burst** - once per day, violently shed outer layer, all adjacent enemies take {Level÷2} damage               |
| Ironbark Wood | +2  | **Living Fortress** - once per day, sprout protective barriers that grant all allies within 3 hexes +2 DR for one round |

---
# Weapons
## Weapon Categories
- See [[Combat#Flow Actions by Weapon Category|Weapon Flow Actions]] for special attacks for each category.
- What weapon you use is up to you and your proficiencies; what category it belongs in belongs in a combination of common sense + DM judgement call
	- especially true when it comes to Rapiers or other Finesse-like weapons.
- Damage types are not exhaustive, and not all weapons in each category do all those damages
	- Good examples: A club can't do Piercing damage, but a Morningstar can.  A Halberd can't do Bludgeoning damage, but a quarterstaff can.
## Weapon Categories Summary

|  Category  | Reach<br>(hex) | Damage<br>(1h/2h) |  B  |  P  |  S  |
| :--------: | :------------: | :---------------: | :-: | :-: | :-: |
|   Sword    |       1        |      d10/d12      |     |  ✓  |  ✓  |
|    Mace    |       1        |      d10/d12      |  ✓  |  ✓  |     |
|  Finesse   |       1        |      d8/d10       |     |  ✓  |  ✓  |
|    Axe     |       1        |      d10/d12      |     |     |  ✓  |
|  Polearm   |    varies¹     |      d10/d12      |  ✓  |  ✓  |  ✓  |
|   Brawl    |       1        |       d8/--       |  ✓  |  ✓  |     |
| (Cross)Bow |    varies²     |      varies²      |     |  ✓  |     |

*¹2h Polearms have a reach of 2*
*²See [[#Bow Ranges & Damage]]*
This clearly shows the damage type coverage for each weapon category along with their mechanical properties.
### Bow Ranges & Damage
|      Type      | Range | Damage |
|:--------------:|:-----:|:------:|
|    Shortbow    |   6   |   d8   |
|    Longbow     |  12   |  d10   |
| Hand Crossbow  |   4   |   d8   |
|    Crossbow    |   8   |  d10   |
| Heavy Crossbow |  10   |  d12   |

---
# Shields
Like Weapons, Shields also have Flow Actions they grant you when wielding.  See [[Combat#Shield|Shield Flow Actions]] for more information.
## Shield Categories
| Category     | Block Roll | Penalty* |
| ------------ | ---------- | -------- |
| Small Shield | -10        | 0        |
| Large Shield | +0         | -5       |
| Tower Shield | +10        | -10      |

*Applied to Athletics, Agility, and Thievery while carrying OR wielding the shield.{Level÷2}