# Workflow

## Core Operating Rules

- Keep changes focused and well-scoped. Avoid unnecessary cross-file churn.
- All code must pass CI before merging to main.
- Route issues through GitHub Issues with appropriate labels.
- Before finalizing work, ensure documentation is updated.
- Follow the organization-wide contribution guidelines.

## Documentation Contract

- If you change public APIs, features, or workflows, update the README and any relevant docs.
- Keep agent-facing guidance synchronized through `.agent/` instead of adding divergent copies.
- Before closing a local implementation slice, record the change in `.agent/phases/current.md`.

## Delivery Style

- Prefer concise, structured work with concrete file ownership and verification notes.
- Test your changes before marking them complete.
- Link related issues and PRs across repositories when work spans the organization.
