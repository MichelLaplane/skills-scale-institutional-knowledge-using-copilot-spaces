# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager coordinates all release activities and ensures proper communication.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — **Owner: Release Manager**
- [ ] Backup or snapshot (if applicable) — **Owner: DevOps/Infrastructure**
- [ ] Deploy to staging and run smoke tests — **Owner: Developer/DevOps**
- [ ] Smoke tests validated — **Owner: QA**
- [ ] Release notes finalized — **Owner: Release Manager with input from Product Manager**
- [ ] Stakeholders notified of upcoming release — **Owner: Release Manager**
- [ ] Deploy to production (automated pipeline preferred) — **Owner: Developer/DevOps**
- [ ] Run post-deploy verifications — **Owner: QA/Developer**
- [ ] Monitor error rates and key metrics — **Owner: Developer/On-call**
- [ ] Announce release to stakeholders and support — **Owner: Release Manager**
- [ ] Update documentation if needed — **Owner: Technical Writer/Developer**

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Related Documents
- [RACI Matrix](./roles-raci.md) - Role accountability for release activities
- [Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role descriptions including Release Manager
