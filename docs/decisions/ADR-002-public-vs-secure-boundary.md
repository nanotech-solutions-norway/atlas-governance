# ADR-002: Public vs Secure Boundary

## Status
Accepted

## Decision
Atlas will separate public-safe commercial content from protected runtime operations.

## Public-safe layer
- approved package descriptions
- pricing and FAQ copy
- public trust and proof content
- non-sensitive Wix field mappings

## Secure layer
- entitlements
- protected delivery
- audit logging
- secret handling
- customer-sensitive execution state

## Consequences
Any feature requiring revocable access, signed delivery, protected state, or policy enforcement must be routed to the secure runtime.
