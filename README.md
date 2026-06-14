# FPS-002 Repository Review Package

Project: **FPS-002 — DIGITAL REALITY RUN**  
Umbrella project lane: **FPS-000**  
Purpose: provide a GitHub-ready repository structure for review, documentation synchronization, and future Claude handoffs.

## Load Order for a New Claude Thread

1. `docs/PROJECT/CURRENT_STATE.md`
2. `docs/PROJECT/DESIGN_LOCK.md`
3. `docs/PROJECT/KNOWN_ISSUES.md`
4. `docs/PROJECT/NEXT_QUEUE.md`
5. `docs/PATCHES/PATCH_LOG.md`
6. `docs/ACCEPTANCE/ACCEPTANCE_STATUS.md`
7. `docs/LESSONS/LESSONS_LEARNED.md`
8. `docs/HANDOFFS/FPS002_HANDOFF_CURRENT.md`
9. Latest `index.html`

## Repository Rule

No patch is complete until:

1. Code is updated.
2. QA is performed.
3. Acceptance result is recorded.
4. Patch log is updated.
5. Known issues are updated.
6. Next queue is updated.

## Current Immediate Priority

**FPS002-WEAPON-AUDIT-001** — restore Burst Charge behavior:

- 8-shot magazine.
- No auto recharge before empty.
- Reload only when empty.
- 3-second reload.
- Restore all 8 charges after reload.

## Current Accepted State

The latest `index.html` is included at the repository root and is the live implementation source of truth.
