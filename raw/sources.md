# Raw Source Index

This document is the registry for every raw source. It tracks each source's ID, path, hash, and ingestion status. Any Wiki content followed back through its provenance must ultimately lead to an original through this table.

## Registration

When adding a source, append one row to the table below and record the result of `git hash-object <path>` in the `Hash` column. If a later hash differs from the registered value, the original has changed. Do not update the Wiki automatically. Mark the pages that rely on the source `REVIEW_REQUIRED` so that a person can review them again.

## Source List

| Source ID | Path | Type | Date | Attribution | Hash | Ingested | Wiki Status |
|---|---|---|---|---|---|---|---|
| `SRC-2026-09-03-llm-wiki-agent-prompt` | `raw/documents/2026-09-03-llm-wiki-agent-prompt.md` | document | 2026-09-03 | `user-originated` | `32061c00c30ada052406b2d4af3d0b36931697ed` | 2026-09-03 (pilot) | promoted (partial) |
| `SRC-2026-09-03-chatgpt-brainstorming` | `raw/conversations/ChatGPT-brain-storming-20260903-2252.md` | conversation | 2026-09-03 | `jointly-developed` | `d3593674301fa501dbae01ca5d4d0f8d668d30a9` | 2026-09-03 | promoted (partial) |
| `SRC-2026-09-03-claude-collection-survey` | `raw/surveys/2026-09-03-claude-collection-survey.md` | survey | 2026-09-03 | `llm-proposed` | `db090264b82450dbe82c00f4d747d34b3897d947` | 2026-09-03 | promoted (partial) |
| `SRC-2026-09-03-gemini-collection-survey` | `raw/surveys/2026-09-03-gemini-collection-survey.md` | survey | 2026-09-03 | `llm-proposed` | `ce6aafd9cf7db4df4cd38a4c706328891bdd0d2e` | 2026-09-03 | promoted (partial) |
| `SRC-2026-09-03-perplexcity-collection-survey` | `raw/surveys/2026-09-03-perplexcity-collection-survey.md` | survey | 2026-09-03 | `llm-proposed` | `7a2ab85744652bff4e77d6f15e3a66a1ca79cf77` | 2026-09-03 | promoted (partial) |
| `SRC-2026-09-04-commerce-product-rnd-summary` | `raw/conversations/2026-09-04-commerce-product-rnd-summary.md` | derived conversation summary | 2026-09-04 | `jointly-developed` | `3a9b6069aa7f0714cbebdce1e78c19794d5aec0c` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-gemini-collection-v0.4-survey` | `raw/surveys/2026-09-04-gemini-collection-v0.4-survey.md` | survey | 2026-09-04 | `llm-proposed` | `aec9c140762a12a2291b980f02717a270e2e4132` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-claude-collection-v0.4-survey` | `raw/surveys/2026-09-04-claude-collection-v0.4-survey.md` | survey | 2026-09-04 | `llm-proposed` | `b7bc49d8e478d1c71e13de49928436e7cf829a0e` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-gemini-product-image-system-survey` | `raw/surveys/2026-09-04-gemini-product-image-system-survey.md` | survey | 2026-09-04 | `llm-proposed` | `6bc820c8eab852c026bd841ed34c02e897f47bd8` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-glm-product-image-system-survey` | `raw/surveys/2026-09-04-glm-product-image-system-survey.md` | survey | 2026-09-04 | `llm-proposed` | `c33a095684408f09fa037005afcac574d9957c70` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-grok-product-image-system-survey` | `raw/surveys/2026-09-04-grok-product-image-system-survey.md` | survey | 2026-09-04 | `llm-proposed` | `9dfcfda479d9f2da9f836f04b87a5f689e59dbfb` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-gemini-collection-v0.5-survey` | `raw/surveys/2026-09-04-gemini-collection-v0.5-survey.md` | survey | 2026-09-04 | `llm-proposed` | `94ac9fa3c67153e6613541709e126ce609595f41` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-glm-collection-v0.5-survey` | `raw/surveys/2026-09-04-glm-collection-v0.5-survey.md` | survey | 2026-09-04 | `llm-proposed` | `c6470a3dfd8e8b608a7b6f85602ede92bd65f53d` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-grok-collection-v0.5-survey` | `raw/surveys/2026-09-04-grok-collection-v0.5-survey.md` | survey | 2026-09-04 | `llm-proposed` | `a99595dcfcf88f563cae4a2e8c2ff87bea8d4466` | 2026-09-04 | promoted (partial) |
| `SRC-2026-09-04-kimi-collection-v0.5-survey` | `raw/surveys/2026-09-04-kimi-collection-v0.5-survey.md` | survey | 2026-09-04 | `llm-proposed` | `d5be49ebe614a739fe89b14faf442b2372142c6a` | 2026-09-04 | promoted (partial) |

## Known Provenance Gaps

### Initial record on 2026-09-03

`SRC-2026-09-03-llm-wiki-agent-prompt` referred to four product candidates (`The Smell After Rain on April 21`, `Sunlight at 4 p.m. on June 13`, `Yesterday`, and `Summer at Sixteen`) and the work's central question as already discussed, but the original conversation was not in the repository. At that point, these claims could be verified only as secondary citations through `SRC-2026-09-03-llm-wiki-agent-prompt`.

### Gap resolved on 2026-09-03

The original conversation behind the four product candidates and central question that had only been secondarily cited in `SRC-2026-09-03-llm-wiki-agent-prompt` was registered as `SRC-2026-09-03-chatgpt-brainstorming`. It confirms that the user directly proposed the four candidates.

### Provenance limit of a new source on 2026-09-04

`SRC-2026-09-04-commerce-product-rnd-summary` is a derivative summary, not a conversation transcript. The document itself states that if the original conversation is preserved separately, final provenance should favor that original conversation. Material promoted from this source—Collection v0.2/v0.3, Product Grammar, and DEC-005 through DEC-007—therefore remains a secondary citation. Obtaining the original export of the conversation summarized here remains an open task.

### Missing v0.4 evaluation prompt

The original “OTHER GOODS — Commerce R&D Collection v0.4 Evaluation Prompt,” which contained the 30 product candidates and evaluation criteria assessed by `SRC-2026-09-04-gemini-collection-v0.4-survey` and `SRC-2026-09-04-claude-collection-v0.4-survey`, is not in this repository. Only the two responses are registered.

### Missing Product Image System prompt and reference image

The shared prompt answered by `SRC-2026-09-04-gemini-product-image-system-survey`, `SRC-2026-09-04-glm-product-image-system-survey`, and `SRC-2026-09-04-grok-product-image-system-survey`, as well as the flower ASCII reference image they evaluated, is not in the repository. The responses clearly address the same question structure, but the originals do not establish that the prompts were identical or that each model saw the image directly. The GLM response explicitly states that it relied on a text description rather than the actual pixels. Treat repetition across the responses as a strong design signal, not as audience evidence or a user decision.

### Missing v0.5 evaluation prompt and its embedded frames

The original “OTHER GOODS — Commerce R&D Collection v0.5” evaluation prompt, answered by `SRC-2026-09-04-gemini-collection-v0.5-survey`, `SRC-2026-09-04-glm-collection-v0.5-survey`, `SRC-2026-09-04-grok-collection-v0.5-survey`, and `SRC-2026-09-04-kimi-collection-v0.5-survey`, is not in this repository. Only the four responses are registered. This repeats the gap already recorded for v0.4.

Three things reach the Wiki only through those responses and must be treated as inferred rather than established:

1. **The 24-item v0.5 list.** Reconstructed from the four evaluation tables. All four assign identical numbers and titles to all 24, which is strong evidence, but it is not verification against the original.
2. **The naming principle under test** — “Use the driest name that preserves the product's essential image” — quoted or paraphrased by all four under a dedicated section. Promoted to [[Q-007-product-naming-register]] as a principle *being evaluated*, never as one adopted.
3. **The three-way classification Commerce-Generated / Commerce-Activated / Commerce-Displayed**, used by name in all four responses without being introduced. Recorded in [[Q-005-commerce-generative-vs-display]], where the four surveys are also shown to assign the same products to different categories.

Two further names, **“Machine Blindness”** and **“Placeholder Aesthetics”**, appear in the Gemini response as though already established and exist in no registered source. They most likely come from the unregistered prompt or from image-system work done outside this repository. They are recorded in `wiki/concepts/product-image-system.md` as unregistered, not as project concepts.

It also cannot be verified from the responses alone whether the four models answered independently of one another. Their convergence is therefore a strong signal, not four separate confirmations.

## Notes

This is an append-oriented document. Never delete an existing row. If a source is invalidated, change its `Wiki Status` to `invalidated` and add a footnote explaining why.
