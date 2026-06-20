# Braintrust (braintrust-data)

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
