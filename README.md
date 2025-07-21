# github-actions

[`LICENSE`](./LICENSE.md) | [`TODO`s](./TODO.md)

[![[C]ontinuous [I]ntegration](https://github.com/percebus/github-actions/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/github-actions/actions/workflows/always.yml) [![Pull Request](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml/badge.svg?event=pull_request)](https://github.com/percebus/github-actions/actions/workflows/pull_request.yml)

GitHub re-usable Actions &amp; Workflows

## Repositories

### Common

| Name                                                        | semantic-release |
| ----------------------------------------------------------- | ---------------- |
| [common](https://github.com/percebus/github-actions-common) | ❌               |
| [percebus/commons](https://github.com/percebus/commons)     | ❌               |

### Node.js

| Name                                                    | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ------------------------------------------------------- | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [node](https://github.com/percebus/github-actions-node) | ✅     | N/A               | ✅           | ✅         | ❌               |
| [npm](https://github.com/percebus/github-actions-npm)   | ❌     | ✅                | ✅           | ❌         | ❌               |
| [nvm](https://github.com/percebus/github-actions-nvm)   | ❌     | N/A               | ⚠️           | ✅         | ❌               |
| [yarn](https://github.com/percebus/github-actions-yarn) | ❌     | ✅                | ✅           | ❌         | ❌               |

### Python

| Name                                                        | CodeQL | dependency-review | pull_request | semantic-release |
| ----------------------------------------------------------- | ------ | ----------------- | ------------ | ---------------- |
| [python](https://github.com/percebus/github-actions-python) | ✅     | N/A               | ✅           | ❌               |
| [pip](https://github.com/percebus/github-actions-pip)       | ❌     | ❔                | ❌           | ❌               |
| [pipx](https://github.com/percebus/github-actions-pipx)     | ❌     | ❌                | ❌           | ❌               |
| [poetry](https://github.com/percebus/github-actions-poetry) | ❌     | N/A               | ❌           | ❌               |
| [uv](https://github.com/percebus/github-actions-uv)         | ❌     | N/A               | ❌           | ❌               |

### Containerization

| Name                                                                            | naming | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ------------------------------------------------------------------------------- | ------ | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [containerization](https://github.com/percebus/github-actions-containerization) | ✅     | ❌     | ❔                | ❌           | ❌         | ❌               |
| [docker](https://github.com/percebus/github-actions-docker)                     | ❌     | ❌     | ❔                | ❌           | ❌         | ❌               |

### Testing

| Name                                                          | CodeQL | dependency-review | pull_request | Trigger 1x | semantic-release |
| ------------------------------------------------------------- | ------ | ----------------- | ------------ | ---------- | ---------------- |
| [testing](https://github.com/percebus/github-actions-testing) | ❌     | N/A               | ✅           | ❌         | ❌               |
