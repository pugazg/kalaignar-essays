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

- title: **திராவிட சம்பத்து**
- author: **கலைஞர் மு. கருணாநிதி**
- edition: **முதல பதிப்பு, செப்டம்பர் 1951**
- publisher: **அறிவு மன்றம், சென்னை-1**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை-1**
- physical scans: **16**
- source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- source PDF committed: **No**
- condition: **heavily damaged / multiple torn-away text areas**

### Publication-specific source rule

The user-supplied transcription is the lexical baseline for surviving Tamil words. The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, page/article boundaries and physical-copy evidence. Text physically lost under torn-away paper is not reconstructed from context.

### Frozen Tamil source status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **2 / 2 COMPLETE**
- P4: **PASS**
- P5: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- unresolved Tamil blockers: **0**

Frozen Tamil authorities:

1. `திராவிட சம்பத்து` — scans **5–6, 13–16** — `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

### Final English translation / release status

- E0: **COMPLETE / PASS**
- T0: **2 / 2 PASS**
- T1: **2 / 2 PASS**
- T2: **2 / 2 PASS**
- T3: **2 / 2 PASS**
- T4: **2 / 2 PASS**
- T5: **2 / 2 PASS**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- unresolved translation/release blockers: **0**

Released English authorities:

1. [`Dravidian Wealth`](publications/thiraavida-sampaththu/translations/en/01-thiraavida-sampaththu.md) — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. [`Iyer Announces!`](publications/thiraavida-sampaththu/translations/en/02-aiyar-arivikkirar.md) — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

E7 confirmed both English blobs still match the E6-passed baseline, both frozen Tamil blobs remain unchanged, no article gate was reopened, no source/release defect was discovered and release blockers remain **0**.

Detailed records:

- [`README.md`](publications/thiraavida-sampaththu/README.md)
- [`metadata/source.md`](publications/thiraavida-sampaththu/metadata/source.md)
- [`PUBLICATION_COMPLETION_REVIEW.md`](publications/thiraavida-sampaththu/PUBLICATION_COMPLETION_REVIEW.md)
- [`TRANSLATION_PLAN.md`](publications/thiraavida-sampaththu/TRANSLATION_PLAN.md)
- [`translations/en/README.md`](publications/thiraavida-sampaththu/translations/en/README.md)
- [`translations/en/LEXICON.md`](publications/thiraavida-sampaththu/translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](publications/thiraavida-sampaththu/translations/en/TRANSLATION_REVIEW.md)

## Current project state / next activity

Publications **1–4 are COMPLETE / FROZEN / RELEASED**. There is no pending review gate.

**Next project activity:** intake of the next supplied Kalaignar essay/article publication. Fetch live `main` first, follow the permanent processing guide and do not reopen Publications 1–4 absent a genuine source-supported or release-blocking defect.