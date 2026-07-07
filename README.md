# OiMy Design Share

A shared drop for design/dev artifacts between collaborators (HTML previews, zips, exports)
working on the OiMy landing page and related visual assets — agent-friendly: push directly
via `git` from Claude Code, Claude Design, or any local tool, no special access needed
beyond a repo collaborator invite.

## Convention
- Put each artifact in its own dated folder, e.g. `2026-07-07-landing-v9/index.html`.
- Zips are fine for multi-file exports (fonts, images, etc.) — just note in a sibling
  `.md` file what's inside and how to open it.
- This repo itself isn't meant to be the "pretty" viewing link (GitHub doesn't render
  HTML from a repo by default) — for a live clickable preview, either:
  1. Ask to have the file mirrored to `https://bharath-tj69.oimyai.com/docs/shared/...`
     (the production Hetzner static host, no login needed for viewers), or
  2. Enable GitHub Pages on this repo (Settings → Pages → Deploy from branch `main` /
     root) for a `https://aahalife.github.io/oimy-design-share/...` URL — not yet
     enabled as of repo creation (needs a repo-admin click, the automation token used
     to set this repo up doesn't have Pages permission).

No production credentials or secrets belong in this repo — it's presentation/design
assets only.
