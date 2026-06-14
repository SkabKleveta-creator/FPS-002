# FPS-002 Known Issues

## KI-001 — Burst Charge Weapon Drift

Status: **OPEN**  
Priority: **HIGH**

Expected behavior:

- Burst Charge holds 8 shots.
- No auto recharge while charges remain.
- Each trigger pull consumes 1 charge.
- Player can fire all 8 charges according to weapon cadence.
- When charges reach 0, weapon enters reload state.
- Reload takes 3 seconds.
- Reload restores all 8 charges.

Current reported behavior:

- One shot fires.
- Player must wait 3 seconds.
- Then another shot fires.

Impact:

This changes the weapon from a magazine/reload weapon into a single-shot cooldown weapon.

Required patch:

**FPS002-WEAPON-AUDIT-001**

## KI-002 — Signal Gate Still Reads More Like Door Than Teleport

Status: **OPEN**  
Priority: **MEDIUM**

The Signal Gate should feel like a teleport/transit gate, not a normal door.

Candidate patch:

**FPS002-GATE-TELEPORT**

## KI-003 — Room Architecture Still Simple

Status: **OPEN**  
Priority: **MEDIUM**

Floor objects now help, but room architecture is still simple. Future work should improve room composition and facility identity.

Candidate patch:

**FPS002-ARCH-001**

## KI-004 — Audio Deferred

Status: **DEFERRED**

Audio/sound/music are intentionally frozen for now. Environmental and gameplay identity work has priority.
