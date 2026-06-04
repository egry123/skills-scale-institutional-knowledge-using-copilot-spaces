# OctoAcme Project Management Docs

## Overview

Welcome to the OctoAcme Project Management Docs! This README provides a brief summary of the OctoAcme approach to running projects and serves as an entry point to all detailed process documents.

## OctoAcme Project Management Principles

OctoAcme follows a structured, lifecycle-based approach to project management built around five core principles:

- **Customer-first:** Prioritize customer value and usability in all decisions.
- **Iterative delivery:** Deliver work in small, testable increments to enable faster feedback and course correction.
- **Clear ownership:** Every project has a named Project Manager and Product Lead responsible for delivery and outcomes.
- **Data-informed decisions:** Use evidence, metrics, and user research to guide prioritization and iteration.
- **Transparency & Psychological Safety:** Maintain shared, living documentation and encourage team feedback and learning.

## Project Lifecycle

OctoAcme projects move through five integrated phases:

1. **Initiation**: Confirm project need, identify stakeholders, establish success metrics, and gain sponsor alignment through a lightweight Project One-pager.

2. **Planning**: Break work into shippable increments, create a prioritized backlog with acceptance criteria, estimate scope, define quality standards, and identify dependencies and risks.

3. **Execution & Tracking**: Deliver features iteratively using a predictable team rhythm (daily standups, weekly syncs, sprint-based iterations). Embed quality through small PRs, automated testing, and continuous integration.

4. **Release & Deployment**: Standardize releases with pre-release checklists, smoke testing, rollback plans, and post-deploy verification to reduce risk and improve observability.

5. **Retrospective & Continuous Improvement**: Capture learnings after each sprint, release, or milestone. Convert insights into actionable improvements with clear ownership and timelines.

## Core Roles & Responsibilities

- **Project Managers (PM)**: Coordinate delivery, manage schedules, risks, and cross-team communications. Ensure consistent planning and status reporting.
- **Product Managers (PdM)**: Define outcomes, prioritize the backlog, and measure success. Own the product vision and customer value.
- **Developers**: Implement features, write tests, collaborate on design and testability. Help identify technical risks and estimate work.
- **QA/Testing**: Validate quality and acceptance criteria. Partner with the team on test strategy and coverage.
- **Stakeholders**: Provide inputs, approvals, and strategic guidance. Participate in key meetings and decision gates.

## Communication & Quality Practices

**Team Rhythm:**
- Daily standups (15 min) — progress, blockers, dependencies
- Weekly PM–PdM alignment — strategy and risk review
- Twice-weekly delivery syncs — progress and dependency checks
- Monthly stakeholder updates — roadmap and milestone status
- Sprint/milestone retrospectives — capture learnings and action items

**Quality Assurance:**
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI/CD pipelines
- Manual QA for feature acceptance when needed
- Small PRs (≤400 lines when possible) with at least one approval before merge

**Risk & Escalation:**
- Maintain a Risk Register tracking impact, likelihood, mitigation, and status
- Escalation path: Team-level triage → PM → Product Lead → Sponsor
- Weekly risk reviews in PM sync and standups

---

## Process Documents

Explore detailed guidance for each phase:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme roles, principles, artifacts, and lifecycle.
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **[Project Planning](./octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, and define quality standards.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, workflows, and blocker escalation.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, track, and communicate risks and dependencies.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized approach to releases, rollbacks, and incident response.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and drive iterative improvements.
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles and their responsibilities.

---

## Getting Started

**For new team members:**
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for a 5-minute orientation.
2. Review your role in [Roles and Personas](./octoacme-roles-and-personas.md).
3. Bookmark this README and the phase-specific docs for reference during your projects.

**For project leads:**
1. Use [Project Initiation Guide](./octoacme-project-initiation.md) to kick off a new project.
2. Follow the checklists in each phase doc to stay on track.
3. Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md) for stakeholder updates and escalations.

**For continuous improvement:**
- Submit process updates using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- Share learnings from retrospectives and feed validated improvements back into these living docs.