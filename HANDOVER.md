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
- Last confirmed live HEAD immediately before this handover synchronization: `ad2014b1396f1638bec8b652f225364f60d9b069` — `Record Ina Muzhakkam Article 2 T5 provenance`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ARTICLES 1–2 T5 VERIFIED

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

Therefore the supplied transcription is the lexical baseline for the frozen Tamil layer; scans control structure/punctuation/quotation/page placement; scan/baseline lexical or numeric disagreements are documented, not silently substituted; English translates only the frozen strict-reviewed Tamil assemblies.

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
- T1: **2 / 6 PASS**
- T2: **2 / 6 PASS**
- T3: **2 / 6 PASS**
- T4: **2 / 6 PASS**
- T5: **2 / 6 PASS**
- E6/E7: **NOT STARTED**
- English blockers: **0**

## Article 1 — `இன முழக்கம்` — T5 VERIFIED

- Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- English file: `publications/ina-muzhakkam/translations/en/01-ina-muzhakkam.md`
- verified title: **The Clarion Call of the Race**
- T5 English blob: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`
- `translation_status`: `verified`
- source comments: **8 / 8 preserved**
- blockers: **0**

Article 1 is individually frozen. Its verified terminology, incomplete `Self-Respect ....` / `giv....`, `Vadalur Ramalingam / Vadalur Ramalingar`, `Kanaka Visayar`, scan-9→10 `suf— / fer......`, and Vallal Pari unmatched opening quotation are non-regression requirements.

## Article 2 — `சொர்க்க லோகத்தில்` — T5 COMPLETE / VERIFIED

- Tamil blob: `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
- English file: `publications/ina-muzhakkam/translations/en/02-sorgga-logaththil.md`
- verified title: **In the Heavenly Realm**
- T1 English blob: `b02cc0e167e1f69aa324d5b761878f6be7134b5f`
- T2 English blob: `b9ed854519806bbe65dc5b006183fb4675cb2c3a`
- T3 English blob: `0d77a253523204f970b0cc89bfdc47f41ee793ef`
- T4 English blob: `641c65e20b8f2636dae420d874d31af626517afb`
- T5 verified English blob: `bcd98fb1abf03e3109da1c4802570b77fddfe015`
- `translation_status`: `verified`
- source comments: **11 / 11 preserved in order** for scans 14–24
- T2 fidelity body corrections: **3**
- T3 voice/style body corrections: **5**
- T4 source/quotation body corrections: **2**
- T5 body corrections: **0**
- Tamil source changes: **0**
- blockers: **0**

### Article 2 T5 verified source-bearing decisions

1. `சொர்க்க லோகம் / சொர்க்க லோகத்தில்` → **heavenly realm / In the Heavenly Realm**.
2. `குடியேறியவர்` → **‘Immigrant’**.
3. `பூணூல் / பூனூல்கார அய்யர்` → **sacred thread / sacred-thread-wearing Ayyar**.
4. `ஆகஸ்ட் தியாகிகள் / ஆகஸ்ட் போராட்டம்` → **August martyrs / August struggle**, no outside identification.
5. `ஆச்சரியார் / ஆச்சாரியார்` → **Aachariyar / Aachaariyar**, source-distinct.
6. `திராவிடர் / ஆரியர்` → **Dravidians / an Aryan**.
7. `காமராஜர் / கிராமாணியார்` → **Kamarajar / Gramaaniyar**, source-distinct.
8. closing `இனமுழக்கம்` → **The Clarion Call of the Race**.
9. `திருவிளையாடல் புராணம் / மாபாதகம் தீர்த்த படலம்` → ***Thiruvilaiyadal Puranam*** / **Mahapathagam Theertha Padalam**.
10. `காரைக்கால் அம்மையார் / காரைக்காலம்மை` → **Karaikkal Ammaiyar / Karaikkal Ammai**, source-distinct.
11. source-irregular `மாதாவை மகா மனைவியாக்குவது மல்லவா` remains **“Making one's mother into a great wife—is it not...?”** without guessed completion.
12. scan-14→15 remains `engag— / ed`; scan-18→19 remains after **my father,**; scan-19→20 remains `boast— / ing`.
13. all **11 / 11** source comments, nested quotations and parenthetical stage directions remain intact.

### Article 2 accumulated corrections — verified at T5

T2 fidelity corrections:

1. `சுழல் வண்டுகளென` → **whirling bees**.
2. Kotpuli Nayanar's adult paddy-eating cause and child's milk-derived cause remain distinct, with scan-18→19 after **my father,**.
3. Mother's `தம்பி` → **son**.

T3 voice corrections:

1. **Their talk did not become a great debate.** → **It was no great debate.**
2. **The fruit of that is this heavenly realm for me.** → **This heavenly realm is the fruit of that.**
3. **There is no difference between you and the August martyrs, fellows!** → **You fellows are no different from the August martyrs!**
4. stiff **What is the reason that...** → direct **How is it that...**.
5. **I rose, declaring loudly...** → active **I rose and declared loudly...**.

T4 source/quotation corrections:

1. scan-22 `காரைக்காலம்மை` → source-distinct **Karaikkal Ammai**.
2. removed English-only inner quotation marks around **Mahapathagam Theertha Padalam**.

### Article 2 T5 final findings

T5 reread frozen Tamil blob `8fea1497ed2dcbdb395418590c1b9875e6066b8c` against T4 English blob `641c65e20b8f2636dae420d874d31af626517afb` and confirmed:

- omitted clauses: **0**;
- added claims: **0**;
- remaining terminology/source-witness defects: **0**;
- quotation/stage-direction defects: **0**;
- source-comment/page-trace defects: **0**;
- T5 body corrections: **0**;
- all T2/T3/T4 corrections remain intact.

Article 2 is now individually frozen at T5. Reopen only for a genuine source-supported defect.

## Translation non-regression

- Translate frozen Tamil; do not use OCR/raw transcription/scan-alternate readings.
- Preserve direct address, commands, questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained labels from outside knowledge.
- Preserve ordered source comments, page-boundary traces, quotation status and source punctuation irregularities.
- Scan-24/37 promotions, scan-40 front matter/review and scan-50 catalogue remain excluded.
- `கவிதைகள்` English must preserve frozen headings and lineation.
- Known source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` must not be replaced with scan alternatives.
- Article 1 and Article 2 verified decisions must not be reopened without genuine source support.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — Article 3 `முரசறைவாய்` — T1 close draft only.**

Required steps:

1. fetch live `main` first;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 3 and confirm blob `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`;
4. establish the English title from the frozen Tamil only;
5. establish only Article-3 terminology/source-bearing choices actually encountered, preserving Article-1/2 verified decisions where the same Tamil form/function genuinely recurs but not mechanically harmonising distinct forms;
6. translate the complete frozen Article-3 Tamil paragraph by paragraph, preserving direct address, commands, rhetorical questions, repetition, polemical force, quotation structure and every ordered source-page comment;
7. do not use OCR, raw supplied transcription, scan-alternate lexical readings, web text, later editions or outside identification as translation authority;
8. create/update `publications/ina-muzhakkam/translations/en/03-murasaraivai.md` with `translation_status: draft`;
9. record the T1 English blob, title and exact lexicon/source-bearing decisions in tracker/plan/lexicon/review/handover;
10. **stop after Article 3 T1. Do not perform Article 3 T2 in the same activity.**