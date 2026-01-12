# Copilot instructions for this repository

This is a small static site repository (single-page) containing `index.html` and `style.css`.
Keep guidance compact and focused on actionable, repository-specific details so AI coding agents are immediately productive.

**Quick Context**
- Project type: Static HTML/CSS (no build tool). Key files: `index.html`, `style.css`, `README.md`.
- Dev container: `.devcontainer/devcontainer.json` exists — use Codespaces / devcontainer for a consistent environment.

## Copilot instructions — 01-codepilot

This is a minimal static site: a single HTML page and a single global CSS file. Key files:

- [index.html](index.html) — page markup (header/title present).
- [style.css](style.css) — global styling for the page.
- [README.md](README.md) — project notes and preview hints.
- .devcontainer/devcontainer.json — devcontainer available for Codespaces.

Quick facts
- No build tool or bundler. The site is served as static files.
- No JS present by default; behavioral changes are not required here.

Common tasks & examples
- Edit page content: update the DOM in [index.html](index.html) (e.g., modify the `<header>` and `<h1>`).
- Edit visual styles: change selectors in [style.css](style.css). Styles are global — prefer small, targeted edits.

Previewing locally
- Simple Python server: `python -m http.server 8000` then open http://localhost:8000
- Alternative: `live-server` (npm) for auto-reload.
- In Codespaces/devcontainer forward port `8000` to preview the running server.

Developer notes for agents
- Keep changes minimal and focused — this repo favors tiny, surgical edits.
- When adding new files (JS, build tooling), update [README.md](README.md) with exact commands to run and preview.
- No tests or CI detected — validate changes by running the local preview and verifying visual output.

PR & commit guidance
- One logical change per PR. In the PR description include: what changed, why, and the preview steps (the `python -m http.server` command is sufficient).

If anything here is unclear or you want more details (devcontainer usage, preview automation, or suggested branch naming), tell me which part to expand.
If anything in this file is unclear or missing, tell me which parts you want expanded (devcontainer details, preferred preview commands, or commit conventions).
