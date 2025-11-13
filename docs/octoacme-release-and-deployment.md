# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (Security Lead review completed)
- Release notes drafted (PM coordinates)
- Rollback / mitigation plan documented (DevOps Engineer owns)
- Smoke tests prepared (QA + DevOps Engineer)
- Security review completed for high-risk changes (Security Lead sign-off)
- Analytics instrumentation verified (Data Analyst confirms tracking in place)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — coordinated by PM and DevOps Engineer
- [ ] Backup or snapshot (if applicable) — DevOps Engineer responsibility
- [ ] Deploy to staging and run smoke tests — DevOps Engineer + QA
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer executes
- [ ] Run post-deploy verifications — DevOps Engineer monitors, Data Analyst checks analytics
- [ ] Announce release to stakeholders and support — PM communicates

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads technical response)
  - Engage Security Lead immediately if security-related
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Triage root cause and capture action items (PM facilitates, technical leads investigate)
  - Communicate impact to stakeholders (PM with support from DevOps and Security as needed)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
