# .github
Shared workflows and templates used across SFDO-Tooling repositories.

## Shared Workflows

The following workflows are reused across the SFDO-Tooling organization:

### Docs Review
`docs.yml`: Shared SFDO-Tooling Docs Review, which requests review from a technical writer when a pull request modifies markdown or RestructuredText files, and fails until the writer approves the PR.

### Pre-Commit Linting
`pre-commit.yml`: SFDO-Tooling Pre-commit, which provides a pre-configured workflow to run [pre-commit](https://pre-commit.com/index.html), which typically includes auto-formatters and code linting utilities.

Inputs:
  - `python-version` (default: `3.10`):specifies the python version used to run `pre-commit`.


