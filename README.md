# Awesome-Distributed-Tracing

## Top Distributed Tracing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on End-to-End Request Tracing, OpenTelemetry, Span Analysis, Service Maps & Observability for Microservices*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Distributed Tracing**. These systems follow requests across services, queues, and databases so teams can debug latency, errors, and dependencies in modern distributed systems.



**Examples** include Jaeger, Zipkin, Honeycomb, Datadog APM, New Relic, Dynatrace, Grafana Tempo, Lightstep (ServiceNow), Elastic APM, Splunk Observability, and AppDynamics (the category leaders).



**Open-source emphasis**: Distributed tracing is one of the strongest open observability domains. **OpenTelemetry**, **Jaeger**, **Zipkin**, **Grafana Tempo**, and **Apache SkyWalking** form production-grade stacks. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Datadog APM, New Relic, Dynatrace, Splunk Observability, AppDynamics](https://www.datadoghq.com/)**  

  Full-stack observability platforms with deep distributed tracing, service maps, and AI-assisted root-cause analysis.



- **[Honeycomb, Lightstep (ServiceNow)](https://www.honeycomb.io/)**  

  High-cardinality tracing and observability platforms optimized for complex production debugging.



- **[Grafana Cloud (Tempo), Elastic APM, Jaeger Cloud offerings](https://grafana.com/)**  

  Managed open-core tracing backends and APM products built on or compatible with open standards.



- **[Other commercial tracing / APM platforms](https://www.datadoghq.com/)**  

  Additional application performance and distributed tracing solutions for enterprises.



## Open-Source GitHub Projects



- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)**  

  CNCF standard for traces, metrics, and logs—vendor-neutral instrumentation, Collector, and SDKs that feed every major backend.



- **[Jaeger](https://github.com/jaegertracing/jaeger)**  

  CNCF graduated distributed tracing system—end-to-end request tracking, originally from Uber; widely deployed with OpenTelemetry.



- **[Zipkin](https://github.com/openzipkin/zipkin)**  

  Pioneer open-source distributed tracing system—simple architecture, broad language support, and long production history.



- **[Grafana Tempo](https://github.com/grafana/tempo)**  

  Open-source, high-scale, cost-efficient distributed tracing backend—designed for object storage and Grafana integration.



- **[Apache SkyWalking](https://github.com/apache/skywalking)**  

  Open-source APM and distributed tracing platform with strong service mesh and polyglot agent support.



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  Open-source observability platform—traces, metrics, and logs in one product, OpenTelemetry-native.



- **[OpenTelemetry Collector Contrib & processors](https://github.com/open-telemetry/opentelemetry-collector-contrib)**  

  Extended receivers, processors, and exporters for production OpenTelemetry pipelines.



- **[Uptrace, HyperDX & open OTel UIs](https://github.com/uptrace/uptrace)**  

  Open tracing UIs and backends built on OpenTelemetry and ClickHouse or similar stores.



### Additional Strong Open-Source Options



- **Instrumentation standard**: OpenTelemetry everywhere (apps, gateways, mesh).

- **Self-hosted backends**: Jaeger, Tempo, or Zipkin depending on scale and storage preference.

- **All-in-one**: SigNoz or SkyWalking for traces + metrics + UI.

- **Composable stacks**: OTel SDK → OTel Collector → Tempo/Jaeger → Grafana.

- Commercial APM still leads in AI RCA, unified product analytics, and enterprise support SLAs.



**Frameworks for building custom systems**:  

**OpenTelemetry** is the universal instrumentation layer.  

Backends: **Jaeger**, **Grafana Tempo**, **Zipkin**, or **SigNoz**.  

Commercial platforms (Datadog, New Relic, Dynatrace, Honeycomb, etc.) add managed scale and advanced analytics.  

Most modern teams instrument with OpenTelemetry and choose open or commercial backends based on scale and budget. Fully open distributed tracing is production-standard at very large scale.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Traces can contain sensitive request data (headers, payloads, user identifiers). Apply sampling, redaction, and retention policies. High-cardinality attributes can drive cost and storage—design carefully.

- Open-source stacks offer full control and no per-seat tracing fees but require operations expertise. Commercial platforms shift storage, UX, and support to the vendor. Neither replaces good SLOs and incident practice.



---



**Made for SREs, platform engineers, and teams debugging microservices in production.**  

Let's expand open, standards-based distributed tracing while recognizing the AI-assisted analysis that leading commercial APM platforms deliver.
