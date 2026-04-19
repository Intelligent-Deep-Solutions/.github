# Contributing to IDeeps

Thank you for contributing to an IDeeps project. This document describes the workflow we follow across all our repositories.

## Branch strategy
- `main` is protected. No direct pushes are allowed.
- Create feature branches from `main` using the format: `feature/<short-description>`, `fix/<short-description>`, or `chore/<short-description>`.

## Commit messages
Use the Conventional Commits style:
- `feat:` new feature
- `fix:` bug fix
- `docs:` documentation only
- `refactor:` code change that neither fixes a bug nor adds a feature
- `test:` tests only
- `chore:` maintenance tasks

Example: `feat(auth): add OAuth login flow`

## Pull requests
1. Open a PR against `main` using our PR template.
2. Link the related issue (if any).
3. Ensure all CI checks pass.
4. Request review from at least one member of the relevant team.
5. Squash and merge once approved.

## Code quality
- Follow the linter and formatter defined in each repository.
- Write tests for new features and bug fixes.
- Keep PRs focused and reasonably sized.

## Questions?
Reach out in the organization Discussions or email info@ideeps.ai.
