---
status: unknown
attribution: llm-proposed
updated: 2026-09-07
sources:
  - SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position
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

# Q-008 — Is the Unit of the Work the Product or the Transaction?

## Question

Is the atomic unit a listing/product, or a state-changing transaction? Does real money move, or is commerce simulated? These are linked but separable decisions.

## Why It Matters

The answer determines whether price, checkout, refunds, order history, fulfillment, and post-purchase states are representational or operational. It also determines what counts as a complete prototype and what the Behavior Sheet must test.

## Evidence From the Six Critiques

Claude directly raises real money. GLM directly couples product-versus-transaction with real exchange. DeepSeek reframes Commerce as semantic agent versus container. Qwen asks for the minimum meaning-changing commerce operation. Grok and Kimi supply adjacent constraints rather than the same direct question.

## Two Axes

- Product-centered versus transaction-centered.
- Simulated exchange versus real exchange.

No quadrant is selected.

## Consequences to Test

- Substrate for order history and refunds.
- Real customer commitment and stakes.
- Fulfillment cost and operational responsibility.
- Legal and ethical review if money moves.
- Whether a product page can ever be sufficient by itself.

## The 2026-09-06 Working Direction

`jointly-developed`, `status: working`. The working decisions take a position on the **first** axis and a provisional position on the second.

> **Product = entry point. Transaction = activation.**

The product remains a meaningful artistic unit; the transaction may activate, expose, transform, or simply frame that ontology. This resolves neither quadrant into a decision, but it declines the pure transaction-centered reading: the atomic unit is not replaced by the transaction, it is completed by it.

On the second axis the source states a scope limit rather than an answer: **for v0.6 R&D the working assumption is to simulate normal USD commerce**, rather than making real-money settlement the focus of the experiment. It records this as revisitable and explicitly not a permanent public-release settlement decision.

Two adjacent working positions bear on this question:

- **A third unit type now exists.** Some work may belong to the storefront system rather than to a SKU — the working example being `Control Over Final Outcome — Unavailable` as an unavailable option, add-on, warranty, or checkout choice. Two consecutive critique rounds (6/6, then 5/5) place it at system level. This broadens the atomic-unit question beyond product-versus-transaction to **product / relationship / system behavior**.
- **Sellability is separable from existence.** The Tolerance Pair holds a product that has a price, inventory, and a page while being ineligible for purchase. A transaction that *cannot occur* becomes a designable state, which is a case neither axis above anticipated.

**(2026-09-06, `llm-proposed`)** The five critiques do not reopen real payment. None of the twelve forced questions asks about it, and none of the five raises it unprompted as the most important unresolved question — a marked change from the previous round, where real money was the strongest unresolved cluster. Their attention moved to whether the simulated frame is *credible*: DeepSeek conditions Commerce-as-Assertion on "a complete and credible commercial frame," and Qwen on the interface enforcing "the logistical, financial, and bureaucratic realities" of buying. Whether that shift reflects the brief's framing or genuine agreement cannot be determined, because the brief is not registered. See [[pre-v0.6-evaluation-round-2]].

## Current State

**Partially directed, not decided.** `Product = entry point, Transaction = activation` is a `jointly-developed` working direction, not a user confirmation, and the simulated-USD assumption is scoped to v0.6 R&D. Whether real money moves in any public edition remains `unknown`. The question must not be answered through survey vote. v0.6 remains uncomposed, and no transactional surface exists in this repository.

## Related

- [[commerce-as-medium]]
- [[Q-005-commerce-generative-vs-display]]
- [[Q-006-post-purchase-behavior]]
- [[Q-004-rnd-collection-exit-condition]]
- [[pre-v0.6-evaluation]]
- [[pre-v0.6-evaluation-round-2]]
- [[rnd-collection]] — Holds the working transaction direction, the three R&D unit types, and the Tolerance Pair.

## Sources

- [[SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position]] — [raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md](../../raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md); the derivative position under review.
- [[SRC-2026-09-04-claude-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-claude-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-claude-pre-v0.6-rnd-position.md); `llm-proposed` critique.
- [[SRC-2026-09-04-deepseek-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-deepseek-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-deepseek-pre-v0.6-rnd-position.md); `llm-proposed` critique.
- [[SRC-2026-09-04-glm-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-glm-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-glm-pre-v0.6-rnd-position.md); `llm-proposed` critique.
- [[SRC-2026-09-04-grok-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-grok-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-grok-pre-v0.6-rnd-position.md); `llm-proposed` critique.
- [[SRC-2026-09-04-kimi-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-kimi-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-kimi-pre-v0.6-rnd-position.md); `llm-proposed` critique.
- [[SRC-2026-09-04-qwen-pre-v0.6-rnd-position]] — [raw/surveys/2026-09-04-qwen-pre-v0.6-rnd-position.md](../../raw/surveys/2026-09-04-qwen-pre-v0.6-rnd-position.md); `llm-proposed` critique. Real-money and legal statements are unverified LLM-proposed risk flags; the shared prompt and evaluator independence are not verified.
- [[SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions]] — [raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md](../../raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md); the `jointly-developed` working direction on this question, `status: working` and not user-confirmed.
- [[SRC-2026-09-05-deepseek-pre-v0.6-survey]], [[SRC-2026-09-05-gemini-pre-v0.6-survey]], [[SRC-2026-09-05-glm-pre-v0.6-survey]], [[SRC-2026-09-05-grok-pre-v0.6-survey]], and [[SRC-2026-09-05-qwen-pre-v0.6-survey]] — five `llm-proposed` critiques. Their shared brief is not registered, so the absence of real-money questions in that round cannot be distinguished from the brief not asking about it.
