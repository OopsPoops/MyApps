# MyApps

Single-page app launcher (`index.html`, vanilla HTML/CSS/JS, no build step). Hosted at https://oopspoops.github.io/MyApps/ from the `main` branch of https://github.com/OopsPoops/MyApps.

## Workflow

- Edit `index.html` directly, commit, and **push to `main` immediately** — the user asked for changes to go live without a review step.
- Remote URL: `https://github.com/OopsPoops/MyApps.git` (repo moved from `oopspoops` to `OopsPoops`).
- Do not commit `.DS_Store` or stale local files (e.g. `assets/icons/runner-cat*.svg` were deleted upstream).

## Verify

- Serve locally: `python3 -m http.server <port>` inside this folder, open `http://localhost:<port>/`.
- `agent-browser` CLI is installed for screenshots/DOM checks.
