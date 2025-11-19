# OctoAcme — Release Checklist

This checklist provides a practical, step-by-step guide for preparing and executing releases. Each item indicates the role(s) primarily responsible.

## Pre-Release Validation

- [ ] **All acceptance criteria met and PRs merged** — `Dev`, `QA`
- [ ] **CI pipeline passing (build, tests, security scans)** — `Dev`, `Tech Lead`
- [ ] **Code review completed for all changes** — `Tech Lead`, `Dev`
- [ ] **Integration tests passing in staging environment** — `QA`
- [ ] **End-to-end smoke tests executed successfully** — `QA`
- [ ] **Performance and load testing completed (if applicable)** — `Dev`, `QA`
- [ ] **Security vulnerabilities addressed or accepted** — `Tech Lead`, `Dev`
- [ ] **Database migrations tested and reviewed** — `Dev`, `Tech Lead`
- [ ] **Feature flags configured (if using progressive rollout)** — `Dev`, `Release Manager`

## Release Documentation

- [ ] **Release notes drafted and reviewed** — `PdM`, `PM`, `Release Manager`
- [ ] **Known issues and limitations documented** — `QA`, `Dev`
- [ ] **Migration steps documented (if required)** — `Dev`, `Tech Lead`
- [ ] **Rollback plan documented and validated** — `Release Manager`, `Tech Lead`
- [ ] **Runbook updated with new operational procedures** — `Dev`, `Release Manager`

## Approvals and Communications

- [ ] **Product Manager sign-off on feature completeness** — `PdM`
- [ ] **QA sign-off on testing completion** — `QA`
- [ ] **Technical Lead approval on release readiness** — `Tech Lead`
- [ ] **Stakeholders notified of release schedule** — `PM`, `Release Manager`
- [ ] **Support team briefed on new features and potential issues** — `PdM`, `PM`
- [ ] **Release window scheduled and communicated** — `Release Manager`, `PM`

## Deployment Execution

- [ ] **Backup or snapshot created (if applicable)** — `Dev`, `Release Manager`
- [ ] **Deployment to staging environment successful** — `Dev`, `Release Manager`
- [ ] **Smoke tests pass in staging** — `QA`
- [ ] **Deploy to production (via automated pipeline or manual process)** — `Release Manager`, `Dev`
- [ ] **Post-deployment verifications completed** — `Dev`, `QA`, `Release Manager`
  - Health checks passing
  - Key metrics within expected ranges
  - Critical user flows working
- [ ] **Monitoring dashboards reviewed for anomalies** — `Dev`, `Release Manager`

## Post-Release Activities

- [ ] **Release announcement sent to stakeholders** — `Release Manager`, `PM`
- [ ] **Support team and customer success notified** — `PdM`, `PM`
- [ ] **Release retrospective scheduled** — `PM`, `Scrum Master`
- [ ] **Production monitoring active for next 24-48 hours** — `Dev`, `Release Manager`
- [ ] **Release tagged in version control** — `Dev`, `Release Manager`
- [ ] **Release documented in project tracking system** — `PM`, `Release Manager`

## Rollback Procedures (If Needed)

- [ ] **Incident declared and on-call team notified** — `Release Manager`, `Dev`
- [ ] **Rollback decision made and communicated** — `Release Manager`, `Tech Lead`
- [ ] **Rollback executed to last known-good release** — `Dev`, `Release Manager`
- [ ] **Post-rollback verification completed** — `QA`, `Dev`
- [ ] **Root cause analysis initiated** — `Tech Lead`, `Dev`
- [ ] **Action items captured for future releases** — `PM`, `Scrum Master`

---

## Role Shortcodes Reference

- **PdM** = Product Manager
- **PM** = Project Manager  
- **Dev** = Developer
- **QA** = QA Engineer
- **Tech Lead** = Technical Lead
- **Release Manager** = Release Manager
- **Scrum Master** = Scrum Master

---

For more information on release processes, see [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md).

For role definitions and interactions, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).
