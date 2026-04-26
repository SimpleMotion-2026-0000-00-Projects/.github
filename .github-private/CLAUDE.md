# CLAUDE.md

Template for the per-org `.github-private` repo.

## When working in an instance (org `<slug>/.github-private`)

- Visible only to org members. Safe for internal documentation, on-call notes, internal branding.
- GitHub recognises this repo name as the source of **private** community health defaults for the org.
- Do NOT put public-facing content here; that belongs in `<slug>/.github`.

## When working in the template itself

- Keep content generic / placeholder-driven. Use `{{ORG_SLUG}}`, `{{ORG_DISPLAY_NAME}}`, etc. for org-specific values.
- Changes here do NOT propagate to existing instances. Cross-org rollouts happen via `SimpleMotion-9997-0003-00-Orgs/scripts/`.

## IP

All IP assigned to SimpleMotion.Global Pty Ltd per `ASSIGN.md`.
