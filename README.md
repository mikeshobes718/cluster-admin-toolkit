# Cluster Admin Toolkit

[![CI](https://github.com/mikeshobes718/cluster-admin-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/cluster-admin-toolkit/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

SRE toolkit for Kubernetes day-2 operations: node/deployment views, rollout status, logs/events, health snapshots, and cordon/drain + restart workflows.

## Features
- Node and deployment inventory with health summaries
- Rollout status and restart workflows
- Tail logs and fetch related events for quick triage
- Cordon/drain helpers with safety checks

## Quickstart
```bash
# Coming soon: CLI entrypoint
python -m cluster_admin_toolkit --help
```

## Architecture
- CLI wrappers around kubectl with sane defaults
- Read-only by default; privileged actions have confirmations

## Roadmap
- Pod disruption budget helpers
- Risk-aware drain with surge limits
- Multi-cluster context support

## License
MIT
