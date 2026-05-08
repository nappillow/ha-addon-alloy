# Changelog

## Unreleased

### Added
- `tls_ca_file` option for verifying HTTPS Loki endpoints signed by an internal/private CA, so users with self-hosted Loki behind cert-manager / a private root CA don't have to fall back to `insecure_skip_verify`.

## 1.0.0 - 2026-02-21

### Added
- Initial release
- Grafana Alloy v1.13.1
- Systemd journal log shipping to Loki
- Journal field relabeling (unit, hostname, syslog_identifier, transport, container_name, level)
- Debug UI on port 12345
- Configurable Loki URL, log level, and additional config
- Watchdog health check via Alloy's `/-/ready` endpoint
- Support for amd64 and aarch64 architectures
