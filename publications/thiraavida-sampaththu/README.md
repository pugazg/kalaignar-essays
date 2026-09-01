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

## Article assemblies

1. [`articles/01-thiraavida-sampaththu.md`](articles/01-thiraavida-sampaththu.md) — scans **5–6, 13–16** — P3 complete / P4 source-complete.
2. [`articles/02-aiyar-arivikkirar.md`](articles/02-aiyar-arivikkirar.md) — scans **12, 3** — P3 complete / P4 source-complete.

Both assemblies preserve the reconstructed reading order, source-page comments and torn-text non-reconstruction rule. Article 1 retains the explicit scan-15/16 `SOURCE DAMAGE` markers and the documented scan-16 source-visible recovery `மொழி.`.

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + reconstructed reading order + content map: **COMPLETE**
- P2 page-level transcription / structural review: **16 / 16 COMPLETE**
- direct scan structure/punctuation/paragraph review: **16 / 16**
- P3 article assemblies: **COMPLETE — 2 / 2**
- P4 source audit / completeness review: **PASS**
- P5 strict word/punctuation fidelity pass: **NOT STARTED**
- English translation: **NOT STARTED**

P4 confirmed all 16 physical scans are represented exactly once in the reconstructed publication order, both article boundaries are correct, publisher matter/advertisements remain outside the article bodies, no mapped body segment is missing or duplicated, and no user-baseline lexical token was silently replaced. Physical paper loss remains documented rather than reconstructed.

Detailed P4 record: [`audit.md`](audit.md).

## Exact next activity

Execute **P5 — strict visual text-fidelity review across all 16 physical scans**, word by word and punctuation by punctuation, under the publication-specific lexical-baseline rule. Record every permitted structural/punctuation/spacing/layout correction and every scan/transcription lexical conflict; preserve all torn-away gaps without reconstruction. Propagate corrections to dependent records and create `VISUAL_TEXT_FIDELITY_REVIEW.md` plus `PUBLICATION_COMPLETION_REVIEW.md` if P5 passes. Do **not** begin English translation in the same activity.
