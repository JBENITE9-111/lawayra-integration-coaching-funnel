# GitHub Repository Setup

This folder is ready to be the GitHub repository for the LaWayra integration coaching funnel.

## Current Local Repo

The local repository is initialized on branch `main` with an initial commit.

## Create Or Push The GitHub Repo

If GitHub CLI needs re-authentication:

```bash
gh auth login -h github.com
```

Then create and push the repository:

```bash
cd /Users/macmac/Documents/Codex/LAWAYRA
gh repo create lawayra-integration-coaching-funnel --public --source=. --remote=origin --push
```

If the repository already exists, just push updates:

```bash
cd /Users/macmac/Documents/Codex/LAWAYRA
git push origin main
```

## GitHub Pages

In the repository settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

## Team Upload Notes

The live funnel files are at the repository root:

- `index.html`
- `assets/`
