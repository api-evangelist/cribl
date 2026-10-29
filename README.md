# Cribl

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

**Areas:** Configuration · Data Lake · Data Pipeline · Data Routing · Edge Computing · Infrastructure as Code · Observability · Search · Security Data · Stream Processing · Telemetry

## Cribl on APIs.io

Everything profiled for Cribl is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cribl/](https://apis.io/providers/cribl/)** — or go straight to one of the APIs or properties below.

### APIs (32)

- [Cribl API Credentials API](https://apis.io/apis/cribl/cribl-api-credentials-api/) — Manage API credentials used for OAuth 2.0 client credentials authentication. Credentials consist of a client ID and client secret used to obtain bearer…
- [Cribl Authentication API](https://apis.io/apis/cribl/cribl-authentication-api/) — Obtain and manage authentication tokens for API access.
- [Cribl Collectors API](https://apis.io/apis/cribl/cribl-collectors-api/) — Manage scheduled and on-demand data collection jobs from REST APIs, databases, scripts, and other sources.
- [Cribl Database Connections API](https://apis.io/apis/cribl/cribl-database-connections-api/) — Configure and manage database connections used by collectors and lookup functions.
- [Cribl Datasets API](https://apis.io/apis/cribl/cribl-datasets-api/) — Manage Cribl Lake datasets that define storage buckets for observability and security data in open formats.
- [Cribl Destinations API](https://apis.io/apis/cribl/cribl-destinations-api/) — Manage data output destinations where processed events are sent, including Splunk, S3, Elasticsearch, and webhook endpoints.
- [Cribl Edge Destinations API](https://apis.io/apis/cribl/cribl-edge-destinations-api/) — Manage data output destinations for edge nodes including forwarding to Stream workers, cloud storage, and analytics platforms.
- [Cribl Edge Fleets API](https://apis.io/apis/cribl/cribl-edge-fleets-api/) — Manage edge fleets that organize groups of edge nodes deployed on endpoints for local data collection and processing.
- [Cribl Edge Nodes API](https://apis.io/apis/cribl/cribl-edge-nodes-api/) — Monitor and manage individual edge nodes deployed on endpoints including their status, version, and resource utilization.
- [Cribl Edge Pipelines API](https://apis.io/apis/cribl/cribl-edge-pipelines-api/) — Manage processing pipelines running on edge nodes for local data transformation and filtering before forwarding.
- [Cribl Edge Routes API](https://apis.io/apis/cribl/cribl-edge-routes-api/) — Manage routes on edge nodes for directing collected data to appropriate pipelines and destinations.
- [Cribl Edge Sources API](https://apis.io/apis/cribl/cribl-edge-sources-api/) — Manage data input sources on edge nodes including file monitors, Windows Event Log, system metrics, AppScope, and other local collection methods.
- [Cribl Functions API](https://apis.io/apis/cribl/cribl-functions-api/) — Retrieve available processing functions that can be used within pipelines for data transformation.
- [Cribl Groups API](https://apis.io/apis/cribl/cribl-groups-api/) — Manage Worker Groups and Edge Fleets, which organize and deploy configurations to sets of worker nodes or edge agents.
- [Cribl Health API](https://apis.io/apis/cribl/cribl-health-api/) — Check the health and availability of the Cribl Cloud management plane services.
- [Cribl Jobs API](https://apis.io/apis/cribl/cribl-jobs-api/) — Monitor and manage running and completed collection and processing jobs.
- [Cribl Lake Datasets API](https://apis.io/apis/cribl/cribl-lake-datasets-api/) — Manage Cribl Lake datasets for storing and organizing observability data in open formats.
- [Cribl Lookups API](https://apis.io/apis/cribl/cribl-lookups-api/) — Manage lookup files and tables used for data enrichment in pipelines.
- [Cribl Nodes API](https://apis.io/apis/cribl/cribl-nodes-api/) — Monitor and manage individual worker nodes and edge nodes within groups and fleets.
- [Cribl Notifications API](https://apis.io/apis/cribl/cribl-notifications-api/) — Configure notification rules and targets for alerting on data flow anomalies and system events.
- [Cribl Packs API](https://apis.io/apis/cribl/cribl-packs-api/) — Install, manage, and distribute reusable configuration packs containing pipelines, routes, and other resources.
- [Cribl Pipelines API](https://apis.io/apis/cribl/cribl-pipelines-api/) — Manage processing pipelines that contain ordered sequences of functions for transforming, filtering, and enriching events.
- [Cribl Retention API](https://apis.io/apis/cribl/cribl-retention-api/) — Configure data retention policies that control how long data is stored in Lake datasets before automatic cleanup.
- [Cribl Routes API](https://apis.io/apis/cribl/cribl-routes-api/) — Manage routes that filter and direct incoming data across pipelines and destinations using filter expressions.
- [Cribl Saved Searches API](https://apis.io/apis/cribl/cribl-saved-searches-api/) — Create and manage saved search queries for reuse and sharing across teams and workflows.
- [Cribl Search Jobs API](https://apis.io/apis/cribl/cribl-search-jobs-api/) — Execute and manage search queries across live and stored observability data with support for federated search across multiple data sources.
- [Cribl Search Notifications API](https://apis.io/apis/cribl/cribl-search-notifications-api/) — Configure notification rules that trigger alerts based on search results using webhook and other notification targets.
- [Cribl Sources API](https://apis.io/apis/cribl/cribl-sources-api/) — Manage data input sources that collect events from various systems including Syslog, HTTP, Kafka, Splunk, and other protocols.
- [Cribl System API](https://apis.io/apis/cribl/cribl-system-api/) — Access system-level settings including Git configuration, licensing, and global preferences.
- [Cribl Versioning API](https://apis.io/apis/cribl/cribl-versioning-api/) — Manage configuration versions, commits, and deployment history.
- [Cribl Worker Groups API](https://apis.io/apis/cribl/cribl-worker-groups-api/) — Manage Stream worker groups that organize worker nodes and deploy shared pipeline configurations across clusters.
- [Cribl Workspaces API](https://apis.io/apis/cribl/cribl-workspaces-api/) — Manage Cribl Cloud workspaces which are unique VPC containers each isolating an instance of the Cribl Product Suite including Stream, Edge, Search, and Lake.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cribl Agentic Access](https://apis.io/agentic-access/cribl/cribl-agentic-access/)

#### JSON Schema (38)

The data models the API reads and writes.

- [ApiCredential](https://apis.io/schemas/cribl/cribl-apicredential/)
- [ApiCredentialCreate](https://apis.io/schemas/cribl/cribl-apicredentialcreate/)
- [ApiCredentialUpdate](https://apis.io/schemas/cribl/cribl-apicredentialupdate/)
- [ApiCredentialWithSecret](https://apis.io/schemas/cribl/cribl-apicredentialwithsecret/)
- [Collector](https://apis.io/schemas/cribl/cribl-collector/)
- [DatabaseConnection](https://apis.io/schemas/cribl/cribl-databaseconnection/)
- [Cribl Destination](https://apis.io/schemas/cribl/cribl-destination/)
- [DestinationStatus](https://apis.io/schemas/cribl/cribl-destinationstatus/)
- [EdgeDestination](https://apis.io/schemas/cribl/cribl-edgedestination/)
- [EdgeFleet](https://apis.io/schemas/cribl/cribl-edgefleet/)
- [EdgeNode](https://apis.io/schemas/cribl/cribl-edgenode/)
- [EdgePipeline](https://apis.io/schemas/cribl/cribl-edgepipeline/)
- [EdgeRoute](https://apis.io/schemas/cribl/cribl-edgeroute/)
- [EdgeSource](https://apis.io/schemas/cribl/cribl-edgesource/)
- [Function](https://apis.io/schemas/cribl/cribl-function/)
- [GitSettings](https://apis.io/schemas/cribl/cribl-gitsettings/)
- [Group](https://apis.io/schemas/cribl/cribl-group/)
- [HealthStatus](https://apis.io/schemas/cribl/cribl-healthstatus/)
- [Job](https://apis.io/schemas/cribl/cribl-job/)
- [LakeDataset](https://apis.io/schemas/cribl/cribl-lakedataset/)
- [Lookup](https://apis.io/schemas/cribl/cribl-lookup/)
- [Node](https://apis.io/schemas/cribl/cribl-node/)
- [Notification](https://apis.io/schemas/cribl/cribl-notification/)
- [Pack](https://apis.io/schemas/cribl/cribl-pack/)
- [Cribl Pipeline](https://apis.io/schemas/cribl/cribl-pipeline/)
- …and 13 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Cribl Structure](https://apis.io/json-structure/cribl/cribl-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cribl Context](https://apis.io/jsonld/cribl/cribl-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cribl Domain Vocabulary](https://apis.io/vocabularies/cribl/cribl-vocabulary/)

#### Collections (38)

Postman and Open Collection request collections.

- [Cribl As Code API Credentials API](https://apis.io/collections/cribl/open-cribl-api-credentials-api/)
- [Cribl As Code API](https://apis.io/collections/cribl/open-cribl-as-code-api/)
- [Cribl As Code API Credentials Authentication API](https://apis.io/collections/cribl/open-cribl-authentication-api/)
- [Cribl Cloud API](https://apis.io/collections/cribl/open-cribl-cloud-api/)
- [Cribl As Code API Credentials Collectors API](https://apis.io/collections/cribl/open-cribl-collectors-api/)
- [Cribl As Code API Credentials Database Connections API](https://apis.io/collections/cribl/open-cribl-database-connections-api/)
- [Cribl As Code API Credentials Datasets API](https://apis.io/collections/cribl/open-cribl-datasets-api/)
- [Cribl As Code API Credentials Destinations API](https://apis.io/collections/cribl/open-cribl-destinations-api/)
- [Cribl Edge API](https://apis.io/collections/cribl/open-cribl-edge-api/)
- [Cribl As Code API Credentials Edge Destinations API](https://apis.io/collections/cribl/open-cribl-edge-destinations-api/)
- [Cribl As Code API Credentials Edge Fleets API](https://apis.io/collections/cribl/open-cribl-edge-fleets-api/)
- [Cribl As Code API Credentials Edge Nodes API](https://apis.io/collections/cribl/open-cribl-edge-nodes-api/)
- [Cribl As Code API Credentials Edge Pipelines API](https://apis.io/collections/cribl/open-cribl-edge-pipelines-api/)
- [Cribl As Code API Credentials Edge Routes API](https://apis.io/collections/cribl/open-cribl-edge-routes-api/)
- [Cribl As Code API Credentials Edge Sources API](https://apis.io/collections/cribl/open-cribl-edge-sources-api/)
- [Cribl As Code API Credentials Functions API](https://apis.io/collections/cribl/open-cribl-functions-api/)
- [Cribl As Code API Credentials Groups API](https://apis.io/collections/cribl/open-cribl-groups-api/)
- [Cribl As Code API Credentials Health API](https://apis.io/collections/cribl/open-cribl-health-api/)
- [Cribl As Code API Credentials Jobs API](https://apis.io/collections/cribl/open-cribl-jobs-api/)
- [Cribl Lake API](https://apis.io/collections/cribl/open-cribl-lake-api/)
- [Cribl As Code API Credentials Lake Datasets API](https://apis.io/collections/cribl/open-cribl-lake-datasets-api/)
- [Cribl As Code API Credentials Lookups API](https://apis.io/collections/cribl/open-cribl-lookups-api/)
- [Cribl As Code API Credentials Nodes API](https://apis.io/collections/cribl/open-cribl-nodes-api/)
- [Cribl As Code API Credentials Notifications API](https://apis.io/collections/cribl/open-cribl-notifications-api/)
- [Cribl As Code API Credentials Packs API](https://apis.io/collections/cribl/open-cribl-packs-api/)
- …and 13 more published on APIs.io

#### Governance rules (7)

Spectral rulesets for the provider's contracts.

- [Cribl — as code api rules](https://apis.io/rules/cribl/cribl-as-code-api-rules/)
- [Cribl — cloud api rules](https://apis.io/rules/cribl/cribl-cloud-api-rules/)
- [Cribl — edge api rules](https://apis.io/rules/cribl/cribl-edge-api-rules/)
- [Cribl — jsonschema rules](https://apis.io/rules/cribl/cribl-jsonschema-spectral-rules/)
- [Cribl — lake api rules](https://apis.io/rules/cribl/cribl-lake-api-rules/)
- [Cribl — search api rules](https://apis.io/rules/cribl/cribl-search-api-rules/)
- [Cribl — stream api rules](https://apis.io/rules/cribl/cribl-stream-api-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cribl Authentication](https://apis.io/security/cribl/cribl-authentication/)
- [Cribl Domain Security](https://apis.io/security/cribl/cribl-domain-security/)
- [Cribl Vulnerability Disclosure](https://apis.io/security/cribl/cribl-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Cribl Scopes](https://apis.io/scopes/cribl/cribl-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cribl Plans Pricing](https://apis.io/plans/cribl/cribl-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cribl Rate Limits](https://apis.io/rate-limits/cribl/cribl-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cribl Finops](https://apis.io/finops/cribl/cribl-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cribl.io/)
- [Documentation](https://docs.cribl.io/)
- [Pricing](https://cribl.io/pricing/plan/)
- [Blog](https://cribl.io/blog/)
- [Terms of service](https://cribl.io/terms-of-service/)
- [Privacy policy](https://cribl.io/privacy-policy/)
- [GitHub](https://github.com/criblio)

## API Evangelist rating

**Kin Score 50.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 58.7 |
| Contract governance | 13.6 |
| Operational transparency | 21.1 |
| Developer ergonomics | 33.3 |
| Access clarity | 69.7 |

**Agent readiness 20.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cribl/](https://apis.io/providers/cribl/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cribl: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cribl/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
