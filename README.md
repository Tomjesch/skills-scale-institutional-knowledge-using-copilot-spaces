# OctoAcme Project Management Docs – README

This README is the entry point for OctoAcme's project management playbook. It summarizes our lightweight, evidence-driven lifecycle and links to the detailed process documents stored in this folder. Use this as the starting point for onboarding, reference, and process updates.

## Brief overview of OctoAcme project management processes

OctoAcme runs projects using a customer-first, iterative lifecycle: Initiation → Planning → Execution → Release → Retrospective. Initiation captures the problem, stakeholders, goals and success metrics in a Project One-pager. Planning turns approved initiatives into a prioritized, estimated backlog, with a Definition of Done, release milestones, and a shared risk register.

Day-to-day execution follows a simple board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR process (small PRs, acceptance criteria in PRs, CI gates, security scans, and at least one approval before merging). Releases use standardized checklists, staging smoke tests, rollback plans, and post-deploy verifications. Quality assurance combines automated unit/integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed.

Roles are explicit: Product Managers (define outcomes and success metrics), Project Managers (coordinate delivery, schedule and risks), Developers (implement and test), QA (validate acceptance), and Stakeholders (approve and provide input). Communication cadence includes daily standups, weekly delivery/PM syncs, monthly stakeholder updates, and clear escalation paths. Retrospectives capture learnings and convert them into tracked action items for continuous improvement.

## Documentation index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

---

How to propose changes
- Use the `.github/ISSUE_TEMPLATE/Add content to project management process docs` issue template to request additions or edits.
- Keep docs small and focused; add example artifacts (one-pager, risk register) to the project repo.
