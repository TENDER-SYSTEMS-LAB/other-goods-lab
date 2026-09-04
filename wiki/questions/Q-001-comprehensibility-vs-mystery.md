---
status: unknown
attribution: user-originated
updated: 2026-09-04
sources:
  - SRC-2026-09-03-llm-wiki-agent-prompt
  - SRC-2026-09-03-chatgpt-brainstorming
  - SRC-2026-09-04-commerce-product-rnd-summary
  - SRC-2026-09-04-gemini-collection-v0.4-survey
  - SRC-2026-09-04-claude-collection-v0.4-survey
  - SRC-2026-09-04-gemini-product-image-system-survey
  - SRC-2026-09-04-glm-product-image-system-survey
  - SRC-2026-09-04-grok-product-image-system-survey
---

# Q-001 — The Balance Between Comprehensibility and Mystery

## Question

What must be adjusted, and how, so that the work is easy for visitors to enter but its interpretation does not close too quickly? Can it give them something to think about without becoming so difficult that they leave, and can its deep world-building become a path of voluntary discovery rather than an instruction manual?

## Why it matters

Not knowing how to use something and leaving its meaning open are different. OTHER GOODS's store interface must be familiar and immediately usable, while the meaning of purchasing and owning things that are not products must remain open in multiple directions.

## Discussed Approaches

### Low Floor, High Ceiling

An LLM proposed a layered structure in which “what is happening is easy to understand, but its meaning keeps one thinking.” The work can stand through the store alone, and additional channels such as GitHub, Instagram, and YouTube become optional rabbit holes rather than required explanations. This approach is `attribution: llm-proposed` and has not been explicitly confirmed by the user.

### Progressive Displacement

To prevent visitor boredom, an approach was discussed in which, at the moment visitors feel they understand the work's rules, the same rules begin to operate differently. The user supported this as a philosophy of the work. See [[progressive-displacement]].

### Core principle — "The interface should be immediately understandable. The work should not be."

Separate the roles: the interface is responsible for comprehensibility, while the work is responsible for incomprehensibility. This condenses into one sentence the direction already recorded in [[conceptual-contrast]] and [[DEC-002-perfect-store-principle]].

### Mixing Product Roles Within the Collection

Mix products in different roles, such as Broad Hook, Conceptual Anchor, Polarizer, System Piece, and Dry Counterweight. Do not gather only products with high average scores. This is a `user-confirmed` direction.

### Accessibility / Freshness / Residue Evaluation Axes

An attempt to measure this balance at the product level. It is organized in [[rnd-collection]]. This framework has not yet been verified.

[[progressive-displacement]] is also a partial answer to this question, and `SRC-2026-09-04-commerce-product-rnd-summary` reconfirmed it (the Recognition → Mastery → Displacement rhythm).

## Current State

Some partial direction has emerged, but the question remains open. Progressive Displacement gives a principle for the rhythm of exploration, but it does not settle the overall difficulty of the work, the amount of information exposed, or the actual scope of its world-building.

Newly surfaced subquestions:

- What is the appropriate proportion of emotional/human products to dry products?
- How can Grammars such as Boundaryless and Counterfactual be made concrete enough that they do not appear excessively poetic?
- What should be measured in actual audience testing?

Because it is a `user-confirmed` direction that virtual-persona evaluation is only an auxiliary simulation tool and does not substitute for real audiences, this question will not close before actual audience testing.

**2026-09-04.** Two v0.4 surveys provided the first quantitative evidence for this question. Claude counted 13 of 30 (43%) as Type 2 products that are immediately consumed as “Oh, this is that kind of emotional product,” and Gemini likewise identified a nostalgia bias as the greatest risk. The products both surveys identified as risky are 01, 08, 13, 15, and 24.

Claude also made a structural observation: **the problem is not proportion but the order of contact** — visitors determine the genre from the first three or four products in the list, so if 01 and 16 appear at the top, all remaining 28 products will be read within that frame. This is not a problem of product selection but of exposure order, and it connects to [[progressive-displacement]] and [[Q-006-post-purchase-behavior]].

All of this is `llm-proposed`, and the question remains open.

**2026-09-04.** The three Product Image System surveys found the same problem recurring at the image layer. If a single ASCII style repeats across the entire Catalog, visitors may close the work after a few products with the explanation “this store converts concepts into ASCII,” flattening the differences among more than 100 products under the same style. All three responses selected Option C, which demotes ASCII to one renderer within a larger Representation System, but they did not agree on ASCII's own conceptual necessity. This shows that comprehensibility is at stake not only in explanatory copy or product arrangement but also in **the learnability of the image policy**. See [[product-image-system]] for details. Because this is not actual audience data, the question remains `unknown`.

## Related

- [[commerce-as-medium]]
- [[progressive-displacement]]
- [[other-goods-as-entity]]
- [[current-state]]
- [[rnd-collection]] — The work in which this question's evaluation axes (Accessibility/Freshness/Residue) are actually applied.
- [[product-grammar]] — Records the candidate Grammars related to mixing product roles within the Collection.
- [[v0.4-evaluation]] — Detailed basis from the 2026-09-04 v0.4 surveys regarding the proportion of emotional products and exposure order.
- [[product-image-system]] — Addresses the unresolved problem of premature closure through a single image grammar and a multiple-renderer policy.

## Sources

- `SRC-2026-09-03-chatgpt-brainstorming` — `raw/conversations/ChatGPT-brain-storming-20260903-2252.md`
- `SRC-2026-09-03-llm-wiki-agent-prompt` — `raw/documents/2026-09-03-llm-wiki-agent-prompt.md`
- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`. This is a derivative summary rather than the original conversation transcript; if the original conversation is preserved separately, its provenance takes precedence.
- `SRC-2026-09-04-gemini-collection-v0.4-survey` — `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md`. It is `llm-proposed`, and the original v0.4 evaluation prompt is not in the repository.
- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`. It is `llm-proposed` and has the same provenance limitation described above.
- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`. It is `llm-proposed` and raises the risk of premature closure through an image rule.
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`. It is `llm-proposed` and explicitly states that it relied on a text description rather than actual pixels.
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`. It is `llm-proposed` and raises the same risk.
