In Ettes Eternal, some characters are able to craft Traps in order to ensnare enemies both in combat or with well-prepared setups they lead the enemies into. **Hunters** especially gain a lot of class benefits for dealing with traps.

# Core Mechanics

## Crafting

Every trap is crafted using an abstracted concept of "Trap Materials", which are defined as such for simplicity of not micromanaging how many spikes or hooks or nets you happen to have. You can purchase **Trap Materials** in the [[Gear & Services#Toolkits|Gear]] section. Trap Materials are consumed upon crafting the trap, and generally cannot be recovered.

Traps generally have a **crafting time** of ~10 minutes per Tier. There are, like many other parts of Ettes Eternal, five Tiers of traps; Apprentice through Legendary.

## Usage

Placing any trap, whether in combat or not, requires a **Survival Check** to successfully place the trap. This roll will also set a difficulty for resisting, detecting, or disarming the trap (as an [[1. Basics/index#Opposed Checks|Opposed Check]]).

If you fail your **Survival Check** to place the trap, **the trap is wasted, along with the materials to craft it**.

## Activation

Traps have 4 primary **Activation Triggers**, which are pretty straightforward:

1. **Manual** - the trap only activates if the trap-setter personally performs an action to trigger it (_generally 1 AP if in combat_)
2. **Contact** - the trap activates when a creature touches the trap.
3. **Timed** - some kind of rudimentary fuse or timer is set with the trap and it goes off when that timer ends. This is most common with things like grenade-like traps.
4. **Magical** - This is much more general and will vary on meaning case-by-case, but in general it means any non-natural means of triggering; whether it's triggered by a spell, movement/sound detection, or more exotic means. Unless specified otherwise, traps may remain active essentially permanently until triggered (or the timer goes off for Timed Traps).

## Defending Against Traps

As mentioned earlier, defense comes in three forms against traps:

1. **Disarming** - A successful Survival or Crafting check lets the creature disarm the device provided they can get close enough to do so
2. **Detecting** - A successful Perception check lets the creature realize the trap is there, allowing them to circumvent it or avoid setting it off
3. **Dodging/Resisting** - A successful Agility or Endurance check lets the creature either partially or fully dodge/resist the effects of the trap _after it is set off_. In all 3 cases, the check to defend against the trap is an [[1. Basics/index#Opposed Checks|Opposed Check]] against the original **Survival Check** the trapper rolled to originally set the trap.

---

# Trap List

| Name             | Tier       | Materials        | Coverage | Trigger        | Effect                                                                      |
| ---------------- | ---------- | ---------------- | -------- | -------------- | --------------------------------------------------------------------------- |
| Snare Trap       | Apprentice | 1 Trap Material  | 1 hex    | Contact        | Restrained on failed Agility                                                |
| Caltrops         | Apprentice | 1 Trap Material  | 3 hexes  | Contact        | 1d4 + Slowed (remove/3 rounds)                                              |
| Flash Powder     | Apprentice | 1 Trap Material  | Blast 2  | Manual/Timed   | Blind 1 round (Endurance save)                                              |
| Alarm            | Apprentice | 1 Trap Material  | 1 hex    | Magical        | Silent alert to setter; target Slowed, no save                              |
| Spike Strip      | Journeyman | 1 Trap Material  | Line 3   | Contact        | 1d8 + 1 Persistent Bleed                                                    |
| Smokescreen      | Journeyman | 1 Trap Material  | Blast 3  | Manual/Timed   | Obscuring cloud (3 rounds)                                                  |
| Poison Mist      | Journeyman | 2 Trap Materials | Blast 3  | Contact/Timed  | 3 Persistent Poison/round; lingers 2 rounds                                 |
| Silence Trap     | Expert     | 2 Trap Materials | Blast 4  | Magical/Manual | Soundproof boundary; sound cannot enter or leave (5 rounds)                 |
| Concussive Mine  | Expert     | 2 Trap Materials | Blast 2  | Contact/Manual | 4d6+Survival Mod + Stunned 1 round (Endurance save to halve/negate)         |
| Convergence Trap | Expert     | 2 Trap Materials | 1 hex    | Contact/Manual | Pulls 2 connected traps within 4 hexes here and triggers all simultaneously |

---

# Trap Descriptions

## Apprentice Traps

### Snare Trap

**Materials**: 1 Trap Material  
**Trigger**: Contact  
**Effect**: Target becomes Restrained.  
**Coverage**: 1 hex

### Caltrops

**Materials**: 1 Trap Material  
**Trigger**: Contact  
**Effect**: 1d4 damage + Slowed until 2 AP spent removing them OR 3 rounds pass. If a creature would end its movement on a Caltrops hex, then no Agility Check is possible to avoid this damage.  
**Coverage**: 3 adjacent hexes  
**Detection**: Difficult (-10 to Perception checks)

### Flash Powder

**Materials**: 1 Trap Material  
**Trigger**: Manual activation (1 AP) or Timed  
**Effect**: All creatures within 2 hexes make an Endurance check vs the trap's Survival roll or be Blinded for 1 round.  
**Coverage**: Blast 2

### Alarm

**Materials**: 1 Trap Material  
**Trigger**: Magical (motion within 2 hexes)  
**Effect**: Sends a silent signal to the setter the instant any creature moves within range, regardless of distance. The triggering creature is Slowed until they spend 1 AP to remove the line — no Agility check to avoid this.  
**Coverage**: 1 hex  
**Detection**: Difficult (-10 to Perception checks)

## Journeyman Traps

### Spike Strip

**Materials**: 1 Trap Material  
**Trigger**: Contact  
**Effect**: 1d8 damage and 1 Persistent Bleed damage/round. If a creature would end its movement on a Spike Strip hex, then no Agility Check is possible to avoid this damage.  
**Coverage**: Line 3

### Smokescreen

**Materials**: 1 Trap Material  
**Trigger**: Manual activation (1 AP) or Timed  
**Effect**: Creatures inside the smoke are Blind while in the effect, and creatures inside the effect are Invisible to creatures outside the effect.  
**Coverage**: Blast 2
**Notes**: Creates concealment, not direct harm.

### Poison Mist

**Materials**: 2 Trap Materials  
**Trigger**: Contact or Timed  
**Effect**: A pressurized canister releases a toxic mist. Any creature that enters or starts their turn in the area takes 3 Persistent Poison damage per round unless they succeed at an Opposed Endurance Check. The mist lingers for 2 rounds after activation before dispersing, meaning it can affect creatures who did not trigger it.  
**Coverage**: Blast 3

## Expert Traps

### Silence Trap

**Materials**: 2 Trap Materials  
**Trigger**: Magical or Manual (1 AP)  
**Effect**: A soundproof barrier forms at the boundary of the area. Sound cannot enter or leave the affected zone, though sound within it functions normally.  
**Duration**: 5 rounds  
**Coverage**: Blast 4

### Concussive Mine

**Materials**: 2 Trap Materials  
**Trigger**: Contact or Manual (1 AP)  
**Effect**: An explosive percussion device detonates on trigger. All creatures in the blast make an Endurance check against your Survival roll: failures take full damage and are Stunned for 1 round; successes take half damage and are not Stunned.  
**Damage**: 4d6 + Survival Modifier  
**Coverage**: Blast 2

### Convergence Trap

**Materials**: 2 Trap Materials  
**Trigger**: Contact or Manual (1 AP)  
**Effect**: When triggered, up to 2 connected traps within 4 hexes are pulled to the Convergence Trap's location and trigger simultaneously. All triggered traps resolve in the same area, but their effects are treated as a single instance for the purposes of stacking — one save per trap effect, not multiple saves for the same effect. Connected traps must be designated at placement time. Pulled traps do not trigger on anything they pass over during the pull.  
**Coverage**: 1 hex