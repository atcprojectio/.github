# Active Traffic Control (ATC)

ATC automates Consul `service-resolver` configuration. It watches the Consul catalog and publishes failover and redirect rules for services that opt in with tags, so traffic moves to another datacenter without hand-written resolver entries.

## Repositories

| Repository | What it is |
|---|---|
| [atc](https://github.com/atcprojectio/atc) | The ATC daemon: a Go service with an embedded dashboard, REST API and MCP server, plus a Helm chart and Nomad job. |
| [atc-demo](https://github.com/atcprojectio/atc-demo) | A local multi-datacenter Consul sandbox with an observability stack (Grafana, Loki, Tempo, Prometheus) and step-by-step scenarios. |
| [homebrew-tap](https://github.com/atcprojectio/homebrew-tap) | The Homebrew tap for installing ATC on macOS. |

## Get started

```bash
brew install --cask atcprojectio/tap/atc
```

Documentation: **[atc-project.io](https://atc-project.io)**
