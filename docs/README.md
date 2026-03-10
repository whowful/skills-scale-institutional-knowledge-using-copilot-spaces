# OctoAcme Project Management Docs

This folder is the central knowledge base for OctoAcme's project management processes. Whether you are onboarding to the team or looking for a specific process reference, start here.

## Overview

OctoAcme's project management approach is built on five core principles: **customer-first prioritization**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Every cross-functional project that delivers product features, services, or integrations follows a five-stage lifecycle:

1. **Initiation** — Validate the business need, align stakeholders, and produce a lightweight Project One-pager with success metrics and an initial risk list.
2. **Planning** — Turn the approved initiative into a prioritized backlog with acceptance criteria, a Definition of Done, a release plan, and a risk register.
3. **Execution** — Drive daily progress through standups, sprint tracking on GitHub Projects, and disciplined pull request practices (small PRs ≤ 400 lines, automated CI, and at least one peer review before merge).
4. **Release** — Verify readiness, deploy through a standardized pipeline, and announce the release to stakeholders.
5. **Close & Retrospective** — Capture learnings and convert them into backlog action items that drive continuous improvement.

Quality is embedded throughout the delivery cycle. The team writes unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before each release. Security scanning runs in CI on every PR, and manual QA acceptance validates features against defined criteria. Each release — patch, minor, or major — requires the following before deployment proceeds:

- All acceptance criteria met and PRs merged
- Passing CI pipeline and security scans
- Release notes drafted
- Rollback plan documented

Communication and risk management are handled through a structured cadence and a living risk register. The Project Manager and Product Manager sync weekly; the delivery team holds twice-weekly standups; and stakeholders receive monthly updates using a standardized status template. Risks are identified, assessed (impact × likelihood), mitigated, and reviewed every week. Escalation follows a clear path: team-level triage → PM → Product Lead → Sponsor. Security incidents follow a dedicated runbook and trigger immediate on-call notification. After every sprint, release, or incident, the team holds a retrospective to capture learnings and convert them into backlog action items that drive continuous improvement.

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, project lifecycle, and communication cadence |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, One-pager template, and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, sprint planning, Definition of Done, dependency management, and planning checklist |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Team rhythm, PR workflow, quality and testing standards, reporting metrics, and blocker escalation |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication, weekly status template, and escalation paths |
| [Release and Deployment Guide](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running guide, action item tracking, and continuous improvement culture |

---

## How to Use This Documentation

### Onboarding

If you are new to the team, read the documents in this order:

1. **[Project Management Overview](octoacme-project-management-overview.md)** — Understand our principles, roles, and project lifecycle at a glance.
2. **[Roles and Personas](octoacme-roles-and-personas.md)** — Find your role and understand the responsibilities and communication expectations that come with it.
3. **[Execution and Tracking](octoacme-execution-and-tracking.md)** — Learn how the team runs day-to-day: standups, sprint boards, PR conventions, and quality standards.
4. **[Risks and Communication](octoacme-risks-and-communication.md)** — Understand how risks are tracked and how to communicate status and escalate issues.

### Starting a New Project

Follow the lifecycle in order:

1. [Project Initiation Guide](octoacme-project-initiation.md) — Complete the One-pager and get stakeholder sign-off.
2. [Project Planning](octoacme-project-planning.md) — Run kickoff, build the backlog, define Done, and create the release plan.
3. [Execution and Tracking](octoacme-execution-and-tracking.md) — Run sprints, track progress, manage quality, and escalate blockers.
4. [Risks and Communication](octoacme-risks-and-communication.md) — Maintain the risk register and send regular stakeholder updates.
5. [Release and Deployment Guide](octoacme-release-and-deployment.md) — Verify readiness, deploy, and announce the release.
6. [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and create actionable improvements.

### Process Improvements

If you want to suggest changes to these processes, open an issue in this repository using the **Add/Update Content to Process Docs** issue template and link to the document you want to update.