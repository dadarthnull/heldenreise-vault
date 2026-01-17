# The Lich Lord Malachar & Verathrax, the Bone Wyrm

## Encounter Overview

**Raid Size:** 15 characters, level 11
**Estimated Duration:** 60-90 minutes (real time), ~30-45 rounds
**Difficulty:** Challenging raid encounter for optimized parties

---

## Encounter-Wide Rules

### Telegraphed Attack System

All dragon zone attacks follow this pattern:

- **Warning Round:** Zone is highlighted with visual indicator (ghostly green flames outline the area, bones rattle, temperature drops)
- **Execution Round:** Attack occurs, dealing damage to all creatures in the zone

Players can use their turn to identify zones (no check needed—the visual is obvious) and reposition.

---

## Phase 1: The Mounted Doom

> *The Lich Lord rides atop Verathrax. A shimmering barrier of necrotic energy surrounds him—all damage dealt to him is instead dealt to the dragon.*

---

## Verathrax, the Bone Wyrm (Phase 1)

**Type:** Undead (Dragon)
**Difficulty:** 20
**Bonus:** +12
**Speed:** 40ft fly (hover)
**HP:** 1200
**AC:** 17

**Saving Throws:** +10 STR, +6 DEX, +12 CON, +8 WIS

**Immunities:** Necrotic, Poison, Exhaustion, Frightened, Poisoned
**Resistances:** Cold, Lightning, Piercing/Slashing/Bludgeoning from nonmagical attacks
**Vulnerabilities:** Radiant

---

### Life Bond (Phase 1 Only)

All damage targeting Malachar is redirected to Verathrax. Malachar cannot be targeted by effects that don't deal damage (he's protected by a barrier). The barrier drops when Verathrax reaches 0 HP.

---

### Verathrax Attack Rotation

The dragon cycles through these attacks in order, then repeats. Each attack telegraphs on one round and executes the next.

| Round | Telegraph | Round | Execute |
|-------|-----------|-------|---------|
| 1     | Attack A  | 2     | Attack A |
| 2     | Attack B  | 3     | Attack B |
| 3     | Attack C  | 4     | Attack C |
| 4     | Attack D  | 5     | Attack D |
| 5     | Attack E  | 6     | Attack E |
| 6     | Attack F  | 7     | Attack F |
| 7     | Attack A  | 8     | Attack A |
| ...   | ...       | ...   | ...     |

> [!info] Overlap
> Telegraph and Execute overlap—while one attack executes, the next is being telegraphed.

---

### Attack A — Necrotic Breath (Ground Cone)

**Telegraph:** 60ft cone originating from dragon, floor glows with ghostly green runes, spectral hands reach upward

**Zone:** 60ft cone, ground level only (0-10ft height)

**Execution:** All creatures in the zone must make a **DC 18 Constitution saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **55 [10d10]** necrotic damage |
| Success | Half damage |

**Flying Counter:** Creatures above 10ft are completely safe.

> [!note] Visual
> A torrent of screaming souls and green fire sweeps across the floor.

---

### Attack B — Bone Shard Eruption (Ground Circles)

**Telegraph:** Three 20ft radius circles appear on the ground (positioned to cover common grouping spots), bones begin pushing up through the floor

**Zone:** Three 20ft radius circles, ground level only (0-15ft height)

**Execution:** All creatures in any zone must make a **DC 17 Dexterity saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **42 [12d6]** piercing damage and knocked prone |
| Success | Half damage, not prone |

**Flying Counter:** Creatures above 15ft are completely safe.

> [!note] Visual
> Massive bone spikes erupt from the ground like a forest of death.

---

### Attack C — Soul Storm (Full Height Column)

**Telegraph:** A 30ft radius circle appears in the center of the room, ghostly winds begin spiraling from floor to ceiling

**Zone:** 30ft radius cylinder, floor to ceiling (all heights)

**Execution:** All creatures in the zone must make a **DC 18 Wisdom saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **38 [7d10]** psychic damage and frightened until end of next turn |
| Success | Half damage, not frightened |

**Flying Counter:** NONE—this attack reaches ceiling. Fly elsewhere.

> [!note] Visual
> A tornado of screaming souls fills the column, tearing at minds.

---

### Attack D — Frost Wing Buffet (Side Waves)

**Telegraph:** Two 40ft wide, 60ft long rectangles appear on either side of the dragon (left and right), frost begins crystallizing in the air

**Zone:** Two rectangular zones flanking the dragon, ground to 20ft height

**Execution:** All creatures in either zone must make a **DC 17 Strength saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **35 [10d6]** cold damage, pushed 30ft away, speed halved until end of next turn |
| Success | Half damage, pushed 15ft, speed not reduced |

**Flying Counter:** Creatures above 20ft are safe, but being pushed while flying might be dangerous.

> [!note] Visual
> The dragon beats its wings and waves of freezing deathly energy blast outward.

---

### Attack E — Grave Rain (Ceiling to Floor)

**Telegraph:** Four 15ft radius circles scattered across the room, dark clouds form at the ceiling above each

**Zone:** Four 15ft radius cylinders, floor to ceiling (all heights)

**Execution:** All creatures in any zone must make a **DC 16 Dexterity saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **45 [10d8]** bludgeoning damage and restrained until end of next turn (buried) |
| Success | Half damage, not restrained |

**Flying Counter:** NONE—bones rain from ceiling. Fly elsewhere.

> [!note] Visual
> A cascade of bones falls from shadowy portals on the ceiling, burying everything below.

---

### Attack F — Death's Embrace (Expanding Ring)

**Telegraph:** A ring pattern appears centered on the dragon—the ring starts at 20ft radius and will expand to 50ft radius, showing the "danger zone" (everything between 20ft and 50ft from dragon)

**Zone:** Ring shape, inner radius 20ft, outer radius 50ft, ground to 25ft height

**Execution:** All creatures in the ring must make a **DC 18 Constitution saving throw**.

| Result | Effect |
|--------|--------|
| Failure | **48 [8d10+4]** necrotic damage and cannot regain HP until end of next turn |
| Success | Half damage, can regain HP normally |

**Safe Zones:** Within 20ft of dragon (melee range) OR more than 50ft away OR above 25ft

**Flying Counter:** Above 25ft is safe, or stay very close/very far.

> [!note] Visual
> A wave of pure death energy pulses outward from the dragon in a ring.

---

## Malachar's Debuffs (Phase 1)

While riding Verathrax, Malachar casts debilitating curses. He acts on the same initiative as Verathrax but after the dragon's telegraph/attack.

**Each Round, Malachar uses one of the following (cycling or chosen by DM):**

---

### Curse of Weakness

**Target:** Up to 3 creatures Malachar can see

**Effect:** Targets must make a **DC 18 Charisma saving throw** or deal half damage with weapon attacks until the end of their next turn.

---

### Life Drain Link

**Target:** 2 creatures within 60ft of each other

**Effect:** Targets must make a **DC 17 Constitution saving throw**. On failure, they are linked for 1 minute. Whenever one takes damage, the other takes **10** necrotic damage (no save). The link can be broken by being more than 60ft apart for a full round or by *remove curse*.

---

### Grave Chill

**Target:** All creatures in a 20ft radius sphere centered on a point within 90ft

**Effect:** Targets must make a **DC 17 Constitution saving throw** or have their speed reduced by 20ft and have disadvantage on Dexterity saving throws until the end of their next turn.

---

### Soul Mark

**Target:** 1 creature Malachar can see

**Effect:** Target must make a **DC 18 Wisdom saving throw** or be marked for 1 minute. While marked, the creature has vulnerability to necrotic damage. Save ends at end of each turn.

---

## Phase 1 Transition

> [!danger] Transition Trigger
> When Verathrax reaches **0 HP**

> *The bone dragon crashes to the ground, its form crumbling. The necrotic barrier around Malachar shatters, and the Lich Lord rises from the wreckage, hovering in the air.*
> 
> **"You think destroying my pet will save you? I have commanded legions of the dead for centuries. Let me show you true necromancy."**

---

## Phase 2: The Lich Unbound

> *Malachar hovers 20ft above the ground, raining death upon the party. The floor becomes a spawning ground for undead minions.*

---

## Lich Lord Malachar (Phase 2)

**Type:** Undead (Humanoid)
**Difficulty:** 21
**Bonus:** +12
**Speed:** 0ft, 40ft fly (hover)
**HP:** 900
**AC:** 19

**Saving Throws:** +8 CON, +12 INT, +10 WIS, +9 CHA

**Immunities:** Necrotic, Poison, Exhaustion, Charmed, Frightened, Paralyzed, Poisoned
**Resistances:** Cold, Lightning, Bludgeoning/Piercing/Slashing from nonmagical attacks
**Vulnerabilities:** Radiant

---

### Flight Mechanic

Malachar hovers at 20ft altitude by default. He can be reached by:

- Flying characters
- Characters with reach weapons (if he descends)
- Ranged attacks and spells

**Grounding:** If Malachar takes **80+ damage in a single round**, he descends to 10ft altitude until the end of his next turn. If a character is grappling him or he is restrained, he cannot hover.

---

### Malachar's Actions (Phase 2)

Malachar has **3 Legendary Actions** per round, usable at the end of other creatures' turns.

---

### Standard Action — Depends on Contact

#### If NO creature is within 5ft: Death Bolts

**Attack:** Ranged spell attack, +12 to hit, range 120ft
**Targets:** Up to 3 different creatures
**Damage:** **28 [8d6]** necrotic damage per bolt

> *Malachar launches three bolts of concentrated death energy.*

---

#### If ANY creature is within 5ft: Withering Touch + Curse

**Attack:** Melee spell attack, +10 to hit, reach 5ft
**Targets:** One creature
**Damage:** **14 [4d6]** necrotic damage

**Curse Applied (no save while in contact):** The touched creature gains one stack of **Lich's Grasp**.

| Stacks | Effect |
|--------|--------|
| 1 | -2 to all saving throws |
| 2 | -2 to all saving throws, disadvantage on attack rolls |
| 3 | -2 to all saving throws, disadvantage on attack rolls, speed halved |
| 4+ | As above, plus **10** necrotic damage at start of each turn |

Stacks last 1 minute or until removed by *greater restoration* or similar magic. One stack is removed per casting.

> *Malachar's touch drains life and layers curses upon those foolish enough to stay close.*

---

### Legendary Actions

#### Necrotic Lance (2 Actions)

**Attack:** Ranged spell attack, +12 to hit, range 90ft
**Target:** One creature
**Damage:** **36 [8d8]** necrotic damage, and the target must make a **DC 17 Constitution saving throw** or be unable to regain HP until the end of their next turn.

---

#### Command Undead (1 Action)

All Risen Thralls within 60ft can immediately move up to half their speed toward the nearest living creature.

---

#### Dark Pact (1 Action)

Malachar sacrifices one Risen Thrall within 30ft. It immediately explodes (see Thrall stat block), and Malachar regains **40 HP**.

---

#### Curse of Binding (2 Actions)

One creature within 60ft must make a **DC 18 Wisdom saving throw** or be paralyzed until the end of their next turn.

---

## Risen Thralls (Phase 2 Adds)

> [!warning] Spawn Rate
> **4 Thralls** spawn at the start of each of Malachar's turns, appearing in the Bone Pits (corners of the room).

---

## Risen Thrall

**Type:** Undead
**HP:** 50
**AC:** 12
**Speed:** 30ft

**Attack:** Claw +5, **7 [2d6]** slashing damage

**Immunities:** Necrotic, Poison, Poisoned
**Vulnerability:** Radiant

---

### Necrotic Overload

If a Thrall is not killed within **3 rounds** of spawning, it explodes at the start of its fourth turn.

**Explosion:**

- 15ft radius
- All creatures in radius must make a **DC 14 Dexterity saving throw**

| Result | Effect |
|--------|--------|
| Failure | **21 [6d6]** necrotic damage |
| Success | Half damage |

- **Malachar heals 30 HP** per Thrall that explodes (regardless of distance)

> [!tip] Tactical Note
> Thralls should be killed quickly or kited away from the party before they explode.

---

## Phase 2 Transition

> [!danger] Transition Trigger
> When Malachar reaches **300 HP (33%)**

> *Malachar staggers in the air, dark ichor leaking from wounds that glow with radiant burns. He throws back his head and laughs—a sound like cracking tombstones.*
> 
> **"You think this is victory? I have prepared for this moment for a thousand years. VERATHRAX! RISE!"**
> 
> *The ground shakes. Reality tears. You are suddenly elsewhere—a vast chamber of black stone, miles beneath the earth. And before you, reassembling bone by bone, is the dragon.*

All creatures are teleported to the **Throne of Bones** (Phase 3 arena).

---

## Phase 3: The Throne of Bones

> *A massive underground throne room. Verathrax has been resurrected at reduced power. Both Malachar and the dragon fight simultaneously.*

---

## Arena — Throne of Bones

- **Size:** 120ft diameter circular chamber, 60ft ceiling
- **Central Throne:** Raised 10ft platform at north end (Malachar's phylactery is hidden here—destroying it prevents resurrection, but requires finding it first: DC 20 Investigation)
- **Bone Pillars:** Four pillars provide half cover but are destroyed if they take 50 damage
- **No Bone Pits:** Thralls spawn directly from the floor anywhere

---

## Verathrax, Reborn (Phase 3)

**Type:** Undead (Dragon)
**HP:** 700
**AC:** 16
**All other stats identical to Phase 1**

---

### Reduced Attack Rotation

Verathrax only uses **3 attacks** in rotation (chosen by DM or roll d6: 1-2 = A, 3-4 = C, 5-6 = E). The rotation is faster—attacks still telegraph one round, execute the next, but now overlap more (always telegraphing while executing).

---

### Linked Life (Phase 3)

Malachar and Verathrax share a soul bond. While both live:

- If one would take radiant damage, the other takes half that damage as well (this can trigger vulnerability)
- If one is below 25% HP, the other gains **+2 to all saving throws** (desperate fury)

---

## Lich Lord Malachar (Phase 3)

**Type:** Undead (Humanoid)
**HP:** 300 (continues from Phase 2)
**AC:** 19
**All other stats identical to Phase 2**

---

### Phase 3 Changes

- Still hovers and uses Death Bolts / Withering Touch as before
- **Thrall spawn rate reduced:** 2 Thralls per turn instead of 4

---

### Soul Tether (Recharge 5-6)

Malachar creates a beam of necrotic energy between himself and Verathrax. Until the start of his next turn:

- Any damage dealt to Malachar is split evenly between him and Verathrax
- Any damage dealt to Verathrax is split evenly between him and Malachar
- Any creature that passes through the beam (30ft long, 5ft wide) takes **22 [4d10]** necrotic damage

> [!tip] Tactical Note
> This forces the party to consider positioning and whether to damage one or the other.

---

## Combined Mechanics

### Synchronous Death

If either Malachar or Verathrax reaches 0 HP while the other is above 50% HP, read:

> **"NO! The bond sustains us! RISE!"**

The fallen one regenerates **100 HP** at the start of the next round unless the other is brought below 50% HP within that round.

---

### Victory Conditions

- Both must be below 50% HP, OR
- Both must be reduced to 0 HP within 2 rounds of each other

---

### Phylactery

If Malachar's phylactery is found and destroyed:

- **DC 20 Investigation** to find on the throne
- **100 HP** to destroy
- **AC 15**
- Immune to necrotic/poison

Destroying the phylactery disables the Synchronous Death mechanic and Malachar cannot regenerate.

---

## Quick Reference Table

| Creature | Phase | HP | AC | Key Damage | Save DC |
|----------|-------|------|-----|------------|---------|
| Verathrax | 1 | 1200 | 17 | 35-55 per zone | 16-18 |
| Malachar | 1 | — | — | Debuffs only | 17-18 |
| Malachar | 2 | 900 | 19 | 28×3 or 14+curse | 17-18 |
| Risen Thrall | 2/3 | 50 | 12 | 7 melee, 21 explode | 14 |
| Verathrax | 3 | 700 | 16 | 35-55 per zone | 16-18 |
| Malachar | 3 | 300 | 19 | 28×3 or 14+curse | 17-18 |

---

## Total HP Pool

| Phase | Target | HP |
|-------|--------|-----|
| Phase 1 | Verathrax | 1200 |
| Phase 2 | Malachar | 600 (900 → 300) |
| Phase 3 | Both | 1000 (700 + 300) |
| **Total** | | **2800** |

> [!info] Calculation
> With 15 characters dealing an average of 40 DPR (some higher, some support), that's ~600 damage per round before deaths/healing. Expected duration: ~5-6 rounds per phase, totaling ~15-20 rounds of active combat.

---

## Expected Damage Output vs Party

| Phase | Expected Damage/Round | Notes |
|-------|----------------------|-------|
| Phase 1 | 50-100 | If party positions well; 150+ with poor positioning |
| Phase 2 | 100-150 | Between Death Bolts and Thrall management; exploding Thralls spike this |
| Phase 3 | 150-200 | Both bosses active; this is the "burn" phase |

---

## Narrative Beats

### Phase 1 Start
> *"Mortals dare enter my sanctum? Verathrax... show them the cold embrace of the grave."*

### First Breath Attack
> *"BURN IN THE FIRES OF THE DAMNED!"*

### Phase 1 → 2 Transition
> *"You think destroying my pet will save you? I have commanded legions of the dead for centuries. Let me show you true necromancy."*

### First Thrall Wave
> *"Rise, my children! Feast upon the living!"*

### Phase 2 → 3 Transition
> *"You think this is victory? I have prepared for this moment for a thousand years. VERATHRAX! RISE!"*

### Soul Tether Activation
> *"Our souls are ONE! Strike one, and you strike BOTH!"*

### Below 25% HP
> *"No... NO! I will not fall! Not to insects like YOU!"*

### Death
> *"The darkness... it calls me home... but I shall... return..."*

---

## Loot

### Malachar's Phylactery Shard

*Wondrous item, very rare (requires attunement)*

Once per long rest, when you would be reduced to 0 HP, you instead drop to 1 HP. Additionally, you gain resistance to necrotic damage.

**Curse:** Each time this item saves you from death, you gain one level of exhaustion that cannot be removed except by *greater restoration* or finishing a week-long rest.

---

### Verathrax's Fang

*Weapon (greatsword), very rare (requires attunement)*

This massive blade was carved from Verathrax's largest fang. You gain +2 to attack and damage rolls. When you hit a creature, you can choose to deal an additional **2d6** necrotic damage and regain HP equal to the necrotic damage dealt. You can use this property three times per long rest.

---

### Robes of the Death Lord

*Armor (robes), very rare (requires attunement by a spellcaster)*

While wearing these robes, you gain +2 AC, immunity to the frightened condition, and resistance to necrotic damage. Additionally, once per long rest, you can cast *circle of death* (DC 17) without expending a spell slot.

---

### Bone Wyrm Scale Shield

*Armor (shield), rare*

This shield is made from interlocking dragon bones. While holding it, you have resistance to cold damage. As a reaction when you take necrotic damage, you can halve that damage. You can use this reaction three times per long rest.

---

### Crown of the Oathbroken

*Wondrous item, very rare (requires attunement)*

This tarnished silver crown was once holy but has been corrupted by centuries of undeath. While wearing it:

- You have advantage on saving throws against being charmed or frightened
- You can speak and understand all languages spoken by undead
- Once per long rest, you can cast *speak with dead* without components

**Curse:** While attuned, you appear slightly more gaunt and pale. Healing spells cast on you restore only 75% of their normal value.

---

### Malachar's Spellbook

*Wondrous item, very rare*

This tome bound in preserved skin contains the following spells (wizard spell list):

- *Animate dead*
- *Bestow curse*
- *Blight*
- *Circle of death*
- *Create undead*
- *Finger of death*
- *Soul cage*
- *Negative energy flood*

A wizard can copy these spells into their own spellbook using the normal rules and costs.

---

## DM Checklist

### Before the Session

- [ ] Print/prepare zone attack diagrams
- [ ] Prepare Thrall tracking sheet (spawn round, explosion round)
- [ ] Review player flight capabilities
- [ ] Have Malachar's debuff rotation planned
- [ ] Prepare Verathrax attack rotation order
- [ ] Set up initiative tracker with Legendary Action reminders

### During Phase 1

- [ ] Track dragon HP (1200)
- [ ] Announce telegraph zones clearly
- [ ] Apply debuffs and track durations
- [ ] Reward good positioning with damage avoidance

### During Phase 2

- [ ] Track Malachar HP (900 → 300 for transition)
- [ ] Spawn 4 Thralls per round
- [ ] Track Thrall explosion timers (3 rounds)
- [ ] Use Legendary Actions after player turns
- [ ] Remember grounding mechanic (80+ damage in one round)

### During Phase 3

- [ ] Both bosses act on same initiative (dragon first)
- [ ] Reduced Thrall spawn (2 per round)
- [ ] Track Linked Life radiant damage sharing
- [ ] Watch for Synchronous Death trigger
- [ ] Track Soul Tether recharge

---

## Zone Attack Visual Aid

```
ATTACK A - Necrotic Breath (60ft Cone, Ground Only)
        
         ╱ · · · · · · ╲
       ╱ · · · · · · · · ╲
     ╱ · · · · · · · · · · ╲
   ╱ · · · · · · · · · · · · ╲
 🐉─────────────────────────────
   ╲ · · · · · · · · · · · · ╱
     ╲ · · · · · · · · · · ╱
       ╲ · · · · · · · · ╱
         ╲ · · · · · · ╱

Height: 0-10ft only
Safe: Above 10ft
```

```
ATTACK B - Bone Shard Eruption (3x 20ft Circles, Ground Only)

    ┌─────┐         ┌─────┐
    │  ·  │         │  ·  │
    │  ·  │         │  ·  │
    └─────┘         └─────┘
              
           ┌─────┐
           │  ·  │
           │  ·  │
           └─────┘

Height: 0-15ft only
Safe: Above 15ft
```

```
ATTACK C - Soul Storm (30ft Radius, Full Height)

         ╭───────────╮
         │ ╭───────╮ │
         │ │ ░░░░░ │ │  ← FULL HEIGHT
         │ │ ░░░░░ │ │    FLOOR TO CEILING
         │ │ ░░░░░ │ │
         │ ╰───────╯ │
         ╰───────────╯

Height: ALL
Safe: Outside 30ft radius only
```

```
ATTACK D - Frost Wing Buffet (Side Rectangles, Ground to 20ft)

    ┌────────────┐     ┌────────────┐
    │ · · · · ·  │     │  · · · · · │
    │ · · · · ·  │ 🐉  │  · · · · · │
    │ · · · · ·  │     │  · · · · · │
    └────────────┘     └────────────┘
         LEFT              RIGHT

Height: 0-20ft
Safe: Behind/in front of dragon, or above 20ft
```

```
ATTACK E - Grave Rain (4x 15ft Cylinders, Full Height)

    ┌───┐              ┌───┐
    │ ▼ │              │ ▼ │
    └───┘              └───┘
              
              ┌───┐              ┌───┐
              │ ▼ │              │ ▼ │
              └───┘              └───┘

Height: ALL (rains from ceiling)
Safe: Outside circles only
```

```
ATTACK F - Death's Embrace (Ring 20ft-50ft, Ground to 25ft)

              ╭─────────────────╮
           ╭──┤ · · · · · · · · ├──╮
         ╭─┤  │                 │  ├─╮
         │ │  │    ┌─────┐      │  │ │
         │ │  │    │SAFE │ 🐉   │  │ │
         │ │  │    └─────┘      │  │ │
         ╰─┤  │                 │  ├─╯
           ╰──┤ · · · · · · · · ├──╯
              ╰─────────────────╯

Height: 0-25ft
Safe: Within 20ft OR beyond 50ft OR above 25ft
```

---

## Thrall Tracking Sheet

| Thrall # | Spawn Round | Explodes Round | Status |
|----------|-------------|----------------|--------|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |
| 5 | | | |
| 6 | | | |
| 7 | | | |
| 8 | | | |
| 9 | | | |
| 10 | | | |
| 11 | | | |
| 12 | | | |
| 13 | | | |
| 14 | | | |
| 15 | | | |
| 16 | | | |