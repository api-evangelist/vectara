# Vectara (vectara)

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

Vectara is a Retrieval Augmented Generation (RAG) as a service platform that provides grounded generative AI for enterprises. The API-first platform exposes a unified REST API v2 for managing corpora, ingesting documents, performing semantic and hybrid search, generating answers with hallucination detection via the Hughes Hallucination Evaluation Model (HHEM), and building agents and pipelines on top of enterprise data. Headquartered in Mountain View, California and founded by former Google Search engineers, Vectara ships first-party Python and TypeScript SDKs, a public MCP server, React UI widgets, and an open ingestion framework.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vectara/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vectara/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- AI
- Agents
- Corpora
- Embeddings
- Enterprise Search
- Generative AI
- Grounded Generation
- Hallucination Detection
- LLM
- MCP
- RAG
- Retrieval
- Search
- Semantic Search
- Vector Search

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Vectara REST API

The Vectara REST API v2 is the unified interface for the Vectara RAG platform. It exposes endpoints for managing corpora, uploading and indexing documents, running semantic and hybrid queries with grounded generation, managing agents and pipelines, configuring generation presets, evaluating hallucinations, controlling access, and reading analytics.

- **Human URL:** [https://docs.vectara.com/docs/rest-api/](https://docs.vectara.com/docs/rest-api/)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Agents
- Analytics
- Corpora
- Documents
- Generation
- Pipelines
- Query
- RAG
- Search

#### Properties

- [Documentation](https://docs.vectara.com/docs/rest-api/)
- [Authentication](https://docs.vectara.com/docs/learn/authentication/oauth-2)
- [OpenAPI](openapi/vectara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://docs.vectara.com/vectara-oas-v2.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Vectara Corpora API

Create, list, update, and delete corpora that hold indexed documents for retrieval and grounded generation.

- **Human URL:** [https://docs.vectara.com/docs/api-reference/admin-apis/corpora](https://docs.vectara.com/docs/api-reference/admin-apis/corpora)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Admin
- Corpora
- Index

#### Properties

- [Documentation](https://docs.vectara.com/docs/api-reference/admin-apis/corpora)
- [OpenAPI](openapi/vectara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vectara-corpus-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/vectara-corpus-structure.json)
- [JSON-LD](json-ld/vectara-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Vectara Indexing API

Upload and index documents into a Vectara corpus using either structured Core indexing or unstructured file upload. Supports add, replace, and delete operations on documents.

- **Human URL:** [https://docs.vectara.com/docs/api-reference/indexing-apis/indexing](https://docs.vectara.com/docs/api-reference/indexing-apis/indexing)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Documents
- Index
- Upload

#### Properties

- [Documentation](https://docs.vectara.com/docs/api-reference/indexing-apis/indexing)
- [OpenAPI](openapi/vectara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vectara-document-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Vectara Query API

Run semantic, keyword, and hybrid queries across one or more corpora with optional grounded generation, citations, reranking, and Hughes Hallucination Evaluation Model (HHEM) factual-consistency scoring.

- **Human URL:** [https://docs.vectara.com/docs/api-reference/search-apis/search](https://docs.vectara.com/docs/api-reference/search-apis/search)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Generation
- Grounded Generation
- Hybrid Search
- Query
- Search

#### Properties

- [Documentation](https://docs.vectara.com/docs/api-reference/search-apis/search)
- [OpenAPI](openapi/vectara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vectara-query-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Vectara Chat API

Multi-turn conversational interface over a Vectara corpus that maintains chat history and produces grounded, cited answers with optional streaming.

- **Human URL:** [https://docs.vectara.com/docs/api-reference/chat-apis/chat-apis](https://docs.vectara.com/docs/api-reference/chat-apis/chat-apis)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Chat
- Conversation
- Generation
- RAG

#### Properties

- [Documentation](https://docs.vectara.com/docs/api-reference/chat-apis/chat-apis)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vectara Agents API

Build and operate agents over Vectara corpora with tools, tool servers (MCP-compatible), planning, sessions, and grounded generation.

- **Human URL:** [https://docs.vectara.com/docs/api-reference/agents-api/agents](https://docs.vectara.com/docs/api-reference/agents-api/agents)
- **Base URL:** `https://api.vectara.io/v2`

#### Tags

- Agents
- AI
- Tools

#### Properties

- [Documentation](https://docs.vectara.com/docs/api-reference/agents-api/agents)
- [OpenAPI](openapi/vectara-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vectara-agent-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Vectara OAuth 2.0 Token API

OAuth 2.0 client credentials flow used to obtain a short-lived JWT for calling the Vectara REST API.

- **Human URL:** [https://docs.vectara.com/docs/learn/authentication/oauth-2](https://docs.vectara.com/docs/learn/authentication/oauth-2)
- **Base URL:** `https://auth.vectara.io`

#### Tags

- Authentication
- OAuth2
- Tokens

#### Properties

- [Documentation](https://docs.vectara.com/docs/learn/authentication/oauth-2)
- [Postman Collection](collections/vectara.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vectara.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.vectara.com/)
- [Developer](https://docs.vectara.com/docs)
- [Documentation](https://docs.vectara.com/docs/rest-api/)
- [OpenAPI](https://docs.vectara.com/vectara-oas-v2.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://github.com/vectara/python-sdk)
- [SDK](https://github.com/vectara/typescript-sdk)
- [SDK](https://github.com/vectara/py-vectara-agentic)
- [SDK](https://github.com/vectara/langchain-vectara)
- [Tools](https://github.com/vectara/vectara-mcp)
- [Tools](https://github.com/vectara/vectara-ingest)
- [Tools](https://github.com/vectara/vectara-ui)
- [Tools](https://github.com/vectara/react-search)
- [Tools](https://github.com/vectara/react-chatbot)
- [Tools](https://github.com/vectara/stream-query-client)
- [Tools](https://github.com/vectara/create-ui)
- [Tools](https://github.com/vectara/vectara-answer)
- [Tools](https://github.com/vectara/open-rag-eval)
- [Tools](https://github.com/vectara/hallucination-leaderboard)
- [Tools](https://github.com/vectara/agent-skills)
- [Samples](https://github.com/vectara/getting-started)
- [Samples](https://github.com/vectara/example-notebooks)
- [Samples](https://github.com/vectara/design-patterns)
- [Git Hub](https://github.com/vectara)
- [Blog](https://www.vectara.com/blog)
- [Pricing](https://www.vectara.com/pricing)
- [Status Page](https://status.vectara.com/)
- [Support](https://docs.vectara.com/docs/support)
- [Privacy Policy](https://vectara.com/legal/privacy-policy/)
- [Terms of Service](https://vectara.com/legal/terms-of-service/)
- [LinkedIn](https://www.linkedin.com/company/vectara/)
- [Changelog](https://docs.vectara.com/docs/release-notes)
- [Integrations](https://docs.vectara.com/docs/integrations)
- [L L Ms Txt](https://docs.vectara.com/llms.txt)
- [Rate Limits](rate-limits/vectara-rate-limits.yml)
- [Plans](plans/vectara-plans-pricing.yml)
- [Fin Ops](finops/vectara-finops.yml)
- [Rules](rules/vectara-rules.yml)
- [Vocabulary](vocabulary/vectara-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
