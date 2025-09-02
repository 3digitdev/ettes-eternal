---
title: 3. Classes
description: An overview of how Classes work
---

You character class is the absolute core of your identity in Ettes Eternal.  It will define the majority of your special abilities, how your character fights, and what role they play in your party.
# Hit Die
Each Class has a defined Hit Die that defines how much HP they get per level.  See the [[1. Basics/index#Health|health mechanics]] on how to calculate your HP.  At Level 1, this is simply:
```
Maximum roll of the Hit Die + your Endurance Modifier + 10.
```
So a Barbarian with 65 Endurance would have **`12 + 6 + 10` = 28 HP** at level 1.
# Weapon Proficiencies
Most classes will start proficient in at least 1 [[Weapons#Weapon Categories|Weapon Category]] (several spellcasters start with none).  In some cases you will be asked to pick from a set of options.  Characters proficient in a weapon are proficient in both 1h and 2h weapons that fall under this category.

Additionally, each player may choose 1 **extra** Weapon Category to start the game proficient in.  This includes classes that have none, like Sorcerer!  This ensures that every class starts with at least 1 Weapon Proficiency, with some player agency to flesh out their character more.
# Starting Equipment
All Classes start with an extremely simple initial set of equipment:
- A single weapon that they are proficient in
- A set of [[Armor#Armor Materials|standard-material]] armor that they are proficient in
- A [[Gear & Services#Standard Adventurer's Kit|Standard Adventurer's Kit]]
- 5 gold pieces
- 2 [[#Specialized Class Equipment]] items
# Specialized Class Equipment
This will be defined for each class, but these are a set of 5 options for interesting and unique items that your character can start with if they choose this Class.  **You may pick up to 2 of these items** and add them to your character sheet.  Some are consumables, and are noted as such.  If not noted, then the item does not decay, expire, or get consumed by use.
# Classes Overview
The following is a table providing a general look at the basics of each class

| Class     | Hit Die | Weapons             | Armor        | Spellcaster? |
| --------- | ------- | ------------------- | ------------ | ------------ |
| Barbarian | d12     | Pick any two melee  | Medium       | No           |
| Bard      | d8      | Finesse OR Crossbow | Light        | No           |
| Druid     | d8      | Polearm OR Mace     | Light        | Yes          |
| Fighter   | d12     | All                 | All + Shield | No           |
| Hunter    | d10     | Bow OR Crossbow     | Light        | No           |
| Monk      | d10     | Brawl OR Polearm    | None         | No           |
| Rogue     | d8      | Finesse OR Bow      | Light        | No           |
| Sorcerer  | d6      | None                | None         | Yes          |
| Witch     | d6      | None                | None         | Yes          |

---
# Multiclassing
In order to provide the maximum amount of customization within reason, Ettes Eternal also allows players to "**Multiclass**"; that is, to select an entire secondary Character Class that interacts with their Primary Class and grants new abilities.
#### IMPORTANT RULE TERMINOLOGY
- Throughout this document, and the rest of the rulebook, you will hear reference to "Primary Class" to refer to your base Class that you created your character with, and "Secondary Class" to refer to the Class you choose to Multiclass into.
- **For the sake of all non-secondary-class effects, when an effect would refer to "Level" (such as "you deal {Level÷2} damage, it is referring to your PRIMARY Class Level.  So if you are a Level 10 Sorcerer and Level 2 Fighter, you would deal 5 damage (Level 10 ÷ 2)**.
## How to Multiclass
### Multiclass Limit
In order to avoid issues with scaling and balance, you are limited to **a single Secondary Class**

Additionally, you can never have more than {Level÷2} Levels in your Secondary Class.  So even if you could afford to achieve Level 7 in your Secondary Class by Level 12, you still cannot do so until at least Level 13 (since you round up on division)
### Multiclass Perks
In order to multiclass, you must first obtain the [[Multiclassing Perks#Multiclass Acolyte|Multiclass Acolyte]] Perk.  This Perk is one of many that "stacks" on itself.  Taking this Perk for the first time, you pick your Secondary Class and gain specific one-time bonuses (see the Perk's description for more detail).  **Each additional time you take this Perk** (up to 5 total stacks), you "level up" in that chosen Class (up to Level 5)

Once you have achieved 5 stacks of **Multiclass Acolyte**, you then gain access to the [[Multiclassing Perks#Multiclass Expert|Multiclass Expert]] Perk.  This perk works essentially the same as Multiclass Acolyte, except it covers granting you **Levels 6-10** of your Secondary Class.

As stated above, **you may not be higher than {Level÷2} (round up as always) in your Secondary Level**.
## Multiclass Spellcasters
When you multiclass **into** a Spellcasting class, as with your Class Abilities, your access to Spells for that class scale with the Level of your Secondary Class.  When you Level up that class, you learn spells at the normal scaling rate, and your mana pool is also based on your Secondary Class Level.

**Example:**
A Level 8 Fighter has multiclassed as a Level 2 Sorcerer.  They take a 3rd stack of Multiclass Acolyte, making the Level 3 Sorcerer.  They would gain 1 Mana (from level 2-3), they would gain access to Level 3 Spells, and they would add 2 new Spells to their known Spells (Level 3 or lower).
## Dual-Caster Multiclassing
This works mostly as you expect, but we will specify two special cases:
1. Your Primary and Secondary Class spell lists are **separate** for each class.  When you level up in your Primary Class, the new spells you pick from come only from your Primary Class's spell list, and vice-versa for your Secondary Class.
2. **Your Mana Pool does not change.**  Your Mana is still, and always will be, calculated only using your **Primary Class Level**.

**Example:**
A Level 8 Sorcerer is multiclassed as a Level 2 Witch.  Thanks to 70 Spellcasting, they have 17 Mana (10 from Level 8 Sorcerer, 7 from Spellcasting Modifier).

When they level up to Level 9 Sorcerer at the end of a session, they gain +2 Mana (total of 19), and they can then select 2 new spells.  These spells can be 5th level or higher (thanks to Level 9), and **must be Sorcerer Spells.**

They then decide to take **Multiclass Acolyte** as their Level 9 Perk, and gain a third stack.  They are now a Level 3 Witch.  **They gain no mana from this**.  They now have access to Level 2 **Witch Spells** and gain 2 new Witch Spells of that level or lower, and **must be Witch Spells**.

---
# Class Tier System
The Class Tier system represents your growing mastery and power within each of your character classes. Unlike equipment-based scaling, your Class Tier is an **inherent** part of your class progression.  While this is simply an abstraction of your Class Level, this is used to help scale power levels throughout the game for various systems.
## Tier Progression
Each class advances through the five Tiers based on your level in that class, as mentioned in the [[1. Basics/index#Tiered Systems|Tier System]] description.  **You automatically gain the next Class Tier upon reaching the minimum level required for it**.  There are no feats, no training.  A heavier roleplay group might want to set up a "training" requirement, or some kind of instructor to help you "tier up", but this is not required by the rules.

| Class Tier | Minimum Level | Description                                       |
| ---------- | ------------- | ------------------------------------------------- |
| Apprentice | 1             | Foundation learning and basic competency          |
| Journeyman | 5             | Developing skill and reliable performance         |
| Expert     | 10            | Advanced mastery and specialized techniques       |
| Master     | 14            | Near-perfect execution and innovative application |
| Legendary  | 17            | Transcendent ability approaching mythical status  |
## System Applications
### Damage Scaling
Your Class Tier determines the number of damage dice you roll for weapon attacks, and for spells cast from that class.  See the [[5. Combat/index|Combat]] page for more information.
### Weapon Attacks
All weapon attacks use your **highest martial Class Tier** for damage scaling, regardless of which class originally granted weapon proficiency. A Barbarian 20/Fighter 5attacks with Legendary tier damage dice even when using Fighter class abilities (although the actual _effects_ of the Fighter's abilities will still use the Fighter Class Tier as normal)
### Class Abilities
Special abilities, maneuvers, and class abilities scale according to the Class Tier of the class that grants them. A good example of this is the Rogue's Sneak Attack, which gains damage at Class Tiers as well.  If you were a Fighter 10/Rogue 5, you would attack with Expert damage dice on your weapon (from Fighter Class Tier) but Journeyman Sneak Attack (from Rogue Class Tier)
### Spellcasting
Spells use the Class Tier of the specific spellcasting class they belong to for damage scaling and other mechanical effects. A Sorcerer's spells scale with the character's Sorcerer Class Tier, while a multiclassed Witch's spells scale with their Witch Class Tier.  Beyond just the scaling of damage dice (mentioned before), the vast majority of non-damaging spells will also delineate how they change with each new Class Tier, allowing old spells to remain relevant.
### Multiclassing
See [[#Appendix A Multiclassing Examples|Appendix A]] for a more detailed look at how this works for multiclassing more clearly.

---
# Appendix A: Multiclassing Examples
Since this can get a little complicated for multiclassing, we'll try to explain each of the possible situations that can arise for various combinations of Martial/Caster:
## Martial + Martial
Fighter 15 (Master) / Barbarian 7 (Journeyman)**
- **Weapon Attacks:** Use Master tier (Fighter's highest) = 3 damage dice
- **Fighter Abilities:** Castle, Situational Awareness scale with Master tier
- **Barbarian Abilities:** Rage damage bonus, Rampage scale with Journeyman tier
- **Result:** Powerful weapon attacks with strong Fighter tactics but moderate Barbarian enhancements
## Martial + Caster
**Rogue 12 (Expert) / Sorcerer 6 (Journeyman)**
- **Weapon Attacks:** Use Expert tier (Rogue) = 2 damage dice
- **Rogue Abilities:** Sneak Attack, Opportunist scale with Expert tier
- **Sorcerer Spells:** Scale with Journeyman tier = 2 damage dice
- **Result:** Skilled mundane combat with modest magical supplementation
## Caster + Martial
**Witch 18 (Legendary) / Fighter 9 (Journeyman)**
- **Weapon Attacks:** Use Journeyman tier (Fighter) = 2 damage dice
- **Witch Spells:** Scale with Legendary tier = 4 damage dice
- **Fighter Abilities:** Battlefield Commander scales with Journeyman tier
- **Result:** Incredibly powerful magic with competent but unremarkable martial skills
## Caster + Caster
**Sorcerer 14 (Master) / Druid 7 (Journeyman)**
- **Sorcerer Spells:** Scale with Master tier = 3 damage dice
- **Druid Spells:** Scale with Journeyman tier = 2 damage dice
- **Class Abilities:** Sorcerer features use Master tier, Druid features use Journeyman tier
- **Result:** Devastating arcane magic with modest nature magic and utility