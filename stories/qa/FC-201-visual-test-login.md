# FC-201 — Visual Regression Test for Login Page

Type: Story
Role: QA Engineer
Status: To Do
Sprint: Sprint 2
Priority: P0
Story Points: 3
Epic: FreshCart Web App MVP
Covers AC of: FC-001

## User Story

As a QA Engineer, I want to automate visual regression tests for the Login page so that any unintended UI change is caught before reaching production.

## Acceptance Criteria

- AC-1: TestNG test class LoginPageTest exists in src/test/java
- AC-2: Test opens the live FreshCart URL in a browser via Selenium
- AC-3: Test captures a visual checkpoint of the full login page
- AC-4: Checkpoint runs on Chrome, Firefox, Safari, and mobile viewports via UFG
- AC-5: Test belongs to a named batch: FreshCart Sprint 1 Regression
- AC-6: Match level is set to Strict for static elements
- AC-7: Test passes on first run, creating an initial baseline
- AC-8: Re-run produces no diffs unless the page actually changes

## Definition of Done

- Test code written and committed
- Test runs locally via mvn test
- Baseline created in Applitools dashboard
- Test runs in CI pipeline (FC-102)
- Documentation updated

## Test Scenarios

- Scenario 1: First run creates baseline (expected: pass)
- Scenario 2: Re-run with no UI changes (expected: pass, no diffs)
- Scenario 3: Re-run after intentional UI change (expected: fail with diff for review)

## Linked Stories

- FC-001 (the page being tested)
- FC-101 (deployment that hosts the URL)
- FC-302 (batch strategy)
