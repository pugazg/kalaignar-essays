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

The PDF physical scan sequence is **not** the publication reading sequence. The reconstructed reading sequence is:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

See [`indexes/page-map.md`](indexes/page-map.md).

## Source condition

The book is heavily damaged. Large pieces of paper are missing from multiple scans, especially scans **3–4, 7–8, 11–16**. Missing torn text is represented only by explicit source-damage comments and is not reconstructed.

## Final strict-reviewed Tamil assemblies

1. [`articles/01-thiraavida-sampaththu.md`](articles/01-thiraavida-sampaththu.md) — scans **5–6, 13–16** — **P5 PASS / strict-reviewed** — blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. [`articles/02-aiyar-arivikkirar.md`](articles/02-aiyar-arivikkirar.md) — scans **12, 3** — **P5 PASS / strict-reviewed** — blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

These are the frozen Tamil authorities for downstream English work.

## P5 non-regression

Documented lexical-witness conflicts were retained rather than silently substituted:

- scan 3: baseline `கல்லுரி` vs scan-appearing `கல்லூரி`;
- scan 4: baseline promoted title `ரூசோ` vs scan-visible `ஜூலி`;
- scan 5: baseline `கண்னை` vs scan-appearing `கண்ணை`;
- scan 16: baseline `பேச்சுல` vs scan-appearing `பேச்சை`.

Source-visible recoveries include scan 16 `மொழி.` and scan 15 `கிரேக்க மொழி`. No word physically hidden by missing paper was reconstructed.

Detailed P5 provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).  
Publication Tamil closeout: [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md).  
Combined source audit: [`audit.md`](audit.md).

## Current Tamil archival status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **2 / 2 COMPLETE**
- P4: **PASS**
- P5: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- workflow blockers: **0**

## English translation status

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 close drafts: **2 / 2**
- T2 fidelity-reviewed: **1 / 2**
- T3 voice-reviewed: **1 / 2**
- T4 audited: **1 / 2**
- T5 verified: **1 / 2**
- English article bodies created: **2 / 2**
- English translation blockers: **0**

English workspace:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)
- [`translations/en/01-thiraavida-sampaththu.md`](translations/en/01-thiraavida-sampaththu.md) — **Article 1 VERIFIED**
- [`translations/en/02-aiyar-arivikkirar.md`](translations/en/02-aiyar-arivikkirar.md) — **Article 2 T1 draft**

## Article 1 — verified English boundary

- English title: **Dravidian Wealth — VERIFIED**
- frozen Tamil authority: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`
- final T5 verified English blob: `10dca72882043db491fe8c6ad3f858bc4c9c584f`
- metadata status: `verified`
- T5 body corrections: **0**

## Article 2 — T1 draft boundary

- Tamil title: `ஐயர் அறிவிக்கிறார்!`
- working English title: **Iyer Announces!** — not frozen
- frozen Tamil authority: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`
- T1 English draft blob: `1b70952ae377668162fcb35eb045e142a0597190`
- metadata status: `draft`
- source-page comments: **2 / 2 present**
- `ஐயர்` / `அய்யர்`: working **Iyer / Ayyar** distinction retained
- damaged/ambiguous frozen `அயம்`: **ayam**, not guessed
- `ஏனோதானோ` / `ஏனோதானோக்கள்`: working **Enothano / Enothanos**
- normal `கல்லூரி`: **College**; frozen scan-3 `கல்லுரி`: working source-bearing **kalluri**
- quoted inscription: working source-bearing **Maha Mahopadhyaya Dravida Vidya Bhushana Dr. Saminatha Ayyar**
- frozen Tamil changes during T1: **0**
- unresolved T1 blockers: **0**

## Exact next activity

Execute **Article 2 T2 — bilingual fidelity review** against frozen Tamil blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6` and T1 English blob `1b70952ae377668162fcb35eb045e142a0597190`.

Compare every surviving clause and paragraph side by side. Audit the working title, `Iyer` / `Ayyar`, damaged source-bearing `ayam`, `Enothano(s)`, normal `College` versus frozen anomalous `kalluri`, quotation scope, inscription wording and both source-page comments. Make only fidelity-required corrections and document them.

**Stop after Article 2 T2. Do not perform Article 2 T3 in the same activity, and do not reopen the frozen Tamil bodies absent a genuine source-supported correction.**