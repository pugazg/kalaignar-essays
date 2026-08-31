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
- Tamil page records: **83 / 83**
- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Detailed records are inside the publication workspace. Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is discovered.

## Publication 2 — கயிற்றில் தொங்கிய கணபதி — COMPLETE / FROZEN / RELEASED

Workspace: [`publications/kayittril-thongiya-kanapathi/`](publications/kayittril-thongiya-kanapathi/)

- physical scans: **17**
- Tamil page records: **17 / 17**
- P4: **PASS**
- P5 strict visual fidelity: **17 / 17 PASS**
- article strict-fidelity recheck: **1 / 1 PASS**
- Tamil source: **COMPLETE / FROZEN**
- English translation/release: **COMPLETE / RELEASED**
- unresolved blockers: **0**

Detailed records:

- [`PUBLICATION_COMPLETION_REVIEW.md`](publications/kayittril-thongiya-kanapathi/PUBLICATION_COMPLETION_REVIEW.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/kayittril-thongiya-kanapathi/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`translations/en/`](publications/kayittril-thongiya-kanapathi/translations/en/)

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is discovered.

## Publication 3 — உணர்ச்சிமாலை — TAMIL SOURCE COMPLETE / FROZEN; ENGLISH T0 COMPLETE

Workspace: [`publications/unarchchimaalai/`](publications/unarchchimaalai/)

- author witnesses: **`மு.கருணாநிதி` / `மு. கருணாநிதி`**
- edition statement: **`முதற்பதிப்பு—1951`**
- publisher: **கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.**
- type: **10-article collection / multi-article publication**
- physical scans: **50**
- source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- source PDF committed: **No**
- printed contents page: **none**

### Publication-specific lexical rule

For this publication only, the user explicitly established:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features.**

Therefore scan/Gemini lexical disagreements are documented instead of silently normalised.

### Final Tamil source status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2 page records: **COMPLETE — 50 / 50 verified**
- P3 article assemblies: **COMPLETE — 10 / 10**
- P4 source audit / completeness review: **PASS**
- P5 strict visual-text-fidelity pass: **COMPLETE — 50 / 50 PASS**
- article strict-fidelity recheck: **10 / 10 PASS**
- source-supported P5 structural/punctuation/spacing/layout corrections propagated: **236**
- documented Gemini/source lexical conflicts retained under the user rule: **18**
- outstanding `needs-review` / blocked fidelity items: **0**
- unresolved Tamil/body blockers: **0**
- **Tamil source: COMPLETE / FROZEN**

Important frozen P5 results include the corrected scan 33/34 boundary, source-recovered scan-42 `பதில் இல்லை.`, scan-43 `* * *`, scan-49 `அன்பன் அச்சகம், சென்னை-1.` outside Article 10, and stacked scan-50 `BALU` / `BROS` advertisement text.

Detailed final Tamil records:

- [`README.md`](publications/unarchchimaalai/README.md)
- [`metadata/source.md`](publications/unarchchimaalai/metadata/source.md)
- [`indexes/page-map.md`](publications/unarchchimaalai/indexes/page-map.md)
- [`indexes/contents.md`](publications/unarchchimaalai/indexes/contents.md)
- [`audit.md`](publications/unarchchimaalai/audit.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/unarchchimaalai/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`PUBLICATION_COMPLETION_REVIEW.md`](publications/unarchchimaalai/PUBLICATION_COMPLETION_REVIEW.md)

### English translation status

- T0 source prerequisite/setup: **COMPLETE / PASS**
- ten frozen Tamil article blob authorities: **10 / 10 reverified against live `main`**
- T1 drafts: **0 / 10**
- T2 fidelity-reviewed: **0 / 10**
- T3 voice-reviewed: **0 / 10**
- T4 audited: **0 / 10**
- T5 verified: **0 / 10**
- English body translation: **NOT STARTED**
- unresolved translation blockers: **0**

Translation workspace:

- [`TRANSLATION_PLAN.md`](publications/unarchchimaalai/TRANSLATION_PLAN.md)
- [`translations/en/README.md`](publications/unarchchimaalai/translations/en/README.md)
- [`translations/en/LEXICON.md`](publications/unarchchimaalai/translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md)

### Frozen Tamil article blob authorities

1. `c63837a9f7c02d6f3a18171a512d46788f66ad92`
2. `dda81363f512ee2f829c367ae929ce3610604fe9`
3. `92eb1a68d65f65dd71274e5e79f3209e63359d9a`
4. `006f2f75dbc3eea796170a29aee0befd162522e7`
5. `c8ac4d7c241832e07bbb24c5cee935588673f4ac`
6. `f3634a63bff94f5647dbbdfa7dfe9b1b0a2479d8`
7. `bac121257d24477bc3c7e8c65f4b3f7b8a419bad`
8. `2e57a4c7c53ae4354942b5e64c5a2c4a33f3be2f`
9. `4dd0bbc03f278c9bfc02b189b285a1891aa44d2d`
10. `f856664d86695237a23d0ffc0bef088d32a82fe9`

These are the translation authorities unless a later source-supported Tamil correction explicitly reopens P5.

## Current project state / exact next activity

Publications 1 and 2 are **COMPLETE / FROZEN / RELEASED**. Publication 3 `உணர்ச்சிமாலை` has a **COMPLETE / FROZEN Tamil source** and its English **T0 setup is COMPLETE / PASS**.

**Exact next activity:** execute **Article 1 T1 — complete close English draft for `உணர்ச்சி மாலை`** from frozen Tamil blob `c63837a9f7c02d6f3a18171a512d46788f66ad92`. Preserve all verse and scan-boundary provenance, establish a provisional English title and initial living-lexicon decisions, leave the article at `translation_status: draft`, and stop before T2 bilingual review.