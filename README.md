# Cribl (cribl)

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
