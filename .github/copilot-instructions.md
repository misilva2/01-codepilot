# Copilot instructions for this repository

This is a small static site repository (single-page) containing `index.html` and `style.css`.
Keep guidance compact and focused on actionable, repository-specific details so AI coding agents are immediately productive.

**Quick Context**
- Project type: Static HTML/CSS (no build tool). Key files: `index.html`, `style.css`, `README.md`.
- Dev container: `.devcontainer/devcontainer.json` exists — use Codespaces / devcontainer for a consistent environment.

**What to edit**
- Change markup in `index.html` for structure/content updates.
- Change visual styles in `style.css`. There is no JS; frontend behavior is purely static.

**Local preview**
- There is no build step. Preview the site by opening `index.html` in a browser or serving the folder:

```bash
python -m http.server 8000
# or
npm install -g live-server && live-server
```

In Codespaces / devcontainer, forward port `8000` to preview the running server.

**Testing & CI**
- No tests or CI configured in this repo. Small iterative changes should be verified by running the local preview.

**Coding conventions & patterns**
- Keep markup semantic and minimal: this project favors straightforward HTML structure in `index.html`.
- CSS is global (single `style.css`), not component-scoped — avoid introducing heavy CSS frameworks without updating README.

**Change suggestions for agents**
- For content changes: modify `index.html` and run a quick preview to verify layout.
- For style tweaks: edit `style.css`; prefer small, incremental changes and verify visually.
- If adding JS or new tooling, include a short note in `README.md` documenting the new commands and rationale.

**Commit & PR guidance**
- Keep changes small and focused: one logical change per branch/PR.
- PR description: state what changed, why, and how to preview locally (commands above).

If anything in this file is unclear or missing, tell me which parts you want expanded (devcontainer details, preferred preview commands, or commit conventions).
