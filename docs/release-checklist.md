# Release & Deployment Checklist

Pre-release
- [ ] Confirm all acceptance criteria are met and PRs merged
- [ ] CI and security scans passed
- [ ] Release notes drafted with notable changes and migration steps
- [ ] Backup/rollback plan documented and tested (if applicable)
- [ ] Stakeholders and on-call notified of planned window

Staging
- [ ] Deploy to staging
- [ ] Run smoke tests and critical path E2E checks
- [ ] Verify metrics and logs for anomalies

Production
- [ ] Deploy following approved pipeline
- [ ] Run post-deploy verification checks (smoke tests, key dashboards)
- [ ] Monitor for errors and performance regressions
- [ ] Communicate release complete to stakeholders

Post-release
- [ ] Capture any incidents and start a blameless retrospective
- [ ] Update runbooks and action items in backlog
