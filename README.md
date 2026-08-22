# Apache RocketMQ (apache-rocketmq)

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
