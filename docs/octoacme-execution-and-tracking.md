# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer + QA collaboration)
- End-to-end smoke tests for critical flows before release (QA + DevOps Engineer)
- Security scanning in CI (DevOps Engineer + Security Lead)
- Accessibility testing for UI changes (UX Designer + QA)
- Manual QA for feature acceptance when needed
- Data validation for analytics features (Data Analyst involvement)

## Reporting & Metrics
- Track velocity and burndown (PM responsibility)
- Monitor success metrics identified in the Project One-pager (Data Analyst creates dashboards)
- Use dashboards for key signals (errors, latency, usage) — DevOps Engineer maintains observability
- Report on security posture and vulnerabilities (Security Lead provides updates)

## Blocker Escalation
- **Level 1:** Team-level triage in daily standup (Developer, UX Designer, QA collaborate)
- **Level 2:** PM escalates to Product Lead and dependent teams; DevOps Engineer for infrastructure issues; Security Lead for security concerns
- **Level 3:** Sponsor/Executive Stakeholder escalation for business-impacting issues or when cross-organizational alignment is needed

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
