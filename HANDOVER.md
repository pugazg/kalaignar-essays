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
- Last confirmed live HEAD immediately before this handover synchronization: `b84e3e752c75b5a529b351712928906221847368` — `Advance Ina Muzhakkam Article 5 lexicon through T3`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / ARTICLE 5 T3 PASS

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
- T1: **5 / 6 PASS**
- T2: **5 / 6 PASS**
- T3: **5 / 6 PASS**
- T4: **4 / 6 PASS**
- T5: **4 / 6 PASS**
- E6/E7: **NOT STARTED**
- English blockers: **0**

## Articles 1–4 — T5 VERIFIED / INDIVIDUALLY FROZEN

1. `இன முழக்கம்` — **The Clarion Call of the Race** — verified English `01d0d16c4f52cb134eba9fd35c06ad8376e256cb` — **8 / 8** source comments.
2. `சொர்க்க லோகத்தில்` — **In the Heavenly Realm** — verified English `bcd98fb1abf03e3109da1c4802570b77fddfe015` — **11 / 11** source comments.
3. `முரசறைவாய்` — **Beat the Drum** — verified English `c526195d7eb16b2dc446f8b3b15ae674c75548d5` — **5 / 5** source comments.
4. `பழிக்குப் பழி` — **Revenge for Revenge** — verified English `46627c3cecfd186e1735d8766ddda27414118e62` — **8 / 8** source comments.

Do not reopen these articles without a genuine source-supported defect.

## Article 5 — `ஆரியம் பேசுகிறது` — T3 COMPLETE / VOICE-REVIEWED

- Tamil blob: `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675`
- English file: `publications/ina-muzhakkam/translations/en/05-aariyam-pesugirathu.md`
- working English title: **Aryanism Speaks**
- T1 English blob: `4630e6b7ae5539e71e279ff461f6bc75fb7acbe3`
- T2 English blob: `508639503ab830e83d8cac547476c83d26a8494f`
- T3 English blob: `77310ccb8bac5304f15050ee0988ae26d8302b10`
- `translation_status`: `voice-reviewed`
- source comments: **2 / 2 preserved in order** for scans 38–39
- scan-38→39 trace: `Kula— / chirai`
- T2 fidelity corrections: **2 / 2 preserved**
- T3 voice/style body corrections: **0**
- Tamil source changes: **0**
- blockers: **0**

### Article 5 source-bearing decisions through T3

1. `ஆரியம் பேசுகிறது` → **Aryanism Speaks**; recurring abstract `ஆரியம்` → **Aryanism**.
2. `இரணியன் / பிரகலாதன்` → **Hiraniyan / Pragalathan**.
3. `இராவணன் / விபீஷணன் / வாலி / சுக்ரீவன்` → **Ravanan / Vibheeshanan / Vali / Sugrivan**.
4. `வாலிவதைப் படலம்` → **the chapter of Vali's slaying**.
5. `கோடாரிக் காம்பு` → **axe-handle**; source name `குலச் சிறை` → **Kulachirai**, preserving the physical scan boundary as `Kula— / chirai`.
6. recurring `காந்தியார் / கோட்சே` retain verified **Gandhiyar / Gotse**.
7. `ஓமாந்தூரார்` → **Omaanthooraar**, without outside identification.
8. quoted `ஆரியத்துக்கு எதிர்ப்பா?` → **“Opposition to Aryanism?”**.
9. `கறுப்புப் படை` → **Black Army**, without outside expansion.
10. closing plural `விபீஷண சுக்ரீவர்` → **Vibheeshanans and Sugrivans**; `உங்கள் இனம்` → **your race**.
11. both source-page comments and the scan-38→39 boundary remain explicit.

### Article 5 T2 bilingual fidelity corrections — preserved at T3

1. `அவனிடத்தில் ஆசை வலை விரித்தேன்.` — T1 **I spread a net of desire for him.** → T2 **I cast a net of desire around him.** The T1 preposition could imply that the speaker desired Vibheeshanan; T2 restores the source's entrapment relation.
2. `ஓமாந்தூராரை அதட்டிக் கேட்டேன்` — T1 **I barked at Omaanthooraar** → T2 **I demanded of Omaanthooraar**. T1 added an animal metaphor absent from the frozen Tamil; T2 preserves harsh questioning without adding imagery.

T2 final findings after correction: omitted clauses **0**; added claims **0**; name/referent defects **0**; negative/comparison/logical-relation defects **0**; quotation-scope defects **0**; source-comment/page-trace defects **0**; blockers **0**.

### Article 5 T3 Kalaignar voice review

T3 re-fetched and compared frozen Tamil blob `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675` with T2 English blob `508639503ab830e83d8cac547476c83d26a8494f`. The fidelity-reviewed English already preserved the source's direct first-person personification, sarcasm/mockery, rhetorical questions, abrupt contrasts, visceral physical imagery, repetition and boastful cadence. No harsh formulation had been softened, no repeated phrase removed, no vivid image abstracted and no academic explanation inserted.

**No T3 body correction was required.** Both T2 fidelity corrections, all source-bearing forms, both source comments, scan-38→39 `Kula— / chirai` and quotation scope remain intact. T3 English blob is `77310ccb8bac5304f15050ee0988ae26d8302b10`.

## Translation non-regression

- Translate frozen Tamil; do not use OCR/raw transcription/scan-alternate readings.
- Preserve direct address, commands, questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained labels from outside knowledge.
- Preserve ordered source comments, page-boundary traces, quotation status and source punctuation irregularities.
- Scan-24/37 promotions, scan-40 front matter/review and scan-50 catalogue remain excluded.
- `கவிதைகள்` English must preserve frozen headings and lineation.
- Known source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` must not be replaced with scan alternatives.
- Articles 1–4 are individually T5-frozen.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — Article 5 `ஆரியம் பேசுகிறது` — T4 terminology / quotation / citation / source audit only.**

Required steps:

1. fetch live `main` first;
2. re-read translation plan, tracker, lexicon and review ledger;
3. re-fetch frozen Tamil Article 5 and confirm blob `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675`;
4. re-fetch T3 English Article 5 and confirm blob `77310ccb8bac5304f15050ee0988ae26d8302b10`;
5. audit title/ideological terminology, source-specific names, proper-name/source-witness treatment, quotation scope, source-page comments and scan-38→39 `Kula— / chirai`;
6. preserve both T2 fidelity corrections and the T3 zero-body-change result unless a genuine T4 terminology/quotation/citation/source defect requires correction;
7. make **T4 audit corrections only** and record exact findings across durable records;
8. **STOP AFTER ARTICLE 5 T4. DO NOT PERFORM ARTICLE 5 T5 IN THE SAME ACTIVITY.**
