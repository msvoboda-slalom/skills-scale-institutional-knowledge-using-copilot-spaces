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

---

## Business Analysts

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, analyze processes, and ensure solutions align with business objectives and user needs.

### Responsibilities
- Elicit and document business requirements
- Conduct stakeholder interviews and workshops
- Create process flows and business rule documentation
- Validate solutions against business requirements
- Support user acceptance testing coordination

### Goals
- Ensure business value is clearly defined and measurable
- Reduce ambiguity in requirements and acceptance criteria
- Facilitate alignment between business and technical teams

### Typical Communication
- Requirements workshops and review sessions
- Business process documentation and flowcharts
- User story refinement and acceptance criteria validation
- Weekly alignment with Product Managers and Technical Leads

---

## UX/UI Designers

### Role Summary
UX/UI Designers create intuitive, accessible, and visually consistent user experiences. They advocate for user needs through research, design, and iterative testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and visual design systems
- Collaborate with developers on implementation feasibility
- Validate designs through user feedback and analytics

### Goals
- Optimize user satisfaction and task completion rates
- Ensure consistency and accessibility across experiences
- Reduce user friction and support requests

### Typical Communication
- Design reviews and critique sessions
- Prototype sharing and feedback gathering
- Handoff specifications with developers
- Collaboration with Product Managers on feature definition

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects define system architecture, technology strategy, and technical standards. They guide developers on complex design decisions and ensure long-term maintainability.

### Responsibilities
- Design system architecture and technical approaches
- Define coding standards and best practices
- Review and approve significant design decisions
- Identify and mitigate technical debt and risks
- Mentor developers and provide technical guidance
- Evaluate and recommend technologies and tools

### Goals
- Ensure scalable, maintainable, and secure architectures
- Reduce technical complexity and improve system reliability
- Enable team productivity through clear technical direction

### Typical Communication
- Architecture decision records (ADRs)
- Technical design review meetings
- Code reviews for critical or complex changes
- Coordination with Project Managers on technical risks
- Consultation with Product Managers on technical feasibility

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads establish testing strategies, ensure quality standards are met, and coordinate test execution. They advocate for quality throughout the development lifecycle.

### Responsibilities
- Define test strategy and quality standards
- Create test plans and test cases
- Coordinate test execution and defect tracking
- Establish and maintain test automation frameworks
- Verify acceptance criteria and Definition of Done
- Report on quality metrics and test coverage

### Goals
- Prevent defects from reaching production
- Ensure features meet acceptance criteria and quality standards
- Improve testability and test automation coverage

### Typical Communication
- Test plan reviews and test case walkthroughs
- Daily standup participation and blocker escalation
- Defect triage meetings
- Sign-off on release readiness
- Collaboration with Developers on testability
- Alignment with Product Managers on acceptance criteria

---

## Support / Operations Lead

### Role Summary
Support/Operations Leads ensure smooth production operations, incident response, and system reliability. They bridge development and production environments and advocate for operational excellence.

### Responsibilities
- Monitor system health and performance metrics
- Coordinate incident response and resolution
- Define and maintain runbooks and operational procedures
- Manage deployment processes and release coordination
- Identify and escalate operational risks
- Provide feedback on supportability and operability

### Goals
- Maximize system uptime and reliability
- Minimize time to detect and resolve incidents
- Ensure smooth deployments with minimal disruption
- Reduce operational toil through automation

### Typical Communication
- On-call rotations and incident retrospectives
- Deployment coordination and readiness reviews
- Operational metrics and SLA reporting
- Feedback to developers on production issues
- Collaboration with Technical Leads on operational architecture
- Alignment with Project Managers on release timing

---

## Role Interaction Map

The following table shows key interaction points between roles during typical project phases:

| Phase | Primary Owner | Key Collaborators | Handoffs & Touchpoints |
|-------|--------------|-------------------|------------------------|
| **Initiation** | Product Manager | Business Analyst, Project Manager | PdM defines problem → BA gathers requirements → PM creates project plan |
| **Requirements** | Business Analyst | Product Manager, UX/UI Designer, Technical Lead | BA documents requirements → Designer creates concepts → Tech Lead validates feasibility |
| **Planning** | Project Manager | All roles | PM coordinates → Tech Lead estimates architecture → QA Lead defines test approach → Ops Lead reviews deployment needs |
| **Design** | UX/UI Designer | Business Analyst, Developers, Product Manager | Designer creates specs → BA validates against requirements → Developers review feasibility → PdM approves scope |
| **Development** | Developers | Technical Lead, QA Lead | Tech Lead guides design → Developers implement → QA Lead validates quality |
| **Testing** | QA Lead | Developers, Business Analyst, UX/UI Designer | Developers fix defects → BA validates business rules → Designer validates UX → QA Lead signs off |
| **Release** | Support/Ops Lead | Project Manager, Developers, QA Lead | Ops Lead coordinates deployment → PM tracks release → Developers support deployment → QA Lead validates production |
| **Operations** | Support/Ops Lead | Developers, Technical Lead, Product Manager | Ops Lead monitors → Developers respond to incidents → Tech Lead guides fixes → PdM prioritizes improvements |

### Cross-Role Communication Guidelines

- **Daily Standups**: Developers, QA Lead, Technical Lead (Project Manager facilitates)
- **Weekly Planning**: Project Manager, Product Manager, Technical Lead, BA
- **Sprint Reviews**: All roles attend; Product Manager and UX Designer lead acceptance
- **Retrospectives**: All delivery team members
- **Architecture Reviews**: Technical Lead leads; Developers, QA Lead, Ops Lead participate
- **Release Planning**: Project Manager, Ops Lead, QA Lead, Technical Lead
- **Stakeholder Updates**: Project Manager presents; Product Manager provides context

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

