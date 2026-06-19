### Hi, I'm Aleksandr 👋

**Backend & Platform Engineer — Node.js/TypeScript · C#/.NET · Containers · Observability · CI/CD · Document automation**

I build backend and platform systems for document-heavy and integration-heavy workflows: XML/XSLT → PDF pipelines, digital signatures, task runners, internal APIs, containerized deployments, observability, CI/CD, and production reliability.

My main production stack is Node.js/TypeScript, but I also work with C#/.NET for backend services and tooling, and Swift/SwiftUI for iOS apps and experiments.

#### Systems I build

- **Document pipelines** — XML/XSLT3 transformations, Apache FOP rendering, PDF/FO workflows, custom fonts, hyphenation, caching, and worker orchestration.
- **Digital signature workflows** — CryptoPro/CAdES/CMS helpers, PKCS#7/PKCS#12 flows, detached/attached signatures, PDF signing, and rate-limit aware processing.
- **Task runners & integrations** — resilient background workers over MSSQL, Redis, RabbitMQ, and external APIs.
- **Runtime & containerization** — Docker images, BuildKit builds, slim runtime containers, environment-driven configuration, PM2 process management, and container-friendly service layouts.
- **Platform reliability** — reverse proxies, internal DNS, health checks, structured logs, tracing, dashboards, alerts, and production debugging.

#### What I'm working on

- **signature-service** — fast PNG/SVG signature stamp generation, PDF signing workflows, smart caching, and production-friendly rate limiting.
- **xml-xslt-transformer** — Saxon EE XSLT3 → Apache FOP 2.11 for FO→PDF, custom fonts and hyphenation, multi-instance workers, semaphores, and cache TTLs.
- **Platform tooling** — Docker/BuildKit, PM2, Nginx/Traefik, internal DNS, healthz endpoints, OTLP tracing, Pino logs, Grafana/Loki dashboards, and GitLab CI/CD pipelines.

#### Selected projects

- **rfmo** — Node.js RFMO/Fedsfm API client for calls through an mTLS gateway; token caching, retries, binary downloads, envelope capture, portal notification handling, tests, and a Docker image.  
  https://github.com/omggga/rfmo
- **mtls** — production-oriented mTLS playground with Nginx/Traefik configs, client certificate auth, OpenSSL/CFSSL tooling, and Node/Undici test clients.  
  https://github.com/omggga/mtls
- **crypto_pro_api** — Node/TypeScript helpers for CryptoPro CAdES/CMS: certificate discovery, detached/attached signatures, and PKCS#7/PKCS#12 flows.  
  https://github.com/omggga/crypto_pro_api
- **jaeger-to-mattermost** — lightweight bridge that surfaces trace errors and latency signals from Jaeger into Mattermost via webhooks.  
  https://github.com/omggga/jaeger-to-mattermost

#### Also exploring

- **AI-assisted development** — Codex/Claude Code-style workflows, MCP tools, automation agents, and developer tooling.
- **iOS with Swift/SwiftUI** — multilingual apps, offline data, map deep links, and practical mobile UX.
- **C#/.NET** — backend services, integration tooling, tests, and cross-stack maintenance.

#### I work with

**Backend:** Node.js 22/24, TypeScript 5+, C#/.NET, MSSQL, Redis, RabbitMQ, Pino, Undici  
**Documents & signing:** XML, XSLT3, Saxon EE, Apache FOP, PDF/FO, CryptoPro, CAdES/CMS, PKCS#7/12  
**Containers & platform:** Docker, BuildKit, PM2, GitLab Runner, GitLab CI/CD, Nginx, Traefik, Linux  
**Observability:** OpenTelemetry, OTLP, Jaeger, Grafana, Loki, Promtail, structured logging  
**Security & networking:** mTLS, OpenSSL, CFSSL, client certificates, reverse proxies, internal DNS  
**Mobile & Apple:** Swift, SwiftUI, Xcode  
**AI/tooling:** MCP, AI-assisted development, automation scripts, CI helpers

#### Open to

Remote part-time/contract work where the problem involves backend systems, document/PDF automation, digital signatures, containerized services, observability, CI/CD, production debugging, or integration-heavy workflows.

Time zones: EU/Asia friendly.

Issues/PRs welcome — thanks for using my code!

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=omggga&layout=compact&langs_count=10&hide=html,css,c,c%2B%2B,perl,postscript&exclude_repo=dotfiles,old-scripts&cache_seconds=21600)
