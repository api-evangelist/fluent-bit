# Fluent Bit (fluent-bit)

Fluent Bit is an open source lightweight log processor and forwarder for collecting, parsing, and routing logs and metrics at scale. It exposes an embedded HTTP monitoring server with v1 and v2 endpoints for build info, uptime, internal metrics (JSON, Prometheus, cmetrics), storage stats, health checks, and hot reload.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Logging, Observability, Metrics, Open Source

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-28

## APIs

### Fluent Bit Monitoring HTTP API

Fluent Bit's embedded HTTP server (default port 2020, enabled with `service.http_server: on`) exposes endpoints for build information, uptime, internal plugin metrics in JSON, Prometheus, and cmetrics formats, storage layer statistics, health checks, and hot reload.

**Human URL:** [https://docs.fluentbit.io/manual/administration/monitoring](https://docs.fluentbit.io/manual/administration/monitoring)

**Base URL:** `http://127.0.0.1:2020`

#### Tags

- Logging, Observability, Metrics, Health Check, Prometheus

#### Properties

- [Documentation](https://docs.fluentbit.io/manual/administration/monitoring)
- [OpenAPI](openapi/fluent-bit-monitoring-openapi.yml)

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://fluentbit.io |
| Documentation | https://docs.fluentbit.io |
| GitHub | https://github.com/fluent/fluent-bit |
| Slack | https://launchpass.com/fluent-all |
| Community | https://fluentbit.io/community/ |

## Maintainers

- **Kin Lane** - kin@apievangelist.com
