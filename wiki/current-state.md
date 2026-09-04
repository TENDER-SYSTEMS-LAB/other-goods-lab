---
status: working
attribution: jointly-developed
updated: 2026-09-04
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
---

# Current State

Reference date: 2026-09-04.

## Current Definition

OTHER GOODS is an interactive conceptual-art project that explores the conceptual collision produced when a highly finished e-commerce system treats things that cannot ordinarily be considered products as normal merchandise. See [[overview]] for the full definition. The project has now moved beyond choosing the first Collection's product list and entered R&D: it is discovering Product Grammar through [[rnd-collection]].

## Confirmed Identity

- Project/store name: **OTHER GOODS**
- Customer-facing tagline: **A store for other kinds of goods.**
- Project statement seed: **Treating the unownable as merchandise.**

All three items have `status: confirmed` and `attribution: user-confirmed`. See [[DEC-003-other-goods-identity]] for the decision context.

## Current Direction

Following [[DEC-004-commerce-first]], **OTHER GOODS / Commerce** is being developed first as an independent work. Claude, Gemini, and Perplexcity evaluated 14 candidates, and, until then, the highest priority was to brainstorm the first Collection again with ChatGPT on the basis of that comparative material.

That brainstorming was actually conducted on 2026-09-03–04; `SRC-2026-09-04-commerce-product-rnd-summary` records it. As a result, the Collection expanded through v0.2 and v0.3. The current direction, following [[DEC-006-collection-before-catalog]], is to operate the Collection as an R&D Set rather than a final product list and to discover Product Grammar through the Product Ontology / Commerce Collision two-layer structure established by [[DEC-007-ontology-before-commerce]]. See [[rnd-collection]] for the complete candidate list and version-by-version changes.

R&D advanced to v0.4 (30 items) and received evaluations in a second survey round (Gemini and Claude). Both surveys judged it `WORKING BUT NEEDS CORRECTION`, but their prescriptions are opposed. See [[v0.4-evaluation]] for details.

Regarding product images, all three surveys—Gemini, GLM, and Grok—selected Option C: **do not use ASCII as a single global style; demote it to one renderer within a larger Representation System**. Their reasons differ. Gemini recognizes ASCII's structural metaphor but identifies risks of scalability and genre; GLM considers it structural only when actual store data is the material of its glyphs; Grok considers its conceptual necessity itself weak. The strong convergence is therefore not a justification for ASCII, but an architecture requiring a plural imaging policy rather than a single style. This is an `llm-proposed` hypothesis from the three LLMs, not a user decision. See [[product-image-system]] for details.

## Accepted Decisions

- [[DEC-001-minimal-wiki-first]] — recording system
- [[DEC-002-perfect-store-principle]] — formal quality standard for the work
- [[DEC-003-other-goods-identity]] — name and reference phrases
- [[DEC-004-commerce-first]] — current work scope
- [[DEC-005-no-ip-products]] — do not use products dependent on specific IP
- [[DEC-006-collection-before-catalog]] — discover Product Grammar through a Collection before expanding the Catalog
- [[DEC-007-ontology-before-commerce]] — put Product Ontology before Commerce Collision
  - [[DEC-007-ontology-before-commerce]] received a challenge from Claude's 2026-09-04 survey, but because the survey is `llm-proposed`, the decision remains valid. The unresolved challenge is tracked in [[Q-005-commerce-generative-vs-display]].

## Working Principles

- [[conceptual-contrast]] — focuses on the collision produced when a completely normal commercial system handles noncommercial objects (`status: working`, `attribution: user-confirmed`).
- [[progressive-displacement]] — when visitors feel they understand a rule, that same rule leads them to discover a different result (`status: working`; the principle is `user-confirmed`, while the English name is `llm-proposed`).
- The work's use should be immediately understandable, while interpretation should not close easily. The `Low Floor, High Ceiling` structure is an LLM proposal, not a confirmed user decision.
- Products must not become a collection of "pretty sentences" (`status: confirmed`, `attribution: user-confirmed`).
- Different kinds of products must stand alongside one another in the Collection (`status: confirmed`, `attribution: user-confirmed`).
- Virtual persona evaluation is a supplementary tool and does not replace actual visitors (`status: confirmed`, `attribution: user-confirmed`).

The v0.4 surveys applied disconfirming pressure to two hypotheses. (1) The hypothesis that the Product Grammar taxonomy is a valid research tool: both surveys judged it over-segmented. (2) The hypothesis that [[progressive-displacement]] works in the current Collection: Claude noted that its emotional temperature is uniform, making it physically unable to operate. Both are `llm-proposed` disconfirmations, not confirmed disconfirmations.

The three Product Image System surveys raised a separate repeated risk. All three noted that a single ASCII treatment could quickly be learned as one formula in a 100–200-item Catalog, classified as the net.art or terminal genre, and flatten different products into the same digital material. This is not an actual visitor observation but a design hypothesis to test in prototypes.

## Active Product Candidates

Candidates expanded from 14 in v0.1, through 14 in v0.2 and 26 in v0.3, to 30 in v0.4. The v0.4 list was reconstructed from the two surveys because the original prompt is not in the repository; it appears in [[v0.4-evaluation]]. Record the five products both surveys placed in the Top—02 `Yesterday`, 04 `The First Typo in a New Notebook`, 09 `The Upper-Right Corner Dented During Shipping`, 22 `Warmth Left on a Park Bench`, and 28 `The Room Before Calling It “Home”`—as well as the four both placed in the Bottom (08, 15, 21, and 24). Also record that the two surveys reached directly opposite judgments on 05, 07, and 10. All are `llm-proposed`; the user has not yet selected any.

The complete list and version-by-version changes are in [[rnd-collection]]. This document does not repeat the candidate list; it only records the current disposition of the four initial candidates directly supplied by the user. All have `attribution: user-originated`.

- `Yesterday` — retained in every version from v0.1 through v0.3. `status: working`.
- `Summer at Sixteen` — retained in every version from v0.1 through v0.3. `status: working`.
- `The Smell After Rain on April 21` — a shared weakness was noted in the v0.1 evaluation: it was too close to a perfume or diffuser product. It was removed from v0.2 onward. The source does not say whether it is permanently excluded. `status: deferred`.
- `Sunlight at 4 p.m. on June 13` — not included in the v0.1 evaluation set and does not appear in later versions. The source does not explain why. `status: unknown`.

`The First Time Reading Episode 1 of Tower of God`, which was evaluated alongside the initial Collection v0.1 survey, has `status: rejected`: under [[DEC-005-no-ip-products]], it was removed for dependence on specific IP and replaced with `The Last Ten Minutes Watched Without Knowing the Ending`.

The original proposers of the other ten v0.1 candidates, apart from the first four, cannot be identified from the registered survey responses alone. See [[Q-002-first-collection-selection]] for the evaluation comparison and attribution limits.

[[rnd-collection]] explains why individual product pages do not yet exist.

## Deferred Directions

- [[time-as-currency]] — blockchain-based internal currency, `TIME` units, real-time value fluctuation
- [[other-goods-as-entity]] — anonymous artist persona, GitHub·Instagram·YouTube world-building, subsequent services
- Services other than Commerce, including Delivery, Markets, and Maps

These items were not discarded; they are deferred outside the current scope under [[DEC-004-commerce-first]].

## Open Questions

- [[Q-001-comprehensibility-vs-mystery]]
- [[Q-002-first-collection-selection]] — the “next brainstorming” item was partly carried out in `SRC-2026-09-04-commerce-product-rnd-summary`.
- [[Q-003-product-grammar-taxonomy-scope]]
- [[Q-004-rnd-collection-exit-condition]]
- [[Q-005-commerce-generative-vs-display]] — an unresolved challenge to the confirmed decision [[DEC-007-ontology-before-commerce]].
- [[Q-006-post-purchase-behavior]]
- The open question in [[product-image-system]] — can several renderers be bound into one store policy without closing them into a new style taxonomy?
- Which products should constitute the first Collection, and which commerce function should be primary for each product?
- Does actual payment and checkout strengthen or weaken the concept?
- What does the visitor actually receive or own?
- How should price, inventory, shipping, and return rules be set for each product?

The following are open questions from §16 of `SRC-2026-09-04-commerce-product-rnd-summary` that do not yet have separate question pages.

- How many Product Ontology candidates should be added to reduce the Commerce-native bias?
- What should the ratio of emotional products to dry products be?
- How should the poetic bias of Grammars such as Boundaryless and Counterfactual be made concrete?
- How can “products one does not want” extend Ontology?
- What should be the minimum strength of a Long-tail product during Catalog expansion?
- What should be measured in actual visitor testing?

## Current Priorities

The following are not confirmed decisions, but `attribution: llm-proposed` proposals from §17 of `SRC-2026-09-04-commerce-product-rnd-summary`.

1. Generate 15–20 new candidates beginning from Product Ontology.
2. Compose R&D Collection v0.4 (25–30 items), recording ten fields for each product: Product Grammar, Primary/Secondary Commerce Collision, Intrinsic Strength, Commerce Dependency, Accessibility, Freshness, Residue, Main Risk, and Collection Role.
3. Develop 8–10 representative products to the Product Page level.
4. Then determine whether to expand the Catalog.

2026-09-04 — Before v0.5, the two surveys proposed resolving the following: reduce emotional bias (shared); determine the proportion of Commerce-generative products ([[Q-005-commerce-generative-vs-display]]); consolidate the Grammar taxonomy ([[Q-003-product-grammar-taxonomy-scope]]); design the post-purchase experience ([[Q-006-post-purchase-behavior]]); and decide the site structure, including whether to control viewing order. All are `llm-proposed` proposals that the user has not yet selected.

On the same day, the three Product Image System surveys' shared next step was not to confirm a single ASCII approach, but to build comparative prototypes: an ASCII stress test for formless products; several-renderer comparisons of the same product; and visitor testing of a mixed-policy Catalog inside a normal Commerce shell. Detailed implementation and ordering remain unadopted and are organized in [[product-image-system]].

## Recently Changed

- 2026-09-04 — Ingested three Product Image System surveys. Synthesized into [[product-image-system]] the 3/3 convergence against global ASCII and for a higher-level Representation System, five repeated risks, six alternative system families, and a prototype gate. No new decision.
- 2026-09-04 — Ingested two v0.4 surveys. Candidates: 26 → 30; two new questions (Q-005 and Q-006); recorded an unresolved challenge in [[DEC-007-ontology-before-commerce]].
- 2026-09-04 — Ingested the first Commerce Product R&D. The Collection expanded through v0.2/v0.3 (4 → 26 candidates); confirmed three decisions (DEC-005/006/007); introduced the Product Ontology vs. Commerce Collision two-layer frame; discarded the Commerce-function-centered Grammar frame.
- 2026-09-03 — Ingested the Claude, Gemini, and Perplexcity Collection v0.1 surveys. Compared the three surveys as `llm-proposed` and organized the next ChatGPT brainstorming agenda in [[Q-002-first-collection-selection]].
- 2026-09-03 — Ingested the original brainstorming conversation. Resolved the existing provenance gap. Promoted the Perfect Store Principle, OTHER GOODS identity, Commerce-first scope, and Progressive Displacement principle.
- 2026-09-03 — Initialized the Wiki.

## Sources

- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`. An `llm-proposed` survey. It recognizes ASCII's structural fit but proposes a larger Representation System instead of a global style.
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`. An `llm-proposed` survey. It explicitly states that it relied on text descriptions rather than viewing actual pixels.
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`. An `llm-proposed` survey. It judges ASCII's conceptual necessity to be weak.
- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`. An `llm-proposed` survey. The original v0.4 evaluation prompt (the 30-item list and evaluation criteria) is not in the repository.
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`. An `llm-proposed` survey. It shares the same limitation of the missing original prompt.
- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`. A derivative summary, not a conversation transcript; if the original conversation is separately preserved, its provenance takes precedence.
- `SRC-2026-09-03-chatgpt-brainstorming` — `raw/conversations/ChatGPT-brain-storming-20260903-2252.md`
- `SRC-2026-09-03-claude-collection-survey` — `raw/surveys/2026-09-03-claude-collection-survey.md`
- `SRC-2026-09-03-gemini-collection-survey` — `raw/surveys/2026-09-03-gemini-collection-survey.md`
- `SRC-2026-09-03-perplexcity-collection-survey` — `raw/surveys/2026-09-03-perplexcity-collection-survey.md`
- `SRC-2026-09-03-llm-wiki-agent-prompt` — `raw/documents/2026-09-03-llm-wiki-agent-prompt.md`
