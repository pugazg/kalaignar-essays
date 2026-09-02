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

These are the frozen Tamil authorities.

## P5 non-regression

Documented lexical-witness conflicts remain frozen rather than silently substituted. Source-visible recoveries include scan 16 `மொழி.` and scan 15 `கிரேக்க மொழி`. No word physically hidden by missing paper was reconstructed.

Detailed Tamil provenance:

- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md)
- [`audit.md`](audit.md)

## Final Tamil archival status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **2 / 2 COMPLETE**
- P4: **PASS**
- P5: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- workflow blockers: **0**

## Final English translation / release status

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 close drafts: **2 / 2 PASS**
- T2 fidelity-reviewed: **2 / 2 PASS**
- T3 voice-reviewed: **2 / 2 PASS**
- T4 audited: **2 / 2 PASS**
- T5 verified: **2 / 2 PASS**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- English article bodies: **2 / 2**
- unresolved translation/release blockers: **0**
- **English translation: COMPLETE / RELEASED / FROZEN**

Released English authorities:

1. [`translations/en/01-thiraavida-sampaththu.md`](translations/en/01-thiraavida-sampaththu.md) — **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. [`translations/en/02-aiyar-arivikkirar.md`](translations/en/02-aiyar-arivikkirar.md) — **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Both article files retain `translation_status: verified`; E7 is the publication-level release closeout.

English records:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)

## E7 release result

E7 re-fetched live `main`, both E6-passed English authorities and both frozen Tamil authorities and confirmed:

- English article blobs unchanged from E6: **2 / 2 PASS**
- frozen Tamil authority blobs unchanged: **2 / 2 PASS**
- T0–T5 and E6 remain durable: **PASS**
- English body changes after E6: **0 / 2**
- English metadata changes after E6: **0 / 2**
- frozen Tamil changes during E7: **0**
- source/translation gates reopened: **No**
- source/release defects discovered: **0**
- release blockers: **0**

**E7 RESULT: PASS / ENGLISH TRANSLATION COMPLETE / RELEASE COMPLETE / FROZEN.**

## Release boundary

`திராவிட சம்பத்து` is now **COMPLETE / FROZEN / RELEASED in Tamil and English**. Do not reopen the frozen Tamil or released English bodies for stylistic polishing, lexical conventionalisation or terminology homogenisation. Reopen only for a genuine source-supported or release-blocking defect.

## Next activity

No further activity is pending for this publication. The next project activity is intake of the next supplied Kalaignar essay/article publication.