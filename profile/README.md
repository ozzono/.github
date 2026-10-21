# Hi, I'm Hugo Virgílio

Senior Backend Engineer designing and scaling high-throughput Go microservices and cloud infrastructure (GCP/AWS). I care about clean architecture, observability, and test suites that catch real bugs instead of padding line coverage.

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)

## Featured Projects

### [Daedalus](https://github.com/ozzono/daedalus) · Sandboxed AI Developer Agent Control Plane
Local control plane in Go for orchestrating durable, multi-step AI code generation and refactoring operations via Temporal workflows. Uses `git worktree` for isolated workspace management and `ai-jail` process sandboxing to run AI-driven edits safely, with automated testing loops.

### [GoLens: Metrics](https://github.com/GoLens-Project/golens-metrics) · Observability Middleware for Go
Lightweight, declarative HTTP and gRPC middleware package for exporting standardized performance metrics and endpoint usage data. Ships with native hooks for Prometheus scraping and Grafana dashboards, cutting the boilerplate of instrumenting Go microservices.

## Honorable Mentions

- **[GoLens: Mutant](https://github.com/GoLens-Project/golens-mutant)** · Declarative mutation testing for Go. Introduces AST-level code mutations to measure test suite resilience beyond line coverage, flagging weak assertions and untested paths with detailed mutation score reports.
- **[HodlBook](https://github.com/HodlBook/hodlbook)** · Self-hosted cryptocurrency portfolio tracker in Go (Gin + SQLite, HTMX frontend) that records deposits, withdrawals, and exchanges to show allocation and profit by reference currency.

## Shipped Projects

- **[Arete](https://areteoikos.com.br)** · Freelance SaaS for homeschooling families built around a classical education (Trivium) curriculum and a 52-week virtue formation program. Multi-tenant Go (Gin) + SQLite backend, Flutter PWA frontend, deployed on Dokku behind Cloudflare.
- **[HodlBook](https://hodlbook.app)** · Crypto portfolio tracker for manual asset management, started from the [open source version](https://github.com/HodlBook/hodlbook) and since evolved well beyond it: live prices over SSE, ACB-based P/L tracking, multi-wallet management, planning panel, and Stripe/Plisio subscriptions, on Go + HTMX web and Flutter apps.

## Toolbox

**Languages:** Go, Python, SQL, TypeScript, Dart  
**Backend:** gRPC, REST, GraphQL, Kafka, RabbitMQ, Redis, Postgres  
**Infra:** GCP, AWS, Kubernetes, Docker, Terraform, GitHub Actions  
**Observability:** Prometheus, Grafana, Loki, OpenTelemetry, CloudWatch, Golens-Metrics

## AI Tooling

I'm an AI enthusiast both at work and on my own machines. Daily workflow runs on the major assistants (Claude Code, Codex, GitHub Copilot), but I also go deeper into the niche side: self-hosted models through Ollama and MLX, local inference when data can't leave the machine, and LLM automation tooling, from API integrations to full agent orchestration (that's what Daedalus above is about).

## GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ozzono&show_icons=true&rank_icon=github&hide_border=true&exclude_repos=.github,GadgetBridge,ralph,DAppNodePackage-monero,awesome-chatgpt-prompts,xmrig,http-scraper,challenge-bravo,rock-band,vuex_todo_manager" alt="ozzono's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ozzono&layout=compact&hide_border=true&langs_count=8&exclude_repo=.github,GadgetBridge,ralph,DAppNodePackage-monero,awesome-chatgpt-prompts,xmrig,http-scraper,challenge-bravo,rock-band,vuex_todo_manager" alt="Top languages" />
</p>
