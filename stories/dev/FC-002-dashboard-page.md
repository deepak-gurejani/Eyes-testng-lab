# FC-002 — Build Dashboard Page

Type: Story
Role: Developer
Status: Done
Sprint: Sprint 1
Priority: P0
Story Points: 3
Epic: FreshCart Web App MVP

## User Story

As a Developer, I want to build a customer dashboard page showing account summary so that signed-in customers can quickly view their orders, savings, and reward points.

## Acceptance Criteria

- AC-1: Header includes FreshCart logo and navigation
- AC-2: Welcome message includes the customer name
- AC-3: Dynamic timestamp shows last login date and time
- AC-4: Three metric cards displayed: Orders, Saved, Points
- AC-5: Card numbers are large, bold, and green
- AC-6: Cards arranged in a responsive grid
- AC-7: Footer matches the login page footer
- AC-8: Page is responsive across desktop, tablet, and mobile viewports

## Definition of Done

- HTML, CSS, and JS implemented
- Dynamic timestamp working via JavaScript
- Code reviewed via PR
- Merged to develop branch
- Visual regression tests covered by FC-202

## Out of Scope

- Real customer data
- Card click-through actions

## Linked Stories

- FC-001 (login entry point)
- FC-003 (products onward navigation)
- FC-202 (QA visual coverage)
