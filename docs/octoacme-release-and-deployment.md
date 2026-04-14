# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (DevOps Engineer + Security Lead sign-off)
- Release notes drafted (Technical Writer)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA / DevOps Engineer)
- Support team briefed on upcoming changes (Support/Customer Success)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Project Manager + DevOps Engineer
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Security sign-off from Security Lead (for major releases)
- [ ] Deploy to staging and run smoke tests — DevOps Engineer + QA
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer + QA
- [ ] Announce release to stakeholders and support — Project Manager + Support/Customer Success
- [ ] Update public documentation and release notes — Technical Writer

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
