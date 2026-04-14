# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This README serves as a guide and index for all the process documents that define how we manage projects at OctoAcme.

## Overview: OctoAcme Project Management Processes

OctoAcme's project management processes are built around structured, iterative workflows that channel projects from idea through execution, release, and continuous improvement. The lifecycle begins with project initiation—where proposals are validated, measurable outcomes and success criteria are set, and a one-pager aligns stakeholders. Planning follows, breaking projects into shippable increments with prioritized backlogs, estimation, and risk identification, culminating in kickoff meetings and clear definitions of done. Execution leverages project boards (e.g., GitHub Projects) to track progress with stages like Backlog, In Progress, and QA, reinforced by regular standups, delivery syncs, and end-of-sprint demos.

The methodology emphasizes clear role definitions and team responsibilities. Project Managers (PMs) coordinate delivery, timelines, and stakeholder communication, while Product Managers shape outcomes, manage backlogs, and ensure product-market fit. Developers build and test features, focusing on code quality, review, and agile delivery. QA/Testing roles validate releases, and stakeholders provide approval and ongoing feedback. Each role's communication cadence is intentionally designed, featuring weekly PM/PdM syncs, twice-weekly team standups, monthly stakeholder updates, and structured escalation paths for resolving blockers or risks.

Risk management and communication remain central throughout, with routine risk identification, assessment, and mitigation tracked in a risk register and reviewed in sync meetings. Quality assurance is addressed at multiple layers: developers provide unit, integration, and end-to-end tests; CI pipelines enforce automated checks and security scans; manual QA gates features before acceptance or critical releases. Pre-release protocols include drafted release notes, rollback plans, and post-deployment verification.

Continuous improvement closes the feedback loop—retrospectives after milestones or incidents generate actionable items owned by team members and reviewed weekly. All process changes, rationale, and learnings are versioned and stored in process docs within the repository, ensuring knowledge is centralized, accessible, and iteratively refined for future projects and rapid onboarding.

---

## Communication and Status Reporting for Cross-Functional Projects

> **Addresses:** [Issue #2 — What is the recommended way to set up communication and status reporting across teams for cross-functional projects in OctoAcme?](https://github.com/francisco-guemes/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)

### Communication Cadence

Consistent, role-appropriate communication rhythms keep cross-functional teams aligned and prevent information silos:

| Cadence | Participants | Purpose |
|---|---|---|
| **Twice-weekly standups** | Full team (developers, PM, PdM) | Share daily progress, surface blockers, coordinate dependencies |
| **Weekly PM/PdM sync** | Project Manager + Product Manager | Align on priorities, timelines, and backlog changes |
| **Monthly stakeholder updates** | PM + stakeholders/sponsors | Report milestone progress, risks, and decisions needed |
| **Ad-hoc delivery syncs** | PM + leads | Address immediate blockers or cross-team dependencies |
| **End-of-sprint demos** | Full team + stakeholders | Demonstrate shippable increments and gather feedback |

### Single Source of Truth: Documentation and Dashboards

All project status, decisions, and risk information should be centralized to avoid confusion across teams:

- **Project board** (e.g., GitHub Projects): tracks work items across stages — Backlog, In Progress, QA, Done — visible to all stakeholders.
- **Project README / release doc**: serves as the authoritative status document; updated at each communication milestone.
- **Risk register**: maintained throughout the project lifecycle and reviewed at weekly syncs; captures ID, description, impact, likelihood, owner, mitigation plan, and status.
- **Process docs** (this folder): versioned documentation of all workflows, rationale, and learnings, ensuring knowledge is accessible to new and existing team members.

### Communication Templates

**Weekly Status Update**

```
Progress this week:
Next steps:
Risks & blockers:
Ask / decisions needed:
```

**Incident Communication**

```
Triage summary:
Actions being taken:
Expected timeline:
Post-incident blameless retrospective scheduled: [date]
```

### Escalation Paths

When blockers or risks cannot be resolved at the team level, use the following escalation path:

```
Team-level → Project Manager (PM) → Product Lead → Sponsor
```

For security incidents, follow the security incident runbook and notify the Security on-call team immediately.

---

## Process Document Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management methodology |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to kick off a new project: proposals, success criteria, and stakeholder alignment |
| [Project Planning Guide](./octoacme-project-planning.md) | Breaking work into increments, backlog prioritization, estimation, and risk identification |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Using project boards, standups, and delivery syncs to drive execution |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release types, checklists, rollback plans, and post-deployment verification |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and turning learnings into process improvements |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Definitions and responsibilities for PMs, PdMs, Developers, QA, and stakeholders |

For details on any part of the project management process, see the linked documents above.
