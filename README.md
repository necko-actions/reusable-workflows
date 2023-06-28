# github-workflows

Central place of all reusable workflows.

# Available workflows

| Tittle                                                            | Description                                                                                                                                                                 | Example                                                        |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| [Pull Request Name Lint](.github/workflows/pull-request-lint.yml) | Validate pull request title with conventional commit                                                                                                                        | [.github/workflows/pr-lint.yml](.github/workflows/pr-lint.yml) |
| [Release Please](.github/workflows/release-please.yml)            | Use [release please](https://github.com/google-github-actions/release-please-action) with and automatically tag with the major version (e.g v1) on he latest v1.X.X release | [.github/workflows/release.yml](.github/workflows/release.yml) |
| [Rome](.github/workflows/rome.yml)                                | Run `rome ci .` with the rome version specified on `package.json` and `yarn.lock`                                                                                           | [.github/workflows/rome-ci.yml](.github/workflows/rome-ci.yml) |
| [Check Directory](.github/workflows/check-directory.yml)          | Checks if the specified folder has any difference in git after running `yarn build`                                                                                         | [examples/check-directory.yml](examples/check-directory.yml)   |
