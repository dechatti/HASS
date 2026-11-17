# Contributing

## Branches
- `main`: stable, release-ready code
- `develop`: integration branch; all feature work merges here
- `feature/<short-name>`: new work, branched from `develop`
- `fix/<short-name>`: bug fixes, branched from `develop`

## Workflow
1. Branch from `develop`.
2. Make small, focused commits (for example `feat: add patient search`, `fix: correct slot overlap check`).
3. Open a pull request into `develop` and wait for CI to pass.
4. Merge `develop` into `main` only for releases.