# Definition of Done (DoD) Template

A clear Definition of Done ensures consistent quality and reduces ambiguity about when work is truly complete.

---

## Project Information

- **Project Name**: _________________________
- **QA Lead**: _________________________
- **Technical Lead**: _________________________
- **Last Updated**: _________________________

---

## Purpose

The Definition of Done is a shared understanding of what "complete" means for work items. No item should move to "Done" status without meeting these criteria.

---

## General Definition of Done

Use this checklist for all backlog items (user stories, features, tasks) unless specific exceptions are noted.

### Code Quality

- [ ] Code follows project coding standards and style guide
- [ ] Code reviewed and approved by at least one peer
- [ ] Complex or critical changes reviewed by Technical Lead
- [ ] No commented-out code or debug statements
- [ ] No new compiler warnings or static analysis errors
- [ ] Technical debt is documented (if any shortcuts taken)

### Testing

- [ ] Unit tests written for new logic (minimum coverage: ___%)
- [ ] All unit tests passing locally and in CI
- [ ] Integration tests updated or added (where applicable)
- [ ] Manual testing performed against acceptance criteria
- [ ] Edge cases and error scenarios tested
- [ ] Regression testing completed (no existing features broken)
- [ ] Approved by QA Lead

### Documentation

- [ ] Code comments added for complex logic
- [ ] API documentation updated (if applicable)
- [ ] README or user guide updated (if user-facing changes)
- [ ] Architecture Decision Records (ADRs) created for significant decisions
- [ ] Release notes entry drafted (if needed)

### Functional Requirements

- [ ] All acceptance criteria met and validated
- [ ] Business rules verified with Business Analyst
- [ ] UX/UI design specifications implemented correctly (if applicable)
- [ ] Validated by Product Manager or Business Analyst

### Non-Functional Requirements

- [ ] Performance meets requirements (if applicable)
- [ ] Security best practices followed
- [ ] Accessibility guidelines met (WCAG 2.1 AA or project standard)
- [ ] Responsive design works on required screen sizes (if UI change)

### Deployment & Operations

- [ ] Feature flags or toggles configured (if applicable)
- [ ] Deployment instructions documented or updated
- [ ] Monitoring and logging added for new functionality
- [ ] Alerts configured for critical paths (if applicable)
- [ ] Reviewed by Support/Ops Lead (for significant changes)

### Process & Tracking

- [ ] Issue/ticket updated with final status
- [ ] Linked issues or dependencies resolved or documented
- [ ] Branch merged and closed
- [ ] Demo-ready for sprint review

---

## Role-Specific Sign-Offs

### When QA Sign-Off is Required

All features require QA Lead approval before marking as Done. QA Lead confirms:
- Acceptance criteria validated
- Test execution completed
- No critical or high-priority defects

### When Technical Lead Sign-Off is Required

The following require Technical Lead approval:
- Architecture changes or new patterns
- Database schema changes
- New external dependencies or libraries
- Security-sensitive code
- Performance-critical implementations

### When UX/UI Designer Sign-Off is Required

User-facing changes require UX/UI Designer approval:
- New user interfaces or screens
- Changes to existing user flows
- Visual design updates
- Accessibility improvements

### When Business Analyst Sign-Off is Required

Complex business logic requires Business Analyst validation:
- Business rule implementations
- Data transformations or calculations
- Workflow or process changes
- Compliance or regulatory requirements

### When Support/Ops Lead Sign-Off is Required

Operational changes require Ops Lead approval:
- Deployment process changes
- Infrastructure or configuration updates
- Monitoring or alerting changes
- Performance or scaling modifications

---

## Item-Type Specific DoD

### User Stories / Features

All General DoD criteria above, plus:
- [ ] Demonstrated in sprint review
- [ ] User acceptance testing completed (if required)
- [ ] Training materials updated (if needed)

### Bugs / Defects

- [ ] Root cause identified and documented
- [ ] Fix verified against original issue
- [ ] Regression tests added to prevent recurrence
- [ ] Related issues checked (no similar bugs remaining)

### Technical Debt / Refactoring

- [ ] Original problem documented (why refactoring needed)
- [ ] Refactoring does not change external behavior
- [ ] Test coverage maintained or improved
- [ ] Performance impact measured (if applicable)

### Spikes / Research

- [ ] Findings documented with recommendations
- [ ] Demo or presentation to team completed
- [ ] Follow-up stories created (if needed)
- [ ] Decision recorded in ADR (if architectural)

### Documentation Tasks

- [ ] Reviewed for accuracy by subject matter expert
- [ ] Grammar and spelling checked
- [ ] Examples tested and validated
- [ ] Published to appropriate location

---

## DoD Exceptions

Sometimes the full DoD cannot be met. Document exceptions here with justification:

| Item ID | Exception | Reason | Approved By | Follow-up Task |
|---------|-----------|--------|-------------|----------------|
| #123 | Skipped integration tests | Test environment unavailable | Tech Lead | #124 - Add tests when env ready |
| | | | | |
| | | | | |

**Note**: Exceptions should be rare and always have follow-up tasks to complete the DoD.

---

## Quality Metrics

Track these metrics to understand DoD compliance:

| Metric | Target | Current | Trend |
|--------|--------|---------|-------|
| % items requiring DoD exceptions | <5% | | |
| Test coverage | >80% | | |
| Code review time (avg) | <2 days | | |
| Defects found post-release | <2 per sprint | | |
| Items returned from QA | <10% | | |

---

## DoD Review Schedule

- **Sprint Retrospective**: Review DoD effectiveness, suggest improvements
- **Quarterly**: Update DoD based on team learnings and project evolution
- **As Needed**: Adjust for new technology, tools, or requirements

---

## Team Agreement

This Definition of Done was reviewed and agreed upon by the team:

| Role | Name | Date |
|------|------|------|
| Technical Lead | | |
| QA Lead | | |
| Project Manager | | |
| Developers | | |
| Product Manager | | |

---

## Revision History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | | Initial version | |
| | | | |
| | | | |

---

## Tips for Success

1. **Start Simple**: Don't make DoD too complex initially. Add criteria as team matures.
2. **Make it Visible**: Post DoD where team can see it daily (project board, wiki, repo README).
3. **Review Regularly**: DoD should evolve with the project and team.
4. **Automate Checks**: Use CI/CD to automatically validate DoD criteria (tests, linting, coverage).
5. **Enforce Consistently**: Don't let items slip through without meeting DoD.
6. **Be Realistic**: DoD should be challenging but achievable within sprint timebox.

---

## Related Documents

- [Project One-Pager](./template-project-one-pager.md)
- [Role Assignment and Handoff Checklist](./checklist-role-assignment-and-handoffs.md)
- [Risk Register](./template-risk-register.md)
- [OctoAcme Project Planning Guide](./octoacme-project-planning.md)
