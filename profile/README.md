<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/fuseone-logo-dark.svg">
  <img src="assets/fuseone-logo-light.svg" alt="FuseOne" width="360">
</picture>

<p><strong>Integração poderosa. Simplicidade real.</strong><br>
The intelligent layer between systems: we remove layers of complexity, we don't add new ones.</p>

<p>
  <a href="https://fuseone.io">fuseone.io</a> ·
  <a href="https://fusescope.fuseone.io">FuseScope</a> ·
  <a href="https://fuseone-io.github.io/fuseone-agents/docs/">FuseOne Agents docs</a>
</p>

</div>

---

FuseOne builds infrastructure software for companies that need their systems to talk to each other: integration, API management, observability and governed AI agents. Every product installs in the customer's own environment, on Kubernetes, and is built on open standards: Apache Camel, Apache APISIX, OpenTelemetry and MCP.

## Products

### FuseOne Flow

The visual integration platform (iPaaS) on Apache Camel-K. You design flows on a canvas, connect them to hundreds of Kamelets and FuseOne Fuselets, keep credentials in a built-in vault, and deploy to your own clusters through a remote agent. Multi-tenant, with SSO (OAuth2, SAML), 2FA and RBAC by workspace and project.

`Go` · `Next.js` · `Apache Camel-K` · `Kubernetes` · `gRPC`

### [FuseOne Agents](https://github.com/fuseone-io/fuseone-agents)

Governed AI agents for business operations. Every tool call clears a policy gate, every step is sealed into a hash-chained ledger, and a person approves what matters before it happens. Agents reach CRM, ERP, support queues and internal APIs through scoped MCP servers and connectors. One binary, one PostgreSQL, one Helm chart.

[Repository](https://github.com/fuseone-io/fuseone-agents) · [Documentation](https://fuseone-io.github.io/fuseone-agents/docs/) · [Landing page](https://github.com/fuseone-io/fuseone-agents-site)

### [FuseScope](https://github.com/fuseone-io/fusescope)

Open source, OpenTelemetry-native observability: APM, distributed tracing, logs, metrics, dashboards and alerts on ClickHouse, with PostgreSQL HA and OIDC SSO built in. A FuseOne fork of SigNoz, MIT licensed.

| Repository | What it is |
| --- | --- |
| [fusescope](https://github.com/fuseone-io/fusescope) | Backend and web UI |
| [fusescope-otel-collector](https://github.com/fuseone-io/fusescope-otel-collector) | Ingestion layer: OpenTelemetry Collector distribution and ClickHouse schema migrator |
| [fusescope-collector-server](https://github.com/fuseone-io/fusescope-collector-server) | FuseScope distribution of the OpenTelemetry Collector, built from upstream components |
| [fusescope-engine](https://github.com/fuseone-io/fusescope-engine) | Storage and query engine for telemetry on object storage (Rust, Arrow, DataFusion) |
| [fusescope-charts](https://github.com/fuseone-io/fusescope-charts) | Helm charts for Kubernetes |
| [fusescope-integrations](https://github.com/fuseone-io/fusescope-integrations) | Integration packages: collector configs, dashboards and pipelines, as a signed catalog |
| [fusescope-sdk](https://github.com/fuseone-io/fusescope-sdk) | Real User Monitoring SDKs for the browser and React |
| [fusescope-sdk-android](https://github.com/fuseone-io/fusescope-sdk-android) | Real User Monitoring for Android |
| [fusescope-mcp-server](https://github.com/fuseone-io/fusescope-mcp-server) | MCP server so AI assistants can query and manage FuseScope |
| [terraform-provider-fusescope](https://github.com/fuseone-io/terraform-provider-fusescope) | Terraform and OpenTofu provider: alerts, dashboards, RUM apps and access as code |
| [fusescope-docs](https://github.com/fuseone-io/fusescope-docs) · [fusescope-site](https://github.com/fuseone-io/fusescope-site) | [Documentation](https://docs.fusescope.fuseone.io/) and [landing page](https://fusescope.fuseone.io) |

### [FuseOne API Gateway](https://github.com/fuseone-io/fuseone-api-gateway)

Enterprise API management on Apache APISIX. A management console for routes, upstreams and consumers, 60+ plugin policies, authentication (JWT, OAuth2/OIDC, API key, HMAC, LDAP), rate limiting, an AI gateway for LLM traffic, an event gateway for Kafka and NATS, and a self-service developer portal.

`Go` · `Next.js` · `Apache APISIX`

### FuseOne Forja

The execution runtime of the FuseOne software factory: an MCP server that takes "implement issue X in repository Y" and returns a pull request with verifiable evidence — the commands that ran, their exit codes and the raw test logs. Early stage: the PRD and backlog are [open](https://github.com/fuseone-io/fuseone-forja).

### FuseOne ERP

ERP for supermarkets in the state of São Paulo: desktop point of sale, back-office web app and NFC-e fiscal invoicing.

`Python` · `Qt/C++` · `React`

## Principles

- **Simplify without hiding the engineering.** Every product shows what it does and why.
- **Structure without rigidity.** Open standards and open formats, no lock-in.
- **Scale without weight.** Small footprint, installs in your own cluster.
- **Robust without bureaucracy.** Audit trails, RBAC and SSO by default.

---

<div align="center">
<sub>Made in Brazil by the FuseOne team · <a href="https://fuseone.io">fuseone.io</a></sub>
</div>
