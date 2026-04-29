# OctoAcme Project Management Docs

Welcome! This README provides an overview of OctoAcme's project management approach and quick links to all process documentation in this folder.

## Project Management Overview

OctoAcme uses a cross-functional, iterative project management approach with defined roles, clear decision gates, and a focus on transparency and continuous improvement. The process moves through five key phases:

1. **Initiation** — Validate the business need, identify stakeholders, define success metrics, and produce a project one-pager with a high-level timeline, risks, and resource needs.
2. **Planning** — Run a kickoff, define scope and dependencies, estimate work, document the Definition of Done, and create a release and milestone map.
3. **Execution & Tracking** — Deliver in small increments using daily standups, weekly delivery syncs, and a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done. Keep pull requests small, linked to issues, and reviewed before merge.
4. **Release** — Ensure acceptance criteria are met, tests pass, release notes are drafted, and a rollback plan is in place before deployment.
5. **Retrospective** — Capture lessons learned and convert them into tracked action items to support continuous improvement.

## Key Roles & Personas

| Role | Responsibilities |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, documentation, and stakeholder communication |
| **Product Manager (PdM)** | Owns outcomes, prioritizes the backlog, and measures success metrics |
| **Developers** | Implement features, write tests, participate in reviews, and identify technical risks |
| **QA / Testing** | Validates acceptance criteria and release quality |
| **Stakeholders** | Provide inputs and approvals at key decision points |

## Communication Practices

- **Daily standups** to surface progress, blockers, and dependencies
- **Weekly delivery syncs** for status updates and risk review
- **Monthly stakeholder updates** for broader alignment
- Status reports follow a consistent template: progress, next steps, risks/blockers, and decisions needed
- **Escalation path**: team-level triage → PM → Product Lead → Sponsor

## Quality Assurance

- Small pull requests linked to issues, with acceptance criteria in PR descriptions
- CI testing, linting, and security scanning before merge
- At least one approval required before merging
- Unit tests, integration tests, smoke tests for critical flows, and manual QA as needed
- Releases require all tests to pass and a rollback plan to be ready

---

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level principles, roles, lifecycle, and communication cadence |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps and checklist for starting a new project |
| [Project Planning](octoacme-project-planning.md) | Scope definition, backlog setup, and milestone planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Delivery workflow, board management, and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, status updates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and rollback procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for each role on the team |
