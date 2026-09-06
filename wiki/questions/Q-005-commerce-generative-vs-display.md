---
status: unknown
attribution: llm-proposed
updated: 2026-09-06
sources:
  - SRC-2026-09-04-gemini-collection-v0.4-survey
  - SRC-2026-09-04-claude-collection-v0.4-survey
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

# Q-005 — Is Commerce an Amplifier of Ontology or an Ontology-Producing Institution?

## Question

[[DEC-007-ontology-before-commerce]] decided that “ideas begin in Product Ontology, and Commerce is an amplifier, classifier, and collision device.” Claude's v0.4 survey argues that this proposition is partially wrong. Which is right, or how can the two propositions coexist?

## Why it matters

This axis produces opposite criteria for product selection. The v0.4 surveys produced directly opposite results — for the same three products (05 The First Canceled Order, 07 The Day After the Refund Period Ends, 10 A ₩8,000 Price Drop Ten Minutes After Purchase), **Gemini judged them Bottom 8, while Claude judged them Top 8**. Without this criterion, half of a 200-product Catalog could be made in the wrong direction. [[DEC-006-collection-before-catalog]] is contingent on it.

## The two positions

**Position A — Amplifier (the currently confirmed [[DEC-007-ontology-before-commerce]], `user-confirmed`)**

Beginning with Commerce functions narrows OTHER GOODS to “a meta-work that deconstructs an e-commerce system.” Ideas must begin with experiences, states, time, and relationships in reality. Gemini's survey supports this position — it placed 05, 07, and 10 in the Bottom 8, evaluating them as “e-commerce jokes,” “extensions of consumer complaints,” and “dependent on Commerce functions rather than properties of the object itself.”

**Position B — Producing institution (Claude survey, `llm-proposed`)**

To quote Claude's formulation: “Commerce is not an amplifier but an ontology-producing institution. SKUs, order histories, return deadlines, condition grades, and resale prices are object categories that Commerce has actually created anew in the world.” Its basis is that the strongest products in v0.4 are all Commerce-generative, and that 05, 07, and 10 would not have been made had DEC-007 been followed literally. Product 07 sells “an expired right that is neither experience nor object,” which is an object type the current taxonomy does not capture.

## The discriminating axis proposed by Claude

Claude proposed **Commerce-generative vs. Commerce-display** as an axis with more discriminating power than the 25-Grammar taxonomy. The criterion is “does it die if printed in a book of poetry?” — if it dies, it is generative; if it survives, it is display. By Claude's count, 20 of the 30 lose almost nothing when Commerce is removed. The evidence offered is that only 01–10 have a `Primary Commerce Collision` field in the original document, while 11–30 do not. The proposed balance is 40–50% Commerce-generative / 30% collision-based / no more than 20% independent.

All of this is `llm-proposed` and has not been adopted.

## The v0.5 round — the axis was used, not settled

**(2026-09-04)** By the v0.5 round, Claude's axis had been turned into a working three-way classification — **Commerce-Generated / Commerce-Activated / Commerce-Displayed** — and all four surveys applied it by name without introducing it, which indicates the v0.5 prompt supplied it. The prompt itself is not registered, so this is inference from the responses.

Four results follow.

1. **All four judge the current balance unhealthy, with too large a Commerce-Displayed share.** Counts: Grok 12 / 40 / 48 %, GLM 17 / 50 / 33 %, Kimi 12.5 / 50 / 37.5 %; Gemini gave no count but called the collection “heavily skewed” to Displayed. Recommended Generated share: 20–25 % from three of four, 40 % from Gemini.
2. **The gap between the two v0.4 positions narrowed in practice.** Gemini, the model that in v0.4 treated commerce-nativeness itself as a weakness, now rates 05, 07, and 08 as the collection's strongest products and calls `First Canceled Order` the strongest product in v0.5. Its stated reason is that commerce-generated products are the only ones that scale to 200 SKUs. This is a reversal on the same axis by the same model, on the same three products it had placed in its Bottom 8 one round earlier. It is a change of `llm-proposed` opinion, not evidence about the question.
3. **GLM argues the dichotomy itself is false.** “Commerce-generated products *are* ontology-first products whose ontology happens to be commercial.” Its proposed instruction is to mine commerce's own ontologies *and* collide commerce with non-commercial ones, with a single test applied to both: does a commerce mechanism — price logic, policy, inventory behavior, review semantics, delivery — do conceptual work that changes what the thing means? This corresponds to conclusion (b) in the list below, not to (a) or (c).
4. **The classification is not operationally stable.** Gemini lists `Yesterday`, `17,400 Hz`, and `Unit 12B, Unoccupied` as Commerce-Displayed; GLM classifies all three as Commerce-Activated; Kimi places `Yesterday` in Activated in its table and then again among “Displayed products worth keeping.” The same products land in different categories under different evaluators, so the percentages above are not directly comparable and no target ratio can yet be enforced. **Defining the categories precisely enough to be reproducible is now a prerequisite for using the axis at all.**

## The v0.6 discussion — a proposed bridge, not a resolution

**(2026-09-05)** The conversation proposed that a product name may carry human or philosophical meaning provided Commerce does not merely illustrate it but materially tests or transforms it. `What Payment Cannot Undo` is the clearest example: the human territory is guilt, atonement, and consequences, while payment supplies the collision that exposes what exchange cannot settle. This is an `llm-proposed` bridge between the two positions, prompted by the user's objection to excessively technical naming; it does not revise [[DEC-007-ontology-before-commerce]].

The derivative pre-v0.6 position note states the bridge as a two-part test: **Commerce must materially change the product, and the product must still contain something worth changing.** This keeps Commerce from becoming either a decorative shell or the sole source of ontology. It is a concise working proposal, not an independent confirmation or a revision of the current decision.

**(2026-09-05, `llm-proposed`)** The six critiques converge around requiring at least one meaning-changing commerce operation, while disagreeing about retaining the three-way taxonomy. That convergence challenges but does not alter [[DEC-007-ontology-before-commerce]], which remains confirmed. The related question of whether the artwork's atomic unit is a product or transaction is recorded in [[Q-008-product-or-transaction]].

## Current State

Unresolved. [[DEC-007-ontology-before-commerce]] remains `confirmed` / `user-confirmed`; this question does not invalidate it. The surveys are `llm-proposed`, and the two models point in opposite directions, so there is not even consensus. User judgment is required.

Three possible conclusions are: (a) retain DEC-007 and reject Claude's claim; (b) revise DEC-007 to permit both starting points; (c) make a new decision that replaces DEC-007. None has yet been selected. Four further `llm-proposed` surveys now point toward (b), and none toward (a), but a count of model opinions is not a user decision and does not move the decision's status.

## The 2026-09-06 reframing — the question moved, it did not close

`jointly-developed`, `status: working`. The working decisions replace the operative test rather than answering the amplifier-versus-institution question. The earlier evaluation logic — *if Commerce does not materially transform the product, the product is weak* — is judged **too narrow** and replaced by:

> **Does Commerce create a tension that would not exist without it?**

This admits products where Commerce does almost nothing beyond calmly declaring that the thing is merchandise, and it is the reasoning behind the third of three new observation axes:

- **Commerce-Generated** — Commerce creates the state or object.
- **Commerce-Transformative** — the thing exists independently, but Commerce changes how its identity, condition, ownership, value, or lifecycle is understood.
- **Commerce-as-Assertion** — Commerce may barely transform the thing; the tension is the institution's calm assertion that it is a product.

Three things this changes for this question, none of them a resolution.

1. **The three-way classification changed shape.** Commerce-Generated / Commerce-Activated / Commerce-Displayed — the triad the unregistered v0.5 prompt supplied, whose instability is recorded above — is superseded by Generated / Transformative / **Assertion**. The source labels the new triad **experimental observation axes, explicitly not a final taxonomy**, so it must not be recorded as the answer to Q-003 either.
2. **The weakest category was reinterpreted rather than deleted.** Commerce-Displayed was the category everything unwanted fell into. Assertion occupies roughly the same position with the opposite valence: GLM's distinction is that Displayed products sit beside commerce inertly and are *whimsical* merchandise, while Assertion products are *contested* merchandise, where the institution's calm certainty collides with the thing's unownability. Whether that distinction survives contact with real visitors is untested.
3. **The rejection criterion problem is unchanged and arguably sharper.** GLM argues the reframed question is **unfalsifiable on its own**, because any strange thing placed beside a price produces some tension, and that this is precisely the door through which "the poetry book with price tags" re-enters.

### The proposed guardrail — feature localization

`llm-proposed`, single-model, unadopted. GLM's instrument: the tension a product creates must be traceable to **one named commercial feature** — price, stock, shipping, the address field, condition grade, purchase eligibility, reviews, returns, restock, refund, notification. For every candidate the team should be able to write down the one feature it bends. *If the only writable answer is "there is a price tag," the product is a displayed poem rather than merchandise.*

Two properties make it the most usable proposal this question has received. It is **falsifiable**, unlike the reframed test it guards. And it is **not a class penalty**: GLM applies it across temperatures, benching the human product that fails it (`30th Rain Through the Same Window`, the only pool item whose sole activated feature is the price tag) while keeping assertion-led products that pass through the address field (`Distance to Home: 1,847 mi`) or the condition grade (`The World I Helped Break`).

It also **does not disturb [[DEC-007-ontology-before-commerce]]**. It is a Layer 2 test: it does not require ideas to begin with commerce, only that a candidate be able to land on one commercial feature. Applied, it would supply what the four v0.5 surveys said the grammar lacks — a way to exclude — without deciding whether Commerce amplifies or produces ontology.

**(2026-09-06, `llm-proposed`)** Five critiques divide on the axis itself: three answer "test only," two a qualified yes, none rejects it, and none accepts it unconditionally. All five independently name the same risk — Assertion becoming an admission loophole. Their shared condition is that the commercial frame around such a product must be complete and deadpan; Qwen's version is that Commerce-as-Assertion "requires the UI to do 100% of the conceptual heavy lifting." See [[pre-v0.6-evaluation-round-2]].

**Status: still unresolved.** [[DEC-007-ontology-before-commerce]] remains `confirmed`. Neither the reframed test nor the guardrail is adopted, and neither selects among conclusions (a), (b), and (c) above.

## Related

- [[DEC-007-ontology-before-commerce]] — The decision challenged by this question, but a challenge does not itself overturn a decision.
- [[v0.4-evaluation]] — The evaluation itself in which the two judgments behind this question emerged.
- [[commerce-as-medium]] — This question overlaps with whether Commerce should be seen as a medium or an ontology-producing institution.
- [[product-grammar]] — The claim that the Commerce-generative/Commerce-display axis can replace the existing 25-Grammar taxonomy is at stake.
- [[DEC-006-collection-before-catalog]] — The absence of this criterion poses a practical risk when expanding to a 200-product Catalog.
- [[v0.5-evaluation]] — Where the four surveys' counts, target ratios, and conflicting classifications are recorded in full.
- [[Q-006-post-purchase-behavior]] — Connected because three of the four surveys propose using the post-purchase test as the practical way to tell Displayed products from the rest.
- [[Q-008-product-or-transaction]]
- [[pre-v0.6-evaluation-round-2]] — Where the five critiques of Commerce-as-Assertion and the feature-localization guardrail are compared.
- [[rnd-collection]] — Holds the three observation axes and the active pool they classify.

## Sources

- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`

- `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, `SRC-2026-09-04-kimi-collection-v0.5-survey` — the four v0.5 surveys under `raw/surveys/`.

The six survey sources above are `llm-proposed`, not user decisions. Neither the v0.4 nor the v0.5 evaluation prompt is registered in this repository, so what the surveys actually responded to — including the definitions of Commerce-Generated, Commerce-Activated, and Commerce-Displayed — can only be inferred through their texts.

- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`. User-originated thematic territory and objection; the proposed bridge and product titles remain `llm-proposed`.
- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`. Derivative restatement of the bridge, not independent evidence.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
- `SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions` — `raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md`. A `jointly-developed` working-decision summary, `status: working`. It is a decision summary rather than a conversation transcript, and nothing in it is `user-confirmed`.
- `SRC-2026-09-05-deepseek-pre-v0.6-survey`, `SRC-2026-09-05-gemini-pre-v0.6-survey`, `SRC-2026-09-05-glm-pre-v0.6-survey`, `SRC-2026-09-05-grok-pre-v0.6-survey`, and `SRC-2026-09-05-qwen-pre-v0.6-survey` — five `llm-proposed` critiques under `raw/surveys/`. Their shared evaluation brief is not registered and does not match the working-decisions document's section numbering; despite an earlier filename date, their content places them after those working decisions. Evaluator independence is unverified.
