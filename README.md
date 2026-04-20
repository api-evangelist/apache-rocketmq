# Apache RocketMQ (apache-rocketmq)
Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal, transactional, delayed, and ordered messages.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-rocketmq/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Native, Messaging, Message Queue, Pub-Sub, Streaming, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache RocketMQ REST API
RocketMQ provides REST endpoints for sending and receiving messages, managing topics and subscriptions, and monitoring brokers and consumer groups, with producer and consumer client SDKs in Java, Go, Python, C++, and more.

**Human URL:** [https://rocketmq.apache.org/docs/](https://rocketmq.apache.org/docs/)

#### Tags:

 - Cloud Native, Messaging, REST, Apache, Open Source

#### Properties

- [Documentation](https://rocketmq.apache.org/docs/)
- [OpenAPI](openapi/apache-rocketmq-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/rocketmq)
- [Documentation](https://rocketmq.apache.org/)
- [SpectralRules](rules/apache-rocketmq-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-rocketmq-vocabulary.yaml)
- [NaftikoCapability](capabilities/rocketmq-workflow.yaml)
- [JSON-LD](json-ld/apache-rocketmq-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| High Throughput | Billion-level message throughput with low latency |
| Multiple Message Types | Normal, ordered, delayed, transactional, and batch messages |
| Message Filtering | Server-side tag and SQL expression filtering |
| Exactly-Once Semantics | Transactional messages for exactly-once delivery |
| Delayed Messages | Schedule messages with configurable delay levels |
| Dead Letter Queue | Automatic dead letter queue for failed messages |
| Message Tracing | End-to-end message tracing for debugging and monitoring |

## Use Cases

| Name | Description |
|------|-------------|
| Order Processing | Ensure ordered processing of e-commerce order events |
| Event-Driven Microservices | Decouple microservices with reliable asynchronous messaging |
| Log Aggregation | Aggregate application logs from distributed services |
| Financial Transactions | Reliable transactional messaging for financial systems |

## Integrations

| Name | Description |
|------|-------------|
| Spring Boot | RocketMQ Spring Boot starter for easy integration |
| Apache Flink | Flink connector for stream processing from RocketMQ |
| Apache Spark | Spark Streaming connector for RocketMQ |
| Kubernetes | RocketMQ Operator for Kubernetes-native deployment |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache RocketMQ REST API](openapi/apache-rocketmq-rest-api.yaml)

### JSON Schema

- [Message](json-schema/apache-rocketmq-message-schema.json)
- [Topic](json-schema/apache-rocketmq-topic-schema.json)
- [Consumer Group](json-schema/apache-rocketmq-consumer-group-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache RocketMQ JSON Structures](json-structure/)

### JSON-LD

- [Apache RocketMQ Context](json-ld/apache-rocketmq-context.jsonld)

### Examples

- [Apache RocketMQ Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Messaging Workflow](capabilities/rocketmq-workflow.yaml) | Apache RocketMQ | 8 | Application Developer, Platform Engineer |

## Vocabulary

- [Apache RocketMQ Vocabulary](vocabulary/apache-rocketmq-vocabulary.yaml) — Unified taxonomy mapping messaging resources, actions, workflows, and personas

## Rules

- [Apache RocketMQ Spectral Rules](rules/apache-rocketmq-spectral-rules.yml) — Rules enforcing Apache RocketMQ API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
