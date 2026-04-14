# OctoAcme — Handoff & Quality Gates

## Purpose
Define role-specific quality gates and handoff checklists to ensure smooth transitions between project phases and reduce gaps caused by unclear ownership.

---

## Phase Handoff Overview

| From Phase | To Phase | Primary Owner | Key Handoff Artifact |
|---|---|---|---|
| Initiation | Planning | Project Manager | Approved Project One-pager |
| Planning | Execution | Project Manager + Product Manager | Prioritized backlog, Definition of Done, kickoff meeting |
| Execution | QA / Review | Developers + QA | PR merged, acceptance criteria met, test results |
| QA / Review | Release | QA + DevOps Engineer | QA sign-off, deployment checklist |
| Release | Close & Retrospective | Project Manager | Post-deploy verification, release announcement |

---

## Role-Specific Quality Gates

### UX/UI Designer Gate
Before development begins on any user-facing feature:
- [ ] Wireframes or high-fidelity mockups reviewed and approved by Product Manager
- [ ] Accessibility requirements identified and incorporated in designs
- [ ] Design assets handed off to Developers in agreed format
- [ ] Design review session held with at least one Developer

### Technical Writer Gate
Before a feature or release is marked complete:
- [ ] Feature documentation drafted or updated (user guide, API reference, release notes)
- [ ] Onboarding materials updated if the feature changes a core workflow
- [ ] Documentation reviewed by at least one Developer or Product Manager for accuracy
- [ ] New or changed processes reflected in the appropriate docs/ document

### DevOps Engineer Gate
Before any deployment to staging or production:
- [ ] CI pipeline passing (tests, lint, security scans)
- [ ] Infrastructure changes reviewed and approved (infrastructure-as-code PR merged)
- [ ] Deployment runbook updated for any new environment or configuration change
- [ ] Rollback plan documented and tested where feasible
- [ ] Deployment window communicated to Project Manager and Support/Customer Success

### Security Lead Gate
For any release with new authentication, authorization, data handling, or external integrations:
- [ ] Threat model reviewed and accepted risks documented
- [ ] Security code review completed for relevant changes
- [ ] Dependency vulnerability scan reviewed and critical findings resolved
- [ ] Security sign-off recorded (issue comment or PR approval)
- [ ] Compliance requirements checked (e.g., data privacy, access controls)

### Support / Customer Success Gate
Before a public-facing release:
- [ ] Release notes shared with Support team for review
- [ ] Known issues list updated
- [ ] Support runbook updated for new features or changed behaviors
- [ ] Communication drafted for users (in-app notification, email, or changelog)
- [ ] Escalation path confirmed for post-release issues

---

## Cross-Role Handoff Checklist Template

Use this template when formally handing off work between phases or teams:

```
Handoff Date:
From Role / Team:
To Role / Team:
Project / Feature:

Artifacts Delivered:
- [ ] Link or attachment:

Acceptance Criteria Status:
- [ ] All AC met: Yes / No / Partial (explain below)

Open Items / Known Issues:
- Item:
  Owner:
  Due date:

Dependencies or Risks:
- Description:
  Mitigation:

Sign-off:
- Delivering role:
- Receiving role:
```

---

## Onboarding Quick-Reference

To reduce single-person dependency and support fast onboarding, each new team member should:

1. Read the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) docs.
2. Review the active Risk Register and project board.
3. Complete a 1:1 with the Project Manager for context on current status, risks, and blockers.
4. Shadow one full sprint cycle before taking on independent ownership.
5. Identify a buddy from an adjacent role for cross-role collaboration clarity.

---

## Continuous Improvement for Handoffs
- Capture handoff friction points in sprint retrospectives.
- Update this document when new gaps are identified.
- Review the cross-role handoff checklist template at least once per quarter.
