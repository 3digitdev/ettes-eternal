# Introduction
This document provides guidelines for converting Ettes Eternal from its hex-based tactical combat system to a Theatre-of-the-Mind (TOTM) approach using range bands. The original system was designed around precise positioning for tactical depth, so this conversion requires significant modifications to core mechanics.

The range band system abstracts exact positioning while maintaining the strategic elements of combat. Players and GMs focus on narrative positioning and general distances rather than counting hexes. This approach speeds up combat resolution while preserving most of the system's tactical options.

Some mechanics that depend heavily on precise positioning will be removed or significantly altered. The core action economy, Flow Point system, and most class abilities remain intact with minor modifications.

**Please note, that with this conversion, some abilities WILL become more powerful by nature.**

---
# Range Increments
The system uses five range bands to represent relative distances between characters and objects:

**Adjacent/Engaged**: Characters are in immediate physical contact or within arm's reach. Melee attacks, grappling, and close-quarters actions occur at this range. Moving out of Engaged range provokes Reaction Attacks unless using specific abilities.

**Short Range**: Close proximity, roughly equivalent to 1-6 hexes in the original system. Characters can easily communicate without raising voices and can close to Engaged range with a single movement action. Most thrown weapons and some spells work optimally at this range.

**Medium Range**: Moderate distance, equivalent to 7-12 hexes. Normal conversation requires raised voices. Characters need to spend significant movement to close to melee range. Many ranged weapons and spells function well at this distance.

**Long Range**: Substantial separation, equivalent to 13-18 hexes. Shouting is required for communication. Only ranged attacks and long-distance spells can effectively target at this range. Multiple movement actions are needed to close distance.

**Extreme Range**: Maximum interaction distance, equivalent to 19+ hexes. Communication is nearly impossible without magical or technological aid. Only specialized long-range weapons and spells can reach targets at this distance.

---
# Movement in Range Bands
Movement in the Theatre-of-the-Mind system uses the same Action Point costs as the hex-based system, but instead of moving a specific number of hexes, characters move between range bands.

- **Basic Movement**: Spending 1 AP on a Move action allows a character to move to an adjacent range band (closer or farther). For example, a character at Medium Range can move to Short Range or Long Range with a single Move action.
- **Sprint Action**: Spending 2 AP on a Sprint action allows movement across two range bands. A character could move from Long Range directly to Short Range, or from Engaged to Medium Range.
- **Maximum Movement**: The 2 AP per turn movement limit remains in effect. Characters cannot spend more than 2 AP on movement actions during their turn, maintaining the tactical constraint of choosing between movement and other actions.
- **Taking a Step**: This free action allows movement out of Engaged range to Short Range without provoking Reaction Attacks, or repositioning within the same range band for tactical advantage.
- **Narrative Positioning**: Within each range band, the GM and players can describe specific positioning for narrative purposes without mechanical effect. Being "behind cover at Medium Range" or "flanking at Short Range" adds tactical flavor without requiring precise hex counting.

---
# Converting Ettes Eternal
## Removed/Broken
The following mechanics are fundamentally incompatible with range band abstraction and are removed from TOTM play:
- **Combat Perks**: 
	- Battle Dance (1 hex movement after attacks becomes meaningless)
	- Acrobat (moving through enemy spaces has no equivalent)
	- Enhanced Reactive Roll (1-hex movement is too granular)
	- Fleet (+2 hexes movement speed has no range band equivalent)
- **Special Actions**: 
	- Tumble Through (moving through enemy hexes cannot be represented abstractly)
- **Core Concepts**: 
	- Reach mechanics for weapons (Reach 2 weapons lose their extended threat range)
	- Precise threat zones for Reaction Attacks
- **Animal Companion Abilities**:
	- Arm Reach for Apes (attacking at exactly 2 hexes has no range band equivalent)
## Converting Effects
### Combat Mechanics
- **Gang Up Bonuses**: Instead of requiring allies to threaten from adjacent hexes, Gang Up applies when 2 or more characters are Engaged with the same enemy. This simplifies positioning while maintaining the tactical advantage of coordinated attacks.
- **Knockback and Forced Movement**: Effects that push, shove, or forcibly move **adjacent targets 1 hex away** now move them out to Short Range.  Anything that moves targets further, or not adjacent (such as spells) should be handled using [[#Distance Conversions]] rules.
- **Adjacency Requirements**: Any mechanic referring to "adjacent" targets or "1 hex away" now applies to targets within the same range band. For most combat effects, this means characters who are Engaged with each other or the same enemy.
- **Taking a Step**: This free movement action becomes the ability to move out of Engaged range without provoking Reaction Attacks. Characters can reposition within the same range band or move to an adjacent range band safely once per turn.
- **Reaction Attack Triggers**: Reaction Attacks are provoked when enemies move out of Engaged range, regardless of their destination. This maintains the tactical importance of positioning while simplifying trigger conditions.
- **Creature Size Categories**:  Translating size categories for enemies are generally a difficult proposition without having "relative" Ranges which becomes impossible to track for the GM.  As a result, our official recommendation is to avoid worrying about this too much.  One suggestion is for the GM to rule that Reaction Attack Triggers get expanded for Large/Huge creatures to allow triggering on some amounts of movement within Short Range, rather than just Engaged Range.
### Perks
- **[[Combat Perks#Charge|Charge]]**: The condition for this Perk's effect for this is now "if you moved from Short or further range into Engaged with an enemy before attacking"
### Flow Actions
- **[[Weapons#Finesse|Blade Dance]]** (Finesse Flow Action): The second attack can target either the same enemy or a different enemy that is Engaged with you, rather than specifically targeting adjacent hexes.
- **[[Flow System#Deflection|Deflection]]** (Global Flow Action): Redirected damage affects a different target who is Engaged with the original attacker, rather than specifically adjacent targets.
- **[[Flow System#Global Flow Actions|Cleave/Pierce]]** (2h Weapons): Secondary damage affects enemies Engaged with the primary target (Cleave) or a different enemy at the same range as the primary target (Pierce).
- **[[Weapons#Polearm|Control]]** (Polearm): Push effects move targets from Engaged to Short Range instead of "back 10 feet."
- **[[Weapons#Defensive Stance|Defensive Stance]]** (Polearm): This ability is replaced with a new effect:
	- **Defensive Stance** (3 FP): Grants Reaction Attacks against any enemy who moves **into** Engaged range with you.
### Class Abilities
#### Fighter
- **[[Fighter🚧#Castle|Castle]]**: The position-swapping range converts based on tier level. Apprentice/Journeyman (2-3 hexes) becomes Short Range, Expert/Master (4-5 hexes) becomes Medium Range, Legendary (6 hexes) becomes Medium Range.
#### Barbarian
- **[[Barbarian#Intimidating Presence|Intimidating Presence]]**: Fear effects apply to **up to 3 enemies** within Short Range (instead of "within 2 hexes").
#### Hunter
- **[[Hunter🚧#Environmental Advantage|Environmental Advantage]]**: Effects apply to the current scene's range band rather than specific hex positioning.
#### Rogue
- **[[Rogue🚧#Setup Strike|Setup Strike]]**: Gang Up bonuses apply to all allies Engaged with the same target until the start of your next turn.
### Animal Companions
#### Movement
Free movement allows companions to move between adjacent range bands once per round.
#### [[Animal Companions#Large Cat|Large Cat]]
- **Pounce** (Large Cat): Allows movement of one range band combined with an attack in a single command, rather than the specific 3-hex movement limitation.
- **Swipe** (Large Cat): Secondary damage affects a different enemy that is Engaged with the same target, representing the sweeping claw attack affecting nearby foes.
#### [[Animal Companions#Boar|Boar]]
- **Charge Attack** (Boar): Bonus damage applies when the companion moves at least one full range band before attacking, rather than requiring exactly 4 hexes of movement.
#### [[Animal Companions#Bear|Bear]]
- **Bear Hug** (Bear): Grappling mechanics remain unchanged as they don't depend on precise positioning.
#### [[Animal Companions#Wolf|Wolf]]
- **Trip Attack** (Wolf): Knockdown effects remain unchanged as they affect individual targets.
### Distance Conversions
Abilities affecting targets within 1-6 hexes become Short Range, 7-12 hexes become Medium Range, 13-18 hexes become Long Range, and 19+ hexes become Extreme Range.

Generally, if an effect would move an enemy a multiple of 6 hexes, you can assume the effect is allowed to move them between Short/Medium/Long/Extreme range.
## AoE Effects
Area-of-Effect abilities are one of the hardest things to get right in Theatre-of-the-Mind combat.  We will attempt to describe here a set of **guidelines**, but in the end this can be highly situational, and GMs are encouraged to use best judgement at the moment if they think the situation doesn't line up with these guidelines, one way or the other.
### Player Intent
First, it's important to remember that in the end interpretation has to come down to kind understanding of player intent.  If a player is trying to cast fireball, it can be **generally** assumed that the player:
1. Wants to hit as many enemies as they possibly can
2. Would like to avoid hitting their allies
So without any other guidance, you should be aiming to help describe them achieving these goals.  If the player indicates otherwise, then work with them **within reason** to achieve their intended results.

**PLAYERS**: As a player, you also need to communicate with the DM in order to make sure you can position your spell to not hit allies if needed.  The GM may limit the number of enemies by deviating from the guidelines below, if they decide you must sacrifice some area of effect to avoid friendly fire.
### Converting AoE Templates
In Ettes Eternal, there are 3 AoE templates: **Blast**, **Cone**, and **Line**.  Each has a number value associated with it to represent size.  In general, here's how you can interpret them:
#### Blast
Since the number value represents a radius for Blast, these tend to be the spells that hit the most targets.  For Blast, every **2 radius increment**, you roll a 1d4 to determine how many enemies you hit.  So for Blast 1 or Blast 2, you roll 1d4.  Blast 3/4, you roll 2d4, etc.
#### Cone
Since the number represents a distance from the player, and the cone width grows with distance, these tend to hit the second-most targets.  As a result, follow this template:
- **Cone 2**: You hit 1 target, unless you position really well
- **Cone 3-4**: You hit 1d3 targets
- **Cone 5-6**: You hit 2d3 targets
- **Cone 7+**: GM discretion;  These effects will be very rare.
#### Line
Since the number represents simply the length of the 1-hex-wide line, these tend to hit far fewer enemies, but can also be the most variable depending on the situation.  As a general rule, every **3 length** of the line, you should hit **1 additional enemy**: therefore, **Line 2-3** hits 1 enemy, **Line 4-6** hits 2 enemies, etc.  This may seem low, but realistically in a combat, perfect lines of multiple enemies can be quite rare.  As always, GM discretion overrides this if they choose.
## Spell Targeting
Most of spell targeting is handled via either "touch" (which translates easily to Engaged Range), or a distance + line-of-sight.  In this case, the general rule should be that at Short Range, you have basically guaranteed line-of-sight.  When you reach Medium or Long Range, line-of-sight may be less guaranteed, and at Extreme+ Range, line-of-sight should be much more difficult in the average combat setting.  Since line-of-sight is so variable and dependent on the combat situation, we cannot provide better guidelines for GMs beyond this.