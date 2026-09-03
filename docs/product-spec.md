# Notes — Product Spec

## Problem

Most note-taking tools require an account, a backend, or a heavier app than a quick note needs. Sometimes the fastest way to jot something down is a page that opens instantly with no sign-up.

## Target user

Anyone who wants a fast, no-friction place to write and keep short notes in the browser, without creating an account or installing anything.

## Goals

- Zero friction from opening the page to writing a note
- No backend, no account, no setup
- Notes persist locally between visits

## Non-goals (v1)

- Multi-device sync
- Collaboration / sharing notes with others
- Rich text / attachments

## Core features (v1 scope)

| Feature | Description |
| --- | --- |
| Create/edit notes | Instant create and edit, no save button |
| Search | Filter notes by title/content |
| Theme toggle | Light/dark mode |
| Local persistence | Notes stored in the browser so they survive a refresh |

## User stories

- As a user, I want to create a note instantly without signing up.
- As a user, I want my notes to still be there when I come back to the page.
- As a user, I want to search my notes quickly as the list grows.

## Status

Live at pryank18.github.io/notes-app/. Single-device, browser-local storage only — no sync across devices in v1.
