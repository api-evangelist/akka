# Akka (akka)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of libraries including actors, HTTP, streams, cluster, persistence, and gRPC for building reactive, microservice-based architectures.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Actor Model
- Distributed Systems
- Frameworks
- Java
- Microservices
- Reactive
- Scala

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Akka Management

Akka Management provides a suite of utilities for operating Akka-based distributed systems, including an HTTP management API for cluster management, health checks, and cluster bootstrap. The HTTP API exposes endpoints for liveness probes, readiness probes, cluster member management, and seed node discovery.

- **Human URL:** [https://doc.akka.io/libraries/akka-management/current/](https://doc.akka.io/libraries/akka-management/current/)

#### Tags

- Actor Model
- Cluster Management
- Distributed Systems
- Health Checks

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-management/current/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/openapi/akka-management.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akka-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akka-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akka HTTP

Akka HTTP is a full HTTP stack (client and server-side) built on Akka actors and streams. It provides a routing DSL for building REST and WebSocket services, with built-in JSON marshalling, TLS support, and HTTP/2 capabilities.

- **Human URL:** [https://doc.akka.io/libraries/akka-http/current/](https://doc.akka.io/libraries/akka-http/current/)

#### Tags

- HTTP
- REST API
- Reactive
- Streaming

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-http/current/)
- [Getting Started](https://doc.akka.io/libraries/akka-http/current/introduction.html)
- [Postman Collection](collections/akka-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akka-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akka Streams

Akka Streams is a library to process and transfer a sequence of elements using bounded buffer space, implementing the Reactive Streams specification for asynchronous stream processing with non-blocking backpressure.

- **Human URL:** [https://doc.akka.io/libraries/akka/current/stream/index.html](https://doc.akka.io/libraries/akka/current/stream/index.html)

#### Tags

- Backpressure
- Data Streaming
- Reactive
- Reactive Streams

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka/current/stream/index.html)
- [Postman Collection](collections/akka-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akka-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akka gRPC

Akka gRPC provides support for building streaming gRPC servers and clients on top of Akka Streams, with code generation from protobuf definitions for both Java and Scala.

- **Human URL:** [https://doc.akka.io/libraries/akka-grpc/current/](https://doc.akka.io/libraries/akka-grpc/current/)

#### Tags

- gRPC
- Protobuf
- Streaming

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-grpc/current/)
- [Postman Collection](collections/akka-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akka-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/akka-io)
- [Website](https://akka.io/)
- [Documentation](https://doc.akka.io/)
- [Getting Started](https://doc.akka.io/libraries/akka/current/typed/guide/introduction.html)
- [GitHub Organization](https://github.com/akka)
- [Blog](https://akka.io/blog/)
- [Pricing](https://akka.io/pricing/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/json-schema/akka-config.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/rules/akka-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/vocabulary/akka-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://akka.io/partners)
- [L L Ms Txt](https://akka.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
