# Contributing to Quattrobit repositories

Thank you for taking the time to improve the project. Repository-specific instructions take precedence; the rules below apply when a repository does not define its own guide.

## Before opening a change

1. Start with an issue for behavioral, architectural, or security-sensitive changes.
2. Keep the change focused on one responsibility.
3. Follow the repository's existing architecture and verification commands.
4. Update contracts and documentation when behavior changes.
5. Remove credentials, personal data, generated secrets, and local environment files.

## Architectural boundary

- Shared cross-runtime contracts belong in `octron-protocol`.
- Product runtimes consume versioned contracts; they do not redefine them locally.
- Public or source-available repositories must not import private implementation code.
- Security and privacy claims require tests at the boundary they describe.

## Pull requests

A useful pull request explains the problem, the chosen boundary, verification performed, and any compatibility or rollout impact. Large mixed refactors may be returned for separation even when the code works.

By contributing, you agree that your work is distributed under the license of the repository receiving the change.
