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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional recommended personas (new)

These roles are commonly present in modern product teams and help close gaps in handoffs, documentation, release coordination, and measurement. Add short descriptions, responsibilities, and interactions for each of the following to improve clarity and accountability.

### UX Designer
Role summary:
- Responsible for user research, product UX strategy, wireframes/prototypes, and usability validation.

Responsibilities:
- Conduct user interviews and usability testing
- Produce wireframes, prototypes, and design specs
- Validate designs against accessibility and usability standards
- Provide design input during backlog refinement and sprint planning

How they interact with existing roles:
- Work with Product Managers to define user problems and success criteria
- Partner with Developers to ensure designs are implementable and testable
- Collaborate with QA to validate UX acceptance criteria during testing

Typical communication:
- Design critiques, stakeholder demos, and handoff sessions
- Deliver design artifacts (Figma, prototypes, annotated flows)

---

### Technical Writer
Role summary:
- Owns user-facing and developer-facing documentation, guides, and release notes.

Responsibilities:
- Maintain user docs, API references, and runbooks
- Collaborate with developers to keep docs up to date when APIs or features change
- Draft release notes and migration guides
- Ensure documentation meets style and accessibility guidelines

How they interact with existing roles:
- Work with Developers and QA to capture technical details and verification steps
- Pair with Product Managers to document feature intent and acceptance criteria
- Coordinate with Release Manager to produce release notes

Typical communication:
- Doc reviews in PRs, regular syncs with engineering and product

---

### Release Manager
Role summary:
- Coordinates release planning, release criteria, deployment windows, and communications across teams.

Responsibilities:
- Maintain release calendar and coordinate release cutoffs
- Ensure pre-release checks (CI, security scans, smoke tests) are completed
- Orchestrate rollback plans and incident communications if needed
- Conduct release readiness reviews

How they interact with existing roles:
- Coordinate with Developers, QA, and DevOps for deployment readiness
- Work with Product Managers and PMs to schedule releases and stakeholder communications
- Source release notes from Technical Writer and Product Manager

Typical communication:
- Release readiness meetings, deployment announcements, incident updates

---

### Business Analyst
Role summary:
- Bridges product and stakeholder needs with technical implementation by clarifying requirements and success measures.

Responsibilities:
- Elicit and document business requirements and user journeys
- Analyze data to validate business assumptions and outcomes
- Assist in backlog refinement and acceptance criteria creation
- Track requirement-to-delivery traceability

How they interact with existing roles:
- Work with Product Managers to translate business goals into backlog items
- Collaborate with Developers and QA to ensure acceptance criteria are testable
- Report findings to stakeholders and product leadership

Typical communication:
- Requirement workshops, stakeholder interviews, and acceptance test definitions

---

### DevOps / Platform Engineer (recommended)
Role summary:
- Design and maintain CI/CD pipelines, platform reliability, and operational automation.

Responsibilities:
- Build and maintain deployment pipelines and infrastructure as code
- Monitor system health and implement alerts/observability
- Support incident response and post-incident remediation

How they interact with existing roles:
- Work with Developers, QA, and Release Manager on deployment and observability requirements
- Provide runbooks and production support guidance to PMs and stakeholders

Typical communication:
- On-call rotation updates, runbook maintenance, and deployment coordination

---

### Data Analyst (recommended)
Role summary:
- Provides measurement and reporting to validate success metrics and product impact.

Responsibilities:
- Define instrumentation needs for experiments and features
- Build dashboards and reports to track success metrics
- Support Product and PM decisions with data analysis

How they interact with existing roles:
- Collaborate with Product Managers to define measurable success criteria
- Work with Developers to ensure proper instrumentation is implemented
- Share dashboards with stakeholders and PMs

Typical communication:
- Dashboards, metric definitions, and regular metric reviews

---

## Using the persona entries

- Each persona entry should include:
  - Role summary (one-sentence)
  - Responsibilities (bulleted)
  - How they interact with existing roles (hand-offs and collaboration)
  - Typical communication channels and artifacts

- Keep entries concise (one to three short paragraphs + 4–8 bullets) so they remain useful during planning and onboarding.
