# OctoAcme — Handoff & RACI Template

This document provides a RACI (Responsible, Accountable, Consulted, Informed) template for common project processes and handoffs at OctoAcme. Use this template to clarify who does what during key activities and transitions.

## What is RACI?

- **R (Responsible)**: Does the work to complete the task
- **A (Accountable)**: Has final authority and accountability for the outcome (only one A per activity)
- **C (Consulted)**: Provides input and expertise before decisions are made
- **I (Informed)**: Kept up-to-date on progress and outcomes

## RACI Matrix Template

| Activity/Process | PdM | PM | Dev | QA | Scrum Master | Tech Lead | UX Designer | Release Manager |
|------------------|-----|----|----|----|--------------|-----------| ------------|-----------------|
| Planning → Execution Handoff | | | | | | | | |
| Feature Handoff (Design → Dev) | | | | | | | | |
| Feature Handoff (Dev → QA) | | | | | | | | |
| Release Handoff (QA → Release) | | | | | | | | |
| Incident Triage | | | | | | | | |

## Example: Release to Production

Below is a completed example showing how to use the RACI matrix for the "Release to Production" process:

| Activity/Process | PdM | PM | Dev | QA | Scrum Master | Tech Lead | UX Designer | Release Manager |
|------------------|-----|----|----|----|--------------|-----------| ------------|-----------------|
| **Release to Production** | C | C | R | R | I | C | I | **A**/R |

**Explanation:**
- **Release Manager** is Accountable (final authority) and Responsible (coordinates execution)
- **Developers** are Responsible for deployment execution and verification
- **QA Engineers** are Responsible for final validation and sign-off
- **Product Manager** is Consulted on feature completeness and release content
- **Project Manager** is Consulted on schedule and stakeholder communication
- **Technical Lead** is Consulted on technical risks and rollback procedures
- **Scrum Master** is Informed of release status
- **UX Designer** is Informed of release completion

## Filled Template Example

Here's a more complete example showing multiple processes:

| Activity/Process | PdM | PM | Dev | QA | Scrum Master | Tech Lead | UX Designer | Release Manager |
|------------------|-----|----|----|----|--------------|-----------| ------------|-----------------|
| **Planning → Execution Handoff** | **A**/R | R | C | C | R | C | C | I |
| **Feature Handoff (Design → Dev)** | C | I | R | I | I | C | **A**/R | I |
| **Feature Handoff (Dev → QA)** | I | I | R | **A**/R | I | C | I | I |
| **Release Handoff (QA → Release)** | C | C | R | R | I | C | I | **A**/R |
| **Incident Triage** | I | C | R | R | C | **A**/R | I | R |

## How to Use This Template

### For New Projects
1. Copy the template matrix at the start of a project
2. Customize the activities list to match your project needs
3. Fill in the RACI assignments with your team
4. Review and get agreement from all roles
5. Reference during handoffs to clarify expectations

### For Process Improvement
1. When handoffs feel unclear, create a RACI matrix for that specific process
2. Discuss as a team to identify gaps (missing R or A) or overload (too many Rs)
3. Update your process documentation with the agreed RACI
4. Review in retrospectives and adjust as needed

### Best Practices
- **Every activity should have exactly one A (Accountable)**
- **At least one R (Responsible) per activity**
- **Keep Consulted (C) to a minimum to avoid slowing decisions**
- **Be generous with Informed (I) for transparency**
- **Review and update quarterly or when team structure changes**

## Common Handoff Scenarios

### Sprint Planning → Sprint Execution
**Key Question**: Who ensures the team has everything needed to start work?

**Typical RACI**:
- Scrum Master: A/R (runs planning, ensures team is ready)
- Developers: R (commit to sprint goals)
- Product Manager: C (clarifies priorities and acceptance criteria)
- QA: C (reviews testability of stories)

### Design Complete → Development Starts
**Key Question**: Who confirms the design is ready and development can begin?

**Typical RACI**:
- UX Designer: A/R (delivers design, confirms specs are complete)
- Developers: R (review design for feasibility)
- Technical Lead: C (reviews technical implications)
- Product Manager: C (confirms alignment with requirements)

### Development Complete → QA Begins
**Key Question**: Who confirms the feature is ready for testing?

**Typical RACI**:
- Developer: R (marks feature complete, provides test guidance)
- QA Engineer: A/R (accepts handoff, begins testing)
- Technical Lead: C (confirms code review complete)

### Testing Complete → Release
**Key Question**: Who approves the release and coordinates deployment?

**Typical RACI**:
- Release Manager: A/R (coordinates release, makes go/no-go decision)
- QA Engineer: R (provides test sign-off)
- Product Manager: C (confirms feature completeness)
- Technical Lead: C (reviews technical risks)

---

## Role Shortcodes Reference

- **PdM** = Product Manager
- **PM** = Project Manager
- **Dev** = Developer
- **QA** = QA Engineer
- **Tech Lead** = Technical Lead
- **UX Designer** = UX Designer
- **Scrum Master** = Scrum Master
- **Release Manager** = Release Manager

---

For more information on roles and their typical interactions, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

For release-specific responsibilities, see [OctoAcme Release Checklist](octoacme-release-checklist.md).
