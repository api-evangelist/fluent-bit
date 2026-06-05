# Fluent Bit (fluent-bit)

Fluent Bit is an open source lightweight log processor and forwarder for collecting, parsing, and routing logs and metrics at scale. It exposes an embedded HTTP monitoring server with v1 and v2 endpoints for build info, uptime, internal metrics (JSON, Prometheus, cmetrics), storage stats, health checks, and hot reload.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fluent-bit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Logging
- Observability
- Metrics
- Open Source

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Fluent Bit Monitoring HTTP API

Fluent Bit's embedded HTTP server (default port 2020) exposes endpoints for build information, uptime, internal plugin metrics in JSON, Prometheus, and cmetrics formats, storage layer statistics, health checks, and hot reload.

- **Human URL:** [https://docs.fluentbit.io/manual/administration/monitoring](https://docs.fluentbit.io/manual/administration/monitoring)
- **Base URL:** `http://127.0.0.1:2020`

#### Tags

- Logging
- Observability
- Metrics
- Health Check
- Prometheus

#### Properties

- [Documentation](https://docs.fluentbit.io/manual/administration/monitoring)
- [OpenAPI](openapi/fluent-bit-monitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fluent-bit-monitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fluent-bit-monitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://fluentbit.io)
- [Documentation](https://docs.fluentbit.io)
- [GitHub Repository](https://github.com/fluent/fluent-bit)
- [Slack](https://launchpass.com/fluent-all)
- [Community](https://fluentbit.io/community/)
- [Integrations](https://fluentbit.io/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
