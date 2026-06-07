# OctoAcme Project Management Docs

This README provides a summary and quick links to all OctoAcme project management process documents. Use it as the starting point for understanding how OctoAcme runs projects at scale.

## Summary of Project Management Processes

OctoAcme operates under a structured yet flexible project management framework designed around five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization follows a well-defined lifecycle that spans from initiation through retrospective, ensuring that new ideas are validated early, stakeholders are aligned before work begins, and learnings are captured after each milestone to drive continuous improvement.

### Key Stages

- **Initiation:** Define problem, success metrics, key stakeholders, and high-level timeline. A Project One-pager captures business need and measurable outcomes.
- **Planning:** Break work into shippable increments, identify dependencies and risks, create prioritized backlog with acceptance criteria, and define Definition of Done.
- **Execution & Tracking:** Manage work via GitHub Projects (Backlog → Ready → In Progress → In Review → QA → Done), disciplined PR workflow, daily standups, and quality checks including unit/integration/smoke tests and security scans.
- **Risk Management & Communication:** Maintain a Risk Register, monitor risks weekly, escalate via clear paths (team → PM → Product Lead → Sponsor), and provide regular stakeholder updates.
- **Release & Deployment:** Standardize pre-release requirements (passing CI, security scans, rollback plans), deploy to staging, verify, and communicate to stakeholders.
- **Retrospective & Continuous Improvement:** Capture learnings post-delivery or milestone, prioritize 2–3 action items, and track improvements against success criteria.

### Core Roles & Communication

Three primary roles anchor OctoAcme's delivery model:

- **Project Managers (PMs):** Coordinate schedules, risks, and communications. Ensure transparency and alignment across stakeholders.
- **Product Managers (PdMs):** Define outcomes, prioritize backlogs, and measure success based on data-driven insights.
- **Developers:** Implement features, write tests, collaborate on design, and help identify technical risks.

Supporting roles include QA/Testing teams and stakeholders. Communication happens through a regular cadence:
- Weekly syncs between PM and PdM
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations as needed

Daily 15-minute standups focus on progress, blockers, and dependencies, while weekly delivery syncs showcase progress and flag risks. This rhythm keeps all parties aligned and enables quick identification of issues.

## Documentation Index

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, key artifacts, and lifecycle.
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies.
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized process for releases to reduce risk and improve observability.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities (Developers, Product Managers, Project Managers).

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level orientation.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md).

**In active delivery?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md).

**Preparing to release?** Check [Release & Deployment](./octoacme-release-and-deployment.md).

**After a milestone?** Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

---

For questions or process improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
