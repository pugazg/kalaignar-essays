# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`0bdd6d9e4f6146a5c7d10e5396dbe1507d32335b` — `Synchronize handover after Ina Muzhakkam E0`

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
13. all six frozen Tamil assemblies; for the next activity especially Article 1.

## Frozen Tamil authority

The completed P5 Tamil layer is **COMPLETE / STRICT-REVIEWED / FROZEN**. Do not reopen it for translation convenience.

Frozen Tamil authorities:

1. `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010` — `இன முழக்கம்`
2. `8fea1497ed2dcbdb395418590c1b9875e6066b8c` — `சொர்க்க லோகத்தில்`
3. `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8` — `முரசறைவாய்`
4. `e140df7f6234e8362b9139793706533fec0c62d8` — `பழிக்குப் பழி`
5. `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675` — `ஆரியம் பேசுகிறது`
6. `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c` — `கவிதைகள்`

E0 re-fetched all six: **6 / 6 exact SHA matches / T0 PASS**.

## Current durable state

- Tamil P0–P5: **COMPLETE / FROZEN**
- E0 translation planning/setup: **COMPLETE / PASS**
- T0: **6 / 6 PASS**
- T1: **0 / 6**
- T2: **0 / 6**
- T3: **0 / 6**
- T4: **0 / 6**
- T5: **0 / 6**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- blockers: **0**

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only the frozen strict-reviewed Tamil assemblies, not OCR/raw transcription/scan-alternate lexical readings;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained epithets or labels from outside knowledge;
- retain ordered `<!-- Tamil source: scan ... -->` comments;
- preserve quotation status and document material source punctuation anomalies rather than inventing missing Tamil punctuation;
- scan-24 and scan-37 promotions, scan-40 `கவிதைகளைப் பற்றி` + `மதிப்புரை`, and scan-50 catalogue are outside the six English bodies unless separately authorised;
- `கவிதைகள்` translation must preserve frozen poem headings and lineation;
- source-sensitive frozen forms such as `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives during translation;
- English titles are established article by article at T1, not pre-frozen globally at E0.

## EXACT NEXT ACTIVITY

**Article 1 `இன முழக்கம்` — T1 close English draft only.**

1. fetch live `main`;
2. re-fetch `articles/01-ina-muzhakkam.md` and confirm blob `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`;
3. establish the working English title from the frozen Tamil title and record it in `LEXICON.md` and `TRANSLATION_REVIEW.md`;
4. establish only Article-1 terminology actually encountered; do not pre-freeze later-article choices;
5. translate the entire frozen Article 1 paragraph by paragraph, preserving quotation structure, questions, exclamations, repetition and rhetoric;
6. retain every ordered source-page comment in English form;
7. create `translations/en/01-ina-muzhakkam.md` with `translation_status: draft` and the frozen Tamil blob SHA;
8. record the T1 English blob and decisions in tracker/plan/lexicon/review/handover;
9. **stop after T1. Do not perform T2 in the same activity.**
