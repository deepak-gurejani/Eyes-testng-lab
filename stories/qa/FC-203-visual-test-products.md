# FC-203 — Visual Regression Test for Products Page

Type: Story
Role: QA Engineer
Status: To Do
Sprint: Sprint 2
Priority: P0
Story Points: 3
Epic: FreshCart Web App MVP
Covers AC of: FC-003

## User Story

As a QA Engineer, I want to automate visual regression tests for the Products page so that the product grid layout and card styling stay consistent across releases.

## Acceptance Criteria

- AC-1: TestNG test class ProductsPageTest exists in src/test/java
- AC-2: Test navigates from Dashboard to Products via nav link
- AC-3: Test captures a visual checkpoint of the full product grid
- AC-4: All 6 product cards are included in the checkpoint
- AC-5: Checkpoint runs on Chrome, Firefox, Safari, and mobile viewports via UFG
- AC-6: Test belongs to the same batch as FC-201 and FC-202
- AC-7: Match level is Strict for product card styling
- AC-8: Test passes on first run

## Definition of Done

- Test code written and committed
- Baseline created in Applitools dashboard
- All 6 products verified in baseline
- Test runs in CI pipeline

## Test Scenarios

- Scenario 1: First run creates baseline (expected: pass)
- Scenario 2: Product order changes (expected: fail with diff)
- Scenario 3: Price color changed (expected: fail with diff)

## Linked Stories

- FC-003 (the page being tested)
- FC-201, FC-202 (sibling tests, same batch)
- FC-302 (batch strategy)
