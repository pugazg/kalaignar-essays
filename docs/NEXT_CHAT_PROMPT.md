# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`d7f01e87eb3adf1c45d77d940274dc9dccab9bd5` — `Synchronize handover after Ina Muzhakkam Article 2 T5`

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
13. frozen Tamil `publications/ina-muzhakkam/articles/03-murasaraivai.md`

Articles 1 and 2 are T5 verified and individually frozen. They are non-regression references only; do not reopen them during Article 3 work without a genuine source-supported defect.

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
- T1: **2 / 6 PASS**
- T2: **2 / 6 PASS**
- T3: **2 / 6 PASS**
- T4: **2 / 6 PASS**
- T5: **2 / 6 PASS**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T5 verified boundary

- Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English title: **The Clarion Call of the Race**
- verified English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status: verified`
- source comments: **8 / 8 preserved**

## Article 2 T5 verified boundary

- Tamil title: `சொர்க்க லோகத்தில்`
- frozen Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `translations/en/02-sorgga-logaththil.md`
- verified English title: **In the Heavenly Realm**
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- T2 English blob: `b9ed854519806bbe65dc5b006183fb4675cb2c3a`
- T3 English blob: `0d77a253523204f970b0cc89bfdc47f41ee793ef`
- T4 English blob: `641c65e20b8f2636dae420d874d31af626517afb`
- T5 verified English blob: `bcd98fb1abf03e3109da1c4802570b77fddfe015`
- `translation_status: verified`
- source comments: **11 / 11 preserved in order**
- T2 fidelity corrections: **3 / 3 preserved**
- T3 voice corrections: **5 / 5 preserved**
- T4 source/quotation corrections: **2 / 2 preserved**
- T5 body corrections: **0**
- blockers: **0**

### Article 2 verified source-bearing non-regression

- **In the Heavenly Realm / heavenly realm** remains distinct from `Sivalokam`, `Kailasa`, `realm of moksha` and other source-specific afterlife/place terms.
- `குடியேறியவர்` → **‘Immigrant’**.
- `பூணூல் / பூனூல்கார அய்யர்` → **sacred thread / sacred-thread-wearing Ayyar**.
- `ஆகஸ்ட் தியாகிகள் / ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle** without outside identification.
- `ஆச்சரியார் / ஆச்சாரியார்` → **Aachariyar / Aachaariyar**.
- `திராவிடர் / ஆரியர்` → **Dravidians / an Aryan**.
- `காமராஜர் / கிராமாணியார்` → **Kamarajar / Gramaaniyar**.
- `காரைக்கால் அம்மையார் / காரைக்காலம்மை` → **Karaikkal Ammaiyar / Karaikkal Ammai**.
- `திருவிளையாடல் புராணம் / மாபாதகம் தீர்த்த படலம்` → ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
- incomplete `மாதாவை மகா மனைவியாக்குவது மல்லவா` remains **“Making one's mother into a great wife—is it not...?”** without guessed completion.
- all 11 source comments, nested quotations, stage directions, `engag— / ed`, scan-18→19 after **my father,**, and `boast— / ing` remain frozen.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered source comments and documented page-boundary traces;
- preserve quotation status and source punctuation irregularities;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- Article 1 and Article 2 verified English decisions must not be reopened without genuine source support;
- when the same Tamil form/function genuinely recurs in Article 3, preserve verified terminology; do not mechanically overwrite distinct Article-3 source forms.

## EXACT NEXT ACTIVITY

**Article 3 `முரசறைவாய்` — T1 close draft only.**

1. fetch live `main`;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 3 and confirm blob `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`;
4. establish the English title from frozen Tamil only;
5. establish only Article-3 terminology/source-bearing choices actually encountered; preserve Article-1/2 verified decisions only where the same Tamil form/function genuinely recurs;
6. translate the complete frozen Article-3 Tamil paragraph by paragraph, preserving direct address, commands, rhetorical questions, repetition, polemical force, quotation structure and every ordered source-page comment;
7. do not use OCR, raw supplied transcription, scan-alternate lexical readings, later editions, web text or outside identification as translation authority;
8. create/update `publications/ina-muzhakkam/translations/en/03-murasaraivai.md` with `translation_status: draft`;
9. record the T1 English blob, English title and exact terminology/source-bearing decisions in tracker/plan/lexicon/review/handover;
10. **stop after Article 3 T1. Do not perform Article 3 T2 in the same activity.**