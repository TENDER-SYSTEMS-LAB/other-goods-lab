# OTHER GOODS Lab

**A store for other kinds of goods.**

OTHER GOODS is an interactive conceptual art project that explores the conceptual collision created when a polished e-commerce system treats things that cannot be owned or delivered—such as time, memory, sensation, and moments—as ordinary merchandise.

This repository does not contain the work's application code. It is an R&D repository and long-term memory for what the work is becoming. It preserves primary materials such as conversations and surveys, then continuously updates a connected Wiki of decisions, hypotheses, questions, and changes.

## What the Work Asks

> What happens when a completely normal commerce system treats something that cannot be a product as though it were one?

OTHER GOODS does more than imitate the appearance of a store. It uses the full set of familiar commerce rules—price, inventory, search, recommendation, cart, checkout, shipping, ownership, and returns—as the medium of the work. Visitors feel that they are using a normal store, yet repeatedly encounter things those rules cannot handle.

The current confirmed direction is:

- The first standalone work focuses on **OTHER GOODS / Commerce**.
- The store aims for the quality of a real commercial service rather than parody.
- Products do not depend on external IP such as specific works or characters.
- The project discovers a Product Grammar through an R&D Collection before expanding a final Catalog.
- Product ideas begin with “what kind of thing is this?” before commerce functions are applied.

## Work in Progress

As of 2026-09-04, the project is not selecting a final first product list. It is **developing a grammar for deciding what can become an OTHER GOODS product**.

- The R&D Collection has reached v0.4 with 30 candidates. It is a research set for comparison and elimination, not the final collection.
- The scope of Product Grammar, the balance between emotive and dry products, and the exit conditions for R&D remain open.
- The Product Image System is considering several renderers governed by one store policy instead of applying one ASCII style globally. This is a `hypothesis`, not a user decision.
- Real payment, post-purchase experience, and product-specific rules for price, inventory, shipping, and returns have not yet been designed.

## Timeline

- **2026-09-03** — Initialized the Wiki; established the project name, tagline, statement seed, and Commerce-first scope; and collected evaluations of the first 14 product candidates from three agents.
- **2026-09-04** — Expanded the Collection to 30 candidates in v0.4 and separated Product Grammar from the key decisions and questions. Synthesized three Product Image System surveys into a multi-renderer hypothesis and a prototype program.

The [Activity Log](wiki/log.md) preserves the detailed history in chronological order.

## How This Repository Builds Memory

The repository has three layers:

- [`raw/`](raw/) — the Source of Truth, preserving original conversations, documents, and surveys without alteration.
- [`wiki/`](wiki/) — the synthesis layer, comparing and connecting multiple sources to maintain the best current understanding.
- [`schema.md`](schema.md) and [`AGENTS.md`](AGENTS.md) — the operating layer, defining Wiki structure, provenance, ingestion, language, and maintenance rules.

Unlike ordinary document search, each new source prompts updates to the relevant Wiki pages and their relationships. The Wiki is therefore not a search result reconstructed from scratch for every question; it is a persistent body of knowledge that becomes more precise over time.

## Where to Start

- [Current State](wiki/current-state.md) — a snapshot of what is confirmed, in progress, and still unknown.
- [Project Overview](wiki/overview.md) — the work's definition, identity, central question, and principles.
- [R&D Collection](wiki/collections/rnd-collection.md) — how product candidates changed from v0.1 through v0.4.
- [Product Image System](wiki/concepts/product-image-system.md) — the current hypothesis that treats product images as a representation policy rather than one style.
- [Wiki Index](wiki/index.md) — the working catalog of every Wiki page by type.

In the Wiki, `confirmed` denotes material accepted by the user, while `working` and `hypothesis` denote ongoing or unverified material. LLM proposals are not recorded as decisions until the user adopts them. Each page's `Sources` section identifies the underlying material and any provenance limits.

## Language and Translations

English is the canonical language of the repository and the default language shown to public readers. All maintained documentation and future Wiki work are written in English. Registered raw sources remain in their original language because they are immutable evidence; their promoted summaries and interpretations are written in English.

When public translations are added, localized entry points will use names such as `README.ko.md`, `README.zh-CN.md`, and `README.ja.md`, with `README.md` remaining the canonical English version. Larger translated document sets may mirror canonical paths under `docs/i18n/<locale>/`. Translations must link to the English source, remain clearly labeled, and must not introduce project facts or decisions that do not exist in the canonical version.

## Working in This Repository

Human readers should begin with [Current State](wiki/current-state.md). Follow [`raw/README.md`](raw/README.md) when adding source material. Agents must read [`AGENTS.md`](AGENTS.md) and [`schema.md`](schema.md) first. The [Wiki Index](wiki/index.md), rather than this README, provides the complete page map and editing destinations.
