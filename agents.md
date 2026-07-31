# AI Agent Guidelines for Awesome oCIS

This file provides context for AI coding agents (Claude Code, GitHub Copilot, Cursor, etc.) working in this repository.

## Repository Overview
- **Product family:** oCIS
- **Primary language(s):** Markdown
- **Build system:** None
- **Test framework:** None
- **CI system:** None

## Architecture & Key Paths
- `README.md` - The curated list of oCIS apps and extensions
- `webApps/` - Additional web app resources
- `LICENSE` - Apache-2.0 license

## Development Conventions
- **Branching:** main
- **Commit messages:** DCO sign-off required (`git commit -s`)
- **Code style:** Markdown formatting
- **PR process:** Open a PR against main. All CI checks must pass.

## Build & Test Commands
```bash
# Build
Not applicable - this is a curated list

# Test
Not applicable

# Lint
Not applicable
```

## Important Constraints
- All code contributions must be compatible with the **Apache-2.0** license
- Do not introduce new **copyleft-licensed dependencies** (GPL, AGPL, LGPL, MPL) without explicit discussion in an issue first. This is especially important for repos migrating to Apache 2.0.
- Do not introduce new dependencies without discussion in an issue first
- Entries should link to real, working projects
- Maintain consistent formatting for list entries


## OSPO Policy Constraints

### GitHub Actions
- **Only** use actions owned by `owncloud`, created by GitHub (`actions/*`), verified on the GitHub Marketplace, or verified by the ownCloud Maintainers.
- Pin all actions to their full commit SHA (not tags): `uses: actions/checkout@<SHA> # vX.Y.Z`
- Never introduce actions from unverified third parties.

### Dependency Management
- Dependabot is configured for automated dependency updates.
- Review and merge Dependabot PRs as part of regular maintenance.
- Do not introduce new dependencies without discussion in an issue first.

### Git Workflow
- **Rebase policy**: Always rebase; never create merge commits. Use `git pull --rebase` and `git rebase` before pushing.
- **Signed commits**: All commits **must** be PGP/GPG signed (`git commit -S -s`).
- **DCO sign-off**: Every commit needs a `Signed-off-by` line (`git commit -s`).
- **Conventional Commits & Squash Merge**: Use the [Conventional Commits](https://www.conventionalcommits.org/) format where the repository enforces it. Many repos use squash merge, where the PR title becomes the commit message on the default branch — apply Conventional Commits format to PR titles as well. A reusable GitHub Actions workflow enforces this.

## Context for AI Agents
- Match existing code style
- Do not refactor unrelated code in the same PR
- Keep PRs focused and atomic
- New entries should follow the existing list format: `[Name](URL) - Description`
- Verify that linked repositories actually exist before adding entries
