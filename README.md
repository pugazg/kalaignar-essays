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

## Publication 3 — உணர்ச்சிமாலை — COMPLETE / FROZEN / RELEASED

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

### Final English translation / release status

- T0 source prerequisite/setup: **COMPLETE / PASS**
- T1 drafts: **10 / 10**
- T2 fidelity-reviewed: **10 / 10**
- T3 voice-reviewed: **10 / 10**
- T4 audited: **10 / 10**
- T5 verified: **10 / 10**
- E6 publication-wide English consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- English body corrections during E6/E7: **0**
- unresolved translation/release blockers: **0**
- **English translation: COMPLETE / RELEASED / FROZEN**

Translation/release workspace:

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

### Final English article blob authorities

1. `4246c9f1e206d5703fe50297657bb0af2a8e57e6`
2. `f1599a8e7cae4ba749b9be2857705b152887f9f8`
3. `1134185bc21478775419adb3560b110c001d2b75`
4. `03ac3b0fc25f38a4b56c352f53bf73915b1f33fb`
5. `c689ff90f08d389a5e7ebc4849c30d58dfe81766`
6. `cf9187b40bc1bc64806a1df84e45c884b1b8d9a8`
7. `6cfb28e2d83ba84ee2daa54606561479b61498b0`
8. `6b12e6b3cc09b6de402998bb3824e7a98808f885`
9. `204ffed012f4bd91b3077065f031d6b2db747854`
10. `cee8ea3c33495615ffc988a1875d71e40f8224a3`

These Tamil and English authorities remain frozen unless a genuine source-supported or release-blocking defect explicitly reopens the affected gate.

## Publication 4 — திராவிட சம்பத்து — ACTIVE / ARTICLE 2 T2 PASS

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

### Publication-specific lexical rule

The user supplied a transcription that captured the surviving wording and established it as the lexical baseline. **Retain those words.** The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, page/article boundaries and physical-copy evidence. Text physically lost under torn-away paper must not be reconstructed from context.

### Frozen Tamil source status

- P0 source intake: **COMPLETE**
- P1 metadata / page map / reading-order reconstruction: **COMPLETE**
- P2 page-level transcription / structural review: **16 / 16 COMPLETE**
- P3 article assemblies: **COMPLETE — 2 / 2**
- P4 source/completeness audit: **PASS**
- P5 strict visual word/punctuation fidelity: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- unresolved Tamil workflow blockers: **0**

Frozen Tamil translation authorities:

1. `திராவிட சம்பத்து` — scans **5–6, 13–16** — `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

P5 documented and retained the publication's source-witness conflicts; all torn-away text remains unreconstructed.

### English translation status

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 drafts: **2 / 2 PASS**
- T2 fidelity-reviewed: **2 / 2 PASS**
- T3 voice-reviewed: **1 / 2 PASS**
- T4 audited: **1 / 2 PASS**
- T5 verified: **1 / 2 PASS**
- English article bodies: **2 / 2**
- translation blockers: **0**

Translation workspace:

- [`TRANSLATION_PLAN.md`](publications/thiraavida-sampaththu/TRANSLATION_PLAN.md)
- [`translations/en/README.md`](publications/thiraavida-sampaththu/translations/en/README.md)
- [`translations/en/LEXICON.md`](publications/thiraavida-sampaththu/translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](publications/thiraavida-sampaththu/translations/en/TRANSLATION_REVIEW.md)
- [`translations/en/01-thiraavida-sampaththu.md`](publications/thiraavida-sampaththu/translations/en/01-thiraavida-sampaththu.md) — **Article 1 VERIFIED**
- [`translations/en/02-aiyar-arivikkirar.md`](publications/thiraavida-sampaththu/translations/en/02-aiyar-arivikkirar.md) — **Article 2 T2 fidelity-reviewed**

Article 1 English title: **Dravidian Wealth — VERIFIED**.  
Article 2 working English title: **Iyer Announces! — T2 semantic pass / not frozen**.

Article 2 T2:

- frozen Tamil blob: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`
- T1 draft blob: `1b70952ae377668162fcb35eb045e142a0597190`
- T2 fidelity-reviewed blob: `b7361d26a711d61938da24d33b3512ddf5653e53`
- source comments: scans **12, 3 — 2 / 2 present and ordered**
- `ஐயர்` / `அய்யர்`: **Iyer / Ayyar** distinction retained
- frozen damaged `அயம்`: source-bearing **ayam**, unrepaired
- `ஏனோதானோ` / `ஏனோதானோக்கள்`: **Enothano / Enothanos**
- normal `கல்லூரி`: **College**; frozen `கல்லுரி`: source-bearing **kalluri**
- narrative `சாமிநாதய்யர்`: **Saminathayyar**; inscription `சாமிநாத அய்யர்`: **Saminatha Ayyar**
- inscription: source-bearing **Maha Mahopadhyaya Dravida Vidya Bhushana Dr. Saminatha Ayyar**
- T2 body corrections: **3**
- frozen Tamil changes: **0**
- unresolved T2 blockers: **0**

Detailed Tamil/English records:

- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/thiraavida-sampaththu/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`PUBLICATION_COMPLETION_REVIEW.md`](publications/thiraavida-sampaththu/PUBLICATION_COMPLETION_REVIEW.md)

## Current project state / exact next activity

Publications 1, 2 and 3 are **COMPLETE / FROZEN / RELEASED**. Publication 4 `திராவிட சம்பத்து` has a frozen Tamil layer, Article 1 is **T5 VERIFIED**, and Article 2 is **T2 PASS**.

**Exact next activity:** execute **Article 2 T3 — Kalaignar voice review** against frozen Tamil blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6` and T2 English blob `b7361d26a711d61938da24d33b3512ddf5653e53`. Review direct address, commands, repetition, mockery, the startled `அய்யராவது...` construction, `உண்மை நண்பர்களே உண்மை!`, the fire-stepping image, `ஏனோதானோ` ridicule, the imperative ending and the inscription reveal. Make only meaning-neutral voice/cadence changes and stop after T3. Do not perform Article 2 T4 in the same activity.