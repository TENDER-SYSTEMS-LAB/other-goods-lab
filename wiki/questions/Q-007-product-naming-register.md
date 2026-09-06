---
status: unknown
attribution: jointly-developed
updated: 2026-09-06
sources:
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
  - SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions
  - SRC-2026-09-05-deepseek-pre-v0.6-survey
  - SRC-2026-09-05-gemini-pre-v0.6-survey
  - SRC-2026-09-05-glm-pre-v0.6-survey
  - SRC-2026-09-05-grok-pre-v0.6-survey
  - SRC-2026-09-05-qwen-pre-v0.6-survey
---

# Q-007 — In What Register Should Products Be Named?

## Question

The v0.5 round tested a naming principle: **“Use the driest name that preserves the product's essential image.”** Is that principle correct? If not, what governs a product name — and how does the store avoid replacing a sentimental house style with a dry one?

## Why it matters

Product titles are currently doing most of the work. All four v0.5 surveys independently concluded that the collection's improvement from v0.4 was **largely lexical** and that naming is standing in for ontology — GLM's phrasing is that “naming is doing ontology's job.” A naming rule applied across 100–200 SKUs is therefore not a copywriting decision but a structural one: it determines whether visitors read the store as a real commercial service ([[DEC-002-perfect-store-principle]]) or recognize a formula and close their interpretation ([[progressive-displacement]]).

The question is also where the v0.5 surveys disagree most sharply on a concrete artifact, which makes it a useful discriminator rather than a matter of taste.

## The direct conflict

The same product title received opposite final verdicts.

- **Grok** and **Kimi** named `Residual Warmth on a Park Bench` the **best naming decision in v0.5**. Kimi: “‘Residual’ removes sentiment without destroying the image. It demonstrates that dryness can be precise, not merely cold.”
- **GLM** named it the **worst naming decision in v0.5** and asked to revert to `Warmth Left on a Park Bench` or `Warm Spot on a Park Bench`. Its argument: “Left” is not decoration but ontology — someone was here, the trace is theirs, it is running out — while “Residual” is register anxiety that removes naturalness without removing sentiment, because the sentiment lives in the phenomenon, not the adjective. It calls “residual warmth” itself a technical cliché: one sentimental register swapped for another.
- **Gemini** placed it in neither list, filing it under names needing revision and proposing *Thermal Residue (Public Seating)*.

The disagreement is not about whether the name is pretty. It is about **where sentiment lives** — in the wording, or in the phenomenon the wording points at. If GLM is right, dryness applied lexically cannot work at all, and the whole principle is misdirected.

## Four proposed replacement principles

All four surveys rejected the tested principle as a global rule and proposed a replacement. All are `llm-proposed` and unadopted.

- **Gemini** — “Name the product exactly as its governing system would classify it.” Logistics language for shipping-generated products, acoustic specifications for audio, quality-assurance terminology for products born of human error.
- **Grok** — “Use the driest name that still forces the essential commercial collision into view.” Where a human or contextual cue is required to make the collision visible, keep the minimal cue: “context is not sentiment; it is the condition that makes the product purchasable rather than merely nameable.”
- **GLM** — **Register Matching:** “Name each product in the language of the real-world system that would plausibly handle it. Where no such system exists, use plain spoken English. **Dryness is a byproduct of register fidelity, not a goal.**” A park bench has no native commercial register, so plain warm English is correct there.
- **Kimi** — “Name the condition, not the feeling.” Dryness should be applied when sentimentality threatens to replace ontology and resisted when the “wet” detail is the conceptual engine.

Gemini, GLM, and Grok converge on the same underlying move: the name should borrow the register of whatever real system would handle the object. Kimi's rule is compatible but stated at the level of content rather than register.

## Agreement — dryness must not become a house style

This is 4/4, and it is the clearest result of the round.

- GLM: three v0.5 titles already use the same “Noun, Status” template — `Unit 12B, Unoccupied`, `12 Stairs, Never Counted`, and a proposed `Ocean, 3 Seconds`. At 200 SKUs that template becomes “the sentimentality of bureaucratic cool.” Its counter-move: **real stores mix marketing names, spec names, status strings, and plain names — register diversity is itself a realism signal.**
- Gemini: if everything becomes “Residual X” or “Temporal State Y,” the store devolves into predictable bureaucratic parody.
- Grok: pure dryness becomes its own aesthetic formula (“Residual X on Y”, “Nth Z Never Counted”).
- Kimi (as its most dangerous blind spot for the whole project): a store of 200 dry conceptual titles is as monotonous as a store of 200 memory fragments.

This connects directly to [[progressive-displacement]]: a legible naming template is a rule the visitor can learn, and a learned rule closes interpretation.

## Agreement — specific names

Names all four called strong: `Yesterday`, `First Typo in a New Notebook`, `First Canceled Order`, `Day After the Return Window Closed`, `17,400 Hz`, `Unit 12B, Unoccupied`.

Names at least three of four asked to revise: `Last 10 Minutes Before Knowing the Ending` (Grok, GLM, and Kimi place it among the worst; GLM notes it is grammatically ambiguous about whose ten minutes are meant), `Summer, Age 16`, `Rear View of a Building, Bus Window Only` (GLM: “Bus Window Only” is not idiomatic English), `“These Days,” 5 Years Ago` (GLM and Grok both flag the quotation marks as an art-title tell — a title that needs punctuation to explain itself).

GLM raises a factual objection no other survey makes: `First 12 Sheets Discarded Before Printing` is inaccurate, because the sheets *are* printed, during setup. It proposes `Makeready Sheets, First 12`, “makeready” being the real industry term — an example of its own register-matching rule.

## User pressure against technical overcorrection

**(2026-09-05)** While developing a candidate from guilt, atonement, and continuing consequences, the conversation moved from `Payment Complete, Liability Outstanding` to `Account Settled, Consequences Ongoing`. The user then objected that `Account` was again too technical and asked why philosophical or emotional language was being avoided. This is direct evidence against treating register fidelity as an automatic instruction to bureaucratize every title; it is an objection, not acceptance of a replacement rule.

The LLM's revised proposal was: **a product name may carry human meaning, as long as the Commerce system does not merely illustrate it but meaningfully tests and transforms it.** It preferred `What Payment Cannot Undo`, with `The Cost Was Paid. The Consequences Remain.` as the more human alternative. Neither title nor the principle was user-confirmed.

A derivative pre-v0.6 position note formalizes register fidelity as ChatGPT's current recommendation but also places external critique and resolution of the naming principle before v0.6 composition. Because it synthesizes the same surveys and discussion, it does not add an independent vote for register fidelity.

## Unresolved subproblems

- **The store's naming language.** v0.5's titles are English and its prices are in dollars, whereas v0.4's were Korean-derived and in won. No registered source explains the change and no user decision records it. Whether English is the store's canonical product language, or a working language for evaluation only, is unknown.
- **Whether register-matching scales.** If every product borrows the register of a real system, products with no adjacent real system (park benches, alleys, ordinary rooms) become the exceptions — and it is unclear whether the exceptions read as texture or as inconsistency.
- **Whether a name can be evaluated at all before the mechanics exist.** All four surveys note that titles are currently carrying the concept. If [[Q-006-post-purchase-behavior]] is answered first, the naming criterion may change, because the name would no longer be the product's only surface.

## Current State

Unresolved and unadopted. The tested principle has four independent rejections as a global rule and four different replacements, three of which converge on register-matching. The later user objection adds direct pressure against technical overcorrection but does not select a replacement. No user decision exists on any naming principle, on the naming language, or on the specific disputed titles.

**(2026-09-05, `llm-proposed`)** Six critiques give qualified 6/6 support to Register Fidelity over Dryness, while all six warn that it can become another device or house style. Claude proposes Register Variance and requires real reference documents for claimed register fidelity. Naming remains unresolved.

**(2026-09-06, `jointly-developed`, `status: working`)** The tested principle is now explicitly set aside as a global rule. The working decisions state that maximizing dryness "is no longer accepted as a global rule," that technical or bureaucratic language should not automatically displace philosophical, emotional, or ordinary language, and that **a product name may carry human meaning**. The reasoning is that Commerce can produce the collision elsewhere — through price, stock, eligibility, checkout, return, order history, or simply the visual fact of presentation as merchandise — so the title need not carry it alone.

The positive direction is **register diversity, not a replacement rule**: a real store contains specification names, plain names, status strings, ordinary spoken English, descriptive titles, and institutional language side by side. "Uniform bureaucratic cool is itself a stylistic trap." This resolves the direction of travel — the same direction the four v0.5 surveys converged on from the opposite side — while still selecting no governing principle.

Two concrete title dispositions follow from it, both `jointly-developed` working titles rather than confirmations:

- `What Payment Cannot Undo` was judged **inadequate** for its intended territory: it translated the idea too quickly into payment, debt, and settlement. The working replacement `The World I Helped Break` is preferred precisely because it is *not* translated into commercial register, and because the speaker is implicated in what is being sold.
- `"These Days," Five Years Ago` retains its quotation marks on the argument that the phrase itself is the object under examination rather than decorative punctuation, and spells `Five` rather than `5`.

**(2026-09-06, `llm-proposed`)** Five critiques of those decisions largely support the shift while dividing on the hardest case. Four of five affirm the quotation marks as necessary rather than affectation, three of them for the same reason the working decisions give; Gemini alone proposes reformatting or removing them. On `The World I Helped Break`, four of five keep the title — GLM arguing that "helped" refuses grandiosity and that first-person titles transfer their "I" on purchase — while Qwen alone judges it too literary and proposes translating it into commercial language (`Acknowledged Complicity, Non-Refundable`). Three of five note that the `First ___` and number-plus-unit templates are forming visible families regardless of register.

The unresolved subproblems below are unchanged, including the store's naming language: **the switch to English titles and dollar prices is still explained by no registered source.** See [[pre-v0.6-evaluation-round-2]].

## Related

- [[v0.5-evaluation]] — The round in which this question arose, including the full naming comparison.
- [[progressive-displacement]] — Why a legible naming template is a structural risk, not a stylistic one.
- [[Q-001-comprehensibility-vs-mystery]] — Naming register is one of the levers that sets how quickly a visitor thinks they understand the store.
- [[Q-006-post-purchase-behavior]] — If mechanics carry the concept, the naming criterion changes.
- [[product-grammar]] — The surveys' criticism that titles are retrofitted labels applies to both the taxonomy and the names.
- [[DEC-002-perfect-store-principle]] — Real commercial services mix naming registers; register uniformity is a realism cost.
- [[pre-v0.6-evaluation]]
- [[pre-v0.6-evaluation-round-2]] — Where the five critiques of the 2026-09-06 naming direction are compared.

## Sources

- `SRC-2026-09-04-gemini-collection-v0.5-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.5-survey.md`
- `SRC-2026-09-04-glm-collection-v0.5-survey` — `raw/surveys/2026-09-04-glm-collection-v0.5-survey.md`
- `SRC-2026-09-04-grok-collection-v0.5-survey` — `raw/surveys/2026-09-04-grok-collection-v0.5-survey.md`
- `SRC-2026-09-04-kimi-collection-v0.5-survey` — `raw/surveys/2026-09-04-kimi-collection-v0.5-survey.md`

The four survey sources above are `llm-proposed`. The naming principle under test is visible only through the four responses; the original v0.5 prompt that stated it is not registered in this repository.

- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`. Primary evidence for the user's objection to over-technical naming; the replacement principle and titles are LLM proposals.
- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`. Derivative ChatGPT position; not an additional independent evaluator.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
- `SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions` — `raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md`. A `jointly-developed` working-decision summary, `status: working`. It is a decision summary rather than a conversation transcript, and nothing in it is `user-confirmed`.
- `SRC-2026-09-05-deepseek-pre-v0.6-survey`, `SRC-2026-09-05-gemini-pre-v0.6-survey`, `SRC-2026-09-05-glm-pre-v0.6-survey`, `SRC-2026-09-05-grok-pre-v0.6-survey`, and `SRC-2026-09-05-qwen-pre-v0.6-survey` — five `llm-proposed` critiques under `raw/surveys/`. Their shared evaluation brief is not registered and does not match the working-decisions document's section numbering; despite an earlier filename date, their content places them after those working decisions. Evaluator independence is unverified.
