# OctoAcme Project Management Docs

## Overview

OctoAcme uses a lightweight, repeatable project-management framework to move work from idea to delivery with clarity and predictability. Projects begin with a short Project One‑pager to validate the problem, define measurable success metrics, identify stakeholders, and capture initial risks. Approved initiatives move into planning where work is broken into shippable increments, acceptance criteria and a Definition of Done are defined, estimates are captured, and a release plan is mapped to milestones.

Day‑to‑day delivery is coordinated through a project board (Backlog → Ready → In Progress → In Review → QA → Done), a disciplined pull‑request workflow (small PRs, explicit acceptance criteria, CI checks, and reviewer approvals), and a regular team rhythm that includes daily standups, weekly delivery syncs, and sprint demos. The process emphasizes clear ownership — each project has named PM and Product Lead responsibilities — and captures responsibilities for Developers, QA, and Stakeholders in role documents.

Quality is enforced through automated and manual checks: unit and integration tests for new logic, end‑to‑end smoke tests for critical flows, CI linting and security scans, and manual QA as required. Releases follow a checklist-driven approach (pre-release verification, release notes, rollback plans, and staged smoke tests) and incidents follow an escalation and blameless retrospective playbook so learnings feed back into the process.

These docs are intended as a single source of truth for OctoAcme’s program processes — use this README to find the right guidance for initiation, planning, execution, risk management, release, and continuous improvement.

## Documentation index

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, principles, and lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate business need, align stakeholders, and authorize work.
- [Project Planning](./octoacme-project-planning.md) — How to break work into increments, estimate scope, and create release plans.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, pull-request workflow, and progress tracking.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and dependencies.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standards for releasing features to production safely and reliably.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — How to capture learnings and convert them into actionable improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities.

## Getting started

- New project? Start with the [Project Initiation Guide](./octoacme-project-initiation.md).
- Planning a release? Review [Project Planning](./octoacme-project-planning.md).
- Executing work? Follow [Execution & Tracking](./octoacme-execution-and-tracking.md) and the branch/PR conventions.
- Managing risks or incidents? See [Risk Management & Communication](./octoacme-risks-and-communication.md).
- Preparing to release? Use the checklist in [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- Capture improvements in [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## Questions or changes

Use the "Add Content to Project Management Process Docs" issue template to propose updates, or contact your Project Manager or Product Manager for guidance.
