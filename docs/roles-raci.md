# OctoAcme RACI Matrix

This document defines role accountability for key project activities using the RACI model:
- **R** = Responsible (does the work)
- **A** = Accountable (ultimately answerable, approves)
- **C** = Consulted (provides input)
- **I** = Informed (kept up to date)

---

## Key Project Activities

### Project Initiation

| Activity | PM | PdM | Developer | QA | Scrum Master | UX Designer | Release Manager | Business Analyst | Stakeholders |
|----------|----|----|-----------|-------|--------------|-------------|-----------------|------------------|--------------|
| Create Project One-pager | R | C | I | I | C | C | I | C | I |
| Define Success Metrics | C | R/A | I | I | I | C | I | C | C |
| Identify Stakeholders | R/A | C | I | I | C | I | I | C | C |
| Initial Risk Assessment | R/A | C | C | C | C | I | I | C | I |
| Requirements Gathering | C | C | I | I | I | C | I | R | C |
| Go/No-Go Decision | I | A | I | I | I | I | I | I | R |

### Project Planning

| Activity | PM | PdM | Developer | QA | Scrum Master | UX Designer | Release Manager | Business Analyst | Stakeholders |
|----------|----|----|-----------|-------|--------------|-------------|-----------------|------------------|--------------|
| Backlog Creation | C | R/A | C | C | R | I | I | R | I |
| Sprint Planning | R | C | R | C | A | I | I | C | I |
| Estimation | C | I | R | C | C | I | I | I | I |
| Define Definition of Done | R | C | R | R | C | C | I | I | I |
| Risk & Dependency Tracking | R/A | C | C | C | C | I | C | I | I |
| Release Timeline | R | C | C | C | C | I | C | I | C |
| User Research & Wireframes | I | C | I | I | I | R/A | I | C | I |
| Workflow Documentation | C | I | I | I | I | C | I | R/A | I |

### Execution & Tracking

| Activity | PM | PdM | Developer | QA | Scrum Master | UX Designer | Release Manager | Business Analyst | Stakeholders |
|----------|----|----|-----------|-------|--------------|-------------|-----------------|------------------|--------------|
| Daily Standups | C | I | R | R | A | R | I | C | I |
| Feature Development | C | I | R/A | C | C | C | I | C | I |
| Code Reviews | I | I | R/A | C | I | I | I | I | I |
| Testing | C | I | C | R/A | I | I | I | I | I |
| Sprint Demo | R | C | R | R | A | C | I | I | C |
| Blocker Resolution | C | C | R | R | R/A | C | I | C | I |
| Progress Reporting | R/A | I | I | I | C | I | I | I | I |
| Design Validation | C | C | C | I | I | R/A | I | C | C |

### Release & Deployment

| Activity | PM | PdM | Developer | QA | Scrum Master | UX Designer | Release Manager | Business Analyst | Stakeholders |
|----------|----|----|-----------|-------|--------------|-------------|-----------------|------------------|--------------|
| Release Planning | C | C | C | C | I | I | R/A | I | I |
| Pre-release Testing | I | I | C | R/A | I | I | C | I | I |
| Deployment Coordination | C | I | R | C | I | I | A | I | I |
| Smoke Tests | I | I | C | R/A | I | I | C | I | I |
| Release Notes | C | C | C | I | I | I | R/A | I | I |
| Stakeholder Communication | C | I | I | I | I | I | R/A | I | I |
| Rollback Decision | C | C | C | C | I | I | A | I | C |
| Post-release Monitoring | C | I | R | R | I | I | C | I | I |

### Retrospective & Continuous Improvement

| Activity | PM | PdM | Developer | QA | Scrum Master | UX Designer | Release Manager | Business Analyst | Stakeholders |
|----------|----|----|-----------|-------|--------------|-------------|-----------------|------------------|--------------|
| Facilitate Retrospective | C | I | R | R | R/A | R | I | C | I |
| Action Item Tracking | R | I | C | C | C | I | I | I | I |
| Process Improvement | C | C | R | R | R/A | C | C | C | I |
| Metrics Review | R/A | C | C | C | C | I | C | I | I |

---

## Notes on RACI Usage
- Each activity should have exactly **one** person who is **Accountable (A)**
- Multiple people can be **Responsible (R)** for completing the work
- Avoid having too many people **Consulted (C)** — focus on those whose input is truly needed
- Keep **Informed (I)** limited to those who need to know, but don't need to provide input

## Related Documents
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [Role Responsibility Template](./role-responsibility-template.md)
- [Project Planning Guide](./octoacme-project-planning.md)
- [Execution & Tracking Guide](./octoacme-execution-and-tracking.md)
