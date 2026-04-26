# Internal org assets

Source-of-truth for this org's internal branding assets (e.g. internal-only logo variants, avatars for private contexts).

## Files

- `avatar-internal.png` — square PNG, ≥500×500, <1 MB. Optional internal variant; only used where explicitly referenced, since org avatar on github.com is set via `<org>/.github/assets/avatar.png`.

## Conventions

- Contents are visible only to org members. Appropriate for internal-only logos, pre-release branding, restricted illustrations.
- Do NOT duplicate public assets here — reference `<slug>/.github/assets/` via README link where needed.
- Append to `PROVENANCE.md` (create if missing) when swapping any asset: `YYYY-MM-DD <short-sha> <asset> <uploader>`.
