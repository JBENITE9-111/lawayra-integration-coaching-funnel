# LaWayra Post-Retreat Integration Coaching Funnel

A clean, repository-ready static landing page package for LaWayra's post-retreat integration coaching funnel. The page is designed to be shared with the team and uploaded to any static server, funnel builder, or hosting provider.

## Quick Preview

Open this file directly in a browser:

`landing_page/index.html`

No local server or build step is required.

## Repository Structure

```text
.
├── index.html                  # Redirects to landing_page/ for root hosting
├── landing_page/               # Deployable funnel page
│   ├── index.html              # Main landing page
│   ├── README.md               # Page-specific notes
│   └── assets/images/          # Only images required by the live page
├── docs/                       # Team handoff, deployment, and source notes
├── source_materials/           # Archived AP source files and extra assets
├── AGENTS.md                   # Codex instructions for future work
├── .gitignore
└── .nojekyll                   # Keeps GitHub Pages from processing the site with Jekyll
```

## What To Upload To The Server

Upload the contents of `landing_page/` when the team wants only the funnel page.

Upload the whole repository if the hosting service expects a project root. The root `index.html` redirects visitors to `landing_page/`.

## Current CTA

The page uses this team-ready CTA:

`Book your free 30 min consultation`

The CTA currently points to `https://ayahuascaincolombia.com`. Replace this URL with the final calendar or funnel URL before launch.

## Useful Docs

- `docs/DEPLOYMENT.md` - upload and GitHub Pages notes.
- `docs/TEAM_HANDOFF.md` - what the team should review before launch.
- `docs/CONTENT_GUIDE.md` - brand, copy, and editing guidance.

## Source Reference

The original source/reference folder remains here:

`/Users/macmac/Documents/LAWAYRA/AP_PROJECT`

A copy of the source material used for this build is preserved in `source_materials/`.
