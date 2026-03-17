# OctoAcme — Cross-Functional Checklists

## Purpose
Provide standardized checklists for common project activities to ensure all cross-functional roles understand their responsibilities and handoff criteria.

---

## Release Readiness Checklist

**Owner:** Project Manager (with input from all roles)

- [ ] **Development Complete**
  - [ ] All acceptance criteria met (verified by Developers)
  - [ ] Code reviewed and approved (2+ approvals if policy requires)
  - [ ] All commits have linked issues
  - [ ] Technical debt or known limitations documented

- [ ] **Testing & Quality**
  - [ ] Unit test coverage meets team standard (QA Automation Engineer)
  - [ ] Integration tests passing (QA Automation Engineer)
  - [ ] End-to-end smoke tests prepared (QA Automation Engineer)
  - [ ] Security scanning completed with no blockers (DevOps/SRE)
  - [ ] Manual QA sign-off obtained (QA/Testing)
  - [ ] Design approval confirmed (Design Lead)

- [ ] **Documentation & Communication**
  - [ ] Release notes drafted (Product Manager + Project Manager)
  - [ ] User-facing documentation updated (Product Manager)
  - [ ] Internal runbooks updated (DevOps/SRE)
  - [ ] Stakeholder announcement prepared (Project Manager)

- [ ] **Deployment Preparation**
  - [ ] Deployment plan reviewed (DevOps/SRE)
  - [ ] Rollback procedure documented (DevOps/SRE)
  - [ ] Deployment window scheduled (if needed) (Project Manager)
  - [ ] On-call rotation confirmed (DevOps/SRE)
  - [ ] Post-deployment monitoring configured (DevOps/SRE)

- [ ] **Go/No-Go Decision**
  - [ ] Sponsor approval obtained (Project Manager)
  - [ ] Release blocked or approved (Project Manager)

---

## Feature Kickoff Checklist

**Owner:** Project Manager (facilitated with all roles)

- [ ] **Stakeholder Alignment**
  - [ ] All key stakeholders identified and invited (Project Manager)
  - [ ] Sponsor/executive sponsor confirmed (Project Manager)
  - [ ] Communication plan defined (Project Manager)

- [ ] **Requirements & Scope**
  - [ ] Problem statement clearly articulated (Product Manager)
  - [ ] Success metrics defined and measurable (Product Manager)
  - [ ] Business requirements documented (Business Analyst)
  - [ ] User stories refined with acceptance criteria (Product Manager + Business Analyst)
  - [ ] Scope boundaries defined (no-gos) (Product Manager)

- [ ] **Design & Architecture**
  - [ ] Design concepts reviewed and approved (Design Lead)
  - [ ] Technical approach discussed (Developers)
  - [ ] Architectural risks identified (Developers)
  - [ ] Integration points mapped (Developers + DevOps/SRE)
  - [ ] External dependencies identified (Business Analyst + Project Manager)

- [ ] **Planning & Resources**
  - [ ] Team roles and owners assigned (Project Manager)
  - [ ] Rough effort estimate provided (Developers + Design Lead + QA Automation Engineer)
  - [ ] Timeline and milestones proposed (Project Manager)
  - [ ] Resource conflicts identified (Project Manager)
  - [ ] Vendor/external partner roles clarified (Project Manager)

- [ ] **Risk & Dependencies**
  - [ ] Initial risks identified and captured (all roles)
  - [ ] Cross-team dependencies logged (Project Manager)
  - [ ] Mitigation strategies discussed (Project Manager)

- [ ] **Artifacts & Setup**
  - [ ] Project board/repo skeleton created (Project Manager)
  - [ ] Initial documentation in place (all roles)
  - [ ] Communication channels established (Project Manager)

---

## Design Handoff to Development Checklist

**Owner:** Design Lead (with Developers)

- [ ] **Design Completeness**
  - [ ] All user flows mapped and designed (Design Lead)
  - [ ] Edge cases and error states included (Design Lead)
  - [ ] Accessibility considerations documented (Design Lead)
  - [ ] Design system components used consistently (Design Lead)

- [ ] **Developer Readiness**
  - [ ] Design specs and mockups reviewed by lead developer (Design Lead)
  - [ ] Implementation feasibility discussed (Design Lead + Developers)
  - [ ] Technical questions answered (Design Lead)
  - [ ] Responsive design expectations confirmed (Design Lead)

- [ ] **Documentation & Assets**
  - [ ] Figma links and prototypes shared (Design Lead)
  - [ ] Design tokens/system documented (Design Lead)
  - [ ] Browser/device compatibility expectations documented (Design Lead)
  - [ ] Animation/interaction specs provided if applicable (Design Lead)

- [ ] **Acceptance Criteria**
  - [ ] Visual acceptance criteria defined (Design Lead + Developers)
  - [ ] QA testing criteria for visual correctness included (Design Lead + QA/Testing)
  - [ ] Sign-off process defined (Design Lead)

---

## QA Test Plan Finalization Checklist

**Owner:** QA Automation Engineer (with QA/Testing)

- [ ] **Test Strategy**
  - [ ] Test scenarios identified and prioritized (QA Automation Engineer + QA/Testing)
  - [ ] Automated vs. manual test approach defined (QA Automation Engineer + QA/Testing)
  - [ ] Test data requirements documented (QA Automation Engineer)
  - [ ] Test environments prepared (QA Automation Engineer + DevOps/SRE)

- [ ] **Automation Coverage**
  - [ ] Unit test coverage target defined (QA Automation Engineer + Developers)
  - [ ] Integration test scenarios scoped (QA Automation Engineer + Developers)
  - [ ] End-to-end smoke test scenarios identified (QA Automation Engineer)
  - [ ] Regression test suite scope defined (QA Automation Engineer)

- [ ] **Manual Testing**
  - [ ] Manual test cases documented (QA/Testing)
  - [ ] User acceptance testing (UAT) scope defined if needed (QA/Testing + Product Manager)
  - [ ] Exploratory testing time allocated (QA/Testing)

- [ ] **CI/CD Integration**
  - [ ] Tests integrated into CI pipeline (QA Automation Engineer + DevOps/SRE)
  - [ ] Test failure notifications configured (DevOps/SRE)
  - [ ] Coverage reporting enabled (QA Automation Engineer)

- [ ] **Success Criteria**
  - [ ] Coverage targets defined (QA Automation Engineer)
  - [ ] Pass/fail thresholds established (QA Automation Engineer)
  - [ ] Critical path tests identified (QA Automation Engineer + QA/Testing)

---

## Incident Response Checklist

**Owner:** DevOps/SRE (with Project Manager & all roles as needed)

- [ ] **Immediate Response (First 15 minutes)**
  - [ ] Incident severity assessed (DevOps/SRE)
  - [ ] Incident declared if P1/P2 (DevOps/SRE)
  - [ ] On-call team notified (DevOps/SRE)
  - [ ] Incident channel created (DevOps/SRE)
  - [ ] Rollback plan reviewed (DevOps/SRE + Project Manager)

- [ ] **Stabilization**
  - [ ] Root cause identified (DevOps/SRE + Developers)
  - [ ] Mitigation applied or rollback executed (DevOps/SRE)
  - [ ] System health verified (DevOps/SRE)
  - [ ] Stakeholders notified (Project Manager)

- [ ] **Communication (Ongoing)**
  - [ ] Status updates sent to stakeholders every 30 minutes until resolved (Project Manager)
  - [ ] Customer/support notified of issue and ETA (Project Manager)
  - [ ] Post-incident retrospective scheduled (Project Manager)

- [ ] **Post-Incident (24-48 hours)**
  - [ ] Incident timeline documented (DevOps/SRE)
  - [ ] Root cause analysis completed (DevOps/SRE + Developers)
  - [ ] Action items for prevention identified (all contributors)
  - [ ] Preventive monitoring/alerting implemented (DevOps/SRE)
  - [ ] Incident retrospective held (all contributors)

---

## External Partner / Vendor Onboarding Checklist

**Owner:** Project Manager (with Vendor/Partner)

- [ ] **Agreement & Scope**
  - [ ] Contract or SOW signed (Project Manager)
  - [ ] Scope of work clearly defined (Project Manager)
  - [ ] Deliverables and acceptance criteria documented (Project Manager)
  - [ ] Timeline and milestones agreed (Project Manager)

- [ ] **Integration Planning**
  - [ ] Technical integration requirements documented (Project Manager + Developers)
  - [ ] APIs, data formats, and interfaces defined (Developers)
  - [ ] Security and compliance requirements communicated (Project Manager)
  - [ ] NDAs or data agreements signed if needed (Project Manager)

- [ ] **Communication & Governance**
  - [ ] Primary and secondary contacts identified (Project Manager)
  - [ ] Status meeting cadence established (Project Manager)
  - [ ] Escalation path defined (Project Manager)
  - [ ] Communication channels set up (Project Manager)

- [ ] **Handoff & Acceptance**
  - [ ] Quality acceptance criteria confirmed (Project Manager + QA/Testing)
  - [ ] Testing approach coordinated (Project Manager + QA/Testing)
  - [ ] Sign-off process defined (Project Manager)
  - [ ] Support and maintenance expectations clarified (Project Manager)

---

## Retrospective Action Items Tracking

**Owner:** Project Manager (with all team members)

### Template
- **Action Item ID:** [e.g., RET-001]
- **Description:** [What needs to be improved?]
- **Owner:** [Who is responsible?]
- **Due Date:** [When should this be completed?]
- **Priority:** High / Medium / Low
- **Status:** Open / In Progress / Completed
- **Impact:** [How will this improve future projects?]

### Best Practices
- Assign no more than 2–3 high-priority items per retrospective
- Review outstanding items in weekly PM syncs
- Close items when acceptance criteria are met
- Share learnings across teams for continuous improvement
