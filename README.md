# .github
Shared workflows and templates used across SFDO-Tooling repositories.

## Shared Workflows

The following workflows are reused across the SFDO-Tooling organization:

### Docs Review
`docs.yml`: Shared SFDO-Tooling Docs Review, which notifies documentation writers when a pull request is labeled with "doc review needed", and fails until the "docs reviewed" label is added.

### Pre-Commit Linting
`pre-commit.yml`: SFDO-Tooling Pre-commit, which provides a pre-configured workflow to run [pre-commit](https://pre-commit.com/index.html), which typically includes auto-formatters and code linting utilities.

Inputs:
  - `python-version` (default: `3.10`):specifies the python version used to run `pre-commit`.


