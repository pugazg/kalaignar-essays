# Future Kalaignar Essay / Article Work Guidelines

Repository: `pugazg/kalaignar-essays`  
Applies to: **all future Kalaignar essays, articles, serial essays, pamphlets and multi-article publications** added to this repository.

This document is a reusable operational guide. It does **not** replace the permanent repository policies:

- [`../ESSAY_PROCESSING_GUIDE.md`](../ESSAY_PROCESSING_GUIDE.md) — Tamil source/archive policy
- [`../ESSAY_TRANSLATION_GUIDE.md`](../ESSAY_TRANSLATION_GUIDE.md) — English translation policy
- [`../HANDOVER.md`](../HANDOVER.md) — single authoritative live project handover

When there is any conflict, those permanent documents control.

## 1. Core principle

> **The supplied scan is the controlling source.**

The repository is an archival representation of the supplied edition, not a corrected or modernised edition.

Never silently:

- correct spelling, grammar, punctuation or historical usage;
- modernise Tamil;
- replace a source name with a better-known modern form;
- reconcile contradictions within Kalaignar's text;
- import wording from another edition, website, OCR output or memory;
- reconstruct text hidden by stamps, damage or bleed-through from context alone;
- turn a source-specific oddity into what the editor thinks the author “must have meant.”

If the pixels support an unusual reading, preserve it and document it.

## 2. Repository policy for source PDFs

**Do not commit source PDFs to GitHub.**

For every new supplied PDF, create a publication-level source record containing at least:

- source filename;
- SHA-256 checksum;
- file size;
- total physical scan count;
- title and author as printed;
- edition / publisher / year visible in the scan;
- printed-page numbering behaviour;
- scan condition;
- stamps, handwriting, accession marks, damage, bleed-through, illustrations, advertisements and other physical-copy features.

## 3. Mandatory startup for every new work

Before creating or changing files:

1. read `ESSAY_PROCESSING_GUIDE.md` completely;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely if English translation is in scope;
3. read the current root `HANDOVER.md` completely;
4. inspect the actual repository state on `main`;
5. search for the work and confirm it has not already been started;
6. inspect the **actual supplied scan**, including cover/title/imprint/contents pages, before deciding title, publication type or structure;
7. determine whether the PDF is a standalone article, a pamphlet, a serial collection or a multi-article publication;
8. continue existing work if present—never create a duplicate publication tree.

The filename is a clue, not source authority.

## 4. Publication-first structure

Use one archival publication unit per supplied edition.

```text
publications/<publication-slug>/
  README.md
  metadata/
    source.md
  indexes/
    contents.md
    page-map.md
  pages/
    0001-....md
  articles/
    01-....md
  TRANSLATION_PLAN.md              # only when translation is in scope
  translations/
    en/
      README.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-....md
```

Do not duplicate shared front matter or the same PDF metadata for every article in a collection.

## 5. Every physical scan gets a record

Create a page record for **every** physical scan, including:

- front cover;
- inside cover;
- title page;
- imprint / edition pages;
- preface;
- contents;
- article pages;
- illustrations;
- advertisements;
- blank pages;
- back cover.

Separate printed text from physical-copy marks. A library stamp or handwriting is evidence about the physical copy, not part of Kalaignar's printed text unless the publication itself printed it.

## 6. Transcription workflow

Use a source-first page-by-page workflow.

For each page:

1. inspect the scan directly;
2. transcribe only source-visible printed material;
3. preserve paragraph boundaries, quotations, dates, numbers, headings and punctuation;
4. record physical-copy marks separately;
5. flag difficult readings rather than guessing;
6. use enlarged crops / contrast variants / nearby glyph comparison when needed;
7. verify page-to-page continuations;
8. mark `verified` only after direct visual comparison.

OCR may assist, but it is never authoritative.

## 7. Article boundaries and assemblies

Do not infer an article boundary only from printed page numbers or contents-page expectations.

Confirm starts and ends from the scan itself. Then create `articles/NN-....md` as a reading assembly from the verified page layer.

Assemblies must:

- preserve source wording exactly;
- retain source-supported headings only;
- keep page-boundary comments for traceability;
- keep editorial notes outside the body;
- document unresolved readings explicitly.

## 8. Multiple source witnesses must stay separate

Contents-page titles, article-heading titles, repeated excerpts, advertisements, back-cover promotions and later errata may differ.

**Preserve each witness independently. Never normalise one witness from another.**

The first publication in this repository demonstrated why this matters: contents/heading punctuation and spelling can differ, and a promotional back-cover excerpt can differ from the controlling body text.

## 9. Initial verification is not the final fidelity gate

After all pages and article assemblies are complete, perform a separate **strict visual-text-fidelity pass** over the entire physical publication.

That pass must recheck:

- every visible word;
- every word boundary / unusual spacing that matters;
- punctuation and quotation marks;
- headings;
- dates and numbers;
- paragraph continuations;
- article boundaries;
- advertisements and non-body sections;
- contents/body/advertisement witness differences.

Record old reading → source-visible correction provenance for every correction found.

Only after this pass may the Tamil publication be marked **visual-text-fidelity complete**.

## 10. Translation begins only from a frozen Tamil source

Do not translate from OCR, memory or an unfinished transcription.

English begins only after the Tamil source prerequisites in `ESSAY_TRANSLATION_GUIDE.md` are satisfied.

For every translated publication, create:

- `TRANSLATION_PLAN.md`;
- `translations/en/README.md`;
- `translations/en/LEXICON.md`;
- `translations/en/TRANSLATION_REVIEW.md`.

Translate one article at a time through **T0–T5**:

- **T0** source prerequisite + Tamil blob SHA;
- **T1** complete close draft;
- **T2** bilingual fidelity review;
- **T3** Kalaignar voice review;
- **T4** terminology / quotation / citation / source audit;
- **T5** verified.

After all articles reach T5, run the publication-wide consistency gate before declaring English complete.

## 11. Retaining Kalaignar's language in English

> **Translate the language; do not neutralise the voice.**

Preserve:

- direct address;
- commands;
- rhetorical questions;
- deliberate repetition;
- sarcasm and ridicule;
- polemical labels;
- abrupt contrasts;
- exclamations;
- physical metaphors;
- politically / socially loaded vocabulary;
- wordplay where English can carry it.

Do not turn Kalaignar into detached academic prose.

A slightly rough but faithful English sentence is preferable to elegant English that removes his force.

## 12. Publication-specific identity decisions are not universal rules

Do **not** mechanically carry one publication's editorial identification into a future work.

For example, the established `ஆச்சாரியார்` → **Achariyar** decision belongs to the current `சக்கரவர்த்தியின் திருமகன்` publication because the user explicitly established the referent and preferred transliteration there.

For a new work:

- first preserve Kalaignar's source label;
- identify a referent only when the source/user/research supports it;
- record the decision in that publication's lexicon;
- preserve Kalaignar's own switches between labels.

## 13. Difficult, unexplained or culturally marked forms

If a term is not explained by the source and its identification is uncertain:

1. preserve the source-bearing form or wordplay;
2. do not silently “correct” it to a familiar name;
3. add a translator/source note only when useful;
4. use external research only when the user asks or when clearly required and explicitly separated from source evidence.

## 14. Quotations and verse

For quoted prose:

- preserve quotation status, attribution, date and publication reference;
- translate the supplied Tamil witness rather than importing an external published English version;
- document unmatched or irregular source punctuation.

For verse:

- preserve lineation where practical;
- prioritise semantic/rhetorical fidelity over invented rhyme;
- use Kalaignar's own explanation as an interpretive aid when present;
- do not import outside literary translations unless explicitly authorised.

## 15. Continuous documentation

After every meaningful activity, update the root [`../HANDOVER.md`](../HANDOVER.md).

Record:

- active publication;
- source file and source status;
- pages / articles completed;
- strict-fidelity status;
- translation status by gate;
- corrections made;
- frozen non-regression decisions;
- unresolved issues;
- **exact next activity**.

There must remain **one authoritative live handover**: the root `HANDOVER.md`.

## 16. Completion sequence for a publication

A future publication should normally move through these gates:

1. **P0 — source intake / publication identification**
2. **P1 — metadata + page map + contents mapping**
3. **P2 — page-level transcription**
4. **P3 — article assemblies**
5. **P4 — source audit / completeness review**
6. **P5 — strict visual word/punctuation fidelity pass**
7. **E0 — translation planning** (if English is required)
8. **E1–E5 — article translation batches through T0–T5**
9. **E6 — publication-wide English consistency review**
10. **E7 — English release closeout**

Do not skip a gate merely because the text looks easy.

## 17. What “proceed with next activity” means

When the user says **“Proceed with next activity”**:

- read the root handover;
- identify the exact next activity already recorded there;
- execute it completely without asking the user to restate context;
- update all dependent records;
- update the handover again before ending.

Do not restart completed work, and do not choose a smaller activity merely because it is easier when the recorded next activity clearly supports a larger batch.

## 18. Final rule

The archive must be able to answer two questions at any time:

1. **What exactly does this supplied edition visibly say?**
2. **What exactly has been completed, reviewed and verified—and what remains next?**

If either answer is unclear, the documentation is not yet sufficient.
