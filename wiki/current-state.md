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
  - SRC-2026-09-04-gemini-collection-v0.5-survey
  - SRC-2026-09-04-glm-collection-v0.5-survey
  - SRC-2026-09-04-grok-collection-v0.5-survey
  - SRC-2026-09-04-kimi-collection-v0.5-survey
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

R&D then moved to v0.5, and this is the current version. **v0.5 is the first version to shrink: 30 → 24 items.** Nine v0.4 candidates were removed, including all four that both v0.4 surveys had placed in their Bottom 8, and three were added — `17,400 Hz`, `Unit 12B, Unoccupied`, and `First 12 Sheets Discarded Before Printing`. Two formal changes arrived with it and are explained by no registered source: the product titles are now English rather than translated Korean, and prices are in dollars rather than won. A third survey round of four models (Gemini, GLM, Grok, Kimi) evaluated v0.5, and **all four returned `WORKING BUT NEEDS CORRECTION`** — the same verdict as the v0.4 round. See [[v0.5-evaluation]] for the full comparison and [[rnd-collection]] for the version history.

Two consecutive rounds returning the same verdict is itself a signal for [[Q-004-rnd-collection-exit-condition]]: swapping candidates is not moving the Collection toward a “ready” assessment. What changed instead is where the surveys locate the problem. In v0.4 the correction concerned *which products exist*; in v0.5 all four locate it in *what the store does after the product page*, and all four name building the transaction and post-purchase layer as the single thing to do before v0.6. This is `llm-proposed` convergence, not a user decision.

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

The v0.5 surveys added two further `llm-proposed` disconfirmations, both directed at the method rather than at individual products.

1. **The generative formula is visible and has no rejection criterion.** All four independently report that a title of the form “ordinary phenomenon + condition or count” can be produced for almost anything, so the current taxonomy can label everything and therefore exclude nothing. GLM proposes the only concrete instrument — *does a commerce mechanism do conceptual work that changes what the thing means?* — which is unadopted and would bear on [[DEC-007-ontology-before-commerce]] through [[Q-005-commerce-generative-vs-display]].
2. **A second bias may be replacing the first.** All four warn that the correction added cold objects rather than discriminating among warm ones, and that a store of 200 dry conceptual titles is as reducible as a store of 200 memory fragments. GLM's version of the risk is that warm/cold alternation itself becomes the displacement formula; this qualifies Claude's “emotional betrayal” constraint in [[progressive-displacement]].

The three Product Image System surveys raised a separate repeated risk. All three noted that a single ASCII treatment could quickly be learned as one formula in a 100–200-item Catalog, classified as the net.art or terminal genre, and flatten different products into the same digital material. This is not an actual visitor observation but a design hypothesis to test in prototypes.

## Active Product Candidates

Candidates expanded from 14 in v0.1, through 14 in v0.2, 26 in v0.3, and 30 in v0.4, then contracted to **24 in v0.5**, the current version. The v0.4 and v0.5 lists were both reconstructed from their surveys because neither original prompt is in the repository; they appear in [[v0.4-evaluation]] and [[v0.5-evaluation]].

From the v0.4 round, record the five products both surveys placed in the Top—02 `Yesterday`, 04 `The First Typo in a New Notebook`, 09 `The Upper-Right Corner Dented During Shipping`, 22 `Warmth Left on a Park Bench`, and 28 `The Room Before Calling It “Home”`—as well as the four both placed in the Bottom (08, 15, 21, and 24), and the directly opposite judgments on 05, 07, and 10.

From the v0.5 round, six products appear in all four Top 8 lists: **02 `Yesterday`, 04 `First Typo in a New Notebook`, 05 `First Canceled Order`, 08 `Upper-Right Corner, Dented in Transit`, 22 `17,400 Hz`, and 23 `Unit 12B, Unoccupied`**. Two more appear in three of four: 07 `Day After the Return Window Closed` and 24 `First 12 Sheets Discarded Before Printing`. Only **11 `Wrong-Turn Alley`** was placed in the Bottom by all four. This is a far stronger consensus than v0.4 produced, and the surveys still disagree sharply on 01, 14, 15, 16, 17, 19, and 21 — see [[v0.5-evaluation]].

Note one dependency: the three products added in v0.5 are near-verbatim instantiations of example objects Claude proposed in its v0.4 survey, and all four v0.5 surveys rate that new territory as the collection's most valuable. The strongest-rated material in the current version therefore rests on one `llm-proposed` source.

All of the above is `llm-proposed`; the user has not yet selected any product.

The complete list and version-by-version changes are in [[rnd-collection]]. This document does not repeat the candidate list; it only records the current disposition of the four initial candidates directly supplied by the user. All have `attribution: user-originated`.

- `Yesterday` — retained in every version from v0.1 through v0.5, and placed in the Top by every survey in both the v0.4 and v0.5 rounds — six of six. `status: working`.
- `Summer at Sixteen` — retained in every version through v0.5, where it appears as `Summer, Age 16`. Three of the four v0.5 surveys place it at or near the Bottom; GLM alone defends it, arguing its grammar is top-tier and only its referent is clichéd. `status: working`.
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
- [[Q-006-post-purchase-behavior]] — no longer a single-source question; four v0.5 surveys now address it and split on whether the field should be mandatory for every product.
- [[Q-007-product-naming-register]] — in what register products should be named, and whether the tested “driest name” principle survives. New on 2026-09-04.
- The open question in [[product-image-system]] — can several renderers be bound into one store policy without closing them into a new style taxonomy?
- **Price as a conceptual surface.** GLM's v0.5 survey names this the project's most dangerous blind spot: price is treated everywhere as a display field and never as conceptual material, yet at catalog scale arbitrary prices will read as arbitrary. Single-source and `llm-proposed`; no page created.
- **What language the store's products are named in.** v0.5 switched to English titles and dollar prices with no registered explanation.
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

2026-09-04, v0.5 round. The four surveys converge on a different next step from the one above: **build the transaction and post-purchase layer, not more product names.** They differ only in scope — design the full post-purchase flow for exactly one abstract product (Gemini), wire the complete transaction loop including real prices, confirmation, a six-month order-history view, and working returns for the eight strongest (GLM), or write the complete post-purchase path for every retained product and discard those it only turns into gimmicks (Grok, Kimi). Kimi adds a gate: do not expand past 30 products until the Commerce-Displayed share falls below 20%. All `llm-proposed` and unselected. See [[Q-006-post-purchase-behavior]].

On the same day, the three Product Image System surveys' shared next step was not to confirm a single ASCII approach, but to build comparative prototypes: an ASCII stress test for formless products; several-renderer comparisons of the same product; and visitor testing of a mixed-policy Catalog inside a normal Commerce shell. Detailed implementation and ordering remain unadopted and are organized in [[product-image-system]].

## Recently Changed

- 2026-09-04 — Ingested four Collection v0.5 surveys (Gemini, GLM, Grok, Kimi). Candidates: 30 → 24, the first contraction. Created [[v0.5-evaluation]] and [[Q-007-product-naming-register]]. Recorded the 4/4 verdict, a six-product agreed Top, the 4/4 criticism that the generative formula has no rejection criterion, the five-category grammar convergence, and the 4/4 shift of the correction from products to the post-purchase layer. Removed the single-source dependency on [[Q-006-post-purchase-behavior]]. No new decision.
- 2026-09-04 — Ingested three Product Image System surveys. Synthesized into [[product-image-system]] the 3/3 convergence against global ASCII and for a higher-level Representation System, five repeated risks, six alternative system families, and a prototype gate. No new decision.
- 2026-09-04 — Ingested two v0.4 surveys. Candidates: 26 → 30; two new questions (Q-005 and Q-006); recorded an unresolved challenge in [[DEC-007-ontology-before-commerce]].
- 2026-09-04 — Ingested the first Commerce Product R&D. The Collection expanded through v0.2/v0.3 (4 → 26 candidates); confirmed three decisions (DEC-005/006/007); introduced the Product Ontology vs. Commerce Collision two-layer frame; discarded the Commerce-function-centered Grammar frame.
- 2026-09-03 — Ingested the Claude, Gemini, and Perplexcity Collection v0.1 surveys. Compared the three surveys as `llm-proposed` and organized the next ChatGPT brainstorming agenda in [[Q-002-first-collection-selection]].
- 2026-09-03 — Ingested the original brainstorming conversation. Resolved the existing provenance gap. Promoted the Perfect Store Principle, OTHER GOODS identity, Commerce-first scope, and Progressive Displacement principle.
- 2026-09-03 — Initialized the Wiki.

## Sources

- `SRC-2026-09-04-gemini-collection-v0.5-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.5-survey.md`. An `llm-proposed` survey. It also raises the visual-output risk recorded in [[product-image-system]] and refers to two concept names absent from this repository.
- `SRC-2026-09-04-glm-collection-v0.5-survey` — `raw/surveys/2026-09-04-glm-collection-v0.5-survey.md`. An `llm-proposed` survey. The only source for the price blind spot and for the rejection-criterion test.
- `SRC-2026-09-04-grok-collection-v0.5-survey` — `raw/surveys/2026-09-04-grok-collection-v0.5-survey.md`. An `llm-proposed` survey.
- `SRC-2026-09-04-kimi-collection-v0.5-survey` — `raw/surveys/2026-09-04-kimi-collection-v0.5-survey.md`. An `llm-proposed` survey.

The v0.5 evaluation prompt behind all four is not in the repository, so the 24-item list, the three-way commerce classification, and the naming principle under test are known only through the responses.

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
