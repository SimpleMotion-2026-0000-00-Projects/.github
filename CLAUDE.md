# CLAUDE.md

## What this repo is

The **public org profile repo** for `SimpleMotion-2026-0000-00-Projects`. GitHub renders `profile/README.md` at https://github.com/SimpleMotion-2026-0000-00-Projects — that's the only meaningful content.

## Architecture

- `profile/README.md` — the only user-facing content; shown on the org page.
- **Brand assets are referenced by raw URL** from tier-0 `simplemotion/.github/profile/sm-assets/`. Do **not** duplicate the SM lockup / favicons / logos here — the tier-0 tree is the source of truth and propagating edits across per-org copies is a losing battle.
- No issue templates, no PR template, no workflow templates. Those org-level defaults live in `.github-private` (for private/internal child repos) or in `simplemotion/.github` (for public child repos).

## Visibility

This repo is **public** — that's the GitHub convention for `.github` so the org profile renders for non-members. The containing org `SimpleMotion-2026-0000-00-Projects` is `INTERNAL`, so in practice the profile page is only reachable by enterprise members, but keep the repo itself public to match GitHub's expected pattern.

## Rules

- Do not include `Co-Authored-By` trailers in git commits.
- IP is assigned to SimpleMotion.Global Pty Ltd per `ASSIGN.md`.
