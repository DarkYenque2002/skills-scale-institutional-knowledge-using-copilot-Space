# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This folder contains comprehensive guides for running projects, managing teams, and delivering value consistently across our organization.

## Overview

OctoAcme follows a structured, iterative approach to project management grounded in the following principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has defined roles and accountabilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Process Documentation

Our project management lifecycle is divided into five key phases, each with dedicated guidance:

### 1. [Project Initiation](./octoacme-project-initiation.md)
**When**: Whenever a new project idea or feature proposal is ready to be explored

Validate and authorize work, align stakeholders, and create a lightweight plan. This phase ensures we're solving the right problem for the right reasons.

**Key deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list
- Resource needs and effort estimates

---

### 2. [Project Planning](./octoacme-project-planning.md)
**When**: After stakeholder approval to move into delivery

Turn an approved initiative into an actionable plan and backlog. This phase breaks work into shippable increments and identifies dependencies.

**Key activities:**
- Kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope (T-shirt sizing or story points)
- Define Definition of Done (DoD)
- Create release plan and milestone map

---

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
**When**: During active development and delivery

Manage day-to-day execution and track progress toward project milestones. This phase maintains momentum while ensuring quality and transparency.

**Key practices:**
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
- Small PRs (≤ 400 lines) with automated tests and CI checks
- Track velocity, burndown, and key success metrics

---

### 4. [Release & Deployment](./octoacme-release-and-deployment.md)
**When**: When features are ready to move to production

Standardize how we release features to production to reduce risk and improve observability.

**Release types:**
- **Patch**: Hotfixes addressing critical production issues
- **Minor**: Incremental features and improvements
- **Major**: Significant functionality or breaking changes

**Pre-release requirements:**
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback/mitigation plan documented
- Smoke tests prepared and executed

---

### 5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
**When**: After each sprint, release, or important milestone

Capture learnings and convert them into actionable improvements. This phase ensures we learn from every project and continuously evolve our processes.

**Structure:**
- What went well
- What could be improved
- Action items (owner, due date)
- Follow-up on previous action items

---

## Supporting Resources

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
Learn how to identify, manage, and communicate risks and dependencies throughout the project lifecycle. Includes risk register templates, escalation paths, and stakeholder communication strategies.

### [Roles and Personas](./octoacme-roles-and-personas.md)
Understand the key roles in OctoAcme projects:
- **Developers**: Design, build, test, and deliver software components
- **Product Managers**: Define what should be built and measure outcomes
- **Project Managers**: Coordinate delivery, manage schedules and risks

### [Project Management Overview](./octoacme-project-management-overview.md)
A concise introduction to OctoAcme's approach, roles, key artifacts, and the high-level lifecycle. Start here if you're new to our processes.

---

## Key Artifacts

Every OctoAcme project maintains:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders
- **Roadmap and Release Plan** — Milestones and delivery timeline
- **Sprint/Iteration Backlog** — Prioritized, estimated work items
- **Acceptance Criteria & Definition of Done** — Quality standards
- **Risk Register** — Identified risks, impact, mitigation plans
- **Retrospective Notes** — Learnings and action items

---

## Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** on progress and metrics
- **Ad-hoc escalations** as needed for blockers or risks

---

## Getting Started

1. **New project?** Start with [Project Initiation](./octoacme-project-initiation.md)
2. **Approved and ready to plan?** Move to [Project Planning](./octoacme-project-planning.md)
3. **In active delivery?** Use [Execution & Tracking](./octoacme-execution-and-tracking.md) as your guide
4. **Approaching release?** Review [Release & Deployment](./octoacme-release-and-deployment.md)
5. **Project complete?** Conduct a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

---

## Contributing to Process Documentation

We continuously refine our processes based on team feedback and lessons learned. To suggest improvements:

1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the gap, update, or improvement needed
3. Include rationale and any suggested content
4. Our team will review and incorporate validated improvements

---

## Questions?

These docs are a living resource. If you have questions, spot gaps, or see areas for improvement, please raise an issue or reach out to your Project Manager or Product Lead.

Happy shipping! 🚀
