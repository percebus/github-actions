# github-actions

[`TODO`s](./TODO.md)

[![[C]ontinuous [I]ntegration](https://github.com/percebus/github-actions/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/github-actions/actions/workflows/always.yml) [![Pull Request](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml/badge.svg?event=pull_request)](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml)

GitHub re-usable Actions &amp; Workflows

## Repositories

### Common

| Name                                                        | semantic-release |
| ----------------------------------------------------------- | ---------------- |
| [common](https://github.com/percebus/github-actions-common) | ❌               |

### Node.js

| Name                                                    | naming | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ------------------------------------------------------- | ------ | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [node](https://github.com/percebus/github-actions-node) | ✅     | ❌     | N/A               | ⚠️           | ✅         | ❌               |
| [npm](https://github.com/percebus/github-actions-npm)   | ❌     | ❌     | ✅                | ✅           | ❌         | ❌               |
| [nvm](https://github.com/percebus/github-actions-nvm)   | ✅     | ❌     | N/A               | ⚠️           | ✅         | ❌               |
| [yarn](https://github.com/percebus/github-actions-yarn) | ✅     | ❌     | ✅                | ✅           | ❌         | ❌               |

### Python

| Name                                                        | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ----------------------------------------------------------- | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [python](https://github.com/percebus/github-actions-python) | ❌     | N/A               | ❌           | ❌         | ❌               |
| [pip](https://github.com/percebus/github-actions-pip)       | ❌     | ❔                | ❌           | ✅         | ❌               |
| [pipx](https://github.com/percebus/github-actions-pipx)     | ❌     | ❌                | ❌           | ✅         | ❌               |
| [poetry](https://github.com/percebus/github-actions-poetry) | ❌     | N/A               | ❌           | ✅         | ❌               |
| [uv](https://github.com/percebus/github-actions-uv)         | ❌     | N/A               | ❌           | ✅         | ❌               |

### Containerization

| Name                                                                            | naming | CodeQL | dependency-review | pull_request | Trigger 1x | Tests | semantic-release |
| ------------------------------------------------------------------------------- | ------ | ------ | ----------------- | ------------ | ---------- | ----- | ---------------- |
| [containerization](https://github.com/percebus/github-actions-containerization) | ✅     | ❌     | ❔                | ❌           | ❌         | ✅    | ❌               |
| [docker](https://github.com/percebus/github-actions-docker)                     | ❌     | ❌     | ❔                | ❌           | ❌         | ✅    | ❌               |

### Testing

| Name                                                          | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ------------------------------------------------------------- | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [testing](https://github.com/percebus/github-actions-testing) | ❌     | N/A               | ✅           | ❌         | ❌               |

### Related

- [percebus/commons](https://github.com/percebus/commons): Common scripts and tools for DevOps.
