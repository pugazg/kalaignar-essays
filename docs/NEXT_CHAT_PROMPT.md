# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`efe0e859f5a41e943cc52742c32a5632d87c4a55` — `Synchronize handover after Ina Muzhakkam Article 2 T4`

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
14. T4 English `translations/en/02-sorgga-logaththil.md`

Article 1 `translations/en/01-ina-muzhakkam.md` is T5 verified and is an article-level non-regression reference. Do not reopen it during Article 2 work without a genuine source-supported defect.

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
- T5: **1 / 6 PASS**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T5 verified boundary

- Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English title: **The Clarion Call of the Race**
- English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status: verified`
- source comments: **8 / 8 preserved**

Preserve Article-1 verified terminology and source-witness decisions where the same Tamil form/function genuinely recurs; do not mechanically overwrite distinct Article-2 source forms.

## Article 2 T4 durable boundary

- Tamil title: `சொர்க்க லோகத்தில்`
- frozen Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `translations/en/02-sorgga-logaththil.md`
- working English title: **In the Heavenly Realm** — T4 confirmed, not T5-frozen
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- T2 English blob: `b9ed854519806bbe65dc5b006183fb4675cb2c3a`
- T3 English blob: `0d77a253523204f970b0cc89bfdc47f41ee793ef`
- T4 English blob: `641c65e20b8f2636dae420d874d31af626517afb`
- `translation_status: voice-reviewed`
- source comments: **11 / 11 preserved in order**
- T2 fidelity corrections preserved: **3 / 3**
- T3 voice/style corrections preserved: **5 / 5**
- T4 source/quotation body corrections: **2**
- blockers: **0**

### Article 2 source-bearing decisions through T4

1. `சொர்க்க லோகம் / சொர்க்க லோகத்தில்` → **heavenly realm / In the Heavenly Realm**.
2. `குடியேறியவர்` → **‘Immigrant’**.
3. `பூணூல் / பூனூல்கார அய்யர்` → **sacred thread / sacred-thread-wearing Ayyar**.
4. `ஆகஸ்ட் தியாகிகள் / ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle**, no outside identification.
5. `ஆச்சரியார் / ஆச்சாரியார்` → **Aachariyar / Aachaariyar**, source-distinct.
6. `திராவிடர் / ஆரியர்` → **Dravidians / an Aryan**.
7. closing `காமராஜர் / கிராமாணியார்` → **Kamarajar / Gramaaniyar**.
8. quoted closing `இனமுழக்கம்` → **The Clarion Call of the Race**.
9. `திருவிளையாடல் புராணம் / மாபாதகம் தீர்த்த படலம்` → ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
10. `காரைக்கால் அம்மையார் / காரைக்காலம்மை` → **Karaikkal Ammaiyar / Karaikkal Ammai**, preserving the scan-22 source-form distinction.
11. source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` remains **“Making one's mother into a great wife—is it not...?”** without guessed completion.
12. scan-14→15 `ஈடுபட்டிருந் / தார்கள்` → `engag— / ed`.
13. scan-19→20 `பெருமை / யடித்துக்` → `boast— / ing`.
14. all 11 source comments, nested quotations and parenthetical stage directions remain intact.

### Article 2 T2 fidelity corrections — preserve

1. `சுழல் வண்டுகளென` → **whirling bees**.
2. Kotpuli Nayanar's adult paddy-eating cause and child's milk-derived cause remain grammatically distinct, with scan-18→19 after **my father,**.
3. Mother's `தம்பி` → **son**.

### Article 2 T3 voice corrections — preserve

1. **Their talk did not become a great debate.** → **It was no great debate.**
2. **The fruit of that is this heavenly realm for me.** → **This heavenly realm is the fruit of that.**
3. **There is no difference between you and the August martyrs, fellows!** → **You fellows are no different from the August martyrs!**
4. **What is the reason that...** → direct **How is it that...**.
5. **I rose, declaring loudly...** → active **I rose and declared loudly...**.

### Article 2 T4 source / quotation corrections — preserve

1. scan-22 `காரைக்காலம்மை`: harmonised **Karaikkal Ammaiyar** → source-distinct **Karaikkal Ammai**.
2. `மாபாதகம் தீர்த்த படலம்`: removed English-only nested quotation marks around **Mahapathagam Theertha Padalam** because the frozen Tamil does not mark the chapter label as an inner quotation.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered source comments and documented page-boundary traces;
- preserve quotation status and source punctuation irregularities;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- Article 1 verified English decisions must not be reopened without genuine source support;
- Article 2 T2–T4 decisions are non-regression inputs to T5 and must not be casually rewritten.

## EXACT NEXT ACTIVITY

**Article 2 `சொர்க்க லோகத்தில்` — T5 final article verification only.**

1. fetch live `main`;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 2 and confirm blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c`;
4. re-fetch T4 English Article 2 and confirm blob `641c65e20b8f2636dae420d874d31af626517afb`;
5. reread the complete English against frozen Tamil and every T1–T4 decision for final completeness, meaning, directness, satire, terminology, source-witness distinctions, quotation/citation structure, stage directions and source-page trace;
6. verify all three T2 fidelity corrections, all five T3 voice corrections and both T4 source/quotation corrections remain intact;
7. verify all **11 / 11** source comments, `engag— / ed`, scan-18→19 after **my father,**, and `boast— / ing`;
8. make a final correction only for a genuine remaining defect;
9. if PASS, set `translation_status: verified`, record the T5 verified English blob and freeze Article 2 at article level;
10. **stop after Article 2 T5. Do not begin Article 3 T1 in the same activity.**