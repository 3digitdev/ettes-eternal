Magic in this system is not going to feel the same as it does in systems like D&D.  Many RPG systems use what's called [Vancian Magic](https://tvtropes.org/pmwiki/pmwiki.php/Main/VancianMagic), and it involves Spell Slots, Preparing Spells each morning, etc.

This system takes a more free-form approach;  Each Spellcaster simply has a list of known Spells, and a **Mana Pool** that they use to cast/modify those spells of various levels/costs.  There is no limit to how many of each Spell Level you can cast per day, provided you have the **Mana** for it, but there's a tradeoff of power versus a wider array of options throughout the day.

There are 5 Spell Tiers in this system (matching directly to [[Character Classes#Class Tier System|Class Tiers]]), as well as **Novice Spells**
## Novice Spells
Novice Spells are a special type of "innate" spell that are significantly weaker or simple utility spells.  **For all purposes where Spell Tier counts, Novice Spells are 1 step below Apprentice Spells.**
### Novice Spell Scaling
Unlike other spells, Novice Spells scale with your **Adventurer Tier** (based on total character level) rather than your individual Class Tier. This ensures that even multiclass characters and resource-depleted casters maintain competitive basic magical attacks.

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

Mana Cost is based on Spell Tier:
- **Novice:** 0 mana
- **Apprentice:** 1 mana
- **Journeyman:** 2 mana
- **Expert:** 3 mana
- **Master:** 4 mana
- **Legendary:** 5 mana

You'll notice that **Novice Spells** have a Mana cost of 0; this ensures that Spellcasters will always be able to cast _some_ form of magic, rather than resorting to more...barbaric...methods.

Additionally, you can expend additional Mana for various effects, the core option being on [[#Metamagic]] if you have any available to you.  Some Spellcasting Classes will also have alternative uses for your Mana!

Finally, if a spell targets 1 or more creatures (as opposed to being Blast/Cone/Line) then **you must have Line of Sight on the target(s) of the Spell**, unless the spell states otherwise.
## Casting a Spell
You can cast any spell that you have in your Spell List AND that you have the required Mana to cast.  There is no limit or cooldowns on spells, unless an effect states otherwise.

After selecting your Spell, immediately pay the AP and Mana costs associated with the spell, as well as any additional AP/Mana required for additional effects such as Metamagic.  If you cannot afford to pay these costs immediately, **you cannot cast the Spell**.  Once you have paid the required costs, you can make your...
### Heightened Spells
When you choose a Spell to cast, and BEFORE rolling the Spellcasting Check, you may choose to **Heighten** the spell.

**Heightening Cost**: +1 mana per Spell Tier increased. An Apprentice spell heightened to Expert costs +2 mana (total 3 mana).

**Heightening Limit**: You **may not** Heighten a spell to a Tier higher than **the highest Spell tier you can currently cast**.

**Heightening Effects**: Each level of Heightening increases the spell's damage dice and often provides additional benefits as described in the individual spell. Heightened spells use the damage scaling of their heightened tier, not their base tier.

**Examples**:

- A Level 10 Sorcerer (Expert Class Tier) can heighten a Journeyman spell to Expert tier for +1 mana
- A Level 5 Sorcerer (Journeyman Class Tier) cannot heighten any spell beyond Journeyman tier
- An Apprentice spell heightened to Master tier would cost 1 + 3 = 4 total mana
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
Every Spellcaster will have a prescribed number of Novice and Apprentice Spells that they know when they start the adventure. This number is specific to each Class; refer to the Class itself for this number.
## New Spells by Class Level
Each time you level up in your **spellcaster** Class, you can learn 2 new Spells of any Spell Tier that you can currently cast.  This means that when you Level up and gain access to a new Spell Tier (like gaining access to Journeyman Spells at Class Level 5), you can immediately learn 2 Spells at that newly-obtained Spell Tier.

This means that, barring any additional spells learned by other means (see below), you should have roughly 38 Spells + your starting spells by level 20 (~45 spells or so).
## Learning Spells on Adventures🚧
Outside of the spells you learn while adventuring, you can also learn new spells via a few different methods that boil down to 
1. Access to the spell you want to learn (a book, a teacher, etc)
2. Significant time to study, understand, and practice the spell


---
# Spellcasting Advancement Table
The following table demonstrates the scaling of your Base Mana (not linear per level!) and demonstrates what your Mana Pool would be assuming **50 Spellcasting (+5 Modifier)**.  It also shows what the maximum Spell Tier you can cast at each level is.

| Level | Base Mana | Max Spell Tier | Mana @ 50 |
| ----- | --------- | -------------- | --------- |
| 1     | 2         | Apprentice     | 7         |
| 2     | 3         |                | 8         |
| 3     | 4         |                | 9         |
| 4     | 5         |                | 10        |
| 5     | 6         | Journeyman     | 11        |
| 6     | 7         |                | 12        |
| 7     | 9         |                | 14        |
| 8     | 11        |                | 16        |
| 9     | 13        |                | 18        |
| 10    | 15        | Expert         | 20        |
| 11    | 17        |                | 22        |
| 12    | 19        |                | 24        |
| 13    | 20        |                | 25        |
| 14    | 21        | Master         | 26        |
| 15    | 22        |                | 27        |
| 16    | 23        |                | 28        |
| 17    | 24        | Legendary      | 29        |
| 18    | 26        |                | 31        |
| 19    | 28        |                | 33        |
| 20    | 30        |                | 35        |

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
