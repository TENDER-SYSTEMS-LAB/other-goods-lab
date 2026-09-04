---
status: working
attribution: user-confirmed
updated: 2026-09-05
sources:
  - SRC-2026-09-03-chatgpt-brainstorming
  - SRC-2026-09-04-claude-collection-v0.4-survey
  - SRC-2026-09-04-gemini-product-image-system-survey
  - SRC-2026-09-04-glm-product-image-system-survey
  - SRC-2026-09-04-grok-product-image-system-survey
  - SRC-2026-09-04-gemini-collection-v0.5-survey
  - SRC-2026-09-04-glm-collection-v0.5-survey
  - SRC-2026-09-04-grok-collection-v0.5-survey
  - SRC-2026-09-04-kimi-collection-v0.5-survey
  - SRC-2026-09-04-claude-pre-v0.6-rnd-position
  - SRC-2026-09-04-deepseek-pre-v0.6-rnd-position
  - SRC-2026-09-04-glm-pre-v0.6-rnd-position
  - SRC-2026-09-04-grok-pre-v0.6-rnd-position
  - SRC-2026-09-04-kimi-pre-v0.6-rnd-position
  - SRC-2026-09-04-qwen-pre-v0.6-rnd-position
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

**(2026-09-04, `llm-proposed`)** Four v0.5 surveys addressed the principle directly, and two results bear on it.

1. **A new constraint: alternation can become the formula.** GLM warns that the v0.5 correction “added cold objects rather than discriminating among warm ones,” producing a collection organized as poles — tender-personal against cold-institutional — with a thin middle. If displacement is delivered by warm/cold alternation, the alternation is itself a learnable rule, and the principle fails the same way a single visual style would. Its prescription is to cut within the sentimental family rather than keep balancing by adding cold products, and to build out the ordinary middle register, which is what makes a store feel like a store rather than a designed contrast. This qualifies Claude's v0.4 “emotional betrayal” constraint above: betrayal that arrives on a schedule stops being betrayal.
2. **Four models given the same 24 products chose four different openings.** Each proposed its own ten-step sequence, opening with `First Typo in a New Notebook` (Gemini), `Residual Warmth on a Park Bench` (Grok), `The Room Before It Became Home` (GLM), and `Third Door Opened Today` (Kimi). Because Claude's v0.4 observation is that the visitor fixes the genre from the first three or four products, the opening is the load-bearing choice — and it is precisely where the surveys do not converge. Three of the four nonetheless close on an ordinary or commerce-native product rather than a climax; GLM ends on `12 Stairs, Never Counted` so that “the store exits into the visitor's building.”

The sequences themselves are in [[v0.5-evaluation]] and are not repeated here. None is adopted.

**(2026-09-05, `llm-proposed`)** Six further responses support a neutral, uniform system handling products of variable temperatures. They also warn that a uniformly “special” 12–16-product set can read as an exhibition rather than a catalog; ordinary stock and default behavior may be structurally necessary for realism and displacement.

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
- [[v0.5-evaluation]] — Holds the four proposed displacement sequences and the warning that warm/cold alternation can itself become the formula.
- [[Q-007-product-naming-register]] — Connected because a legible naming template is another rule a visitor can learn, closing interpretation in the same way.

## Sources

- `SRC-2026-09-03-chatgpt-brainstorming` — `raw/conversations/ChatGPT-brain-storming-20260903-2252.md`
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`. An `llm-proposed` survey that does not confirm the Principle.
- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`. An `llm-proposed` survey that raises the risk of closure through repeated ASCII.
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`. An `llm-proposed` survey that raises the same risk and proposes a mixed-policy catalog test.
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`. An `llm-proposed` survey that raises the same risk and proposes audience testing.
- `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, `SRC-2026-09-04-kimi-collection-v0.5-survey` — the four v0.5 surveys under `raw/surveys/`. All `llm-proposed`; each proposes a displacement sequence, and none confirms the Principle.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
