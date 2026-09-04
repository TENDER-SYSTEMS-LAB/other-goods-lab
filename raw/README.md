# Raw Layer

`raw/` is this project's Source of Truth. Preserve its materials as immutably as possible. Once a file has been added, do not edit it. If content must be corrected or extended, add a separate revision file instead of changing the existing one.

`raw/` is not the Wiki. No matter how well material has been organized or interpreted in `wiki/`, never use it to replace an original in `raw/` or to justify deleting raw material. The Wiki is an interpretive layer built on raw sources; it cannot substitute for them.

## Language

Raw sources retain the language in which they were originally created. The repository's English-default policy applies to this guide, the source registry, and all Wiki synthesis, but never authorizes translating or rewriting a registered source in place. When English access is needed, write an English synthesis in the Wiki or add a separately registered translation without modifying the original.

## Subdirectories

- **`conversations/`** — Exports of conversations with LLMs. These are the most important primary materials in the OTHER GOODS project because most ideas, product candidates, and conceptual discussions emerge in conversation.
- **`documents/`** — Plans, briefs, instructions, and other documents written directly by the user.
- **`surveys/`** — Responses in which several LLMs independently evaluate the same candidates or questions. Preserve each response as `llm-proposed`; agreement among them is not a user decision.
- **`inbox/`** — Temporary storage for material that has not yet been classified or reviewed. Treat anything in `inbox/` as not promoted to the Wiki.

## File Naming

Use `YYYY-MM-DD-kebab-case-slug.md`. When adding multiple files on the same date, distinguish them with `-2`, `-3`, and so on.

## Source Registration

Every new source added under `raw/` must also be registered in `raw/sources.md`. An unregistered source is treated as nonexistent.

## Current-State Notes

On 2026-09-03, the first conversation export and the Collection v0.1 evaluation surveys from Claude, Gemini, and Perplexcity were registered. The conversation establishes the initial ideas and user selections; the surveys make it possible to compare each agent's hypotheses and evaluation differences. Preserve the originals and hashes of additional material in the same way.

On 2026-09-04, `SRC-2026-09-04-commerce-product-rnd-summary`, two Collection v0.4 surveys, and three Product Image System surveys were added, bringing the registered source count to 11. The R&D summary is a derivative summary rather than a conversation transcript, so material promoted from it has secondary-citation provenance. The shared Product Image System prompt and its flower ASCII reference image are also absent from the repository and are recorded as a separate provenance limitation.

Later on 2026-09-04, four Collection v0.5 surveys (Gemini, GLM, Grok, and Kimi) were added and ingested, bringing the registered source count to 15. As with v0.4, the v0.5 evaluation prompt itself is absent, so the 24-item candidate list, the naming principle those surveys tested, and the Commerce-Generated / Activated / Displayed classification they applied are known only through the responses. That limitation is recorded in `sources.md`.

On 2026-09-05, `SRC-2026-09-05-chatgpt-v0.6-rnd` was registered and partially promoted, bringing the registered source count to 16. It records a discussion of a possible v0.6 Deep R&D Set and a user-originated exploration of guilt, homecoming, atonement, responsibility, control, and continuing consequences. The video and attachment discussed in the conversation are not registered; only the user's pasted account is available.

Later on 2026-09-05, `SRC-2026-09-04-chatgpt-pre-v0.6-rnd-position` was registered and partially promoted, bringing the registered source count to 17. Although dated 2026-09-04, it is a derivative ChatGPT position note that synthesizes the Wiki, v0.5 surveys, naming discussion, and supplied video analysis. It is not an independent evaluation or a user decision.

Later on 2026-09-05, six pre-v0.6 critique surveys (Claude, DeepSeek, GLM, Grok, Kimi, and Qwen) were registered and partially promoted, bringing the registered source count to 23. They critique the derivative ChatGPT position note rather than an actual v0.6; their matching structure indicates a common brief, but the prompt, delivery, and evaluator independence are not verifiable. Their convergence is LLM synthesis, never user confirmation.
