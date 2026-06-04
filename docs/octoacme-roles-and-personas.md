# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- Collaborate with QA Lead on acceptance criteria and test coverage
- Work with Release Manager during release planning and deployment
- Support Business Analyst in clarifying technical requirements
- Iterate with UX Designer on implementation details for user-facing features

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- Work with Business Analyst to translate business needs into technical requirements
- Collaborate with UX Designer on user experience strategy and priorities
- Partner with QA Lead to define quality and acceptance standards
- Engage Support Lead to incorporate customer feedback into product priorities

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- Coordinate with Release Manager on deployment timelines and milestones
- Work with all delivery roles to track progress and manage dependencies
- Escalate blockers and risks through established paths (team → PM → Product Lead → Sponsor)

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project, coordinates testing efforts, and ensures acceptance criteria are met before release. They work closely with Developers, Product Managers, and Release Managers to validate delivery quality and user experience.

### Responsibilities
- Define and maintain the test plan and QA approach
- Coordinate test activities across development team and testers
- Enforce acceptance criteria and Definition of Done
- Identify and escalate quality blockers
- Plan manual and automated testing strategies
- Collaborate on test coverage and critical path validation

### Goals
- Ensure all deliverables meet acceptance criteria
- Reduce defects reaching production
- Enable fast, confident releases through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement meetings
- Quality gates and test result summaries
- Defect tracking and escalation
- Release readiness reviews

### Interactions with Other Roles
- **Developers**: Review acceptance criteria, collaborate on test coverage, validate fixes
- **Product Manager**: Clarify acceptance criteria and quality requirements
- **Project Manager**: Report quality status and escalate blockers
- **Release Manager**: Confirm QA readiness before deployment
- **UX Designer**: Validate user experience during testing

---

## Release Manager

### Role Summary
The Release Manager plans, coordinates, and executes releases to production. They ensure pre-release requirements are met, manage deployment logistics, and communicate status to stakeholders. They own the rollback strategy and post-release verification.

### Responsibilities
- Create and maintain release plans and timelines
- Coordinate pre-release activities (testing, documentation, backups)
- Execute deployments to staging and production environments
- Manage rollback and incident response procedures
- Conduct post-release verification and smoke testing
- Communicate release status to stakeholders and support teams

### Goals
- Deliver releases on schedule with minimal risk
- Reduce time-to-recovery during incidents
- Maintain customer trust through reliable deployments

### Typical Communication
- Release coordination meetings and kickoffs
- Deployment checklists and status updates
- Incident notifications and resolution updates
- Post-release retrospectives and action items

### Interactions with Other Roles
- **Developers**: Coordinate code freeze dates and deployment readiness
- **QA Lead**: Confirm QA sign-off and critical test results
- **Project Manager**: Align release schedule with project milestones
- **Support Lead**: Brief on new features and known issues for customer communication
- **Product Manager**: Communicate feature readiness and customer impact

---

## Business Analyst

### Role Summary
The Business Analyst bridges business requirements and technical delivery. They document and clarify requirements, work with stakeholders to define acceptance criteria, and help evolve solutions to meet business objectives.

### Responsibilities
- Gather and document business requirements from stakeholders
- Define and refine acceptance criteria with Product Managers and Developers
- Create requirement specifications and user stories
- Clarify ambiguities and scope during planning and execution
- Validate delivered solutions against business requirements
- Support traceability from business needs to technical implementation

### Goals
- Ensure delivered features meet business objectives
- Reduce misalignment between stakeholders and delivery teams
- Minimize rework and scope creep

### Typical Communication
- Stakeholder interviews and requirements workshops
- Detailed requirement documentation and user stories
- Design reviews and acceptance criteria clarification
- Stakeholder sign-off and validation reports

### Interactions with Other Roles
- **Product Manager**: Collaborate on prioritization and requirements translation
- **Developers**: Clarify technical feasibility and refine acceptance criteria
- **Project Manager**: Track requirement changes and scope impact
- **UX Designer**: Align user experience with business process requirements
- **QA Lead**: Define business-relevant test scenarios

---

## UX Designer

### Role Summary
The UX Designer focuses on user journeys, interactions, and overall usability. They ensure acceptance criteria include user experience considerations and work with Developers to iterate on designs that balance usability with technical constraints.

### Responsibilities
- Conduct user research and define user journey maps
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and usability standards
- Collaborate with Developers on implementation feasibility
- Validate designs through user testing and feedback
- Ensure accessibility and inclusive design principles

### Goals
- Deliver intuitive, usable features that delight users
- Reduce user errors and support burden
- Maintain consistent brand and experience standards

### Typical Communication
- Design specifications and wireframes
- Usability testing results and feedback
- Design review discussions and iteration notes
- Accessibility and design pattern documentation

### Interactions with Other Roles
- **Product Manager**: Align design with product vision and priorities
- **Developers**: Partner on implementation details and technical constraints
- **QA Lead**: Define user experience test scenarios
- **Business Analyst**: Align design with business process requirements
- **Support Lead**: Incorporate user feedback and support trends into design improvements

---

## Support Lead

### Role Summary
The Support Lead coordinates post-release support, triages issues from end users, and communicates support trends back to the team. They serve as the voice of the customer, helping ensure product improvements address real user needs.

### Responsibilities
- Coordinate support team during and after release
- Triage and prioritize customer-reported issues
- Communicate support trends and common issues to Product and Engineering teams
- Collaborate with Developers on hotfixes and urgent issues
- Document known issues and workarounds for customers
- Gather customer feedback for future improvements

### Goals
- Minimize customer impact from issues
- Reduce support burden through better product design
- Capture customer insights to inform product decisions

### Typical Communication
- Release announcement and customer communications
- Support ticket summaries and trend reports
- Incident escalation and resolution updates
- Customer feedback summaries and feature requests

### Interactions with Other Roles
- **Release Manager**: Brief on release features and known issues before launch
- **Developers**: Escalate critical issues and collaborate on fixes
- **Product Manager**: Report customer trends and feedback for prioritization
- **QA Lead**: Identify quality issues and regressions in production
- **Project Manager**: Escalate critical customer-impacting issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how roles interact to identify collaboration touchpoints and potential gaps in communication.
- Reference the interaction sections to coordinate work across teams and establish clear handoff points.
