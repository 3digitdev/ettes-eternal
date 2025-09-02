# Weapon Proficiency
In order to wield a weapon effectively, you must have Proficiency in it.  Each class starts with proficiency in a set of Weapon Categories, and you can take perks to gain proficiencies

If you attempt to wield a weapon you are not proficient with, you take a **-20 penalty** to your Combat Skill while wielding it.
# Weapon Categories
Weapons are organized into a set of "categories" representing all similar weapons of that type. What _exact_ weapon you use is up to you and your proficiencies; what category it belongs in belongs in a combination of common sense + GM judgement call.

Each Weapon Category has specific Flow Actions associated with it, as well as a set of Class Tier bonuses you gain as passive effects with that category, which stack on each other.
# Damage by Class Tier
All weapons follow the same tier progression for damage scaling:

| Class Tier | Damage Dice |
| ---------- | ----------- |
| Apprentice | 1           |
| Journeyman | 2           |
| Expert     | 3           |
| Master     | 4           |
| Legendary  | 5           |

--- 
# Melee Weapons
_Not all weapons in each category do all those damages.  Examples: A Club can't do Piercing damage, but a Morningstar can.  A Halberd can't do Bludgeoning damage, but a Quarterstaff can._

|  Category  | Damage (1h/2h) |    Reach     |  B  |  P  |  S  |
| :--------: | :------------: | :----------: | :-: | :-: | :-: |
|    Axe     |     d6/d10     |    1 hex     |     |     |  ✓  |
|   Brawl    |     d6/--      |    1 hex     |  ✓  |  ✓  |     |
|  Finesse   |     d6/d10     |    1 hex     |     |  ✓  |  ✓  |
| Improvised |     d6/d10     |    1 hex     |  ✓  |  ✓  |  ✓  |
|    Mace    |     d6/d10     |    1 hex     |  ✓  |  ✓  |     |
|  Polearm   |     d6/d10     | 1 hex/2 hex† |  ✓  |  ✓  |  ✓  |
|   Sword    |     d6/d10     |    1 hex     |     |  ✓  |  ✓  |

†_2h Polearms have a reach of 2 hexes_
## [[Flow System#Flow Actions|Flow Actions]] for 1h/2h Weapons
### One-Handed Weapons
In addition to the Flow Actions for their weapon category, all 1h weapons also receive:
- **Combat Flow** (2 FP): Gain 1 AP this turn. Declared after a successful non-Reaction Attack once per round.
### Two-Handed Weapons
In addition to the Flow Actions for their weapon category, all 2h weapons also receive:
- **Cleave** (2 FP): Deal half damage to one enemy adjacent to you **and** your target. Declared after any attack that deals damage.
	- For Ranged weapons, this is called "**Pierce**" and deals half damage to one enemy _directly behind_ your target.

---
## Axe

### Flow Actions
- **Devastating Strike** (2 FP): Deal maximum damage.  Declared after Reactions to an attack are resolved.
- **Rending Strike** (3 FP): Target takes ongoing bleeding damage each round equal to minimum weapon damage from an average success.  Declared after rolling damage on an attack.
- **Whirlwind** (5 FP): Attack all enemies within your Reach. Each attack uses your full damage dice but at -10 accuracy.  Declared before rolling an attack. **No FP will be gained from this action**.
### Class Tier Bonuses
- **Journeyman:** Attacks ignore 2 points of enemy DR
- **Expert:** Adjacent enemies Frightened 1 round after Devastating Strike
- **Master:** Critical hits automatically trigger Devastating Strike effect for free
- **Legendary:** All attacks have 10% chance to trigger Rending automatically (roll 1d100 against a Target Number of 10)

---
## Brawl
### Flow Actions
- **Pressure Point** (2 FP): Target's physical damage output reduced by half until beginning of your next turn.  Declared after rolling damage for a successful attack.
- **Crippling Strike** (3 FP): Target loses 2 AP on their next turn.  Declared after rolling damage for a successful attack.
- **Weapon Turn** (5 FP): Force an enemy wielding a weapon to attack themselves or an adjacent ally of your choice using their own weapon and attack skill.  Declared at any time during your turn.
### Class Tier Bonuses
- **Journeyman:** Deal +2 damage to enemies suffering from any status effect
- **Expert:** Deal +5 damage to enemies at half health or less
- **Master:** Can counter-attack immediately after being hit (spend 1 RP to perform a Reaction Attack) once per round
- **Legendary:** Your attacks can grab and throw enemies - move target 2 hexes in any direction on hit.  Only affects targets your size category or lower.

---
## Finesse
### Flow Actions
- **Expose Weakness** (2 FP): Next ally attack on same target gets +4 damage bonus.  Declared after a successful damage roll.
- **Blade Dance** (3 FP): Immediately make a second attack at -20 accuracy against same or adjacent target.  Declared after an attack resolves, regardless of the result.
- **Precision Focus** (5 FP): When using this Flow Action, choose **one** effect: 
1. Gain Advantage on all attack rolls until the beginning of your next turn and deal normal damage
2. Gain Disadvantage on all attack rolls until the beginning of your next turn, but all successful hits are automatically Critical Hits.  
**No attacks made while Precision Focus is active will earn Flow Points.**
Declared at any time during your turn.
### Class Tier Bonuses
- **Journeyman:** Gain 1 FP when an ally you are Ganging Up with scores a critical hit
- **Expert:** Blade Dance second attack accuracy penalty reduced to -10
- **Master:** Expose Weakness grants allies +1 FP when they hit the marked target
- **Legendary:** All successful attacks grant +1 FP to adjacent allies

---
## Improvised
### Flow Actions
- **Unexpected** (2 FP): Your first attack with a newly picked-up improvised weapon gains +4 damage as opponents aren't prepared for your creative choice of armament.  Declared after picking up a new improvised weapon.
- **Breaking Strike** (3 FP):  Your weapon breaks after this attack, but the attack gains +1 damage die from the devastating impact of sacrificing your weapon.  Declared after Reactions are resolved for a successful attack.
- **Improvised Fury** (5 FP): Make three improvised weapon attacks against any targets within reach. Each attack uses a different improvised weapon that you grab from the environment as part of the action. All weapons break after their attack regardless of success. This counts as a single action for escalating AP costs. _**Note:** These attacks do not benefit from Breaking Strike's +1 damage die bonus._  Declared at any time during your turn.  **These attacks do not gain FP.**
### Class Tier Bonuses
- **Journeyman:** Generate 1 FP when you pick up a new improvised weapon (once per weapon type per combat)
- **Expert:** When an improvised weapon breaks (from Breaking Strike or Improvised Fury), adjacent enemies take {Level÷2} damage from flying debris
- **Master:** The breaking damage debris also applies on all attacks that get a Major or Critical Success. (Critical Success will multiply the damage as usual)
- **Legendary:** Once per combat, you can use any improvised weapon as if it were a proper weapon of your choice from any category.  The weapon keeps its improvised damage dice but gains that chosen weapon category's Flow Actions until the beginning of your next turn.  **This includes Shields.**

---
## Mace
### Flow Actions
- **Stunning Blow** (2 FP): Target loses 1 AP and is Stunned next turn.  Declared after rolling damage for a successful attack
- **Crushing Blow** (3 FP): Attack ignores all armor.  Declared after Reactions are resolved.
- **Shockwave** (5 FP): Strike the ground. All enemies within 3 hexes must make Agility checks or be knocked Prone and take half weapon damage.  Declared at any time during your turn.  **No FP will be earned during this action.**
### Class Tier Bonuses
- **Journeyman:** Deal +2 damage for each enemy you've killed this combat
- **Expert:** Stunning Blow causes target to lose 2 AP instead of 1
- **Master:** Critical hits automatically apply Stunning Blow effect for free
- **Legendary:** Once per combat, any one attack can target all enemies adjacent to you

---
## Polearm
### Flow Actions
- **Control Strike** (2 FP): Choose to either trip target or push back 10 feet.  Declared after rolling damage for a successful attack
- **Defensive Stance** (3 FP): Make Reaction Attacks against enemies moving through your reach zone.  Declared at any time during your turn.
- **Impaling Thrust** (5 FP): Attack an enemy up to 3 hexes away in a straight line. If successful, pull them adjacent to you and they're Restrained until they spend 2 AP to break free. Your weapon is unusable until they free themselves or you spend a free action to remove it.  Declared before rolling an attack.
### Class Tier Bonuses
- **Journeyman:** You cannot be flanked or surrounded - no Gang Up bonuses apply against you
- **Expert:** Reaction Attacks with polearms deal +3 damage
- **Master:** Defensive Stance lasts until end of next turn instead of just next turn
- **Legendary:** 3/day, can attack all enemies in a 3-hex line within Reach 2

---
## Sword
### Flow Actions
- **Flowing Counter** (2 FP): After successfully parrying, next attack costs 1 less AP.  Declared immediately after parrying.
- **Steal Momentum** (3 FP): Target loses 1 AP next turn, you gain 1 AP this turn.  Declared at any time during your turn.
- **Blade Barrier** (5 FP): Until start of your next turn, any enemy that enters a hex adjacent to you takes weapon damage automatically. This is treated as a Normal Success for Opposed Reactions. Each enemy can only trigger this once per round.  Declared at any time during your turn. **These do not count as attacks and you cannot gain FP from killing blows from this**
### Class Tier Bonuses
- **Journeyman:** Start each combat with +1 RP
- **Expert:** Parrying an attack lets you immediately move 1 hex without provoking reactions
- **Master:** Steal Momentum causes one adjacent enemy to also lose 1 AP
- **Legendary:** You gain 2 FP from first Reaction Attack per round

---
# Ranged Weapons

|      Type      | Damage |  Range   |  B  |  P  |  S  |
| :------------: | :----: | :------: | :-: | :-: | :-: |
|    Shortbow    |   d8   | 6 hexes  |     |  ✓  |     |
|    Longbow     |   d8   | 12 hexes |     |  ✓  |     |
| Hand Crossbow  |   d6   | 4 hexes  |     |  ✓  |     |
|    Crossbow    |   d8   | 6 hexes  |     |  ✓  |     |
| Heavy Crossbow |   d8   | 12 hexes |     |  ✓  |     |

---
## Bow
### Flow Actions
- **Pin Shot** (2 FP): Target cannot move more than 1 hex per AP until freed by spending 2 AP.  Declared after Reactions are resolved for an attack.
- **Called Shot** (3 FP): Target specific body part, gain +5 to hit, choose effect (Disarm/Blind/Halve movement).  Declared before rolling an attack.
- **Seeking Shot** (5 FP): Your next shot automatically achieves Normal Success and curves around cover/obstacles. Target can not Dodge this attack.  Declared before rolling an attack.  **This attack does not gain FP**.
### Class Tier Bonuses
- **Journeyman:** Pin Shot also reduces target's AP by 1 next turn
- **Expert:** Each arrow sticks in target for 1 damage each when they move; 1 AP to remove all arrows
- **Master:** Called Shot effects last 2 rounds instead of 1
- **Legendary:** Once per combat, your attack deals 10 Persistent Bleed; can only remove with extended care

---
## Crossbow
### Flow Actions
- **Hard To Predict** (2 FP): Dodging this attack requires 1 extra RP than normal.  Declared before rolling an attack.
- **Perfect Shot** (3 FP): Increases the success level of your attack by one tier.  Declared before Reactions are rolled.
- **Rapid Volley** (5 FP): Fire up to your Ranged Modifier bolts at the same target. Take -10 accuracy for each bolt beyond the first. Roll damage separately for each hit.  Declared before rolling an attack.  **These attacks do not gain FP**.
### Class Tier Bonuses
- **Journeyman:** Critical hits with crossbows knock enemies prone from impact force
- **Expert:** Can aim for 2 extra AP to guarantee at least Normal Success
- **Master:** Missing with crossbow grants stacking +5 to hit until you succeed
- **Legendary:** 3/day your attack hits one enemy directly behind within range for full damage
