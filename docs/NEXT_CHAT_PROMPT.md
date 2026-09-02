# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`308877a2dc0447967b31e8555dd4a77954dffc14` — `Synchronize handover after Ina Muzhakkam Article 1 T5`

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
13. frozen Tamil `articles/02-sorgga-logaththil.md`

Article 1 `translations/en/01-ina-muzhakkam.md` is now T5 verified and should be treated as an article-level non-regression reference, not reopened during Article 2 work.

## Frozen Tamil authority

The Tamil P5 layer is **COMPLETE / STRICT-REVIEWED / FROZEN**. Do not reopen it for translation convenience.

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
- T1: **1 / 6 PASS**
- T2: **1 / 6 PASS**
- T3: **1 / 6 PASS**
- T4: **1 / 6 PASS**
- T5: **1 / 6 PASS**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T5 verified boundary

- Tamil title: `இன முழக்கம்`
- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `translations/en/01-ina-muzhakkam.md`
- verified English title: **The Clarion Call of the Race**
- T4 English blob: `8d3238ca5cd309660c6d938b8f546eca2ba5698c`
- T5 verified English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status: verified`
- source-page comments: **8 / 8 preserved in order**
- T2 fidelity corrections preserved: **5 / 5**
- T3 voice/style body corrections preserved: **10 / 10**
- T4 body corrections: **0**
- T5 body corrections: **0**
- blockers: **0**

### Article 1 verified decisions — non-regression reference

- `இன முழக்கம்` → **The Clarion Call of the Race**; contextual closing occurrence → **the clarion call of the race**;
- `திராவிடன்` → **Dravidian**;
- `திராவிட இனம்` / `ஆரிய இனம்` → **Dravidian race / Aryan race**;
- `சுயமரியாதைக்காரன்` → **Self-Respecter**;
- incomplete `சுயமரியாதைக் ....` → **Self-Respect ....**;
- incomplete `அளித் ....` → **giv....**;
- repeated `தமிழன்` → **Tamilian**;
- `காமராஜ நாடார்` → **Kamaraj Nadar**;
- `கிராமணியார்` → **Gramaniyar**;
- frozen `கனக விசயர்` → **Kanaka Visayar** without outside identification;
- `பாரிவள்ளல்` → **Vallal Pari**;
- `அருட்பெருஞ் சோதி` → **Arutperum Jothi**;
- source distinction `வடலூர் இராமலிங்கம்` / vocative `வடலூர் இராமலிங்கரே` remains **Vadalur Ramalingam / Vadalur Ramalingar**;
- scan-9→10 `அல்லலுற்` / `றோமே` remains `suf—` / `fer......`;
- Vallal Pari's unmatched outer opening quotation remains a documented frozen source punctuation anomaly.

Article 1 is individually frozen at T5. Reopen only for a genuine source-supported defect. Do not alter it merely to make Article 2 terminology look more uniform.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only the frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered `<!-- Tamil source: scan ... -->` comments;
- preserve quotation status and documented source punctuation anomalies;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- frozen source-sensitive forms such as `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives;
- Article 1 verified English decisions must not be reopened without a genuine source-supported defect.

## EXACT NEXT ACTIVITY

**Article 2 `சொர்க்க லோகத்தில்` — T1 close draft only.**

1. fetch live `main`;
2. re-read the translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 2 and confirm blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c`;
4. establish the English title from the frozen Tamil only;
5. establish only the Article-2 names, ideological/social labels, source-specific transliterations and difficult recurring terms actually encountered; preserve Article-1 verified decisions where the same Tamil form/function genuinely recurs, but do not force them mechanically onto a different context;
6. translate the complete Article-2 frozen Tamil paragraph by paragraph, preserving quotation structure, direct address, commands, rhetorical questions, repetition, irony/ridicule, polemical force and every ordered source-page comment;
7. do not use OCR, raw supplied transcription, scan-alternate lexical readings, web text, later editions or outside identification as translation authority;
8. create/update `translations/en/02-sorgga-logaththil.md` with `translation_status: draft`, record the T1 English blob and exact title/lexicon decisions in tracker/plan/lexicon/review/handover;
9. **stop after Article 2 T1. Do not perform Article 2 T2 in the same activity.**