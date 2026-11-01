# Vectara

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

**Areas:** Artificial Intelligence · Agents · Corpora · Embeddings · Enterprise Search · Generative AI · Grounded Generation · Hallucination Detection · LLM · MCP · RAG · Retrieval

## Vectara on APIs.io

Everything profiled for Vectara is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vectara/](https://apis.io/providers/vectara/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Vectara Chat API](https://apis.io/apis/vectara/vectara-chat-api/) — Multi-turn conversational interface over a Vectara corpus that maintains chat history and produces grounded, cited answers with optional streaming.
- [Vectara OAuth 2.0 Token API](https://apis.io/apis/vectara/vectara-oauth2-api/) — OAuth 2.0 client credentials flow used to obtain a short-lived JWT for calling the Vectara REST API.
- [Vectara Agents API](https://apis.io/apis/vectara/vectara-agents-api/) — Build and operate agents over Vectara corpora.
- [Vectara Authentication API](https://apis.io/apis/vectara/vectara-authentication-api/) — OAuth 2.0 client credentials flow for obtaining JWT tokens.
- [Vectara Corpora API](https://apis.io/apis/vectara/vectara-corpora-api/) — Create, list, update, and delete corpora that hold indexed documents.
- [Vectara Documents API](https://apis.io/apis/vectara/vectara-documents-api/) — Upload, index, retrieve, update, and delete documents in a corpus.
- [Vectara Pipelines API](https://apis.io/apis/vectara/vectara-pipelines-api/) — Manage pipelines and inspect pipeline runs.
- [Vectara Query API](https://apis.io/apis/vectara/vectara-query-api/) — Semantic, keyword, and hybrid queries with optional grounded generation.
- [Vectara Tools API](https://apis.io/apis/vectara/vectara-tools-api/) — Manage tools and tool servers used by agents.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Vectara Agentic Access](https://apis.io/agentic-access/vectara/vectara-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Vectara Agent](https://apis.io/schemas/vectara/vectara-agent/)
- [Vectara Corpus](https://apis.io/schemas/vectara/vectara-corpus/)
- [Vectara Document](https://apis.io/schemas/vectara/vectara-document/)
- [Vectara Query Request](https://apis.io/schemas/vectara/vectara-query/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Vectara Corpus Structure](https://apis.io/json-structure/vectara/vectara-corpus-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Vectara Context](https://apis.io/jsonld/vectara/vectara-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Vectara Vocabulary](https://apis.io/vocabularies/vectara/vectara-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Vectara Add Document Example](https://apis.io/examples/vectara/vectara-add-document-example/)
- [Vectara Create Corpus Example](https://apis.io/examples/vectara/vectara-create-corpus-example/)
- [Vectara Oauth Token Example](https://apis.io/examples/vectara/vectara-oauth-token-example/)
- [Vectara Query Corpus Example](https://apis.io/examples/vectara/vectara-query-corpus-example/)

#### Collections (15)

Postman and Open Collection request collections.

- [Vectara REST API](https://apis.io/collections/vectara/open-vectara/)
- [Vectara REST Agents API](https://apis.io/collections/vectara/open-vectara-agents-api/)
- [Vectara REST Agents Authentication API](https://apis.io/collections/vectara/open-vectara-authentication-api/)
- [Vectara REST Agents Corpora API](https://apis.io/collections/vectara/open-vectara-corpora-api/)
- [Vectara REST Agents Documents API](https://apis.io/collections/vectara/open-vectara-documents-api/)
- [Vectara REST Agents Pipelines API](https://apis.io/collections/vectara/open-vectara-pipelines-api/)
- [Vectara REST Agents Query API](https://apis.io/collections/vectara/open-vectara-query-api/)
- [Vectara REST Agents Tools API](https://apis.io/collections/vectara/open-vectara-tools-api/)
- [Vectara REST Agents API](https://apis.io/collections/vectara/postman-vectara-agents-api/)
- [Vectara REST Agents Authentication API](https://apis.io/collections/vectara/postman-vectara-authentication-api/)
- [Vectara REST Agents Corpora API](https://apis.io/collections/vectara/postman-vectara-corpora-api/)
- [Vectara REST Agents Documents API](https://apis.io/collections/vectara/postman-vectara-documents-api/)
- [Vectara REST Agents Pipelines API](https://apis.io/collections/vectara/postman-vectara-pipelines-api/)
- [Vectara REST Agents Query API](https://apis.io/collections/vectara/postman-vectara-query-api/)
- [Vectara REST Agents Tools API](https://apis.io/collections/vectara/postman-vectara-tools-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Vectara — jsonschema rules](https://apis.io/rules/vectara/vectara-jsonschema-spectral-rules/)
- [Vectara API Rules](https://apis.io/rules/vectara/vectara-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Vectara Authentication](https://apis.io/security/vectara/vectara-authentication/)
- [Vectara Domain Security](https://apis.io/security/vectara/vectara-domain-security/)
- [Vectara Trust Center](https://apis.io/security/vectara/vectara-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Vectara Scopes](https://apis.io/scopes/vectara/vectara-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Vectara Plans Pricing](https://apis.io/plans/vectara/vectara-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Vectara Rate Limits](https://apis.io/rate-limits/vectara/vectara-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Vectara Finops](https://apis.io/finops/vectara/vectara-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.vectara.com/)
- [Documentation](https://docs.vectara.com/docs/rest-api/)
- [Pricing](https://www.vectara.com/pricing)
- [Support](https://docs.vectara.com/docs/support)
- [Changelog](https://docs.vectara.com/docs/release-notes)
- [Blog](https://www.vectara.com/blog)
- [Terms of service](https://vectara.com/legal/terms-of-service/)
- [Privacy policy](https://vectara.com/legal/privacy-policy/)
- [Status](https://status.vectara.com/)

## API Evangelist rating

**Kin Score 48.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 61.4 |
| Contract governance | 27.3 |
| Operational transparency | 42.1 |
| Developer ergonomics | 29.8 |
| Access clarity | 44.7 |

**Agent readiness 22.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 36.4** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vectara/](https://apis.io/providers/vectara/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vectara: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vectara/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
