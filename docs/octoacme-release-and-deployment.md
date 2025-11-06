# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager owns this process and coordinates with all relevant teams.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (validated by Security Lead)
- Release notes drafted (by Technical Writer or Release Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared (by QA Testers)
- UX review completed for user-facing changes
- Support team briefed on new features and known issues

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) by Release Manager
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA sign-off required)
- [ ] Security review completed by Security Lead
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Release notes published (Technical Writer coordinates)
- [ ] Announce release to stakeholders and support team
- [ ] Hand-off to Support Engineers with known issues and troubleshooting guide

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager leads coordination)
  - Notify Support Engineers immediately to prepare for user communications
  - Rollback to last known-good release if necessary
  - Security Lead assesses if incident has security implications
  - Triage root cause and capture action items
  - Support Engineers update knowledge base and communicate with affected users

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
