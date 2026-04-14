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

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

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

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards before release. They design and execute test plans, surface defects, and champion quality throughout the delivery lifecycle.

### Responsibilities
- Design and maintain test plans, test cases, and automated test suites
- Execute manual and automated regression tests before releases
- Log, triage, and track defects to resolution
- Verify acceptance criteria with developers and Product Managers
- Contribute to the Definition of Done and quality gates

### Goals
- Prevent defects from reaching production
- Enable fast, confident releases
- Promote testability in design and implementation

### Interactions
Works closely with Developers on defect triage; coordinates with Project Manager on release readiness; collaborates with Product Manager on acceptance criteria; partners with DevOps Engineer on CI test integration.

---

## UX/UI Designer

### Role Summary
UX/UI Designers own user experience and interface design, ensuring usability, accessibility, and visual consistency across product features.

### Responsibilities
- Collaborate with Product Manager to clarify user needs and translate them into design requirements
- Produce wireframes, prototypes, and final UI assets
- Facilitate usability testing and incorporate feedback into designs
- Maintain and evolve design systems and component libraries
- Work closely with Developers to ensure design fidelity during implementation
- Participate in design reviews and definition-of-done gates

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce rework by aligning design and engineering early
- Advocate for the user in every project phase

### Interactions
Works with Product Manager for requirements alignment; partners with Developers for implementation fidelity; coordinates with QA on usability validation; consults Technical Writer on in-product copy and onboarding flows.

---

## Technical Writer

### Role Summary
Technical Writers develop and maintain user-facing and internal documentation, ensuring that knowledge is accurate, well-structured, and accessible to all relevant audiences.

### Responsibilities
- Work with Developers and Product Managers to produce accurate feature documentation and release notes
- Update process docs, API references, onboarding materials, and user guides
- Drive consistency and clarity in all written artifacts
- Review and edit documentation contributions from other team members
- Maintain the docs/ folder and documentation index (README)

### Goals
- Ensure every role and feature is clearly documented to reduce single-person dependency
- Support fast onboarding by keeping documentation current and approachable
- Provide a centralized knowledge base for the team and stakeholders

### Interactions
Collaborates with all roles for content accuracy; works with Product Manager for feature context; works with Developers and DevOps Engineer for technical accuracy; incorporates feedback from Support/Customer Success on common user questions.

---

## DevOps Engineer

### Role Summary
DevOps Engineers ensure reliable, repeatable deployment pipelines and operational excellence. They manage infrastructure, CI/CD systems, and support incident response.

### Responsibilities
- Configure, maintain, and improve CI/CD pipelines and automation
- Manage infrastructure provisioning and environment configuration (infrastructure-as-code)
- Monitor deployment health, reliability, and performance
- Support incident response and coordinate post-release monitoring
- Enforce security and compliance controls in the deployment pipeline
- Coordinate with Project Manager for release scheduling and deployment windows

### Goals
- Achieve fast, reliable, and safe deployments
- Minimize mean time to recovery (MTTR) for production incidents
- Reduce manual toil through automation

### Interactions
Works closely with Developers for deployment readiness; coordinates with QA on CI test integration; partners with Security Lead for secure pipeline configurations; collaborates with Project Manager on release scheduling; supports Support/Customer Success during post-release monitoring.

---

## Support / Customer Success

### Role Summary
Support and Customer Success roles act as the bridge between end users/customers and the development team, ensuring feedback loops are closed and users are informed.

### Responsibilities
- Collect, triage, and prioritize user feedback and reported issues
- Communicate product updates, release notes, and incident resolutions to users
- Surface actionable insights to the Product Manager and Project Manager
- Maintain user-facing FAQs, known-issues lists, and support documentation
- Coordinate with DevOps Engineer during production incidents to track user impact

### Goals
- Maximize user satisfaction and adoption
- Ensure development teams hear and act on user feedback
- Reduce time-to-resolution for support issues

### Interactions
Interfaces directly with end users; feeds user insights to Product Manager and Project Manager; coordinates with Technical Writer for user documentation; works with DevOps Engineer during incidents; consults Security Lead on security-related user concerns.

---

## Security Lead

### Role Summary
The Security Lead is responsible for embedding security best practices into all stages of the project lifecycle and ensuring compliance with security policies and standards.

### Responsibilities
- Review designs, architecture, and code for security vulnerabilities
- Define and communicate security policies, standards, and compliance requirements
- Lead security incident triage, post-mortems, and remediation tracking
- Collaborate with DevOps Engineer to ensure secure pipeline and infrastructure configurations
- Educate and coach team members on secure coding and threat modeling
- Own the security risk register and escalate critical findings

### Goals
- Prevent security vulnerabilities from reaching production
- Build a security-aware team culture
- Ensure compliance with relevant standards and regulations

### Interactions
Works with Developers for secure code reviews and threat modeling; partners with Project Manager for risk assessment and security milestones; collaborates with DevOps Engineer for secure deployments and pipeline hardening; advises Product Manager on security trade-offs; supports incident response with Support/Customer Success.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when assigning ownership in process docs, checklists, and templates.

