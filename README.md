# FreshCart — Visual Regression Testing Demo

A reference project demonstrating end-to-end visual regression testing using Applitools Eyes, Selenium WebDriver, TestNG, and a real deployed web application.

## Live App

https://deepak-gurejani.github.io/Eyes-testng-lab/

A 3-page demo storefront for a fictional grocery retailer (FreshCart).

- Login page
- Dashboard with metric cards
- Products grid

## Tech Stack

- Frontend: HTML, CSS, vanilla JavaScript
- Hosting: GitHub Pages (HTTPS, free tier)
- Test framework: TestNG
- Browser automation: Selenium WebDriver
- Visual testing: Applitools Eyes (eyes-selenium-java SDK)
- Cross-browser parallelism: Applitools Ultrafast Grid (UFG)
- Build tool: Maven (Java 17)
- CI/CD: GitHub Actions
- Source control: Git, branched workflow (main, develop, feature)

## SDLC Roles Modeled

This project is built with multi-persona thinking to mirror a real engineering team:

- Product Owner: writes user stories with acceptance criteria
- Developer: builds the FreshCart web app (FC-001 to FC-003)
- DevOps Engineer: deploys app and sets up CI (FC-101, FC-102)
- QA Engineer: writes visual regression tests (FC-201 to FC-204)
- Technical Account Manager: configures Applitools, defines strategy, enables team (FC-301 to FC-303)

## Branch Strategy

- main: Production-ready, deploys to GitHub Pages
- develop: Integration branch for sprint work
- feature/ui-changes: Intentional UI changes to demonstrate Applitools diff detection
- docs/po-stories: Product Owner story authoring

## Status

Current sprint: Sprint 2 (Visual Testing setup in progress)

## Note

This is a personal learning lab. It is not affiliated with or endorsed by Applitools as a company.
