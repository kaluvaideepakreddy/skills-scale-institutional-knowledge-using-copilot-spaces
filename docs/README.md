# OctoAcme Project Management Docs

This README provides an overview of OctoAcme's project management processes and serves as a directory for all process documentation stored in this repo's docs/ folder. It is intended to help new team members onboard quickly and to act as a single source of truth for how we initiate, plan, execute, release, and continuously improve our work.

OctoAcme follows a stage-based lifecycle: Initiation (define the problem, success metrics, stakeholders, and get approval), Planning (create the backlog, estimate scope, define milestones, and identify dependencies), Execution & Tracking (manage day-to-day work on a project board, use small PRs, follow CI and review rules, and run standups/demos), Release & Deployment (pre-release checks, staged deployments, smoke tests, and rollback plans), Risk Management & Communication (maintain a risk register, follow escalation paths, and provide regular stakeholder updates), and Retrospective & Continuous Improvement (capture learnings, create action items, and track results).

Roles and responsibilities are clearly defined so ownership is explicit: Product Managers set outcomes and priorities, Project Managers coordinate delivery and communication, Developers implement and test, QA ensures acceptance criteria and quality, and Stakeholders provide inputs and approvals. Our communication cadence includes daily standups, weekly delivery syncs, PM+PdM alignment meetings, milestone demos, and periodic stakeholder updates; incident and status templates help standardize reporting.

Quality is enforced through automated testing and security scanning in CI, supplemented by integration and end-to-end smoke tests for critical flows and manual QA where needed. Pull requests should be small and include issue links and acceptance criteria; CI must pass and at least one approval is required before merging. Retrospectives feed improvements back into the backlog and our process docs to keep practices current.

## Docs Directory

- [Project Management Overview](./octoacme-project-management-overview.md)  
- [Project Initiation Guide](./octoacme-project-initiation.md)  
- [Project Planning](./octoacme-project-planning.md)  
- [Execution & Tracking](./octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](./octoacme-risks-and-communication.md)  
- [Release & Deployment](./octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use
- Use this README as a starting point to find process docs and templates.
- If you want to propose updates, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
- For edits, create a small PR referencing the relevant issue and include acceptance criteria in the PR description.
