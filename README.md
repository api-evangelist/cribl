# Cribl (cribl)

Cribl is an observability pipeline company providing a suite of products for collecting, processing, routing, searching, and storing telemetry data at scale. Cribl's developer platform offers REST APIs across Stream, Edge, Search, Lake, and the As Code product line, exposing programmatic control over data pipelines, edge agents, federated search jobs, lake datasets, and infrastructure-as-code configuration management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cribl/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Configuration, Data Lake, Data Pipelines, Data Routing, Edge Computing, Infrastructure as Code, Observability, Search, Security Data, Stream Processing, Telemetry

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-04-28

## APIs

### Cribl Cloud API

RESTful control plane API for managing Cribl resources across Stream, Edge, Search, and Lake deployments using OAuth 2.0 client credentials.

- [Documentation](https://docs.cribl.io/api-reference/)
- [OpenAPI](openapi/cribl-cloud-api-openapi.yml)
- [Rules](rules/cribl-cloud-api-rules.yml)
- [Capabilities](capabilities/cribl-cloud-api-capabilities.yml)

### Cribl Stream API

Programmatic access to Cribl Stream pipelines, routes, sources, destinations, and worker groups for real-time observability data processing.

- [Documentation](https://docs.cribl.io/stream/)
- [OpenAPI](openapi/cribl-stream-api-openapi.yml)
- [Rules](rules/cribl-stream-api-rules.yml)
- [Capabilities](capabilities/cribl-stream-api-capabilities.yml)

### Cribl Edge API

Programmatic access to Cribl Edge fleets, edge nodes, endpoint sources, and edge pipelines for processing data near the source.

- [Documentation](https://docs.cribl.io/edge/)
- [OpenAPI](openapi/cribl-edge-api-openapi.yml)
- [Rules](rules/cribl-edge-api-rules.yml)
- [Capabilities](capabilities/cribl-edge-api-capabilities.yml)

### Cribl Search API

Programmatic federated search across live and stored observability data with search jobs, datasets, and saved searches.

- [Documentation](https://docs.cribl.io/search/)
- [OpenAPI](openapi/cribl-search-api-openapi.yml)
- [Rules](rules/cribl-search-api-rules.yml)
- [Capabilities](capabilities/cribl-search-api-capabilities.yml)

### Cribl Lake API

Programmatic management of Cribl Lake datasets, retention policies, and access policies for observability and security data.

- [Documentation](https://docs.cribl.io/lake/)
- [OpenAPI](openapi/cribl-lake-api-openapi.yml)
- [Rules](rules/cribl-lake-api-rules.yml)
- [Capabilities](capabilities/cribl-lake-api-capabilities.yml)

### Cribl As Code API

Infrastructure-as-code management of Cribl configurations through export, import, and diff operations against the gateway.cribl.cloud control plane.

- [Documentation](https://docs.cribl.io/cribl-as-code/api/)
- [OpenAPI](openapi/cribl-as-code-api-openapi.yml)
- [Rules](rules/cribl-as-code-api-rules.yml)
- [Capabilities](capabilities/cribl-as-code-api-capabilities.yml)

## Common Properties

- [Website](https://cribl.io/)
- [Documentation Portal](https://docs.cribl.io/)
- [Login](https://login.cribl.cloud/)
- [Blog](https://cribl.io/blog/)
- [JSON-LD Context](json-ld/cribl-context.jsonld)
- [Pipeline Schema](json-schema/cribl-pipeline-schema.json)
- [Route Schema](json-schema/cribl-route-schema.json)
- [Source Schema](json-schema/cribl-source-schema.json)
- [Destination Schema](json-schema/cribl-destination-schema.json)
- [Worker Group Schema](json-schema/cribl-worker-group-schema.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
