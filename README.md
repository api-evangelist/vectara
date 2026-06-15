# Vectara (vectara)

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
