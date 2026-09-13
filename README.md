# hey, i'm Dağlar

Product engineer focused on **backend systems, real-time infrastructure, control planes, and AI-native products**.

I like taking messy operational problems and turning them into systems that are observable, permission-aware, and actually useful in production.

## selected engineering

### [elastic-telemetry](https://github.com/rnaefe/elastic-telemetry)
Telemetry/search control plane for noisy semi-structured runtime events.

- Thin JSON ingest path with Elasticsearch-backed search and aggregations.
- MySQL-backed users, sessions, servers, channels, and access mappings.
- Next.js control surface that keeps raw Elasticsearch access behind application authorization.
- Designed around a deliberate split between the hot ingest path, search-heavy data, and relational control state.

### [fivem-watch](https://github.com/rnaefe/fivem-watch)
Self-hosted real-time operations console for multiplayer servers.

- Watcher-scoped stream relay instead of global broadcast.
- Demand-driven client capture: expensive work starts only when an operator asks for it.
- Centralized auth, stream ownership, cleanup, and routing with distributed edge capture.
- Built around explicit operational trade-offs rather than a P2P-first design.

### [Arabic-First Support POC](https://github.com/rnaefe/case-study)
AI support system where the model handles language understanding while deterministic application code owns authorization, policy, evidence, and side effects.

- Mixed English / Arabic / Arabizi support.
- Explicit tenant, OTP, private-order, policy, confirmation-token, idempotency, handoff, and redaction boundaries.
- Deterministic integration/e2e tests plus tagged live-model evaluation suites.
- Architecture keeps semantic interpretation separate from business authority.

## engineering interests

```txt
backend systems     real-time infrastructure     developer tools
control planes      observability                AI product engineering
Rust                TypeScript                   Elasticsearch / SQL
```

I care more about **system boundaries, failure modes, trade-offs, and measurable behavior** than collecting frameworks.

## currently

Spending more time on Rust, AI-first product engineering, and systems where models can assist with decisions without owning authorization or execution.

## links

portfolio: https://daglarefe.com  
linkedin: https://linkedin.com/in/daglar-efe-goksoy  
email: goksoyefedaglar@gmail.com
