# OctoAcme Project Management Documentation

## Purpose

This documentation provides OctoAcme's project management framework for delivering cross-functional projects that create customer value. Whether you're a new team member or an experienced contributor, these guides help you understand our iterative, customer-first approach to planning, executing, and shipping product features, services, and integrations.

**Who this is for:** Project Managers, Product Managers, Developers, QA Engineers, and stakeholders involved in delivering OctoAcme projects.

## Project Lifecycle Overview

OctoAcme follows a structured five-phase lifecycle that emphasizes iterative delivery and continuous improvement:

1. **Initiation** — Validate the business need, define success metrics, identify stakeholders, and create a project one-pager to confirm go/no-go decisions.
2. **Planning** — Break work into shippable increments, estimate scope, identify dependencies and risks, and establish a release plan with clear acceptance criteria.
3. **Execution & Tracking** — Build and test features through regular sprints, conduct daily standups and weekly syncs, manage risks, and track progress on project boards.
4. **Release & Deployment** — Deploy to production following pre-release checklists, run smoke tests, announce releases, and maintain rollback plans.
5. **Retrospective** — Capture learnings, celebrate wins, identify improvements, and convert action items into backlog tasks for continuous improvement.

## Core Roles & Responsibilities

- **Project Manager (PM):** Coordinates delivery timelines, manages schedules and risks, facilitates meetings, and maintains project documentation and stakeholder communication.
- **Product Manager (PdM):** Defines product vision and outcomes, prioritizes the backlog, collaborates on trade-offs, and measures success through customer research and metrics.
- **Developers:** Implement features to meet acceptance criteria, write tests and documentation, participate in code reviews, estimate work, and identify technical risks.
- **QA/Testing:** Validate quality standards, verify acceptance criteria, conduct integration and end-to-end testing, and ensure feature completeness before release.

## Key Ceremonies & Team Rhythm

OctoAcme maintains a consistent cadence to ensure alignment and transparency:

- **Daily Standups** (15 min) — Team shares progress, blockers, and dependencies
- **Weekly PM + PdM Sync** — Align on priorities, review risks, and address escalations
- **Weekly Delivery Sync** — Demonstrate progress, update timelines, and flag risks to stakeholders
- **Sprint/Milestone Demos** — Showcase completed features and gather feedback
- **Monthly Stakeholder Updates** — Communicate roadmap status and key decisions
- **Retrospectives** — Held after each sprint, release, or milestone to capture learnings and action items

## Detailed Documentation

Each phase of the project lifecycle has dedicated guides in the `docs/` directory:

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — High-level principles, key artifacts, and communication cadence
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Detailed role definitions for Developers, Product Managers, and Project Managers
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Project one-pager template, stakeholder alignment, and decision gates
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — Backlog creation, sprint planning, estimation, and dependency management
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Team workflows, PR conventions, quality practices, and blocker escalation
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Release types, deployment checklists, rollback procedures, and release notes
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Risk register management, stakeholder updates, and escalation paths
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, action item tracking, and improvement culture

**Using process docs with Copilot Spaces:** Consider adding process-specific documentation to `.copilot/` in your project repository to provide AI-powered context and guidance during development.

## Execution Checklist & Next Steps

When starting a new project, ensure these foundational elements are in place:

### Initiation
- [ ] Complete project one-pager with problem statement, goals, and success metrics
- [ ] Identify and align stakeholders; confirm sponsor approval
- [ ] Create initial risk register and resource plan
- [ ] Set up project repository and board

### Planning
- [ ] Conduct project kickoff meeting
- [ ] Build prioritized backlog with acceptance criteria
- [ ] Define Definition of Done (DoD)
- [ ] Create release timeline and milestone map
- [ ] Draft initial test and QA approach

### Execution
- [ ] Document branching and PR conventions (small PRs, issue links, CI checks)
- [ ] Configure CI for automated tests, linting, and security scans
- [ ] Schedule regular demos and retrospectives
- [ ] Maintain and review risk register weekly
- [ ] Track velocity and monitor success metrics

### Release
- [ ] Verify all acceptance criteria met and PRs merged
- [ ] Draft release notes and rollback plan
- [ ] Deploy to staging and run smoke tests
- [ ] Execute production deployment and post-deploy verification
- [ ] Announce release to stakeholders and support teams

### Retrospective
- [ ] Facilitate retrospective (what went well, what to improve)
- [ ] Prioritize 2-3 action items with owners and due dates
- [ ] Add action items to backlog and track progress

---

**Questions?** Refer to the detailed guides above or reach out to your Project Manager or Product Manager for support.
