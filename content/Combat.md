# Action Economy
The combat system is based on an Action Economy, with various actions taking certain types of action Points _(described further below)_:
- **[[#Actions|Action Points (AP)]]** - used for most normal actions such as attacking, casting spells, etc.
- **[[Combat#Reactions|Reaction Points (RP)]]** - used for acting on another creature's turn to react to something, such as dodging an incoming attack, etc.
- **[[#Combat Flow System|Flow Points (FP)]]** - used for special types of combat abilities that vary depending on character, weapon, etc.
You character will start each round/combat with a number of each of these, and gain/lose them by performing actions.
## Actions/Turn Cheat Sheet:
- 6 AP per round
	- 2 AP for attacks/spells; +1 AP escalation
	- 1 AP per Move Speed; maximum 2 AP/turn
	- 1-2 AP for various actions
- 2 RP per round
	- Dodge/Parry/Block/Reaction Attack for 1 RP each
	- Riposte/Intercept/Shield Bash for 2 RP each
- 2 FP at start of combat
	- Gain 1 FP from attacks that hit, 3 FP from crits
		- Limit 1 FP from reactions per round
	- Lose 1 FP per round
## Actions
Your primary action type are just "Actions".  These are things you do in combat that will cost **Action Points (AP)**.  

Every player starts each round of combat with **6 AP**.  Any unused AP at the end of your turn is forfeited; there is no banking or saving up of AP.  Various abilities will cost AP.  It is possible to start a round with more than 6, or to gain additional AP throughout your turn/round thanks to various abilities.  There is not currently a limit to AP you can spend in a single round, provided you have the abilities to justify it.

**Common Actions and their costs:**
_(this is not an exhaustive list!)
- Movement: 1 AP to move full [[Basic Mechanics#Movement|Move Speed]]
- Sprint: 2 AP to move double Move Speed
- First Attack per round: 2 AP _(see [[#Escalating Costs]])_
- Casting first Spell per round: 2 AP _(see [[#Escalating Costs]] and [[Magic (OLD)#Casting Spells|Casting Spells]])_
- Drawing/Sheathing an item: 1 AP each _(thus, 2 AP to switch weapons)_
- Drinking a potion from your bag: 2 AP _(1 AP to draw potion, 1 AP to drink)_
- Using a Magic Item: 1-2 AP _(specific to each item)_
## Reactions
Reactions are used for what they sound like; **reacting** to actions that don't happen on your turn.  Examples might include dodging an attack, or quickly attacking someone as they cast a spell/run away

Every player starts each round of combat with **2 RP**. Any unused RP at the end of your turn is forfeited; there is no banking or saving up of RP.  It is possible to gain more starting RP through various abilities/spell effects, or to gain RP temporarily for a round via similar effects.  There is not currently a limit to RP you can spend in a single round, provided you have the abilities to justify it.

**You may not perform multiple Reactions against a single attack, unless performing a [[#Riposte/Shield Bash|Riposte or Shield Bash]]**
### Basic Reactions & costs
_(there are more abilities that work as Reactions, with their own costs, but the following list is available to all characters from Level 1, regardless of build)_
- **Dodge**: 1 RP to roll Agility to avoid a melee or ranged attack
- **Parry**: 1 RP to roll Melee to deflect another melee attack
- **Block:** 1 RP to roll Endurance to block a melee or ranged attack; _requires a shield_
- **Reaction Attack**: 1 RP to roll a single unmodified attack against an enemy who performs a triggering action within range; _many abilities refer to Reaction Attacks in their effects; this is what they refer to._
- **Riposte**: 2 RP to Parry and immediately counterattack on success
- **Intercept**: 2 RP to move up to 3 Hexes and roll Agility to take an attack for an ally; _does not require a shield_
- **Shield Bash**: 2 RP to roll Endurance to Block and then immediately strike with your shield; _requires a shield_
### Reaction Attacks
Reaction Attacks are a special attack that can be used to disrupt or punish enemies for taking an action that distracts them from your fight.  These can include things like moving out of a hex, spellcasting, standing up from prone, or other actions.  These actions only provoke **Reaction Attacks** if they happen within your [[#Threat Range]].  

For the sake certain abilities, **Reaction Attacks** are a special type of attack.  Many abilities may explicitly single out or _exclude_ Reaction Attacks from their effects.  Refer to the text of each ability for that.  **If not overtly excluded, you may assume that Reaction Attacks are included in the effect if it talks about "attacks"**
### Dodge/Parry/Block
The rules around this are relatively straightforward.  When an attack of the right type would succeed against you, you may spend 1 RP to attempt any of these abilities in order to avoid taking damage from the attack.  Each is either an **Agility** (Dodge), **Endurance** (Block), or **Melee** (Parry) Skill Check.  Treat this check as an [[Basic Mechanics#Opposed Checks|Opposed Check]] against the attacker's attack Skill Check, and resolve as normal.  **If you win the Opposed Check, then the attack does no damage to you**, unless another rule would state otherwise.

**A note on critical results**:  If in the very rare case where you are critically hit and are attempting a Dodge/Parry/Block, which you then **critically fail**, this is an extreme result that actually amplifies the damage you take.  Instead of just taking 2x damage from the critical hit, you will instead take **3x damage from the attack**.

If you **critically succeed** at your Dodge/Parry/Block roll, as long as the enemy attack was not also a critical success, **you regain the 1 RP you spent on the Reaction**.
### Riposte/Shield Bash
For both of these, they are a one-two combo of a **Parry** (Riposte) or **Block** (Shield Bash) followed by a **Reaction Attack** with either your melee weapon (Riposte) or Shield (Shield Bash).  Resolve the action as a combination of these two, with the Reaction Attack being possible only if the Parry/Block succeeds first.  **If an ability would affect Reaction Attacks, it also affects Riposte/Shield Bash.**  These abilities are special in that they let you effectively do 2 reactions against a single attack.
### Intercept
This is a special reaction that can allow you to take an attack from an enemy in place of a nearby ally.  You first must be within **3 hexes** of the attacker **and** your ally. Put simply: if you cannot move to be adjacent to BOTH of them with 3 hexes of movement, **you may not perform Intercept**

Once you have moved to **Intercept**, you must make an **Agility** Check against their attack as an [[Basic Mechanics#Opposed Checks|Opposed Check]], and resolve as normal.  **If you win the Opposed Check**, you take the **full damage** of the attack from the enemy, and your ally takes no damage.  No other reactions may be used as a result of this, and normal damage rules still apply.

**Additionally**, you may optionally choose to move your ally 1 hex away from your movement direction, and take their place (even if this extra hex of movement is above the 3 hexes from your Intercept)
## Special Actions

| Action         | Cost | Effect                                                          |
| -------------- | ---- | --------------------------------------------------------------- |
| Disarm         | 2 AP | Force an opponent to drop an item nearby                        |
| Draw/Sheathe   | 1 AP | Draw or stow a weapon or item                                   |
| Feint          | 2 AP | Fake an attack to gain Advantage                                |
| Flow State     | 1 AP | Retain all FP at the end of your turn; no FP decay              |
| Grapple        | 2 AP | Wrestle to restrain an opponent                                 |
| Ready Action   | ---- | Define a trigger for when you'll take a specified future action |
| Shove          | 2 AP | Knock an opponent backwards or to the floor                     |
| Total Defense  | 3 AP | Ends turn; +1 RP and Advantage on Reactions                     |
| Tumble Through | 1 AP | Move through an enemy's hex without triggering Reactions        |
### Disarm
**Cost:** 2 AP  
**Mechanic:** Make a normal attack roll at Disadvantage. No damage is dealt on success.  
**Restrictions:**  You can only Disarm targets that are your size category or smaller
**Effect:** Target drops one held item.
**Success Results:**
- **Normal Success:** Item lands in adjacent hex (target's choice)
- **Hard Success:** Either take the item (if you have free hand) OR choose any open hex within 2 hexes
- **Major Success:** Either take the item OR choose any open hex within 3 hexes
- **Critical Success:** Either take the item OR choose any open hex within 4 hexes
### Draw/Sheathe Weapon
**Cost:** 1 AP  
**Effect:** Draw a or stow a weapon/shield
### Feint
**Cost:** 2 AP  
**Mechanic:** Make an opposed Melee or Deception roll vs target's Melee or Agility (target's choice).  
**Effect:** On success, your next attack against that target gains Advantage.
### Flow State
**Cost:** 1 AP
**Effect**: Retain all [[#Flow Points]] at the end of your turn, skipping the normal 1 FP decay.  This is essentially just trading 1 AP for that 1 FP next round.
_NOTE: This is a great choice if you have 1 AP left on your turn and nothing else to do!_
### Grapple
**Cost:** 2 AP  
**Mechanic:** Opposed Athletics roll vs target.  
**Restrictions:**  You can only Grapple targets that are your size category or smaller
**Effect:** On success, both characters are grappled.
**Effects While Grappled:**
- **Attacker:** Can make reasonable actions (GM discretion) at Disadvantage
- **Defender:** Cannot take actions except one Opposed Athletics check per round to break free
- **Movement:** Neither can move independently
- **Duration:** Until defender wins Athletics contest or effect is broken
### Ready Action
**Cost:** N/A
**Effect:** Define a specific trigger condition and choose an action to take when that trigger occurs. When the trigger happens, you act immediately at that point in the initiative order. Your initiative position moves to that point for subsequent rounds.

***Example Triggers:** "When an enemy enters my reach," "When the wizard starts casting," "When the door opens"*
### Shove
**Cost:** 2 AP  
**Mechanic:** Opposed Athletics roll vs target.
**Restrictions:**  You can only Shove targets that are your size category or smaller
**Before Rolling:** Choose either Push Back OR Knock Prone.
**Success Results:**
- **Normal Success:** Achieve chosen effect (push back 1 hex OR knock prone)
- **Hard Success+:** Can choose to do both effects (push back 1 hex AND knock prone)
### Total Defense
**Cost:** 3 AP (ends turn immediately)  
**Effect:** Gain +1 RP and Advantage on all Reactions until the beginning of your next turn.
### Tumble Through
**Cost**: 1 AP
**Requirement**: Adjacent to an enemy
**Effect** You make an **Agility Check**.  If you succeed, you can move directly through the enemy's Hex to the other side of them without provoking **Reaction Attacks** from any enemy.  If you **fail** your **Agility Check**, you must stay where you are, and this attempted action will provoke **Reaction Attacks** from _only the enemy you attempted this on_, and not any other adjacent enemies.
**You can attempt this in the MIDDLE of Move Action.  The extra hexes do not count toward your movement for that Action.**
## Free Actions
Free actions are things you can perform without spending any type of action point.  These are considered quick or trivial actions not worth keeping track of.  **Please keep Free Action use in combat to a reasonable amount; Talking is a Free Action, but you still only have ~6 seconds per round**.  We leave it up to GMs and players to decide what is a reasonable limit.

**Example Free Actions**:
_(this list is not exhaustive!)_
- **Taking a Step** (_[[#Taking a Step||see below]]_)
- Making a Knowledge Skill Check
- Speaking/yelling something
- Dropping something to the ground
- Operating a small object
- Opening a door

---
# Initiative
1. Everyone rolls 1d10 + Agility [[Basic Mechanics#Modifiers|Modifier]]
2. Initiative proceeds from highest to lowest roll
3. Ties are resolved [[Basic Mechanics#Resolving Ties|as normal]]
## Surprise Attacks
Surprise Attacks happen when one side of a potential combat gets the drop on the other.  This can happen through a variety of ways, but is primarily done when one party is unaware of the other.

Surprise attacks are simply 1 round of combat resolved normally, but only the surprising party may act in that round.

First, roll initiative for everyone (even the surprised party).  The _surprising_ party gets their free 2 FP at the start of combat in this Surprise Round.  **The surprised party starts the Surprise round with 0 AP, 0 RP, and 0 FP** (they get their 2 free FP at the start of the first normal round of combat)

Resolve the Surprise Round as a normal round of combat other than these rule exceptions above.  Once the surprising party has all taken a turn, then combat proceeds as normal following initiative order.  _This can mean that high-rolling surprisers will get multiple turns before the enemy gets one!_
## Round Resolution Cheat Sheet
### Round Structure
1. **Initiative Order**: Characters act in order determined by Initiative result
2. **Sequential Actions**: Each character declares one action, resolves it, then decides next action
3. **Reaction Interruptions**: Reactions can interrupt the active character's turn when triggered
4. **Round End**: "End of round" effects resolve, and new round begins; *same initiative order*
### Individual Turn Sequence
1. **Declare action** and spend AP
2. **Resolve action** (including any triggered reactions)
3. **Repeat** until AP exhausted or player chooses to end turn
4. **Ongoing effects resolve** (bleeding, poison, etc.)
5. **FP decay**: Lose 1 FP (unless Flow State was used)
6. **Next character's turn**
### Round End
- After all characters complete turns, new round begins with same initiative order
- No additional effects or resets

---
# Movement 
## Movement In Combat
**The battle map for combat in the system operates on a ~5 ft (~2 m) hex grid.**

Unless stated otherwise, all player characters start with **6 hexes** of movement per [[#Actions|Action Point]] spent.  The most a player can move per round is 2 AP worth of movement (~12 hexes)

As a round of combat is normally about 6 seconds, this translates to roughly 7 mph (3 m/s) which is running speed for an average human.

You can move through allies' hexes for free with no penalties, but you cannot move through an enemy hex unless you attempt to [[#Tumble Through]].
### Taking a Step
A special Free Action that can be taken **once per round**, "**Taking a Step**" is the ability to move 1 hex in any direction without provoking Reaction Attacks from adjacent enemies who [[#Threat Range|threaten]] you.  This does not count towards your Move Speed for the sake of Move Actions; You can hypothetically Take a Step, then spend 2 AP to move an additional 12 hexes for a total of 13 hexes.
## Movement Outside Combat
Outside of combat, movement obviously does not cost anything like AP.  For the sake of speeds, assume a normal walking speed is 2-4 mph (~1-2 m/s), jogging speed is 4-6 mph (~2-3 m/s), and running speed is 6-10 mph (3-5 m/s).  If the players would like to attempt to exceed 10mph running speed, they should attempt an Athletics Check at the discretion of the GM based on the situation/duration.

---
# Reach
"Reach" is how far away you can reasonably perform a melee attack against an opponent, and is denoted with "Reach #", with the # representing your Reach value.

Reach is generally defined by your Size, which is Medium of Small for all player characters by default. Medium and Small creatures have **Reach 1**, which means they [[#threat Range|Threaten]] enemies within 1 hex, which is all _adjacent_ hexes to the creature. For each size category above Medium, increase **Reach** by +1.  So a Large enemy would have **Reach 2**, and they [[#Threat Range|threaten]] enemies within 2 hexes, so all adjacent hexes + all hexes adjacent to those (total of 18 hexes of threat).  Huge Enemies have **Reach 3**, etc.

Reach can also be modified by weapon type;  for example, 2h Polearm weapons often have a Reach 2, which means that they threaten the 18 surrounding hexes around the wielder.  **Reach values do not stack; you take the highest Reach value you have as your total Reach.**
## Threat Range
**Threat**, as stated before, is defined by your **Reach**; it is any square you can reasonably reach with a melee attack.  Many different effects will refer to "threat", "threatening" or "threatened", and this is what they refer to.

If an opponent takes certain "triggering" actions within your **Threat Range**, or moves OUT of any hex you **threaten**, then you may use 1 RP to perform a [[#Reaction Attacks|Reaction Attack]] against that enemy provided you have the RP to do so.

_Note: if an enemy moves between hexes you threaten, they have technically moved "out" of the hex they occupied when they started, and thus trigger a Reaction Attack, **unless they [[#Taking a Step|Took a Step]]**.  The wording of "moves OUT" above was chosen specifically to avoid ambiguity._
## Range Penalties
When firing a ranged weapon, your weapon will have a Range value (such as Range 6 for the Shortbow).  This represents the furthest you can fire the weapon to attack with no penalties.

Ranged attacks from outside your weapon's range incur a `-10` penalty to your **Ranged Skill Check** per "range increment"; so a Shortbow (Range 6) gets a `-10` for 7-12 hexes, `-20` for 13-18 hexes, etc.

---
# Attacking
## Melee
Melee attacking is relatively straightforward as opposed to most systems, but here are the detailed steps:
1. Pick a target within your [[#Threat Range]] to attack
2. Declare what attack you are doing, or what special abilities you are using
3. Roll a **Melee Skill Check** to see if your attack succeeds
4. If your attack succeeds, continue; otherwise, your action is over and you can either do your next action or end your turn.
5. Allow GM to declare if the enemy is performing a Reaction and then resolve the Reaction
6. If the Reaction fails, or no Reaction is used, then [[#Damage|roll damage]] for your attack.  
7. Apply Critical effect if necessary or any other special abilities that apply when the attack succeeds
8. Proceed with your next action
## Ranged
Ranged attacking is basically the same as [[#Melee]], except instead of selecting a target in Threat Range, you instead pick any target within range of your weapon that you have Line of Sight (LoS) on, then you roll a **Ranged Skill Check**.  Beyond this, the attack works exactly the same as melee attacking.
## Spellcasting
See [[Magic (OLD)#Casting Spells|Casting Spells]] for a detailed look at how this works
## Escalating Costs
The first attack or spell cast each round costs 2 AP.  Each additional attack or spell in the same round has an Escalating Cost: your second attack/spell is 3 AP, the third is 4 AP.  This means realistically you can attempt at most 2 attacks/spells per round, barring serious benefits of gaining another 2 AP that round from various abilities and forgoing your movement.

**Escalating Costs stack with each other.** If you cast a spell for 2 AP, and then melee attack, your melee attack would cost 3 AP.
#### AP Reduction via Abilities
There are certain abilities that may reduce the cost of one of your attacks/spells in a round by 1 AP (or more).  **This does not reset or modify the escalating cost.**  

**Example**: You cast a spell with Quickened Metamagic for 1 AP, rather than the normal 2.  Your next spell would **still cost 3 AP to cast.**  Otherwise you're effectively getting 2 or more "free" AP which would be too powerful!

---
# Damage
What you roll for damage is highly variable. However, there are 3 different sources that can modify your damage roll for any given attack or spell.
## Bonus Damage Sources
### Bonus Damage Dice
You gain bonus damage dice on all weapon and spell attack damage as a result of your [[Character Classes#Class Tier System|Class Tier]]. The progression, repeated here:

| Class Tier | Total Dice |
| ---------- | ---------- |
| Apprentice | 1          |
| Journeyman | 2          |
| Expert     | 2          |
| Master     | 3          |
| Legendary  | 4          |
### Bonus Damage Modifier
- **Melee Attacks:** Higher of Melee or Agility Modifier
- **Ranged Attacks:** Higher of Ranged or Agility Modifier
- **Spells**: Spellcasting Modifier
### Success Level Bonuses
- **Normal Success:** +0 damage
- **Hard Success**: +2 damage
- **Major Success**: +4 damage
- **Critical Success (≤05)**: as Major Success, AND 2x final damage after all bonuses
## Sample Attack
You are a Level 5 Fighter (Journeyman) wielding a longsword (d8 weapon dice) with 75 Melee and 62 Agility.  You roll your Melee attack and get a result of **15**.  This is a **Major Success**, and thankfully the attack lands when the enemy fails its Dodge.

Barring any other abilities, your damage roll would be **`2d8+11`**
- 2d8 from your weapon
	- 1d8 base weapon damage
	- +1d8 from your **Journeyman Class Tier**
- +7 from your **Melee Skill**
- +4 from the **Major Success**
## Critical Damage
When you roll a Critical Hit on an attack or spell, you always do 2x damage on the attack.  This is calculated simply by rolling your damage normally and multiplying the result of the damage.

Many spells will not have damaging components.  In those cases, the individual spell will define a Critical Effect to apply in this situation instead.
## Persistent Damage
In some situations you may apply or receive [[Status Effects#Persistent Damage Types|Persistent Damage]].  In a nutshell this is damage a creature will take at the **end** of each of its turns that it can potentially clear with various actions or rolls.  The damage for these is denoted with **"Persistent #"** with the # being the damage.  # can be a flat value or a dice roll.  See [[Status Effects#Persistent Damage Types|Persistent Damage]] for full details.

---
# Combat Mechanics 🚧
## Gang-up
When 2 or more allies are threatening the same enemy, they are ganging up and gain a +10 Melee bonus to attacking that enemy
## Firing into Melee
You're all competent adventurers. Firing into melee does not incur penalties, but critical fumbles might get interesting...
## Two-Weapon Fighting
In general, attacking with your non-dominant hand will yield a -10 to your Melee skill on attack.  **Finesse and Brawl weapons do not have this penalty**.  There is a [[Combat Perks#Dual Wield|Perk]] to remove this detriment entirely.
#### A Note on TWF
_Yes, you're correct in realizing there's absolutely no base mechanical benefit to dual-wielding the same weapon category (dual daggers).  That's because **it's BORING to do that**.  Get **creative** if you want to dual-wield!  Wielding 2 weapon categories means more options for Flow Actions!  Sword/Fist; Dagger/Sap (Mace); Axe/Hand Crossbow! Get CRAZY!_

---
# Combat Flow System
## Inspiration
The **Flow System** is a new concept to this system that is intended to make Melee and Ranged combatants have more interesting things to do on their turn than the standard class abilities and "I swing my sword twice, roll damage".  **Note that this system is not applied to Spellcasters**. They have many of their own interesting things to do each round due to expansive spell lists, and thus did not need this.  You can think of this as a sort of "Spell List" for Martial Combat.
## Flow Points
**Flow Points** are a separate pool of action points given to martial combatants as reward for certain actions, and represent a martial character getting into the "flow of combat", and being able to achieve interesting results the more/longer they fight.  **Flow Points** are gained in a variety of ways, and **can be banked between turns**.  You are not required to have 0 FP at the end of your turn or risk losing it.  There is a [[#Flow Decay]] mechanic that will sap some FP each turn, and many abilities that may sap FP in their effect.
### Maximum FP
As a default, **no character may exceed their Melee or Ranged [[Skills#Skill Modifiers|Modifier]] in total FP**.  So a character with 72 **Ranged Skill** could bank a total of **7 FP** during combat.  Any FP gained while at maximum are lost.
### Initial Flow Points
At the start of every combat, **all combatants begin with 2 FP**; this represents the adrenaline spike from entering combat as everyone plans their first moves.
### Flow Decay
At the end of your turn (after all other effects are applied) you lose **1 FP** from your pool (down to 0).  This represents the flow of combat passing by, and encourages you to use FP while making it harder to hit maximum for huge combinations.
### Gaining Flow Points
At a basic level, you gain FP by succeeding on attacks in combat.
- **Attack hits** _(regardless of Success level)_: +1 FP
- **Attack Critically Hits**: +3 FP
- **First Reaction:** +1-3 FP ([[#Special Case Reactions|see below]])
#### Special Case: Reactions
Each round if you successfully perform a Reaction of any kind (including Dodge, Riposte, or _even Intercept_) you gain +1 FP **for your first successful Reaction**

If the Reaction is a **Reaction Attack**, and it critically hits, you still gain +3 FP as usual for crits.
### Summary + Example
This means that, in an _incredibly lucky situation_, if you manage to attack 2 times, crit both, then perform a Dodge, you will have gained 3+3+1 = **7 Flow Points** in a single round (although you would Decay 1 FP at the end of your turn as usual).  On average though a melee combatant cutting their way through a battle is likely to earn around 3 FP in a round barring any special abilities/effects. (2 successful attacks + 1 successful reaction)
## Flow Actions
There are MANY different Flow Actions that you can perform.  [[#Global Flow Actions|Some]] are available to everyone, [[#Flow Actions by Weapon Category|others]] are dependent on what type of weapon you wield.  Some will even be granted by various [[Perks|Perks]] or Class Abilities.
### Global Flow Actions
All characters have access to a small number of Flow Actions available regardless of your weapon category or any other feature.
#### Power Strike
**Cost**: 2 FP
**Effect**: +1 extra damage dice on next attack.  If for some reason the attack uses multiple different damage dice, you get +1 to the largest dice.  **This cannot be used to increase the damage dice of a Persistent Damage effect**
#### Guaranteed Critical
**Cost**: 3 FP
**Effect**: Your next attack roll automatically achieves a critical hit without rolling (consider your roll a 5 for the sake of ties, etc).  **This critical hit will not grant any FP**, otherwise you could loop endlessly (_Nice try_).
#### Perfect Defense
**Cost**: 2 FP
**Effect**: Your next Reaction automatically achieves a Normal Success without rolling (consider the roll equal to your Skill Level for the appropriate Skill, for the sake of ties etc). **This Reaction will not grant any FP**.  You can still earn 1 FP from a different Reaction in the round later.
#### Deflection
**Cost**: 3 FP
**Effect**: Redirect the damage of an attack you just Parried successfully onto a target adjacent to the attack, other than the attacker themselves.  **If you use this Flow Action, the successful Parry will not grant any FP**.  You can still earn 1 FP from a different Reaction in the round later.
### Flow Actions for 1h/2h
#### One-Handed Weapons
In addition to the Weapon Category Flow Actions, all 1-handed weapons also receive:
- **Combat Flow** (2 FP): Gain 1 AP this turn. Apply after a successful non-Reaction Attack once per round.
#### Two-Handed Weapons
In addition to the Weapon Category Flow Actions, all 2-handed weapons also receive:
- **Cleave** (2 FP): Deal half damage to one enemy adjacent to you **and** your target. Apply after any attack that deals damage.
	- For Ranged weapons, this is called "**Pierce**" and deals half damage to one enemy _directly behind_ your target.
### Flow Actions by Weapon Category
Refer to the [[Weapon Categories]] page for a detailed look.