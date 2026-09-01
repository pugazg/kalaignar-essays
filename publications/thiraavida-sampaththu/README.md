# திராவிட சம்பத்து

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி  
**முதல பதிப்பு:** செப்டம்பர் 1951  
**வெளியிடுவோர்:** அறிவு மன்றம், சென்னை-1  
**விற்பனையாளர்:** பாரி நிலையம், 59, பிராட்வே, சென்னை-1  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied source ஒரு **கடுமையாக சேதமடைந்த சிறுநூல் / pamphlet**. இதில் கலைஞரின் இரண்டு கட்டுரை அலகுகள் உள்ளன:

1. `திராவிட சம்பத்து`
2. `ஐயர் அறிவிக்கிறார்!`

மேலும் `மன்றத்தில்` என்ற வெளியீட்டாளர் முன்னுரை, `முக்கிய குறிப்பு` என்ற வெளியீட்டாளர் குறிப்பு, மற்றும் இறுதி விளம்பரப் பக்கம் உள்ளன.

## Publication-specific transcription rule — USER ESTABLISHED

> **User supplied transcription is the lexical baseline for all surviving words. The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, page/article boundaries and physical-copy evidence. Text physically lost to tears must not be reconstructed from context.**

Operationally:

- supplied transcription words are retained unless the user later authorises a lexical correction;
- source-visible structure/punctuation/paragraph breaks may be corrected;
- source-visible text omitted by the supplied transcription may be restored only when directly readable from the scan and must be documented;
- text under torn-away paper is never guessed;
- scan/transcription lexical disagreements are logged rather than silently substituted.

## Source identity

- source filename: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`
- physical scans: **16**
- source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- source file size: **26,071,193 bytes**
- source PDF committed: **No**
- printed contents page: **none**

## Critical source-order finding

The PDF physical scan sequence is **not the publication reading sequence**. The surviving copy was scanned in a leaf/imposition order. Pencil folio numbers `2`–`8` appear on scans 3, 5, 7, 9, 11, 13 and 15; they are physical-copy marks, not printed page numerals.

The reconstructed reading sequence from direct continuations and publisher cues is:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

See [`indexes/page-map.md`](indexes/page-map.md).

## Source condition

The book is heavily damaged. Large pieces of paper are missing from multiple scans, especially scans **3–4, 7–8, 11–16**. Damage cuts through printed lines on several body pages. Surviving words from the supplied transcription are retained; missing torn text is represented only by explicit source-damage comments and is not reconstructed.

Reverse-side show-through, ageing, stains and pencil folio marks are also visible. These are kept separate from printed text.

## Final strict-reviewed article assemblies

1. [`articles/01-thiraavida-sampaththu.md`](articles/01-thiraavida-sampaththu.md) — scans **5–6, 13–16** — **P5 PASS / strict-reviewed** — blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. [`articles/02-aiyar-arivikkirar.md`](articles/02-aiyar-arivikkirar.md) — scans **12, 3** — **P5 PASS / strict-reviewed** — blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

These two blobs are the frozen Tamil authorities for downstream English work. Both assemblies preserve reconstructed reading order, source-page comments and torn-text non-reconstruction. Article 1 retains the explicit scan-15/16 `SOURCE DAMAGE` markers.

## P5 non-regression

P5 rechecked **16 / 16 physical scans** word by word and punctuation by punctuation.

Documented lexical-witness conflicts were retained rather than silently substituted:

- scan 3: baseline `கல்லுரி` vs scan-appearing `கல்லூரி`;
- scan 4: baseline promoted title `ரூசோ` vs scan-visible `ஜூலி`;
- scan 5: baseline `கண்னை` vs scan-appearing `கண்ணை`;
- scan 16: baseline `பேச்சுல` vs scan-appearing `பேச்சை`.

Source-visible omissions/recoveries:

- scan 16 `மொழி.` — earlier documented recovery retained;
- scan 15 `கிரேக்க மொழி` — P5 directly restored visible omitted `ழி` from supplied `கிரேக்க மொ`.

No word physically hidden by missing paper was reconstructed.

Detailed P5 provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).  
Publication Tamil closeout: [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md).  
Combined source audit: [`audit.md`](audit.md).

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + reconstructed reading order + content map: **COMPLETE**
- P2 page-level transcription / structural review: **16 / 16 COMPLETE**
- P3 article assemblies: **COMPLETE — 2 / 2**
- P4 source audit / completeness review: **PASS**
- P5 strict word/punctuation fidelity pass: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- workflow blockers: **0**

## English translation status

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 close drafts: **1 / 2**
- T2 fidelity-reviewed: **1 / 2**
- T3 voice-reviewed: **0 / 2**
- T4 audited: **0 / 2**
- T5 verified: **0 / 2**
- English article bodies created: **1 / 2**
- English translation blockers: **0**

English workspace:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)
- [`translations/en/01-thiraavida-sampaththu.md`](translations/en/01-thiraavida-sampaththu.md) — Article 1 T2 fidelity-reviewed

Article 1 working English title: **Dravidian Wealth**. T2 found it semantically acceptable but it is not frozen yet.

- frozen Tamil authority: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`
- T1 baseline blob: `bb5937921ab00d532d91bc89c5a9df57dc8acaa2`
- T2 fidelity-reviewed English blob: `155299ac2b71b0aaba431f63d3c882191a3c710b`
- metadata status: `fidelity-reviewed`

Article 1 T2 checked every surviving paragraph/clause, retained source-page comments for scans **5, 6, 13, 14, 15, 16**, preserved all four scan-15/16 source-damage boundaries, reconstructed **0** hidden words, and made **0** frozen-Tamil changes. Fidelity corrections and terminology decisions are recorded in `translations/en/TRANSLATION_REVIEW.md` and `translations/en/LEXICON.md`.

## Exact next activity

Execute **Article 1 T3 — Kalaignar voice review** against frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015` and T2 English blob `155299ac2b71b0aaba431f63d3c882191a3c710b`.

Review directness, sarcasm, ridicule, rhetorical questions, repetition, abrupt contrasts, insults and monkey/tail/poison imagery. Make only meaning-neutral voice/cadence corrections, preserve T2-secured meaning and every `SOURCE DAMAGE` boundary, document each intervention, and stop after T3.

Do **not** perform T4 in the same activity, and do **not** reopen the frozen Tamil bodies for stylistic polishing, lexical conventionalisation or terminology homogenisation.