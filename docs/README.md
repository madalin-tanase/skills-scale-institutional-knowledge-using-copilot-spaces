# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. It serves as a structured knowledge base for team members, covering how OctoAcme initiates, plans, executes, and closes projects — including roles, communication, risk management, release practices, and continuous improvement.

---

## Overview of OctoAcme Project Management

OctoAcme uses a lightweight but structured project management approach that guides work from initiation through planning, execution, release, and retrospective improvement. Projects begin with a clear business need, stakeholder alignment, success metrics, and a lightweight one-pager that defines goals, risks, rough timelines, and team roles. Once approved, work moves into planning, where teams break initiatives into shippable increments, define acceptance criteria, estimate scope, identify dependencies, and document a Definition of Done. This creates a practical bridge between strategy and delivery while keeping planning focused on measurable outcomes and clear ownership.

The process depends on well-defined cross-functional roles. Project Managers coordinate delivery, timelines, risks, documentation, and stakeholder communication; Product Managers define outcomes, prioritize backlog items, and measure success; Developers implement solutions, maintain quality, and help identify technical risks; QA contributors validate that features meet acceptance criteria; and Stakeholders provide input and approvals. OctoAcme emphasizes clear accountability through named owners, shared artifacts such as project charters, backlogs, risk registers, and retrospective notes, and persona-based guidance that helps teams tailor communication and decisions to each role's responsibilities.

Communication is built into the operating model through recurring cadences and escalation paths. Core rhythms include standups, weekly PM/Product alignment, delivery syncs, sprint or milestone demos, monthly stakeholder updates, and ad hoc escalation when risks or blockers arise. Teams are expected to use a single source of truth — such as a project README, release document, or project board — and to maintain regular status updates that highlight progress, next steps, blockers, and decisions needed. Risks and dependencies are actively tracked in a risk register, reviewed in weekly syncs, and escalated from the team level to PM, Product Lead, and sponsor when business impact increases.

Quality assurance is treated as a shared responsibility throughout execution and release. OctoAcme recommends small pull requests, issue-linked PR descriptions with acceptance criteria, automated CI checks for tests and linting, and at least one approval before merge. Teams are expected to use unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed for feature acceptance. Before release, teams confirm that acceptance criteria are met, CI and security scans pass, release notes and rollback plans are prepared, and post-deployment verification is completed. After each sprint, release, milestone, or incident, retrospectives capture lessons learned and convert them into a small number of tracked improvement actions.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythms, PR workflows, quality practices, and escalation paths |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register format, stakeholder communication templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, track action items, and build a continuous improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers |

---

## Using These Docs in Copilot Spaces

These documents are structured as a knowledge source for [GitHub Copilot Spaces](https://docs.github.com/en/copilot/). When added to a Copilot Space, they enable role-specific, context-aware assistance for project management tasks. To get the most out of them:

- Add relevant docs to your Space so Copilot can reference OctoAcme process context when answering questions or generating artifacts.
- Use the [Roles & Personas](octoacme-roles-and-personas.md) doc to shape persona prompts that tailor Copilot's responses to a specific role (e.g., Developer, Product Manager, or Project Manager).
- Reference individual docs when asking Copilot to draft plans, status updates, risk registers, retrospective notes, or release checklists aligned with OctoAcme standards.
