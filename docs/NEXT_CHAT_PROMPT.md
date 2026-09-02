# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`20b3f83bfccb27824311d5c8182c667318156429` — `Synchronize handover after Ina Muzhakkam Article 2 T1`

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
14. T1 English `translations/en/02-sorgga-logaththil.md`

Article 1 `translations/en/01-ina-muzhakkam.md` is T5 verified and is an article-level non-regression reference. Do not reopen it during Article 2 work without a genuine source-supported defect.

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
- T1: **2 / 6 PASS**
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
- T5 verified English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status: verified`
- source-page comments: **8 / 8 preserved in order**
- blockers: **0**

Article 1 is individually frozen at T5. Preserve its verified terminology and source-witness decisions where the same Tamil form/function genuinely recurs, but do not mechanically overwrite different Article-2 source forms.

## Article 2 T1 durable boundary

- Tamil title: `சொர்க்க லோகத்தில்`
- frozen Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `translations/en/02-sorgga-logaththil.md`
- working English title: **In the Heavenly Realm**
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- `translation_status: draft`
- source-page comments: **11 / 11 preserved in order** for scans 14–24
- blockers: **0**

### Article 2 T1 working decisions

1. `சொர்க்க லோகம்` / title `சொர்க்க லோகத்தில்` → **heavenly realm / In the Heavenly Realm**.
2. badge `குடியேறியவர்` → **‘Immigrant’**.
3. `பூணூல்` → **sacred thread**; `பூனூல்கார அய்யர்` → **sacred-thread-wearing Ayyar**.
4. `ஆகஸ்ட் தியாகிகள்` / `ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle**; do not import outside historical identification.
5. frozen source variants `ஆச்சரியார்` / `ஆச்சாரியார்` → **Aachariyar / Aachaariyar** at T1; do not silently harmonise them before audit.
6. `திராவிடர்` / `ஆரியர்` → **Dravidians / an Aryan**.
7. closing `காமராஜர்` / `கிராமாணியார்` → **Kamarajar / Gramaaniyar**, preserving Article-2 forms rather than importing Article-1 `Kamaraj Nadar / Gramaniyar`.
8. quoted closing `இனமுழக்கம்` → verified Article-1 title **The Clarion Call of the Race**.
9. `திருவிளையாடல் புராணம்` / `மாபாதகம் தீர்த்த படலம்` → source-bearing ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
10. frozen source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` → cautious T1 **“Making one's mother into a great wife—is it not...?”**; T2 must determine whether this is the best fidelity treatment without supplying unsupported Tamil.
11. scan-14→15 `ஈடுபட்டிருந்` / `தார்கள்` → traceable `engag— / ed`.
12. scan-19→20 `பெருமை` / `யடித்துக்` → traceable `boast— / ing`.
13. long outer quotations, nested speech and parenthetical stage directions remain structurally explicit.

These are **T1 working decisions only**. None is T2-confirmed yet.

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
- Article 1 verified English decisions must not be reopened without a genuine source-supported defect;
- Article 2 T1 choices remain provisional until T2–T5.

## EXACT NEXT ACTIVITY

**Article 2 `சொர்க்க லோகத்தில்` — T2 bilingual fidelity review only.**

1. fetch live `main`;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 2 and confirm blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c`;
4. re-fetch T1 English Article 2 and confirm blob `b02cc0e167e1f69aa324d5b761878f6be7134b5f`;
5. compare every Tamil paragraph and clause against English for omissions, added claims, names/referents, numbers, negatives, comparisons, logical connectors and deliberate repetition;
6. audit quotation scope, nested speech, parenthetical stage directions and all **11 / 11** ordered source-page comments;
7. explicitly audit `engag— / ed`, `boast— / ing`, source-distinct `Aachariyar / Aachaariyar`, `Kamarajar / Gramaaniyar`, `sacred thread`, `August martyrs / August struggle`, and the source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` treatment;
8. preserve Article-1 verified decisions and do not use outside identification or scan-alternate Tamil readings;
9. make **T2 fidelity corrections only**; if PASS, set `translation_status: fidelity-reviewed`, record the T2 English blob and exact findings/corrections in tracker/plan/lexicon/review/handover;
10. **stop after Article 2 T2. Do not perform Article 2 T3 in the same activity.**