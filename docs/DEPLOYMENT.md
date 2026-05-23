# Deployment Guide

## Option 1: Upload Only The Funnel

Upload the contents of `landing_page/` to the server or funnel host. The landing page entry file is:

`landing_page/index.html`

Keep the `assets/images/` folder next to `index.html` so image paths continue to work.

## Option 2: Upload The Whole Repository

If the host expects a project root, upload the whole repository. The root `index.html` redirects to `landing_page/`.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload or push this folder.
3. In GitHub, go to Settings -> Pages.
4. Choose the main branch and root folder.
5. GitHub Pages will load the root `index.html`, which redirects to `landing_page/`.

## Before Launch

- Replace the consultation CTA URL with the final calendar or funnel URL.
- Confirm the legal/disclaimer language.
- Confirm all coach bios and photo usage permissions.
- Test on mobile, tablet, and desktop.
