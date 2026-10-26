# Cribl (cribl)

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

Cribl is an observability pipeline company providing a suite of products for collecting, processing, routing, searching, and storing telemetry data at scale. Cribl's developer platform offers REST APIs across Stream, Edge, Search, Lake, and the As Code product line, exposing programmatic control over data pipelines, edge agents, federated search jobs, lake datasets, and infrastructure-as-code configuration management. The Cribl Cloud API acts as a centrally managed control plane across all deployments and authenticates with OAuth 2.0 client credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Configuration
- Data Lake
- Data Pipelines
- Data Routing
- Edge Computing
- Infrastructure as Code
- Observability
- Search
- Security Data
- Stream Processing
- Telemetry

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-05-19

## APIs

### Cribl Cloud API

The Cribl Cloud API is a RESTful control plane API for programmatically configuring and managing Cribl resources across Stream, Edge, Search, and Lake deployments. It allows developers to retrieve and manage data, automate repetitive manual processes, and integrate with third-party applications. The API uses OAuth 2.0 client credentials and follows a resource-based structure where each endpoint corresponds to a specific Cribl resource or collection.

- **Human URL:** [https://docs.cribl.io/api-reference/](https://docs.cribl.io/api-reference/)
- **Base URL:** `https://api.cribl.cloud`

#### Tags

- Cloud
- Configuration
- Control Plane
- Data Pipelines
- Management
- Observability

#### Properties

- [Documentation](https://docs.cribl.io/api-reference/)
- [OpenAPI](openapi/cribl-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-cloud-api-rules.yml)
- [Capabilities](capabilities/cribl-cloud-api-capabilities.yml)

### Cribl Stream API

The Cribl Stream API provides programmatic access to Cribl Stream, an observability pipeline platform that processes and routes telemetry data in real time. Through the API, developers can manage pipelines, routes, sources, destinations, and worker groups. It enables automation of data collection, transformation, and routing workflows.

- **Human URL:** [https://docs.cribl.io/stream/](https://docs.cribl.io/stream/)
- **Base URL:** `https://api.example.com`

#### Tags

- Data Pipelines
- Observability
- Routing
- Stream Processing
- Telemetry

#### Properties

- [Documentation](https://docs.cribl.io/stream/)
- [OpenAPI](openapi/cribl-stream-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-stream-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-stream-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-stream-api-rules.yml)
- [Capabilities](capabilities/cribl-stream-api-capabilities.yml)

### Cribl Edge API

The Cribl Edge API provides programmatic access to Cribl Edge, which extends Stream capabilities to the network edge by deploying lightweight agents on endpoints. The API allows developers to manage edge fleets, configure data collection from endpoints, and control data processing closer to the source.

- **Human URL:** [https://docs.cribl.io/edge/](https://docs.cribl.io/edge/)
- **Base URL:** `https://api.example.com`

#### Tags

- Agents
- Data Collection
- Edge Computing
- Observability
- Telemetry

#### Properties

- [Documentation](https://docs.cribl.io/edge/)
- [OpenAPI](openapi/cribl-edge-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-edge-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-edge-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-edge-api-rules.yml)
- [Capabilities](capabilities/cribl-edge-api-capabilities.yml)

### Cribl Search API

The Cribl Search API provides programmatic access to Cribl Search, a tool for exploring and querying both live and stored observability data in real time. Developers can use the API to execute search queries, retrieve results, and integrate search capabilities into their own applications and workflows.

- **Human URL:** [https://docs.cribl.io/search/](https://docs.cribl.io/search/)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Data Exploration
- Federated Search
- Observability
- Querying

#### Properties

- [Documentation](https://docs.cribl.io/search/)
- [OpenAPI](openapi/cribl-search-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-search-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-search-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-search-api-rules.yml)
- [Capabilities](capabilities/cribl-search-api-capabilities.yml)

### Cribl Lake API

The Cribl Lake API provides programmatic access to Cribl Lake, a data lake solution purpose-built for observability and security data. The API enables developers to manage data storage, retention policies, and access controls for large volumes of telemetry data in open formats.

- **Human URL:** [https://docs.cribl.io/lake/](https://docs.cribl.io/lake/)
- **Base URL:** `https://api.example.com`

#### Tags

- Analytics
- Data Lake
- Data Management
- Observability
- Storage

#### Properties

- [Documentation](https://docs.cribl.io/lake/)
- [OpenAPI](openapi/cribl-lake-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-lake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-lake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-lake-api-rules.yml)
- [Capabilities](capabilities/cribl-lake-api-capabilities.yml)

### Cribl As Code API

The Cribl As Code API enables developers to manage Cribl configurations programmatically using infrastructure-as-code principles. It supports exporting and importing configurations across deployments, enabling version control, CI/CD integration, and reproducible infrastructure management. Developers can use the API alongside SDKs for Python, Go, and TypeScript or through Terraform providers.

- **Human URL:** [https://docs.cribl.io/cribl-as-code/api/](https://docs.cribl.io/cribl-as-code/api/)
- **Base URL:** `https://gateway.cribl.cloud`

#### Tags

- Automation
- Configuration
- DevOps
- Infrastructure as Code
- Version Control

#### Properties

- [Documentation](https://docs.cribl.io/cribl-as-code/api/)
- [OpenAPI](openapi/cribl-as-code-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cribl-as-code-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cribl-as-code-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/cribl-as-code-api-rules.yml)
- [Capabilities](capabilities/cribl-as-code-api-capabilities.yml)

## Common Properties

- [GitHub Organization](https://github.com/criblio)
- [LinkedIn](https://www.linkedin.com/company/cribl)
- [JSON-LD](json-ld/cribl-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cribl-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cribl-route-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cribl-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cribl-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cribl-worker-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://cribl.io/)
- [Documentation](https://docs.cribl.io/)
- [Portal](https://docs.cribl.io/)
- [Login](https://login.cribl.cloud/)
- [Blog](https://cribl.io/blog/)
- [Privacy Policy](https://cribl.io/privacy-policy/)
- [Terms of Service](https://cribl.io/terms-of-service/)
- [Integrations](https://cribl.io/integrations/)
- [L L Ms Txt](https://docs.cribl.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
