# Kalaignar Essays — English Translation Guide

This document is the permanent translation policy for `pugazg/kalaignar-essays`.

It applies to all present and future English translations of Kalaignar M. Karunanidhi's essays, articles, serial essays, pamphlets and multi-article publications stored in this repository.

The purpose is **not** to produce a smoother modern adaptation. The purpose is to produce readable English that remains recognisably Kalaignar in argument, cadence, irony, directness and political/literary force.

> **Translate the language; do not neutralise the voice.**

## 1. Translation may begin only after the Tamil source is closed

English translation is downstream of the Tamil archival layer.

Before an article is translated:

1. all of its Tamil source pages must be source-complete;
2. its article boundaries must be verified;
3. its Tamil article assembly must agree with the page layer;
4. the publication's required strict visual-text-fidelity pass must have reached that article;
5. no unresolved body-text reading may be silently guessed for translation.

If the Tamil source later changes because of a source-supported correction, every affected English translation must be reopened and reviewed.

## 2. Translation authority

For translation work, authority is ordered as follows:

1. the **strict-reviewed Tamil article assembly** in `articles/`;
2. the corresponding verified page records and controlling scan, when a punctuation, quotation, page-boundary or source-witness question must be checked;
3. documented repository notes that explain source-witness distinctions.

OCR, web transcriptions, later editions, remembered wording and general knowledge must not replace the repository's controlling Tamil reading.

Outside sources may be used only when the user explicitly asks for research or when a clearly labelled translator's note requires corroboration. They must never silently rewrite Kalaignar's text.

## 3. Core objective — retain Kalaignar's language in English

A good translation must preserve both **meaning** and **rhetorical action**.

### Preserve especially

- direct address to the reader;
- commands such as `படியுங்கள்!`, `பாருங்கள்!`, `கேளுங்கள்!` as commands, not as explanatory prose;
- rhetorical questions as rhetorical questions;
- repetition, including deliberately repeated words and clauses;
- irony, sarcasm, ridicule and polemical bite;
- abrupt contrasts and short emphatic sentences;
- exclamations and accumulative lists;
- dashes used to drive the argument forward;
- parallel sentence structures;
- recurring epithets and labels chosen by Kalaignar;
- the emotional temperature of praise, accusation, mockery, anger or challenge;
- deliberate shifts between narration, quotation and direct commentary.

Do **not** convert Kalaignar's polemical prose into detached academic English.

For example, do not insert distancing phrases such as `Karunanidhi argues that`, `he appears to suggest`, `in the author's view`, or explanatory qualifiers when the Tamil itself states something directly.

## 4. No softening, sanitising or ideological neutralisation

Do not soften a harsh word merely because a milder English phrase sounds more polite.

Do not:

- replace an insult with a neutral description;
- turn an accusation into a tentative claim;
- remove irony;
- reduce repeated exclamation for stylistic neatness;
- replace culturally or politically loaded terms with generic modern language;
- make the prose sound more conciliatory than the Tamil;
- add present-day disclaimers inside Kalaignar's body text.

The English translation represents the source text, not the translator's agreement or disagreement with it.

## 5. Author-chosen names, epithets and labels

The translation must follow the **referential choice made in the Tamil sentence**.

If Kalaignar uses an epithet, title or label, do not silently replace it with a person's modern full name. If he changes the label elsewhere, preserve that change.

Examples of the rule:

- a source use of `ஆச்சாரியார்` should remain a source-bearing English form of that chosen label, not silently become a substituted personal name; in the active `சக்கரவர்த்தியின் திருமகன்` publication the user-established form is **`Achariyar`**, referring to C. Rajagopalachari (Rajaji) only in translator/editorial notes;
- a source use of `ராஜாஜி` may be rendered `Rajaji`;
- `ஆரியர்` and `திராவிடர்` must not be flattened into generic groups that erase Kalaignar's terminology.

Conventional English forms may be used for well-established epic proper names for readability, but the translator must not use that convention to alter Kalaignar's actual referent or rhetorical contrast.

## 6. Culturally loaded and source-specific terms

Do not force a culturally loaded Tamil term into the nearest English social category merely because that category is familiar.

For each difficult recurring term:

1. determine its function in the immediate sentence;
2. choose the closest English rendering that preserves its force;
3. record the choice in the publication's living English lexicon;
4. allow a contextual variant when the Tamil sense genuinely changes;
5. never invent a stronger caste, religious, political or social identification than the Tamil supports.

If Kalaignar uses a **source-specific expression, nickname, pun, coined insult, or culturally specific reference that the article itself does not explain**, do not silently identify or expand it from memory or outside knowledge. Prefer one of these, in order:

1. carry the wordplay naturally into English when possible;
2. retain a source-bearing transliteration when that preserves the rhetorical function better;
3. add a clearly separated translator/source note explaining only what is supported and why the source form was retained;
4. research externally only when the user explicitly asks for verification or expansion.

A source-bearing transliteration is preferable to a confident but unsupported identification.

A lexicon is a consistency aid, not a licence to mechanically translate every occurrence the same way.

## 7. Quotations and cited passages

When Kalaignar quotes another work or writer:

- translate the quoted Tamil into English;
- preserve the fact that it is a quotation;
- preserve its attribution, date and publication citation;
- do not improve or reconcile the quoted statement with another version;
- do not import a published English translation unless explicitly authorised;
- keep Kalaignar's surrounding framing separate from the quoted speaker's words.

If a quotation is visibly incomplete or source-irregular in the Tamil layer, do not silently manufacture missing content.

## 8. Verse and highly literary passages

For verse embedded in an essay:

- preserve line divisions where the Tamil source presents them as verse;
- prioritise semantic and rhetorical fidelity over invented rhyme;
- do not add poetic imagery not present in the source;
- retain repeated images and parallel structures;
- if a compact Tamil wordplay cannot be fully carried into English, translate the argument faithfully and record the loss/choice outside the body in the review ledger if it materially matters.

## 9. Punctuation and typography in English

This is a translation layer, not a second diplomatic transcription layer.

Therefore:

- preserve rhetorically meaningful `?`, `!`, repeated punctuation, quotation structure and dashes;
- preserve paragraph boundaries unless English grammar absolutely requires a small internal adjustment;
- retain source page-boundary comments for traceability;
- normal English spacing around punctuation may be used;
- purely typographic Tamil spacing anomalies do not have to be imitated mechanically in English;
- when a source punctuation anomaly affects meaning or quotation scope, document it in the translation review instead of silently resolving it.

## 10. Paragraph fidelity and completeness

Translation is performed **paragraph by paragraph** against the Tamil assembly.

Every Tamil paragraph must have an English counterpart unless it is a non-body editorial/source comment.

Do not:

- omit repetitive sentences because they seem redundant;
- merge distant paragraphs for elegance;
- add explanatory paragraphs;
- turn a sequence of rhetorical questions into a summary;
- omit dates, issue references, numbers or source citations.

Page-boundary comments should be retained in the English file in the form:

```html
<!-- Tamil source: scan 9 / printed 7 -->
```

This makes bilingual rechecking possible without embedding duplicate Tamil text in the English file.

## 11. English translation file structure

Use:

```text
publications/<publication>/
  translations/
    en/
      README.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-<source-slug>.md
      02-<source-slug>.md
      ...
```

Each article translation should begin with metadata similar to:

```yaml
---
publication: "publication-slug"
article_number: 1
title_ta: "..."
title_en: "..."
source_tamil: "../../articles/01-....md"
source_tamil_blob_sha: "..."
source_scan_pages: "..."
source_printed_pages: "..."
language: "en"
translation_status: "draft"
translation_method: "close rhetorical translation preserving Kalaignar's voice"
---
```

The Tamil title remains in metadata even after an English title is chosen.

## 12. Translation statuses

Use these statuses in the English tracker:

- `not-started`
- `draft`
- `fidelity-reviewed`
- `voice-reviewed`
- `verified`

`verified` is a translation-release status. It must not be assigned merely because a first draft exists.

## 13. Translation gates

Every article passes the following gates.

### T0 — source prerequisite

Confirm the Tamil assembly being translated is strict-reviewed and record its blob SHA.

### T1 — close draft

Translate the entire article paragraph by paragraph. Preserve quotations, citations, questions, exclamations, repetitions and page-boundary comments.

### T2 — bilingual fidelity review

Re-read Tamil and English side by side and check:

- no omitted sentence or clause;
- no added claim;
- names/referents correct;
- dates and numbers correct;
- quotations complete;
- negatives, comparisons and logical connectors preserved;
- deliberate repetitions retained;
- source witness distinctions not accidentally harmonised.

### T3 — Kalaignar voice review

Read the English as English while comparing to Tamil and ask:

- Does the directness remain?
- Does sarcasm still bite?
- Are rhetorical questions still questions?
- Are commands still commands?
- Has any harsh formulation been politely softened?
- Has a vivid image become abstract prose?
- Has a repeated phrase been edited away?
- Has the translator inserted academic explanation into the body?
- Has a source-bearing pun, coined label, or strange repetition been "fixed" merely because it sounds unusual in English?

### T4 — terminology / quotation / citation audit

Check the publication lexicon, proper-name policy, recurring epithets, quoted material, dates, periodical titles, source-page comments, source-specific transliterations, and documented punctuation/source anomalies.

### T5 — article verification

Only after T1–T4 pass may the article be marked `verified` in `translations/en/README.md` and the publication review ledger.

## 14. Publication-level English release gate

After all articles are individually verified, perform one cross-article consistency review for:

- recurring names and epithets;
- `Aryan` / `Dravidian` and other ideological vocabulary;
- repeated phrases or slogans;
- source publication names;
- epic-name conventions;
- treatment of quoted material;
- title style;
- tone consistency;
- source-bearing puns/transliterations and explanatory restraint;
- accidental smoothing introduced in later articles;
- completeness of all 14/other article units.

Only then may a publication be described as **English-translation complete**.

## 15. Living lexicon

Each publication's `translations/en/LEXICON.md` must be updated while translating, not reconstructed only at the end.

Recommended columns:

| Tamil | Preferred English | Context / exception | First established in | Status |
|---|---|---|---|---|

Record especially:

- recurring epithets;
- ideological vocabulary;
- difficult compounds;
- terms whose force could easily be softened;
- source-specific puns, coined insults and unexplained references;
- publication names and source labels;
- words for which more than one contextual English rendering is intentionally used.

## 16. Review ledger

`translations/en/TRANSLATION_REVIEW.md` is the permanent review provenance for the English layer.

For each article record:

- source Tamil blob SHA;
- draft completion;
- T2 findings/corrections;
- T3 findings/corrections;
- T4 findings/corrections;
- final status;
- any unresolved translation choice.

Do not hide corrections made during review.

## 17. Single project handover document

The repository root [`HANDOVER.md`](HANDOVER.md) is the **single authoritative project handover document**.

It must be updated after every meaningful translation or review activity with:

- current publication;
- Tamil source/fidelity state;
- English translation count by status;
- latest article/gate completed;
- important translation decisions that must not regress;
- unresolved questions, if any;
- exact next activity.

Do not create competing handover documents unless the user explicitly requests one.

## 18. Future works

For every new Kalaignar essay/article publication:

1. complete the Tamil archival and strict-fidelity workflow first;
2. create a publication-specific `TRANSLATION_PLAN.md`;
3. create `translations/en/README.md`, `LEXICON.md` and `TRANSLATION_REVIEW.md`;
4. translate from the strict-reviewed Tamil assemblies, not from OCR or memory;
5. establish the voice baseline on the first article before accelerating later articles;
6. preserve unexplained source-specific labels/wordplay rather than silently identifying them from outside knowledge;
7. update the single root `HANDOVER.md` after each translation activity;
8. run the publication-level cross-article consistency gate before declaring English completion.

## 19. Final principle

A translation may be slightly less polished and still be faithful. It must never become more polished by losing Kalaignar.

When forced to choose between elegant neutral English and accurate preservation of his rhetorical force, **preserve the force**.
