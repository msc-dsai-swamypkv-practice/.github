# CLAUDE.md — Claude Code entry point

## Repository

**GitHub organization profile** for the `bits-dsai` organization on GitHub.

This repository exists so GitHub can render the **organization README** from `profile/README.md`. It is **not** a course codebase: there is no `src/`, `notebooks/`, or application to run.

## Non-negotiable framing: Swamy-only

The **entire bits-dsai organization** and **all repositories under it** are:

1. **Swamy’s learning** — personal academic artifacts, not institutional or third-party curriculum.
2. **Only for Swamy** — not presented as a resource for other learners, employers, or the public. Never reword `profile/README.md` to imply a general audience, “students like you,” open courseware, or community use.

When editing `profile/README.md` or root `README.md`, **preserve and respect** that strict personal scope. Do not soften it into “welcome fellow learners” or similar unless Swamy explicitly asks.

## What to edit

- **`profile/README.md`** — Public org landing page (primary content); must keep the strict scope block accurate.
- **`README.md`** (repo root) — Short note for humans cloning this repo.
- **`LICENSE`**, **`.gitignore`** — Meta only, change rarely.

## What not to assume

- **Do not** apply Term 1 “seven-layer week companion” rules, preprocessing CI commands, or course folder layouts here. Those live in individual `t1-*` (and other) repositories.
- **Do not** add workflows, Python tooling, or skills bundles unless Swamy explicitly wants automation in *this* meta repo.

## Assistant alignment

- Prefer **clear, accurate Markdown** and the **strict personal-only** framing.
- When the user works on **course repos**, open that repository’s own `CLAUDE.md` and `.github/copilot-instructions.md` — and still treat those repos as **Swamy’s personal learning**, not public course material, unless Swamy overrides.

## Key files

| Path | Purpose |
|------|---------|
| `profile/README.md` | Organization profile shown on GitHub |
| `.github/copilot-instructions.md` | Copilot / agent scope for this repo only |
| `.cursor/rules/00_org-profile-repository.mdc` | Cursor scope for this repo only |
