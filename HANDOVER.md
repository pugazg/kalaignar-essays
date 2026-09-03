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
7. for `இன முழக்கம்` English work also read `TRANSLATION_PLAN.md`, `translations/en/README.md`, `translations/en/LEXICON.md`, `translations/en/TRANSLATION_REVIEW.md`, and the relevant frozen Tamil/English files.

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Live-main rule

- **Live `main` is authoritative.**
- Never reset, overwrite, repeat or reopen later durable work because an older prompt records an earlier checkpoint.
- Re-fetch target files before writes.
- Last confirmed live HEAD immediately before this handover synchronization: `4e6606df6b6e61a7b7b017bcca00a1ea84ba0b5f` — `Record Ina Muzhakkam Article 6 T5 source provenance`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ALL SIX ARTICLES T5 VERIFIED

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
- T1: **6 / 6 PASS**
- T2: **6 / 6 PASS**
- T3: **6 / 6 PASS**
- T4: **6 / 6 PASS**
- T5: **6 / 6 PASS**
- E6/E7: **NOT STARTED**
- English blockers: **0**

## Articles 1–6 — T5 VERIFIED / INDIVIDUALLY FROZEN

1. `இன முழக்கம்` — **The Clarion Call of the Race** — verified English `01d0d16c4f52cb134eba9fd35c06ad8376e256cb` — **8 / 8** source comments.
2. `சொர்க்க லோகத்தில்` — **In the Heavenly Realm** — verified English `bcd98fb1abf03e3109da1c4802570b77fddfe015` — **11 / 11** source comments.
3. `முரசறைவாய்` — **Beat the Drum** — verified English `c526195d7eb16b2dc446f8b3b15ae674c75548d5` — **5 / 5** source comments.
4. `பழிக்குப் பழி` — **Revenge for Revenge** — verified English `46627c3cecfd186e1735d8766ddda27414118e62` — **8 / 8** source comments.
5. `ஆரியம் பேசுகிறது` — **Aryanism Speaks** — verified English `4b1666afd885c3d8b800b08410a3dbfe498856bc` — **2 / 2** source comments.
6. `கவிதைகள்` — **Poems** — verified English `9e6f90b00bfa9a5059f1eef6875e8cef3c3652c3` — **9 / 9** source comments and **11 / 11** poem headings.

Do not reopen these articles without a genuine source-supported defect.

## Article 6 — `கவிதைகள்` — T1–T5 COMPLETE / VERIFIED

- Tamil blob: `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c`
- English file: `publications/ina-muzhakkam/translations/en/06-kavithaigal.md`
- verified English title: **Poems**
- T1 English blob: `fedc9d4dc196fc458b593cb60fa08f075c661f1e`
- T2 English blob: `9da9bcbd0e5fd31d1d4f5a9592d8b1ffdc059bbe`
- T3 English blob: `ca33119ed5b7d69a1fedb57349610d222d14ff71`
- T4 English blob: `099397023559005dfd73087e4e14bb94eef7f672`
- T5 verified English blob: `9e6f90b00bfa9a5059f1eef6875e8cef3c3652c3`
- `translation_status`: `verified`
- source comments: **9 / 9 preserved in order** for scans 41–49
- poem headings: **11 / 11 preserved**, including source punctuation
- Tamil source changes: **0**
- blockers: **0**

### Article 6 source-bearing decisions through T5

1. `கவிதைகள்` → **Poems**.
2. `நியாயத் திராசு!` → **Scale of Justice!**.
3. `ஏற்பரோ!` → **Will They Accept!**, preserving source `!` rather than editorially changing it to `?`.
4. `சைவரே! / சைவம்` → **Saivites! / Saivism**.
5. `வா!` → **Come!**.
6. `பொதுவுடைமையே!` → **Common Ownership!**.
7. `யோசித்துப் பார்!` → **Think It Over!**.
8. `மாணவர் எழுச்சி.` → **Student Uprising.**.
9. `வாளிங்கே!` → **Here Is the Sword!**.
10. `தோல்வி எப்பொழுது?` → **When Will There Be Defeat?**.
11. `இன்னுமா கூச்சல்?` → **Still This Clamour?**.
12. `வருணமா? மரணமா?` → **Varna or Death?**.
13. Source-bearing **Muthamizh**, **sotha / sothas**, **veli / velis**, **payasam**, **Varna**, **Eripaththar**, **Kotpuli**, **Kulachirai**, and the epic/source-name forms are retained without outside identification.
14. Source-sensitive `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` remain governed by frozen Tamil rather than scan alternatives.
15. The mismatched source quotation marks in `பொதுவுடைமையே!` remain deliberately unmatched in English.

### Article 6 T2 bilingual fidelity corrections

Five corrections:

1. restored the exact nine-line source structure in `Common Ownership!`;
2. removed unsupported `war` from `முழவு`, leaving **drum**;
3. restored `செந்தமிழ்க் காளைகள் / நந்தமிழ் நாட்டை` as **pure-Tamil bulls / our fair Tamil land**;
4. `கருத்தெரிய`: **truth** → **matter**;
5. `வண்டமிழ்`: **honeyed Tamil** → **rich Tamil**.

After correction: omitted poem lines **0**; added claims **0**; name/referent defects **0**; command/question/exclamation defects **0**; source-comment defects **0**; verse-lineation defects **0**.

### Article 6 T3 Kalaignar voice review

Five voice/style-only refinements:

1. **put medicine on a wound** → **dress a wound with medicine**;
2. **straightened herself once** → **drew herself upright**;
3. **urged on her pace** → **quickened her pace**;
4. **tell me where my warrior's milk went** → **tell me what became of my warrior's milk**;
5. **At the news that a mouse has come** → **At word that a mouse has come**.

Meaning, lineation and all T2 decisions remained intact.

### Article 6 T4 terminology / quotation / citation / source audit

Four corrections:

1. **Scales of Justice!** → **Scale of Justice!**;
2. **Will They Accept?** → **Will They Accept!** to preserve source punctuation;
3. removed unsupported object **us** from the Saivism-net image;
4. restored the source-aligned sequence/lineation in the closing half of **When Will There Be Defeat?**.

T4 then closed with terminology defects **0**; source-witness defects **0**; quotation/citation defects **0**; source-comment defects **0**; heading/lineation defects **0**; blockers **0**.

### Article 6 T5 final verification

T5 reread the entire T4 English against frozen Tamil and all T1–T4 decisions. Completeness, poem ordering, headings, lineation, meaning, commands/questions/exclamations, narrative/polemical force, terminology, names, source-cultural forms, quotation treatment and all **9 / 9** page comments pass. **No final body correction was required.** Article 6 is individually frozen.

## Translation non-regression

- Translate frozen Tamil; do not use OCR/raw transcription/scan-alternate readings.
- Preserve direct address, commands, questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained labels from outside knowledge.
- Preserve ordered source comments, page-boundary traces, quotation status and source punctuation irregularities.
- Scan-24/37 promotions, scan-40 front matter/review and scan-50 catalogue remain excluded.
- Known source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` must not be replaced with scan alternatives.
- Articles 1–6 are individually T5-frozen.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — E6 publication-wide English consistency review only.**

Required steps:

1. fetch live `main` first;
2. re-read `TRANSLATION_PLAN.md`, `translations/en/README.md`, `LEXICON.md`, `TRANSLATION_REVIEW.md`, and all six verified English units;
3. cross-check recurring names/epithets, Aryan/Dravidian vocabulary, source-specific transliterations, title style, quotation/source treatment, source-page comments, source-cultural terms and voice consistency;
4. preserve deliberately source-distinct forms and all individually verified article decisions unless a genuine cross-article defect is found;
5. record exact E6 findings across durable records;
6. **STOP AFTER E6. DO NOT PERFORM E7 RELEASE CLOSEOUT IN THE SAME ACTIVITY.**
