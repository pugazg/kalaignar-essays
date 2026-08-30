# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் கட்டுரைத் தொகுப்புகளை **மூல ஸ்கேனை controlling source ஆகக் கொண்டு** Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் தெரியும் எழுத்து, பழைய எழுத்துப்பாங்கு, punctuation, பெயர்கள், எண்கள், மீளுரைகள், வழக்கத்திற்கு மாறான இலக்கணம் ஆகியவை அமைதியாகச் சீர்திருத்தப்படவோ நவீனப்படுத்தப்படவோ கூடாது. Source PDF files repository-யில் commit செய்யப்படாது.

## Permanent workflow documents

- [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
- [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)
- [`docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`](docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md)
- [`docs/START_NEW_ESSAY_WORK_PROMPT.md`](docs/START_NEW_ESSAY_WORK_PROMPT.md)

## Publication 1 — சக்கரவர்த்தியின் திருமகன் — COMPLETE / FROZEN

Workspace: [`publications/sakkaravarththiyin-thirumagan/`](publications/sakkaravarththiyin-thirumagan/)

- ஆசிரியர்: **கலைஞர் மு. கருணாநிதி**
- first-edition statement: **மே 1956**
- supplied edition: **2018 மறுபதிப்பு**
- physical scans: **83**
- printed contents: **14 கட்டுரைகள்**
- source PDF committed: **No**
- Tamil page records: **83 / 83**
- strict Tamil fidelity: **83 / 83**
- Tamil assemblies: **14 / 14**
- English release: **COMPLETE / RELEASED**

Detailed records:

- [`PUBLICATION_COMPLETION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/PUBLICATION_COMPLETION_REVIEW.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`translations/en/`](publications/sakkaravarththiyin-thirumagan/translations/en/)

Do not restart or stylistically rewrite Publication 1 unless a genuine source-supported defect is discovered.

## Publication 2 — கயிற்றில் தொங்கிய கணபதி — TAMIL SOURCE ACTIVE

Workspace: [`publications/kayittril-thongiya-kanapathi/`](publications/kayittril-thongiya-kanapathi/)

- ஆசிரியர்: **மு. கருணாநிதி**
- publication date: **ஜூலை 1949**
- publisher: **அறிவுப்பண்ணை**
- type: **standalone single-article pamphlet / சிறுநூல்**
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source PDF committed: **No**

### Current source status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2 page records: **COMPLETE — 17 / 17 verified**
- P3 article assembly: **COMPLETE — 1 / 1**
- P4 source audit / completeness review: **COMPLETE / PASS**
- audit: [`PUBLICATION_COMPLETION_REVIEW.md`](publications/kayittril-thongiya-kanapathi/PUBLICATION_COMPLETION_REVIEW.md)
- **P5 strict visual-text-fidelity pass: NEXT — 0 / 17**
- Tamil source freeze: **NOT YET**
- English translation: **NOT STARTED**

Source structure remains: scans 1–5 front matter, scan 4 `பதிப்புரை`, scan 5 blank, scans 6–15 article, scans 16–17 separate ads. Scan 6 has no visible printed numeral; scans 7–15 carry visible printed pages 6–14.

P4 confirmed all 17 scans are represented exactly once, page-map/page-record structure is complete, the single assembly uses scans 6–15 only, front matter/advertisements are excluded, and unresolved source/body blockers are **0**.

Retrospective source recheck of the earlier assistant-origin corrections:

- `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டீர்களா!`**. The earlier assistant change to `தூக்குபோட்டுவிட்டார்களா!` was wrong and has been withdrawn; only the final `1` → `!` correction is source-supported.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — rechecked and retained.
- `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — rechecked and retained.

Source-supported forms such as `உரைந்திருக்கும்`, `அடபாபமே!`, `கவலைப்பட வில்லை.`, `சோறில்லை`, `நன்றுக`, `அவர்கட்கு`, `அக்கரை` and final `அளிக்குமாக /` remain unnormalised.

Article: [`01-kayittril-thongiya-kanapathi.md`](publications/kayittril-thongiya-kanapathi/articles/01-kayittril-thongiya-kanapathi.md)  
Source metadata: [`metadata/source.md`](publications/kayittril-thongiya-kanapathi/metadata/source.md)

## Current project state / exact next activity

Publication 1 remains frozen. Publication 2 has completed **P0–P4**.

**Exact next activity:** execute **P5 — strict visual word/punctuation fidelity pass over all 17 physical scans in one activity**. Treat the existing verified transcription as the baseline and change it only when clear source pixels prove a discrepancy. Recheck every visible word, punctuation mark, heading, date, number, meaningful word boundary, continuation and witness boundary; record and propagate every genuinely source-supported correction; create `VISUAL_TEXT_FIDELITY_REVIEW.md`; then recheck the article assembly. Do not mark Tamil frozen or begin English translation until P5 passes.