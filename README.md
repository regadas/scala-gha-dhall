# scala-gha-dhall

Example scala project using [`github-action-dhall`](https://github.com/regadas/github-actions-dhall) to manage your CI workflow.

## Usage

1. Install [`dhall`](https://github.com/dhall-lang/dhall-lang#getting-started).

2. Use one of the provided examples:

  ```bash
  curl https://raw.githubusercontent.com/regadas/github-actions-dhall/master/examples/scala.dhall > scala.dhall
  ```

3. Update it to your taste and convert it to yaml:

  ```bash
  dhall-to-yaml --file scala.dhall > .github/workflows/ci.yaml
  ```
  