# FC-301 — Applitools Account and API Key Setup

Type: Story
Role: Technical Account Manager
Status: To Do
Sprint: Sprint 2
Priority: P0
Story Points: 2
Epic: FreshCart Web App MVP

## User Story

As a Technical Account Manager, I want to configure the Applitools account and API key for the FreshCart project so that the QA team can immediately start writing and running visual tests without infrastructure delays.

## Acceptance Criteria

- AC-1: Applitools free tier account created
- AC-2: New project named FreshCart created in Applitools dashboard
- AC-3: API key generated and securely shared with the team
- AC-4: API key stored locally as APPLITOOLS_API_KEY environment variable
- AC-5: API key added to GitHub Secrets for CI use (covered by FC-102)
- AC-6: Applitools dashboard access granted to QA team members
- AC-7: Team region (US/EU) confirmed and documented
- AC-8: Free tier limits documented (units per month, retention)

## Definition of Done

- Account created and verified
- API key working locally
- API key working in GitHub Actions
- Team has dashboard access
- Quick-start guide written for QA team

## Linked Stories

- FC-102 (CI pipeline using API key)
- FC-201, FC-202, FC-203 (tests requiring API key)
