# FPS-002 Current State

## Project Name

**FPS-002 — DIGITAL REALITY RUN**  
Umbrella project lane: **FPS-000**

## Core Fantasy

The player is moving through a digital reconstruction of real facilities: spaces that used to make sense, now rebuilt from system memory and held together by a hostile command signal.

Core feeling:

> I am walking through a digital reconstruction of a real place that used to make sense.

## Current Game Loop

1. Enter a sector.
2. Navigate a first-person raycast environment.
3. Fight drones and the Automaton.
4. Cut Replicator Stations.
5. Collapse the command network.
6. Unlock the Signal Gate.
7. Enter the Gate to advance.
8. Review sector-clear stats.

## Current Sectors

Current build contains three sectors:

1. **Sector 1 — Signal Maintenance Bay**
2. **Sector 2 — Storage Deck**
3. **Sector 3 — Reactor Node / Reactor Arcade Node lineage**

The implementation uses generated sector layouts with fallback static maps.

## Current Enemy / Objective Classes

- **Automaton** — command source / system avatar visual direction.
- **Drones** — mobile hostile units with archetypes and states.
- **Replicator Stations** — fixed spawner/objective infrastructure.
- **Signal Gate** — locked progression exit.

## Current Weapons

- Pistol
- Rifle
- Burst Charge
- Signal Baton on B

Known issue: Burst Charge behavior has drifted and must be audited/restored.

## Current UI

- Mobile-safe HUD modules.
- Objective chips for AUTO / STA / DRN / GATE.
- Compact sector label.
- Sector-clear stats card.

## Current Environment Systems

- Per-sector palette identity.
- Industrial floor and wall material cues.
- Slow visual degradation over runtime.
- Solid floor objects / props.
- Clustered operational prop placement.
- Drones respect prop collision.
- Player respects prop collision.

## Current Floor Object Status

Accepted after player feedback:

- Cabinet vs crate instantly recognizable.
- Objects feel grounded.
- Objects block fairly.
- Drones respect collision.
- Clusters help rooms feel real.
- No frustrating shooting/movement blockage reported.

Pending rule to add formally:

- Floor objects may be visually stackable only with like items.
