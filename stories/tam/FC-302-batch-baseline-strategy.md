# FC-302 — Define Applitools Batch and Baseline Strategy

Type: Story
Role: Technical Account Manager
Status: To Do
Sprint: Sprint 2
Priority: P0
Story Points: 3
Epic: FreshCart Web App MVP

## User Story

As a Technical Account Manager, I want to standardize the Applitools batch naming convention and baseline branching strategy so that the QA team has predictable, traceable test results that align with our Git workflow.

## Acceptance Criteria

- AC-1: Batch naming convention defined: FreshCart [Branch] [Sprint] [Date]
- AC-2: Baseline strategy aligned with Git branches: main, develop, feature
- AC-3: Parent baseline relationship set: develop inherits from main, feature inherits from develop
- AC-4: Match level guidance documented per page type
- AC-5: Ignore region patterns documented for dynamic content
- AC-6: Unit budget calculated and shared with team
- AC-7: Strategy document committed to repo at /docs/applitools-strategy.md
- AC-8: Team trained on the strategy in a 1-hour session

## Definition of Done

- Strategy document written and reviewed
- Batch naming applied to all existing tests
- Baseline branches verified working
- Team trained and acknowledged
- Strategy referenced in QA test code

## Unit Budget Plan

- 3 pages x 8 browser configs = 24 units per full run
- Estimated runs per day: 10 (PR checks plus nightly)
- Daily budget: 240 units
- Monthly budget: 7200 units (within free tier of 100 monthly)

## Linked Stories

- FC-201, FC-202, FC-203, FC-204 (tests using the strategy)
- FC-303 (team documentation)
