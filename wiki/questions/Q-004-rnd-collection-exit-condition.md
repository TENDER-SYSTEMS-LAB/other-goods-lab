---
status: unknown
attribution: jointly-developed
updated: 2026-09-05
sources:
  - SRC-2026-09-04-commerce-product-rnd-summary
  - SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position
  - SRC-2026-09-05-chatgpt-v0.6-rnd
  - SRC-2026-09-04-claude-pre-v0.6-rnd-position
  - SRC-2026-09-04-deepseek-pre-v0.6-rnd-position
  - SRC-2026-09-04-glm-pre-v0.6-rnd-position
  - SRC-2026-09-04-grok-pre-v0.6-rnd-position
  - SRC-2026-09-04-kimi-pre-v0.6-rnd-position
  - SRC-2026-09-04-qwen-pre-v0.6-rnd-position
---

# Q-004 — When Does the R&D Collection End and Move to the Catalog Stage?

## Question

What determines that Product Grammar has become “sufficiently stable”? What are the exit conditions for the R&D Collection?

## Why it matters

[[DEC-006-collection-before-catalog]] makes Catalog expansion conditional on this condition (“after Product Grammar has become sufficiently stable”). If the condition is not defined, R&D risks continuing indefinitely or ending arbitrarily. The question of the minimum strength of long-tail products during Catalog expansion is also contingent on this condition. Further, because the density of a real commercial service required by [[DEC-002-perfect-store-principle]] cannot be achieved without Catalog scale, this question also ultimately determines when that principle can be realized.

## Current State

The exit conditions have not been defined. A v0.4 configuration of 25–30 products and elaboration of 8–10 representative products have been proposed as the next stage, but there is no account of what must then be fulfilled to proceed to the Catalog.

## Discussed Approaches

The sole next stage discussed is an R&D plan (retain the 8–10 strong candidates from v0.3; add 15–20 new candidates beginning from Product Ontology; form a v0.4 of about 25–30 products; record each product's Product Grammar / Commerce Collision / evaluation axes; develop 8–10 representative products to Product Page level; stabilize Product Grammar; then expand to a Catalog of 100–200 SKUs), and it is `llm-proposed`. It is a plan for proceeding, not exit conditions themselves.

**(2026-09-05)** A later conversation proposed redefining v0.6 as a 16-item Deep R&D Set whose purpose is to prove that strong products survive the full commercial lifecycle. This is more testable than another title-generation round, but it still supplies a next-stage experiment rather than a Catalog exit condition. The size, composition, and lifecycle gate are `llm-proposed` and unadopted.

A derivative pre-v0.6 position note narrows this into a version-entry sequence: external critique → naming principle → moral-residue test → decision on `What Payment Cannot Undo` → Product Behavior Sheet fields → composition of v0.6. It gives a gate for beginning v0.6, not for ending the R&D Collection or expanding to the Catalog.

**(2026-09-05, `llm-proposed`)** The six critiques give 6/6 qualified support for 12–16 as a temporary R&D unit and 6/6 warning that it is neither Catalog density nor an exit condition. Reusable mechanics/default policies and human testing are proposals for the next experiment, not gates. The R&D-to-Catalog exit condition remains unknown.

## Related

- [[DEC-006-collection-before-catalog]]
- [[rnd-collection]]
- [[Q-002-first-collection-selection]] — Unlike the Collection v0.1 selection discussion, this question addresses when R&D ends.
- [[pre-v0.6-evaluation]]

## Sources

- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`. This source is a derivative summary rather than the original conversation transcript; it summarizes the 2026-09-03–04 brainstorming.
- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`. It proposes a lifecycle-focused v0.6 but records no user-confirmed exit condition.
- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`. A derivative LLM recommendation that explicitly says not to finalize v0.6 yet.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
