# Agam Documentation Website — Agent Board

This directory is the shared source of truth for agent-facing project guidance.
Use it as the canonical layer behind `AGENTS.md` and `CLAUDE.md`.

## Layout

- `include/`: compact shared context that all agents should read first.
- `rules/`: repo guardrails for structure, quality, and process.
- `policy/`: structured operating rules and project overview.
- `phases/`: compact phase-status board for what is active, complete, and next.
- `skills/`: repeatable project-specific workflows.

## Start Order

1. Read the root entrypoint for your client: `AGENTS.md` or `CLAUDE.md`.
2. Read `include/project-context.md` and `include/workflow.md`.
3. Read `phases/current.md` when deciding what to build next.
4. Read `policy/` for structured operating rules.
5. Read relevant files under `rules/`.
6. Use `skills/` when routing specialized work.

## Organization Context

This repository is part of the `agam-lang` GitHub organization.
The core compiler lives at `agam-lang/agam`.
Cross-repository architecture is documented in the `.github` repo's profile README.
