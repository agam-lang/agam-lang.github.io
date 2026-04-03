# Agam Documentation Website — Agent Instructions

This file is the Codex entrypoint and universal repo entrypoint for shared agent guidance.
The canonical shared source of truth lives under `.agent/`.

## Read First

- `.agent/README.md`
- `.agent/include/project-context.md`
- `.agent/include/workflow.md`
- `.agent/phases/current.md`
- `.agent/rules/`

## Non-Negotiables

- This repository is part of the `agam-lang` organization ecosystem.
- All work must align with the Agam language vision: Python readability, Rust safety, native performance.
- Follow the coding and quality standards defined in `.agent/rules/`.
- Before closing a local slice, update `.agent/phases/current.md` and commit.

## Repo Map

- `.agent/`: canonical project guidance, rules, phases, skills, and policies
- `.github/`: CI/CD workflows and GitHub automation
- `README.md`: public-facing project description

## Multi-Agent Guidance

- Shared routing rules: `.agent/include/workflow.md`
- Role briefs and policies: `.agent/policy/`
