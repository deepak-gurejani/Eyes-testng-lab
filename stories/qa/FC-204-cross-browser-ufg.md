# FC-204 — Cross-Browser Coverage via Ultrafast Grid

Type: Story
Role: QA Engineer
Status: To Do
Sprint: Sprint 2
Priority: P1
Story Points: 5
Epic: FreshCart Web App MVP

## User Story

As a QA Engineer, I want to run all visual regression tests across multiple browsers and viewports in parallel using Applitools Ultrafast Grid so that cross-browser issues are caught without running tests on real devices.

## Acceptance Criteria

- AC-1: Tests run via VisualGridRunner instead of classic ClassicRunner
- AC-2: Browser configurations defined: Chrome, Firefox, Safari, Edge
- AC-3: Mobile viewport configurations defined: iPhone 12, Pixel 5
- AC-4: All configurations execute in parallel for each test
- AC-5: Total test execution time under 5 minutes for full suite
- AC-6: Each browser/viewport combination produces its own baseline
- AC-7: Diffs visible per browser in Applitools dashboard
- AC-8: Failed configurations clearly identified in test output

## Definition of Done

- VisualGridRunner configured in test setup
- All 8 browser/viewport configs verified working
- Baselines created for all configs
- Documentation explains how to add or remove configs

## Technical Notes

- Each config consumes 1 unit per checkpoint
- Total units per full run: 3 pages x 8 configs = 24 units
- See FC-302 for unit budget planning

## Linked Stories

- FC-201, FC-202, FC-203 (tests being parallelized)
- FC-302 (unit consumption strategy)
