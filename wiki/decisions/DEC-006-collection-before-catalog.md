---
status: confirmed
attribution: user-confirmed
updated: 2026-09-04
sources:
  - SRC-2026-09-04-commerce-product-rnd-summary
---

# DEC-006 — Discover Product Grammar Through a Collection Before Expanding the Catalog

## Status

accepted (2026-09-04)

## Context

To resemble a real e-commerce service, the final store needs a Catalog of 100–200 or more products rather than 14. That scale creates the density of search, categories, recommendations, pagination, sold-out states, and the long tail. This requirement develops the “quality of a real commercial service” confirmed in [[DEC-002-perfect-store-principle]] at the level of Catalog scale.

## Decision

Do not build the Catalog now. First make the product grammar concrete and refine it through a Collection, then expand into a Catalog. The source wording is: “The current Collection is not the final product list; it is an R&D Set for discovering the Product Grammar of OTHER GOODS.”

## Why

Creating 100–200 products while the grammar is unstable would mass-produce weak products and require all of them to be revised when the grammar changes. The user explicitly preferred the sequence Collection → Catalog.

## Alternatives Considered

The conversation also considered discovering the grammar while immediately building the Catalog, but rejected that option. Scale does not substitute for quality.

## Consequences

The Collection changes from a “final product list” into an “R&D Set,” which also changes how it is evaluated. The point at which R&D ends and Catalog work begins remains undecided; see [[Q-004-rnd-collection-exit-condition]]. The minimum strength of a long-tail product during Catalog expansion is also unresolved.

## Sources

- `SRC-2026-09-04-commerce-product-rnd-summary` — `raw/conversations/2026-09-04-commerce-product-rnd-summary.md`. This source is a derivative summary of the 2026-09-03–04 brainstorming rather than the original conversation transcript.

## Related

- [[rnd-collection]]
- [[Q-004-rnd-collection-exit-condition]]
- [[DEC-002-perfect-store-principle]] — The requirement for Catalog scale derives from this principle.
