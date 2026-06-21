# OpenStatus (openstatus)

OpenStatus is an open-source synthetic monitoring and status-page platform. It runs HTTP, TCP, and DNS uptime checks from 28 global regions, publishes hosted and self-hostable status pages, and manages incidents and status reports. The OpenStatus REST API at https://api.openstatus.dev/v1 lets teams programmatically manage monitors, status pages, status reports, incidents, and on-demand checks. The platform is free to self-host (AGPL-3.0) and also available as a managed cloud service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openstatus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openstatus/refs/heads/main/apis.yml)

## Tags

- Monitoring
- Synthetic Monitoring
- Uptime
- Status Pages
- Incidents
- Open Source
- Observability

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### OpenStatus Monitors

Create, read, update, and delete HTTP, TCP, and DNS uptime monitors running across 28 global regions, with periodicity, assertions, retries, timeouts, and OpenTelemetry export. Includes monitor summaries, results, and on-demand runs.

- **Human URL:** [https://www.openstatus.dev/docs/api-reference/v1/monitor](https://www.openstatus.dev/docs/api-reference/v1/monitor)
- **Base URL:** `https://api.openstatus.dev/v1`

#### Tags

- Monitors
- Uptime
- HTTP
- TCP
- DNS

#### Properties

- [Documentation](https://www.openstatus.dev/docs/api-reference/v1/monitor)
- [API Reference](https://www.openstatus.dev/docs/api-reference/v1/monitor)
- [OpenAPI](openapi/openstatus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstatus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstatus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStatus Incidents

List, retrieve, acknowledge, and resolve incidents automatically opened when a monitor fails its assertions, tying detected downtime back to the originating monitor.

- **Human URL:** [https://www.openstatus.dev/docs/api-reference/v1/incident](https://www.openstatus.dev/docs/api-reference/v1/incident)
- **Base URL:** `https://api.openstatus.dev/v1`

#### Tags

- Incidents
- Alerts
- Acknowledgement

#### Properties

- [Documentation](https://www.openstatus.dev/docs/api-reference/v1/incident)
- [API Reference](https://www.openstatus.dev/docs/api-reference/v1/incident)
- [OpenAPI](openapi/openstatus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstatus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstatus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStatus Status Reports

Create and manage status reports and their timeline of updates (investigating, identified, monitoring, resolved) that publish incident communications to a status page and its affected monitors.

- **Human URL:** [https://www.openstatus.dev/docs/api-reference/v1/status-report](https://www.openstatus.dev/docs/api-reference/v1/status-report)
- **Base URL:** `https://api.openstatus.dev/v1`

#### Tags

- Status Reports
- Updates
- Communication

#### Properties

- [Documentation](https://www.openstatus.dev/docs/api-reference/v1/status-report)
- [API Reference](https://www.openstatus.dev/docs/api-reference/v1/status-report)
- [OpenAPI](openapi/openstatus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstatus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstatus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStatus Status Pages

Create and manage public status pages with custom domains, access controls (public, password, email-domain), grouped monitor components, and email subscribers.

- **Human URL:** [https://www.openstatus.dev/docs/api-reference/v1/page](https://www.openstatus.dev/docs/api-reference/v1/page)
- **Base URL:** `https://api.openstatus.dev/v1`

#### Tags

- Status Pages
- Subscribers
- Public

#### Properties

- [Documentation](https://www.openstatus.dev/docs/api-reference/v1/page)
- [API Reference](https://www.openstatus.dev/docs/api-reference/v1/page)
- [OpenAPI](openapi/openstatus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstatus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstatus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStatus Checks

Run on-demand synthetic checks against a URL from one or more regions without creating a persistent monitor, returning per-region latency and assertion results.

- **Human URL:** [https://www.openstatus.dev/docs/api-reference/v1/check](https://www.openstatus.dev/docs/api-reference/v1/check)
- **Base URL:** `https://api.openstatus.dev/v1`

#### Tags

- Checks
- On-Demand
- Synthetic

#### Properties

- [Documentation](https://www.openstatus.dev/docs/api-reference/v1/check)
- [API Reference](https://www.openstatus.dev/docs/api-reference/v1/check)
- [OpenAPI](openapi/openstatus-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstatus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstatus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/openstatusHQ)
- [LinkedIn](https://www.linkedin.com/company/openstatushq)
- [Website](https://www.openstatus.dev)
- [Documentation](https://www.openstatus.dev/docs)
- [Plans](plans/openstatus-plans-pricing.yml)
- [Rate Limits](rate-limits/openstatus-rate-limits.yml)
- [Fin Ops](finops/openstatus-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
