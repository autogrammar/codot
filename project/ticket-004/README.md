# Ticket 004: Verify and consolidate 3 pending API dependency upgrades

- **ID**: ticket-004
- **Owner**: agent:codex
- **Status**: IN_PROGRESS
- **Workflow state**: PUBLICATION
- **Created**: 2026-10-07

SESSION_EXECUTION_AUTHORIZATION: User requested continuing repairs, tests and protected publication of pending PRs. Consolidates Codot PR #12 (uvicorn), #13 (PyJWT) and #14 (jsonschema) after adding independently approved hosted API CI.

## Acceptance criteria

- [x] AC-01: Only the three requested version pins change; both Python versions pass existing tests and actual dependency binding smoke checks.
- [ ] AC-02: Native governance, all four hosted checks and independent exact-head protected publication pass.
