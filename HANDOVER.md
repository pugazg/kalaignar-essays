# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, transcription, fidelity, translation or release activity.**

## Mandatory startup

Before changing anything:

1. read `ESSAY_PROCESSING_GUIDE.md` completely;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely when English is in scope;
3. read `docs/FUTURE_WORK_GUIDELINES.md` completely;
4. fetch live `main` and read this `HANDOVER.md` completely;
5. read `docs/NEXT_CHAT_PROMPT.md` only as a convenience summary;
6. read the active publication README / metadata / indexes / audit / fidelity records;
7. for active `இன முழக்கம்` English work, also read `TRANSLATION_PLAN.md`, `translations/en/README.md`, `translations/en/LEXICON.md`, `translations/en/TRANSLATION_REVIEW.md`, and the relevant frozen Tamil/English article files.

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Live-main rule

- **Live `main` is authoritative.**
- Never reset, overwrite, repeat or reopen later durable work because an older prompt records an earlier checkpoint.
- Re-fetch target files before writes.
- Last confirmed live HEAD immediately before this handover synchronization: `d4d9178afa07efde375ba268aee9cc0d341d014f` — `Record Ina Muzhakkam Article 2 T2 provenance`.

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

- Tamil strict fidelity: **83 / 83 PASS**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

- Tamil P5: **17 / 17 PASS**
- frozen Tamil authority: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- verified English blob: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 3 — உணர்ச்சிமாலை — RELEASE COMPLETE / FROZEN

- Tamil P5: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- English T0–T5: **10 / 10 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 4 — திராவிட சம்பத்து — RELEASE COMPLETE / FROZEN

Workspace: `publications/thiraavida-sampaththu/`

- Tamil P0–P5: **COMPLETE / FROZEN**
- English T0–T5: **2 / 2 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Released English authorities:

1. **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ARTICLE 2 T2 PASS

Workspace: `publications/ina-muzhakkam/`  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## Source identity

- title: **இன முழக்கம்**
- title-page author: **கலைஞர் கருணாநிதி**
- first edition: **செப்டம்பர் 1951**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- price: **அணா 0-8-0**
- printer: **கே. ஜி. பிரஸ், சென்னை—1**
- physical scans: **50**
- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- source PDF committed: **No**

## Publication-specific authority — USER ESTABLISHED

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Therefore:

- supplied transcription = lexical baseline for the completed Tamil archival layer;
- scan = structure, punctuation, quotation scope, page/paragraph placement, headings, poetry lineation and physical-copy evidence;
- scan/baseline lexical or numeric disagreements are documented, not silently substituted;
- stamps, handwriting, show-through, damage and marginal marks remain outside printed body text;
- English translation uses only the frozen strict-reviewed Tamil assemblies.

## Publication boundaries

- scans 1–5 — front matter / `பதிப்புரை`
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

## Tamil gate status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2 canonical page records: **50 / 50 COMPLETE**
- P3 assemblies: **6 / 6 COMPLETE**
- P4 source/completeness audit: **PASS**
- P5 page-level strict review: **50 / 50 PASS**
- P5 final assembly recheck: **6 / 6 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- Tamil blockers: **0**

## Frozen Tamil translation authorities

1. `articles/01-ina-muzhakkam.md` — `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
2. `articles/02-sorgga-logaththil.md` — `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
3. `articles/03-murasaraivai.md` — `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`
4. `articles/04-pazhikku-pazhi.md` — `e140df7f6234e8362b9139793706533fec0c62d8`
5. `articles/05-aariyam-pesugirathu.md` — `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675`
6. `articles/06-kavithaigal.md` — `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c`

## English gate status

- E0: **COMPLETE / PASS**
- T0: **6 / 6 PASS**
- T1: **2 / 6 PASS**
- T2: **2 / 6 PASS**
- T3: **1 / 6 PASS**
- T4: **1 / 6 PASS**
- T5: **1 / 6 PASS**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- English blockers: **0**

## Article 1 — `இன முழக்கம்` — T5 COMPLETE / VERIFIED

- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `publications/ina-muzhakkam/translations/en/01-ina-muzhakkam.md`
- verified English title: **The Clarion Call of the Race**
- T5 verified English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status`: `verified`
- source-page comments: **8 / 8 preserved in order**
- blockers: **0**

Article 1 is individually frozen at T5. Reopen only for a genuine source-supported defect.

## Article 2 — `சொர்க்க லோகத்தில்` — T2 COMPLETE / PASS

- frozen Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `publications/ina-muzhakkam/translations/en/02-sorgga-logaththil.md`
- working English title: **In the Heavenly Realm** — T2 confirmed, not T5-frozen
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- T2 English blob: `b9ed854519806bbe65dc5b006183fb4675cb2c3a`
- `translation_status`: `fidelity-reviewed`
- source-page comments: **11 / 11 preserved in order** for scans 14–24
- T2 fidelity body corrections: **3**
- Tamil source changes: **0**
- blockers: **0**

### Article 2 T1 working decisions retained at T2

- `சொர்க்க லோகம்` / `சொர்க்க லோகத்தில்` → **heavenly realm / In the Heavenly Realm**.
- badge `குடியேறியவர்` → **‘Immigrant’**.
- `பூணூல்` → **sacred thread**; `பூனூல்கார அய்யர்` → **sacred-thread-wearing Ayyar**.
- `ஆகஸ்ட் தியாகிகள்` / `ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle** without outside historical identification.
- frozen `ஆச்சரியார்` / later `ஆச்சாரியார்` → **Aachariyar / Aachaariyar**, deliberately source-distinct.
- `திராவிடர்` / `ஆரியர்` → **Dravidians / an Aryan**.
- closing `காமராஜர்` / `கிராமாணியார்` → **Kamarajar / Gramaaniyar**, preserving Article-2 forms.
- quoted closing `இனமுழக்கம்` → **The Clarion Call of the Race**.
- `திருவிளையாடல் புராணம்` / `மாபாதகம் தீர்த்த படலம்` → ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
- source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` → **“Making one's mother into a great wife—is it not...?”** without a guessed completion.
- scan-14→15 `ஈடுபட்டிருந்` / `தார்கள்` → `engag—` / `ed`.
- scan-19→20 `பெருமை` / `யடித்துக்` → `boast—` / `ing`.

### Article 2 T2 fidelity corrections

1. `சுழல் வண்டுகளென` — **whirling beetles** → **whirling bees**.
2. Kotpuli Nayanar's killing sentence was restructured so the paddy-eating cause for mother/father/wife and the child's milk-derived cause are unambiguous; the scan-18→19 boundary remains immediately after **`my father,`**.
3. Mother's closing `தம்பி` — literal **little brother** → contextual **son**.

### Article 2 T2 findings

- omitted clauses after correction: **0**
- added claims: **0**
- unresolved names/referents defects: **0**
- negative/comparison/logical-connector defects: **0**
- source-page comment defects: **0**
- all **11 / 11** ordered source comments remain scans 14–24
- quotation scope / nested speech / stage directions: preserved
- source-distinct `Aachariyar / Aachaariyar` and `Kamarajar / Gramaaniyar`: preserved
- source-irregular maternal-wife clause: retained incomplete without outside repair

## Translation non-regression

- **Translate the language; do not neutralise the voice.**
- Translate frozen Tamil, not raw OCR/transcription or scan-alternate lexical readings.
- Preserve direct address, commands, rhetorical questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained source labels from outside knowledge.
- Preserve ordered source-page comments and documented page-boundary traces.
- Preserve quotation status and source punctuation irregularities rather than inventing Tamil punctuation.
- Scan-24 and scan-37 promotions, scan-40 `கவிதைகளைப் பற்றி` + `மதிப்புரை`, and scan-50 catalogue remain outside the six English bodies unless separately authorised.
- `கவிதைகள்` English must preserve frozen headings and source lineation.
- Frozen source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives.
- Article 1 verified decisions must not be reopened without a genuine source-supported defect.
- Article 2 T2 decisions remain subject to T3–T5 but must not be altered at T3 for fidelity reasons already settled.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — Article 2 `சொர்க்க லோகத்தில்` — T3 Kalaignar voice review only.**

Required steps:

1. fetch live `main` first;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 2 and confirm blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c`;
4. re-fetch T2 English Article 2 and confirm blob `b9ed854519806bbe65dc5b006183fb4675cb2c3a`;
5. review the complete English article against Tamil for directness, satire, sexual mockery, graphic devotional claims, commands/questions, deliberate repetition, political ridicule, abrupt contrasts and closing polemical force;
6. preserve all three T2 fidelity corrections and all T2-confirmed terminology/source-witness decisions unless a genuine voice-only refinement can be made without meaning drift;
7. preserve all **11 / 11** source comments, `engag— / ed`, `boast— / ing`, nested quotation scope, stage directions, `Aachariyar / Aachaariyar`, `Kamarajar / Gramaaniyar`, and the incomplete maternal-wife clause;
8. make **T3 voice/style corrections only**;
9. if PASS, set `translation_status: voice-reviewed`, record the T3 English blob and exact findings/corrections in tracker/plan/lexicon/review/handover;
10. **stop after Article 2 T3. Do not perform Article 2 T4 in the same activity.**