<p align="center">
  <img src="assets/zabforge-banner.svg" alt="zabforge — Zabbix monitoring, forged as code" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-work%20in%20progress-FF6A1A" alt="Status: work in progress">
  <img src="https://img.shields.io/badge/license-MIT-4A5361" alt="License: MIT">
</p>

**zabforge** turns Zabbix monitoring into something you can version, review and rebuild from scratch: a reproducible Docker lab, configuration as code, and detection of log sources that silently stop sending data.

## The problem

- Templates, macros and hosts change through the UI with no history.
- Environments drift apart and nobody notices until something breaks.
- A log source stops sending data, and the silence goes unalerted.

## Roadmap

- [ ] **Lab** — Zabbix Server, PostgreSQL and the web frontend behind Nginx with TLS, started with a single command
- [ ] **Remote sites** — two proxies on isolated networks with PSK encryption, plus a network troubleshooting guide
- [ ] **Config as code** — Python CLI to export, import and diff templates, macros and hosts as YAML, validated in CI
- [ ] **Silent source detection** — LLD template that alerts when a log source goes quiet, with a synthetic data generator

## Stack

Zabbix · Docker Compose · PostgreSQL · Nginx · Python · GitHub Actions

## Getting started

Coming soon.

## Disclaimer

This is an independent learning project, not affiliated with or endorsed by Zabbix SIA. All data is synthetic.

## License

[MIT](LICENSE)
