# Ticket 003: Verify API dependency candidates in hosted CI

- **ID**: ticket-003
- **Owner**: agent:codex
- **Status**: IN_PROGRESS
- **Workflow state**: PUBLICATION
- **Created**: 2026-10-07

SESSION_EXECUTION_AUTHORIZATION: User requested continuing repairs, tests and protected publication of overdue PRs. This ticket adds actual API test coverage needed for Codot dependency publication.

## Acceptance criteria

- [x] AC-01: Existing API tests run against candidate requirements on Python 3.10 and 3.12 for every PR and main push, with read-only GitHub permissions.
- [ ] AC-02: Native governance and independent exact-head CI verification pass before protected publication.
