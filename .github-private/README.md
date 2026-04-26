<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/{{ORG_SLUG}}/.github-private/main/assets/banners/SM-Black.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/{{ORG_SLUG}}/.github-private/main/assets/banners/SM-White.svg">
    <img alt="SimpleMotion" src="https://raw.githubusercontent.com/{{ORG_SLUG}}/.github-private/main/assets/banners/SM-White.svg" width="800">
  </picture>
</p>

<p align="center">
  <strong>🔒 INTERNAL — SimpleMotion enterprise members only</strong>
</p>

# {{ORG_DISPLAY_NAME}} — `.github-private`

Private org-level defaults for `{{ORG_SLUG}}`. Visible only to SimpleMotion enterprise members.

## What's here

- `assets/` — internal branding and avatar variants not appropriate for public view (see `assets/README.md`).
- Internal playbooks, on-call notes, and issue templates for private repos — added here as they stabilise.

## What does *not* belong here

Public-facing content. Anything intended for public viewers — profile README, public contributing guide, public security policy — lives in `{{ORG_SLUG}}/.github`.

## How it's managed

Instantiated from `SimpleMotion-9998-0000-00-Templates/SimpleMotion-9998-0004-00-SM-Template-dot-github-private`. Cross-org updates happen at the template. Rollout automation lives in `SimpleMotion-9997-0000-00-Workflows/SimpleMotion-9997-0003-00-Orgs`.
