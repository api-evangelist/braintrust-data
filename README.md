# Braintrust (braintrust-data)

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

Braintrust (braintrust.dev) is an end-to-end platform for building, evaluating, and observing AI applications. Its REST API at api.braintrust.dev exposes projects, experiments, datasets, logs/spans, prompts, functions and scorers, evals, and full organization/ACL management, plus an OpenAI-compatible AI proxy, all authenticated with a Bearer API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/braintrust-data/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/braintrust-data/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Evaluation
- Observability
- LLMOps

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Braintrust Projects API

Create, list, update, and delete projects - the top-level containers that organize AI features, experiments, datasets, logs, prompts, and scorers.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Projects
- Organization

#### Properties

- [Documentation](https://www.braintrust.dev/docs/reference/api)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Experiments API

Manage evaluation experiments and their events - create experiments, insert and fetch events, submit feedback, summarize results, and launch evals.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Experiments
- Evaluation

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/evals)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Datasets API

Manage datasets and dataset events used as test cases - create datasets, insert, fetch, and summarize records, and submit feedback, plus dataset snapshots.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Datasets
- Test Data

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/datasets)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Logs and Spans API

Insert, fetch, and provide feedback on production trace spans and log events stored under a project, the backbone of Braintrust observability.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Logs
- Spans
- Tracing

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/logging)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Prompts API

Create, version, list, update, and delete prompts that bundle model, messages, and parameters for reuse across the platform and at runtime.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Prompts
- Versioning

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/prompts)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Functions and Scorers API

Manage and invoke functions - tools, prompts, and code/LLM scorers - including create, list, update, delete, and server-side invocation.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Functions
- Scorers
- Tools

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/functions)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Project Configuration API

Configure project-level resources - project scores, tags, automations, saved views, and span iframes - that shape how data is scored and displayed.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- Project Scores
- Tags
- Automations
- Views

#### Properties

- [Documentation](https://www.braintrust.dev/docs/reference/api)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Organization and ACL API

Manage organizations, members, users, groups, roles, and fine-grained ACLs for governing access to every Braintrust resource.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- ACL
- Organization
- Users
- Roles
- Groups

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/access-control)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust Credentials and Secrets API

List and revoke API keys, manage service tokens, store provider AI secrets, and set environment variables and MCP server connections.

- **Human URL:** [https://www.braintrust.dev/docs/api-reference](https://www.braintrust.dev/docs/api-reference)
- **Base URL:** `https://api.braintrust.dev/v1`

#### Tags

- API Keys
- Service Tokens
- AI Secrets
- Environment Variables

#### Properties

- [Documentation](https://www.braintrust.dev/docs/reference/api)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintrust AI Proxy API

OpenAI-compatible proxy for chat/completions, completions, and embeddings across many model providers, with caching, logging, and temporary credentials.

- **Human URL:** [https://www.braintrust.dev/docs/guides/proxy](https://www.braintrust.dev/docs/guides/proxy)
- **Base URL:** `https://api.braintrust.dev/v1/proxy`

#### Tags

- AI Proxy
- OpenAI Compatible
- Inference

#### Properties

- [Documentation](https://www.braintrust.dev/docs/guides/proxy)
- [API Reference](https://www.braintrust.dev/docs/api-reference)
- [OpenAPI](openapi/braintrust-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintrust-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintrust-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/braintrustdata)
- [LinkedIn](https://www.linkedin.com/company/braintrustdata)
- [Website](https://www.braintrust.dev/)
- [Documentation](https://www.braintrust.dev/docs)
- [Plans](plans/braintrust-data-plans-pricing.yml)
- [Rate Limits](rate-limits/braintrust-data-rate-limits.yml)
- [Fin Ops](finops/braintrust-data-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
