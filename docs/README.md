# OctoAcme Project Management Docs

## Overview

Welcome to the OctoAcme Project Management Docs! This README provides a summary of the OctoAcme approach to running projects and serves as an entry point to all detailed process documents.

## OctoAcme Project Management Approach

OctoAcme operates a structured, lifecycle-based project management approach designed to deliver value iteratively while maintaining clear ownership and stakeholder alignment. The organization follows five core phases: **Initiation**, where business needs and success metrics are validated; **Planning**, where work is broken into shippable increments with defined acceptance criteria; **Execution**, where teams deliver and track progress daily; **Release**, where features move to production with rigorous quality gates; and **Retrospective**, where learnings drive continuous improvement. This lifecycle is supported by lightweight but essential artifacts—including a Project One-pager, prioritized backlog, risk register, and release notes—that serve as a shared source of truth across the organization.

The organizational structure at OctoAcme centers on three core roles working in coordination. **Product Managers** own the vision, define success metrics, and prioritize work based on customer value and data-driven insights. **Project Managers** orchestrate delivery, manage schedules, risks, and communications to ensure projects stay on track and aligned with stakeholders. **Developers** implement features while maintaining quality through testing, code review, and design collaboration. This clear ownership model is complemented by a strong communication cadence—daily standups for delivery teams, weekly syncs between PMs and Product Managers, and monthly stakeholder updates—ensuring transparency and enabling rapid issue escalation through defined levels (team → PM → Product Lead → Sponsor).

Quality and risk management are embedded throughout OctoAcme's processes. During execution, teams use GitHub Projects boards to track work across Backlog, Ready, In Progress, In Review, QA, and Done stages, with small PRs (<400 lines), mandatory code reviews, and CI-automated testing and security scanning. Before release, all acceptance criteria must be met, smoke tests passed, and a rollback plan prepared. Risk management operates continuously: risks are identified during planning and execution, captured in a risk register with impact/likelihood assessments, monitored weekly, and escalated when necessary. This proactive stance, combined with post-deployment verification and blameless retrospectives after incidents, creates a culture of psychological safety and continuous learning that drives both reliability and iterative improvement.

## Core Principles

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver in small, testable increments.
- **Clear ownership:** Every project has a PM and Product Lead.
- **Data-informed decisions:** Use evidence and metrics to guide iteration.
- **Transparency:** Shared, living docs for process and decisions.

## Project Lifecycle

Our project lifecycle includes five phases:

1. **Initiation**: Confirm project need, stakeholders, and success criteria.
2. **Planning**: Define scope, schedule, risks, and backlog.
3. **Execution & Tracking**: Deliver, measure, review progress.
4. **Release & Deployment**: Standardize releases, automate where possible.
5. **Retrospective & Continuous Improvement**: Capture learnings and feed them back into process.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to Use These Docs

- **New to OctoAcme?** Start here to understand our core approach, then dive into the specific phase docs that are relevant to your current project.
- **Leading a project?** Reference the Project Management Overview and follow the lifecycle guides for each phase.
- **Contributing to the docs?** Submit updates via the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
