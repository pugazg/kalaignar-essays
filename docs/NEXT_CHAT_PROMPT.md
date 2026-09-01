# Next Chat Prompt — Kalaignar Essays / திராவிட சம்பத்து

Use this file only as a convenience handoff. **Live `main` and the root `HANDOVER.md` are authoritative.**

Continue the Kalaignar Essays / Articles archival project directly in:

`pugazg/kalaignar-essays`

Branch: `main`

Active publication:

`publications/thiraavida-sampaththu/` — **திராவிட சம்பத்து**

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. The last confirmed live HEAD immediately before this continuation prompt was synchronized was:

`6cb9258b9f4bb44ea96e63e4c4afe5135bc330a5` — `Advance Thiraavida Sampaththu handover to P5`

If `main` has advanced beyond that checkpoint, preserve the newer durable state. **Do not reset, overwrite, repeat or reopen later completed work merely because this prompt contains an older checkpoint.**

Before every write, re-fetch the target file and current live state as needed. Work directly on `main`.

## Mandatory startup

Before making any repository change, read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. `HANDOVER.md`
5. this `docs/NEXT_CHAT_PROMPT.md`
6. `publications/thiraavida-sampaththu/README.md`
7. `publications/thiraavida-sampaththu/metadata/source.md`
8. `publications/thiraavida-sampaththu/indexes/page-map.md`
9. `publications/thiraavida-sampaththu/indexes/contents.md`
10. `publications/thiraavida-sampaththu/audit.md`
11. `publications/thiraavida-sampaththu/articles/01-thiraavida-sampaththu.md`
12. `publications/thiraavida-sampaththu/articles/02-aiyar-arivikkirar.md`
13. all 16 page records for the P5 activity.

The controlling PDF must be attached/resolved for fresh page-level visual verification.

## Source identity

- source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`
- title: **திராவிட சம்பத்து**
- author: **கலைஞர் மு. கருணாநிதி**
- edition: **முதல பதிப்பு, செப்டம்பர் 1951**
- publisher: **அறிவு மன்றம், சென்னை-1**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை-1**
- physical scans: **16**
- source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- file size: **26,071,193 bytes**
- source PDF committed: **No**
- printed contents page: **none**

## Publication-specific lexical rule — USER ESTABLISHED

The user supplied a transcription that captured the surviving words and explicitly instructed:

- **use those transcription words as the lexical baseline**;
- review/correct **structure, punctuation, spacing, paragraphing, headings, reading order, boundaries and missing paragraphs/source-visible omissions** from the scan;
- never reconstruct words physically lost because the paper is torn away.

Therefore:

- do not silently replace a supplied word merely because the scan appears to show another lexical form;
- log scan/transcription lexical disagreements explicitly;
- a directly visible word omitted by the supplied transcription may be restored only as a documented source-visible recovery;
- torn-away text remains an explicit `SOURCE DAMAGE` gap, not a contextual reconstruction.

## Critical physical-order finding

The physical PDF scan sequence is **not publication reading order**. The source appears scanned in leaf/imposition order. Pencil folio marks `2`–`8` on alternating scans are physical-copy marks, not printed page numerals.

Reconstructed reading sequence:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

Direct continuations that must not regress:

- scan 6 `...என்று` → scan 13 `கூறினோம்.`;
- scan 15 `...திராவிடம், திராவிட` → scan 16 `மொழி. திராவிட...`;
- scan 7 `...முத` → scan 8 `லாவது...`;
- scan 8 → scan 11 within `முக்கிய குறிப்பு`;
- scan 12 `...வாயிலிலே நின்று` → scan 3 `கொண்டிருக்கிறார்...`.

## Publication units

1. cover — scan 1
2. imprint — scan 2
3. publisher foreword `மன்றத்தில்` — scans 9–10
4. Article 1 `திராவிட சம்பத்து` — scans **5–6, 13–16**
5. publisher note `முக்கிய குறிப்பு` — scans **7–8, 11**
6. Article 2 `ஐயர் அறிவிக்கிறார்!` — scans **12, 3**
7. advertisements — scan 4

## Current durable status

- P0 source intake: **COMPLETE**
- P1 metadata + page map + reading-order reconstruction: **COMPLETE**
- P2 page-level transcription / structural review: **16 / 16 COMPLETE**
- P3 article assemblies: **COMPLETE — 2 / 2**
- P4 source/completeness audit: **PASS**
- P5 strict word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

P3 assemblies:

- Article 1 `திராவிட சம்பத்து` — blob `43c1123a0bdb14dc20dc351a581b1e46c9df04fa`;
- Article 2 `ஐயர் அறிவிக்கிறார்!` — blob `357b7c7f7431b33e9c465956227337631550e2c1`.

P4 confirmed:

- all 16 physical scans are represented exactly once in reconstructed reading order;
- both article assemblies contain each mapped page once and in correct order;
- all required source-page comments are present;
- article boundaries are correct;
- `மன்றத்தில்`, `முக்கிய குறிப்பு` and scan-4 advertisements remain outside article bodies;
- mapped source segments missing/duplicated/out of order: **0**;
- user-baseline lexical substitutions made in P3/P4: **0**;
- P4 body corrections: **0**;
- no hidden text under torn paper was reconstructed.

## Source-damage / lexical non-regression

The source is heavily damaged. Large torn-away areas intersect printed text on several pages, especially scans **3–4, 7–8, 11–16**. Physical source loss must remain documented, not repaired by inference.

High-value decisions:

- scan 16 visible `மொழி.` was absent from the supplied transcription and remains a **documented source-visible missing-text recovery**;
- scan 15/16 Article 1 retains explicit `SOURCE DAMAGE` markers;
- scan 4 supplied advertisement-title reading `ரூசோ` remains the lexical baseline despite an apparent scan disagreement; log this in P5 rather than silently changing it;
- damaged/ambiguous supplied tokens such as scan-3 `அயம்` remain baseline readings unless the user explicitly authorises a lexical change.

## EXACT NEXT ACTIVITY

Execute **P5 — strict visual text-fidelity review across all 16 physical scans**.

1. Recheck cover, imprint, `மன்றத்தில்`, Article 1, `முக்கிய குறிப்பு`, Article 2 and scan-4 advertisements word by word and punctuation by punctuation.
2. Preserve the user-supplied lexical baseline for all surviving words; do not silently substitute scan-appearing lexical forms.
3. Record every scan/transcription lexical disagreement explicitly.
4. Correct only source-supported structure, punctuation, spacing, paragraphing, headings/layout and directly visible omitted material allowed by the user's rule.
5. Preserve all torn-away gaps without contextual reconstruction.
6. Propagate any permitted corrections into page records, assemblies, indexes, README, metadata, audit and handover.
7. Create `VISUAL_TEXT_FIDELITY_REVIEW.md` and, if P5 passes, `PUBLICATION_COMPLETION_REVIEW.md`.
8. **Do not begin English translation in the same P5 activity.**

## Previous publication non-regression

`உணர்ச்சிமாலை` remains **COMPLETE / FROZEN / RELEASED** in Tamil and English. Do not reopen it absent a genuine source-supported or release-blocking defect.

## Fresh-window execution rule

When the user says **“Proceed with next activity”**, do not ask them to restate context. Fetch live `main`, read the authoritative handover/current records, resolve the controlling PDF, and execute the exact P5 activity completely.
