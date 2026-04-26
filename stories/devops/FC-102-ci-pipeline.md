# FC-102 — Set Up CI/CD Pipeline for Visual Tests

Type: Story
Role: DevOps Engineer
Status: To Do
Sprint: Sprint 2
Priority: P1
Story Points: 5
Epic: FreshCart Web App MVP

## User Story

As a DevOps Engineer, I want to set up an automated CI pipeline that runs visual regression tests on every pull request so that UI changes are automatically validated before being merged into main.

## Acceptance Criteria

- AC-1: GitHub Actions workflow file exists at .github/workflows/qa-tests.yml
- AC-2: Workflow triggers on every pull request to main and develop
- AC-3: Workflow uses Maven to install dependencies
- AC-4: Workflow runs the TestNG suite via mvn test
- AC-5: Applitools API key stored securely as a GitHub Secret
- AC-6: Workflow failure blocks the pull request from merging
- AC-7: Test results visible in the PR check status
- AC-8: Build duration is under 10 minutes

## Definition of Done

- Workflow YAML file written and committed
- APPLITOOLS_API_KEY added to GitHub Secrets
- Test PR demonstrates pipeline triggers correctly
- Failing test correctly blocks merge
- Documentation updated for team

## Technical Notes

- Use actions/setup-java with JDK 17
- Cache Maven dependencies for faster builds
- Run tests in headless Chrome via UFG

## Linked Stories

- FC-101 (app must be deployed first)
- FC-201, FC-202, FC-203 (the tests this pipeline runs)
- FC-302 (TAM-defined batch strategy)
