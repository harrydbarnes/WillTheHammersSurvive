## 2025-02-18 - [Swipe Mode Transition Bug]
**Learning:** Found an existing bug where the main grid does not reflect results predicted in Swipe Mode after exiting. The `resetAll()` call on swipe entry clears results, and exiting swipe mode shows the stale grid.
**Action:** When working on Swipe Mode, ensure `renderFixtures()` or `updateFixtureUI()` is called to sync the grid with `results`.
