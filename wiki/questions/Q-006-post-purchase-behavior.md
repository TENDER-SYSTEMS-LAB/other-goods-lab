---
status: unknown
attribution: llm-proposed
updated: 2026-09-05
sources:
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

# Q-006 — What Happens After Payment?

## Question

What happens to the visitor after purchasing a product? Is the post-payment experience designed, from order confirmation, shipping, and receipt through order history and repurchase notifications after time has passed?

## Why it matters

To quote Claude's survey observation: the decisive difference between e-commerce and other media is **that it continues to reach the visitor after the transaction is complete**. A gallery ends when the visitor leaves, but a shopping site sends email even six months later. Concrete examples: the real event of 02 (`Yesterday`) occurs not on the product page but in order history six months later; the real event of 09 (`The Upper-Right Corner Dented During Shipping`) occurs in the response to an exchange request.

This directly connects to [[progressive-displacement]] — the claim is that the greatest opportunity for Displacement lies not in display but afterward. It also connects to [[conceptual-contrast]]'s problem of “not becoming a joke”: Claude's criterion is “if the laughter resolves within the page, it is a joke; if consequences remain after payment, it is a work.”

## Current State

This Wiki has no page dealing with the post-payment stage. Claude diagnoses that all 30 v0.4 products have been designed only to the product-page level. It is a blank area where the question has never been raised.

## Discussed Approaches

Claude proposed a `Post-Purchase Behavior` field with four items: (1) what happens at order confirmation; (2) how shipping and receipt are handled; (3) how it appears in order history six months later; (4) what the system returns when return or repurchase is attempted.

Claude proposed making this field mandatory and removing products for which an answer cannot be written, arguing that this one filter simultaneously resolves three things: eliminating Poetry Risk, enforcing Commerce Necessity, and creating time-axis Displacement. The conclusion is that reducing 30 products to 12 before expanding them to 40 is the proper work of v0.5.

All of this is `llm-proposed` and unadopted.

## The v0.5 round — cross-validated, still unadopted

**(2026-09-04)** The single-source dependency noted below is now resolved. Four independent v0.5 surveys each ran Claude's four-item post-purchase test on their own Top 8, and **all four named the transaction and post-purchase layer as the single most important thing to build before v0.6.** This is the strongest convergence in the round; it remains four `llm-proposed` opinions, not a user decision.

They split on whether the field should be mandatory.

- **YES, for every product** — Gemini (“the fulfillment logic is the actual art piece”) and GLM, with a distinction worth keeping: mandatory as a **test**, not as a **feature**. GLM's reasoning is that the test does not force mechanics but forces honesty — if the honest answer is “nothing meaningful happens after payment,” the product is Commerce-Displayed and the catalog must ration those. It notes that `$8.00 Price Drop`, despite strong commerce-nativeness, is the one product that does not obviously deepen after purchase.
- **ONLY FOR SOME PRODUCT TYPES** — Grok (mandatory for referent-drift, commerce-native, and condition-collapse products; optional for pure perception or byproduct objects) and Kimi (mandatory for Commerce-Generated and Commerce-Activated; forcing it on Displayed products manufactures gimmicks). Kimi's discriminating test: *does post-purchase behavior reveal something the product page could not?*

Their scope proposals differ correspondingly: design the flow for exactly one abstract product (Gemini), for the top eight (GLM), or for every retained product with removal of those that add only gimmick (Grok, Kimi).

The concrete post-purchase designs the four produced overlap closely on the same products — `Yesterday` sold by subscription and false in order history six months later; `First Canceled Order` whose confirmation *is* its cancellation and whose repurchase creates a different product; `Day After the Return Window Closed`, where the return interface exists and always rejects, and the rejection message is the product's content; `Upper-Right Corner, Dented in Transit`, where requesting a replacement destroys the item purchased. These are recorded in [[v0.5-evaluation]] rather than repeated here. All are `llm-proposed`.

GLM adds an adjacent blind spot that no other survey raises and that this question does not currently cover: **price**. It argues price is treated everywhere as a display field and nowhere as a conceptual surface, and that at catalog scale arbitrary prices will read as arbitrary. Single-source; recorded in [[v0.5-evaluation]] and in [[current-state]] as an open question without its own page.

## Proposed v0.6 lifecycle instrument

**(2026-09-05)** A later conversation combined the survey proposals into a `Product Behavior Sheet` for a possible Deep R&D Set. Proposed fields are: customer-facing name; Korean working meaning; register; product role; Commerce type; price and price logic; inventory and inventory logic; order confirmation; fulfillment; six-month order-history behavior; return; repurchase; representation; and a failure test asking what disappears when Commerce is removed.

The same conversation refined the scope: post-purchase should be designed when it expands the product's meaning, not attached to every product as a compulsory gimmick. The sheet may still be mandatory as a diagnostic even where the honest result is “no additional mechanic.” Both the sheet and this distinction are `llm-proposed` and unadopted.

The derivative position note expands the proposed sheet with **Product Grammar**, an explicit **delivery** field, and **resale behavior where relevant**. It also makes price and inventory tests concrete: every product should explain why it costs that amount, what counts as one unit, whether one purchase reduces another visitor's availability, and how or whether stock replenishes. This is elaboration of the same proposal, not independent convergence.

**(2026-09-05, `llm-proposed`)** The six critiques split 3/3 between universal and selective lifecycle design and unanimously warn that the Behavior Sheet can become too heavy. They retain a customer-facing name, price logic, and Failure Test; inventory logic is essential to five and selective to GLM. Five directly retain order-history/lifecycle recording, while GLM emphasizes default-policy deviations. Proposed fields include unit definition, purchase promise, customer/system action, unresolved remainder, third party, support posture, and tax/shipping. None is a final sheet.

## Unresolved subproblems

- What do “shipping” and “receipt” physically mean in this work? Does the visitor actually receive something? This has been an open question since 2026-09-03.
- A separate constraint identified by Claude: for the [[progressive-displacement]] sequence to hold, the shopping site must control visitor browsing order to some extent, but in free Catalog browsing the first three products are determined at random and the design loses force. This is not a product problem but a site-structure problem.

## Related

- [[progressive-displacement]] — Basis for the claim that the post-payment design raised by this question is Displacement's greatest opportunity.
- [[v0.4-evaluation]] — Both the evaluation from which this question emerged and the source of the diagnosis that all 30 products leave this area blank.
- [[conceptual-contrast]] — Connects to the claim that the “not becoming a joke” criterion is determined by whether a post-payment experience is designed.
- [[commerce-as-medium]] — The argument that the ability to reach visitors after a transaction ends is an asset unique to e-commerce as a medium.
- [[DEC-002-perfect-store-principle]] — If real-commercial-service density is required, order confirmation, shipping, and order history must be included in that density.
- [[v0.5-evaluation]] — The four-survey round that cross-validated this question and produced the concrete post-purchase designs.
- [[Q-005-commerce-generative-vs-display]] — Three of the four surveys propose the post-purchase test as the practical way to identify Commerce-Displayed products.
- [[Q-008-product-or-transaction]] — Real payment determines the substrate for post-purchase behavior.

## Sources

- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`
- `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, `SRC-2026-09-04-kimi-collection-v0.5-survey` — the four v0.5 surveys under `raw/surveys/`.

The five survey sources above are `llm-proposed`, not user decisions. When this page was created, Claude's v0.4 survey was its only source and Gemini's v0.4 survey did not address the topic, so the page carried a single-source dependency; the v0.5 round removed it. Neither the v0.4 nor the v0.5 evaluation prompt is registered in this repository, and whether the four v0.5 models answered independently of one another cannot be verified from the responses alone.

- `SRC-2026-09-05-chatgpt-v0.6-rnd` — `raw/conversations/conversation-20260905-0007.md`. Synthesizes the earlier proposals into an unadopted lifecycle sheet and v0.6 framing.
- `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` — `raw/conversations/2026-09-04-chatgpt-pre-v0.6-rnd-position.md`. A derivative position note that elaborates the sheet and explicitly recommends delaying v0.6 composition.
- `SRC-2026-09-04-claude-pre-v0.6-rnd-position`, `SRC-2026-09-04-deepseek-pre-v0.6-rnd-position`, `SRC-2026-09-04-glm-pre-v0.6-rnd-position`, `SRC-2026-09-04-grok-pre-v0.6-rnd-position`, `SRC-2026-09-04-kimi-pre-v0.6-rnd-position`, and `SRC-2026-09-04-qwen-pre-v0.6-rnd-position` — six `llm-proposed` critiques; their shared prompt and independence are unverified.
