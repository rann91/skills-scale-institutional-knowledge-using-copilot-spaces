# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

### Lead Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications. Owns project timeline and stakeholder alignment.
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success. Owns product vision and customer value.

### Delivery Roles
- **Developers**: Implement features, collaborate on design and testability.
- **Design Lead**: Owns user experience, manages design deliverables, collaborates with PM and Developers.
- **QA/Testing**: Validates quality and acceptance criteria.
- **QA Automation Engineer**: Develops and maintains automation scripts, ensures regression coverage.

### Infrastructure & Support Roles
- **DevOps/SRE**: Manages deployment pipelines, infrastructure reliability, and monitoring.
- **Business Analyst**: Translates business requirements into actionable artifacts, supports discovery.

### External Contributors
- **External Partners/Vendors**: Provide specialist input or deliver components per contract scope.

### Stakeholders
- Provide inputs, approvals, and strategic direction.

---

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Cross-functional checklists (release, kickoff, handoff, QA, incident response)
- Retrospective notes and action items

## Lifecycle (high-level)
1. **Initiation**: Problem statement, stakeholders, high-level timeline.
2. **Planning**: Scope, resources, milestones, dependencies, roles clarified.
3. **Execution**: Build, test, review, iterate with cross-functional coordination.
4. **Release**: Deploy, verify, announce with all role responsibilities confirmed.
5. **Close & Retrospective**: Capture learnings and next steps.

## Communication Cadence
- **Weekly PM/PdM Sync**: Alignment on priorities, risks, progress.
- **Twice-weekly Standups**: Delivery team (Engineering, Design, QA, DevOps).
- **Monthly Stakeholder Updates**: Status, milestones, business impact.
- **Ad-hoc Escalations**: Risk, blockers, critical decisions as needed.

## Cross-Functional Handoff Responsibilities

Each phase transition requires explicit handoff and sign-off from relevant roles:

| Phase Transition | Owner | Sign-offs Required |
|---|---|---|
| Design → Development | Design Lead + PM | Developers, Technical Lead |
| Development → QA | Developers + QA Automation Engineer | QA/Testing, PM |
| QA → Release | QA/Testing + DevOps/SRE | Project Manager |
| Release → Post-Launch | DevOps/SRE + PM | Stakeholders, Product Manager |

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `docs/` for easy reference.
- Use cross-functional checklists to standardize handoffs and reduce ambiguity.
- Reference role definitions to clarify responsibilities at each project phase.
