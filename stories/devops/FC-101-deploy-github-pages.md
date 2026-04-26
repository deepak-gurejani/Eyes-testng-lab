# FC-101 — Deploy FreshCart to Public Hosting

Type: Story
Role: DevOps Engineer
Status: Done
Sprint: Sprint 1
Priority: P0
Story Points: 2
Epic: FreshCart Web App MVP

## User Story

As a DevOps Engineer, I want to deploy the FreshCart web app to a public hosting platform so that the app is accessible from any device, anywhere, and ready for QA testing.

## Acceptance Criteria

- AC-1: App is hosted on GitHub Pages with HTTPS enabled
- AC-2: Public URL is accessible from external networks
- AC-3: Hosting source configured: main branch, /docs folder
- AC-4: App loads correctly on Chrome, Safari, Firefox, and mobile browsers
- AC-5: All 3 pages (login, dashboard, products) are reachable
- AC-6: HTTPS is enforced
- AC-7: Deployment is automated on every push to main

## Definition of Done

- GitHub Pages enabled
- Site successfully built
- URL verified accessible from external network
- HTTPS confirmed

## Technical Notes

- Hosting cost: 0 dollars (GitHub Pages free tier)
- Build time: 1 to 3 minutes per push
- Domain: GitHub-provided subdomain

## Linked Stories

- FC-001, FC-002, FC-003 (the app being deployed)
- FC-102 (CI automation)
