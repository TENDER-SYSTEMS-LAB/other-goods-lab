# Activity Log

This is a chronological record showing how the Wiki has changed. Do not modify past entries; append new records to the end of the document.

New entry titles use the format `## [YYYY-MM-DD] <type> | <title>`. Prefer one of `ingest`, `query`, `decision`, `lint`, or `maintenance` for the type. Record only meaningful work that leaves a result in the Wiki; divide detailed entries into `Sources`, `Created`, `Updated`, `Decisions`, `Open Questions`, and `Notes` only when needed. The initial entries below from 2026-09-03 through 2026-09-04 use the previous title format and were not revised retroactively under the append-only principle.

## 2026-09-03 — Wiki initialization and pilot ingest

### Source

- `SRC-2026-09-03-llm-wiki-agent-prompt` — `raw/documents/2026-09-03-llm-wiki-agent-prompt.md`

### Created

- `wiki/overview.md`
- `wiki/current-state.md`
- `wiki/index.md`
- `wiki/log.md`
- `wiki/concepts/commerce-as-medium.md`
- `wiki/decisions/DEC-001-minimal-wiki-first.md`
- `wiki/questions/Q-001-comprehensibility-vs-mystery.md`
- `schema.md`
- `AGENTS.md`
- `README.md`
- `raw/README.md`
- `raw/sources.md`

### Updated

none — initial creation.

### Decisions

- [[DEC-001-minimal-wiki-first]]

### Open Questions

- [[Q-001-comprehensibility-vs-mystery]]

### Schema changes

initial

### Notes

Intentionally not created: `wiki/products/`, placeholder pages, lint scripts, and RAG. The four product candidates (`The Smell After Rain on April 21`, `Sunlight at 4 p.m. on June 13`, `Yesterday`, and `Summer at Sixteen`) still existed only as list items in [[current-state]], without individual pages.

## 2026-09-03 — Brainstorming conversation ingest

### Source

- `SRC-2026-09-03-chatgpt-brainstorming` — `raw/conversations/ChatGPT-brain-storming-20260903-2252.md`

### Created

- `wiki/concepts/conceptual-contrast.md`
- `wiki/concepts/progressive-displacement.md`
- `wiki/concepts/time-as-currency.md`
- `wiki/concepts/other-goods-as-entity.md`
- `wiki/decisions/DEC-002-perfect-store-principle.md`
- `wiki/decisions/DEC-003-other-goods-identity.md`
- `wiki/decisions/DEC-004-commerce-first.md`

### Updated

- `raw/sources.md`
- `raw/README.md`
- `README.md`
- `wiki/index.md`
- `wiki/overview.md`
- `wiki/current-state.md`
- `wiki/concepts/commerce-as-medium.md`
- `wiki/questions/Q-001-comprehensibility-vs-mystery.md`

### Decisions

- [[DEC-002-perfect-store-principle]]
- [[DEC-003-other-goods-identity]]
- [[DEC-004-commerce-first]]

### Promoted concepts

- [[conceptual-contrast]] (`status: working`)
- [[progressive-displacement]] (`status: working`)
- [[time-as-currency]] (`status: deferred`)
- [[other-goods-as-entity]] (`status: deferred`)

### Provenance

The original conversation containing the four product candidates, which had been confirmed only through secondary quotation in the earlier pilot ingest, was obtained. This confirmed that all four were directly supplied by the user. However, the detailed product settings and Collection composition remained at the LLM-proposal stage and were not promoted; individual product pages were not created either.

### Notes

The blockchain-based `TIME` economy and the multi-platform world-building were preserved as `deferred`, not deleted. The current scope is OTHER GOODS / Commerce.

## 2026-09-03 — Collection v0.1 agent survey ingest

### Sources

- `SRC-2026-09-03-claude-collection-survey` — `raw/surveys/2026-09-03-claude-collection-survey.md`
- `SRC-2026-09-03-gemini-collection-survey` — `raw/surveys/2026-09-03-gemini-collection-survey.md`
- `SRC-2026-09-03-perplexcity-collection-survey` — `raw/surveys/2026-09-03-perplexcity-collection-survey.md`

### Moved

- `raw/claude-collection-survey.md` → `raw/surveys/2026-09-03-claude-collection-survey.md`
- `raw/gemini-collection-survey.md` → `raw/surveys/2026-09-03-gemini-collection-survey.md`
- `raw/perplexcity-collection-survey.md` → `raw/surveys/2026-09-03-perplexcity-collection-survey.md`

The hashes before and after the moves matched in each case, and the original contents were not modified.

### Created

- `raw/surveys/`
- `wiki/questions/Q-002-first-collection-selection.md`

### Updated

- `raw/sources.md`
- `raw/README.md`
- `README.md`
- `AGENTS.md`
- `schema.md`
- `wiki/index.md`
- `wiki/current-state.md`

### Synthesis

All three surveys selected `The First Canceled Order`, `The Product Before Reading Reviews`, and `0.7 Seconds Before Payment Approval` as the three most OTHER GOODS-like products. `The First Typo in a New Notebook` and `Four Minutes After the Last Subway Has Passed` also all received KEEP. By contrast, evaluations repeatedly found that `Indoor Humidity at 63%` and `54 Seconds Waiting at a Traffic Light` lacked a strong Commerce Collision.

This agreement is entirely `llm-proposed` and was not promoted to a user decision. Candidates with divergent judgments, empty dimensions, and the agenda for the next ChatGPT brainstorming were organized in [[Q-002-first-collection-selection]].

### Schema changes

Added `surveys/` to the raw classification. The Wiki taxonomy was not expanded; the existing `question` page was used.

## 2026-09-04 — Commerce Product R&D summary ingest

### Source

- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`

### Created

- `wiki/concepts/product-grammar.md`
- `wiki/collections/rnd-collection.md`
- `wiki/collections/` directory
- `wiki/decisions/DEC-005-no-ip-products.md`
- `wiki/decisions/DEC-006-collection-before-catalog.md`
- `wiki/decisions/DEC-007-ontology-before-commerce.md`
- `wiki/questions/Q-003-product-grammar-taxonomy-scope.md`
- `wiki/questions/Q-004-rnd-collection-exit-condition.md`

### Updated

- `raw/sources.md`
- `wiki/current-state.md`
- `wiki/index.md`
- `wiki/concepts/commerce-as-medium.md`
- `wiki/questions/Q-002-first-collection-selection.md`

### Decisions

- [[DEC-005-no-ip-products]]
- [[DEC-006-collection-before-catalog]]
- [[DEC-007-ontology-before-commerce]]

### Open Questions

- [[Q-003-product-grammar-taxonomy-scope]] — new
- [[Q-004-rnd-collection-exit-condition]] — new

### Schema changes

none. However, because a `collection` type became materially necessary in the Wiki taxonomy, `wiki/collections/` was created for the first time.

### Notes

`wiki/products/` was still not created (only two of the 26 candidates had Grammar/Collision data). The Commerce-function-centered Grammar frame (Return/Review/Cart/Shipping Grammar) was discarded and preserved as `rejected` in [[rnd-collection]]. Because this source is a derivative summary rather than a transcript, the provenance of content promoted from it is in a secondary-quotation state. This ingest also contains part of the result of the “next ChatGPT brainstorming” anticipated in [[Q-002-first-collection-selection]].

## 2026-09-04 — Two Collection v0.4 surveys ingest

### Sources

- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`

### Created

- `wiki/collections/v0.4-evaluation.md`
- `wiki/questions/Q-005-commerce-generative-vs-display.md`
- `wiki/questions/Q-006-post-purchase-behavior.md`

### Updated

- `raw/sources.md`
- `wiki/collections/rnd-collection.md`
- `wiki/concepts/product-grammar.md`
- `wiki/concepts/progressive-displacement.md`
- `wiki/decisions/DEC-007-ontology-before-commerce.md`
- `wiki/questions/Q-001-comprehensibility-vs-mystery.md`
- `wiki/questions/Q-002-first-collection-selection.md`
- `wiki/questions/Q-003-product-grammar-taxonomy-scope.md`
- `wiki/current-state.md`
- `wiki/index.md`

### Decisions

none. No new decision. Only an unresolved challenge note was added to [[DEC-007-ontology-before-commerce]], whose status remains `confirmed`.

### Open Questions

- [[Q-005-commerce-generative-vs-display]], [[Q-006-post-purchase-behavior]] — new. Evidence was strengthened for Q-001, Q-002, and Q-003, but all remain `unknown`.

### Synthesis

The central opposition between the two surveys: for the same three products—05 `The First Canceled Order`, 07 `The Day After the Refund Period Ends`, and 10 `A ₩8,000 Price Drop Ten Minutes After Purchase`—Gemini placed them in the Bottom 8 while Claude placed them in the Top 8. This axis is exactly the one decided by [[DEC-007-ontology-before-commerce]]. Conversely, the two surveys agreed that emotional and nostalgia bias is the greatest risk. This agreement is also `llm-proposed` and was not promoted to a user decision.

### Schema changes

none.

### Notes

The original v0.4 evaluation prompt (the 30-item list and evaluation criteria) is not in the repository, so the list was reconstructed from the two surveys' tables. Their numbering agrees, enabling cross-checking, but the original prompt must still be obtained. `wiki/products/` was still not created. The surveys evaluated product names and concept level only; they did not confirm detailed design for each product.

## 2026-09-04 — Three Product Image System surveys ingest

### Sources

- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`

### Created

- `wiki/concepts/product-image-system.md`

### Updated

- `raw/sources.md`
- `raw/README.md`
- `README.md`
- `wiki/index.md`
- `wiki/current-state.md`
- `wiki/concepts/product-grammar.md`
- `wiki/concepts/progressive-displacement.md`
- `wiki/questions/Q-001-comprehensibility-vs-mystery.md`

### Decisions

none. The three surveys' 3/3 convergence on Option C is `llm-proposed` and was not promoted to a user decision.

### Synthesis

All three responses effectively rejected using ASCII as the global Product Image System, selecting Option C, which retains it as one renderer within a larger Representation System. Repeated risks were early learning of a single style, misreading it as the net.art or terminal genre, visual flattening of product variety, illustration preceding system treatment, and weakening of [[progressive-displacement]].

Their conclusions were the same but their reasons differed. Gemini strongly recognized ASCII's structural metaphor; GLM held that it becomes structural only when actual store data such as reviews, testimonials, and order records is the material of its glyphs; Grok assessed ASCII's conceptual necessity itself as weak. Accordingly, [[product-image-system]] records this not as a justification for ASCII, but as architectural convergence that a higher-level imaging policy is needed instead of a single style.

Alternative proposals were grouped into six provisional families: Formal Failure / Absence, Metadata / Specification, Witness / Data-substrate, Evidence / Container / Residue, Measurement / Sensor Capture, and State / Observer-dependent. This is `llm-synthesis` for prototype comparison, not a final taxonomy.

### Open Questions

- Can different renderers be bound into one store policy without becoming “an exhibition of several styles”?
- When ASCII uses actual store data as its material, does it truly transition from style to structure?
- For formless products and before actual visitors, after how many products does the image rule close?

### Schema changes

none. Product Image System became a meaningful unit that could independently develop over time, so one page was added within the existing `concept` taxonomy.

### Provenance

The common prompt for the three surveys and the reference flower ASCII image are not in the repository. The responses establish that they answered the same question structure, but the prompt's complete identity, conditions of independence between models, and whether actual images were viewed cannot be verified. GLM explicitly stated that it did not view actual pixels. This limitation was recorded in `raw/sources.md` and [[product-image-system]].

## [2026-09-04] maintenance | README, Index, and Log role separation

### Updated

- `README.md`
- `wiki/index.md`
- `wiki/log.md`
- `schema.md`
- `AGENTS.md`

### Result

- Removed the complete file tree from README and reorganized it around the work overview, current research, working timeline, the repository's three layers, and a reading path for people.
- Organized the Index as a working catalog containing a one-line summary, status, and update date for every Wiki page, together with editing routing. The individual raw-source list remains only in `raw/sources.md`.
- Added the rule that Log use the `## [YYYY-MM-DD] <type> | <title>` format beginning with new entries. Earlier entries were not revised under the append-only principle.
- Reflected the same role separation and synchronization rules in `schema.md` and `AGENTS.md`.

### Source

This repository-operating structure change was performed under the current user instruction. Because it is not a source that adds project knowledge, it was not registered in `raw/`.

### Current State

The project's concepts, decisions, hypotheses, and priorities did not change, so `wiki/current-state.md` was not updated.

## [2026-09-04] maintenance | English documentation migration

### Result

Maintained documentation became canonical English. Registered raw originals remained untouched in their original language. Language and localization rules were added to README, AGENTS, and the schema. No project-content decision changed.
