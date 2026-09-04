---
status: unknown
attribution: llm-proposed
updated: 2026-09-05
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

## Related

- [[DEC-007-ontology-before-commerce]] — The decision challenged by this question, but a challenge does not itself overturn a decision.
- [[v0.4-evaluation]] — The evaluation itself in which the two judgments behind this question emerged.
- [[commerce-as-medium]] — This question overlaps with whether Commerce should be seen as a medium or an ontology-producing institution.
- [[product-grammar]] — The claim that the Commerce-generative/Commerce-display axis can replace the existing 25-Grammar taxonomy is at stake.
- [[DEC-006-collection-before-catalog]] — The absence of this criterion poses a practical risk when expanding to a 200-product Catalog.
- [[v0.5-evaluation]] — Where the four surveys' counts, target ratios, and conflicting classifications are recorded in full.
- [[Q-006-post-purchase-behavior]] — Connected because three of the four surveys propose using the post-purchase test as the practical way to tell Displayed products from the rest.
- [[Q-008-product-or-transaction]]

## Sources

- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`

- `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, `SRC-2026-09-04-kimi-collection-v0.5-survey` — the four v0.5 surveys under `raw/surveys/`.

The six survey sources above are `llm-proposed`, not user decisions. Neither the v0.4 nor the v0.5 evaluation prompt is registered in this repository, so what the surveys actually responded to — including the definitions of Commerce-Generated, Commerce-Activated, and Commerce-Displayed — can only be inferred through their texts.

- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`. User-originated thematic territory and objection; the proposed bridge and product titles remain `llm-proposed`.
- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`. Derivative restatement of the bridge, not independent evidence.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
