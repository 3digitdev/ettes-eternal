# Stats

- **Hit Dice:** d10
- **Weapon Proficiencies**: Bow OR Crossbow (pick one), plus 1 of your choice
- **Armor Proficiencies:** Light

# Class Equipment

_Pick two at character creation_

- **Quiver of returning**: arrows return after missing targets
- **Quiver of accuracy**: after rolling attack, can add +10 to hit, 1/day
- **Phase arrows**: 3 arrows that ignore 2 points of DR
- **Hunter's mark arrows**: 3 arrows that glow when they hit target, making them easier to track
- **Splitting arrowheads**: 3 special heads that cause arrow to hit two adjacent targets; damage is split

# Core Features

|Level|Feature|Description|
|---|---|---|
|1|Hunter's Mark|Mark targets for sustained accuracy advantage|
|2|Field Crafting|Learn and deploy traps for free each day|
|3|Specialized Ammunition|Craft special arrows with ongoing damage effects|
|4|Environmental Advantage|Inject environmental features for party advantage|
|5|Path Selection|Choose path; Journeyman Class Tier|

### Hunter's Mark

**Cost:** 2 AP  
**Effect:** Choose a target within line of sight to Mark. You gain Advantage on your first ranged attack each round against your Marked target.  
**Duration:** Until you Mark a new target, the Marked target dies, you lose line of sight to the Marked target, or you voluntarily cancel the Mark (free action).  
**Limitation:** You can only have one Marked target at a time.

Once you Mark a target, you can sense its general direction and approximate distance for 1 hour after losing line of sight.

### Field Crafting

You gain access to all [[Traps#Apprentice Traps|Apprentice Traps]] and may craft and deploy each known trap for free up to your daily limit below. You may still craft any number of traps in a day based on time and materials; this ability gives you a number of free crafts each day. You also gain a +5 to Survival when deploying traps to determine spot/disarm/resist difficulties.

As you advance in Hunter Class Tier, you gain access to higher tier traps automatically:

|Class Tier|Free Traps/Day|Trap Access|
|---|---|---|
|Apprentice|2|Apprentice|
|Journeyman|3|Journeyman|
|Expert|4|Expert|
|Master|5|Master|
|Legendary|6|Legendary|

### Specialized Ammunition

Once per day, you can craft a number of special arrows/bolts based on your Hunter Class Tier. When crafting, choose any ongoing damage effect (Bleed, Fire, Ice, Shock, Poison, Acid) for all arrows. When making a ranged attack, you may declare you're using a special arrow before rolling — on a successful hit, the target takes ongoing damage equal to {Level÷2} per round.

|Class Tier|Arrows/day|
|---|---|
|Apprentice|3|
|Journeyman|5|
|Expert|7|
|Master|9|
|Legendary|12|

### Environmental Advantage

Twice per day, when the GM is describing your surroundings, you may inject some feature of the environment (not people or objects, and must be within reason) that would provide your party some advantage in the situation. For the duration of the scene, if any ally can describe how they take advantage of this environmental feature (must spend 1 additional AP in Combat) they can gain Advantage on their applicable roll while doing so.

## Path Selection (Level 5)

At Level 5, Hunters must choose their specialization path:

- **Ambusher Path** specializes in turning any environment into a killing ground through pre-planned trap deployment, grenade weapons, and ambush initiation. They excel at battlefield control, preparation, and striking before enemies can react.
- **Pathfinder Path** specializes in wilderness expertise, natural tracking, and environmental mastery. They excel at working with animals, and navigating untamed lands.

---

## Ambusher Path

|Level|Feature|Description|
|---|---|---|
|5|Trap Grenadier|Craft traps as thrown grenade weapons|
|6|First Strike|Advantage on Initiative when undetected; bonus damage against enemies who haven't acted|
|7|Zero In|Grenade throws at Marked target cannot deviate|

### Trap Grenadier

During downtime crafting, when preparing your free daily traps via [[Hunter_#Field Crafting|Field Crafting]], you may designate any of them as grenade versions instead of placed traps. Grenades and placed traps draw from the same daily pool. A grenade version of a trap costs the same materials and cannot be converted back to a placed trap once crafted.

In combat, throwing a grenade costs 3 AP and targets any hex within 5 hexes, following standard [[Grenade Weapons|Grenade Weapon]] rules. Grenade traps activate on landing regardless of the placed version's trigger type. Your **Ranged skill roll** replaces the normal Survival roll for the purposes of setting detection, disarm, and resistance difficulties.

Traps deployed as grenades are limited to one tier below your current Hunter Class Tier:

|Class Tier|Maximum Grenade Tier|
|---|---|
|Journeyman|Apprentice|
|Expert|Journeyman|
|Master|Expert|
|Legendary|Master|

You are immune to the effects of any trap you personally craft, whether thrown or placed normally.

### First Strike

If you remain undetected by all combatants at the start of combat, you gain Advantage on your Initiative roll.

Additionally, your attacks against any enemy who has not yet taken a turn in the current combat deal bonus damage:

|Class Tier|Bonus Damage|
|---|---|
|Journeyman|+2|
|Expert|+4|
|Master|+6|
|Legendary|+8|

### Zero In

When throwing a grenade trap at the hex occupied by your [[Hunter_#Hunter's Mark|Marked target]], the throw cannot deviate regardless of your Ranged roll. Your Ranged roll still occurs normally for the purposes of setting resist, detect, and disarm difficulties.

---

## Pathfinder Path

|Level|Feature|Description|
|---|---|---|
|5|Animal Companion|Gain a loyal animal partner|
|6|Wild Empathy|Communicate with and influence animals|
|7|Pack Tactics|Coordinate attacks with animal companion|

### Animal Companion

Gain an animal companion. It acts on your initiative and can perform simple commands. See [[Animal Companions|Animal Companion]] rules for details on which animals you can choose and the mechanics of them.

If it dies, it can be resurrected with 3 uninterrupted days of meditation in nature.

### Wild Empathy

You can communicate basic concepts with any natural animal and make Influence checks (within reason) to request simple favors or information. Animals are generally friendly toward you unless threatened. **Note that animals are not inherently intelligent.**

### Pack Tactics

Your Animal Companion now provides Gang Up bonuses to your ranged attacks against targets it is threatening.

---

## 🚧 TODOs

- **Levels 8-12**: Core and path features for both Ambusher and Pathfinder paths are partially designed but not yet finalized. See design notes.
- **Grenade Weapon rules**: Define concrete rules for grenade weapons including deviation on miss, interaction with triggers, and any other edge cases. Trap Grenadier and Zero In depend on these rules being formalized.
- **Ranged Reaction Attacks**: Define whether and how Hunters (and other ranged combatants) can make Reaction Attacks with ranged weapons, and clarify Threat Range/Reach rules for ranged attackers. Consider adding a Combat Perk for this available to any ranged character.