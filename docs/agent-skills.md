# Agent skills (`SKILL.md`) — how I use them here

This note documents **my** agent-tooling layout in this repository. It is not written for a general audience.

## What a skill is

A **skill** is a Markdown file with:

- **YAML frontmatter** — typically `name` and `description` (short, so an agent can match a task without loading the whole file).
- **Body** — procedures, checklists, or commands to follow when the task fits.

There is no separate SDK: plain Markdown in a folder tree.

## Progressive disclosure

The frontmatter acts as a **hook**. The body loads when the task is relevant. That keeps always-on context smaller than inlining every workflow into `CLAUDE.md` or rules.

## How this fits beside other mechanisms

| Mechanism | Role |
|-----------|------|
| `CLAUDE.md`, `.cursor/rules/`, `.github/copilot-instructions.md` | Standing project boundaries and habits |
| `.github/skills/**/SKILL.md` | On-demand workflows (for example org-profile editing or shared habits) |
| MCP (when configured) | Live tools and external data |

Skills **complement** those layers; they do not replace them.

## Paths in this repo

- **Canonical:** `.github/skills/` (what I treat as the source for Copilot).
- **Mirror:** `.cursor/skills/` — kept **byte-identical** to `.github/skills/` where `.github/workflows/ci-skills-parity.yml` runs.

This org-profile repository has **no** course layout (`src/`, `notebooks/`, and so on). Trimester repos under the same organization use the **same** skills file shape, often with additional packs (for example `ci-checks`).

If I use another assistant that expects skills under its own directory, I **copy** the same `SKILL.md` content into the path that tool documents.

## Pointers

- Short index: `.cursor/skills.md`
- Org-specific skill: `.github/skills/org-profile/SKILL.md`
