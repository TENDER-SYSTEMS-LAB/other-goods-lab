---
status: working
attribution: jointly-developed
updated: 2026-09-07
sources:
  - SRC-2026-09-03-llm-wiki-agent-prompt
  - SRC-2026-09-03-chatgpt-brainstorming
  - SRC-2026-09-04-commerce-product-rnd-summary
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

# Commerce as Medium

## Meaning in OTHER GOODS

Commerce is not a shape that contains the work; it is the medium through which the work operates. The full set of commerce rules—product cards, price, inventory, search, recommendation, cart, checkout, shipping, reviews, returns, and order history—becomes its material.

On 2026-09-04, this idea was sharpened: Commerce is not a Product Idea Generator but a **collision device that amplifies Product Ontology**.

## How It Works

Visitors do more than look at the work. They search, compare, add things to a cart, and consider purchase and ownership. An important part of the work is the process in which a visitor naturally enters familiar commercial behavior, then realizes they have tried to buy and own something that is not a product.

An LLM proposed making a different commerce function the central collision for each product. The user explicitly supported the principle that visitors should discover a different operation just when they think they have learned the rules. See [[progressive-displacement]].

The structure was later divided into two layers. Commerce Collision asks, “Which commercial assumption breaks when this is treated as a product?” This is Layer 2. Product ideas themselves begin in Layer 1, Product Ontology or Product Grammar, with Commerce applied afterward. A commerce function is not the product's identity but the “surface of collision,” and is recorded separately from Product Grammar.

For example, `The First Typo in a New Notebook` has New ↔ Used as its Primary Commerce Collision, while `Summer at Sixteen` has SKU ↔ Individual Experience. See [[product-grammar]] for Product Grammar itself and the full candidate set.

## Boundaries

- This is not a parody built from deliberately broken UI or a funny fake store.
- The store does not explain the meaning of the work directly.
- Technologies such as blockchain and AI are used only when they strengthen the conceptual collision. The technology itself is not the subject.
- A good OTHER GOODS product need not be Commerce-native. Ontologically strange products and products that come alive only within Commerce must coexist, preventing visitors from classifying the work too quickly as a “store that sells memories,” a “store that sells time,” or “conceptual art that twists e-commerce.”

## Evolution

The early Wiki lacked the original conversation behind this concept and knew its provenance only through a secondary citation. Once `SRC-2026-09-03-chatgpt-brainstorming` was registered, it directly established that the user had proposed combining a conventional mobile e-commerce UI with content that cannot be sold.

**2026-09-04 — Commerce moved from origin to amplifier.** Previous state: an LLM proposal assigned one commerce function as the central collision for each product. Transition: while building R&D Collection v0.3, Commerce functions such as Return, Review, Cart, and Shipping began to be treated as Product Grammars, and the user observed that “the entire Product Grammar is excessively e-commerce-like.” Current state: separate Product Ontology (Layer 1) from Commerce Collision (Layer 2), and begin ideas in Layer 1. See [[DEC-007-ontology-before-commerce]].

**2026-09-05, `llm-proposed` challenge.** Six pre-v0.6 critiques distinguish Commerce as a semantic agent from Commerce as a container. They propose a minimum test: at least one commerce operation must materially change a product's meaning. This is unadopted and challenges the current framing without modifying [[DEC-007-ontology-before-commerce]]. See [[Q-005-commerce-generative-vs-display]] and [[Q-008-product-or-transaction]].

**2026-09-06 — Commerce need not transform in order to be the medium.** `jointly-developed`, `status: working`. Previous state: the operative test was whether Commerce materially changes the product, which had been pushing the work toward elaborate lifecycle mechanics. Transition: that test was judged too narrow, because it penalized ontologies whose tension is declarative rather than procedural. Current state: the test becomes **"does Commerce create a tension that would not exist without it?"**, which admits products where the store does little beyond calmly asserting that the thing is merchandise.

Three consequences for this concept:

- **Assertion joins the medium's vocabulary.** The plain act of pricing, stocking, listing, and offering is now treated as a use of the medium, not as a failure to use it. This is closer to [[conceptual-contrast]]'s original operating rule — reproduce the commercial system perfectly, keep the things it handles noncommercial — than the transformation test was.
- **The medium extends past the SKU.** Some work belongs to the storefront system rather than to a product: an unavailable option, an add-on, a warranty, a checkout choice. And some belongs to the *relation between* listings, where neither page is fully intelligible alone. Cart, checkout, eligibility rules, and category adjacency become carriers of meaning in their own right, not just surfaces a product collides with.
- **A new medium state appears: the ineligible listing.** A product may have a price, inventory, a page, and specifications while being impossible to purchase — separating existence from sellability. This is a commercial state with no non-commercial equivalent, and it exists only because the medium is being operated rather than depicted.

The accompanying working transaction direction is **Product = entry point, Transaction = activation**, with simulated normal USD commerce as the v0.6 R&D assumption. See [[rnd-collection]] and [[Q-008-product-or-transaction]].

**2026-09-06, `llm-proposed` constraint.** Five critiques accept the reframing but attach the same condition in five formulations: the commercial frame must be complete and deadpan, or Assertion collapses into decoration. Qwen's version is that the interface must do "100% of the conceptual heavy lifting" through banal logistical enforcement; GLM's is that the tension must be traceable to one named commercial feature, or the product is "a displayed poem" rather than merchandise. This is a constraint on execution of the medium, not a revision of the concept, and it is unadopted. See [[pre-v0.6-evaluation-round-2]].

## Related

- [[DEC-002-perfect-store-principle]]
- [[conceptual-contrast]]
- [[progressive-displacement]]
- [[Q-001-comprehensibility-vs-mystery]]
- [[product-grammar]] — Defines Layer 1, Product Ontology.
- [[DEC-007-ontology-before-commerce]] — Records this evolution of the Commerce concept as a decision.
- [[rnd-collection]] — Records the work in which this framing changed.
- [[Q-005-commerce-generative-vs-display]]
- [[Q-008-product-or-transaction]]
- [[pre-v0.6-evaluation-round-2]] — Where the execution constraint on Commerce-as-Assertion is compared.

## Sources

- [[SRC-2026-09-03-chatgpt-brainstorming]] — [raw/conversations/ChatGPT-brain-storming-20260903-2252.md](../../raw/conversations/ChatGPT-brain-storming-20260903-2252.md)
- [[SRC-2026-09-03-llm-wiki-agent-prompt]] — [raw/documents/2026-09-03-llm-wiki-agent-prompt.md](../../raw/documents/2026-09-03-llm-wiki-agent-prompt.md)
- [[SRC-2026-09-04-commerce-product-rnd-summary]] — [raw/conversations/2026-09-04-commerce-product-rnd-summary.md](../../raw/conversations/2026-09-04-commerce-product-rnd-summary.md). This is a derivative summary rather than the original conversation transcript. If the original conversation is preserved separately, its provenance takes precedence.
- [[SRC-2026-09-04-claude-pre-v0.6-rnd-position]], [[SRC-2026-09-04-deepseek-pre-v0.6-rnd-position]], [[SRC-2026-09-04-glm-pre-v0.6-rnd-position]], [[SRC-2026-09-04-grok-pre-v0.6-rnd-position]], [[SRC-2026-09-04-kimi-pre-v0.6-rnd-position]], and [[SRC-2026-09-04-qwen-pre-v0.6-rnd-position]] — six `llm-proposed` critiques; their shared prompt and independence are unverified.
- [[SRC-2026-09-06-post-v0.5-pre-v0.6-working-decisions]] — [raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md](../../raw/conversations/2026-09-06-post-v0.5-pre-v0.6-working-decisions.md). A `jointly-developed` working-decision summary, `status: working`. It is a decision summary rather than a conversation transcript, and nothing in it is `user-confirmed`.
- [[SRC-2026-09-05-deepseek-pre-v0.6-survey]], [[SRC-2026-09-05-gemini-pre-v0.6-survey]], [[SRC-2026-09-05-glm-pre-v0.6-survey]], [[SRC-2026-09-05-grok-pre-v0.6-survey]], and [[SRC-2026-09-05-qwen-pre-v0.6-survey]] — five `llm-proposed` critiques under `raw/surveys/`. Their shared evaluation brief is not registered and does not match the working-decisions document's section numbering; despite an earlier filename date, their content places them after those working decisions. Evaluator independence is unverified.
