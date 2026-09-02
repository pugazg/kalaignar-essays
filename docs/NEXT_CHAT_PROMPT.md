# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`89331eb60620f50715cfc56a1fbe3dc742b24b51` — `Synchronize handover after Ina Muzhakkam Article 1 T2`

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
14. T2 English `translations/en/01-ina-muzhakkam.md`

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
- T3: **0 / 6**
- T4: **0 / 6**
- T5: **0 / 6**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T2 durable boundary

- Tamil title: `இன முழக்கம்`
- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `translations/en/01-ina-muzhakkam.md`
- working English title: **The Clarion Call of the Race** — T2 confirmed, not T5-frozen
- T1 English blob: `b3022e69387662584064d51133e24f4f97e976b2`
- T2 English blob: `6b37eec63209bff533666ce6ff8518c1cba6f733`
- `translation_status: fidelity-reviewed`
- source-page comments: **8 / 8 preserved in order**
- omitted Tamil sentences/clauses after T2: **0**
- added outside claims after T2: **0**
- blockers: **0**

### T2 fidelity corrections

1. `கல்லேற்றி` — **With stones loaded onto...** → **With a stone loaded onto...**.
2. frozen incomplete `அளித் ....` — removed silently completed **I gave** and retained an incomplete English **giv....** treatment.
3. `உங்களிடம் காட்டுவான்` — restored the explicit addressee with **show you**.
4. `புலவர்களுக் கெல்லாம்` — restored **all the poets**.
5. closing `நாட்டில்` — **through the country** → **in the country**.

### T2-confirmed Article-1 working decisions

- `இன முழக்கம்` → **The Clarion Call of the Race**; contextual closing occurrence → **the clarion call of the race**;
- `திராவிடன்` → **Dravidian**;
- `திராவிட இனம்` / `ஆரிய இனம்` → **Dravidian race / Aryan race**;
- `சுயமரியாதைக்காரன்` → **Self-Respecter**;
- incomplete `சுயமரியாதைக் ....` → **Self-Respect ....**, with no guessed completion;
- incomplete `அளித் ....` remains incomplete; do not silently supply the missing finite verb;
- repeated `தமிழன்` → **Tamilian**;
- `காமராஜ நாடார்` → **Kamaraj Nadar**;
- `கிராமணியார்` → **Gramaniyar**;
- frozen `கனக விசயர்` → **Kanaka Visayar**;
- `பாரிவள்ளல்` → **Vallal Pari**;
- `அருட்பெருஞ் சோதி` → **Arutperum Jothi**;
- source distinction `வடலூர் இராமலிங்கம்` / vocative `வடலூர் இராமலிங்கரே` remains **Vadalur Ramalingam / Vadalur Ramalingar**, not harmonised;
- scan-9→10 `அல்லலுற்` / `றோமே` remains traceable as `suf—` / `fer......`.

These decisions passed T2 fidelity review but remain subject to T3–T5; they are not release-frozen.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only the frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered `<!-- Tamil source: scan ... -->` comments;
- preserve quotation status and document material source punctuation anomalies;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- frozen source-sensitive forms such as `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives;
- Article 1 frozen incomplete `சுயமரியாதைக் ....` and `அளித் ....` must not be silently completed at later gates.

## EXACT NEXT ACTIVITY

**Article 1 `இன முழக்கம்` — T3 Kalaignar voice review only.**

1. fetch live `main`;
2. re-fetch frozen Tamil Article 1 and confirm blob `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`;
3. re-fetch T2 English Article 1 and confirm blob `6b37eec63209bff533666ce6ff8518c1cba6f733`;
4. compare the English against the frozen Tamil for directness, sarcasm, rhetorical questions, commands, deliberate repetition, vivid imagery, abrupt contrasts and polemical temperature;
5. preserve every T2 fidelity correction and all **8 / 8** ordered source-page comments;
6. do not silently complete `சுயமரியாதைக் ....` or `அளித் ....`, neutralise ideological/social labels or import outside identifications;
7. make voice/style corrections only where needed without changing T2 meaning/fidelity;
8. if PASS, set the appropriate T3 status and record the T3 English blob and exact findings/corrections in tracker/plan/lexicon/review/handover;
9. **stop after T3. Do not perform T4 in the same activity.**