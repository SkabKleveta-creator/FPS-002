# FPS-002 Lessons Learned

## LL-001 — Small Patches Beat Large Rewrites

Focused patches are safer and easier to QA.

## LL-002 — Readability Beats Realism

A visually richer feature is not accepted if it hides targets, gates, stations, pickups, or controls.

## LL-003 — Composition Beats Object Count

Rooms become believable through functional clusters, not more props.

## LL-004 — Props Must Become Systems of Meaning

One crate says “crate.”

A pallet, crates, and rack together say “loading operation.”

## LL-005 — Solid Props Require Reachability Validation

If props block movement, each placement must be validated against required progression targets.

## LL-006 — Player Feedback Is Authoritative

Source-level QA is not enough. Human playtest determines acceptance.

## LL-007 — Documentation Must Be Updated With Each Patch

If the markdown files do not reflect the latest accepted state, the project will drift.

## LL-008 — Weapon Drift Is a Regression Class

Accepted weapon identity must be documented and tested. Burst Charge drift proves this.

## LL-009 — Like-Item Stacking Only

Future floor-object stacking must be restricted to believable like-item groupings.
