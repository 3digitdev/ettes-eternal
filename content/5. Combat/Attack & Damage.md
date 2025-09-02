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
See [[6. Magic/index#Casting Spells|Casting Spells]] for a detailed look at how this works
## "Automatic" Successes
Whenever something states that you gain an "automatic" success of a specified level, then for the sake of numbers you should consider your "roll" for that check to be _exactly_ the number you need to achieve that result. 
**Examples:**
- If an ability gives you an "automatic" Major Success, and your Melee Skill is 64, then your roll would be considered a 16; exactly ¼ of your Skill.
- If an ability gives you an "automatic" Critical, and due to the **Critical Focus** Perk, you have ≤8 as your critical range, then your "roll" would be considered an 8; exactly enough to achieve a Crit.

---
# Damage
What you roll for damage is highly variable. However, there are 3 different sources that can modify your damage roll for any given attack or spell.
## Bonus Damage Sources
### Bonus Damage Dice
You gain bonus damage dice on all weapon and spell attack damage as a result of your [[3. Classes/index#Class Tier System|Class Tier]]]. The progression, repeated here:

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
- **Hard Success**: +1 damage
- **Major Success**: +2 damage
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