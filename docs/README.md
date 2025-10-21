# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation. This README serves as the central entry point for understanding how OctoAcme runs projects, providing new team members with quick access to our principles, processes, roles, and key workflows.

## Overview

OctoAcme follows a customer-first, iterative approach to project delivery. Our processes are designed to deliver small, testable increments with clear ownership, data-informed decisions, and a culture of psychological safety that encourages feedback and continuous learning.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments frequently
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning without blame

## Project Lifecycle

OctoAcme projects follow a structured lifecycle with five key phases:

1. **Initiation**: Define problem statement, identify stakeholders, and establish high-level timeline
2. **Planning**: Break work into shippable increments, identify dependencies and risks, align timelines
3. **Execution**: Build, test, review, and iterate with continuous tracking and quality assurance
4. **Release & Deployment**: Deploy to production with proper verification and stakeholder communication
5. **Retrospective**: Capture learnings and convert them into actionable improvements

## Core Roles & Personas

### Project Manager (PM)
- Coordinates delivery, schedules, risk management, and communications
- Maintains project plans, timelines, and status reporting
- Facilitates meetings and ensures team alignment
- **Communication**: Weekly status updates, risk registers, stakeholder reports

### Product Manager (PdM)
- Defines outcomes, prioritizes backlog, and measures success
- Owns product vision and customer value delivery
- Makes data-driven prioritization decisions
- **Communication**: Weekly PM alignment, roadmap updates, feature specs

### Developers
- Implement features, collaborate on design and testability
- Write and maintain tests and documentation
- Participate in code reviews and estimation
- **Communication**: Daily standups, PR descriptions, technical design docs

### QA/Testing
- Validate quality and acceptance criteria
- Execute test plans and identify defects
- Ensure features meet definition of done

### Stakeholders
- Provide inputs, approvals, and business context
- Receive regular project updates
- Support decision-making and escalations

## Key Workflows & Practices

### Communication Cadence
- **Daily**: Team standups (15 min) - progress, blockers, dependencies
- **Twice-weekly**: Delivery team coordination (as agreed)
- **Weekly**: PM + PdM sync, delivery team reviews, risk register updates
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communications

### Quality Assurance
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI/CD pipeline
- Manual QA for feature acceptance when needed
- Code reviews with at least one approval before merging

### Risk Management
- Maintain a Risk Register with ID, Description, Impact, Likelihood, Owner, Mitigation, and Status
- Identify risks during planning and ongoing execution
- Review and update risks at weekly syncs
- Escalate through defined paths: Team → PM → Product Lead → Sponsor

### Release & Deployment
- Three release types: Patch (hotfixes), Minor (incremental features), Major (significant changes)
- Pre-release requirements include passing CI, security scans, and prepared smoke tests
- Rollback plans documented for all releases
- Post-deployment verification and stakeholder announcements

## Key Artifacts

- **Project Charter / One-pager**: Problem statement, goals, success metrics, stakeholders
- **Roadmap and Release Plan**: Timeline and milestone mapping
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Definition of Done**: Clear completion criteria for all work items
- **Risk Register**: Tracked risks with mitigation plans
- **Retrospective Notes**: Learnings and action items for continuous improvement

## Process Documentation

Explore our detailed process guides below:

### Core Framework
- [**Project Management Overview**](octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach, principles, and lifecycle
- [**Roles and Personas**](octoacme-roles-and-personas.md) - Detailed role definitions, responsibilities, and communication patterns

### Lifecycle Phases
- [**Project Initiation**](octoacme-project-initiation.md) - Initial validation, stakeholder alignment, and project authorization
- [**Project Planning**](octoacme-project-planning.md) - Creating actionable plans, backlogs, and release timelines
- [**Execution and Tracking**](octoacme-execution-and-tracking.md) - Day-to-day execution, tracking progress, and quality workflows
- [**Release and Deployment**](octoacme-release-and-deployment.md) - Standardized release processes and deployment checklists
- [**Retrospective and Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings and driving improvements

### Cross-cutting Concerns
- [**Risk Management and Communication**](octoacme-risks-and-communication.md) - Risk identification, stakeholder communication, and escalation paths

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach
2. **Understand your role**: Review the [Roles and Personas](octoacme-roles-and-personas.md) guide
3. **Starting a project?** Follow the [Project Initiation](octoacme-project-initiation.md) guide
4. **In execution?** Reference [Execution and Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance
5. **Planning a release?** Check the [Release and Deployment](octoacme-release-and-deployment.md) guide

## Using These Docs

- Keep the Project Charter updated in your project repository
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Reference these guides during project planning, execution, and retrospectives
- Contribute improvements back to these process docs as you learn

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please reach out to your Project Manager or Product Lead.

---

*Last updated: October 2025*
