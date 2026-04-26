# FC-202 — Visual Regression Test for Dashboard Page

Type: Story
Role: QA Engineer
Status: To Do
Sprint: Sprint 2
Priority: P0
Story Points: 3
Epic: FreshCart Web App MVP
Covers AC of: FC-002

## User Story

As a QA Engineer, I want to automate visual regression tests for the Dashboard page so that account summary changes are validated visually across all browsers.

## Acceptance Criteria

- AC-1: TestNG test class DashboardPageTest exists in src/test/java
- AC-2: Test navigates from Login page to Dashboard via Sign In click
- AC-3: Test captures a visual checkpoint of the full dashboard
- AC-4: Dynamic timestamp area is excluded via Applitools ignore region
- AC-5: Checkpoint runs on Chrome, Firefox, Safari, and mobile viewports via UFG
- AC-6: Test belongs to the same batch as FC-201
- AC-7: Match level is Layout for the metric cards section
- AC-8: Test passes on first run

## Definition of Done

- Test code written and committed
- Ignore region for timestamp configured correctly
- Baseline created in Applitools dashboard
- Test runs in CI pipeline

## Test Scenarios

- Scenario 1: First run creates baseline (expected: pass)
- Scenario 2: Timestamp changes between runs (expected: pass, ignored)
- Scenario 3: Card number color changed (expected: fail with diff)

## Linked Stories

- FC-002 (the page being tested)
- FC-201 (sibling test, same batch)
- FC-302 (batch strategy)
