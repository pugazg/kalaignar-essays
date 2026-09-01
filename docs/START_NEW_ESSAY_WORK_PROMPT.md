# Start a New Kalaignar Essay / Article Work — Reusable Prompt

> **Use this file only for intake of a new supplied work/publication.**  
> To continue the **current active repository work in another chat/window**, use [`NEXT_CHAT_PROMPT.md`](NEXT_CHAT_PROMPT.md). The continuation prompt is a convenience handoff; live `main` and root [`HANDOVER.md`](../HANDOVER.md) remain authoritative.

Use the prompt below when opening a new chat/window for the next Kalaignar essay, article, pamphlet or multi-article publication.

Replace only the bracketed placeholders. Attach the controlling PDF to the new conversation.

---

## Copy/paste prompt

Continue the Kalaignar Essays / Articles archival project directly in:

`pugazg/kalaignar-essays`

Work on `main`.

New supplied source PDF:

`[ATTACHED PDF FILENAME]`

Expected work/publication, if already known:

`[EXPECTED TITLE OR "determine from scan"]`

### LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Never assume a checkpoint copied into a prompt is still current. If `main` has advanced, preserve the newer durable state and continue from it; do not reset or overwrite later completed work.

### Mandatory startup

Before making any change, read these repository files completely and follow them exactly:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. `HANDOVER.md`
5. `docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`

Then inspect the current repository state on `main` and confirm whether this supplied work has already been started. If work exists, **continue it**; do not create a duplicate publication tree.

Inspect the **actual attached scan** before creating metadata, choosing a title, deciding article boundaries or assuming publication type. Do not rely on the filename alone.

### Source authority

The attached scan is the controlling source for this edition.

Do not silently modernise, correct, normalise, reconstruct or improve Kalaignar's Tamil.

Preserve source-supported:

- historical spelling;
- punctuation and quotation marks;
- wording and repetitions;
- names and labels;
- dates and numbers;
- unusual grammar;
- typographical forms;
- article-title variants between contents and heading pages.

Distinguish printed text from library stamps, handwriting, accession marks, damage, bleed-through and later annotations.

OCR / parsed text may assist transcription but is **never authoritative**.

Source PDFs must **not** be committed to the GitHub repository.

### Intake and structure

First determine from the scan whether this is:

- a standalone article;
- a pamphlet;
- a serial essay;
- a multi-article publication;
- or another publication form supported by the scan.

Create or continue one publication unit under:

`publications/<publication-slug>/`

Use the repository's publication-first structure and create page records for **every physical scan**, including covers, front matter, contents, body, advertisements, blank pages and back cover.

Create/update:

- `README.md`
- `metadata/source.md`
- `indexes/contents.md` when applicable
- `indexes/page-map.md`
- `pages/`
- `articles/`

Do not duplicate the same edition metadata for every article.

### Transcription and verification

Transcribe page by page from the scan.

For difficult readings:

- inspect enlarged scan crops;
- use non-destructive contrast/gamma/sharpening variants where useful;
- compare nearby glyphs in the same print/font;
- check page continuations;
- never guess hidden text merely from sentence meaning.

Mark a page `verified` only after direct visual comparison.

Keep printed text and physical-copy marks in separate sections.

Confirm article starts/ends from the scan itself rather than inferring them from contents-page numbers alone.

Build article assemblies only from verified page records.

### Multiple source witnesses

If the contents page, article heading, repeated excerpt, advertisement, back cover or printed errata differ, preserve each as a separate witness.

Do **not** use one witness to silently normalise another.

### Strict visual fidelity gate

After the publication's initial page-level transcription and assemblies are complete, perform the repository-required separate strict word-by-word / punctuation-by-punctuation visual fidelity pass over **every physical scan**.

Do not call the Tamil publication complete until that pass is finished and all corrections are propagated to dependent records.

Record correction provenance as old reading → source-visible reading.

### English translation — only after Tamil is frozen

Do not begin English translation until the Tamil source prerequisites in `ESSAY_TRANSLATION_GUIDE.md` are complete.

If/when translation begins, first create a publication-specific translation plan and English workspace:

- `TRANSLATION_PLAN.md`
- `translations/en/README.md`
- `translations/en/LEXICON.md`
- `translations/en/TRANSLATION_REVIEW.md`

Translation principle:

> **Translate the language; do not neutralise the voice.**

Retain Kalaignar's direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, exclamations, physical imagery and wordplay. Do not turn his prose into detached academic English.

Translate one article at a time through T0–T5 and run E6 publication-wide consistency review before declaring English complete.

Do not mechanically import publication-specific editorial choices from earlier works. For example, a name/epithet decision established in `சக்கரவர்த்தியின் திருமகன்` applies to a new publication only if the new source/user evidence supports it.

### Handover discipline

The root `HANDOVER.md` is the **single authoritative live project handover**.

Do not create competing handover files. `docs/NEXT_CHAT_PROMPT.md`, when present, is only a convenient fresh-window prompt and must defer to live `main` and `HANDOVER.md`.

After every meaningful activity update `HANDOVER.md` with:

- active publication;
- source identity and checksum;
- page/article progress;
- strict-fidelity status;
- corrections and source-witness distinctions;
- translation progress/gates if active;
- frozen non-regression decisions;
- unresolved questions;
- the **exact next activity**.

Use `docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md` as the structure when a new publication becomes active.

### Execution rule

Proceed with the largest safe coherent batch supported by the source and current project state; do not unnecessarily reduce every activity to a single page.

When I later say **"Proceed with next activity"**, read live `main` and the current root handover and execute the exact next activity recorded there without asking me to restate the project context.

At the end of this startup activity, report:

- what publication the scan actually contains;
- whether prior work already existed;
- what files were created/updated;
- current source/fidelity status;
- any unresolved source difficulty;
- the exact next activity now recorded in `HANDOVER.md`.

---

## Usage note

For the **first activity of a new work**, attach the actual PDF in the same conversation as this prompt. The prompt is intentionally strict about source inspection because filenames, remembered titles and secondary text are not substitutes for the supplied scan.
