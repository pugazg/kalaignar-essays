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

`e2aa7950ceb22211d5ec40513c9a86ac6ae3bc7f` — `Advance root status through Ina Muzhakkam P3 completion`

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
13. all six P3 assemblies under `publications/ina-muzhakkam/articles/`

## Publication-specific user rule

The user supplied the complete word-to-word transcription and explicitly instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The user transcription remains the lexical baseline. P2 applied source-supported structure and user-authorised placement corrections; P3 assembled only from canonical P2 records. Do **not** silently substitute scan-appearing lexical variants during P4.

## Durable state

- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- physical scans: **50**
- P0: **COMPLETE**
- P1: **COMPLETE**
- structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4: **NOT STARTED**
- P5: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

P3 assembly authorities:

1. `articles/01-ina-muzhakkam.md` — blob `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`
2. `articles/02-sorgga-logaththil.md` — blob `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`
3. `articles/03-murasaraivai.md` — blob `698c178ee5a65e9fe53543be2136e6691f5a8dad`
4. `articles/04-pazhikku-pazhi.md` — blob `d9c57a7a55ab33310b512c34322186cc55a04ef8`
5. `articles/05-aariyam-pesugirathu.md` — blob `651063d641ddbc53c1688e92b13d976b169d04ee`
6. `articles/06-kavithaigal.md` — blob `a11dfc65bfd83c316e090c793f1ede102a72ac21`

Non-regression:

- printed text / physical-copy marks remain separated on all 50 P2 records;
- only directly visible printed numerals are recorded;
- heading scans 6, 14, 25, 30 and 38 use `printed_page: null`;
- scan 10 retains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...` in both P2 and P3;
- scan 22 trailing `2` remains excluded as non-source noise;
- scan 24 promotion remains outside `சொர்க்க லோகத்தில்`;
- `பழிக்குப் பழி` final lines remain on scan 37 and the following promotion remains outside the article;
- scan 40 remains poetry introductory/review matter outside the `கவிதைகள்` body;
- `வா!` begins scan 43;
- `யோசித்துப் பார்!` begins scan 44;
- scans 41–49 preserve source-supported poetry headings and lineation;
- scan 50 remains catalogue matter outside all body units;
- no lexical normalisation was introduced in P3;
- known cover-author and scan-50 lexical/number source/baseline differences remain deferred for explicit audit/fidelity handling.

Printed contents witness:

1. `இன முழக்கம்` — 4
2. `சொர்க்க லோகத்தில்` — 13
3. `முரசறைவாய்` — 24
4. `பழிக்குப் பழி` — 29
5. `ஆரியம் பேசுகிறது` — 37
6. `கவிதைகள்` — 40

## EXACT NEXT ACTIVITY

Proceed with **P4 source/completeness audit** only.

Audit the completed canonical P2 page layer and the six P3 assemblies. Confirm:

1. all **50 / 50** physical scans have canonical P2 records;
2. the six contents-listed reading assemblies exist exactly once;
3. each assembly begins and ends on the source-supported scan boundaries recorded in the page map;
4. page-to-page continuations occur in correct order with provenance comments retained;
5. scan-10 `விசயர்` placement remains exact;
6. scan-24 and scan-37 promotional matter is absent from article bodies;
7. scan-40 `கவிதைகளைப் பற்றி` / `மதிப்புரை` material is absent from the `கவிதைகள்` body;
8. scan-50 catalogue is absent from all six body assemblies;
9. all poetry headings and verse lineation agree with canonical P2;
10. contents-page start-number witnesses remain distinct from directly visible page numerals;
11. no physical-copy marks were imported into printed/body text;
12. no silent lexical normalisation was introduced during P2 or P3;
13. known deferred scan/baseline lexical or number disagreements are explicitly classified/documented for P5 rather than silently corrected;
14. blocked/needs-review counts and publication completeness result are explicitly recorded.

Create/update the appropriate P4 audit/completeness record and synchronize publication README, metadata/indexes, root `HANDOVER.md`, root README and this prompt as needed.

**Stop after P4 — do not begin P5 in the same activity.**

Publications 1–4 remain **COMPLETE / FROZEN / RELEASED** and must not be reopened absent a genuine source-supported or release-blocking defect.