# Hi, I'm Hamza

**.NET Software Engineer** | C#, ASP.NET Core, Azure, SQL Server | M.S. Computer Science, Texas Tech University

I build production backend systems that stay up when things go wrong: event-driven services, fast SQL, and secure, well-tested APIs. Four years across enterprise fintech, healthcare billing and Azure integration platforms.

Based in Vienna, VA. Open to **.NET and backend engineering roles** in the DMV area or remote across the US.

## Selected projects

Reference implementations of patterns I use in production. Each has a README, automated tests and CI, and none contains employer code.

**Try it live:** [Coffee Shop Rush](https://hamzamehmood46.github.io/coffee-shop-rush/) is an animated cafe that shows, without jargon, how real software keeps orders safe when something crashes. Crash the barista, flip the safety net, crash again. Blazor WebAssembly, 23 tests. ([source](https://github.com/hamzamehmood46/coffee-shop-rush))

**Analytics work (SQL and Python):** [SaaS Product Analytics](https://hamzamehmood46.github.io/saas-product-analytics-sql/) (funnel, cohort retention, channel quality in plain SQL with window functions and CTEs) and the [A/B Test Analyzer](https://hamzamehmood46.github.io/ab-test-analyzer/) (live significance calculator, sample-size planner, and a simulation of why peeking at results gives false wins). Both are tested and use synthetic or user-supplied data.

| Project | What it shows |
|---|---|
| [Hold My Seat](https://hamzamehmood46.github.io/seat-booking-dotnet/) | Seat booking in C# (live demo): expiring holds, all-or-nothing reservations, idempotent purchases, and no double-booking under real multi-threaded contention |
| [Till: Point of Sale](https://hamzamehmood46.github.io/point-of-sale-dotnet/) | Offline-first register in C# (live demo): split payments, refunds, drawer reconciliation, and sales that sync exactly once after an outage |
| [Pipeline CRM (live demo)](https://hamzamehmood46.github.io/mini-crm-dotnet/) | CRM-style project: duplicate-proof lead conversion, strict deal pipeline, forecast, OData-style filters, versioned sync to another system; 142 tests |
| [Nudge: invoice reminders (live demo)](https://hamzamehmood46.github.io/invoice-reminders-dotnet/) | Invoicing and payment reminders: escalating schedule, once-only late fees, idempotent payments, aging report, cash forecast; 93 tests |
| [Flagpole: feature flags (live demo)](https://hamzamehmood46.github.io/feature-flags-dotnet/) | Feature flags: targeting rules, stable percentage rollouts, variants, prerequisites, outage-safe client; 125 tests |
| [Webhook Relay (live demo)](https://webhook-relay-dotnet.onrender.com/swagger) | Webhook relay: signature verification, de-duplication, routing, retries, dead letters, replay, circuit breaker, per-customer workspaces; 252 tests |
| [Triage: support inbox (live demo)](https://hamzamehmood46.github.io/support-inbox-dotnet/) | Help desk: business-hours SLA timers that pause while waiting on the customer, skill-based assignment, merging, auto-close, escalation; 237 tests |
| [Stripe payments (live demo)](https://stripe-payments-dotnet.onrender.com/swagger) | Stripe integration: subscriptions, ACH payments, signed idempotent webhooks, with a keyless simulator; 33 tests |
| [Twilio messaging console (live demo)](https://hamzamehmood46.github.io/twilio-messaging-dotnet/) | Texting console following carrier rules: message-part counting, delivery statuses and error codes, STOP/START handling, quiet hours, bulk preview; simulated carrier; 165 tests |
| [Multi-tenant SaaS API (live demo)](https://tenant-saas-api-dotnet.onrender.com/swagger) | Tenant isolation enforced in the query and write layers, roles, per-tenant rate limits; 28 tests |
| [Webhook Gateway (live demo)](https://webhook-gateway-dotnet.onrender.com/swagger) | HMAC-signed webhooks, replay protection, retries, dead letters, idempotent receiver; 68 tests |
| [Job Scheduler (live demo)](https://hamzamehmood46.github.io/job-scheduler-dotnet/) | Cron, retries, missed-run and overlap policies, dead letters, on a simulated clock; 76 tests |
| [Monolith vs Microservices](https://github.com/hamzamehmood46/monolith-vs-microservices-dotnet) | One checkout system as a modular monolith and as four services; the same 12 scenarios (idempotency, compensation, no overselling, outages) pass in both |
| [OrderFlow](https://github.com/hamzamehmood46/orderflow-dotnet) ([live API](https://orderflow-dotnet.onrender.com/swagger)) | Idempotent APIs, retries with backoff, dead-letter handling in ASP.NET Core |
| [Transactional Outbox](https://github.com/hamzamehmood46/outbox-pattern-dotnet) ([live API](https://outbox-pattern-dotnet.onrender.com/swagger)) | Reliable event publishing, competing dispatchers, idempotent consumers |
| [Claims API](https://github.com/hamzamehmood46/claims-api-dotnet) ([live API](https://claims-api-dotnet.onrender.com/swagger)) | Clean Architecture, JWT auth, role-based claim workflow |
| [Event-Sourced Ledger](https://github.com/hamzamehmood46/event-sourced-ledger-dotnet) ([live API](https://event-sourced-ledger-dotnet.onrender.com/swagger)) | Event sourcing, CQRS, optimistic concurrency |
| [SQL Performance Lab](https://github.com/hamzamehmood46/sql-performance-lab-dotnet) | Query tuning verified by identical results and query plans |
| [XML Mapping Service](https://github.com/hamzamehmood46/xml-mapping-service-dotnet) ([live API](https://xml-mapping-service-dotnet.onrender.com/swagger)) | XSD validation, sandboxed XSLT, XXE protection |
| [Resilience Toolkit](https://github.com/hamzamehmood46/resilience-toolkit-dotnet) ([live playground](https://hamzamehmood46.github.io/resilience-toolkit-dotnet/)) | Retry with jitter, circuit breaker, timeout, bulkhead |
| [API Rate Limiter](https://github.com/hamzamehmood46/api-rate-limiter-dotnet) ([live playground](https://hamzamehmood46.github.io/api-rate-limiter-dotnet/)) | Token bucket and sliding window, ASP.NET Core middleware |

### Full-stack (Angular + .NET)

| Project | What it shows |
|---|---|
| [Inventory Manager](https://github.com/hamzamehmood46/inventory-manager-angular-dotnet) | CRUD with Angular 22 and an ASP.NET Core Web API, EF Core, paging and sorting |
| [Claims Portal](https://github.com/hamzamehmood46/claims-portal-angular) | JWT login and role-based workflow UI on top of the Claims API |
| [Employee Directory](https://github.com/hamzamehmood46/employee-directory-angular-dotnet) | Async form validation, minimal APIs, soft delete, dashboard |

## Tech I work with

- **Backend:** C#, .NET 8, ASP.NET Core, Web API, Entity Framework Core, microservices, event-driven architecture
- **Cloud and DevOps:** Azure (Functions, Service Bus, API Management, Key Vault), Docker, Terraform, Azure DevOps, GitHub Actions
- **Data:** SQL Server, PostgreSQL, Oracle, Cosmos DB, query optimization
- **Frontend:** Angular, TypeScript
- **AI:** LLM integration, RAG, evaluation

## Find me

- Portfolio: [hamzamehmood46.github.io](https://hamzamehmood46.github.io)
- LinkedIn: [linkedin.com/in/hamzamehmood46](https://www.linkedin.com/in/hamzamehmood46)
- Email: [hamza.mehmood46@gmail.com](mailto:hamza.mehmood46@gmail.com)
