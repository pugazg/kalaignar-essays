# Next Chat Prompt — Kalaignar Essays / சிந்தனையும் செயலும் — Source Intake

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

Active selected publication: `சிந்தனையும் செயலும்`

Expected workspace after source confirmation: `publications/sinthanaiyum-seyalum/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable work. Publications 1–7 are release-complete/frozen and must not be reopened without a genuine source-supported or release-blocking defect.

## Mandatory startup

Before changing anything, read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. `docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`
6. this prompt

If the publication workspace exists on live `main`, read its current `README.md`, `metadata/source.md`, `indexes/page-map.md`, contents/fidelity records and continue the newer durable state rather than creating duplicates.

## Current durable boundary

Publications **1–7 are RELEASE COMPLETE / FROZEN**.

`சிந்தனையும் செயலும்` has been selected as Publication 8, but the controlling PDF was **not available in the conversation or accessible file Library when this prompt was prepared**. Therefore no scan-derived publication tree, metadata, page map, page records, article boundaries or assemblies were created at that checkpoint.

## User-supplied expected identity — NOT YET SCAN-VERIFIED

Treat these as intake clues until verified against the controlling scan:

- expected title: `சிந்தனையும் செயலும்`
- expected author: `கலைஞர் மு. கருணாநிதி`
- expected publisher: `தமிழ்க்கனி பதிப்பகம்`
- expected edition: `மூன்றாம் பதிப்பு, 2010`
- expected contents description: two Murasoli letters — `பாசியும் தூசியும்` dated **27.04.2005** and `அதிக உயரம் தாண்டுவதற்கு` dated **29.04.2005** — plus **50 articles**.

An older bibliographic witness describes a **2006 first edition**. Keep that edition strictly separate; do not use it to infer, normalise or fill the 2010 third-edition scan.

## Source authority

The actual supplied 2010 third-edition scan is the controlling witness.

Do not silently modernise, correct, normalise, reconstruct or improve Kalaignar's Tamil. Preserve source-visible wording, spelling, punctuation, names, dates, numbers, repetitions and typographical forms. Separate printed text from stamps, handwriting, accession marks, damage and bleed-through.

OCR or parsed text may assist but is never authoritative. Source PDFs must not be committed.

## Exact next activity

**Resolve/attach the actual `சிந்தனையும் செயலும்` controlling PDF and execute P0/P1 as one coherent intake batch:**

1. compute exact source filename, SHA-256, file size and physical scan count;
2. visually inspect cover, title, imprint/edition, contents and other front matter;
3. determine the publication form and exact article/letter witnesses from the scan rather than from the filename or older bibliography;
4. confirm whether live `main` already contains any newer workspace for this publication;
5. if genuinely new, create `publications/sinthanaiyum-seyalum/` with:
   - `README.md`
   - `metadata/source.md`
   - `indexes/contents.md` when applicable
   - `indexes/page-map.md`
   - `pages/` records covering **every physical scan**, including covers/front matter/blank/advertisement/back cover
   - `articles/` directory/workspace as supported by confirmed source boundaries;
6. do not mark a page `verified` until direct visual comparison;
7. update root `HANDOVER.md` with exact source identity, page/article mapping, source-witness distinctions, unresolved difficulties and the next transcription batch.

## Non-regression

- live `main` beats this prompt;
- do not reopen released Publications 1–7;
- do not treat the older 2006 edition as authority for the 2010 edition;
- do not infer article boundaries from contents-page numbers alone;
- do not begin English translation until the Tamil source is frozen through strict fidelity.