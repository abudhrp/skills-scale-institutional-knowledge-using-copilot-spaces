# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation hub. This folder contains the canonical guides and processes the team uses to plan, execute, and learn from cross-functional work. OctoAcme centers on customer-first delivery, iterative progress, clear ownership, data-informed decisions, and psychological safety so teams can move quickly while managing risk and learning from outcomes.

## Overview
OctoAcme follows a lifecycle-based approach that begins with a lightweight initiation (a Project One-pager) to validate the problem and define success metrics, moves into planning to produce a prioritized backlog and release plan, executes work with disciplined CI and PR practices, and finishes with release verification and retrospectives that feed continuous improvement. Roles are explicit — Product Managers define outcomes, Project Managers coordinate delivery and communications, Developers deliver and test code, and QA validates acceptance criteria.

## Project lifecycle at a glance
1. **Initiation** — Define business need, identify stakeholders, and produce the Project One-pager. Move to planning when success metrics and team availability are confirmed.
2. **Planning** — Break approved initiatives into shippable backlog items with acceptance criteria, estimate scope, identify dependencies, and capture risks in the Risk Register.
3. **Execution & Tracking** — Use a project board (Backlog → Ready → In Progress → In Review → QA → Done), keep PRs small and link them to issues/acceptance criteria, run CI (tests, linting, security), and use daily standups and weekly delivery syncs to surface blockers and risks.
4. **Release & Deployment** — Follow pre-release checklists (passing CI and security scans, release notes, rollback plan), stage verification, deploy via automated pipeline when possible, and run post-deploy checks.
5. **Retrospective** — Capture what went well, what could improve, and create action items that are tracked back into the backlog.

## Key workflows & quality practices
- **Pull Request workflow:** small, focused PRs that reference issues and acceptance criteria, run automated tests and linters in CI, and require at least one approval before merging.
- **Testing & QA:** unit and integration tests for new logic, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when appropriate.
- **Risk & communication:** maintain a Risk Register (ID, impact, likelihood, owner, mitigation), use weekly status templates for stakeholder updates, and follow clear escalation paths (Team → PM → Product Lead → Sponsor).
- **Continuous improvement:** run retrospectives after sprints, releases, and incidents; prioritize 2–3 action items and track them in the backlog.

## Documentation index

#### Getting started
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, and lifecycle
- [OctoAcme Personas](octoacme-roles-and-personas.md) — Role descriptions and responsibilities (PM, PdM, Developers, QA)

#### Project phases
- [Project Initiation Guide](octoacme-project-initiation.md) — One-pager, stakeholder alignment, initiation checklist
- [Project Planning](octoacme-project-planning.md) — Backlog templates, estimation, release planning
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythms, board workflows, PR standards
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Deployment checklist, rollback and incident playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and action tracking

#### Cross-cutting concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder comms, escalation paths

## Quick reference
- Branching & PRs: keep PRs small, include acceptance criteria, CI must pass before review.
- Meetings & cadence: daily standups, weekly delivery syncs, demo at the end of each sprint/milestone, monthly stakeholder updates.
- Release types: Patch (hotfix), Minor (features/ improvements), Major (breaking/large changes). Follow pre-release requirements and the deployment checklist.

## Acceptance criteria
- Content aligns with existing process docs
- Improves clarity and discoverability for new teammates
- README is the central navigation point for all docs in docs/

(Closes #2)
