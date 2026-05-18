# OctoAcme — Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART objectives, success metrics, stakeholders, and a high-level timeline. Work only advances into planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. Planning then converts the approved initiative into a prioritized backlog with acceptance criteria, T-shirt sized estimates, a Definition of Done, and a release milestone map — ensuring that all dependencies and risks are surfaced before delivery begins.

Four core personas drive execution: the **Project Manager (PM)**, who owns schedules, risks, and cross-team communication; the **Product Manager (PdM)**, who defines outcomes and prioritizes the backlog; **Developers**, who implement and test features; and **QA/Testing**, who validate acceptance criteria. Collaboration is structured around a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests (≤ 400 lines), mandatory CI checks (tests, linting, security scanning), and at least one peer approval before merging. A Risk Register tracks issues by impact, likelihood, owner, and mitigation plan, and is reviewed continuously throughout the project lifecycle.

Communication at OctoAcme is deliberate and layered. The delivery team holds daily 15-minute standups and weekly delivery syncs, while the PM and PdM align weekly and stakeholders receive monthly updates. Escalation follows a clear three-level path — team triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues. Risk and status information flows through a consistent weekly status template covering progress, next steps, risks/blockers, and decisions needed, with a single source of truth maintained in the project repo.

Quality and continuous improvement are first-class concerns. Every release requires passing CI and security scans, merged PRs with all acceptance criteria met, drafted release notes, and a documented rollback plan before a staged rollout through a staging smoke-test gate and into production. After each sprint, release, or incident, the team runs a timeboxed retrospective (45–75 minutes) to capture what went well, what to improve, and 2–3 prioritized action items with clear owners and due dates. Those action items feed back into the project backlog or issue tracker, closing the loop between learning and execution — a practice central to OctoAcme's culture of iterative, data-informed delivery.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, principles, roles, and project lifecycle |
| [Project Initiation](./octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution guidance, team rhythm, PR workflow, quality, and metrics |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identifying, managing, and communicating risks and dependencies |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Standardized release process, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of typical roles and responsibilities used across OctoAcme project docs |
