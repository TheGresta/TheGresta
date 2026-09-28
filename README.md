<div align="center">
  <img src="https://raw.githubusercontent.com/TheGresta/TheGresta/output/header.svg" alt="Dinçer Dinç" width="100%" />
</div>

<div align="center">

### Senior .NET Backend Engineer · Distributed Systems · Platform Engineering

I design the foundations other services are built on: shared kernels, messaging backbones,<br />
multi-tenant persistence and the guardrails that keep a growing microservice estate consistent.

<a href="https://www.linkedin.com/in/mdinc"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:mdinc.business@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## 👋 About Me

- 🏢 **Software Engineer at Incodi Fintech**, building backend services on **.NET 10**
- 🧱 Author of **[platform-shared-kernel](https://github.com/Gresta-Vertex-Labs/platform-shared-kernel)**, a 100+ package foundation for .NET microservices
- 🧩 I work in **DDD, CQRS and event-driven** architectures, with PostgreSQL, RabbitMQ/Kafka and Redis
- 🔭 Currently focused on build-time architecture enforcement, observability and AI-assisted engineering workflows
- 🌍 Based in Turkey

---

## 🚀 Featured Projects

### 🧱 [platform-shared-kernel](https://github.com/Gresta-Vertex-Labs/platform-shared-kernel)

A mono-repo of NuGet packages that forms the shared kernel of a .NET 10 microservice ecosystem. Cross-cutting concerns are solved once, and the build stops services from drifting away from the architecture.

- **104 packages across 21 capability domains**: persistence, messaging, caching, idempotency, security, workflows, search, storage, AI, reporting and more
- **Architecture enforced at build time**: a 7-tier dependency model checked by MSBuild, **45 custom Roslyn analyzers** and NetArchTest architecture tests
- **Production concerns built in**: multi-tenancy with PostgreSQL row-level security, transactional outbox, idempotency, OpenTelemetry, health and readiness probes, mTLS/OIDC
- **Tested against real infrastructure**: 114 test projects, integration lanes on Testcontainers
- **7 reference services** showing how to consume the kernel, shipped as one versioned release train

`.NET 10` `PostgreSQL` `EF Core` `Dapper` `MassTransit` `RabbitMQ` `Redis` `FusionCache` `Temporal` `OpenTelemetry` `gRPC` `Roslyn`

### 📘 [DotNet.Architect.Playbook](https://github.com/TheGresta/DotNet.Architect.Playbook)

Enterprise .NET patterns as isolated, runnable chapters: polyglot persistence, MassTransit sagas, CQRS, OAuth2/OIDC, RAG with Semantic Kernel and OpenTelemetry-backed observability.

<details>
<summary><b>Earlier work</b></summary>
<br />

- **[Kodlama.io-devs](https://github.com/TheGresta/Kodlama.io-devs)**: a modular monolith on Clean Architecture with CQRS and cross-cutting pipeline behaviours
- **[MailingMicroservice](https://github.com/TheGresta/MailingMicroservice)**: a standalone mailing service consuming a RabbitMQ queue via MailKit

</details>

---

## 🛠️ Tech Stack

| Area | Technologies |
| --- | --- |
| **Core** | .NET 10, C#, ASP.NET Core, gRPC, SignalR |
| **Data** | PostgreSQL, EF Core, Dapper, Redis, FusionCache, Elasticsearch, Meilisearch |
| **Messaging & jobs** | RabbitMQ, Apache Kafka, MassTransit, Wolverine, Temporal, Hangfire |
| **Cloud & delivery** | AWS (S3, SES), Firebase (FCM), Docker, Kubernetes, Nginx, GitHub Actions, Linux & Windows Server |
| **Observability** | OpenTelemetry, Prometheus, Grafana, Jaeger, Serilog |
| **Security** | OpenID Connect, OAuth2, JWT, mTLS |
| **Architecture** | Domain-Driven Design, CQRS, event-driven design, Clean Architecture, multi-tenancy |
| **AI & tooling** | Claude Code, context engineering, Semantic Kernel, Roslyn analyzers |

---

<details>
<summary><b>📊 GitHub stats</b></summary>
<br />
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheGresta/TheGresta/output/stats-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TheGresta/TheGresta/output/stats-light.svg" />
  <img alt="GitHub stats" src="https://raw.githubusercontent.com/TheGresta/TheGresta/output/stats-dark.svg" width="47%" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TheGresta/TheGresta/output/langs-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TheGresta/TheGresta/output/langs-light.svg" />
  <img alt="Most used languages" src="https://raw.githubusercontent.com/TheGresta/TheGresta/output/langs-dark.svg" width="47%" />
</picture>
</div>
</details>

<div align="center">
  <img src="https://raw.githubusercontent.com/TheGresta/TheGresta/output/footer.svg" alt="" width="100%" />
</div>
