# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm

| Meeting | Owner/Facilitator | Participants | Purpose |
|---------|------------------|--------------|---------|
| Daily standups (15 min) | Project Manager | Developers, QA Lead, Technical Lead | Progress, blockers, dependencies |
| Weekly delivery sync | Project Manager | All team leads + Product Manager | Progress updates, risk review, decisions |
| Sprint planning | Project Manager | All delivery team | Commit to sprint backlog |
| Demo/Review | Product Manager | All roles | Validate acceptance and gather feedback |
| Retrospective | Project Manager | All delivery team | Continuous improvement |

## Workflows

### Project Board Management
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Backlog management**: Product Manager prioritizes with Business Analyst input
- **Ready for development**: Items with clear acceptance criteria, signed off by Product Manager and Business Analyst
- **In Progress**: Developer actively working, Technical Lead available for guidance
- **In Review**: Code review by peers and Technical Lead (for complex changes)
- **QA**: Testing by QA Lead or designated QA team
- **Done**: Meets Definition of Done, approved by QA Lead

### Pull Request Workflow
- Small PRs (<= 400 lines when possible) (*Best practice from Technical Lead*)
- Include issue link and acceptance criteria in PR description (*Required by Developers*)
- Run automated tests and linting in CI before requesting review (*Enforced by CI pipeline*)
- Require at least one approval before merging (*Policy set by Technical Lead*)
- QA Lead validates before marking as Done

### Cross-Role Handoffs
- **BA → Developers**: Requirements and acceptance criteria clearly documented in backlog items
- **UX Designer → Developers**: Design specs and assets ready before development starts
- **Developers → QA Lead**: Feature complete, unit tests passing, ready for test execution
- **QA Lead → Ops Lead**: Testing complete, approved for deployment
- **Ops Lead → Team**: Deployment complete, monitoring active, any issues escalated

## Quality & Testing

| Activity | Owner | Collaborators |
|----------|-------|---------------|
| Unit tests for new logic | Developers | Technical Lead (for guidance) |
| Integration tests where applicable | Developers + QA Lead | Technical Lead |
| End-to-end smoke tests for critical flows | QA Lead | Developers (for test environment setup) |
| Security scanning in CI | Technical Lead | Ops Lead (for production security) |
| Manual QA for feature acceptance | QA Lead | Business Analyst (validates business rules), UX Designer (validates UX) |
| Performance testing (when required) | QA Lead + Ops Lead | Technical Lead, Developers |

**Quality Gates**: No feature moves to Done without QA Lead sign-off and passing all defined tests.

## Reporting & Metrics

| Metric | Owner | Frequency | Audience |
|--------|-------|-----------|----------|
| Velocity and burndown | Project Manager | Weekly | Delivery team, Product Manager |
| Success metrics from Project One-pager | Product Manager | Sprint reviews | Stakeholders, team |
| Quality metrics (test coverage, defect rates) | QA Lead | Weekly | Technical Lead, Project Manager |
| System health (errors, latency, usage) | Support/Ops Lead | Real-time/daily | Developers, Technical Lead |
| Project status and risks | Project Manager | Weekly | Stakeholders, Product Manager |

## Blocker Escalation

| Level | When to Use | Owner | Escalation Path |
|-------|------------|-------|-----------------|
| **Level 1**: Team-level | Daily standup, team can resolve within 1-2 days | Developer or QA Lead | → Technical Lead or Project Manager |
| **Level 2**: Cross-team | Requires another team or decision beyond team authority | Project Manager | → Product Manager + dependent team leads |
| **Level 3**: Sponsor/Executive | Business-impacting, requires budget, scope, or timeline change | Project Manager | → Product Manager → Sponsor |

**Blocker Response Times**:
- Level 1: Addressed within 24 hours
- Level 2: Escalated and response within 48 hours
- Level 3: Escalated immediately, executive decision within 72 hours

## Execution Checklist
- [ ] Branching and PR conventions documented in repo (*Owner: Technical Lead*)
- [ ] CI configured for tests and lint (*Owner: Technical Lead + Ops Lead*)
- [ ] Regular demos scheduled (*Owner: Project Manager*)
- [ ] Risk register updated weekly (*Owner: Project Manager*)
- [ ] Test environments available and stable (*Owner: QA Lead + Ops Lead*)
- [ ] Monitoring and alerting configured (*Owner: Support/Ops Lead*)
- [ ] Definition of Done visible and enforced (*Owner: QA Lead*)

**Handoff to Release Phase**: QA Lead confirms all features meet DoD and are approved for deployment. Ops Lead coordinates release activities.
