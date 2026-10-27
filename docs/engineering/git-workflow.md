# Git and Pull Request Workflow

**Status:** Proposed default; team should approve before enforcement.

## Branches

- `main`: protected integration/release branch.
- `feat/<ticket>-short-name`: feature work.
- `fix/<ticket>-short-name`: bug fixes.
- `docs/<topic>`: documentation changes.
- `chore/<topic>`: maintenance.

Adapt branch names to the existing repository where a different convention is already in use.

## Workflow

1. Sync with the base branch.
2. Create a focused branch.
3. Make small commits with meaningful messages.
4. Run relevant lint, tests, and checks.
5. Open a PR with context, issue link, risks, and validation evidence.
6. Obtain the required review; do not self-approve protected changes.
7. Merge using the repository's agreed strategy.
8. Verify CI and deployment outcome; document rollback if needed.

Protect `main`, require CI checks, restrict bypass permissions, and require review for sensitive paths where supported. Exact settings and minimum approvals: TBD.
