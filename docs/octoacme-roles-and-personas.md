# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Design Lead

### Role Summary
Design Leads own the user experience (UX) and design deliverables. They collaborate closely with Product Managers and Developers to ensure features are both functional and user-friendly.

### Responsibilities
- Define and maintain design systems and UI standards
- Create mockups, prototypes, and design specifications
- Conduct user research and usability testing
- Collaborate with Product Managers to clarify feature requirements
- Provide feedback to Developers during implementation
- Document design decisions and rationale
- Participate in design reviews and retrospectives

### Goals
- Deliver intuitive, accessible user experiences
- Ensure design consistency across products
- Reduce rework through early validation
- Enable developers to implement features correctly on first pass

### Key Interactions
- **Product Managers**: Align on feature priority, user needs, and success metrics
- **Developers**: Review designs, answer implementation questions, validate feasibility
- **QA/Testing**: Ensure acceptance criteria capture design intent
- **Stakeholders**: Present design concepts and gather feedback

### Typical Communication
- Design review meetings and design system documentation
- Figma links and mockup comments
- Acceptance criteria sign-off before development

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers develop and maintain automated test scripts to ensure high test coverage, reduce regression risk, and enable faster release cycles. They work alongside Developers and QA/Testing to validate quality.

### Responsibilities
- Design and implement automated test suites (unit, integration, end-to-end)
- Maintain test infrastructure and CI/CD test pipelines
- Ensure high coverage for critical flows and regression scenarios
- Collaborate with Developers to understand new features
- Update test cases based on release cycles and feature changes
- Report on test coverage metrics and test effectiveness
- Participate in test planning and acceptance criteria refinement

### Goals
- Enable faster, safer releases through automation
- Reduce manual testing burden
- Catch regressions early in the CI pipeline
- Maintain high code and feature coverage

### Key Interactions
- **Developers**: Understand new code, collaborate on test strategies, review test results
- **QA/Testing**: Coordinate test scenarios, share findings, support manual testing
- **DevOps/SRE**: Integrate tests into deployment pipelines
- **Project Manager**: Report on test readiness and blockers

### Typical Communication
- Test automation plans and coverage reports
- CI/CD pipeline status and test failure notifications
- QA planning sessions and retrospectives

---

## DevOps / Site Reliability Engineer (SRE)

### Role Summary
DevOps and Site Reliability Engineers (SREs) oversee deployment pipelines, infrastructure reliability, monitoring, and observability. They enable the team to deploy safely and respond quickly to production issues.

### Responsibilities
- Design and maintain CI/CD deployment pipelines
- Manage infrastructure, configuration, and environments
- Implement monitoring, logging, and alerting systems
- Manage production incidents and post-mortems
- Optimize infrastructure performance and cost
- Collaborate with Developers on deployment practices
- Document runbooks and incident response procedures
- Plan for disaster recovery and business continuity

### Goals
- Enable frequent, reliable deployments
- Minimize downtime and mean time to recovery (MTTR)
- Maintain high system availability and performance
- Reduce operational toil through automation

### Key Interactions
- **Developers**: Support deployment practices, CI/CD optimization, incident response
- **Project Manager**: Notify of incidents, release windows, and infrastructure risks
- **QA Automation Engineer**: Integrate smoke tests and automated validation into pipelines
- **Security/Compliance**: Implement security scanning and compliance monitoring

### Typical Communication
- Deployment runbooks and incident playbooks
- SLO dashboards and reliability metrics
- Weekly infrastructure and incident review meetings

---

## Business Analyst

### Role Summary
Business Analysts translate business requirements into actionable artifacts. They support Product Managers and Project Managers in discovery, backlog refinement, and process analysis to ensure alignment between business goals and technical delivery.

### Responsibilities
- Conduct stakeholder discovery and requirements gathering
- Document business processes and acceptance criteria
- Support backlog prioritization and refinement
- Analyze business metrics and impact
- Create process documentation and workflow diagrams
- Identify process inefficiencies and improvement opportunities
- Bridge communication between business and technical teams
- Support training and change management

### Goals
- Ensure business requirements are clearly understood by the team
- Reduce scope creep and rework through clear acceptance criteria
- Identify process improvements that increase efficiency
- Enable data-driven business decisions

### Key Interactions
- **Product Managers**: Refine user stories, validate requirements, analyze business impact
- **Project Managers**: Support planning, identify risks and dependencies
- **Developers**: Clarify requirements, answer technical feasibility questions
- **Stakeholders**: Gather requirements, validate solutions, communicate progress

### Typical Communication
- Requirements documentation and user story templates
- Business process diagrams and flowcharts
- Weekly stakeholder alignment meetings

---

## External Partner / Vendor

### Role Summary
External Partners and Vendors provide specialist expertise, deliver project components, or provide services as part of the project scope. They follow established integration and communication protocols to ensure seamless collaboration.

### Responsibilities
- Deliver agreed-upon components or services per contract
- Maintain communication with assigned Project Manager
- Report progress, blockers, and deliverables on schedule
- Participate in dependency planning and risk discussions
- Document integrations and handoff procedures
- Support testing and acceptance of deliverables
- Adhere to security, compliance, and quality standards

### Goals
- Deliver quality work on time per contract terms
- Minimize integration friction and rework
- Enable the project to meet commitments without over-extending internal resources
- Maintain clear, professional communication

### Key Interactions
- **Project Manager**: Primary point of contact for scope, schedule, and issues
- **Developers**: Collaborate on technical integration, APIs, and acceptance criteria
- **QA/Testing**: Validate deliverables meet quality standards
- **Security/Compliance**: Ensure vendor work meets security and compliance requirements

### Typical Communication
- Weekly status meetings and progress reports
- Integration specifications and technical documentation
- Acceptance criteria and delivery sign-off

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Support Business Analysts in requirements refinement

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Manage external partner relationships and vendor integration
- Escalate issues and blockers appropriately

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction guidelines to clarify handoffs and dependencies in your project workflows.
