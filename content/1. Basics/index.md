# Dice
## Dice Basics
This system uses a d100-based system in order to easily represent difficulties, power level, and odds of success at a glance.

For any non-damage roll that you attempt, you will have a **Target Number** that you need to achieve.  You roll a d100, and simply compare the result of your roll against the **Target Number**.  If your roll is **less than or equal to the Target Number** (commonly but not always your Skill Level), you have succeeded on the check.  If your roll is **greater than the Target Number**, you have failed the check.
## Success & Failure
### Success/Failure Levels
There are 4 **Success Levels** and 2 **Failure Levels** when performing a roll:
- **Critical Failure**: Your roll was ≥95.
	- Even if your **Target Number** was >95 (extremely rare but technically possible), this roll is considered an abject failure, and the GM will assign consequences to the roll appropriate for the situation.
-  **Failure**: Your roll was > **Target Number**
	- You failed to achieve the result you wanted, but no other consequences occur.
-  **Normal Success**: Your roll was ≤ **Target Number**
	- You succeed at the task exactly as you describe, with no extra benefits
- **Hard Success**: Your roll was ≤ ½ **Target Number**
	- You succeeded on the roll in an impressive way, or succeeded at a particularly hard task
- **Major Success**: Your roll was ≤ ¼ **Target Number**
	- You succeeded on the roll in an incredible way, or succeeded on an extremely difficult task
- **Critical Success**: Your roll was ≤ 05
	- You have succeeded in spectacular fashion.  The GM will assign an incredible result along with your expected result, appropriate for the situation.
#### Rounding
When dividing some number for a result (such as ½ **Target Number**):  **ALWAYS ROUND ALL FRACTIONS UP TO NEXT WHOLE NUMBER.**  
e.g. `25.5` becomes `26`, `33.25` becomes `34`, etc.
## Difficulty Levels & Target Numbers
All difficulty modifiers to determining the success of the check will be handled as modifications to either the **Difficulty Level** (making the check require a Hard/Major Success) or the **Target Number** (such as increasing/lowering your skill for the roll by +/- 10), rather than placing bonuses/negatives on the roll result itself.
### Difficulty Levels
As a default any given roll should only require a **Normal Success** in order to succeed at the task.  However, in many circumstances like performing an especially hard task, the GM may require that you achieve a **Hard** or **Major Success** in order to succeed at the check.  In these situations, a **Success Level** lower than that (like a **Normal Success**) will be considered a **Failure**.
### Target Number Modifications
Very rarely, an ability or circumstance may temporarily modify your normal **Target Number** for a roll by ±5, ±10, etc.  These should be straightforward, and are applied only to the **Target Number**, with negatives making the roll harder, and positives making the roll easier.
## Advantage & Disadvantage
An ability or circumstance may grant you **Advantage** or **Disadvantage** on your roll.  In these situations, your **Target Number** remains the same, but you get to roll your dice **2 times**
and take the higher result (**Advantage**) or lower result (**Disadvantage**)
## Opposed Checks
In many situations such as combat, you will find yourself resolving the situation as an **Opposed Check**. In this situation, there's someone on "offense" (the "**Attacker**"), and someone opposing them (the "**Defender**").

**If the attacker succeeds their check**, have the Defender then make their check, and compare the _**success/failure levels,**_ _NOT the resulting rolls_:
- If Defender's success level was less than the Attacker's success level, the Attacker wins
- If the Defender's success level was equal to the Attacker's success level, it's a [[#Resolving Ties|Tie]]
	- NOTE: [[5. Combat/index|Reactions]] in combat handle ties in a specific way!
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

In the rare case that there is a **complete** tie (identical Skill levels), then resolve in favor of the **players**. If it's two players who tied, then the players flip a coin.
### Increasing Success Level
If an ability would allow you to increase your success level on an Opposed Check, and you already rolled a Critical Success, then you automatically win the Opposed Check
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
At the GM's discretion, one play may aid another to achieve success on a **non-combat** check.

*Note for GMs:  This can become powerful if overused, and trivialize many Normal Success checks.  Make sure it makes reasonable sense to be able to Aid!*

**LIMIT:** Only one person may Aid Another on any **Non-Combat** Skill Roll.

On any Skill Check an ally performs where the GM allows you to Aid Another, you may roll your own Skill to assist that ally:
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
**Leader's Modified Roll**: 80 Thievery + 5 + 5 - 5 = 85 Thievery with Disadvantage (The Rogue rolls with effectively 85 skill but must roll twice and take the lower result due to the Hunter's critical failure.)
### Notes
- **Extended Checks**: For longer challenges, the GM **may** call for multiple Group Checks at their discretion (such as every 50 feet of climbing).  This is not a requirement though, and should be left to GM discretion.  In most cases, a single Group Check will work.
- **Participation**: All party members attempting the task **must** participate in the Group Check - characters cannot opt out to avoid penalizing the group.
- **Advantage/Disadvantage**: Multiple sources of Advantage or Disadvantage do not stack - the Leader either has it or doesn't.  Advantage and Disadvantage do **cancel** each other though as usual;  If one player crit succeeds and another crit fails, the Leader takes no penalty or bonus to their roll.
### Failing a Group Check
What happens when you fail a group check is highly dependent on what the group check is.  In the case of the party sneaking past guards, the failure would of course result in the party being discovered together when the guards are alerted.  Other cases may not be so straightforward:  If the group is climbing a cliff and the Group Check fails, then it may be more up to GM discretion:  maybe the group falls with the failing rolling players pulling down the others, or the successes attempt (and fail) to help the others.  The GM may not may it a clear-cut failure either:  It may result in taking significant time, or using up resources, or putting the players in a difficult position.  

---
# Skills Introduction
Your character is defined by a set of 19 different **[[Core Rules/4. Skills/index]]** that your character will have various levels of ability in.  Your Skill may have a value of anywhere between 1-100 (_[[#Skill Limits|limits apply]]_). In the vast majority of circumstances, you will be rolling a Skill Check to resolve a given situation, and your Skill Level (modified rarely) will represent the **Target Number** for your Skill Check.

For more detailed information about Skills, please refer to the [[Core Rules/4. Skills/index]] section of the system

---
# Flow System
In certain situations (primarily [[_Combat|_Combat]]), you can gain **Flow Points** to use to achieve interesting effects or perform special actions.  **Flow Points** are separate from the normal **Action/Reaction Points** used in Combat, and the rules for gaining/losing them depend on the situation.  See the individual sections for more information on how the Flow System works for that section.

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
Any **permanent** change to your Endurance (including leveling up, [[Mythic Perks|Mythic Perks]], or even bonuses from worn items) will cause you to re-calculate your full health total retroactively to level 1.  The easiest way to do this is to just multiply the _change_ in your Endurance [[Core Rules/4. Skills/index#Skill Modifiers|Modifier]] by your current **Level**.  So a Level 15 character that has their Endurance go from 45 to 55 would gain an additional 15 health **immediately**.

_Note: Because this applies to **worn items** too, there is potential for confusion if the player is constantly donning and doffing the item.  For the sake of simplicity, we leave it to the GM and players to determine how to handle this, so that magic items can continue to provide interesting benefits_
#### A note on rolling HP
Note that at no point do characters **roll** their Hit Dice to determine their HP.  This is because there can be far too much variance in health totals due to that, and thus make the game feel unfair.  Groups are allowed to choose to roll their Hit Dice if they prefer to have that variance, but please note that **the system is balanced around an expectation of maximum rolls on Hit Dice**, and so beware when making this choice that the system may feel unbalanced as a result.
### Movement
**The battle map for combat in the system operates on a ~5 ft (~2 m) hex grid.**

All characters have a default **Move Speed** of 6 hexes per round.   Outside of combat we let the math stay simple and say 4 mph (6.5 kph) walking, or 8 mph (13 kph) running.  If the players want to achieve greater than these numbers **outside of combat**, the GM may ask for an Athletics Check with appropriate difficulty.
### Senses
Unless specified otherwise by Ancestry, characters have standard human senses and sense abilities.
## Character Features
### Ancestry
Every character has an [[Core Rules/2. Character Creation/index#Ancestries|Ancestry]] (commonly called a Race in other systems) which represents your bloodline/lineage.  These Ancestries will grant you certain benefits including a Skill Bonus and an Ancestral Trait.  The idea behind these is to simply provide some small flavor and abilities, rather than becoming the "correct" choice for any given class like other systems might be.  See the [[Core Rules/2. Character Creation/index#Ancestries|Ancestries]] for more details
### Background
A [[Core Rules/2. Character Creation/index#Backgrounds|Background]] represents a baseline for what your character used to do before beginning their adventures.  Each Background grants an additional Skill Bonus based on the choice, as well as a set of useful and interesting Roleplaying Bonuses unique to each Background to help give players a leg-up at the beginning of a campaign.  Backgrounds provide very little _mechanical_ benefit;  They are intended to either be a capstone or a jumping-off point for you to define your character's backstory!  See the [[Core Rules/2. Character Creation/index#Backgrounds|Backgrounds]] for more details.
### Class
Common across most RPG systems, your character's [[_Character Classes|Class]] is the core of their identity, representing the lion's share of their abilities, and determines how they power-up as they level throughout the campaign.  See the [[_Character Classes|Classes]] for more details.
### Skills
See [[#Skills Introduction]] for details on Skills.
### Perks
[[_Perks Overview|_Perks Overview]] are what other systems may call Feats, or Talents. They represent larger new "abilities" that generally everyone can take (sometimes with pre-requisites). Perks are gained as you level up, and allow you to further customize your character with new abilities to synergize with your Class Abilities. See [[_Perks Overview|_Perks Overview]] for more details.

---
# Rest and Downtime 🚧
## Rest
When you take approximately 8h to do no strenuous activity (combat, extreme actions, taking damage, etc), you can take a **Long Rest**, and gain bonuses as stated in various abilities/effects/mechanics such as [[#Natural Healing]].
## Downtime 🚧

---
# Dying
When you reach 0 HP, you are considered **Dying**, and go unconscious with 0 HP remaining (there is no negative HP) All ongoing effects on your character end immediately (positive **and negative**, such as Persistent Damage!)

You must begin doing [[#Death Saves]] every round of combat starting on your next turn (or current turn, if you drop to 0 on your own turn).

If an ally stabilizes you at any point in this process, you become unconscious at 0 HP and are free from death saves. If you take any damage while stabilized, you must start Death Saves over again.  Successful Death Saves will not roll over into a subsequent "Dying" state.
## Death Saves
While Dying, you have 4 death save rolls (one per round on your turn) that you can attempt before you permanently die.

The Death Save roll is an Endurance Skill Check.  There are very few, if any, effects or abilities which can modify this Target Number.

In order to fend off permanent death, you need **3 successes to stabilize without assistance**. A Critical Success counts as 2 successes for the sake of this tally, but you still only get 1 success even if your roll is a Major Success.  Critical Failures have no additional effect; they are treated as normal failures.

**If you fail to achieve 3 successes within these 4 turns, your character is permanently dead.**

**Important Note:** If your first 3 rolls all fail, you _technically_ have no possible chance to succeed at naturally stabilizing, even if you critically succeed.  However, **you still do not permanently die until the end of your 4th turn Dying**, so that allies have the full 4 rounds to reach you to help Stabilize you before this point.
### Damage While Dying
If you take any damage while dying, your death save successes are reduced by 1, but you have an extra round to perform Death Saves; essentially, this simply removes one of your previous successes.  If you have not attempted (or succeeded) at a Death Save yet, then nothing happens.

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
**Once per day**, a player may have non-magical healing applied to them (usually through the Medicine Skill), which allows them to take one extra Recovery Roll for that day.  **Note: Better rolls from the healer rolling the Medicine skill may increase the Recovery amount!  See the [[Core Rules/4. Skills/index#Medicine|Medicine Skill]] for more details.**

This means that, outside of magical healing, **a player may not roll more than 2 Recovery Rolls per day.**
# Tiered Systems
Ettes Eternal, in many of its mechanics and systems, uses the concept of "Tiers" of play.  This represents how the game is progressing.  In basically any situation you will have 5 Tiers:
1. Apprentice
2. Journeyman
3. Expert
4. Master
5. Legendary
The abilities, effects, and other mechanics for each Tiered System in Ettes Eternal scales as you increase in Tiers, with Legendary Tier producing effects worthy of its namesake.

This convention was chosen to easily track progress and match up when new systems/tiers unlock across all of Ettes Eternal.  You can see when these Tiers are achieved in the [[Advancement#Class Level Progression|Class Level Progression]] table.  **Without exception**, each new Tier of effects for a subsystem is unlocked at the same time for all subsystems.  You will get access to Expert Tier Perks at the same time as Expert Tier Traps, and Expert Tier Spells, etc.

---
# Getting Started
Now that you have a basic idea of how the system works, you can either check out the various linked pages (we recommend starting in [[Core Rules/4. Skills/index]]), or you can head right over to [[Core Rules/2. Character Creation/index]] and start making your first adventurer!