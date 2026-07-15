# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. These documents capture our team's approach to running projects, from initiation through retrospectives.

## OctoAcme Project Management Overview

OctoAcme operates projects through a structured five-phase lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The Initiation phase validates business need through a lightweight Project One-pager that defines the problem, goals, success metrics, and stakeholder alignment—serving as the decision gate for moving forward. Once approved, the Planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and a documented Definition of Done. Throughout Execution, the team maintains a daily rhythm of 15-minute standups, weekly delivery syncs, and sprint-based iterations using a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). This workflow emphasizes small pull requests (≤400 lines), automated CI/testing, and at least one approval before merging—ensuring quality gates are embedded early.

OctoAcme defines clear ownership across four core personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and collaborate on design; and **QA/Testing** validates acceptance criteria. Communication is structured around regular cadences—weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates—with ad-hoc escalations following a three-level path (team triage → PM escalation → sponsor-level involvement). A single source of truth (project README or release documentation) keeps all stakeholders aligned on status, risks, and decisions.

Quality is built into every phase through unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release. Risk management is continuous: risks are identified during planning, assessed for impact and likelihood, mitigated through specific actions, and monitored weekly. OctoAcme also institutionalizes learning through mandatory retrospectives after each sprint, release, or milestone, using blameless reviews to capture learnings and convert them into actionable improvements tracked in the project backlog.

## Project Lifecycle Overview

Our projects follow a structured lifecycle:

```
1. Initiation → 2. Planning → 3. Execution & Tracking → 4. Release & Deployment → 5. Retrospective & Continuous Improvement
                                          ↓
                          (Risk Management & Communication apply throughout)
```

## Documentation Index

### [Project Management Overview](./octoacme-project-management-overview.md)
A high-level introduction to OctoAcme's approach, key roles, artifacts, and communication cadence. **Start here** if you're new to the team.

### [Project Initiation Guide](./octoacme-project-initiation.md)
Defines the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Use this when kicking off a new project or feature.

### [Project Planning](./octoacme-project-planning.md)
Guide to turning an approved initiative into an actionable plan and backlog for delivery.

### [Execution & Tracking](./octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution, team rhythm, quality standards, and blocker escalation.

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
How to identify, manage, and communicate risks and dependencies throughout the project lifecycle.

### [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardized approach to releasing features to production with reduced risk and improved observability.

### [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
How to run effective retrospectives and convert learnings into actionable improvements.

### [Roles & Personas](./octoacme-roles-and-personas.md)
Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities.

## Using These Docs

- Add these documents to `.copilot/` in your project repo if you want Copilot Spaces to use them as context
- Keep your project charter updated in your project repository
- Reference these docs in your team kickoffs and onboarding materials
- Use the lifecycle overview above to identify which documents are most relevant for your current project phase

## Quick Reference: Which Document Do I Need?

| Project Phase | Primary Documents | When to Use |
|---------------|-------------------|------------|
| **Starting a new project** | Initiation Guide, Project Management Overview | You have a problem statement and need to validate if the project should move forward |
| **Getting ready to build** | Planning, Roles & Personas | Your project is approved and you need to create a detailed plan and backlog |
| **Building and delivering** | Execution & Tracking, Risk Management & Communication | Your team is actively working on the project and needs guidance on daily workflows |
| **Shipping to users** | Release & Deployment Guide, Risk Management & Communication | Your work is ready for production and you need a safe deployment process |
| **Learning from delivery** | Retrospective & Continuous Improvement | Your sprint, release, or project is complete and you want to capture lessons learned |
| **Throughout** | Risk Management & Communication, Roles & Personas | Apply these continuously across all phases for consistent risk oversight and clear ownership |
