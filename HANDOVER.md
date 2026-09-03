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
- Last confirmed live HEAD immediately before this handover synchronization: `5c38c64216c7d7e757ccff07451c4e30d5624cbe` — `Record Ina Muzhakkam E6 source provenance`.

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

# Publication 5 — இன முழக்கம் — TAMIL FROZEN / T0–T5 6/6 / E6 PASS

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
- E6: **PASS / COMPLETE**
- E7: **NOT STARTED**
- English blockers: **0**

## Historical T5 English boundaries

1. `இன முழக்கம்` — **The Clarion Call of the Race** — `01d0d16c4f52cb134eba9fd35c06ad8376e256cb` — **8 / 8** source comments.
2. `சொர்க்க லோகத்தில்` — **In the Heavenly Realm** — `bcd98fb1abf03e3109da1c4802570b77fddfe015` — **11 / 11** source comments.
3. `முரசறைவாய்` — **Beat the Drum** — `c526195d7eb16b2dc446f8b3b15ae674c75548d5` — **5 / 5** source comments.
4. `பழிக்குப் பழி` — **Revenge for Revenge** — `46627c3cecfd186e1735d8766ddda27414118e62` — **8 / 8** source comments.
5. `ஆரியம் பேசுகிறது` — **Aryanism Speaks** — `4b1666afd885c3d8b800b08410a3dbfe498856bc` — **2 / 2** source comments.
6. `கவிதைகள்` — **Poems** — `9e6f90b00bfa9a5059f1eef6875e8cef3c3652c3` — **9 / 9** source comments; **11 / 11** poem headings.

These are historical article-level T5 checkpoints. E6 consistency corrections are downstream and recorded separately.

## E6 publication-wide English consistency review — PASS / COMPLETE

E6 reviewed all six verified units together for recurring names/epithets, Aryan/Dravidian vocabulary, source-specific transliterations, title style, quotation/source treatment, source-page trace, source-cultural terms and accidental smoothing.

Three correction groups were required and completed:

1. Article 2: **Tirugnana Sambandar** → **Thirugnana Sambandar**. The transliteration root now agrees with Article 4 while preserving the source witness distinction `திருஞான சம்பந்தர்` / `திருஞானசம்பந்தர்` as **Thirugnana Sambandar / Thirugnanasambandar**.
2. Article 5: **Vibheeshanan / Sugrivan / Vibheeshanans / Sugrivans** → **Vibhishana / Sugriva / Vibhishanas / Sugrivas**, because Articles 1 and 5 use the same frozen Tamil forms `விபீஷணன் / சுக்ரீவன்`.
3. Article 6: **Parvathi / Ahalyai / Indran / Tharai / Chandran** → **Parvati / Ahalya / Indra / Tara / the Moon**, matching recurring mythic-name treatment already established in Articles 1–2.

### E6 deliberate exceptions retained

Do **not** homogenise these source-supported/contextual differences during E7:

- **Kamaraj Nadar / Kamarajar / Kamarajars**;
- **Gramaniyar / Gramaaniyar**;
- **Aachariyar / Aachaariyar**;
- **Kanaka Visayar / Kanakan / Visayan**;
- **Vadalur Ramalingam / Vadalur Ramalingar**;
- **Arutperum Jothi / Arut Sothi**;
- Article-2 **Eripatha Nayanar** versus frozen Article-6 **Eripaththar**;
- Article-2 **Kotpuli Nayanar** versus Article-6 **Kotpuli**;
- Article-4 **Varnashrama** versus Article-6 **Varna**;
- Article-2 **Parvati Devi** versus Article-6 **Parvati** because `Devi` is source-present only in Article 2.

### E6 release-candidate English authorities

1. Article 1 — `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`.
2. Article 2 — `605db7873d4eaf45cbe04e683280b9b6bd649498`.
3. Article 3 — `c526195d7eb16b2dc446f8b3b15ae674c75548d5`.
4. Article 4 — `46627c3cecfd186e1735d8766ddda27414118e62`.
5. Article 5 — `71656666ae7536a57f88fb5e47938c9c6c9b8e01`.
6. Article 6 — `15b9a08a0aa32305360fd6350e2fab8bb7cd40fb`.

All six files remain `translation_status: verified`.

### E6 final checks

- recurring names/epithets: **PASS**;
- Aryan/Dravidian vocabulary: **PASS**;
- title style: **PASS**;
- quotation/source treatment: **PASS**;
- source-cultural terms / explanatory restraint: **PASS**;
- voice consistency / accidental smoothing: **PASS / 0 defects**;
- ordered source-page comments: **43 / 43 preserved**;
- Article-6 poem headings: **11 / 11 preserved**, with source punctuation and lineation;
- Tamil source changes: **0**;
- blockers: **0**.

## Translation non-regression

- Translate frozen Tamil; do not use OCR/raw transcription/scan-alternate readings.
- Preserve direct address, commands, questions, repetition, sarcasm, mockery, exclamations and loaded ideological/social labels.
- Do not silently identify unexplained labels from outside knowledge.
- Preserve ordered source comments, page-boundary traces, quotation status and source punctuation irregularities.
- Scan-24/37 promotions, scan-40 front matter/review and scan-50 catalogue remain excluded.
- Known source-sensitive forms including `பாரட்டத்`, `ஜோதில்கலந்தான்`, `மனமுள்ளார்`, `ஏறிபத்தர்`, `முடுக்கினாள்`, `போர் வீரனாம்`, `கதறினாள்` must not be replaced with scan alternatives.
- Treat the six E6 release-candidate blobs above as current English authorities for release closeout.

## Current blockers

**None.**

---

# Exact next activity

**Publication 5 — E7 English release closeout only.**

Required steps:

1. fetch live `main` first;
2. re-read `TRANSLATION_PLAN.md`, `translations/en/README.md`, `LEXICON.md`, `TRANSLATION_REVIEW.md`, publication README/metadata and all six E6 release-candidate English units;
3. confirm the six release-candidate blobs exactly: `01d0d16c4f52cb134eba9fd35c06ad8376e256cb`, `605db7873d4eaf45cbe04e683280b9b6bd649498`, `c526195d7eb16b2dc446f8b3b15ae674c75548d5`, `46627c3cecfd186e1735d8766ddda27414118e62`, `71656666ae7536a57f88fb5e47938c9c6c9b8e01`, `15b9a08a0aa32305360fd6350e2fab8bb7cd40fb`;
4. verify release metadata/documentation, source exclusions, 43/43 page comments, Article-6 11/11 headings and zero-blocker state;
5. do not reopen content or E6 choices unless a genuine release-blocking defect is found;
6. if clean, mark `இன முழக்கம்` **English-translation complete / release complete**, freeze the publication release boundary and synchronize all durable records;
7. **STOP AFTER E7. DO NOT START ANOTHER PUBLICATION IN THE SAME ACTIVITY.**