---
status: working
attribution: user-confirmed
updated: 2026-09-04
sources:
  - SRC-2026-09-03-chatgpt-brainstorming
  - SRC-2026-09-04-claude-collection-v0.4-survey
  - SRC-2026-09-04-gemini-product-image-system-survey
  - SRC-2026-09-04-glm-product-image-system-survey
  - SRC-2026-09-04-grok-product-image-system-survey
---

# Progressive Displacement

## Principle

> “I thought I understood the rules of this work, and then, in the next moment, those rules operated in another way.”

The user explicitly supported this experience as a compelling artistic principle. An LLM named it `Progressive Displacement`. The English name has `attribution: llm-proposed`; the principle itself has `attribution: user-confirmed`.

## Experience Rhythm

1. **Recognition** — The visitor discovers the rules of the store and the work.
2. **Mastery** — The visitor believes they understand those rules.
3. **Displacement** — The same rules produce a different and unexpected result.

Repeat this cycle through small reversals so that visitors continue exploring even after they understand the concept.

## Constraint

Surprise must arise from a product's properties and the rules of commerce, not from an arbitrary random event. For example, the order status of `Yesterday` being `Delivered yesterday` follows from its logic; an unrelated visual joke does not.

**(2026-09-04, `llm-proposed`)** Claude's v0.4 survey raised two additional constraints.

1. **One emotional temperature** — If all 30 v0.4 products share the same emotional temperature—quiet loss—Displacement cannot operate in practice. Claude argues that Displacement occurs not through grammatical variation but through **emotional betrayal**. If the rules change but the mood does not, the visitor finishes understanding the work by the third product.
2. **Control of viewing order** — For this principle to work, the store must control the visitor's viewing order to some degree. In a freely browsed catalog, the first three products are random and can neutralize the whole design. Claude sees this as a **site-structure problem**, not a product problem, and argues that it must be decided before v0.5.

**(2026-09-04, `llm-proposed`)** Three Product Image System surveys independently repeated the risk of **premature closure of the visual grammar**. If one ASCII style is applied to the whole Catalog, visitors may see a few products, complete the rule as “a store that converts abstract products into ASCII,” and read subsequent images as variations of one style or as wallpaper rather than displacement. Numerical estimates such as closure after 3–10 exposures are model predictions, not audience data.

Using multiple renderers under one imaging policy emerged as an alternative, but it is not an automatic solution. If Product Grammar maps too directly to renderer, visitors can learn a new taxonomy and close interpretation again. A mixed-policy catalog must therefore test when rule learning occurs, whether visitors voluntarily re-examine earlier images, and whether exceptions genuinely update their model. See [[product-image-system]].

## Design Implications

- Use a different commerce function as the primary collision for each product (`attribution: llm-proposed`).
- Product cards, product details, the cart, checkout, and order history can each reveal a new collision (`attribution: llm-proposed`).
- Discoveries not essential to basic understanding can create depth (`attribution: llm-proposed`).
- **(2026-09-04, `llm-proposed`, unadopted)** Claude proposed a sequence of 10 products selected from v0.4. Its central design move is a **deliberate retreat** in position six: after destroying the emotional frame, give it back and betray it again, producing stronger displacement than a monotonically rising sequence. The full sequence appears in `SRC-2026-09-04-claude-collection-v0.4-survey` (§13) and is not repeated here. This also connects to [[Q-006-post-purchase-behavior]] because Claude sees the post-purchase timeline, rather than product display, as the greatest opportunity for Displacement.

## Related

- [[conceptual-contrast]]
- [[commerce-as-medium]]
- [[Q-001-comprehensibility-vs-mystery]]
- [[Q-006-post-purchase-behavior]] — Claude argues that the greatest opportunity for Displacement lies in the post-purchase timeline rather than product display.
- [[v0.4-evaluation]] — Contains the detailed basis for the critique of one emotional temperature and the proposed 10-stage displacement sequence.
- [[product-image-system]] — Covers the risk that repetition of a single visual grammar closes displacement and the proposed mixed-policy prototypes.

## Sources

- `SRC-2026-09-03-chatgpt-brainstorming` — `raw/conversations/ChatGPT-brain-storming-20260903-2252.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`. An `llm-proposed` survey that does not confirm the Principle.
- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`. An `llm-proposed` survey that raises the risk of closure through repeated ASCII.
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`. An `llm-proposed` survey that raises the same risk and proposes a mixed-policy catalog test.
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`. An `llm-proposed` survey that raises the same risk and proposes audience testing.
