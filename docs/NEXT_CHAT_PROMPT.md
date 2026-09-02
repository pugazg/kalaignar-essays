# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`bbbbc971fce73fea8c740c3e8c5abd06db759c2d` — `Synchronize handover after Ina Muzhakkam Article 1 T1`

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
13. frozen Tamil `articles/01-ina-muzhakkam.md`
14. T1 English `translations/en/01-ina-muzhakkam.md`

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
- T2: **0 / 6**
- T3: **0 / 6**
- T4: **0 / 6**
- T5: **0 / 6**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T1 durable boundary

- Tamil title: `இன முழக்கம்`
- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `translations/en/01-ina-muzhakkam.md`
- working English title: **The Clarion Call of the Race**
- T1 English blob: `b3022e69387662584064d51133e24f4f97e976b2`
- `translation_status: draft`
- source-page comments: **8 / 8 preserved in order**
- blockers: **0**

Working T1 decisions include:

- `இன முழக்கம்` → **The Clarion Call of the Race**;
- `திராவிடன்` → **Dravidian**;
- `திராவிட இனம்` / `ஆரிய இனம்` → **Dravidian race / Aryan race**;
- `சுயமரியாதைக்காரன்` → **Self-Respecter**;
- incomplete `சுயமரியாதைக் ....` → **Self-Respect ....**, with no guessed completion;
- repeated `தமிழன்` → **Tamilian**;
- `கிராமணியார்` → **Gramaniyar**;
- frozen `கனக விசயர்` → **Kanaka Visayar**;
- `பாரிவள்ளல்` → **Vallal Pari**;
- `அருட்பெருஞ் சோதி` → **Arutperum Jothi**.

These are T1 working choices and must be tested at T2 rather than treated as release-frozen.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only the frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered `<!-- Tamil source: scan ... -->` comments;
- preserve quotation status and document material source punctuation anomalies;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- frozen source-sensitive forms such as `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives.

## EXACT NEXT ACTIVITY

**Article 1 `இன முழக்கம்` — T2 bilingual fidelity review only.**

1. fetch live `main`;
2. re-fetch frozen Tamil Article 1 and confirm blob `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`;
3. re-fetch T1 English Article 1 and confirm blob `b3022e69387662584064d51133e24f4f97e976b2`;
4. compare every Tamil paragraph and clause against the T1 English draft;
5. check for omitted clauses, added claims, incorrect negatives/comparisons/connectors, names/referents, quotation completeness and deliberate repetition;
6. verify all **8 / 8** source-page comments remain present and ordered;
7. audit the working title and Article-1 lexicon decisions against the frozen Tamil authority;
8. correct **fidelity defects only**; do not perform T3 voice/style polishing;
9. if PASS, set `translation_status: fidelity-reviewed`, record the T2 English blob and exact corrections/findings in tracker/plan/lexicon/review/handover;
10. **stop after T2. Do not perform T3 in the same activity.**
