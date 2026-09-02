# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் கட்டுரைத் தொகுப்புகளை source-first முறையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

Source-visible wording, பழைய எழுத்துப்பாங்கு, punctuation, பெயர்கள், எண்கள், மீளுரைகள், வழக்கத்திற்கு மாறான இலக்கணம் மற்றும் source-witness வேறுபாடுகள் அமைதியாகச் சீர்திருத்தப்படவோ நவீனப்படுத்தப்படவோ கூடாது. Source PDF files repository-யில் commit செய்யப்படாது.

## Permanent workflow documents

- [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
- [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)
- [`docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`](docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md)
- [`docs/START_NEW_ESSAY_WORK_PROMPT.md`](docs/START_NEW_ESSAY_WORK_PROMPT.md)

## Publication 1 — சக்கரவர்த்தியின் திருமகன் — COMPLETE / FROZEN / RELEASED

Workspace: [`publications/sakkaravarththiyin-thirumagan/`](publications/sakkaravarththiyin-thirumagan/)

- physical scans: **83**
- printed articles: **14**
- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

## Publication 2 — கயிற்றில் தொங்கிய கணபதி — COMPLETE / FROZEN / RELEASED

Workspace: [`publications/kayittril-thongiya-kanapathi/`](publications/kayittril-thongiya-kanapathi/)

- physical scans: **17**
- Tamil page records: **17 / 17**
- P5 strict visual fidelity: **17 / 17 PASS**
- Tamil source: **COMPLETE / FROZEN**
- English translation/release: **COMPLETE / RELEASED**
- unresolved blockers: **0**

## Publication 3 — உணர்ச்சிமாலை — COMPLETE / FROZEN / RELEASED

Workspace: [`publications/unarchchimaalai/`](publications/unarchchimaalai/)

- physical scans: **50**
- Tamil P2: **50 / 50**
- Tamil P3: **10 / 10**
- P4: **PASS**
- P5: **50 / 50 PASS**
- English T0–T5: **10 / 10 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- unresolved blockers: **0**

Detailed records remain in the publication workspace. Do not reopen absent a genuine source-supported or release-blocking defect.

## Publication 4 — திராவிட சம்பத்து — COMPLETE / FROZEN / RELEASED

Workspace: [`publications/thiraavida-sampaththu/`](publications/thiraavida-sampaththu/)

- physical scans: **16**
- Tamil P0–P5: **COMPLETE / FROZEN**
- English T0–T5: **2 / 2 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- unresolved blockers: **0**

Released English authorities:

1. [`Dravidian Wealth`](publications/thiraavida-sampaththu/translations/en/01-thiraavida-sampaththu.md) — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. [`Iyer Announces!`](publications/thiraavida-sampaththu/translations/en/02-aiyar-arivikkirar.md) — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Do not reopen absent a genuine source-supported or release-blocking defect.

## Publication 5 — இன முழக்கம் — ACTIVE / P1 COMPLETE

Workspace: [`publications/ina-muzhakkam/`](publications/ina-muzhakkam/)

- controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`
- physical scans: **50**
- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- edition: **முதற் பதிப்பு: செப்டம்பர் 1951**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- source PDF committed: **No**

### Publication-specific user rule

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The user's full 50-scan transcription has been structurally reassembled against the source into staging records without silently changing lexical tokens.

Printed contents witness:

1. `இன முழக்கம்` — 4
2. `சொர்க்க லோகத்தில்` — 13
3. `முரசறைவாய்` — 24
4. `பழிக்குப் பழி` — 29
5. `ஆரியம் பேசுகிறது` — 37
6. `கவிதைகள்` — 40

Current gates:

- P0: **COMPLETE**
- P1 metadata / contents / page map: **COMPLETE**
- structural transcription intake: **COMPLETE / STAGING**
- P2 canonical page records: **0 / 50**
- P3 article/section assemblies: **0 / 6**
- P4: **NOT STARTED**
- P5: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

Important structural corrections and the corrected staging transcription are recorded in:

- [`STRUCTURAL_REASSEMBLY_REVIEW.md`](publications/ina-muzhakkam/STRUCTURAL_REASSEMBLY_REVIEW.md)
- [`transcription-intake/scans-0001-0020.md`](publications/ina-muzhakkam/transcription-intake/scans-0001-0020.md)
- [`transcription-intake/scans-0021-0040.md`](publications/ina-muzhakkam/transcription-intake/scans-0021-0040.md)
- [`transcription-intake/scans-0041-0050.md`](publications/ina-muzhakkam/transcription-intake/scans-0041-0050.md)

## Current project state / next activity

Publications **1–4 are COMPLETE / FROZEN / RELEASED**. Publication 5 `இன முழக்கம்` is active with P0/P1 and the full structural staging transcription complete.

**Exact next activity:** create and directly verify **P2 canonical page records for scans 1–25**. Preserve printed text separately from physical-copy marks and do not begin P3 assemblies in the same activity.