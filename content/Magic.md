Magic in this system is not going to feel the same as it does in systems like D&D.  Many RPG systems use what's called [Vancian Magic](https://tvtropes.org/pmwiki/pmwiki.php/Main/VancianMagic), and it involves Spell Slots, Preparing Spells each morning, etc.

This system takes a more free-form approach;  Each Spellcaster simply has a list of known Spells, and a **Mana Pool** that they use to cast/modify those spells of various levels/costs.  There is no limit to how many of each Spell Level you can cast per day, provided you have the **Mana** for it, but there's a tradeoff of power versus a wider array of options throughout the day.

There are 7 Spell Levels in this system, as well as **Cantrips**
## Cantrips
Cantrips are a special type of "innate" spell that are significantly weaker or simple utility spells.  **For all purposes where Spell Level counts, Cantrips are 0-level Spells.**

---
# Mana Pool
Mana is a common concept in fantasy referring to your innate capacity to cast spells.  Every spellcasting Class in this system will have a Mana Pool that is calculated by various values.  This Mana Pool **refreshes after a [[Basic Mechanics#Rest|Long Rest]]**.
## Calculating Mana Pool
Your Mana Pool will be a combination of a Base Mana value for your Class Level, combined with your **Spellcasting [[Skills#Skill Modifiers|Modifier]]**.  See the [[#Spellcasting Advancement Table]] for more details.

---
# Casting Spells
## Casting Costs
Every Spell has 2 costs associated with it:  **Action Points (AP)** to actually perform the incantation, and **Mana** to expend to cast and modify the spell.  

AP cost is a static *escalating* amount; See [[Combat#Actions|Combat Actions]] to see more how this works.

Mana Cost is relatively simple:  **Every Spell costs a base amount of Mana equal to its Spell Level** (0-7).  [[#Cantrips]] are 0-Level spells, and thus **cost 0 mana to cast**.  This ensures that Spellcasters will always be able to cast _some_ form of magic, albeit weaker Spells, rather than resorting to more...barbaric...methods.

Additionally, you can expend additional Mana for various effects, the core option being on [[#Metamagic]] if you have any available to you.  Some Spellcasting Classes will also have alternative uses for your Mana!

Finally, if a spell targets 1 or more creatures (as opposed to being Blast/Cone/Line) then **you must have Line of Sight on the target(s) of the Spell**, unless the spell states otherwise.
## Casting a Spell
You can cast any spell that you have in your Spell List AND that you have the required Mana to cast.  There is no limit or cooldowns on spells, unless an effect states otherwise.

After selecting your Spell, immediately pay the AP and Mana costs associated with the spell, as well as any additional AP/Mana required for additional effects such as Metamagic.  If you cannot afford to pay these costs immediately, **you cannot cast the Spell**.  Once you have paid the required costs, you can make your...
### Spellcasting Roll
This is almost always standard **Spellcasting Skill Check**, unless a Spell's effect states otherwise.  If you **fail** the Spellcasting Roll, your spell fizzles and you lost all associated costs for the spell.  If you _critically fail_ the Spellcasting Roll, you may have additional complications as decided by the GM.

If you succeed the Spellcasting Roll, you may apply the effects of the Spell.  This may involve enemies making additional [[Basic Mechanics#Opposed Checks|Opposed Checks]].  Spells may also have additional bonuses associated with Hard/Major Successes, or even custom Critical Success effects.  If a spell does not have a defined Critical Effect on its description, then the spell will simply do **double damage** as normal  (All non-damaging spells **will** have a Critical Effect defined).
## Sustained Spells
Some spells have a duration of "**Sustained**", meaning they continue as long as you can maintain concentration on them.

Sustaining a Spell costs **no mana or AP**, but you can only sustain **a single Spell at a time**.  If you cast a new spell with Sustain duration, the previous effect immediately ends.

**You can still cast other Spells while sustaining a Spell.**

When you take damage while sustaining a Spell, you must make an **[[Basic Mechanics#Opposed Checks|Opposed Spellcasting Check]]** against the original attack roll that dealt the damage. If you lose the opposed check, your sustained Spell ends immediately.  This is not a Reaction and costs nothing to perform.

---
# Learning Spells
## Starting Spells
Every Spellcaster will have a prescribe number of Cantrips and Level 1 Spells that they know when they start the adventure. This number is specific to each Class; refer to the Class itself for this number.
## New Spells by Level
Each time you level up, you can learn 2 new Spells of any Spell Level that you can currently cast.  This means that when you Level up and gain access to a new Spell Level (like learning Level 2 Spells at Class Level 3), you can immediately learn 2 Spells at that newly-obtained Level.

This means that, barring any additional spells learned by other means (see below), you should have roughly 38 Spells + your starting spells by level 20 (~45 spells or so), with between 4-12 spells of each Spell Level, assuming you take 2 of your highest level at each Class Level.
## Learning Spells on Adventures🚧
Outside of the spells you learn while adventuring, you can also learn new spells via a few different methods that boil down to 
1. Access to the spell you want to learn (a book, a teacher, etc)
2. Significant time to study, understand, and practice the spell


---
# Spellcasting Advancement Table
The following table demonstrates the scaling of your Base Mana (not linear per level!) and demonstrates what your Mana Pool would be assuming **50 Spellcasting (+5 Modifier)**.  It also shows what the maximum Spell Level you can cast at each level is.

| Level | Base Mana | Max Spell Level | Mana @ 50 |
| :---: | :-------: | :-------------: | :-------: |
|   1   |     1     |        1        |     6     |
|   2   |     2     |        1        |     7     |
|   3   |     3     |        2        |     8     |
|   4   |     4     |        2        |     9     |
|   5   |     5     |        3        |    10     |
|   6   |     6     |        3        |    11     |
|   7   |     8     |        4        |    13     |
|   8   |    10     |        4        |    15     |
|   9   |    12     |        5        |    17     |
|  10   |    14     |        5        |    19     |
|  11   |    16     |        5        |    21     |
|  12   |    18     |        6        |    23     |
|  13   |    20     |        6        |    25     |
|  14   |    22     |        6        |    27     |
|  15   |    25     |        7        |    30     |
|  16   |    28     |        7        |    33     |
|  17   |    31     |        7        |    36     |
|  18   |    34     |        7        |    39     |
|  19   |    37     |        7        |    42     |
|  20   |    40     |        7        |    45     |
_**Note**: Level 1-2 spells will need to be significantly weaker than linear scaling suggests, given the high daily casting frequency (7-9 level 1 spells by level 2)._

---
# Metamagic
**Metamagic** is a concept around being able to modify the effects, shape, or cost of a spell on the fly.  You can apply Metamagic to any spell you want, provided you can pay the appropriate Mana Cost for it.

**You can only apply a single Metamagic Effect to a Spell when it is cast**.  There may be abilities that provide a limited exception to this, but they are very rare.

Initially, no Spellcaster has access to Metamagic.  You gain access via a set of two [[Perks|Perks]]:
- [[Magic Perks#Basic Metamagic|Basic Metamagic]] grants you access to **ALL** Basic Metamagic effects.
- [[Magic Perks#Advanced Metamagic|Advanced Metamagic]] grants you access to **ONE** Advanced Metamagic effect that you select when you take each stack of the Perk.
## Metamagic List

| Name      | Tier     | Cost | Effect                                                                                                                                                                           |
| --------- | -------- | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Extend    | Basic    | +1   | Increase spell duration by 1 round                                                                                                                                               |
| Split     | Basic    | +1   | Target spell affects two different targets instead of one. Effects are split; Damage and/or durations are halved; _apply the extra 1  from odd values to your choice of target._ |
| Still     | Basic    | +1   | Cast without needing to move your arms/etc. Still requires verbal component                                                                                                      |
| Rebound   | Basic    | +2   | If spell is resisted/saved against, automatically targets nearest enemy                                                                                                          |
| Surge     | Basic    | +2   | Roll damage dice twice, take the higher result                                                                                                                                   |
| Widen     | Basic    | +2   | Increase area of effect                                                                                                                                                          |
| Selective | Advanced | +2   | Exclude any number of targets from a spells effect                                                                                                                               |
| Silent    | Advanced | +2   | Cast without verbal components                                                                                                                                                   |
| Echo      | Advanced | +3   | Half of any rolled damage applies again next round at beginning of your turn                                                                                                     |
| Penetrate | Advanced | +3   | Ignore magical resistances or defenses                                                                                                                                           |
| Quicken   | Advanced | +3   | Reduce casting time/AP cost                                                                                                                                                      |
| Maximize  | Advanced | +4   | All variable effects use maximum values                                                                                                                                          |
| Ricochet  | Advanced | +4   | Single-target spells can bounce to additional targets                                                                                                                            |
