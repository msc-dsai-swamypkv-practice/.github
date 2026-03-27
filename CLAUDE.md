# CLAUDE.md — Claude Code entry point

## Repository

**GitHub organization profile** for the `bits-dsai` organization on GitHub.

This repository exists so GitHub can render the **organization README** from `profile/README.md`. It is **not** a course codebase: there is no `src/`, `notebooks/`, or application to run.

## What to edit

- **`profile/README.md`** — Public org landing page (primary content).
- **`README.md`** (repo root) — Short note for humans cloning this repo.
- **`LICENSE`**, **`.gitignore`** — Meta only, change rarely.

## What not to assume

- **Do not** apply Term 1 “seven-layer week companion” rules, preprocessing CI commands, or course folder layouts here. Those live in individual `t1-*` (and other) repositories.
- **Do not** add workflows, Python tooling, or skills bundles unless the org explicitly wants automation in *this* meta repo.

## Assistant alignment

- Prefer **clear, accurate Markdown** and preserve the disclaimer and personal-academic framing in `profile/README.md` unless the author asks to change it.
- When the user works on **course repos**, open that repository’s own `CLAUDE.md` and `.github/copilot-instructions.md`.

## Key files

| Path | Purpose |
|------|---------|
| `profile/README.md` | Organization profile shown on GitHub |
| `.github/copilot-instructions.md` | Copilot / agent scope for this repo only |
| `.cursor/rules/00_org-profile-repository.mdc` | Cursor scope for this repo only |
