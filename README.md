# Akka (akka)
Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of libraries including actors, HTTP, streams, cluster, persistence, and gRPC for building reactive, microservice-based architectures.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/akka/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Actor Model, Distributed Systems, Frameworks, Java, Microservices, Reactive, Scala

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Akka Management
Akka Management provides a suite of utilities for operating Akka-based distributed systems, including an HTTP management API for cluster management, health checks, and cluster bootstrap.

**Human URL:** [https://doc.akka.io/libraries/akka-management/current/](https://doc.akka.io/libraries/akka-management/current/)

#### Tags:

 - Actor Model, Cluster Management, Distributed Systems, Health Checks

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-management/current/)
- [OpenAPI](openapi/akka-management.json)

### Akka HTTP
Akka HTTP is a full HTTP stack built on Akka actors and streams providing a routing DSL for REST and WebSocket services.

**Human URL:** [https://doc.akka.io/libraries/akka-http/current/](https://doc.akka.io/libraries/akka-http/current/)

#### Tags:

 - HTTP, REST API, Reactive, Streaming

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-http/current/)
- [GettingStarted](https://doc.akka.io/libraries/akka-http/current/introduction.html)

### Akka Streams
Akka Streams implements the Reactive Streams specification for asynchronous stream processing with non-blocking backpressure.

**Human URL:** [https://doc.akka.io/libraries/akka/current/stream/index.html](https://doc.akka.io/libraries/akka/current/stream/index.html)

#### Tags:

 - Backpressure, Data Streaming, Reactive, Reactive Streams

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka/current/stream/index.html)

### Akka gRPC
Akka gRPC provides streaming gRPC servers and clients on top of Akka Streams with protobuf code generation.

**Human URL:** [https://doc.akka.io/libraries/akka-grpc/current/](https://doc.akka.io/libraries/akka-grpc/current/)

#### Tags:

 - gRPC, Protobuf, Streaming

#### Properties

- [Documentation](https://doc.akka.io/libraries/akka-grpc/current/)

## Common Properties

- [Website](https://akka.io/)
- [Documentation](https://doc.akka.io/)
- [GettingStarted](https://doc.akka.io/libraries/akka/current/typed/guide/introduction.html)
- [GitHubOrganization](https://github.com/akka)
- [Blog](https://akka.io/blog/)
- [Pricing](https://akka.io/pricing/)

## Features

| Name | Description |
|------|-------------|
| Actor Model | Lightweight concurrent entities (actors) that communicate via asynchronous message passing, enabling high-throughput distributed computation. |
| Cluster Sharding | Distributes actors across a cluster and automatically rebalances them when nodes join or leave the cluster. |
| Persistence and Event Sourcing | Durable actor state through event sourcing with pluggable journal backends (Cassandra, PostgreSQL, DynamoDB, etc.). |
| Distributed Data | Conflict-free replicated data types (CRDTs) for sharing data across cluster nodes without coordination overhead. |
| HTTP and WebSocket | Full HTTP/1.1 and HTTP/2 server and client stack with routing DSL, JSON support, and WebSocket upgrades. |
| Reactive Streams | Backpressure-aware stream processing compliant with the Reactive Streams specification. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices | Teams build resilient, location-transparent microservices using Akka actors and HTTP with built-in backpressure and supervision. |
| Real-Time Data Processing | Organizations process high-throughput event streams using Akka Streams with exactly-once processing guarantees. |
| Distributed State Management | Applications maintain distributed mutable state using cluster sharding and distributed data without external coordination systems. |
| Event Sourcing | Systems implement event sourcing and CQRS patterns using Akka Persistence with pluggable journal backends. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Alpakka Kafka connector for consuming and producing Kafka messages |
| Cassandra | Alpakka Cassandra connector and Akka Persistence journal |
| AWS | Alpakka connectors for S3, SQS, SNS, DynamoDB, and other AWS services |
| gRPC | Akka gRPC for code generation from protobuf and streaming gRPC services |
| Spring Boot | Integration with Spring Boot for mixed Akka and Spring applications |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Akka Management API](openapi/akka-management.json)

### JSON Schema

- [Akka Config Schema](json-schema/akka-config.json)

### JSON Structure

- [Akka Config Structure](json-structure/akka-config-structure.json)

### JSON-LD

- [Akka Context](json-ld/akka-context.jsonld)

### Examples

- [Akka Management ClusterMembers Example](examples/akka-management-clustermembers-example.json)
- [Akka Management ClusterMember Example](examples/akka-management-clustermember-example.json)
- [Akka Config Example](examples/akka-config-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Akka Management](capabilities/shared/akka-management.yaml) — 4 operations for cluster management and health checks

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cluster Operations](capabilities/cluster-operations.yaml) | Akka Management | 4 | Platform Engineer, SRE |

## Vocabulary

- [Akka Vocabulary](vocabulary/akka-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Akka Spectral Rules](rules/akka-spectral-rules.yml) — 12 rules across 7 categories enforcing Akka Management API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
