# FPS-002 Design Lock

## Identity Lock

FPS-002 is not a generic shooter.

It is a continuous arcade FPS about moving through digitally reconstructed real spaces, cutting hostile signal control, and validating passage through Signal Gates.

## Core Feeling

> I am walking through a digital reconstruction of a real place that used to make sense.

## World Lock

The environment should be inspired by:

- office spaces
- warehouses
- server rooms
- loading docks
- manufacturing floors
- data centers
- maintenance tunnels

Reality degrades during runtime.

## Readability Lock

Readability beats realism.

Targets, objectives, doors, gates, pickups, and navigation lanes must remain legible on mobile.

## Progression Lock

A sector clears only when:

1. Automaton is down.
2. All Replicator Stations are cut.
3. Signal Gate opens.
4. Player enters the Signal Gate.

## Floor Object Lock

Floor objects are:

- solid
- non-movable
- fair-collision blockers
- respected by drones
- clustered into functional operational groupings
- grounded in the floor plane
- objective-safe
- reachability-safe

Floor objects are not:

- inventory
- pushables
- physics objects
- objectives
- enemies
- pickups
- signal sources

## Floor Object Stacking Rule

Floor objects may be visually stackable only with like items.

Allowed:

- crate with crate
- pallet with pallet / crate
- rack row with rack
- cabinet bank with cabinet
- server/data block row with server/data block

Forbidden:

- random mixed stacks
- cabinet on crate
- console stacked with rack
- stacks near Gate, Stations, pickups, doors, spawn, or required objectives

## Patch Discipline Lock

No broad rewrites unless explicitly authorized.

One patch means one focused change.

Every patch must preserve:

- controls
- mobile controls
- movement feel
- gate logic
- station logic
- Automaton logic unless explicitly targeted
- sector reachability
- HUD/stats unless explicitly targeted
