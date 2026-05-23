# GitHub Repository Setup

This folder is ready to become the GitHub repository for the LaWayra integration coaching funnel.

## Current Local Repo

The local repository is initialized on branch `main` with an initial commit.

## Create The GitHub Repo

Because the current `gh` token on this machine is invalid, re-authenticate first:

```bash
gh auth login -h github.com
```

Then create and push the repository:

```bash
cd /Users/macmac/Documents/Codex/LAWAYRA
gh repo create lawayra-integration-coaching-funnel --private --source=. --remote=origin --push
```

Use `--public` instead of `--private` only if the team wants this repository publicly visible.

## Team Upload Notes

- Upload `landing_page/` to the funnel server if the team only needs the live page files.
- Upload the whole repository if the server expects a project root.
- The root `index.html` redirects to `landing_page/`.

## Before Launch

- Replace the consultation CTA URL with the final booking/funnel URL.
- Confirm legal/disclaimer language.
- Confirm image usage permissions.
