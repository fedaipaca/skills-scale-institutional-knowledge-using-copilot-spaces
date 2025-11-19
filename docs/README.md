# OctoAcme Project Management Docs

## Project Management Process Summary

OctoAcme runs projects through a lightweight, outcome-focused lifecycle: Initiation → Planning → Execution &amp; Tracking → Release &amp; Deployment → Retrospective &amp; Continuous Improvement. During Initiation we validate the business need, define success metrics, and align stakeholders using a Project One-pager and a simple decision gate. In Planning the team breaks work into shippable increments with prioritized backlog items, clear acceptance criteria, estimates, and a Definition of Done. Execution emphasizes small, reviewable changes, CI-driven quality checks, and a regular team rhythm (standups, weekly delivery syncs, demos) to surface progress and blockers. Releases follow a staged approach with pre-release smoke tests, runbooks, and rollback plans. After delivery, teams run blameless retrospectives and convert improvements into tracked action items.

Roles and responsibilities are explicit: Project Managers coordinate schedules, risks, and stakeholder communication; Product Managers define outcomes and prioritize the backlog; Developers implement and test; QA validates acceptance criteria and maintains test coverage. These personas are documented to ensure clear ownership for artifacts like the Project One-pager, Risk Register, and Release Notes. Escalation paths and communication templates help route issues quickly across team, PM, Product Lead, and Sponsor as required.

Communication is standardized via a team cadence (daily standups, weekly PM+PdM syncs, sprint demos, and monthly stakeholder updates) and templated status and incident messages to keep a single source of truth. Quality assurance relies on automated unit and integration tests, CI-based security scans, end-to-end smoke tests before release, and manual QA as needed. Metrics and dashboards track velocity, success metrics from the One-pager, and production signals to inform data-driven decisions.

Maintainers: keep this README and the linked docs up to date. Add process-specific docs into .copilot/ if you want Copilot Spaces to use them as context. When updating processes, reference the Acceptance Criteria in the issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) and link PRs to the originating issue.

## Project Management Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution &amp; Tracking](octoacme-execution-and-tracking.md)
- [Risk Management &amp; Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles &amp; Personas](octoacme-roles-and-personas.md)
