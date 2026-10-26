# OpenStatus (openstatus)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
