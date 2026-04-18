# Atlas Governance Repository

This repository is the governance plane for Atlas.

It is the source of truth for:
- launch offer definitions
- configuration blocks
- prompt architecture
- Wix CMS and form contracts
- route logic
- runtime payload contracts
- policies, QA, and release checklists
- brand and messaging guardrails

## System split

Atlas is operated across three planes:

1. **Wix commercial shell**
   - public website
   - CMS-driven content
   - forms and onboarding entry points
   - public proof, pricing, and FAQ pages

2. **GitHub governance plane**
   - versioned source of truth
   - prompt and package definitions
   - policies and release controls
   - Wix mappings and runtime contracts

3. **Secure runtime plane**
   - authentication and entitlements
   - webhook and API handling
   - protected delivery flows
   - audit logging and tenant state

## What belongs here

- approved public claims
- package definitions
- configuration blocks
- prompt templates and overlays
- Wix field dictionaries and route maps
- runtime interface contracts
- release notes, QA, and rollback procedures

## What does not belong here

- secrets
- API keys
- customer-sensitive data
- protected runtime credentials
- production-only environment values

## Branch model

- `main` = approved governance baseline
- `develop` = active integration branch
- `release/*` = milestone preparation
- `hotfix/*` = controlled emergency change

## Core launch offers

- Internal Knowledge and Research Assistant
- Drafting and Delivery Assistant
- Meeting/Admin Follow-Through Assistant

## Operating rule

No public website change, onboarding flow change, or customer-facing package change should be treated as approved until it exists in versioned form in this repository.
