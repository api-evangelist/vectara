# Vectara (vectara)
Vectara is a Mountain View, California-based grounded generative AI / Retrieval Augmented Generation (RAG) as a service platform founded by former Google Search engineers. Its API-first platform exposes a unified REST API v2 for managing corpora, ingesting structured and unstructured content, running semantic and hybrid retrieval, generating cited answers with the Hughes Hallucination Evaluation Model (HHEM) for factual-consistency scoring, and orchestrating agents and pipelines on top of enterprise data. Vectara ships first-party Python and TypeScript SDKs, a public Model Context Protocol (MCP) server, React UI widgets, an open ingestion framework, and reference applications.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/vectara/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- AI, Agents, Corpora, Embeddings, Enterprise Search, Generative AI, Grounded Generation, Hallucination Detection, LLM, MCP, RAG, Retrieval, Search, Semantic Search, Vector Search

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Vectara REST API
The unified REST API v2 for the Vectara platform. Manage corpora, upload and index documents, run semantic and hybrid queries with grounded generation, manage agents and pipelines, configure generation presets, evaluate hallucinations, and read analytics.

**Human URL:** [https://docs.vectara.com/docs/rest-api/](https://docs.vectara.com/docs/rest-api/)

- [Documentation](https://docs.vectara.com/docs/rest-api/)
- [Authentication — OAuth 2.0](https://docs.vectara.com/docs/learn/authentication/oauth-2)
- [OpenAPI (local)](openapi/vectara-openapi.yml)
- [OpenAPI (upstream)](https://docs.vectara.com/vectara-oas-v2.yaml)

### Vectara Corpora API
Create, list, update, and delete corpora that hold indexed documents for retrieval and grounded generation.

**Human URL:** [https://docs.vectara.com/docs/api-reference/admin-apis/corpora](https://docs.vectara.com/docs/api-reference/admin-apis/corpora)

- [OpenAPI](openapi/vectara-openapi.yml)
- [JSON Schema — Corpus](json-schema/vectara-corpus-schema.json)
- [JSON Structure — Corpus](json-structure/vectara-corpus-structure.json)
- [JSON-LD](json-ld/vectara-context.jsonld)
- [Naftiko Capability — Corpora](capabilities/corpora-corpora.yaml)

### Vectara Indexing API
Upload and index documents into a Vectara corpus using either structured Core indexing (`document_parts` with metadata) or unstructured file upload (PDF, DOCX, HTML, and more). Supports add, replace, and delete on documents.

**Human URL:** [https://docs.vectara.com/docs/api-reference/indexing-apis/indexing](https://docs.vectara.com/docs/api-reference/indexing-apis/indexing)

- [OpenAPI](openapi/vectara-openapi.yml)
- [JSON Schema — Document](json-schema/vectara-document-schema.json)
- [Naftiko Capability — Documents](capabilities/indexing-documents.yaml)

### Vectara Query API
Run semantic, keyword, and hybrid queries across one or more corpora with grounded generation, citations, reranking (customer reranker, MMR, chain, user function), and Hughes Hallucination Evaluation Model (HHEM) factual-consistency scoring.

**Human URL:** [https://docs.vectara.com/docs/api-reference/search-apis/search](https://docs.vectara.com/docs/api-reference/search-apis/search)

- [OpenAPI](openapi/vectara-openapi.yml)
- [JSON Schema — Query Request](json-schema/vectara-query-schema.json)
- [Naftiko Capability — Query](capabilities/query-query.yaml)

### Vectara Chat API
Multi-turn conversational interface over a Vectara corpus that maintains chat history and produces grounded, cited answers with optional streaming.

**Human URL:** [https://docs.vectara.com/docs/api-reference/chat-apis/chat-apis](https://docs.vectara.com/docs/api-reference/chat-apis/chat-apis)

### Vectara Agents API
Build and operate agents over Vectara corpora with reusable tools, MCP-compatible tool servers, planning, sessions, and grounded generation.

**Human URL:** [https://docs.vectara.com/docs/api-reference/agents-api/agents](https://docs.vectara.com/docs/api-reference/agents-api/agents)

- [OpenAPI](openapi/vectara-openapi.yml)
- [JSON Schema — Agent](json-schema/vectara-agent-schema.json)
- [Naftiko Capability — Agents](capabilities/agents-agents.yaml)

### Vectara OAuth 2.0 Token API
OAuth 2.0 client credentials flow used to exchange `client_id` + `client_secret` for a short-lived JWT (`expires_in: 1800`) used to call the REST API.

**Human URL:** [https://docs.vectara.com/docs/learn/authentication/oauth-2](https://docs.vectara.com/docs/learn/authentication/oauth-2)

- [Naftiko Capability — Tokens](capabilities/oauth2-tokens.yaml)

## Common Properties

- [Website](https://www.vectara.com/)
- [Developer Portal](https://docs.vectara.com/docs)
- [Documentation — REST API](https://docs.vectara.com/docs/rest-api/)
- [OpenAPI — upstream](https://docs.vectara.com/vectara-oas-v2.yaml)
- [SDK — Python](https://github.com/vectara/python-sdk)
- [SDK — TypeScript](https://github.com/vectara/typescript-sdk)
- [SDK — vectara-agentic (Python)](https://github.com/vectara/py-vectara-agentic)
- [SDK — LangChain Vectara](https://github.com/vectara/langchain-vectara)
- [Tool — Vectara MCP Server](https://github.com/vectara/vectara-mcp)
- [Tool — Vectara Ingest](https://github.com/vectara/vectara-ingest)
- [Tool — Vectara UI](https://github.com/vectara/vectara-ui)
- [Tool — React Search Widget](https://github.com/vectara/react-search)
- [Tool — React Chatbot Widget](https://github.com/vectara/react-chatbot)
- [Tool — Stream Query Client](https://github.com/vectara/stream-query-client)
- [Tool — Create UI Generator](https://github.com/vectara/create-ui)
- [Tool — Vectara Answer Reference App](https://github.com/vectara/vectara-answer)
- [Tool — Open RAG Evaluation](https://github.com/vectara/open-rag-eval)
- [Tool — Hallucination Leaderboard (HHEM)](https://github.com/vectara/hallucination-leaderboard)
- [Tool — Agent Skills](https://github.com/vectara/agent-skills)
- [Samples — Getting Started](https://github.com/vectara/getting-started)
- [Samples — Example Notebooks](https://github.com/vectara/example-notebooks)
- [Samples — Design Patterns](https://github.com/vectara/design-patterns)
- [GitHub Organization](https://github.com/vectara)
- [Blog](https://www.vectara.com/blog)
- [Pricing](https://www.vectara.com/pricing)
- [Status Page](https://status.vectara.com/)
- [Support](https://docs.vectara.com/docs/support)
- [Privacy Policy](https://vectara.com/legal/privacy-policy/)
- [Terms of Service](https://vectara.com/legal/terms-of-service/)
- [LinkedIn](https://www.linkedin.com/company/vectara/)
- [Change Log / Release Notes](https://docs.vectara.com/docs/release-notes)
- [Integrations](https://docs.vectara.com/docs/integrations)
- [llms.txt](https://docs.vectara.com/llms.txt)

## Integrations

LangChain, LlamaIndex, Airbyte, Unstructured, Slack, Snowflake, AWS, Google Cloud, Microsoft Azure, Model Context Protocol (MCP).

## Solutions

- Enterprise Search over Private Data
- Customer Support Assistants
- Internal Knowledge Bases
- Conversational Product Documentation
- Compliance and Policy Question Answering
- Sales and Marketing Content Discovery
- Hallucination-Scored RAG Pipelines
- Agentic Workflows over Corporate Data

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Vectara REST API v2](openapi/vectara-openapi.yml)

### JSON Schema

- [Vectara Corpus](json-schema/vectara-corpus-schema.json)
- [Vectara Document](json-schema/vectara-document-schema.json)
- [Vectara Query Request](json-schema/vectara-query-schema.json)
- [Vectara Agent](json-schema/vectara-agent-schema.json)

### JSON Structure

- [Vectara Corpus Structure](json-structure/vectara-corpus-structure.json)

### JSON-LD

- [Vectara Context](json-ld/vectara-context.jsonld)

### Examples

- [Create Corpus](examples/vectara-create-corpus-example.json)
- [Add Document (Core)](examples/vectara-add-document-example.json)
- [Query Corpus with Grounded Generation](examples/vectara-query-corpus-example.json)
- [Obtain OAuth 2.0 Token](examples/vectara-oauth-token-example.json)

### Naftiko Capabilities

- [Corpora](capabilities/corpora-corpora.yaml)
- [Indexing — Documents](capabilities/indexing-documents.yaml)
- [Query](capabilities/query-query.yaml)
- [Agents](capabilities/agents-agents.yaml)
- [OAuth 2.0 Tokens](capabilities/oauth2-tokens.yaml)

### Spectral Rules

- [Vectara Rules](rules/vectara-rules.yml)

### Vocabulary

- [Vectara Vocabulary](vocabulary/vectara-vocabulary.yml)

### Commercial & Operational

- [Plans (API Commons Plans 0.1)](plans/vectara-plans-pricing.yml)
- [Rate Limits (API Commons 0.1)](rate-limits/vectara-rate-limits.yml)
- [FinOps (FOCUS-aligned)](finops/vectara-finops.yml)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
