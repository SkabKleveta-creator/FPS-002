# FPS-002 Patch Log

## FPS002-001 — Anti-Wallhack Occlusion

Status: Accepted.

Changed:

- Replaced single-column sprite occlusion with per-column visibility clipping.
- Removed boss wall-exemption.

Lesson:

Render exemptions become accidental wallhacks.

## FPS000-QUALITY-002 — Sector 1 Presentation / Identity Copy

Status: Accepted.

Changed:

- Removed generic “destroy” language from player-facing copy.
- Reframed Signal Baton and Sector 1 identity.

## FPS000-QUALITY-003 — Locked Signal Gate Clarity

Status: Accepted.

Changed:

- Added compact/verbose gate requirement text.
- Gate now names remaining requirements.

## FPS000-QUALITY-004 — Replicator Station Visual Identity

Status: Accepted.

Changed:

- Stations became grounded signal infrastructure with amber core/rings.

## FPS000-QUALITY-005 — Automaton Visual Identity

Status: Accepted.

Changed:

- Automaton now reads as command source/system avatar.

Player acceptance:

- Recognizable at first sight.
- Distinct from drones and stations.
- HP bar useful.
- Damage/death/gate behavior preserved.

## FPS000-QUALITY-006A — HUD Modules + Sector Clear Stats

Status: Accepted.

Changed:

- HUD rebuilt as game-style modules.
- Objective chips added.
- Sector-clear stats card added.

## FPS000-VISUAL-002 — Environmental Realism + Degradation

Status: Accepted.

Changed:

- Per-sector palettes.
- Industrial floor cues.
- Wall/floor/ceiling atmosphere.
- Slow degradation effect.

Player acceptance:

- Sector 1 feels more like reconstructed real place.
- Walls/floors improved without hurting target visibility.
- Degradation atmospheric, not noisy.
- S2/S3 color identity heavy pass.

## FPS000-VISUAL-003 — Decorative Environmental Props

Status: Superseded by 003B/003C/003D.

Changed:

- Non-solid decorative props.

Issue:

- Player could walk through them.

## FPS000-VISUAL-003B — Solid Environmental Props

Status: Accepted as physical behavior layer.

Changed:

- Props became solid.
- Player collision added.
- Drone collision added.
- Reachability validation added.

## FPS000-VISUAL-003C — Functional Prop Clustering

Status: Accepted conceptually; paired with 003D for visual anchoring.

Changed:

- Scatter props replaced with functional clusters.
- Sector-specific cluster recipes added.
- Object silhouettes improved.

## FPS000-VISUAL-003D — Fixed Floor-Map Objects / Anchoring

Status: Accepted by player.

Changed:

- Props visually grounded as floor objects.
- Cabinets/crates readable.
- Collision feels fair.
- Drones respect props.
- Clusters make rooms feel real.

Player acceptance:

- Cabinet vs crate instantly recognizable.
- Objects grounded.
- Fair blocking.
- Drones respect collision.
- No annoying shooting/movement blockage.

## Pending — FPS002-WEAPON-AUDIT-001

Status: Next recommended patch.

Purpose:

Restore Burst Charge 8-shot magazine + 3-second reload behavior.
