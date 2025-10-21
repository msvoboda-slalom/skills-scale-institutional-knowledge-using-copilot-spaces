# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

Each project should clearly identify owners for these key roles:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and cross-team communications. *Accountable for project execution and timely delivery.*
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success. *Accountable for product vision and business value.*
- **Business Analyst (BA)**: Gathers requirements, validates business rules, and ensures alignment with business objectives. *Accountable for requirements clarity and traceability.*
- **UX/UI Designer**: Creates user experience designs, conducts user research, and ensures usability. *Accountable for user satisfaction and design quality.*
- **Technical Lead / Architect**: Defines technical architecture, coding standards, and guides technical decisions. *Accountable for technical quality and system design.*
- **Developers**: Implement features, write tests, and collaborate on design. *Accountable for code quality and feature delivery.*
- **Quality Assurance Lead**: Defines test strategy, coordinates testing, and verifies acceptance criteria. *Accountable for quality standards and test coverage.*
- **Support / Operations Lead**: Manages deployments, monitors production, and coordinates incident response. *Accountable for system reliability and operational excellence.*
- **Stakeholders**: Provide business context, inputs, and approvals. *Accountable for business decisions and sponsorship.*

> **Note**: Smaller projects may combine roles (e.g., Product Manager + Business Analyst, or Developer + QA), but accountability for each area must still be clear.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)

1. **Initiation**: Problem statement, stakeholders, high-level timeline.
   - *Led by*: Product Manager
   - *Supported by*: Business Analyst, Project Manager
   - *Handoff*: Approved project charter and stakeholder list → Planning phase

2. **Planning**: Scope, resources, milestones, dependencies.
   - *Led by*: Project Manager
   - *Supported by*: Technical Lead (architecture), QA Lead (test strategy), BA (requirements), Ops Lead (deployment needs)
   - *Handoff*: Release plan and sprint backlog → Execution phase

3. **Execution**: Build, test, review, iterate.
   - *Led by*: Developers (implementation), QA Lead (testing)
   - *Coordinated by*: Project Manager
   - *Supported by*: Technical Lead (design guidance), UX Designer (design validation), Ops Lead (deployment prep)
   - *Handoff*: Tested and approved features → Release phase

4. **Release**: Deploy, verify, announce.
   - *Led by*: Support/Operations Lead
   - *Supported by*: Developers (deployment support), QA Lead (production validation), PM (communications)
   - *Handoff*: Deployed and validated release → Operations & Close phase

5. **Close & Retrospective**: Capture learnings and next steps.
   - *Led by*: Project Manager
   - *Supported by*: All team members
   - *Outputs*: Retrospective notes, improvement action items, success metrics review

## Communication Cadence

- **Daily standups** (15 min): Developers, QA Lead, Technical Lead, PM facilitates
- **Weekly PM + PdM + Technical Lead sync**: Alignment on priorities, risks, and dependencies
- **Bi-weekly sprint planning**: All delivery team members (PM, PdM, BA, Tech Lead, Developers, QA, UX Designer)
- **Sprint reviews/demos**: All roles invited; PdM and UX Designer validate acceptance
- **Monthly stakeholder updates**: PM presents; PdM provides business context
- **Ad-hoc escalations**: As needed through PM or Technical Lead

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
