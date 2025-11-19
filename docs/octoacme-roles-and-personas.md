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

## QA Engineers

### Role Summary
QA Engineers ensure quality throughout the development lifecycle by designing test strategies, identifying defects, and validating that features meet acceptance criteria before release.

### Responsibilities
- Create and execute test plans for features and releases
- Identify, document, and verify bug fixes
- Perform manual and automated testing as appropriate
- Participate in acceptance criteria definition and refinement
- Validate deployments in staging and production environments

### Goals
- Prevent defects from reaching production
- Maintain high confidence in release quality
- Reduce mean time to detect and resolve issues

### Typical Communication
- Bug reports and test case documentation
- Test status updates in sprint reviews
- Collaboration with developers on reproduction steps and fixes

### Typical Interactions
- **With Developers**: Collaborate on reproduction steps, verify fixes, review test coverage
- **With Product Managers**: Validate acceptance criteria, confirm feature behavior
- **With Project Managers**: Report testing progress and quality risks
- **With Release Manager**: Confirm release readiness and sign-off

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team can work efficiently and continuously improve.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Coach team members on agile principles and practices
- Shield the team from external distractions during sprints
- Track and improve team velocity and process metrics

### Goals
- Maximize team productivity and flow
- Foster a culture of continuous improvement
- Ensure consistent execution of agile practices

### Typical Communication
- Facilitation of team ceremonies
- Blocker escalation and resolution tracking
- Retrospective action items and follow-up

### Typical Interactions
- **With Developers**: Remove technical blockers, facilitate collaboration
- **With Product Managers**: Coordinate backlog refinement, protect sprint scope
- **With Project Managers**: Align on timeline and dependencies, escalate risks
- **With QA Engineers**: Ensure quality processes fit within sprint cadence

---

## Technical Lead

### Role Summary
Technical Leads provide technical direction, architectural guidance, and mentorship. They bridge strategic technical decisions with hands-on development and ensure engineering standards are maintained.

### Responsibilities
- Define technical architecture and design patterns
- Review and approve technical designs and complex code changes
- Mentor developers and conduct knowledge sharing sessions
- Identify and address technical debt and scalability concerns
- Collaborate with Product Managers on technical feasibility

### Goals
- Maintain high engineering standards and system quality
- Build scalable, maintainable technical solutions
- Develop team technical capabilities

### Typical Communication
- Technical design documents and architecture diagrams
- Code review comments and technical guidance
- Technology evaluation and recommendation memos

### Typical Interactions
- **With Developers**: Provide technical mentorship, review complex changes
- **With Product Managers**: Assess technical feasibility, propose alternatives
- **With Project Managers**: Estimate technical complexity, flag technical risks
- **With QA Engineers**: Define testing strategies for complex features

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and ensure the product delivers a great user experience. They balance user needs with business goals and technical constraints.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Define interaction patterns and design systems
- Collaborate with Product Managers on feature requirements
- Work with Developers to ensure design implementation fidelity

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs through user research and testing
- Maintain design consistency across the product

### Typical Communication
- Design mockups and interactive prototypes
- User research findings and usability test results
- Design review presentations and feedback sessions

### Typical Interactions
- **With Product Managers**: Translate requirements into user flows and designs
- **With Developers**: Provide design specs, review implementation, discuss constraints
- **With QA Engineers**: Define acceptance criteria for UI/UX, validate final implementation
- **With Stakeholders**: Present designs, gather feedback, iterate based on input

---

## Release Manager

### Role Summary
Release Managers coordinate the release process, ensuring all release requirements are met, risks are mitigated, and deployments are executed smoothly. They are the central point of coordination for release activities.

### Responsibilities
- Plan and schedule release windows
- Coordinate release activities across teams
- Verify release readiness (testing, approvals, documentation)
- Execute or oversee deployment procedures
- Manage rollback procedures if issues occur
- Communicate release status to stakeholders

### Goals
- Deliver reliable, low-risk releases to production
- Minimize deployment-related incidents and downtime
- Maintain clear release visibility and communication

### Typical Communication
- Release schedule and deployment notifications
- Release readiness checklists and status reports
- Post-deployment summaries and incident reports

### Typical Interactions
- **With Developers**: Coordinate code freeze, verify deployments
- **With QA Engineers**: Confirm test completion and sign-off
- **With Product Managers**: Validate feature completeness, coordinate release communications
- **With Project Managers**: Align release schedule with project milestones
- **With Technical Lead**: Review deployment risks and rollback procedures

---

## Role Interaction Matrix

This matrix shows primary responsibilities and common handoffs for key activities. **R** = Responsible (does the work), **A** = Accountable (final authority), **C** = Consulted (provides input), **I** = Informed (kept updated).

| Activity | PdM | PM | Dev | QA | Scrum Master | Tech Lead | UX Designer | Release Manager |
|----------|-----|----|----|----|--------------|-----------| ------------|-----------------|
| **Backlog Grooming** | A/R | C | C | C | R | C | C | I |
| **Sprint Planning** | C | C | R | R | A/R | C | C | I |
| **Design Review** | C | I | C | I | I | C | A/R | I |
| **Code Review** | I | I | R | I | I | A/R | I | I |
| **Release Approval** | C | C | C | R | I | C | I | A/R |
| **Incident Response** | I | C | R | R | C | A/R | I | R |

---

## Using These Persona Definitions

### In Exercises and Scenarios
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

### In Onboarding
- Share this document with new team members to clarify roles and expectations
- Reference specific persona sections when explaining team structure and workflows
- Use the Role Interaction Matrix to illustrate how different roles collaborate

### In Copilot Spaces
- When creating a Copilot Space, include relevant persona definitions in the knowledge base
- Use persona names and responsibilities in prompts to get role-specific guidance (e.g., "As a Technical Lead, review this architecture...")
- Reference the interaction matrix when asking about cross-functional collaboration patterns

