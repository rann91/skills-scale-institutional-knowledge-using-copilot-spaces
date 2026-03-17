# OctoAcme Project Management Docs

This README is your entry point to OctoAcme's project management processes. Below is an overview of how projects are planned, executed, and continuously improved to deliver customer value with transparency and discipline.

## Overview of Project Management Processes

OctoAcme applies a lifecycle-based approach, structured into five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Project work is supported by lightweight, version-controlled documentation, ensuring processes are discoverable, consistent, and continuously improved. The methodology promotes psychological safety, shared ownership, and learning through transparent communication and regular feedback loops.

Key roles include **Project Managers (PMs)** who coordinate delivery and manage risks, **Product Managers (PdMs)** who own strategic outcomes and product vision, **Developers** who implement features and ensure testability, and **QA/Testing** teams who validate quality. Delivery teams operate with daily standups (15 minutes), weekly syncs, sprint-based demos, and regular stakeholder updates. Each project is guided by clear artifacts: project charters/one-pagers, prioritized backlogs with acceptance criteria, risk registers, and actionable retrospective items that drive continuous improvement.

Quality assurance is embedded at every stage, including automated unit, integration, and smoke testing, robust Pull Request conventions (small PRs with automated tests and peer review), and consistent CI practices with security scanning. Risks and dependencies are tracked openly using a weekly-updated risk register and escalated through clearly defined channels: team-level → PM → Product Lead → Sponsor. Communication happens through weekly status templates, monthly stakeholder updates, and incident-driven escalations following a blameless retrospective model.

Continuous improvement is achieved via structured retrospectives (45–75 minutes) held after sprints, releases, or milestones, with 2–3 prioritized action items capturing learnings. The organization uses observability dashboards for key signals (errors, latency, usage) and velocity tracking to measure impact. This closing loop ensures teams continuously learn, iterate on their processes, and maintain a culture of transparency and accountability.

## Process Documentation

Each section below covers a specific stage of the project lifecycle or cross-cutting practice:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Core principles, roles, artifacts, and communication cadence at a glance.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create lightweight plans.
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into shippable increments, identifying dependencies, and defining DoD.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day team rhythm, PR workflows, quality standards, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register, lifecycle, stakeholder communication templates, and escalation paths.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release checklist, deployment workflow, rollback playbook, and release notes.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, tracking improvements, and building a learning culture.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and communication patterns for Developers, Product Managers, Project Managers, and Stakeholders.

## Quick Links by Role

- **As a Project Manager:** Start with [Project Management Overview](octoacme-project-management-overview.md), then explore [Risk Management & Communication](octoacme-risks-and-communication.md) and [Execution & Tracking](octoacme-execution-and-tracking.md).
- **As a Product Manager:** Review [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) for prioritization and acceptance criteria.
- **As a Developer:** Focus on [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflows and quality standards, and [Roles & Personas](octoacme-roles-and-personas.md) for responsibilities.
- **As a QA/Tester:** Review [Execution & Tracking](octoacme-execution-and-tracking.md) for quality standards and [Release & Deployment Guide](octoacme-release-and-deployment.md) for validation steps.

## Getting Started

1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand the five-phase lifecycle and core principles.
2. Refer to the process docs relevant to your current phase or role.
3. Use templates and checklists provided in each document.
4. Keep project artifacts up-to-date in your project repository.
5. Review action items from retrospectives in weekly PM syncs to ensure continuous learning.

For questions or suggestions on improving these processes, please open an issue with the label `process improvement` and reference the relevant process document.