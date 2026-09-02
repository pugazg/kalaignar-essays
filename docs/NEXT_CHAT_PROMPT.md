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

`a8ff7cf6da3e551abe9565dc0c3457b7bc03d22f` — `Synchronize Ina Muzhakkam P4 handover`

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
11. `publications/ina-muzhakkam/SOURCE_COMPLETENESS_AUDIT.md`
12. `publications/ina-muzhakkam/transcription-intake/USER_CORRECTIONS.md`
13. all canonical P2 records under `publications/ina-muzhakkam/pages/`
14. all six P3 assemblies under `publications/ina-muzhakkam/articles/`

## Publication-specific user rule

The user supplied the complete word-to-word transcription and explicitly instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The user transcription remains the lexical baseline. P2 applied source-supported structure and user-authorised placement corrections; P3 assembled only from canonical P2 records; P4 completed the source/completeness audit without lexical normalisation. During P5, **do not silently substitute scan-appearing lexical variants**. Every lexical scan/baseline disagreement must be explicitly classified.

## Durable state

- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- physical scans: **50**
- P0: **COMPLETE**
- P1: **COMPLETE**
- structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4 source/completeness audit: **PASS / COMPLETE**
- P5 strict visual fidelity: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

P3 assembly authorities before P5:

1. `articles/01-ina-muzhakkam.md` — blob `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`
2. `articles/02-sorgga-logaththil.md` — blob `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`
3. `articles/03-murasaraivai.md` — blob `698c178ee5a65e9fe53543be2136e6691f5a8dad`
4. `articles/04-pazhikku-pazhi.md` — blob `d9c57a7a55ab33310b512c34322186cc55a04ef8`
5. `articles/05-aariyam-pesugirathu.md` — blob `651063d641ddbc53c1688e92b13d976b169d04ee`
6. `articles/06-kavithaigal.md` — blob `a11dfc65bfd83c316e090c793f1ede102a72ac21`

P4 confirmed:

- canonical P2 scan coverage: **50 / 50 PASS**;
- six P3 assemblies exist exactly once: **PASS**;
- all source-supported start/end boundaries: **PASS**;
- page-continuation/provenance order: **PASS**;
- scan-10 `விசயர்`: **PASS**;
- scan-24/37 promotions excluded from body assemblies: **PASS**;
- scan-40 poetry front matter excluded from `கவிதைகள்`: **PASS**;
- scan-50 catalogue excluded from body assemblies: **PASS**;
- poetry headings/lineation: **PASS**;
- contents-page start numbers remain separate from directly visible body numerals: **PASS**;
- physical-copy marks imported into body text: **0**;
- silent lexical normalisations introduced during P2/P3: **0**;
- P4 needs-review: **0**;
- P4 blocked: **0**;
- completeness blockers: **0**.

P4 audit authority:

`publications/ina-muzhakkam/SOURCE_COMPLETENESS_AUDIT.md`

## Non-regression

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
- no lexical normalisation may be introduced during P5;
- the cover-author and scan-50 catalogue issues are **P5 fidelity classifications**, not P4 completeness blockers.

Printed contents witness:

1. `இன முழக்கம்` — 4
2. `சொர்க்க லோகத்தில்` — 13
3. `முரசறைவாய்` — 24
4. `பழிக்குப் பழி` — 29
5. `ஆரியம் பேசுகிறது` — 37
6. `கவிதைகள்` — 40

## Deferred P5 witness items

P5 must explicitly inspect and classify, without silently replacing the lexical baseline:

1. **cover author** — visible scan witness `மு. கருணாநிதி` versus supplied baseline `கலைஞர் கருணாநிதி`;
2. **scan 50 catalogue** — documented lexical/number differences or omissions, including the `அழகு நிலா` / `செல்வ குமாரி` price forms and missing `நாடறிந்த நட்சத்திரங்கள்` price.

Any additional scan/baseline lexical disagreement found during the strict pass must be added to the same explicit fidelity record.

## EXACT NEXT ACTIVITY

Proceed with **P5 strict visual word/punctuation fidelity** over all **50 physical scans** only.

Requirements:

1. fetch live `main` and preserve any newer durable state;
2. directly inspect **every physical scan 1–50**, including cover, front matter, contents, prose, promotions, poetry front matter, poems and catalogue;
3. check every visible printed word, word boundary/spacing, punctuation mark, quotation mark, heading, date, number, paragraph continuation, page boundary and source witness against the canonical page record;
4. keep the user-supplied lexical baseline; **do not silently replace lexical tokens with scan-appearing variants**;
5. explicitly classify every scan/baseline lexical disagreement in a permanent P5 fidelity record;
6. preserve the user-established scan-10 sequence exactly: `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
7. explicitly inspect/classify the cover-author witness and all scan-50 catalogue differences/omissions;
8. re-confirm the scan-24 and scan-37 promotion boundaries, scan-40 poetry-front-matter boundary and scan-50 body exclusion;
9. preserve every source-visible poetry heading and source lineation;
10. for any source-supported **structural / punctuation / spacing / heading / placement** correction, record old reading → source-visible reading provenance;
11. propagate every P5 correction to the corresponding page record and any affected P3 assembly, index, README/audit/handover record;
12. create/update `publications/ina-muzhakkam/VISUAL_TEXT_FIDELITY_REVIEW.md` with all 50 scans checked, correction log, lexical-witness conflicts, physical-copy exclusions, needs-review/blocked counts and final gate result;
13. after page-level P5, re-check all six P3 assemblies against the P5-corrected page layer;
14. only if **50 / 50 scans** and **6 / 6 assemblies** pass with no unresolved body-text blocker, mark Tamil **P5 COMPLETE / FROZEN** and record the resulting six frozen Tamil article blob SHAs;
15. synchronize publication README, metadata/indexes, root `HANDOVER.md`, root README and this continuation prompt.

**Stop after P5. Do not begin English translation in the same activity.**

Publications 1–4 remain **COMPLETE / FROZEN / RELEASED** and must not be reopened absent a genuine source-supported or release-blocking defect.