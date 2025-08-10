# Dice
## Dice Basics
This system uses a d100-based system in order to easily represent difficulties, power level, and odds of success at a glance.

For any non-damage roll that you attempt, you will have a **Skill Level** that you need to achieve.  You roll a d100, and simply compare the result of your roll against the **Skill Level**.  If your roll is **less than or equal to the Skill Leve4l**, you have succeeded on the check.  If your roll is **greater than the Skill Level**, you have failed the check.
## Success & Failure
### Success/Failure Levels
There are 4 **Success Levels** and 2 **Failure Levels** when performing a roll:
- **Critical Failure**: Your roll was ≥95.
	- Even if your **Skill Level** was >95 (extremely rare but technically possible), this roll is considered an abject failure, and the GM will assign consequences to the roll appropriate for the situation.
-  **Failure**: Your roll was > **Skill Level**
	- You failed to achieve the result you wanted, but no other consequences occur.
-  **Normal Success**: Your roll was ≤ **Skill Level**
	- You succeed on the roll as normal, with no extra benefits
- **Hard Success**: Your roll was ≤ ½ **Skill Level**
	- You succeeded on the roll in an impressive way, or succeeded at a particularly hard task
- **Major Success**: Your roll was ≤ ¼ **Skill Level**
	- You succeeded on the roll in an incredible way, or succeeded on an extremely difficult task
- **Critical Success**: Your roll was ≤ 05
	- You have succeeded in spectacular fashion.  The GM will assign an incredible result along with your expected result, appropriate for the situation.
#### Rounding
To keep things simple and consistent, when dividing some number for a result (such as ½ **Skill Level**):  **ALWAYS ROUND ALL FRACTIONS UP TO NEXT WHOLE NUMBER.**  
e.g. `25.5` becomes `26`, `33.25` becomes `34`, etc.
## Difficulty Levels & Skill Levels
In order to remain consistent, all difficulty modifiers to determining the success of the check will be handled as modifications to either the **Difficulty Level** or the **Skill Level**, rather than placing bonuses/negatives on the roll result itself.
### Difficulty Levels
As a default any given roll should only require a **Normal Success** in order to succeed at the task.  However, in many circumstances like performing an especially hard task, the GM may require that you achieve a **Hard** or **Major Success** in order to succeed at the check.  In these situations, a **Success Level** lower than that (like a **Normal Success**) will be considered a **Failure**.
### Skill Level Modifications
Very rarely, an ability or circumstance may temporarily modify your normal **Skill Level** for a roll by ±5, ±10, etc.  These should be straightforward, and are applied only to the **Skill Level**, with negatives making the roll harder, and positives making the roll easier.
## Advantage & Disadvantage
Sometimes an ability or circumstance will grant you **Advantage** or **Disadvantage** on your roll.  In these situations, your **Skill Level** remains the same, but you get to roll your dice **2 times**
and take the higher result (**Advantage**) or lower result (**Disadvantage**)
## Opposed Checks
In many situations such as combat, you will find yourself resolving the situation as an **Opposed Check**. In this situation, there's usually someone on offense ("**Attacker**"), and someone opposing them ("**Defender**").

The Attacker makes their check.  **If they succeed**, have the Defender then make their check, and compare **the _**success/failure levels,**_ _NOT the resulting rolls_:
- If Defender's success level was less than the Attacker's success level, the Attacker wins
- If the Defender's success level was equal to the Attacker's success level, it's a [[#Resolving Ties|Tie]]
	- NOTE: [[Combat#Reaction System|Reactions]] in combat handle ties in a specific way!
- If the Defender's success level was greater than the Attacker's Success level, the Defender Wins
#### Opposed Check Example Table

| Attacker       | Defender       | Winner   |
| -------------- | -------------- | -------- |
| Normal Success | Failure        | Attacker |
| Normal Success | Normal Success | Tie      |
| Normal Success | Hard Success   | Defender |
| Hard Success   | Major Success  | Defender |
### Resolving Ties
When 2 people tie a roll, default to the underlying Skill being rolled;  The person with the higher Skill should win the tie.

In the rare case that there is a **complete** tie (identical Skill levels), then resolve in favor of the **players**. If it's two players who tied, then let the players decide who wins their own way.
## Extended Checks
In some situations the GM will request that you do an **Extended Check**.  These represent efforts over an extended period of time, such as crafting an item.

The GM will determine a **number of Successes** that you need to complete the check, and will determine how often you can make the roll.  In certain circumstances, you may need to achieve the desired number of successes within a maximum number of attempts (_example: You need 5 successes in the next week, but can only roll a Check once per day_).

Each time you perform the check, you get a number of successes easily mapped to the **[[#Success/Failure Levels|Success Levels]]**:
- Critical Failure: -2
- Failure: -1
- Normal Success: +1
- Hard Success: +2
- Major Success: +3
- Critical Success: +4

When you have achieved ≥ the number of required **Successes** for the **Extended Check**, you have succeeded, and resolve as normal.

In certain situations like an Extended Check over a course of time, the GM may allow you to continue to roll for the remainder of the time to see how many extra Successes you get above the required to determine any additional benefits/bonuses from the result.
## Aid Another
Aiding another is allowed when at the GM's discretion it makes sense for two skilled players to work together to achieve success on a **non-combat** check.
*Note for GMs:  This can become powerful if overused, and trivialize many Normal Success checks.  Make sure it makes reasonable sense to be able to Aid!*

**LIMIT:** Only one person may Aid Another on any **Non-Combat** Skill Roll.

On any Skill Check, you may roll your own Skill to Aid an ally.
1. **If your Aid Roll succeeds the required check** (e.g. needed Major Success, you rolled Major Success): **The check passes - you did it!** The person you were aiding still rolls to see if they apply any roleplaying bonus (faster results, etc.) or critically succeed for additional bonuses.
2. **If your Aid roll succeeds but doesn't meet the required level** (e.g. needed Hard Success, you rolled Normal Success): You grant **Advantage** to the other player's skill check.

_Note: For Normal Success checks, this effectively allows 2 players to attempt success, which is intended. You can still only have 2 players maximum attempt a check at a time, unless the GM specifies otherwise._
## Group Checks
In certain situations the GM will determine that an **entire group must work together** to achieve success at a task. This might include the entire party attempting to sneak past a guard, everyone climbing up a dangerous cliff face, or the group working together to navigate treacherous terrain.

**Group Checks cannot be used for situations where only one person needs to succeed**, such as Knowledge checks where one person knowing the answer is sufficient for the group. Use [[#Aid Another]] for those situations instead.
### Group Check Process
1. **Designate Leader**: The group chooses a Leader for the check
	- _this is usually the person with the highest relevant skill, but if someone else is 10 lower but has Advantage, it may be best to use them!_
2. **Supporting Rolls**: All other participating party members roll their relevant skill:
    - **Success**: Grant the Leader a bonus to their skill based on success level:
        - Normal Success: +5 to Leader's skill
        - Hard Success: +10 to Leader's skill
        - Major Success: +15 to Leader's skill
    - **Failure**: -5 penalty to Leader's skill
    - **Critical Results**:
        - Critical Success: Leader gains Advantage (non-stacking)
        - Critical Failure: Leader gains Disadvantage (non-stacking)
3. **Leader's Roll**: The Leader makes their skill check with all accumulated modifiers to determine the group's overall success or failure.
### Example
A 5-person party attempts to sneak past guards. The Rogue (80 Thievery) leads while the Fighter (25 Stealth), Barbarian (30 Thievery), Sorcerer (35 Thievery), and Hunter (20 Thievery) provide support.
**Supporting Rolls**:
- Fighter rolls 15 (Normal Success): +5 to Leader's skill
- Barbarian rolls 45 (Failure): -5 to Leader's skill
- Sorcerer rolls 30 (Normal Success): +5 to Leader's skill
- Hunter rolls 95 (Critical Failure): Disadvantage to Leader
**Leader's Modified Roll**: 80 Thievery + 5 + 5 - 5 = 85 Thievery with Disadvantage
The Rogue rolls with effectively 85 skill but must roll twice and take the lower result due to the Hunter's critical failure.
### Notes
- **Extended Checks**: For longer challenges, the GM **may** call for multiple Group Checks at their discretion (such as every 50 feet of climbing).  This is not a requirement though, and should be left to GM discretion.  In most cases, a single Group Check will work.
- **Participation**: All party members attempting the task **must** participate in the Group Check - characters cannot opt out to avoid penalizing the group.
- **Advantage/Disadvantage**: Multiple sources of Advantage or Disadvantage do not stack - the Leader either has it or doesn't.  Advantage and Disadvantage do **cancel** each other though as usual;  If one player crit succeeds and another crit fails, the Leader takes no penalty or bonus to their roll.

---
# Skills Introduction
In this system there is no separation of Attributes/Characteristics and Skills like you find in other systems.  Your character is defined by a set of 19 different **[[Skills]]** that your character will have various levels of ability in.  Your Skill may have a value of anywhere between 1-100 (_[[#Skill Limits|limits apply]]_). In the vast majority of circumstances, you will be rolling a Skill Check to resolve any situation, and your Skill Level (modified rarely) will represent the **Skill Level** for your Skill Check.

**Examples:**
- 50 Endurance → +5 Endurance Modifier
- 33 Agility → +3 Agility Modifier
- 79 Willpower → +7 Willpower Modifier

For more detailed information about Skills, please refer to the [[Skills]] section of the system

---
# Flow System
In certain situations (primarily [[Combat|Combat]]), you can gain **Flow Points** to use to achieve interesting effects or perform special actions.  **Flow Points** are separate from the normal **Action/Reaction Points** used in Combat, and the rules for gaining/losing them depend on the situation.  See the individual sections for more information on how the Flow System works for that section.

---
# Characters
## By The Numbers
### Level
Every character has a **Level**.  Many different abilities will use this to determine an effect, such as "You deal {Level÷2} damage".  As always, round up when making this calculation.

If you choose to **Multiclass** your character, your **Level** for the purposes of any effects will still be your standard Level for your initial Class choice.  In situations where there may be confusion, the system will refer to these as your **Primary Class Level** and **Secondary Class Level**.  To be perfectly clear, if an ability states "{Level} or {Level÷2}", it is referring to your **Primary Class Level**.
### Health
Each class has a Hit Die (HD) value for their class, representing the scaling of their health.

All characters have hitpoints (HP) that are calculated by the following:
> 10 + ((HD Maximum + Endurance [[#Modifiers|Modifier]]) × Level)

**Example:**
A Level 5 Barbarian (d12 HD and 65 Endurance (+6 Modifier) would have
`10 + (12 (HD maximum) + 6) x 5)` →  `10 + (18 x 5)` = **100 HP**
#### Changes to Endurance
Any **permanent** change to your Endurance (including leveling up, [[Variant Rule - Mythic Perks|Variant Rule - Mythic Perks]], or even bonuses from worn items) will cause you to re-calculate your full health total retroactively to level 1.  The easiest way to do this is to just multiply the _change_ in your Endurance [[Skills#Skill Modifiers|Modifier]] by your current **Level**.  So a Level 15 character that has their Endurance go from 45 to 55 would gain an additional 15 health **immediately**.

_Note: Because this applies to **worn items** too, there is potential for confusion if the player is constantly donning and doffing the item.  For the sake of simplicity, we leave it to the GM and players to determine how to handle this, so that magic items can continue to provide interesting benefits_
#### A note on rolling HP
Note that at no point do characters **roll** their Hit Dice to determine their HP.  This is because there can be far too much variance in health totals due to that, and thus make the game feel unfair.  Groups are allowed to choose to roll their Hit Dice if they prefer to have that variance, but please note that **the system is balanced around an expectation of maximum rolls on Hit Dice**, and so beware when making this choice that the system may feel unbalanced or far too brutal as a result.
### Movement
**The battle map for combat in the system operates on a ~5 ft (~2 m) hex grid.**

All characters have a default **Move Speed** of 6 hexes per round.   Outside of combat we let the math stay simple and say 4 miles per hour walking, or 8 miles per hour running.  If the players want to achieve greater than these numbers **outside of combat**, the GM may ask for an Athletics Check with appropriate difficulty
### Senses
Unless specified otherwise by Ancestry, characters have standard human senses and sense abilities.
## Character Features
### Ancestry
Every character has an [[Character Creation#Ancestries|Ancestry]] (commonly called a Race in other systems) which represents your bloodline/lineage.  These Ancestries will grant you certain benefits including a Skill Bonus and an Ancestral Trait.  The idea behind these is to simply provide some small flavor and abilities, rather than becoming the "correct" choice for any given class like other systems might be.  See the [[Character Creation#Ancestries|Ancestries]] for more details
### Background
A [[Character Creation#Backgrounds|Background]] represents a baseline for what your character used to do before beginning their adventures.  Each Background grants an additional Skill Bonus based on the choice, as well as a set of useful and interesting Roleplaying Bonuses unique to each Background to help give players a leg-up at the beginning of a campaign.  Backgrounds provide very little _mechanical_ benefit;  They are intended to either be a capstone or a jumping-off point for you to define your character's backstory!  See the [[Character Creation#Backgrounds|Backgrounds]] for more details.
### Class
Common across most RPG systems, your character's [[Character Classes|Class]] is the core of their identity, representing the lion's share of their abilities, and determines how they power-up as they level throughout the campaign.  See the [[Character Classes|Classes]] for more details.
### Skills
See [[#Skills Introduction]] for details on Skills
### Perks
[[Perks|Perks]] are what other systems may call Feats, or Talents. They represent larger new "abilities" that generally everyone can take (sometimes with pre-requisites). Perks are gained as you level up, and allow you to further customize your character with new abilities to synergize with your Class Abilities. See [[Perks|Perks]] for more details.

---
# Rest and Downtime 🚧
## Rest
When you take approximately 8h to do no strenuous activity (combat, extreme actions, taking damage, etc), you can take a **Long Rest**, and gain bonuses as stated in various abilities/effects/mechanics such as [[#Natural Healing]]
## Downtime 🚧

---
# Dying
When you reach 0 or less HP, you are considered **Dying**, and go unconscious with 0 HP remaining (no negative HP) All ongoing effects on your character end immediately (positive **and negative**, such as Persistent Damage!)

You must begin doing [[#Death Saves]] every round of combat starting on your next turn (or current turn, if you drop to 0 on your own turn).

If an ally stabilizes you at any point in this process, you become unconscious at 0 HP and are free from death saves. If you take any damage while stabilized, you must start Death Saves over again.  Successful Death Saves will not roll over into a subsequent "Dying" state.
## Death Saves
While Dying, you have 4 death save rolls (one per round on your turn) that you can attempt before you permanently die.

The Death Save roll is a flat d100 roll with a **Skill Level of 60**.  There are very few, if any, effects or abilities which can modify this Skill Level.

In order to fend off permanent death, you need **3 successes to stabilize without assistance**. A Critical Success counts as 2 successes for the sake of this tally, but you still only get 1 success even if your roll is a Major Success.

**If you fail to achieve 3 successes within these 4 turns, your character is permanently dead.**

**Important Note:** If your first 3 rolls all fail, you _technically_ have no possible chance to succeed at naturally stabilizing, even if you critically succeed.  However, **you still do not permanently die until the end of your 4th turn Dying**, so that allies have the full 4 rounds to reach you to help Stabilize you before this point.

---
# Healing
## Recovery Roll
In certain situations or as a result from certain spell or ability effects, you may be asked to make a **Recovery Roll**.  This represents a natural healing ability of your character, which can be triggered by these effects.

When you make a Recovery Roll, you can choose each time between a "Safe" Recovery Roll to regain a reasonable static amount of HP, or you can choose a "Luck" Recovery Roll to _actually roll_ for your Recovery, and potentially get significantly more (or less!) HP as a result.
#### Safe Option
You regain 10% of your max HP (round up)
#### Luck Option
You may roll a number of your hit dice equal to your Level÷2 (round up), and regain that many hit points
- *MATH NOTE: Assuming absolute average rolls/stats, a player usually will recover slightly more HP than 10% from this, but potentially much more (or less)!*
## Natural Healing
Every time a character takes a [[#Rest|Long Rest]], they may attempt 1 Recovery Roll
## Applied Healing
**Once per day**, a player may have non-magical healing applied to them (usually through the Medicine Skill), which allows them to take one extra Recovery Roll for that day.  **Note: Better rolls from the healer rolling the Medicine skill may increase the Recovery amount!  See the [[Skills#Medicine|Medicine Skill]] for more details.**

This means that, outside of magical healing, **a player may not roll more than 2 Recovery Rolls per day.**
# Tiered Systems
Ettes Eternal, in many of its mechanics and systems, uses the concept of "Tiers" of play.  This represents how the game is progressing.  In basically any situation you will have 5 Tiers:
1. Apprentice
2. Journeyman
3. Expert
4. Master
5. Legendary
The abilities, effects, and other mechanics for each Tiered System in Ettes Eternal scales as you increase in Tiers, with Legendary Tier producing effects worthy of its namesake.

This convention was chosen to easily track progress and match up when new systems/tiers unlock across all of Ettes Eternal.  You can see when these Tiers are achieved in the [[Character Advancement#Class Level Progression|Class Level Progression]] table.  **Without exception**, each new Tier of effects for a subsystem is unlocked at the same time for all subsystems.  You will get access to Expert Tier Perks at the same time as Expert Tier Traps, and Expert Tier Spells, etc.

---
# Getting Started
Now that you have a basic idea of how the system works, you can either check out the various linked pages (we recommend starting in [[Skills]]), or you can head right over to [[Character Creation]] and start making your first adventurer!