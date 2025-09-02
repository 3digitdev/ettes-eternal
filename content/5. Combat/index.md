---
title: 5. Combat
description: The basic rules of combat
---

# Round Resolution Cheat Sheet
## Round Structure
1. **Initiative Order**: Characters act in order determined by Initiative result
2. **Sequential Actions**: Each character declares one action, resolves it, then decides next action
3. **Reaction Interruptions**: Reactions can interrupt the active character's turn when triggered
4. **Round End**: "End of round" effects resolve, and new round begins; *same initiative order*
## Individual Turn Sequence
1. **Declare action** and spend AP
2. **Resolve action** (including any triggered reactions)
3. **Repeat** until AP exhausted or player chooses to end turn
4. **Ongoing effects resolve** (bleeding, poison, etc.)
5. **FP decay**: Lose 1 FP (unless Flow State was used)
6. **Next character's turn**

---
# Actions/Turn Cheat Sheet
- 5 AP per round
	- 2 AP for attacks/spells; +1 AP escalation
	- 1 AP per Move Speed; maximum 2 AP/turn
	- 1-2 AP for various actions
- 2 RP per round
	- Dodge/Parry/Block/Reaction Attack for 1 RP each
	- Riposte/Intercept for 2 RP each
- 2 FP at start of combat
	- Gain 2 FP from attacks that hit, 3 FP from crits
	- Gain 1 FP from a successful reaction (once per round)
	- Gain 1 FP from a killing blow on an enemy combatant
	- Lose 1 FP per round at end of turn

---
# Action Economy
The combat system is based on an Action Economy, with various actions taking certain types of action Points _(described further below)_:
- **[[#Actions|Action Points (AP)]]** - used for most normal actions such as attacking, casting spells, etc.
- **[[_Combat#Reactions|Reaction Points (RP)]]** - used for acting on another creature's turn to react to something, such as dodging an incoming attack, etc.
- **[[Flow System|Flow Points (FP)]]** - used for special types of combat abilities that vary depending on character, weapon, etc.
You character will start each round/combat with a number of each of these, and gain/lose them by performing actions.
## Actions
Your primary action type are just "Actions".  These are things you do in combat that will cost **Action Points (AP)**.  

Every player starts each round of combat with **5 AP**.  Any unused AP at the end of your turn is forfeited; there is no banking or saving up of AP.  Various abilities will cost AP.  It is possible to start a round with more than 5, or to gain additional AP throughout your turn/round thanks to various abilities.  There is not currently a limit to AP you can spend in a single round, provided you have the abilities to justify it.

**Common Actions and their costs:**
_(this is not an exhaustive list!)_
- Movement: 1 AP to move full [[1. Basics/index#Movement|Move Speed]]
- [[Attack & Damage|Attacking]]/[[6. Magic/index#Casting Spells|Casting a Spell]]: 2 AP
- Drawing/Sheathing an item: 1 AP each _(thus, 2 AP to switch weapons)_
- Drinking a potion from your bag: 2 AP _(1 AP to draw potion, 1 AP to drink)_
- Using a Magic Item: 1-2 AP _(specific to each item)_
## Reactions
Reactions are used for what they sound like; **reacting** to actions that don't happen on your turn.  Examples might include dodging an attack, or quickly attacking someone as they cast a spell/run away

Every player starts combat with **Full RP** (usually 2, unless abilities grant more).  Players regain their RP **at the start of their turn** after combat is underway. It is possible to gain more starting RP through various abilities/spell effects, or to gain RP temporarily for a round via similar effects.  There is not currently a limit to RP you can spend in a single round, provided you have the abilities to justify it.

**You may not perform multiple Reactions against a single attack, unless performing a [[#Riposte|Riposte]]**
### Basic Reactions & costs
_(there are more abilities that work as Reactions, with their own costs, but the following list is available to all characters from Level 1, regardless of build)_
- **Dodge**: 1 RP to roll Agility to avoid a melee or ranged attack
- **Parry**: 1 RP to roll Melee to deflect another melee attack
- **Block:** 1 RP to roll Endurance to block a melee or ranged attack; _requires a shield_
- **Reaction Attack**: 1 RP to roll a single unmodified attack against an enemy who performs a triggering action within range; _many abilities refer to Reaction Attacks in their effects; this is what they refer to._
- **Riposte**: 2 RP to Parry and immediately counterattack on success
- **Intercept**: 2 RP to move up to 3 Hexes and roll Agility to take an attack for an ally; _does not require a shield_
### Reaction Attacks
Reaction Attacks are a special attack that can be used to disrupt or punish enemies for taking an action that distracts them from your fight.  These can include things like moving out of a hex, spellcasting, standing up from prone, or other actions.  These actions only provoke **Reaction Attacks** if they happen within your [[#Threat Range|Threat Range]].

For the sake certain abilities, **Reaction Attacks** are a special type of attack.  Many abilities may explicitly single out or _exclude_ Reaction Attacks from their effects.  Refer to the text of each ability for that.  **If not overtly excluded, you may assume that Reaction Attacks are included in the effect if it talks about "attacks"**
#### Reaction Chains
When a Reaction attack is performed, the defending player still has the ability to react to that attack as normal.  In this situation, if the defending player still has RP left, **you can still Dodge/Parry/Block** as normal, but you **cannot** perform any advanced Reactions; that is, you cannot Riposte or similar.  **Reaction Attacks cannot trigger new attacks in response.**
### Dodge/Parry
When an attack of the right type would succeed against you, you may spend 1 RP to attempt any of these abilities in order to avoid taking damage from the attack.  Each is either an **Agility** (Dodge) or **Melee** (Parry) Skill Check.  Treat this check as an [[1. Basics/index#Opposed Checks|Opposed Check]] against the attacker's attack Skill Check, and resolve as normal.  **If you win the Opposed Check, then the attack does no damage to you**, unless another rule would state otherwise.
#### Critical Results
If you **critically succeed** at your Dodge/Parry roll, as long as the enemy attack was not also a critical success, **you regain the 1 RP you spent on the Reaction**.

Additionally, in the very rare case where a critical hit happens and a Dodge/Parry then **critically fails**, this is an extreme result that actually amplifies the damage taken.  Instead of just dealing 2x damage,  The critical hit will instead deal **3x damage**.
#### Parrying Large Creatures
When a large creature attacks a smaller one (Huge > Large > Medium > Small), the larger attacker is considered to be 1 success level higher for the sake of resolving the Opposed Check between the attack and the Parry.  **You cannot parry an enemy more than 1 size category larger than you**. Example:  A Large creature rolls a Normal Success attacking a Medium creature, who rolls a Normal Success on the Parry.  The Large creature is considered to be a Hard Success for the sake of resolving the Opposed Check, and so the Large creature's attack hits, but deals damage as a Normal Success.
### Riposte
This is a one-two combo of a **Parry** (Riposte) followed by a **Reaction Attack** with your melee weapon.  Resolve the action as a combination of these two, with the Reaction Attack being possible only if the Parry succeeds first.  **If an ability would affect Reaction Attacks, it also affects Riposte.**  This ability is special in that it lets you effectively do 2 reactions against a single attack.
### Intercept
This is a special reaction that can allow you to take a physical attack from an enemy in place of a nearby ally.  If it is a melee attack, you first must be within **3 hexes** of your ally **and** the attacker. Put simply: if you cannot move to be adjacent to BOTH of them with 3 hexes of movement, **you may not perform Intercept**.  For ranged attacks, you must be able to stand **directly between your ally and the attacking enemy** within 3 hexes.  If you can not do this using 3 hexes of movement, **you may not perform Intercept**.

Once you have moved to **Intercept**, you must make an **Agility** Check against their attack as an [[1. Basics/index#Opposed Checks|Opposed Check]], and resolve as normal.  **If you win the Opposed Check**, you take the **full damage** of the attack from the enemy, and your ally takes no damage.  No other reactions may be used as a result of this, and normal damage rules still apply.

**Additionally**, you may optionally choose to move your ally 1 hex away from your movement direction, and take their place (even if this extra hex of movement is above the 3 hexes from your Intercept)
## Special Actions

| Action         | Cost | Effect                                                          |
| -------------- | ---- | --------------------------------------------------------------- |
| Disarm         | 2 AP | Force an opponent to drop an item nearby                        |
| Draw/Sheathe   | 1 AP | Draw or stow a weapon or item                                   |
| Feint          | 1 AP | Fake an attack to gain Advantage                                |
| Flow State     | 1 AP | Retain all FP at the end of your turn; no FP decay              |
| Grapple        | 2 AP | Wrestle to restrain an opponent                                 |
| Ready Action   | ---- | Define a trigger for when you'll take a specified future action |
| Shove          | 1 AP | Knock an opponent backwards or to the floor                     |
| Take a Step    | 1 AP | Move 1 Hex without provoking Reaction Attacks                   |
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
**Cost:** 1 AP
**Mechanic:** Make an opposed Melee or Deception roll vs target's Melee or Agility (target's choice).
**Restriction:** Usable once per round.
**Effect:** On success, your next attack against that target gains Advantage.
### Flow State
**Cost:** 1 AP
**Effect**: Retain all [[#Flow Points]] at the end of your turn, skipping the normal FP decay.  This is essentially just trading 1 AP for that 1 FP next round.
_NOTE: This is a great choice if you have 1 AP left on your turn and nothing else to do!_
### Grapple
**Cost:** 2 AP  
**Mechanic:** Opposed Athletics roll vs target.  
**Restrictions:**  You can only Grapple targets that are your size category or smaller
**Effect:** On success, both characters are grappled.
**Effects While Grappled:**
- **Attacker:** Must spend 2 AP per round to maintain the Grapple; can make reasonable actions (GM discretion) at Disadvantage
- **Defender:** Cannot take actions except one Opposed Athletics check per round to break free
- **Movement:** Neither can move independently
- **Duration:** Until defender wins Athletics contest or the effect is broken or ended
### Ready Action
**Cost:** N/A
**Effect:** Define a specific trigger condition and choose an action to take when that trigger occurs. When the trigger happens, you act immediately at that point in the initiative order. Your initiative position moves to that point for subsequent rounds.  If a trigger does not happen before the end of the round, then you may choose to either continue waiting or cancel the Readied Action at no cost.

***Example Triggers:** "When an enemy enters my reach," "When the wizard starts casting," "When the door opens"*
### Shove
**Cost:** 1 AP
**Mechanic:** Opposed Athletics roll vs target.
**Restrictions:**  You can only Shove targets that are your size category or smaller.  Usable once per round.
**Before Rolling:** Choose either Push Back OR Knock Prone.
**Success Results:**
- **Normal Success:** Achieve chosen effect (push back 1 hex OR knock prone)
- **Hard Success+:** Can choose to do both effects (push back 1 hex AND knock prone)
### Take a Step
**Cost**: 1 AP
**Restriction:** Usable once per round
**Effect**: You move 1 Hex of movement, without triggering any Reaction Attacks or other abilities triggered by movement.  This does not count against your movement maximums for the round (you may still spend 2 further AP to move twice).
### Total Defense
**Cost:** 3 AP (ends turn immediately)
**Effect:** Gain +1 RP and Advantage on all Reactions until the beginning of your next turn.
### Tumble Through
**Cost**: 1 AP
**Requirement**: Adjacent to an enemy
**Effect** You make an **Agility Check**.  If you succeed, you can move directly through the enemy's Hex to the other side of them without provoking **Reaction Attacks** from any enemy.  If you **fail** your **Agility Check**, you must stay where you are, and this attempted action will provoke **Reaction Attacks** from _only the enemy you attempted this on_, and not any other adjacent enemies.
**Notes:**
- You can attempt this in the MIDDLE of Move Action.  The extra hexes do not count toward your movement for that Action.
- **Tumble Through** can NOT be used against enemies larger than Medium size, as it only provides you with a single Hex of reaction-free movement.
## Free Actions
Free actions are things you can perform without spending any type of action point.  These are considered quick or trivial actions not worth keeping track of.  **Please keep Free Action use in combat to a reasonable amount; Talking is a Free Action, but you still only have ~6 seconds per round**.  We leave it up to GMs and players to decide what is a reasonable limit.

**Example Free Actions**:
_(this list is not exhaustive!)
- Making a Knowledge Skill Check
- Speaking/yelling something
- Dropping something to the ground
- Operating a small object
- Opening a door

---
# Initiative
1. Everyone rolls 1d10 + Agility [[4. Skills/index#Skill Modifiers|Modifier]]
2. Initiative proceeds from highest to lowest roll
3. Ties are resolved [[1. Basics/index#Resolving Ties|as normal]]
## Surprise Attacks
Surprise Attacks happen when one side of a potential combat gets the drop on the other.  This can happen through a variety of ways, but is primarily done when one party is unaware of the other.

Surprise attacks are simply 1 round of combat resolved normally, but only the surprising party may act in that round.

First, roll initiative for everyone (even the surprised party).  The _surprising_ party gets their free 2 FP at the start of combat in this Surprise Round.  **The surprised party starts the Surprise round with 0 AP, 0 RP, and 0 FP** (they get their 2 free FP at the start of the first normal round of combat)

Resolve the Surprise Round as a normal round of combat other than these rule exceptions above.  Once the surprising party has all taken a turn, then combat proceeds as normal following initiative order.  _This can mean that high-rolling surprisers will get multiple turns before the enemy gets one!_

---
# Movement 
## Movement In Combat
**The battle map for combat in the system operates on a ~5 ft (~2 m) hex grid.**

Unless stated otherwise, all player characters start with **6 hexes** of movement per [[#Actions|Action Point]] spent.  The most a player can move per round is 2 AP worth of movement (~12 hexes), plus an additional Hex of movement from **Take a Step** for a total of 13 hexes.

As a round of combat is normally about 6 seconds, this translates to roughly 7 mph (3 m/s) which is running speed for an average human.

You can move through allies' hexes for free with no penalties, but you cannot move through an enemy hex unless you attempt to [[#Tumble Through]].  You may not end your movement in the same square as any other enemy or ally.
### Taking a Step
A Special Action that can be taken **once per round**, "**Taking a Step**" is the ability to move 1 hex in any direction without provoking Reaction Attacks from adjacent enemies who [[#Threat Range|threaten]] you.  This does not count towards your Move Speed for the sake of Move Actions.
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
# Combat Mechanics
## Gang-up
When 2 or more allies are threatening the same enemy, they are ganging up and gain a +10 Melee bonus to attacking that enemy.
## Firing into Melee
You're all competent adventurers. Firing into melee does not incur penalties, but critical fumbles might get interesting...
## Two-Weapon Fighting
In general, attacking with your non-dominant hand will yield a -10 to your Melee skill on attack.  **Finesse and Brawl weapons do not have this penalty**.  There is a [[Combat Perks#Dual Wield|Perk]] to remove this detriment entirely.
#### A Note on TWF
_Yes, you're correct in realizing there's absolutely no base mechanical benefit to dual-wielding the same weapon category (dual daggers).  That's because **it's BORING to do that**.  Get **creative** if you want to dual-wield!  Wielding 2 weapon categories means more options for Flow Actions!  Sword/Fist; Dagger/Sap (Mace); Axe/Hand Crossbow! Get CRAZY!_
