# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

Last confirmed handover synchronization when this prompt was prepared:

`c147d7851795adfdc5ee38a98546aed46704a473` — `Synchronize handover after Ina Muzhakkam Article 2 T2`

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
14. T2 English `translations/en/02-sorgga-logaththil.md`

Article 1 `translations/en/01-ina-muzhakkam.md` is T5 verified and is an article-level non-regression reference. Do not reopen it during Article 2 work without a genuine source-supported defect.

## Frozen Tamil authority

The Tamil P5 layer is **COMPLETE / STRICT-REVIEWED / FROZEN**.

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
- T3: **1 / 6 PASS**
- T4: **1 / 6 PASS**
- T5: **1 / 6 PASS**
- E6/E7: **NOT STARTED**
- blockers: **0**

## Article 1 T5 verified boundary

- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- verified English title: **The Clarion Call of the Race**
- T5 verified English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status: verified`
- source-page comments: **8 / 8 preserved in order**

Article 1 is individually frozen. Preserve its verified terminology where the same Tamil form/function genuinely recurs, but do not mechanically overwrite distinct Article-2 source forms.

## Article 2 T2 durable boundary

- Tamil title: `சொர்க்க லோகத்தில்`
- frozen Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `translations/en/02-sorgga-logaththil.md`
- working English title: **In the Heavenly Realm** — T2 confirmed, not T5-frozen
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- T2 English blob: `b9ed854519806bbe65dc5b006183fb4675cb2c3a`
- `translation_status: fidelity-reviewed`
- source-page comments: **11 / 11 preserved in order** for scans 14–24
- T2 fidelity body corrections: **3**
- blockers: **0**

### Article 2 T2-confirmed decisions

1. `சொர்க்க லோகம்` / `சொர்க்க லோகத்தில்` → **heavenly realm / In the Heavenly Realm**.
2. `குடியேறியவர்` → **‘Immigrant’**.
3. `பூணூல்` → **sacred thread**; `பூனூல்கார அய்யர்` → **sacred-thread-wearing Ayyar**.
4. `ஆகஸ்ட் தியாகிகள்` / `ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle** without outside historical identification.
5. source-distinct `ஆச்சரியார்` / `ஆச்சாரியார்` → **Aachariyar / Aachaariyar**.
6. `திராவிடர்` / `ஆரியர்` → **Dravidians / an Aryan**.
7. closing `காமராஜர்` / `கிராமாணியார்` → **Kamarajar / Gramaaniyar**.
8. quoted closing `இனமுழக்கம்` → **The Clarion Call of the Race**.
9. `திருவிளையாடல் புராணம்` / `மாபாதகம் தீர்த்த படலம்` → ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
10. source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` remains **“Making one's mother into a great wife—is it not...?”** without guessed completion.
11. scan-14→15 `ஈடுபட்டிருந்` / `தார்கள்` remains `engag—` / `ed`; scan-19→20 `பெருமை` / `யடித்துக்` remains `boast—` / `ing`.
12. all **11 / 11** source comments, nested quotation scope and parenthetical stage directions remain intact.

### T2 fidelity corrections

1. `சுழல் வண்டுகளென` — **whirling beetles** → **whirling bees**.
2. Kotpuli Nayanar's killing sentence was restructured so the source's paddy-eating cause for mother/father/wife and milk-derived cause for the child are unambiguous; scan-18→19 remains after **`my father,`**.
3. Mother's closing `தம்பி` — **little brother** → **son**.

After correction: omitted clauses **0**, added claims **0**, unresolved names/referents **0**, negative/comparison/logical-connector defects **0**, source-comment defects **0**.

## Translation non-regression

> **Translate the language; do not neutralise the voice.**

- translate only frozen strict-reviewed Tamil assemblies;
- do not use OCR/raw transcription/scan-alternate lexical readings as translation authority;
- preserve direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, exclamations and loaded ideological/social labels;
- do not silently identify unexplained source labels from outside knowledge;
- retain ordered `<!-- Tamil source: scan ... -->` comments and documented page-boundary traces;
- preserve quotation status and source punctuation irregularities;
- scans 24 and 37 promotions, scan 40 front matter/review and scan 50 catalogue stay outside the six English bodies;
- Article 1 verified English decisions must not be reopened without a genuine source-supported defect;
- Article 2 T2 fidelity decisions must not be altered at T3 merely for stylistic preference.

## EXACT NEXT ACTIVITY

**Article 2 `சொர்க்க லோகத்தில்` — T3 Kalaignar voice review only.**

1. fetch live `main`;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 2 and confirm blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c`;
4. re-fetch T2 English Article 2 and confirm blob `b9ed854519806bbe65dc5b006183fb4675cb2c3a`;
5. review the complete English against Tamil for directness, satire, sexual mockery, graphic devotional claims, commands/questions, deliberate repetition, political ridicule, abrupt contrasts and closing polemical force;
6. preserve all three T2 fidelity corrections and every T2-confirmed source-bearing term unless a genuine voice-only refinement can be made without meaning drift;
7. preserve all **11 / 11** source comments, `engag— / ed`, `boast— / ing`, nested quotations, stage directions, `Aachariyar / Aachaariyar`, `Kamarajar / Gramaaniyar`, and the incomplete maternal-wife clause;
8. make **T3 voice/style corrections only**;
9. if PASS, set `translation_status: voice-reviewed`, record the T3 English blob and exact findings/corrections in tracker/plan/lexicon/review/handover;
10. **stop after Article 2 T3. Do not perform Article 2 T4 in the same activity.**