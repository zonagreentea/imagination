# imagination* — zone update

## Zone Principle
Coding happens in zone.
If friction appears, the system—not the person—must change.

## Written Invariants
- If it isn’t written, it doesn’t exist.
- Exits are observations, not failures.
- Timeline is authoritative.
- Safety gates reduce anxiety, not freedom.

## Ball Safety (Referenced)
- Ball pushes are explicit (`BALL_PUSH_OK=1`)
- Clean tree required
- Submodule integrity required
- Canon documented in MDM.md (root)

## Clean Exit
- event: clean_exit
- reason ∈ { user_exit, window_close, process_end, handoff }
- state: satisfied
- continuity: maintained

## Clean Megamix
- Mix never stops
- Busts are per-player only
- Multiplayer is join-in-progress
- Mode changes are projections, not resets

## Megamix Inclusion Rule
Megamix sublayer is included when mode string contains:
- "multi"
- "quickplay"

(String-based, deterministic, no hardware dependency)

## Ethos
Zone is maintained by:
- written constraints
- minimal ceremony
- terminal-first workflows
