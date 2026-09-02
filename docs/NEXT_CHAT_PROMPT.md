# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this file only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Continue directly in:

`pugazg/kalaignar-essays`

Branch: `main`

Active publication:

`publications/ina-muzhakkam/` — **இன முழக்கம்**

Controlling source:

`TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. The last confirmed durable state before this prompt synchronization includes:

`f348319ba16022edd425cdb92f62efff21c72bc5` — `Synchronize Ina Muzhakkam source metadata after P2`

If `main` has advanced, preserve the newer durable state. **Do not reset, overwrite, repeat or reopen later completed work merely because this prompt records an older checkpoint.**

Before every write, re-fetch the target file and current live state as needed. Work directly on `main`.

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. this `docs/NEXT_CHAT_PROMPT.md`
6. `publications/ina-muzhakkam/README.md`
7. `publications/ina-muzhakkam/metadata/source.md`
8. `publications/ina-muzhakkam/indexes/contents.md`
9. `publications/ina-muzhakkam/indexes/page-map.md`
10. `publications/ina-muzhakkam/STRUCTURAL_REASSEMBLY_REVIEW.md`
11. `publications/ina-muzhakkam/transcription-intake/USER_CORRECTIONS.md`
12. all canonical P2 records under `publications/ina-muzhakkam/pages/`

## Publication-specific user rule

The user supplied the complete word-to-word transcription and explicitly instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The user transcription remains the lexical baseline. P2 has already applied source-supported structure and user-authorised placement corrections. Do **not** silently substitute scan-appearing lexical variants during P3 assembly.

## Durable state

- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- physical scans: **50**
- P0: **COMPLETE**
- P1: **COMPLETE**
- structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 assemblies: **0 / 6**
- P4: **NOT STARTED**
- P5: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

P2 non-regression:

- printed text / physical-copy marks separated on all 50 records;
- only directly visible printed numerals recorded;
- heading scans 6, 14, 25, 30 and 38 use `printed_page: null`;
- scan 10 retains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 22 trailing `2` excluded as non-source noise;
- scan 24 promotion outside `சொர்க்க லோகத்தில்`;
- `பழிக்குப் பழி` final lines canonically on scan 37, with following promotion outside article;
- scan 40 is poetry introductory/review matter, outside the `கவிதைகள்` body;
- `வா!` begins scan 43;
- `யோசித்துப் பார்!` begins scan 44;
- scans 41–49 preserve source-supported poetry headings/lineation;
- scan 50 is catalogue matter outside all body units; source/baseline lexical or number differences there remain deferred rather than silently rewritten.

Printed contents witness:

1. `இன முழக்கம்` — 4
2. `சொர்க்க லோகத்தில்` — 13
3. `முரசறைவாய்` — 24
4. `பழிக்குப் பழி` — 29
5. `ஆரியம் பேசுகிறது` — 37
6. `கவிதைகள்` — 40

## EXACT NEXT ACTIVITY

Proceed with **P3 article/section assembly** from the verified canonical P2 page records.

Create exactly these six reading assemblies:

1. `இன முழக்கம்` — scans 6–13;
2. `சொர்க்க லோகத்தில்` — scans 14–24, excluding the scan-24 `திராவிட சம்பத்து` promotion;
3. `முரசறைவாய்` — scans 25–29;
4. `பழிக்குப் பழி` — scans 30–37, excluding the scan-37 two-novel promotion;
5. `ஆரியம் பேசுகிறது` — scans 38–39;
6. `கவிதைகள்` — scans 41–49, preserving all source-visible poem headings and verse lineation.

Requirements:

1. assemble from canonical `pages/` records, **not** the staging transcription;
2. preserve P2 wording and punctuation without lexical normalisation;
3. include page-boundary provenance/comments;
4. preserve scan-10 `விசயர்` placement exactly;
5. do not import scans 1–5 front matter, scan 24/37 promotions, scan 40 author/review matter or scan 50 catalogue into the six body assemblies;
6. preserve every poem heading and verse lineation from P2;
7. update README, indexes and root handover after all six assemblies;
8. **stop after P3** — do not begin P4 in the same activity.

Publications 1–4 remain **COMPLETE / FROZEN / RELEASED** and must not be reopened absent a genuine source-supported or release-blocking defect.