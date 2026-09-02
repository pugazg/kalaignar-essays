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
- Last confirmed live HEAD immediately before this handover synchronization: `f090711167b262d3d0c32da7abb022b7e8ca2aba` — `Advance root status through Ina Muzhakkam Article 1 T1`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ARTICLE 1 T1 PASS

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

Canonical P5 record: `publications/ina-muzhakkam/VISUAL_TEXT_FIDELITY_REVIEW.md`.

## Frozen Tamil translation authorities

1. `articles/01-ina-muzhakkam.md` — `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
2. `articles/02-sorgga-logaththil.md` — `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
3. `articles/03-murasaraivai.md` — `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`
4. `articles/04-pazhikku-pazhi.md` — `e140df7f6234e8362b9139793706533fec0c62d8`
5. `articles/05-aariyam-pesugirathu.md` — `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675`
6. `articles/06-kavithaigal.md` — `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c`

E0 re-fetch verification: **6 / 6 exact SHA matches / T0 PASS**.

## English gate status

- E0: **COMPLETE / PASS**
- T0: **6 / 6 PASS**
- T1: **1 / 6 PASS**
- T2: **0 / 6**
- T3: **0 / 6**
- T4: **0 / 6**
- T5: **0 / 6**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- English blockers: **0**

## Article 1 — `இன முழக்கம்` — T1 COMPLETE / PASS

- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `publications/ina-muzhakkam/translations/en/01-ina-muzhakkam.md`
- working English title: **The Clarion Call of the Race**
- T1 English blob: `b3022e69387662584064d51133e24f4f97e976b2`
- `translation_status`: `draft`
- source-page comments: **8 / 8 preserved in order** for scans 6–13
- known body omissions: **0**
- added outside claims: **0**
- Tamil source changes: **0**
- blockers: **0**

### Article 1 T1 working decisions

- `இன முழக்கம்` → **The Clarion Call of the Race**; contextual closing occurrence → **the clarion call of the race**.
- `திராவிடன்` → **Dravidian**.
- explicit `திராவிட இனம்` / `ஆரிய இனம்` → **Dravidian race / Aryan race**.
- `சுயமரியாதைக்காரன்` → **Self-Respecter**.
- frozen incomplete `சுயமரியாதைக் ....` → **Self-Respect ....**; do not guess the missing source word.
- repeated `தமிழன்` → **Tamilian**.
- `காமராஜ நாடார்` → **Kamaraj Nadar**.
- `கிராமணியார்` → **Gramaniyar**.
- frozen user-established `கனக விசயர்` → **Kanaka Visayar**, retained as a source-bearing compound label without outside identification.
- `பாரிவள்ளல்` → **Vallal Pari**; descriptive `கொடை வள்ளல்` → **great giver**.
- `அருட்பெருஞ் சோதி` → **Arutperum Jothi**.
- scan-9→10 frozen split `அல்லலுற்` / `றோமே` remains traceable in English as `suf—` / `fer......`.

These are T1 working decisions, not release-frozen choices. Audit them at T2–T5 rather than polishing them prematurely.

## Translation non-regression

- **Translate the language; do not neutralise the voice.**
- Translate frozen Tamil, not raw OCR/transcription or scan-alternate lexical readings.
- Preserve direct address, commands, rhetorical questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained source labels from outside knowledge.
- Preserve ordered source-page comments.
- Preserve quotation status and document material source punctuation anomalies rather than inventing Tamil punctuation.
- Scan-24 and scan-37 promotions, scan-40 `கவிதைகளைப் பற்றி` + `மதிப்புரை`, and scan-50 catalogue remain outside the six English bodies unless separately authorised.
- `கவிதைகள்` English must preserve frozen headings and source lineation.
- Frozen source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, and `கதறினாள்` must not be replaced with scan alternatives during translation.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — Article 1 `இன முழக்கம்` — T2 bilingual fidelity review only.**

Required steps:

1. fetch live `main` first;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 1 and confirm blob `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`;
4. re-fetch T1 English Article 1 and confirm blob `b3022e69387662584064d51133e24f4f97e976b2`;
5. compare every Tamil paragraph and clause against English for omission, addition, negative/comparison/logic shifts, names/referents, quotations and rhetorical repetition;
6. verify all **8 / 8** ordered source-page comments;
7. audit the working title and Article-1 T1 terminology against the frozen Tamil authority;
8. correct **fidelity defects only**; do not perform T3 stylistic/voice polishing;
9. if PASS, set `translation_status: fidelity-reviewed`, record the resulting T2 English blob and exact corrections/findings in tracker/plan/lexicon/review/handover;
10. **stop after T2. Do not perform T3 in the same activity.**
