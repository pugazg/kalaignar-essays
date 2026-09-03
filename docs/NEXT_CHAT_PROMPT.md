# Next Chat Prompt — Kalaignar Essays / குடும்பத்தின் நல்விளக்கு

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/kudumbaththin-nalvilakku/` — **குடும்பத்தின் நல்விளக்கு**  
Controlling source: `TVA_BOK_0065602_குடும்பத்தின்_நல்விளக்கு.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset, repeat or reopen completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`61564a57a53b70d761c5ba3f0779fc6640900187` — `Activate Kudumbaththin Nalvilakku after P0 intake`

## Mandatory startup

Before changing anything, read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `docs/FUTURE_WORK_GUIDELINES.md`
3. root `HANDOVER.md`
4. this prompt
5. `docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`
6. `publications/kudumbaththin-nalvilakku/README.md`
7. `publications/kudumbaththin-nalvilakku/metadata/source.md`

Read `ESSAY_TRANSLATION_GUIDE.md` only when English later enters scope; English is not yet active.

## Source must be resolved in the fresh chat

The source PDF is **not committed to GitHub**. Attach or otherwise resolve the exact controlling PDF before direct scan-level work:

`TVA_BOK_0065602_குடும்பத்தின்_நல்விளக்கு.pdf`

Expected identity:

- SHA-256: `1c3389ec76507b0c6f2ae294a4523633e81084d570a1443c7b730ac899e15971`
- file size: **34,464,808 bytes**
- physical scans: **16**

Do not substitute a different edition or web/OCR text.

## Current durable state — P0 COMPLETE

The supplied scan identifies a standalone single-article family-welfare pamphlet:

- title: **குடும்பத்தின் நல்விளக்கு**
- printed author line: **முதல்வர் டாக்டர் கலைஞர் மு. கருணாநிதி**
- departmental publication line: **தமிழ்நாடு குடும்பநலத்துறை வெளியீடு**
- back-cover printing line: **மாநில குடும்பநல அச்சகம், சென்னை-6**
- printed contents page: **none visible**
- edition/year: **not established from the supplied scans at P0**
- prior work/duplicate source ID in repo: **not found**

Preliminary scan structure:

1. scan 1 — front cover
2. scan 2 — title page, with library stamps/handwriting
3. scan 3 — author portrait
4. scans 4–13 — body article `குடும்பத்தின் நல்விளக்கு`
5. scan 14 — visually blank / faint show-through
6. scan 15 — full-page family illustration
7. scan 16 — back cover

Preliminary printed-page evidence:

- scan 4 — article opening, no visible numeral
- scans 5–12 — visible printed numerals **2–9**
- scan 13 — article ending, no visible numeral

Do not infer missing page numbers.

## Current gate status

- P0 — source intake / publication identification: **COMPLETE / PASS**
- P1 — metadata + page map + contents mapping: **NOT STARTED**
- P2 — page-level transcription: **NOT STARTED**
- P3 — article assembly: **NOT STARTED**
- P4 — source/completeness audit: **NOT STARTED**
- P5 — strict visual fidelity: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0 at P0**

## Source authority

The supplied scan is controlling. Do not silently modernise, correct, normalise, reconstruct or improve Kalaignar's Tamil. Separate printed text from library stamps, handwriting, foxing, show-through and other physical-copy marks. OCR/parsed text is not authoritative.

## EXACT NEXT ACTIVITY

**P1 — metadata + page map + contents mapping only.**

1. fetch live `main` first;
2. re-read root handover and active README/source record;
3. resolve and directly inspect all **16** scans;
4. create `publications/kudumbaththin-nalvilakku/indexes/page-map.md` covering every physical scan;
5. create `publications/kudumbaththin-nalvilakku/indexes/contents.md`, explicitly recording that no printed contents page exists and that P0 identifies one body article;
6. confirm the article start/end from scan-visible evidence, currently **scan 4 → scan 13**;
7. record only visible printed page numbers and physical-copy marks; do not infer absent numerals;
8. synchronize README, metadata, root handover and this prompt;
9. **STOP AFTER P1. DO NOT BEGIN P2 PAGE TRANSCRIPTION IN THE SAME ACTIVITY.**
