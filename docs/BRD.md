# Notes — Business Requirements Document

## Business objective

Provide a zero-friction, no-account note-taking tool as a small self-contained utility, distinct from account-based note platforms.

## Background

Most note-taking products require account creation and a backend, adding overhead for a task that's often just "write this down quickly." Notes is scoped intentionally small to remove that overhead entirely.

## Scope

**In scope:** create/edit notes, search, theme toggle, browser-local persistence.

**Out of scope:** multi-device sync, collaboration/sharing, rich text or attachments, backend/account system.

## Stakeholders

- **Primary user:** anyone wanting a fast, no-signup note tool
- **Product owner:** Pryank Wadhera

## Success criteria

- Instant usability with zero setup or account creation
- No data loss across browser sessions on the same device

## Assumptions

- Users are comfortable with notes being stored locally in a single browser (no cross-device access)

## Constraints

- No backend by design — this is a deliberate scope decision, not a limitation to be fixed

## Risks

- Local-only storage means clearing browser data removes notes; this is a known and accepted trade-off for the zero-account model

## Status

Live as a small, self-contained utility project with no backend.
