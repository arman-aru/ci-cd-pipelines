# ci-cd-pipelines

> Production-grade CI/CD with GitHub Actions — lint, test, multi-stage Docker builds, Trivy scanning, GHCR publishing and automated releases for my Python and Go services.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-DevOps-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 2 — DevOps**). I build in the open — follow the commits and the roadmap below.

## Why this project

Turn the Python and Go services from Phase 1 into properly shipped software, and keep the pipelines reusable.

## What I'm learning

- Reusable GitHub Actions workflows and composite actions
- Small, secure multi-stage Docker images (non-root, distroless)
- Build caching and test matrices
- Container scanning with Trivy and dependency updates
- Semantic versioning and automated releases

## Planned stack

GitHub Actions · Docker / Buildx · Trivy · GHCR · Renovate · release-please

## Roadmap

- [ ] Reusable workflow: lint + test for Python
- [ ] Reusable workflow: lint + test for Go
- [ ] Multi-stage Dockerfiles for `lt-vocab-api` and `parcel-locker-api`
- [ ] Build and push to GHCR with caching
- [ ] Trivy scan that fails on critical issues
- [ ] Automated releases and changelogs
- [ ] Renovate for dependency updates
- [ ] README: pipeline diagram + before/after image sizes

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | **ci-cd-pipelines** (this repo) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
