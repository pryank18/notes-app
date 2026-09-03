# Notes — Product Requirements Document

## Summary

A single-page notes app that opens instantly and requires no account, backend, or setup — for anyone who wants a fast place to write short notes in the browser.

## Target users

Anyone needing a quick, low-friction place to capture notes without the overhead of a full note-taking platform or account creation.

## Problem statement

Most note apps require an account and a backend, which is more overhead than a quick note needs. There's a gap for a note tool that opens instantly and just works.

## Functional requirements

1. **Create/edit notes** — instant creation and editing, no save button
2. **Search** — filter the note list by title/content
3. **Theme toggle** — light/dark mode
4. **Local persistence** — notes stored in the browser so they survive a refresh

## Out of scope (v1)

- Multi-device sync
- Collaboration / sharing
- Rich text or attachments

## Success metrics

- Time from page load to first note created (target: near-instant)
- Notes retained across sessions without data loss

## Status

Live at pryank18.github.io/notes-app/, as a small self-contained utility project with no backend.
