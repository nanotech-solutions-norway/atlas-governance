# ADR-001: Governance Repository Model

## Status
Accepted

## Decision
Atlas will maintain a dedicated governance repository as the versioned source of truth for package definitions, policies, mappings, prompt architecture, and runtime contracts.

## Rationale
A separate governance plane reduces drift between the public website, the secure runtime, and the commercial package definitions.

## Consequences
- public-facing changes must be reflected here before release
- runtime contracts must be versioned here
- Wix mappings must be aligned to approved fields and routes
