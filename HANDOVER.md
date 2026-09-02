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
6. read the active publication README / metadata / fidelity records;
7. for `இன முழக்கம்` English work also read `TRANSLATION_PLAN.md`, `translations/en/README.md`, `translations/en/LEXICON.md`, `translations/en/TRANSLATION_REVIEW.md`, and the relevant frozen Tamil/English article files.

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Live-main rule

- **Live `main` is authoritative.**
- Never reset, overwrite, repeat or reopen later durable work because an older prompt records an earlier checkpoint.
- Re-fetch target files before writes.
- Last confirmed live HEAD immediately before this handover synchronization: `6d26cb630c1e6d59bfdb7c917c31646ef030a99e` — `Record Ina Muzhakkam Article 3 T5 provenance in source metadata`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ARTICLE 3 T5 VERIFIED

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

The supplied transcription is the lexical baseline for the frozen Tamil layer; scans control structure/punctuation/quotation/page placement; scan/baseline lexical or numeric disagreements are documented, not silently substituted; English translates only frozen strict-reviewed Tamil assemblies.

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

- P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**
- P2 canonical pages: **50 / 50 COMPLETE**
- P3 assemblies: **6 / 6 COMPLETE**
- P5 page review: **50 / 50 PASS**
- P5 assembly recheck: **6 / 6 PASS**
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
- T1: **3 / 6 PASS**
- T2: **3 / 6 PASS**
- T3: **3 / 6 PASS**
- T4: **3 / 6 PASS**
- T5: **3 / 6 PASS**
- E6/E7: **NOT STARTED**
- English blockers: **0**

## Articles 1–3 — T5 VERIFIED / INDIVIDUALLY FROZEN

1. `இன முழக்கம்` — **The Clarion Call of the Race** — verified English `01d0d16c4f52cb134eba9fd35c06ad8376e256cb` — **8 / 8** source comments.
2. `சொர்க்க லோகத்தில்` — **In the Heavenly Realm** — verified English `bcd98fb1abf03e3109da1c4802570b77fddfe015` — **11 / 11** source comments.
3. `முரசறைவாய்` — **Beat the Drum** — verified English `c526195d7eb16b2dc446f8b3b15ae674c75548d5` — **5 / 5** source comments.

Do not reopen these articles without a genuine source-supported defect.

## Article 3 — `முரசறைவாய்` — T5 COMPLETE / VERIFIED

- Tamil blob: `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`
- English file: `publications/ina-muzhakkam/translations/en/03-murasaraivai.md`
- verified English title: **Beat the Drum**
- T1 English blob: `372a0572b95d6e0d02737f1b534f583b1dddf134`
- T2 English blob: `02d75107effa010ee61b1cc4d999fe4787c66f31`
- T3 English blob: `a4c2e482e4ba5a6a513cbed1b00879ba7fac90c2`
- T4 English blob: `969dc675dc1610d4a3d8e1fb2009d459dc6c41ef`
- T5 verified English blob: `c526195d7eb16b2dc446f8b3b15ae674c75548d5`
- `translation_status`: `verified`
- source comments: **5 / 5 preserved in order** for scans 25–29
- scan-25→26 trace: `ches— / t`
- scan-28→29 trace: `dwarf / fox`
- T2 fidelity corrections: **3 / 3 preserved**
- T3 voice/style corrections: **6 / 6 preserved**
- T4 terminology/quotation/citation/source body corrections: **0**
- T5 body corrections: **0**
- Tamil source changes: **0**
- blockers: **0**

### Article 3 source-bearing decisions through T5

1. `முரசறைவாய்` → **Beat the Drum**; `போர்முரசு / போர் முரசு` → **war drum**; `வெற்றி முரசு` → **victory drum**.
2. **Tamilian / Dravidian / Tamil race** remain stable where the same frozen forms/functions recur.
3. `கனகன் / விசயன்` → **Kanakan / Visayan**, source-distinct from Article-1 `Kanaka Visayar`.
4. `ஆரியர் / ஆரியம்` → **Aryans / an Aryan / Aryanism** contextually.
5. `வடவர்` → **Northerners**.
6. `உருட்டுச்சட்டிப் பொம்மைகள்` → **tumbler-dolls**.
7. quoted `பாராக்கு` → source-bearing **paarakku**, without outside identification.
8. `காமராஜர்கள் / சண்முகங்கள் / ஜீவாக்கள்` → **Kamarajars / Shanmugams / Jeevas**.
9. `அத்தான்` → **Aththaan**; `சோற்றுப் பொங்கல்` → **rice-pongal**.
10. frozen `இசயங்காட்டி` remains deliberately unnormalised as cautious **showing her *isayam***.
11. quoted `வாழ்விலோர் திருநாள்` → **A Festival Day in Life**; `பனிப்பார்வை` → **dewy glance**.
12. `வேட்டாயிற்றே` → **became a blast against a foreign king's fort**.
13. `குன்றெடுக்கும் நெடுந் தோளான்` → literal **long-shouldered hill-lifter**, with no outside mythic identification.
14. `சாணிப் பிள்ளையார் / சீனிப்பாயசம்` → **dung Pillaiyar / sugar payasam**.
15. all **5 / 5** source comments and both physical page-boundary traces remain explicit.

### Article 3 T2 fidelity corrections — preserved through T5

1. `துவண்டாயோ` → **Did you grow weary searching for me?**.
2. `கேட்டுப் பார்` → **Hear of your glories...**.
3. `கடல் கொள்ளாமல் ... வீரத்தை விலை கேட்கும் ஆரியம் கொண்டது ஏன்?` retains direct-address **you / you**; `வீரத்தை` remains inside **which asks a price for valour**.

### Article 3 T3 voice corrections — preserved through T5

1. repeated opening **resound / resounds** cadence;
2. reflowed beloved sentence while retaining **showing her *isayam*** and **the bull who comes**;
3. **turns away, his face hanging in defeat**;
4. **surged over their banks in Dravidian land**;
5. **nothing more than this rice-pongal**;
6. **Think, too, of the horror of this day!**.

### Article 3 T4 audit findings — preserved at T5

T4 found terminology defects **0**; source-witness defects **0**; quotation/citation defects **0**; source-comment/page-trace defects **0**; body corrections **0**.

### Article 3 T5 final verification

T5 reread the complete T4 English against frozen Tamil and all T1–T4 decisions. Completeness, meaning, directness, martial/polemical voice, terminology, source-witness distinctions, quotation/source treatment and page provenance all pass. All three T2 fidelity corrections, all six T3 voice corrections, the T4 zero-defect findings, all five comments, `ches— / t` and `dwarf / fox` remain intact. **No final body correction was required.** Article 3 is individually frozen.

## Translation non-regression

- Translate frozen Tamil; do not use OCR/raw transcription/scan-alternate readings.
- Preserve direct address, commands, questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained labels from outside knowledge.
- Preserve ordered source comments, page-boundary traces, quotation status and source punctuation irregularities.
- Scan-24/37 promotions, scan-40 front matter/review and scan-50 catalogue remain excluded.
- `கவிதைகள்` English must preserve frozen headings and lineation.
- Known source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` must not be replaced with scan alternatives.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — Article 4 `பழிக்குப் பழி` — T1 close English draft only.**

Required steps:

1. fetch live `main` first;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 4 and confirm blob `e140df7f6234e8362b9139793706533fec0c62d8`;
4. establish the English title from frozen Tamil only;
5. establish only terminology/source-bearing choices actually encountered, preserving Articles 1–3 verified decisions where the same form/function genuinely recurs but not mechanically harmonising distinct forms;
6. translate the complete frozen Article 4 paragraph by paragraph preserving direct address, commands, rhetorical questions, repetition, polemical force, quotation structure and every ordered source-page comment;
7. do not use OCR, raw supplied transcription, scan-alternate lexical readings, web text, later editions or outside identification as translation authority;
8. create/update `publications/ina-muzhakkam/translations/en/04-pazhikku-pazhi.md` with `translation_status: draft`;
9. record the T1 English blob, title and exact lexicon/source-bearing decisions across durable records;
10. **STOP AFTER ARTICLE 4 T1. DO NOT PERFORM ARTICLE 4 T2 IN THE SAME ACTIVITY.**