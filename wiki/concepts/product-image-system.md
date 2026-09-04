---
status: hypothesis
attribution: llm-synthesis
updated: 2026-09-04
sources:
  - SRC-2026-09-04-gemini-product-image-system-survey
  - SRC-2026-09-04-glm-product-image-system-survey
  - SRC-2026-09-04-grok-product-image-system-survey
---

# Product Image System

## Scope and Status

This page does not ask what OTHER GOODS product images should depict. It asks **which procedures and output formats the store uses to represent things that cannot be owned**. It is a `hypothesis` synthesizing repeated signals and differences across three surveys from Gemini, GLM, and Grok. It does not mean that the user has confirmed an image policy or a role for ASCII.

All three responses chose **C — ASCII is worth exploring, but it should be one method within a broader Representation System** when forced to choose. Their confidence levels were Gemini 85%, GLM 70%, and Grok 78%. This 3/3 convergence strengthens the architectural signal against global ASCII, but it is not agreement that ASCII is structurally necessary to OTHER GOODS.

## Independent Convergence

| Repeated signal | Gemini | GLM | Grok | Synthesis |
|---|---|---|---|---|
| Repeating one ASCII style across 100–200 products lets visitors close the rule too quickly | yes | yes | yes | A global style is likely to weaken [[progressive-displacement]] |
| Risk of being misread as net.art, terminal, cyberpunk, or retro | yes | yes | yes | A normal Commerce UI cannot fully suppress genre signals inside the image slot |
| Risk that the rendering technique becomes the protagonist and flattens product diversity | yes | yes | yes | The store should not make one visual idea its face |
| Images should be results, documents, or residues of system processing rather than literal illustrations of concepts | yes | yes | yes | A shared direction, while implementation remains undecided |
| Risk that ASCII collapses into noise or arbitrary patterns for formless products | indirect | yes | yes | Stress-test silence, warmth, and absence rather than favorable cases such as flowers |
| Separate disruption inside the product-image slot from the normal Commerce shell | yes | yes | yes | Compatible with [[DEC-002-perfect-store-principle]], though overly explanatory strangeness in the images would still fail |

Here, `yes` records a claim made by a survey response, not a result observed in visitors. Numbers such as 3–10 exposures before the rule closes are model estimates rather than verified thresholds.

## Same Verdict, Different Reasons

The conclusion is shared, but the models assign different conceptual status to ASCII.

- **Gemini** — Sees a strong structural metaphor between ASCII's discrete units and Commerce's SKUs and quantities. It nevertheless judges ASCII a failure as a global style because of repetition, genre misreading, and reduced conceptual diversity.
- **GLM** — Treats the structural connection as conditional. Arbitrary glyphs are currently “a picture drawn to look like system output.” ASCII becomes structure rather than style only when actual store data—reviews, testimony, or order records—forms the substrate of the glyphs.
- **Grok** — Sees little conceptual necessity in ASCII itself. Pixels, dots, or noise could support the same explanation, and the technique risks moving the work's tension from ontology to “strange image style.”

The strongest current convergence is therefore not the **justification of ASCII**, but the **architecture of a Representation System**. Why ASCII should remain is still subject to testing.

## Working Synthesis — Imaging Policy, Not One Style

Reading the three surveys together produces the following working hypothesis (`llm-synthesis`, unconfirmed):

1. A product image should read less like an illustration of the product's meaning and more like an output issued after the store has observed, measured, recorded, packaged, or failed to process the object.
2. Unity should come from one **imaging policy and set of commercial-document conventions**, not one appearance.
3. Several renderers may be used according to a product's ontology or state, but an overly direct mapping becomes another legible filter.
4. Image changes become stronger candidates when tied to actual system state—inventory, time, purchase, location, or accumulated testimony—rather than to symbolic pictures of product names.
5. No renderer should colonize the entire Catalog. GLM proposed an upper limit of one third for any method, but that number is one model's proposal, not an agreement or decision.

GLM condensed this into a **document test**: “Is this a document procedurally issued by the store, or a picture made by the artist?” It is a useful verification question, but has not been promoted to a user principle.

## Alternative System Families

Although the three models used different names, their alternatives can be grouped into six families. This is a temporary synthesis for prototype comparison, not a final taxonomy.

| System family | Central output | Corresponding survey proposals | Main risk |
|---|---|---|---|
| Formal Failure / Absence | no image, placeholder, partial capture, reference-only record, processing-failure document | Gemini `Clinical Placeholder`, `Procedural Degradation`; GLM `Reference Only`; Grok `Absence Catalog`, `Unit Failure` | May read as lazy design, glitch art, or a one-line joke |
| Metadata / Specification | timestamp, coordinates, inventory, SKU, or specification drawing issued in the image slot | Gemini `Forensic Metadata Typography`; GLM `Specification Drawing`; Grok `Catalog Metadata as Image` | Infographic, clever poster, or excessive dryness |
| Witness / Data-substrate | reviews, testimony, or order records become the image's actual material | GLM `Witness Render`; related to Gemini's observation-output direction | Writing quality and production cost; risk that reading content overwhelms the image |
| Evidence / Container / Residue | photographs of packaging, traces, damage, or residue rather than the product itself | GLM `Container Evidence`; Grok `Evidence Residue`; partial overlap with Gemini `Extreme Obscuration` | Regression into vintage styling, emotive branding, or merchandise design |
| Measurement / Sensor Capture | outputs measuring duration, heat, sound, or density | Gemini `Algorithmic Density Graph`; GLM `Duration Exposure` | Shift into emotive photography, sci-fi thermal imagery, or data-art genres |
| State / Observer-dependent | output changes with visitor, location, time, purchase, or inventory | Gemini `Procedural Degradation`; GLM's behavior-linked direction; Grok `Observer-Dependent Capture` | May be misunderstood as random effect, or make the technical device the protagonist |

These families are not mutually exclusive styles. Witness material could be rendered as ASCII, while Duration might accompany a metadata document. The central comparison is not appearance but **which input and procedure produced the output**.

## ASCII's Current Status

Across the three survey judgments, ASCII currently has the following status (`llm-proposed`, unadopted):

- **Global Product Image System:** Effectively rejected by all three responses.
- **Renderer within a broader system:** All three see value in further exploration.
- **Conceptual necessity:** No agreement. Gemini strongly affirms it, GLM makes it conditional on a data substrate, and Grok sees it as weak.
- **Strongest survival proposal:** GLM's Witness Render, in which reviews, testimony, or order data rather than arbitrary glyphs become the actual pixel material. This is one model's specific proposal and needs its own prototype.

If ASCII remains under exploration, the surveys suggest at least these gates:

1. Does it survive with formless products such as silence, warmth, absence, or duration rather than only with a clear silhouette such as a flower?
2. Do visitors read it as `document / capture / report` rather than `terminal / retro / hacker`?
3. Do the glyphs and density arise from actual store data or product state, and would replacing them with another discrete medium change the meaning?
4. When placed beside other renderers, does it read as part of one store policy rather than breaking into an “exhibition of several styles”?

## Prototype Program (Unadopted)

Removing overlap from the three surveys produces a sequence that compares the greatest number of hypotheses at once:

1. **ASCII worst-case stress test** — Place one formed product and 3–12 formless products under the same ASCII rule in normal product cards. Use the flower only as a reference case, not as evidence of success.
2. **Same-product renderer comparison** — Render the same product through Absence, Evidence, Metadata, or Unit Failure, then compare conceptual necessity and over-explanation.
3. **Mixed-policy catalog** — Divide roughly 24 SKUs across 3–4 renderers inside a normal Commerce shell. Measure whether it reads as “one policy” or a “collection of styles,” and how many products visitors see before closing the rule.
4. **Witness substrate test** — Use actual first-person testimony or reviews as ASCII glyphs so the image and review share one data source. Observe whether discovery prompts visitors to re-examine other images voluntarily.
5. **Genre treatment A/B** — Compare a dark terminal treatment with a bright catalog or document treatment to see whether genre associations actually change.

All are `llm-proposed`; success is unknowable before real audience testing.

## Open Questions

- Which policy, framing, and metadata create unity across different renderers?
- How closely should Product Grammar connect to renderer, and where does that become literal illustration?
- How can exceptions and state changes keep [[progressive-displacement]] working after visitors reverse-engineer the image rules?
- Do general visitors understand without explanation that an image is a store “processing document”?
- Does ASCII actually shift from style to structure when actual store data becomes its substrate?

## Provenance Limit

The shared prompt and flower ASCII reference image used by the three surveys are not in the repository. The responses clearly address the same question structure, but the originals do not establish identical prompts, independent conditions, or direct image access. GLM explicitly states that it relied on a text description rather than the actual pixels. This page therefore analyzes **repeated LLM design signals**, not an agreed decision or empirical audience research.

## Related

- [[DEC-002-perfect-store-principle]] — The confirmed principle governing the boundary between a normal Commerce shell and interventions in the images.
- [[progressive-displacement]] — Premature learning of one image grammar may weaken this principle.
- [[product-grammar]] — The relation between product ontology families and renderer policy must be considered alongside the risk of over-visualization.
- [[Q-001-comprehensibility-vs-mystery]] — Premature closure of image rules and openness of interpretation are the same underlying problem.

## Sources

- `SRC-2026-09-04-gemini-product-image-system-survey` — `raw/surveys/2026-09-04-gemini-product-image-system-survey.md`. An `llm-proposed` survey.
- `SRC-2026-09-04-glm-product-image-system-survey` — `raw/surveys/2026-09-04-glm-product-image-system-survey.md`. An `llm-proposed` survey that explicitly states it relied on the provided text description rather than the actual pixels.
- `SRC-2026-09-04-grok-product-image-system-survey` — `raw/surveys/2026-09-04-grok-product-image-system-survey.md`. An `llm-proposed` survey.
