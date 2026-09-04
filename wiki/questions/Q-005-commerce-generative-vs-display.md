---
status: unknown
attribution: llm-proposed
updated: 2026-09-04
sources:
  - SRC-2026-09-04-gemini-collection-v0.4-survey
  - SRC-2026-09-04-claude-collection-v0.4-survey
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

## Current State

Unresolved. [[DEC-007-ontology-before-commerce]] remains `confirmed` / `user-confirmed`; this question does not invalidate it. The surveys are `llm-proposed`, and the two models point in opposite directions, so there is not even consensus. User judgment is required.

Three possible conclusions are: (a) retain DEC-007 and reject Claude's claim; (b) revise DEC-007 to permit both starting points; (c) make a new decision that replaces DEC-007. None has yet been selected.

## Related

- [[DEC-007-ontology-before-commerce]] — The decision challenged by this question, but a challenge does not itself overturn a decision.
- [[v0.4-evaluation]] — The evaluation itself in which the two judgments behind this question emerged.
- [[commerce-as-medium]] — This question overlaps with whether Commerce should be seen as a medium or an ontology-producing institution.
- [[product-grammar]] — The claim that the Commerce-generative/Commerce-display axis can replace the existing 25-Grammar taxonomy is at stake.
- [[DEC-006-collection-before-catalog]] — The absence of this criterion poses a practical risk when expanding to a 200-product Catalog.

## Sources

- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`

Both sources are `llm-proposed`, not user decisions. The original v0.4 Evaluation Prompt is not separately registered in this repository, so what the two surveys actually responded to can only be inferred through their texts.
