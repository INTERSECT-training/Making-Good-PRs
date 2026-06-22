---
title: 'Instructor Notes'
---

## Timing and Schedule

This lesson is designed for a **single 60-minute slot**. It pairs naturally with the **Issue
Tracking** lesson and continues its **StarSort** scenario.

| Time | Episode | Notes |
|------|---------|-------|
| ~8 min | **Introduction** | Benefits table, StarSort callback, and the spack scavenger hunt. |
| ~16 min | **Basic Pull Requests** | The good-PR checklist (moved here, up front) + opening the StarSort fix PR. |
| ~12 min | **Labels and Templates** | Labels recap + building a PR template. |
| ~9 min | **Spotting 'Good' (and Bad) PRs** | The **PR Critique game** — formerly a lecture, now hands-on. |
| ~15 min | **Code Reviews** | Partner reviews — the collaborative high point. Protect this time. |

Total ~60 min.

## The StarSort continuation

This lesson continues the **StarSort** story from Issue Tracking: learners fix the bug they
filed last time. It works fine standalone too — if they skipped Issue Tracking, "fix the
StarSort bug" just means "make a small change to your `README.md`." Play the maintainer when
they `@`-mention you or request a review.

## Running the PR Critique game (good-prs episode)

Learners diagnose three deliberately flawed PRs (too many changes / no description / oversized).
Run it fast and out loud — call on the room, then reveal the solution block. It reinforces the
better practices through spotting violations, which is the reviewer skill.

## Running the partner reviews (reviews episode)

The two partner-review exercises are the best part of the lesson — **protect this time**.
Learners need to add each other as collaborators (or share a repo) to formally request changes.

- Encourage **kind, specific** feedback (suggest, don't just criticize) — see Conventional
  Comments in the learner references.

## GenAI thread

GenAI is woven throughout, never a standalone block:

- **Basic PRs** — draft a PR description from a diff (then supply the *why*).
- **Labels** — generate a PR template, then trim.
- **Good/Bad PRs** — AI as a first-pass reviewer / diff-summarizer, with limits.
- **Reviews** — AI review assistants before human review; data/IP caveat for research code.

Through-line: **AI drafts and assists; the human owns the merge decision.**
