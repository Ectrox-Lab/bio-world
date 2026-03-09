# Open Questions (Atlas Sync)

## blocker
1. Need Atlas-approved acceptance threshold for `L3_real_p001` vs `L3_shuffled_p001` (which metric and minimum effect size).
2. Need canonical CI/r formula source in this repo before Phase 3 continuity probe hook.

## semantic mismatch
1. `lineage_diversity` currently normalized (`distinct_lineages / population`); Atlas may request absolute count.
2. `collapse_event_count` currently uses extinction events from world loop; confirm if Atlas expects per-run terminal collapse only.

## next-phase proposal
1. Add a small comparison command/script to diff `per_run.csv` between two sentinel modes.
2. Add deterministic seed matrix checks for shuffled vs real sampling bandwidth parity.
3. Add explicit anti-oracle regression tests around overpowered negative-control mode.
