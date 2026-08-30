# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover document. Update this file after every meaningful source, translation, review or release activity. Do not create competing handover files unless the user explicitly asks.**

## Mandatory startup for future continuation

Read completely before making changes:

1. [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
3. [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)
4. this `HANDOVER.md`
5. [`docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`](docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md) when activating a new publication
6. the active publication `README.md`, `metadata/source.md`, page map and fidelity/completion records
7. if translation is active: publication `TRANSLATION_PLAN.md`, English tracker, lexicon, review ledger and release report if present

For a brand-new work/chat window, use [`docs/START_NEW_ESSAY_WORK_PROMPT.md`](docs/START_NEW_ESSAY_WORK_PROMPT.md) with the controlling PDF attached.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Never silently modernise, correct, normalise, reconstruct or improve the Tamil. Preserve source-visible wording, spelling, punctuation, names, numbers, repetition, grammar and typographical forms. Separate physical-copy marks from printed text. **Source PDFs are never committed to this repository.**

## Old Tamil glyph rule

Old Tamil letterforms must not be converted to a more familiar modern-looking word merely because context makes that alternative seem likely. When a glyph is difficult:

1. inspect the native scan directly;
2. enlarge/crop the exact glyph;
3. compare nearby examples in the same typeface;
4. use the user's source reading as a candidate and verify against pixels;
5. preserve the source-visible form even when unusual;
6. do not create an OCR correction unless the source pixels clearly support it.

A plausible modern word is **not** evidence.

**Retrospective strengthening after Publication 2:** existing source-verified text is the baseline. Enlargement is a verification aid, not permission to invent a new reading. Change the baseline only when clear character-level source evidence proves it wrong.

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, physical imagery, exclamations and wordplay. Do not academicise or soften him. Unexplained source-specific forms remain source-bearing unless the user explicitly asks for outside research. Source punctuation anomalies that matter must be documented rather than silently repaired.

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

Workspace: `publications/sakkaravarththiyin-thirumagan/`  
Source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

- title: `சக்கரவர்த்தியின் திருமகன்`
- author: `கலைஞர் மு.கருணாநிதி`
- physical scans: **83**
- source SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- source file size: **201,858,823 bytes**
- first edition visible in scan: **May 1956**
- supplied reprint: **2018**
- printed contents: **14 articles**
- source PDF committed to repository: **No**

## Publication 1 Tamil archival status — COMPLETE / FROZEN

- **83 / 83** physical page records complete
- **83 / 83** strict word-by-word / punctuation-by-punctuation visual checks complete
- **14 / 14** Tamil article assemblies complete and strict-rechecked
- **0** unresolved `NEEDS-PIXEL-REVIEW`
- **0** blocked body readings

Do not touch the Tamil body layer unless an explicit source-supported correction is found.

Detailed source records:

- [`publications/sakkaravarththiyin-thirumagan/metadata/source.md`](publications/sakkaravarththiyin-thirumagan/metadata/source.md)
- [`publications/sakkaravarththiyin-thirumagan/indexes/page-map.md`](publications/sakkaravarththiyin-thirumagan/indexes/page-map.md)
- [`publications/sakkaravarththiyin-thirumagan/VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`publications/sakkaravarththiyin-thirumagan/PUBLICATION_COMPLETION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/PUBLICATION_COMPLETION_REVIEW.md)

### Frozen source-witness distinctions

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: `காரியமாகும் வரையில் காலைப் பிடி !`.
- Scan 83 is a separate promotional Article 12 witness and must never overwrite Article 12 body text.
- Scan 82 contains the end of Article 14 followed by a separate printed `விடுதலை` advertisement; the advertisement is not Article 14 body.

### High-value strict readings already verified

- `மற்றுமுள்ள`
- `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`
- `எப்படி பெய்ப்படி`
- `கல் சாசனமோ`
- `சீறிப் பாய்ந்தார்கள்`
- `சப்பைக் கட்டு போடும்`
- `நந்திக் கிராமத்திலே யிருந்து`
- `44ஆவது`
- `அப்பேர்ப்பட்டவர்`
- `மாள்வதைவிட`
- `ஓகோ !`
- `மாறடித்து`
- scan 76 `துராசைப் பட்டுக்`
- scan 80 `சவுந்தாயமும்`
- scan 82 `வர்ணிக்கிறான்`

## Publication 1 English translation / release — COMPLETE / RELEASED

- English drafts: **14 / 14**
- T2 fidelity-reviewed: **14 / 14**
- T3 voice-reviewed: **14 / 14**
- T4 audited: **14 / 14**
- T5 verified: **14 / 14**
- E6 publication-wide consistency review: **PASSED**
- E7 English release closeout: **PASSED / COMPLETE**
- unresolved translation questions: **0**
- release blockers: **0**
- English release gate: **CLOSED**

Publication-wide user-established identity rule: source `ஆச்சாரியார்` → **Achariyar**; explicit source `இராஜாஜி` → **Rajaji**; source plural `ஆச்சாரியார்களுக்கு` → **the Achariyars**.

Detailed translation decisions remain frozen in:

- [`publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)
- [`publications/sakkaravarththiyin-thirumagan/translations/en/README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md)
- [`publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md)
- [`publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md)
- [`publications/sakkaravarththiyin-thirumagan/translations/en/RELEASE_REPORT.md`](publications/sakkaravarththiyin-thirumagan/translations/en/RELEASE_REPORT.md)

Do not restart or stylistically rewrite Publication 1 unless a genuine source-supported defect is discovered.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — TAMIL FROZEN / ENGLISH ACTIVE

Workspace: `publications/kayittril-thongiya-kanapathi/`  
Supplied source: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`

- source title: `கயிற்றில் தொங்கிய கணபதி`
- author witnesses: `மு.கருணாநிதி` on cover; `மு. கருணாநிதி` on title page
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source file size: **26,750,146 bytes**
- publication date: **ஜூலை 1949**
- publisher: **அறிவுப்பண்ணை**
- publication type: **standalone single-article pamphlet / சிறுநூல்**
- printed contents page: **none**
- source PDF committed: **No**

## Source authority / OCR rule

Gemini is a first-pass comparison layer only. Scan pixels control the archive. Existing source-verified Tamil is the baseline; never change an old glyph from semantic familiarity or visual resemblance alone. Physical-copy marks remain separate from printed text.

## Tamil archival status — COMPLETE / FROZEN

- P0 source intake / identification: **COMPLETE**
- P1 metadata + page map / boundaries: **COMPLETE**
- P2 page-level transcription: **COMPLETE — 17 / 17 verified**
- P3 article assembly: **COMPLETE — 1 / 1**
- P4 source audit / completeness review: **COMPLETE / PASS**
- P5 strict visual word/punctuation fidelity: **COMPLETE — 17 / 17 PASS**
- article strict-fidelity recheck: **COMPLETE — 1 / 1 PASS**
- outstanding `NEEDS-PIXEL-REVIEW`: **0**
- unresolved body/source blockers: **0**
- **Tamil source layer: COMPLETE / FROZEN**

Detailed source records:

- [`publications/kayittril-thongiya-kanapathi/README.md`](publications/kayittril-thongiya-kanapathi/README.md)
- [`publications/kayittril-thongiya-kanapathi/metadata/source.md`](publications/kayittril-thongiya-kanapathi/metadata/source.md)
- [`publications/kayittril-thongiya-kanapathi/indexes/page-map.md`](publications/kayittril-thongiya-kanapathi/indexes/page-map.md)
- [`publications/kayittril-thongiya-kanapathi/PUBLICATION_COMPLETION_REVIEW.md`](publications/kayittril-thongiya-kanapathi/PUBLICATION_COMPLETION_REVIEW.md)
- [`publications/kayittril-thongiya-kanapathi/VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/kayittril-thongiya-kanapathi/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`publications/kayittril-thongiya-kanapathi/articles/01-kayittril-thongiya-kanapathi.md`](publications/kayittril-thongiya-kanapathi/articles/01-kayittril-thongiya-kanapathi.md)

## Frozen source structure

- scans **1–5**: front matter; scan 4 `பதிப்புரை`; scan 5 blank
- scan **6**: article opening, **no visible printed numeral**
- scans **7–15**: visible printed pages **6–14**
- scans **6–15**: single article
- scan **15**: article conclusion + printed ornament; physical-copy stamp below
- scans **16–17**: advertisements / promotional matter

## Final correction provenance

The earlier assistant-origin corrections were retrospectively re-audited before P5:

- first pass `தூக்குபோட்டுவிட்டீர்களா 1` → source-visible **`தூக்குபோட்டுவிட்டீர்களா!`**. The source line break is `தூக்குபோட்டுவிட்டீர்` + `களா!`; only `1` → `!` is a genuine correction. Earlier assistant `தூக்குபோட்டுவிட்டார்களா!` was wrong and remains withdrawn.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — source revalidated.
- interim `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — source revalidated.

Failed pre-P5 assistant changes `ஓடித்` → `ஒடித்`, `அபாண்டங்களைச்` → `அபாண்டங்களச்`, `அவளைப்` → `அவனைப்`, and `சாவின் முனையிலே` → `சாவின் முன்னிலே` were reverted before P5 and remain withdrawn.

### Frozen source-specific readings

`உரைந்திருக்கும்`, `அடபாபமே!`, `கவலைப்பட வில்லை.`, `நேரமில்லை`, `சோறில்லை`, `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!`, `நெருக்கடியில்(!)`, `தூக்குபோட்டுவிட்டீர்களா!`, `கொண்டிருக்கிறார்.`, `உரத்தகுரலில்,`, `சாவின் முனையிலே`, and final `அளிக்குமாக /`.

Do not alter these or any other frozen Tamil reading without explicit source-supported evidence. If a future Tamil correction is necessary after English work starts, reopen every affected English gate.

## P5 result

All **17 physical scans** were reopened for a fresh strict pass using the verified Tamil as baseline. Every scan passed; no new textual correction was introduced during the final P5 pass. The **1 / 1** article assembly was then strict-rechecked and passed.

**P5 RESULT: PASS. Tamil source is frozen.**

## English translation state — T0 COMPLETE / PASSED

Translation prerequisite: **SATISFIED**.

Frozen Tamil authority:

- `publications/kayittril-thongiya-kanapathi/articles/01-kayittril-thongiya-kanapathi.md`
- frozen Tamil article blob SHA: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`

T0 records:

- [`publications/kayittril-thongiya-kanapathi/TRANSLATION_PLAN.md`](publications/kayittril-thongiya-kanapathi/TRANSLATION_PLAN.md)
- [`publications/kayittril-thongiya-kanapathi/translations/en/README.md`](publications/kayittril-thongiya-kanapathi/translations/en/README.md)
- [`publications/kayittril-thongiya-kanapathi/translations/en/LEXICON.md`](publications/kayittril-thongiya-kanapathi/translations/en/LEXICON.md)
- [`publications/kayittril-thongiya-kanapathi/translations/en/TRANSLATION_REVIEW.md`](publications/kayittril-thongiya-kanapathi/translations/en/TRANSLATION_REVIEW.md)

Current English state:

- T0 source prerequisite / setup: **COMPLETE / PASS**
- Article 1 translation status: **not-started**
- T1 close draft: **NEXT**
- T2 bilingual fidelity: **NOT STARTED**
- T3 voice review: **NOT STARTED**
- T4 terminology/quotation/source audit: **NOT STARTED**
- T5 verification: **NOT STARTED**
- English body file: **not yet created**
- unresolved translation blockers: **0**

Permanent rule: **Translate the language; do not neutralise the voice.**

## Exact next activity

Execute **T1 — complete close English draft for Article 1 only**:

1. re-fetch live `main` and the frozen Tamil article;
2. confirm the Tamil article blob SHA is still `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
3. create `publications/kayittril-thongiya-kanapathi/translations/en/01-kayittril-thongiya-kanapathi.md`;
4. translate the complete article paragraph by paragraph from the frozen Tamil assembly;
5. preserve scan-boundary comments, quotation structure, commands, repetition, rhetorical questions, exclamations, imagery and polemical force;
6. record actual title/terminology decisions in the living lexicon and source/translation issues in the review ledger;
7. set the English article to `translation_status: draft` only after the full body is complete;
8. update tracker/plan/README/HANDOVER to show T1 complete and T2 next;
9. **do not perform T2 in the same activity**.

## Current blockers

**None.**