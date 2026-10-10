# A21 localization public status viewer

This repository contains **only a read-only GitHub Pages status page** and a strictly allowlisted aggregate JSON snapshot. No original PVF, source strings, translation files, local path, credentials, user identity, or direct remote-control endpoint is shipped.

Use the local (nonpublic) script:
node work/a21-multichat/mobile-status-export.mjs

to refresh status.json. The site is not live-connected to the PC. Updates appear only after the sanitized file is pushed and GitHub Pages finishes deploying. The PC app retains all code execution and AI request functions locally.

GitHub Pages: Settings > Pages > Build and deployment > GitHub Actions (or select branch main/root for a static site).
