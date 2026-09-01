# Next Chat Prompt — Kalaignar Essays / திராவிட சம்பத்து

Use this file only as a convenience handoff. **Live `main` and the root `HANDOVER.md` are authoritative.**

Continue the Kalaignar Essays / Articles archival project directly in:

`pugazg/kalaignar-essays`

Branch: `main`

Active publication:

`publications/thiraavida-sampaththu/` — **திராவிட சம்பத்து**

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. The last confirmed live HEAD immediately before this continuation prompt was synchronized was:

`4a9e6b74aae4a2c84a0d3e8e6211d2c9bfd1395d` — `Activate Thiraavida Sampaththu handover`

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
10. the page records needed for the exact activity below.

The supplied controlling PDF must be attached/resolved again if later work requires fresh page-level visual verification.

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

## Publication-specific lexical rule — USER ESTABLISHED

The user supplied a transcription that captured the surviving words and explicitly instructed:

- **use those transcription words as the lexical baseline**;
- review/correct **structure, punctuation, spacing, paragraphing, headings, reading order, boundaries and missing paragraphs/source-visible omissions** from the scan;
- never reconstruct words physically lost because the paper is torn away.

Therefore:

- do not silently replace a supplied word merely because the scan appears to show another lexical form;
- log scan/transcription lexical disagreements for explicit later review;
- a directly visible word omitted by the supplied transcription may be restored only as a documented source-visible recovery;
- torn-away text remains an explicit `SOURCE DAMAGE` gap, not a contextual reconstruction.

## Critical physical-order finding

The physical PDF scan sequence is **not publication reading order**. The source appears scanned in leaf/imposition order. Pencil folio marks `2`–`8` on alternating scans are physical-copy marks, not printed page numerals.

Reconstructed reading sequence:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

Direct continuations that must not regress:

- scan 6 `...என்று` → scan 13 `கூறினோம்.`;
- scan 15 → scan 16;
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

No printed contents page exists.

## Current durable status

- P0 source intake: **COMPLETE**
- P1 metadata + page map + reading-order reconstruction: **COMPLETE**
- P2 page-level transcription / structural review: **16 / 16 COMPLETE**
- P3 article assemblies: **NOT STARTED**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

The source is heavily damaged. Large torn-away areas intersect printed text on several pages. This physical loss is documented and must not be repaired by inference.

High-value decisions already recorded:

- scan 16 visible `மொழி.` was absent from the supplied transcription and was restored as a **documented source-visible missing-text recovery**;
- scan 4 supplied advertisement-title reading `ரூசோ` remains the lexical baseline despite an apparent scan disagreement; this is a provisional lexical-witness conflict, not a silent correction;
- damaged/ambiguous supplied tokens such as scan-3 `அயம்` remain baseline readings unless explicitly reopened later.

## EXACT NEXT ACTIVITY

Execute **P3 article assembly + initial P4 source/completeness audit**.

1. Create `publications/thiraavida-sampaththu/articles/01-thiraavida-sampaththu.md` from verified scans **5–6, 13–16** in reconstructed reading order.
2. Create `publications/thiraavida-sampaththu/articles/02-aiyar-arivikkirar.md` from verified scans **12, 3** in reconstructed reading order.
3. Preserve every source-page boundary comment and every `SOURCE DAMAGE` marker. Never invent hidden words.
4. Run P4 across the full 16-scan publication, confirming cover/imprint, `மன்றத்தில்`, Article 1, `முக்கிய குறிப்பு`, Article 2 and advertisement boundaries/read order.
5. Create/update the publication audit/completion record needed by the repository workflow and synchronize README, indexes and root `HANDOVER.md` if P4 changes durable state.
6. Stop after P4. **Do not execute P5 or begin English translation in the same activity.**

## Previous publication non-regression

`உணர்ச்சிமாலை` remains **COMPLETE / FROZEN / RELEASED** in Tamil and English. Do not reopen it absent a genuine source-supported or release-blocking defect.

## Fresh-window execution rule

When the user says **“Proceed with next activity”**, do not ask them to restate context. Fetch live `main`, read the authoritative handover/current records, and execute the exact P3+P4 activity completely.