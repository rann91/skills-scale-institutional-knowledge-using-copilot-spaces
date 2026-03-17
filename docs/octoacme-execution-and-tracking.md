# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups** (15 min) — focus on progress, blockers, dependencies. All roles encouraged to attend.
- **Weekly delivery sync** — show progress, updates, and flagged risks. Led by PM and PdM.
- **Demo/Review** at the end of each sprint or milestone. All roles present findings and gather feedback.
- **Weekly PM/PdM sync** — alignment on roadmap, risks, and stakeholder communication.

## Cross-Functional Execution

### Role Responsibilities During Execution

**Developers**
- Implement features according to acceptance criteria
- Raise technical risks and blockers in standups
- Collaborate with Design Lead on implementation questions
- Ensure code is tested and ready for QA

**Design Lead**
- Review design implementation during development
- Answer design clarification questions from Developers
- Coordinate with QA on visual acceptance criteria
- Document design decisions and deviations

**QA Automation Engineer**
- Write and maintain automated tests in parallel with development
- Report test coverage and failures
- Coordinate with Developers on test scenarios
- Prepare regression test suite for releases

**QA/Testing**
- Perform manual testing and acceptance validation
- Report issues and blockers
- Collaborate with QA Automation Engineer on testing strategy
- Sign-off on feature readiness

**DevOps/SRE**
- Monitor CI/CD pipeline and test infrastructure
- Optimize deployment processes
- Monitor production health and performance
- Escalate infrastructure issues

**Project Manager**
- Track progress against timeline
- Identify and escalate blockers
- Manage cross-team dependencies
- Update stakeholders on status and risks

**Business Analyst**
- Clarify requirements and acceptance criteria
- Support backlog refinement
- Capture scope changes and impact
- Support stakeholder alignment

## Workflows
- **Project Board**: Use columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Pull Request workflow**:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - Link to Design approval if visual changes included

## Quality & Testing
- **Unit tests** for new logic (written by Developers, reviewed in PR)
- **Integration tests** where applicable (developed by QA Automation Engineer)
- **End-to-end smoke tests** for critical flows before release (prepared by QA Automation Engineer)
- **Security scanning** in CI (configured by DevOps/SRE)
- **Manual QA** for feature acceptance when needed (performed by QA/Testing)
- **Design verification** for visual correctness (verified by Design Lead)

## Reporting & Metrics
- Track velocity and burndown (PM)
- Monitor success metrics identified in the Project One-pager (Product Manager)
- Use dashboards for key signals: errors, latency, usage, test coverage (DevOps/SRE + QA Automation Engineer)
- Share status reports with stakeholders weekly (PM)

## Blocker Escalation

### Escalation Path
- **Level 1**: Team-level triage in daily standup (all roles)
- **Level 2**: PM escalates to Product Lead and dependent teams within 24 hours
- **Level 3**: PM escalates to Sponsor for business-impacting issues within 4 hours
- **Level 4** (Production Issues): DevOps/SRE escalates to on-call leadership per incident response playbook

### When to Escalate
- Timeline risk: Feature unlikely to meet planned release date
- Resource risk: Team member unavailable; cannot backfill
- Dependency risk: External blocker outside team control
- Quality risk: Test coverage below acceptable threshold
- Production issues: Live customer impact

## Execution Checklist

- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning
- [ ] Regular demos scheduled and stakeholders invited
- [ ] Risk register updated weekly
- [ ] Cross-functional roles confirmed and communication paths clear
- [ ] Project board visible to all stakeholders
- [ ] Status reports shared with stakeholders by Friday COB each week
- [ ] Blocker escalation path communicated to team
- [ ] Design review process integrated into PR workflow
- [ ] QA acceptance criteria aligned with acceptance criteria in backlog items
