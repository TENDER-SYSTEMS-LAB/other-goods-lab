---
status: unknown
attribution: llm-proposed
updated: 2026-09-04
sources:
  - SRC-2026-09-04-claude-collection-v0.4-survey
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

## Unresolved subproblems

- What do “shipping” and “receipt” physically mean in this work? Does the visitor actually receive something? This has been an open question since 2026-09-03.
- A separate constraint identified by Claude: for the [[progressive-displacement]] sequence to hold, the shopping site must control visitor browsing order to some extent, but in free Catalog browsing the first three products are determined at random and the design loses force. This is not a product problem but a site-structure problem.

## Related

- [[progressive-displacement]] — Basis for the claim that the post-payment design raised by this question is Displacement's greatest opportunity.
- [[v0.4-evaluation]] — Both the evaluation from which this question emerged and the source of the diagnosis that all 30 products leave this area blank.
- [[conceptual-contrast]] — Connects to the claim that the “not becoming a joke” criterion is determined by whether a post-payment experience is designed.
- [[commerce-as-medium]] — The argument that the ability to reach visitors after a transaction ends is an asset unique to e-commerce as a medium.
- [[DEC-002-perfect-store-principle]] — If real-commercial-service density is required, order confirmation, shipping, and order history must be included in that density.

## Sources

- `SRC-2026-09-04-claude-collection-v0.4-survey` — `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md`

This source is `llm-proposed`, not a user decision. Gemini's survey does not address this topic separately, so there is no cross-validation. The original v0.4 Evaluation Prompt is not separately registered in this repository.
