# Wix / GitHub / Azure Split

## Wix
Owns the commercial shell and public interaction layer.

### Allowed in Wix
- page composition
- CMS content
- forms and onboarding shell
- public proof, comparison, FAQ, and pricing pages
- light UI logic

### Not allowed in Wix
- secrets
- protected delivery logic
- entitlement checks
- tenant state of record
- sensitive workflow execution

## GitHub
Owns governance and versioned source of truth.

### Allowed in GitHub
- package definitions
- prompt and safeguard templates
- policies
- Wix mappings
- runtime contracts
- QA and release documents

### Not allowed in GitHub
- secrets
- customer-sensitive state
- live runtime credentials
- production-only protected data

## Azure secure runtime
Owns sensitive execution and control.

### Must live in runtime
- auth and entitlements
- webhook/API validation
- provisioning and protected delivery
- auditability and logging
- managed secure mode flows
