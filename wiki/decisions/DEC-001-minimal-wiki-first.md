---
status: confirmed
attribution: user-confirmed
updated: 2026-09-03
sources:
  - SRC-2026-09-03-llm-wiki-agent-prompt
---

# DEC-001 — Minimal Wiki First

## Status

accepted (2026-09-03)

## Context

The repository was empty, and the workspace contained none of the original OTHER GOODS material. The only source was one set of Wiki initialization instructions from the user. At the same time, the project was certain to produce many future LLM conversations and outputs.

## Decision

The judgment is `MINIMAL_WIKI_RECOMMENDED`. Do not create the entire taxonomy or product-specific pages in advance; create only pages with real content. Establish the raw / Wiki / schema layers and the ingestion workflow now.

## Why

1. With only one source to synthesize, the synthesis layer would effectively copy the original. Synthesis from a single source is a review signal, not knowledge.
2. With no recording system, future conversations would be lost just like the original conversation behind the first four product candidates. The system itself is therefore already necessary.
3. Empty placeholder pages tend to remain empty and make the Wiki appear to know more than it does.

## Alternatives Considered

- Return `WIKI_NOT_YET_NEEDED` and create nothing — rejected. Conversations are already being lost, so a minimal system is needed now.
- Return `WIKI_RECOMMENDED` and pre-create the full structure, including product, collection, experiment, audience, exhibition, commerce, brand, and technology directories — rejected. Empty structure is not maintained, and structure created too early constrains future thinking.

## Consequences

There are no product-specific pages, so product questions can currently be answered only at the list level in [[current-state]]. The structure will need revision as conversations accumulate. This is expected: the schema evolves with the project.

## Sources

- `SRC-2026-09-03-llm-wiki-agent-prompt` — `raw/documents/2026-09-03-llm-wiki-agent-prompt.md`

## Related

- [[index]] — Explains why directories such as `wiki/products/` do not yet appear in the index.
- [[overview]] — Shows the distinction between a decision about Wiki structure and a page about the work's subject matter.
