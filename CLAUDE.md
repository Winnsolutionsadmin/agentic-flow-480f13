# ⬆️ UPSTREAM SOURCE OF TRUTH — READ BEFORE ANY WORK

**This repo is a DOWNSTREAM publish target, not the project.** It is the GitHub Pages mirror of one self-contained concept mock-up HTML file. The canonical working copy and its memory-bank live in a private Winn.solutions working folder, NOT in this repo. The exact upstream path is recorded in the operator's local `~/.claude` session-context registry (keyed by this repo's git remote) and auto-injects at session start via the `load-core-context.ts` hook. It is deliberately NOT committed here because this repo is public. If the injected upstream memory and this repo ever disagree, **the upstream working-folder memory wins.**

## What this is

An unlisted GitHub Pages deploy of a confidential concept mock-up: an agentic application / Builder Grant candidate-journey flow (design-language demo, not a live product). Served with `.nojekyll`, `robots.txt` Disallow-all, and `noindex,nofollow,noarchive,nosnippet` meta — effectively an unlisted, confidential link.

Repo type: **published-deploy** (static, no build step). Edit the upstream source, then copy → commit → push here; Pages rebuilds automatically (hard-refresh to see changes).
