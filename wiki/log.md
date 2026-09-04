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

## [2026-09-04] maintenance | Institutional Git identity policy

Added a repository-wide rule requiring new commits to use the repository-local TENDER SYSTEMS identity and requiring commit identity to be verified separately from GitHub push authentication. The rule prohibits personal author or committer fallback, guessed institutional email addresses, secret disclosure, and history rewriting. A dedicated push identity remains preferred; personal push authentication is permitted only with explicit user authorization and acknowledgment that non-commit audit or activity records may retain the push actor. No project knowledge or raw source material changed.

## [2026-09-04] ingest | Collection v0.5 four-survey ingest

### Sources

- `SRC-2026-09-04-gemini-collection-v0.5-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.5-survey.md`
- `SRC-2026-09-04-glm-collection-v0.5-survey` — `raw/surveys/2026-09-04-glm-collection-v0.5-survey.md`
- `SRC-2026-09-04-grok-collection-v0.5-survey` — `raw/surveys/2026-09-04-grok-collection-v0.5-survey.md`
- `SRC-2026-09-04-kimi-collection-v0.5-survey` — `raw/surveys/2026-09-04-kimi-collection-v0.5-survey.md`

All four were already registered in `raw/sources.md` with status `raw-only` / `unreviewed`. This entry records their promotion. Hashes for all fifteen registered sources were verified against the registry before and after the work; all matched, so no page was marked `REVIEW_REQUIRED`.

### Created

- `wiki/collections/v0.5-evaluation.md`
- `wiki/questions/Q-007-product-naming-register.md`

### Updated

- `wiki/collections/rnd-collection.md` — added the v0.5 section: 30 → 24, the first contraction of the Collection.
- `wiki/concepts/product-grammar.md` — added the four v0.5 consolidation proposals and the five-category convergence.
- `wiki/concepts/progressive-displacement.md` — added the alternation-as-formula constraint and the four conflicting opening products.
- `wiki/concepts/product-image-system.md` — recorded Gemini's independent restatement of the visual-output risk and two unregistered concept names.
- `wiki/questions/Q-003-product-grammar-taxonomy-scope.md`, `wiki/questions/Q-005-commerce-generative-vs-display.md`, `wiki/questions/Q-006-post-purchase-behavior.md`
- `wiki/current-state.md`, `wiki/index.md`, `raw/sources.md`, `raw/README.md`, `README.md`

### Decisions

none. All four surveys are `llm-proposed`. Nothing in this round was promoted to a user decision, and [[DEC-007-ontology-before-commerce]] remains `confirmed` despite four further surveys pointing away from it.

### Synthesis

All four surveys returned WORKING BUT NEEDS CORRECTION — the same verdict as the v0.4 round. Two consecutive rounds ending on the same non-verdict is recorded as evidence for [[Q-004-rnd-collection-exit-condition]].

What changed is where the correction is located. In v0.4 it concerned which products exist; in v0.5 all four locate it in what the store does after the product page, and all four name the transaction and post-purchase layer as the one thing to build before v0.6. This removed the single-source dependency that [[Q-006-post-purchase-behavior]] had carried since its creation, though the four split on whether a post-purchase field should be mandatory for every product or only for commerce-generated and commerce-activated ones.

Agreement was much stronger than in v0.4: six of 24 products appear in all four Top 8 lists, and one — `Wrong-Turn Alley` — in all four Bottom lists. Sharp conflicts remain on seven products, most starkly on the name `Residual Warmth on a Park Bench`, which two surveys call the round's best naming decision and one calls its worst.

Two criticisms of method, not of products, are 4/4 and were promoted to [[current-state]]: the collection's generative formula is now visible and the taxonomy supplies no rejection criterion, and the correction may be replacing a sentimental bias with a dry, taxonomic one rather than curing it. GLM's proposed rejection test — does a commerce mechanism do conceptual work that changes what the thing means? — is the only concrete instrument offered and is unadopted.

Four consolidated grammar taxonomies were proposed (5, 8, 9, and 11 categories against the current 14 and the 25 criticized in v0.4). Five categories appear in all four under different names; the convergence table was promoted to [[product-grammar]] and [[Q-003-product-grammar-taxonomy-scope]]. Claude's v0.4 proposal to demote `Irreversible` to a background property is contradicted by all four.

### Open Questions

- [[Q-007-product-naming-register]] was created: the “driest name” principle was rejected as a global rule by all four, which proposed four different replacements; three converge on matching the register of whatever real system would handle the object.
- Price as a conceptual surface — GLM's most dangerous blind spot, single-source. Recorded in [[current-state]] and [[v0.5-evaluation]] without a page.
- Why v0.5's titles became English and its prices dollars. No registered source explains it and no user decision records it.

### Schema changes

none. `v0.5-evaluation` uses the existing `collection` type and `Q-007` the existing `question` type. No new page type or directory was created.

### Notes

Two dependencies are worth watching. First, the three products added in v0.5 — `17,400 Hz`, `Unit 12B, Unoccupied`, and `First 12 Sheets Discarded Before Printing` — are near-verbatim instantiations of example objects proposed in Claude's v0.4 survey, and all four v0.5 surveys rate that territory as the collection's most valuable; the strongest-rated material in the current version therefore rests on one `llm-proposed` source. Second, whether the four v0.5 models answered independently of one another cannot be verified from the responses, so their convergence is a strong signal rather than four separate confirmations.

### Provenance

The v0.5 evaluation prompt is not in the repository. The 24-item list, the v0.4 → v0.5 transition, the naming principle under test, and the Commerce-Generated / Activated / Displayed classification are all known only through the four responses and are labeled as reconstructions or inferences wherever they appear. The gap was recorded in `raw/sources.md`.

## [2026-09-05] ingest | v0.6 R&D conversation ingest

### Source

- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`

The source was registered with hash `5badba367e8f7ed5550a54d4b3c884bbd4687922` and partially promoted. It is a jointly developed conversation: the user introduced the thematic territory and challenged over-technical naming; the v0.6 structure, Product Behavior Sheet, Grammar labels, ratios, and English product titles are LLM proposals.

### Updated

- `wiki/collections/rnd-collection.md` — added an unadopted v0.6 discussion and R&D bench without treating it as a new Collection version.
- `wiki/concepts/product-grammar.md` — recorded five new research territories without adding them to the taxonomy.
- `wiki/questions/Q-004-rnd-collection-exit-condition.md` — distinguished a lifecycle experiment from an actual exit condition.
- `wiki/questions/Q-005-commerce-generative-vs-display.md` — recorded the proposed bridge in which Commerce tests rather than merely illustrates human meaning.
- `wiki/questions/Q-006-post-purchase-behavior.md` — recorded the proposed Product Behavior Sheet and diagnostic/feature distinction.
- `wiki/questions/Q-007-product-naming-register.md` — recorded the user's direct objection to bureaucratic overcorrection and the unadopted replacement principle.
- `wiki/current-state.md`, `wiki/index.md`, `raw/sources.md`, `raw/README.md`.

### Decisions

none. No v0.6 list, item count, ratio, lifecycle gate, naming rule, Grammar category, or product title was user-confirmed. v0.5 remains the current Collection.

### Synthesis

The conversation proposes changing the next R&D unit from another broad title list into a smaller Deep R&D Set that tests products through price, inventory, confirmation, fulfillment, order history, return, and repurchase. It opens user-originated territory around guilt, homecoming, atonement, responsibility, control, and continuing consequences. The most developed title moved through three LLM variants and ended at `What Payment Cannot Undo`; this evolution was retained as evidence in the naming question, not as a selected product.

### Provenance

The conversation names an attached text and relies on a pasted interpretation of a video essay, but neither the source video nor the attachment is registered. The conversation is therefore primary evidence for what the user wants to explore and secondary evidence for claims about the video. A stale statement inside the conversation that the Wiki had not yet synthesized v0.5 was not promoted because the repository had already completed that ingest.

## [2026-09-05] ingest | Pre-v0.6 R&D position note ingest

### Source

- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`

The source was registered with hash `568ed22708d9b57bd9cb2f509025f14ff44e11db` and partially promoted. Its own frontmatter classifies it as `llm-proposed`. It synthesizes the Wiki, four v0.5 surveys, the naming discussion, and supplied video analysis, so it was not counted as an independent evaluation.

### Updated

- `wiki/collections/rnd-collection.md` — qualified the proposed v0.6 size as approximately 12–16, recorded nine deeper-development candidates and bench/rework dispositions, and added a six-step pre-v0.6 gate.
- `wiki/questions/Q-004-rnd-collection-exit-condition.md` — distinguished the proposed v0.6 entry gate from the still-undefined Catalog exit condition.
- `wiki/questions/Q-005-commerce-generative-vs-display.md` — recorded the two-part test that Commerce must change a product that still has something worth changing.
- `wiki/questions/Q-006-post-purchase-behavior.md` — added Product Grammar, delivery, resale, and concrete price/inventory questions to the proposed lifecycle sheet.
- `wiki/questions/Q-007-product-naming-register.md` — recorded ChatGPT's register-fidelity position without treating it as another independent vote.
- `wiki/concepts/product-grammar.md` — recorded the note's recommendation to test the moral-residue territory before taxonomy promotion.
- `wiki/current-state.md`, `wiki/index.md`, `raw/sources.md`, `raw/README.md`.

### Decisions

none. The note explicitly says it is not a user decision and recommends not finalizing v0.6 yet. v0.5 remains the current Collection.

### Synthesis

The note consolidates the pre-v0.6 position around a smaller Deep R&D Set, full-lifecycle testing, non-decorative price and inventory, conditional post-purchase behavior, and protection against overcorrecting from sentimentality into bureaucratic conceptualism. Its strongest concise criterion is dual: Commerce must materially change the product, and the product must still contain something worth changing.

### Provenance

This source repeats and organizes material from already registered sources rather than independently corroborating it. The video underlying the moral-residue discussion is still absent, so claims about that video remain secondary.

## [2026-09-05] ingest | Pre-v0.6 six-survey critique ingest

### Sources

- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`
- `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`
- `SRC-2026-09-04-glm-pre-v0.6-rnd-position`
- `SRC-2026-09-04-grok-pre-v0.6-rnd-position`
- `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`
- `SRC-2026-09-04-qwen-pre-v0.6-rnd-position`

All six survey originals were registered as `llm-proposed`, partially promoted, and hash-verified. The ChatGPT position note under review remains derivative rather than a seventh independent evaluation.

### Created

- `wiki/collections/pre-v0.6-evaluation.md`
- `wiki/questions/Q-008-product-or-transaction.md`

### Updated

- `raw/sources.md`, `raw/README.md`, `README.md`, `AGENTS.md`, `wiki/index.md`, and `wiki/current-state.md`
- `wiki/collections/rnd-collection.md`
- `wiki/concepts/commerce-as-medium.md`, `wiki/concepts/product-grammar.md`, and `wiki/concepts/progressive-displacement.md`
- `wiki/questions/Q-003-product-grammar-taxonomy-scope.md`, `wiki/questions/Q-004-rnd-collection-exit-condition.md`, `wiki/questions/Q-005-commerce-generative-vs-display.md`, `wiki/questions/Q-006-post-purchase-behavior.md`, and `wiki/questions/Q-007-product-naming-register.md`

### Decisions

none. v0.5 remains the current Collection. No v0.6 structure, candidate, naming rule, lifecycle rule, payment model, taxonomy, or Behavior Sheet was confirmed.

### Synthesis

All six responses say `READY WITH ONE REQUIRED CORRECTION`, which is recorded only as directionally ready for another experiment. The comparison records 6/6 qualified support for a temporary 12–16-product R&D unit, a 3/3 lifecycle split, 5/1 price-logic split, 4/2 inventory-logic split, 5/1 rework/keep split for `What Payment Cannot Undo`, and the unanimous rejection of `Self-Assigned Responsibility`. [[Q-008-product-or-transaction]] records the strongest new unresolved cluster: atomic unit and real payment.

### Provenance

The shared evaluation prompt, identical prompt delivery, and evaluator independence are not verified. Counts are LLM convergence, not user confirmation or audience research. The moral-residue material remains downstream of a missing video and attachment, and real-money legal or consumer statements are LLM-proposed risk flags rather than verified legal guidance.

### Verification

Repository-wide raw hashes were checked against the registry before and after this ingest; registered originals matched. The six newly registered survey hashes matched their registry values. No raw original was edited.

## [2026-09-05] maintenance | Agent model-routing preference

### Updated

- `AGENTS.md`

### Result

Added the subagent model-routing preference for simple search/localization, document drafting/editing, and planning/verification. This is an AGENTS-only operational change; no raw project source was registered for it.
