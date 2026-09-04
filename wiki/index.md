---
status: working
attribution: llm-synthesis
updated: 2026-09-05
sources:
  - SRC-2026-09-03-llm-wiki-agent-prompt
  - SRC-2026-09-03-chatgpt-brainstorming
  - SRC-2026-09-03-claude-collection-survey
  - SRC-2026-09-03-gemini-collection-survey
  - SRC-2026-09-03-perplexcity-collection-survey
  - SRC-2026-09-04-commerce-product-rnd-summary
  - SRC-2026-09-04-gemini-collection-v0.4-survey
  - SRC-2026-09-04-claude-collection-v0.4-survey
  - SRC-2026-09-04-gemini-product-image-system-survey
  - SRC-2026-09-04-glm-product-image-system-survey
  - SRC-2026-09-04-grok-product-image-system-survey
  - SRC-2026-09-04-gemini-collection-v0.5-survey
  - SRC-2026-09-04-glm-collection-v0.5-survey
  - SRC-2026-09-04-grok-collection-v0.5-survey
  - SRC-2026-09-04-kimi-collection-v0.5-survey
  - SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position
  - SRC-2026-09-05-chatgpt-v0.6-rnd
  - SRC-2026-09-04-claude-pre-v0.6-rnd-position
  - SRC-2026-09-04-deepseek-pre-v0.6-rnd-position
  - SRC-2026-09-04-glm-pre-v0.6-rnd-position
  - SRC-2026-09-04-grok-pre-v0.6-rnd-position
  - SRC-2026-09-04-kimi-pre-v0.6-rnd-position
  - SRC-2026-09-04-qwen-pre-v0.6-rnd-position
---

# OTHER GOODS Wiki Index

This is the Wiki's working content catalog. Excluding the index itself, every Wiki page appears exactly once under its type using `link + one-line summary + status, when present + updated date`. Do not remove an entry unless its page is deleted. When a page's summary, status, or updated date changes, update this catalog in the same task.

## Routing

| Information to organize | Read or update first |
|---|---|
| Overall definition and central principles of the project | [[overview]] |
| Latest snapshot of decisions, current scope, and priorities | [[current-state]] |
| An idea that develops across several areas | Relevant `wiki/concepts/` page |
| A choice explicitly decided by the user and its rationale | Relevant `wiki/decisions/` page |
| An unanswered question that remains under review | Relevant `wiki/questions/` page |
| A set of product candidates and version-by-version changes or evaluations | Relevant `wiki/collections/` page |
| Chronological record of ingestion, queries, linting, and operational changes | Append to [[log]] |
| A new original and its hash or ingestion status | [Raw Source Index](../raw/sources.md) |

Before creating a page, check this catalog to see whether an existing page can be extended. Never classify `llm-proposed` material as a decision without explicit user confirmation.

## Core

- [[overview]] — Definition, identity, central question, and principles of the work · `working` (2026-09-04)
- [[current-state]] — Latest snapshot of confirmed decisions, current scope, candidates, unresolved questions, and priorities · `working` (2026-09-05)

## Concepts

- [[commerce-as-medium]] — Uses the full set of e-commerce rules, including price, inventory, search, checkout, and shipping, as the work's medium · `working` (2026-09-05)
- [[conceptual-contrast]] — Collision between a normal commercial system and things that cannot be products · `working` (2026-09-03)
- [[progressive-displacement]] — Visitor experience of discovering unfamiliar outcomes after becoming familiar with a rule · `working` (2026-09-05)
- [[product-grammar]] — Current 14-part taxonomy plus unadopted consolidation and new-territory proposals · `working` (2026-09-05)
- [[product-image-system]] — Hypothesis that places ASCII and other renderers under one store representation policy · `hypothesis` (2026-09-04)
- [[time-as-currency]] — Blockchain-based `TIME` currency and changing-value direction · `deferred` (2026-09-03)
- [[other-goods-as-entity]] — Organizational and system world in which OTHER GOODS exists independently of an artist · `deferred` (2026-09-03)

## Collections

- [[rnd-collection]] — Candidates through current v0.5 plus unadopted pre-v0.6 discussion and six-critique synthesis · `working` (2026-09-05)
- [[pre-v0.6-evaluation]] — Comparison of six LLM critiques of the unadopted pre-v0.6 position, including forced-decision splits and candidate dispositions · `working` (2026-09-05)
- [[v0.4-evaluation]] — Comparison of the Gemini and Claude surveys of the 30-item R&D Collection v0.4 · `working` (2026-09-04)
- [[v0.5-evaluation]] — Comparison of the Gemini, GLM, Grok, and Kimi surveys of the 24-item R&D Collection v0.5 · `working` (2026-09-04)

## Decisions

- [[DEC-001-minimal-wiki-first]] — Began with a minimal Wiki structure instead of expanding an empty taxonomy · `confirmed` (2026-09-03)
- [[DEC-002-perfect-store-principle]] — Build the store's technical, visual, and usability quality to the level of a real commercial service · `confirmed` (2026-09-03)
- [[DEC-003-other-goods-identity]] — Confirmed the project name, customer-facing tagline, and statement seed · `confirmed` (2026-09-03)
- [[DEC-004-commerce-first]] — Prioritize OTHER GOODS / Commerce as the first standalone work · `confirmed` (2026-09-03)
- [[DEC-005-no-ip-products]] — Exclude products that depend on external IP such as specific works or characters · `confirmed` (2026-09-04)
- [[DEC-006-collection-before-catalog]] — Discover Product Grammar through an R&D Collection before expanding the Catalog · `confirmed` (2026-09-04)
- [[DEC-007-ontology-before-commerce]] — Generate product ideas from Product Ontology before applying Commerce functions · `confirmed` (2026-09-04)

## Open Questions

- [[Q-001-comprehensibility-vs-mystery]] — Balance between immediately understandable use and lasting interpretive depth · `unknown` (2026-09-04)
- [[Q-002-first-collection-selection]] — How to compare evaluations of the first Collection and narrow it to a final composition · `unknown` (2026-09-04)
- [[Q-003-product-grammar-taxonomy-scope]] — Where to place the scope and boundaries of the Product Grammar taxonomy · `unknown` (2026-09-05)
- [[Q-004-rnd-collection-exit-condition]] — When to end the R&D Collection and move to the Catalog stage · `unknown` (2026-09-05)
- [[Q-005-commerce-generative-vs-display]] — Whether Commerce amplifies already strong objects or produces new ontologies · `unknown` (2026-09-05)
- [[Q-006-post-purchase-behavior]] — What changes after checkout and how a lifecycle sheet should test it · `unknown` (2026-09-05)
- [[Q-007-product-naming-register]] — How to balance register fidelity with the user's objection to over-technical naming · `unknown` (2026-09-05)
- [[Q-008-product-or-transaction]] — Whether the artwork's atomic unit is a product or transaction and whether real money moves · `unknown` (2026-09-05)

## Activity

- [[log]] — Append-only history of ingestion, queries, linting, decisions, and maintenance (2026-09-05)

## Repository Control

- [README](../README.md) — Public overview of the work and repository; canonical English entry point (2026-09-05)
- [AGENTS](../AGENTS.md) — Reading, language, ingestion, verification, institutional Git identity, and model-routing rules for agents (2026-09-05)
- [Schema](../schema.md) — Page taxonomy, status, attribution, provenance, language, and maintenance rules (2026-09-04)
- [Raw README](../raw/README.md) — How to add and preserve original source material, including the original-language exception (2026-09-05)
- [Raw Source Index](../raw/sources.md) — IDs, paths, hashes, and ingestion status for every raw source (2026-09-05)

## Page Creation Gates

- Create `wiki/products/` only when 8–10 representative products are developed to Product Page depth. Until then, record candidates and version changes in [[rnd-collection]].
- Continue tracking post-purchase experience in [[Q-006-post-purchase-behavior]] rather than creating an independent concept page.
- Do not create pages for experiments, audience research, exhibitions, brand, or technology until substantive material begins to develop independently.
- Do not duplicate a per-source raw catalog here. Use the [Raw Source Index](../raw/sources.md) as the single registry.
