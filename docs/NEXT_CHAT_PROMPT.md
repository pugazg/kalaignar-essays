# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`baf34e58044a41b74b0063fdf15839e7c36c9f2e` — `Synchronize handover after Ina Muzhakkam Article 3 T5`

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. this prompt
6. `publications/ina-muzhakkam/README.md`
7. `publications/ina-muzhakkam/VISUAL_TEXT_FIDELITY_REVIEW.md`
8. `publications/ina-muzhakkam/metadata/source.md`
9. `publications/ina-muzhakkam/TRANSLATION_PLAN.md`
10. `publications/ina-muzhakkam/translations/en/README.md`
11. `publications/ina-muzhakkam/translations/en/LEXICON.md`
12. `publications/ina-muzhakkam/translations/en/TRANSLATION_REVIEW.md`
13. frozen Tamil `publications/ina-muzhakkam/articles/04-pazhikku-pazhi.md`

Articles 1–3 are T5 verified and individually frozen. They are non-regression references only; do not reopen them during Article 4 work without a genuine source-supported defect.

## Frozen Tamil authority

Tamil P0–P5 is **COMPLETE / STRICT-REVIEWED / FROZEN**.

Frozen Tamil authorities:

1. `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010` — `இன முழக்கம்`
2. `8fea1497ed2dcbdb395418590c1b9875e6066b8c` — `சொர்க்க லோகத்தில்`
3. `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8` — `முரசறைவாய்`
4. `e140df7f6234e8362b9139793706533fec0c62d8` — `பழிக்குப் பழி`
5. `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675` — `ஆரியம் பேசுகிறது`
6. `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c` — `கவிதைகள்`

## Current durable state

- Tamil P0–P5: **COMPLETE / FROZEN**
- E0: **COMPLETE / PASS**
- T0: **6 / 6 PASS**
- T1: **3 / 6 PASS**
- T2: **3 / 6 PASS**
- T3: **3 / 6 PASS**
- T4: **3 / 6 PASS**
- T5: **3 / 6 PASS**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Articles 1–3 verified boundary

- Article 1 `இன முழக்கம்` — **The Clarion Call of the Race** — T5 English `01d0d16c4f52cb134eba9fd35c06ad8376e256cb` — 8/8 comments.
- Article 2 `சொர்க்க லோகத்தில்` — **In the Heavenly Realm** — T5 English `bcd98fb1abf03e3109da1c4802570b77fddfe015` — 11/11 comments.
- Article 3 `முரசறைவாய்` — **Beat the Drum** — T5 English `c526195d7eb16b2dc446f8b3b15ae674c75548d5` — 5/5 comments.

Preserve their verified terminology/source-witness decisions where the same Tamil form/function genuinely recurs; do not mechanically overwrite distinct Article-4 source forms.

## Article 3 T5 durable boundary

- frozen Tamil blob: `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`
- verified English blob: `c526195d7eb16b2dc446f8b3b15ae674c75548d5`
- verified title: **Beat the Drum**
- `translation_status: verified`
- source comments: **5 / 5 preserved in order**
- scan-25→26: `ches— / t`
- scan-28→29: `dwarf / fox`
- T2 fidelity corrections: **3 / 3 preserved**
- T3 voice/style corrections: **6 / 6 preserved**
- T4 body corrections: **0**
- T5 body corrections: **0**
- blockers: **0**

T5 reread the complete T4 English against frozen Tamil and all T1–T4 decisions. Completeness, meaning, directness, martial/polemical voice, terminology, source-witness distinctions, quotation/source treatment and page provenance all passed. No final body correction was required. Article 3 is individually frozen.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered source comments and documented page-boundary traces;
- preserve quotation status and source punctuation irregularities;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- Articles 1–3 verified English decisions must not be reopened without genuine source support.

## EXACT NEXT ACTIVITY

**Article 4 `பழிக்குப் பழி` — T1 close English draft only.**

1. fetch live `main`;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 4 and confirm blob `e140df7f6234e8362b9139793706533fec0c62d8`;
4. establish the English title from frozen Tamil only;
5. establish only terminology/source-bearing choices actually encountered, preserving Articles 1–3 verified decisions where the same form/function genuinely recurs but not mechanically harmonising distinct forms;
6. translate the complete frozen Article 4 paragraph by paragraph preserving direct address, commands, rhetorical questions, repetition, polemical force, quotation structure and every ordered source-page comment;
7. do not use OCR, raw supplied transcription, scan-alternate lexical readings, web text, later editions or outside identification as translation authority;
8. create/update `publications/ina-muzhakkam/translations/en/04-pazhikku-pazhi.md` with `translation_status: draft`;
9. record the T1 English blob, title and exact lexicon/source-bearing decisions across durable records;
10. **STOP AFTER ARTICLE 4 T1. DO NOT PERFORM ARTICLE 4 T2 IN THE SAME ACTIVITY.**