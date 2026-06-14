# FPS-002 Current Handoff

## Load This First

This handoff summarizes current project truth for a new Claude thread.

Then load:

1. `docs/PROJECT/CURRENT_STATE.md`
2. `docs/PROJECT/DESIGN_LOCK.md`
3. `docs/PROJECT/KNOWN_ISSUES.md`
4. `docs/PROJECT/NEXT_QUEUE.md`
5. `docs/PATCHES/PATCH_LOG.md`
6. latest `index.html`

## Current State

FPS-002 is a single-file browser FPS prototype with:

- mobile controls
- raycast rendering
- Automaton / Stations / Signal Gate loop
- sector-clear stats
- environmental degradation
- sector palettes
- solid clustered floor objects

## Accepted Floor Object Status

Props are now acceptable as grounded, solid room objects.

Do not revert:

- prop collision
- drone prop collision
- clustered placement
- grounded silhouettes
- reachability validation

## Immediate Next Patch

**FPS002-WEAPON-AUDIT-001**

Restore Burst Charge behavior:

- 8-shot magazine.
- No recharge until empty.
- 3-second reload after empty.
- Restore all 8 shots.

## Do Not Start With

- audio
- music
- movable props
- pushing
- new sectors
- architecture rewrite

## Next Visual Candidate After Weapon Fix

**FPS002-GATE-TELEPORT** — make Signal Gate feel like teleport/transit, not a door.
