# github-actions

[![[C]ontinuous [I]ntegration](https://github.com/percebus/github-actions/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/github-actions/actions/workflows/always.yml) [![Pull Request](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml/badge.svg?event=pull_request)](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml)

[`LICENSE`](./LICENSE.md) | [`TODO`s](./TODO.md)

GitHub re-usable Actions &amp; Workflows

## Repositories

### Compliance

| Name                                                                                 | `CodeQL` | `dependency-review` | `semantic-release` | comments       |
| ------------------------------------------------------------------------------------ | -------- | ------------------- | ------------------ | -------------- |
| [`github-actions-compliance`](https://github.com/percebus/github-actions-compliance) | ✅       | ✅                  | ❌                 | checkout, etc. |

### Commons

| Name                                                                         | `CodeQL` | `dependency-review` | `semantic-release` | comments                        |
| ---------------------------------------------------------------------------- | -------- | ------------------- | ------------------ | ------------------------------- |
| [`github-actions-common`](https://github.com/percebus/github-actions-common) | ✅       | ⚠️`DEPRECATED`      | ❌                 | checkout, etc.                  |
| [commons](https://github.com/percebus/commons)                               | ✅       | N/A                 | ❌                 | `scripts/`, `references/`, etc. |

### Node.js

| Name                                                      | `CodeQL` | `dependency-review` | `semantic-release` |
| --------------------------------------------------------- | -------- | ------------------- | ------------------ |
| [`node`](https://github.com/percebus/github-actions-node) | ⚠️       | N/A                 | ❌                 |
| [`npm`](https://github.com/percebus/github-actions-npm)   | ✅       | ✅                  | ❌                 |
| [`nvm`](https://github.com/percebus/github-actions-nvm)   | ❌       | N/A                 | ❌                 |
| [`yarn`](https://github.com/percebus/github-actions-yarn) | ✅       | ✅                  | ❌                 |

### Python

| Name                                                          | `CodeQL` | `dependency-review` | `semantic-release` |
| ------------------------------------------------------------- | -------- | ------------------- | ------------------ |
| [`python`](https://github.com/percebus/github-actions-python) | ⚠️       | N/A                 | ❌                 |
| [`pip`](https://github.com/percebus/github-actions-pip)       | ⚠️       | ❔                  | ❌                 |
| [`pipx`](https://github.com/percebus/github-actions-pipx)     | ✅       | ✅                  | ❌                 |
| [`poetry`](https://github.com/percebus/github-actions-poetry) | ⚠️       | N/A                 | ❌                 |
| [`uv`](https://github.com/percebus/github-actions-uv)         | ⚠️       | N/A                 | ❌                 |

### Containerization

| Name                                                                            | `CodeQL` | `dependency-review` | `semantic-release` |
| ------------------------------------------------------------------------------- | -------- | ------------------- | ------------------ |
| [containerization](https://github.com/percebus/github-actions-containerization) | ⚠️       | ❔                  | ❌                 |
| [`docker`](https://github.com/percebus/github-actions-docker)                   | ⚠️       | ❔                  | ❌                 |

### Testing

| Name                                                          | `CodeQL` | `semantic-release` |
| ------------------------------------------------------------- | -------- | ------------------ |
| [testing](https://github.com/percebus/github-actions-testing) | ❌       | ❌                 |
