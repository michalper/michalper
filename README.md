# Michał Per

Senior PHP Developer & Solution Architect, Katowice, Poland.

14 years of backend engineering — Magento, Symfony, Laravel — including a path from System Architect through CTO to Technology Leader at STATSCORE. I design systems for scale: event-driven architectures, API integrations, payment and messaging pipelines.

For the past three years I've worked daily with AI coding assistants, commercially with Claude Code since December 2025. I build the tools I use, not just the features they're asked for: a Claude Code plugin with its own skill, MCP servers for auditing Magento projects and automating job search, guardrails against hallucinated output.

**Currently open to new opportunities** — [LinkedIn](https://linkedin.com/in/michalper/)

## Highlights

**A technology department of 13** — backend, frontend, DevOps, QA and a Scrum Master; recruitment, mentoring, 1:1s and performance reviews, reporting directly to the CEO (STATSCORE).

**Built the DevOps function from scratch** — it didn't exist before; grew it to a 2-person team, enabling company-wide dockerization and Kubernetes adoption (STATSCORE).

**26 custom Magento modules and 30+ API integrations** delivered for B2B/B2C clients, including payment integrations (Adyen, PayPal, Braintree).

**A real-time marketing engine** (Silex, Redis, RabbitMQ) I designed and built myself — reacts to real-world events and context, from weather-triggered campaigns to on-site personalization, and also powers content/ad recommendations for TVN. Still a core, [publicly advertised](https://www.ipresso.com/features/real-time-marketing) feature of iPresso's platform today.

**A Zapier-style integration hub** (Silex, RabbitMQ, MongoDB) connecting every integration available in iPresso's marketing automation platform — used by clients including LOT, eSky and Nutricia. Still [publicly offered](https://www.ipresso.com/features/integrations) as the platform's integrations hub today.

**A mass-mailing microservice** (Silex, RabbitMQ) handling millions of email/SMS/MMS/audio sends, including a self-written mechanism for randomized A/B/X variant assignment.

**Rebuilt the live data pipeline for [ScoutsFeed](https://www.statscore.com/products/scoutsfeed/)**, STATSCORE's play-by-play sports-data product — it used to drop messages and throw 500 errors under load, now it's fault-tolerant with a sub-second latency requirement.

## Skills

PHP · Magento · Symfony · Laravel · Silex · MySQL · PostgreSQL · Elasticsearch · RabbitMQ · Redis · MongoDB · APIs & system integration · Feature flags · Docker · PHPUnit · Codeception/Selenium (MFTF) · Monitoring & observability (New Relic, Graylog, Grafana, Sentry, Kibana) · Scrum/Kanban · Claude Code

## Projects

**[ordo](https://github.com/michalper/ordo)** — B2B + B2C marketing automation for Magento Open Source: campaign engine, reorder reminders, abandoned cart, SMS/WhatsApp/push.

**[mcp-magento-audit](https://github.com/michalper/mcp-magento-audit)** — MCP server giving an AI agent tools to audit Magento 2 / Adobe Commerce projects for update compatibility, module quality, and dependency security.

**[magento-upgrade-advisor](https://github.com/michalper/magento-upgrade-advisor)** — turns mcp-magento-audit's upgrade-plan data into a prioritized remediation narrative via Claude, with a programmatic faithfulness check (every blocker cited by index, exactly once — no second model call judging the first) and a model-comparison eval harness.

**[mcp-job-search](https://github.com/michalper/mcp-job-search)** — MCP server automating job-search mechanics (multi-source search, posting fetch, CV rendering, a configurable anti-fabrication linter, application-registry tracking) while leaving drafting and fact-checking to the calling assistant.

**[laravel-ddd-invoices](https://github.com/michalper/laravel-ddd-invoices)** — Modular Laravel 13 app: an Invoices module in DDD, with a transactional outbox and a notification-driven send workflow.

**[ai-message-router](https://github.com/michalper/ai-message-router)** — AI-powered message categorization & routing PoC — Symfony, a local LLM via Ollama, function-calling.

**[open-mercato-marketing-automation](https://github.com/michalper/open-mercato-marketing-automation)** — my marketing automation module built on top of Open Mercato, an AI-native CRM/ERP framework.

## Certifications

**Anthropic** — Agentic AI Development, 9 certifications: AI Fluency, Claude API, Claude Code, MCP, Subagents, Agent Skills, Claude Cowork.

**Adobe** — Adobe Certified Professional: Adobe Commerce Developer.

**Lightbend** — Reactive Architecture (3 modules): DDD, CQRS & Event Sourcing, Reactive Microservices.

**MongoDB University** — 4 courses (M001, M100, M103, M112).

**Redis** — Certified Developer + 5 certifications (RU101, RU202, RU203, RU301, RU330).
