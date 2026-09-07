# OctoAcme Project Management Processes

## Executive summary
OctoAcme runs projects with a clear, iterative lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Projects begin with a lightweight Project One-pager and stakeholder alignment to confirm the problem, success metrics, and go/no‑go. Approved initiatives move into planning where the team creates a prioritized backlog, sizes work, defines a Definition of Done (DoD), and captures risks and dependencies in a Risk Register.

## Delivery workflows and pull requests
Day-to-day delivery follows disciplined workflows: timeboxed sprint planning, a prioritized backlog with clear acceptance criteria, and a visible project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Pull requests should be small when possible (≈ ≤400 lines), reference the related issue and acceptance criteria, run CI (tests and linting) before review, and require at least one approval prior to merging. Release activities include staging smoke tests, release notes, and a rollback/mitigation plan for safe deployments.

## Roles, ownership, and communication
Roles and ownership are explicit: Product Managers define outcomes and priorities; Project Managers coordinate schedule, risks, and communications; Developers implement and test; QA validates acceptance criteria and runs manual checks as needed; Stakeholders provide approvals and inputs. Communication cadence includes daily standups for progress and blockers, a weekly delivery sync to surface risks and progress, sprint/milestone demos, and periodic stakeholder updates. Escalation follows a defined path: team → PM → Product Lead → Sponsor.

## Quality assurance and monitoring
QA is integrated into the workflow: unit and integration tests for new logic, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when necessary. Teams track velocity and burndown, monitor success metrics from the Project One-pager, and use dashboards for operational signals (errors, latency, usage). Risk items are tracked in a Risk Register and reviewed regularly; blockers are escalated according to the documented paths.

## Table of contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick reference — key artifacts
- Project One-pager (problem, goal, success metrics)
- Backlog items with acceptance criteria & DoD
- Risk Register (ID, impact, likelihood, owner, mitigation)
- Release notes & rollback plan
- Sprint/iteration backlog and velocity reports

## Onboarding note
This README is intended as the single-entry navigation hub for OctoAcme process docs. Keep the Project One-pager and process-specific artifacts updated in their respective files under docs/, and add new process docs through the repository's process doc issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
