---
status: unknown
attribution: jointly-developed
updated: 2026-09-07
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
  - SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions
  - SRC-2026-09-05-deepseek-pre-v0.6-survey
  - SRC-2026-09-05-gemini-pre-v0.6-survey
  - SRC-2026-09-05-glm-pre-v0.6-survey
  - SRC-2026-09-05-grok-pre-v0.6-survey
  - SRC-2026-09-05-qwen-pre-v0.6-survey
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

**(2026-09-06, `jointly-developed`, `status: working`)** The working decisions remove the count from the discussion rather than defining an exit. **v0.6 is explicitly not fixed to a product count**: the 12–16 recommendation "was useful as a way to force deeper R&D" but "is no longer treated as a hard product-count constraint," and v0.6 may grow if a genuinely distinct ontology is discovered. The replacement measure is that **v0.6 should be counted by conceptual experiments first, not only by SKU count**, with R&D units distinguished from storefront SKUs — one Tolerance Pair being one R&D unit and two SKUs.

This is a real advance for this question, though not the answer to it. It removes a number that could have been mistaken for a gate, and it names what would substitute — distinct ontology, differing Commerce roles, differing temperatures, relational possibility, system-level intervention, and resistance to a single visible generative formula. Those are **composition criteria for entering v0.6**, not conditions for leaving R&D.

**(2026-09-06, `llm-proposed`)** Five critiques recommend roughly 13–14 R&D units and 14–16 storefront SKUs, while three of five answer the forced question on capping by unit count with **no** — preferring per-unit admission standards to a number, which is the same move the working decisions make. More significant for this question: **all five name the same next experiment**, and it is not another composition or another critique. All five call for a live working storefront tested with unbriefed non-specialist visitors, and none proposes a further critique round.

That matters here because the pattern this question has been tracking now has a fourth data point. Two rounds returned `WORKING BUT NEEDS CORRECTION`, the third returned `READY WITH ONE REQUIRED CORRECTION` from six responses, and the fourth returns `READY WITH MINOR REVISIONS` from five. **The verdicts have improved across four rounds while the artifact has not changed state** — no v0.6 exists, and no transactional surface exists. Improving LLM verdicts on successive briefs are therefore not evidence of R&D readiness, and cannot serve as an exit condition. GLM states the underlying risk directly: that critique cycles produce pendulum aesthetics rather than discovered work.

The R&D-to-Catalog exit condition remains **unknown**. What the newest round supplies is a strong `llm-proposed` convergence on what would *begin* to constitute non-LLM evidence. See [[pre-v0.6-evaluation-round-2]].

## Related

- [[DEC-006-collection-before-catalog]]
- [[rnd-collection]]
- [[Q-002-first-collection-selection]] — Unlike the Collection v0.1 selection discussion, this question addresses when R&D ends.
- [[pre-v0.6-evaluation]]
- [[pre-v0.6-evaluation-round-2]] — The fourth round, and the source of the four-round verdict pattern recorded above.

## Sources

- [[SRC-2026-09-04-commerce-product-rnd-summary]] — [raw/conversations/2026-09-04-commerce-product-rnd-summary.md](../../raw/conversations/2026-09-04-commerce-product-rnd-summary.md). This source is a derivative summary rather than the original conversation transcript; it summarizes the 2026-09-03–04 brainstorming.
- [[SRC-2026-09-05-chatgpt-v0.6-rnd]] — [raw/conversations/conversation-20260905-0007.md](../../raw/conversations/conversation-20260905-0007.md). It proposes a lifecycle-focused v0.6 but records no user-confirmed exit condition.
- [[SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position]] — [raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md](../../raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md). A derivative LLM recommendation that explicitly says not to finalize v0.6 yet.
- [[SRC-2026-09-04-claude-pre-v0.6-rnd-position]], [[SRC-2026-09-04-deepseek-pre-v0.6-rnd-position]], [[SRC-2026-09-04-glm-pre-v0.6-rnd-position]], [[SRC-2026-09-04-grok-pre-v0.6-rnd-position]], [[SRC-2026-09-04-kimi-pre-v0.6-rnd-position]], and [[SRC-2026-09-04-qwen-pre-v0.6-rnd-position]] — six `llm-proposed` critiques; their shared prompt and independence are unverified.
- [[SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions]] — [raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md](../../raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md). A `jointly-developed` working-decision summary, `status: working`. It is a decision summary rather than a conversation transcript, and nothing in it is `user-confirmed`.
- [[SRC-2026-09-05-deepseek-pre-v0.6-survey]], [[SRC-2026-09-05-gemini-pre-v0.6-survey]], [[SRC-2026-09-05-glm-pre-v0.6-survey]], [[SRC-2026-09-05-grok-pre-v0.6-survey]], and [[SRC-2026-09-05-qwen-pre-v0.6-survey]] — five `llm-proposed` critiques under `raw/surveys/`. Their shared evaluation brief is not registered and does not match the working-decisions document's section numbering; despite an earlier filename date, their content places them after those working decisions. Evaluator independence is unverified.
