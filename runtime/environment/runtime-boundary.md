# Runtime Boundary

## The secure runtime exists to own sensitive operations.

It must handle:
- authentication and entitlements
- webhook validation
- protected delivery flows
- audit logging
- tenant and package state
- managed secure mode

## The runtime must not be replaced by
- public Wix logic
- GitHub Pages or static hosting
- client-side scripts storing protected state

## Design rule

If an operation needs revocable access, signed delivery, protection, or auditable state, it belongs in the runtime.
