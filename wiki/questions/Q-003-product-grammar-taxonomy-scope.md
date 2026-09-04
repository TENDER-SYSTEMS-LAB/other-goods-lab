---
status: unknown
attribution: jointly-developed
updated: 2026-09-04
sources:
  - SRC-2026-09-04-commerce-product-rnd-summary
  - SRC-2026-09-04-gemini-collection-v0.4-survey
  - SRC-2026-09-04-claude-collection-v0.4-survey
  - SRC-2026-09-04-gemini-collection-v0.5-survey
  - SRC-2026-09-04-glm-collection-v0.5-survey
  - SRC-2026-09-04-grok-collection-v0.5-survey
  - SRC-2026-09-04-kimi-collection-v0.5-survey
---

# Q-003 — The Scope and Boundaries of the Product Grammar Taxonomy

## Question

How many Product Grammar taxonomy categories are appropriate in the end? Can one product belong to several Grammars at the same time? Are Physical Shipping / Packaging / Weight / Damage Product Grammars or Commerce Mechanics?

## Why it matters

[[DEC-007-ontology-before-commerce]] confirmed the two-layer structure of Product Ontology (Layer 1) and Commerce Collision (Layer 2), but did not confirm the contents of Layer 1. If its boundaries remain unclear, the problem rejected in DEC-007 — Commerce functions flowing into Grammar — will recur. Whether Physical Shipping / Packaging / Weight / Damage belong to either layer is precisely a boundary case.

## Current State

The current 14 Grammars (Irreversible, Non-standardizable, Location-bound, Shared-but-different, Boundaryless, Unrecorded, Repeatable-but-not-identical, Unassignable, Counterfactual / Unlived Possibility, Overabundant / Invisible, Unitized / Scale-distorted, Naming-dependent, Value-ambiguous, Identity-drifting) have been proposed, but remain `working`, and most names are `llm-proposed`. They must not be recorded as a confirmed taxonomy. There is also no membership rule yet for whether a product can belong to multiple Grammars.

**2026-09-04.** Both surveys judged the current taxonomy to be over-segmented. In Claude's words: “The current 25 are closer to labels retrofitted to 30 names than discovered classifications.” Claude argues that consolidation would reduce it to 11–12 categories, at which point the taxonomy would finally become a research tool.

It is also worth recording that a partial answer has emerged for one of this question's three subproblems: whether Physical Shipping / Packaging / Weight / Damage are Grammars or Commerce Mechanics. Both surveys proposed treating material, shipping, and damage as independent Grammars (Gemini's Formless Material; Claude's Perishable Immaterial and Byproduct). However, these are `llm-proposed` proposals, not confirmations.

**2026-09-04, v0.5 round.** Four further surveys proposed consolidated taxonomies: Gemini 5 categories, Grok 8, Kimi 9, GLM 11. Five categories appear in all four proposals under different names — referent drift, condition/irreversibility, perceptual threshold, process byproduct, and institutional phantom — with a sixth (commerce events as objects) in three of four. The convergence table is in [[v0.5-evaluation]] and [[product-grammar]].

Three things this changes for the question, none of them a resolution:

- **The answer to “how many” now has a plausible floor.** Six independent proposals across two rounds range from 5 to 12; none defends anything near 25. A five-or-six-category core with an optional periphery is the shape all six point at.
- **Claude's demotion proposal lost support.** Its v0.4 proposal to reclassify `Irreversible` as a background property is contradicted by all four v0.5 taxonomies, each of which keeps a condition/irreversibility grammar at top level.
- **The boundary subproblem moved.** Material, shipping, and damage now appear as top-level Grammars in every v0.5 proposal (Process Byproduct, Defect as Identity, Decaying Trace, Trace Phenomena). Two rounds of surveys have now answered this subproblem the same way — as Grammars, not Commerce Mechanics — but only as `llm-proposed` agreement, never as a user decision.

A newer objection cuts across the counting question entirely. All four v0.5 surveys report that the collection's generative formula is visible and that **the taxonomy supplies no rejection criterion** — it can label anything, so it cannot exclude anything. GLM's proposed instrument is not a category count but a test: *does a commerce mechanism do conceptual work that changes what the thing means?* If that is the right instrument, the size of the taxonomy is not this question's real content, and the decisive test sits in Layer 2. See [[Q-005-commerce-generative-vs-display]].

## Discussed Approaches

A format was proposed that records Product Grammar / Primary Commerce Collision / Secondary Commerce Collision separately for each product. The Primary/Secondary distinction may be a partial answer to the problem of multiple membership on the Commerce Collision side, but it is a structure for Commerce Collision; multiple membership in Grammar remains undecided. The poetic bias of Boundaryless / Counterfactual Grammars and the room for Ontology to extend toward what “products one does not want” indicates were identified as gaps in the taxonomy.

**2026-09-04.** Specific consolidation proposals were presented for the first time. The shared proposals are to absorb Scale-distorted into Unitization and consolidate the Shared-but-different family. The most structural proposal is Claude's: **demote Irreversible from a top-level Grammar and reclassify it as a common background property of other Grammars**. The point of divergence is Counterfactual — Gemini proposes DROP, while Claude proposes retaining it but replacing its instances. See [[v0.4-evaluation]] for the full list. None has been adopted.

## Related

- [[product-grammar]]
- [[DEC-007-ontology-before-commerce]] — Confirmed the two-layer structure but not this taxonomy itself.
- [[commerce-as-medium]]
- [[v0.4-evaluation]] — Detailed basis for the 2026-09-04 taxonomy consolidation proposals.
- [[v0.5-evaluation]] — The four further consolidation proposals and the five-category convergence.
- [[Q-005-commerce-generative-vs-display]] — A question newly raised by the v0.4 surveys alongside the taxonomy consolidation discussion.

## Sources

- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`. This source is a derivative summary rather than the original conversation transcript; it summarizes the 2026-09-03–04 brainstorming.
- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`. It is `llm-proposed`, and the original v0.4 evaluation prompt is not in the repository.
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`. It is `llm-proposed` and has the same provenance limitation described above.
- `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, `SRC-2026-09-04-kimi-collection-v0.5-survey` — the four v0.5 surveys under `raw/surveys/`. All `llm-proposed`; the v0.5 evaluation prompt is likewise not registered.
