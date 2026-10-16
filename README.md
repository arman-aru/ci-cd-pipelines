# ci-cd-pipelines

> Production-grade CI/CD with GitHub Actions — lint, test, multi-stage Docker builds, Trivy scanning, GHCR publishing and automated releases for my Python and Go services.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

Reusable GitHub Actions pipelines for Python and Go services: linting, tests, small and secure Docker images, vulnerability scanning, publishing to GitHub Container Registry and automated releases.

## Features

- Reusable workflows for Python and Go (lint + test)
- Multi-stage Dockerfiles producing small, non-root images
- Build caching for fast pipelines
- Trivy vulnerability scanning that blocks critical issues
- Image publishing to GitHub Container Registry
- Automated versioning, changelogs and dependency updates

## Tech stack

GitHub Actions · Docker / Buildx · Trivy · GHCR · Renovate · release-please

## License

[MIT](LICENSE) © Arman Salek
