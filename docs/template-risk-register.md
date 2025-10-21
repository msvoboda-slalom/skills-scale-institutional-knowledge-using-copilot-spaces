# Risk Register Template

Use this template to track and manage project risks throughout the project lifecycle.

---

## Project Information

- **Project Name**: _________________________
- **Project Manager**: _________________________
- **Last Updated**: _________________________

---

## Risk Categories

- **Technical**: Architecture, dependencies, technology limitations
- **Resource**: Team availability, skill gaps, budget
- **Schedule**: Timeline constraints, dependencies, scope creep
- **Quality**: Testing limitations, technical debt, performance
- **External**: Third-party dependencies, regulatory, market changes
- **Operational**: Deployment, support, infrastructure

---

## Risk Probability Scale

- **High (H)**: >60% chance of occurring
- **Medium (M)**: 30-60% chance of occurring
- **Low (L)**: <30% chance of occurring

## Risk Impact Scale

- **Critical (C)**: Project failure, major scope/schedule/budget impact
- **High (H)**: Significant impact to scope, schedule, or budget
- **Medium (M)**: Moderate impact, manageable with adjustment
- **Low (L)**: Minor impact, easily absorbed

---

## Risk Register

| ID | Risk Description | Category | Probability | Impact | Owner | Mitigation Strategy | Status | Last Updated |
|----|-----------------|----------|-------------|--------|-------|---------------------|--------|--------------|
| R-001 | Example: Legacy API is undocumented | Technical | H | H | Tech Lead | Allocate 2 weeks for reverse engineering, document as we go | Active | 2024-01-15 |
| R-002 | Example: Key developer unavailable during release | Resource | M | H | PM | Cross-train team members, document release procedures | Mitigated | 2024-01-20 |
| R-003 | | | | | | | | |
| R-004 | | | | | | | | |
| R-005 | | | | | | | | |
| R-006 | | | | | | | | |
| R-007 | | | | | | | | |
| R-008 | | | | | | | | |
| R-009 | | | | | | | | |
| R-010 | | | | | | | | |

---

## Risk Status Definitions

- **Active**: Risk is present and being monitored
- **Mitigated**: Mitigation actions taken, risk reduced
- **Realized**: Risk has occurred, now an issue
- **Closed**: Risk no longer applicable or fully mitigated

---

## High-Priority Risks (Current)

| ID | Risk Description | Owner | Action Items | Target Date |
|----|-----------------|-------|--------------|-------------|
| | | | | |
| | | | | |
| | | | | |

---

## Risk Review Schedule

- **Daily Standup**: Developers, QA Lead flag new technical or quality risks
- **Weekly Delivery Sync**: Project Manager reviews all active risks with team leads
- **Sprint Planning**: Review risks that may impact sprint commitments
- **Monthly Stakeholder Update**: Project Manager presents high-priority risks to stakeholders

---

## Risk Escalation Path

1. **Team Level**: Developers, QA Lead, Tech Lead identify and own technical/quality risks
2. **Project Level**: Project Manager owns schedule, resource, external risks
3. **Product/Sponsor Level**: Product Manager escalates risks requiring scope, budget, or timeline decisions

---

## Realized Risks (Issues)

When a risk is realized, it becomes an issue. Track separately in project board or issue tracker.

| Risk ID | Issue # | Description | Resolution | Closed Date |
|---------|---------|-------------|------------|-------------|
| | | | | |
| | | | | |

---

## Risk Retrospective Learnings

At project close, review risks and capture lessons learned:

### What We Learned

1. **Risk that didn't happen but we over-mitigated**: _______________
2. **Risk we underestimated**: _______________
3. **New risk we didn't anticipate**: _______________
4. **Most effective mitigation strategy**: _______________

### Improvements for Next Project

1. _______________________________________________
2. _______________________________________________
3. _______________________________________________

---

## Common Risk Examples by Role

### Technical Lead / Architect
- Complex system integration with unknown APIs
- Technology choice doesn't meet performance requirements
- Technical debt accumulation impacting velocity
- Security vulnerabilities in dependencies

### QA Lead
- Insufficient test environment availability
- Critical test scenarios not covered until late in project
- Test automation framework limitations
- Performance issues not discovered until production-like load

### Support / Operations Lead
- Inadequate monitoring or alerting in production
- Deployment process not tested in staging
- Lack of runbooks or incident procedures
- Infrastructure capacity insufficient for expected load

### Product Manager
- Changing business requirements mid-project
- Stakeholder misalignment on priorities
- Unclear success metrics or acceptance criteria
- Competitive or market changes affecting value

### Business Analyst
- Requirements gaps discovered during development
- Business rules not validated with all stakeholders
- Assumptions about user behavior prove incorrect
- Regulatory or compliance requirements not identified

### Project Manager
- Key team member availability reduced
- Dependencies on other teams not coordinated
- Scope creep from unclear boundaries
- Timeline unrealistic given true complexity

---

## Document History

| Date | Author | Changes |
|------|--------|---------|
| | | Initial version |
| | | |
