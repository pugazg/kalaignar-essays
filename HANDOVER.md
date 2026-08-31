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
6. the active publication README/metadata/page map/fidelity/completion records
7. if translation is active: publication `TRANSLATION_PLAN.md`, English tracker, lexicon, review ledger and release report if present

For a brand-new work/chat window, use [`docs/START_NEW_ESSAY_WORK_PROMPT.md`](docs/START_NEW_ESSAY_WORK_PROMPT.md) with the controlling PDF attached.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Never silently modernise, correct, normalise, reconstruct or improve the Tamil. Preserve source-visible wording, spelling, punctuation, names, numbers, repetition, grammar and typographical forms. Separate physical-copy marks from printed text. **Source PDFs are never committed to this repository.**

## Old Tamil glyph rule

Existing source-verified Tamil is the baseline. Enlargement/cropping is a verification aid, not permission to invent a new reading. Change the baseline only when clear character-level source evidence proves it wrong. A plausible modern word is **not** evidence.

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, physical imagery, exclamations and wordplay. Do not academicise or soften him. Unexplained source-specific forms remain source-bearing unless the user explicitly asks for outside research. Source punctuation anomalies that matter must be documented rather than silently repaired.

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

Workspace: `publications/sakkaravarththiyin-thirumagan/`  
Source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

- source SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- physical scans: **83**
- printed contents/articles: **14**
- Tamil page records: **83 / 83 complete**
- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14 complete**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Publication-wide identity rule: source `ஆச்சாரியார்` → **Achariyar**; explicit source `இராஜாஜி` → **Rajaji**; source plural `ஆச்சாரியார்களுக்கு` → **the Achariyars**.

Do not restart or stylistically rewrite Publication 1 unless a genuine source-supported defect is discovered.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

Workspace: `publications/kayittril-thongiya-kanapathi/`  
Supplied source: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`

## Source identity

- source title: `கயிற்றில் தொங்கிய கணபதி`
- author witnesses: `மு.கருணாநிதி` on cover; `மு. கருணாநிதி` on title page
- publication date: **ஜூலை 1949**
- publisher: **அறிவுப்பண்ணை**
- type: **standalone single-article pamphlet / சிறுநூல்**
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source file size: **26,750,146 bytes**
- source PDF committed: **No**
- printed contents page: **none**

## Tamil archival status — COMPLETE / FROZEN

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2 page records: **17 / 17 verified**
- P3 article assembly: **1 / 1 complete**
- P4 source audit: **PASS**
- P5 strict visual fidelity: **17 / 17 PASS**
- assembly strict-recheck: **1 / 1 PASS**
- unresolved Tamil/body blockers: **0**
- frozen Tamil article blob SHA: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`

Frozen structure:

- scans **1–5** front matter; scan 4 `பதிப்புரை`; scan 5 blank
- scan **6** article opening, **no visible printed numeral**
- scans **7–15** printed pages **6–14**
- scans **6–15** single article
- scan **15** article conclusion + printed ornament
- scans **16–17** advertisements/promotional matter

### Final correction provenance / non-regression

- first pass `தூக்குபோட்டுவிட்டீர்களா 1` → source-visible **`தூக்குபோட்டுவிட்டீர்களா!`**; only `1` → `!` is source-supported. Earlier assistant `தூக்குபோட்டுவிட்டார்களா!` is withdrawn.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — source revalidated.
- interim `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — source revalidated.
- failed assistant changes `ஓடித்` → `ஒடித்`, `அபாண்டங்களைச்` → `அபாண்டங்களச்`, `அவளைப்` → `அவனைப்`, and `சாவின் முனையிலே` → `சாவின் முன்னிலே` remain withdrawn.

Frozen source-specific readings include `உரைந்திருக்கும்`, `அடபாபமே!`, `கவலைப்பட வில்லை.`, `நேரமில்லை`, `சோறில்லை`, `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!`, `நெருக்கடியில்(!)`, `தூக்குபோட்டுவிட்டீர்களா!`, `கொண்டிருக்கிறார்.`, `உரத்தகுரலில்,`, `சாவின் முனையிலே`, and final `அளிக்குமாக /`.

Do not alter the frozen Tamil without explicit source-supported evidence. Any future Tamil correction reopens affected English gates.

## English translation / release state — COMPLETE / FROZEN

English article:

`publications/kayittril-thongiya-kanapathi/translations/en/01-kayittril-thongiya-kanapathi.md`

Final state:

- T0 source prerequisite: **PASS**
- T1 close draft: **PASS**
- T2 bilingual fidelity review: **PASS**
- T3 Kalaignar voice review: **PASS**
- T4 terminology / quotation / citation / source audit: **PASS**
- T5 final article verification: **PASS**
- Article 1 metadata status: **verified**
- verified English articles: **1 / 1**
- verified English title: **Ganapathi Who Hung from the Rope**
- E6 publication-level consistency review: **PASS**
- E7 English release closeout: **PASS / COMPLETE**
- English translation: **COMPLETE**
- English release gate: **CLOSED**
- unresolved translation/release blockers: **0**

### T2–E7 release-frozen decisions

Retain all of the following unless a genuine source-supported/release-blocking defect is documented:

- `the gallows`, `imperialism`, `Dravidam`, `Dravidians`, `Mother Tamil`, `Commonwealth`, `Dravidar Kazhagam`;
- source label `Achariyar` without outside identity substitution;
- source `Jawahar` versus `Nehru` distinction;
- source-bearing `mangu` and `Rani` without guessed identification;
- `Mukari`, `adhirasam`, `akkāra vadisal`, `pallu`;
- `Cry well!` for frozen `நன்றுக அழு!`;
- `in this crisis(!)`;
- `Have you hanged him!`;
- all scan-boundary comments **6–15**;
- documented irregular quotation scope around `சுதந்திர பூமியில்...`;
- documented irregular quotation syntax beginning `மிகவும் உயர்ந்த நிலையில்...`;
- final `/` in `May Ganapathi's murder give the Dravidians this resolve /`.

### E7 release closeout result

E7 was performed against live `main` after E6.

Release checks confirmed:

- verified English article blob reviewed: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`;
- frozen Tamil authority remains `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
- English `source_tamil_blob_sha` matches exactly;
- article remains `translation_status: verified`;
- counts/statuses agree: **1 / 1 verified**;
- T0–T5 and E6 records agree: **PASS**;
- source/advertisement boundaries remain intact;
- pre-E7 recursive Git tree `06b72c1c4239f1e5efb0add19c167a7e18373580` contains **no `.pdf` file**;
- source-bearing decisions and documented source anomalies remain intact;
- English body changes during E7: **0**;
- Tamil body changes during E7: **0**;
- E7 blockers: **0**.

Detailed English/release provenance:

- `publications/kayittril-thongiya-kanapathi/TRANSLATION_PLAN.md`
- `publications/kayittril-thongiya-kanapathi/translations/en/README.md`
- `publications/kayittril-thongiya-kanapathi/translations/en/LEXICON.md`
- `publications/kayittril-thongiya-kanapathi/translations/en/TRANSLATION_REVIEW.md`
- `publications/kayittril-thongiya-kanapathi/translations/en/RELEASE_REPORT.md`

Do not reopen Publication 2 for stylistic polishing unless a genuine source-supported or release-blocking defect is discovered.

---

# Publication 3 — உணர்ச்சிமாலை — TAMIL SOURCE ACTIVE

Workspace: `publications/unarchchimaalai/`  
Supplied source: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`

## Source identity

- title-page witness: `உணர்ச்சிமாலை`
- cover title is displayed over two lines as `உணர்ச்சி` / `மாலை`
- author witnesses: `மு.கருணாநிதி` on cover; `மு. கருணாநிதி` on title page
- edition statement: **`முதற்பதிப்பு—1951`**
- publisher: **கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.**
- type: **10-article collection / multi-article publication**
- physical scans: **50**
- source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- source file size: **79,471,633 bytes**
- source PDF committed: **No**
- printed contents page: **none observed**

## P0 intake result — COMPLETE

- live `main` was checked before intake; no existing `உணர்ச்சிமாலை` publication tree was present
- scans 1–5 are front matter; scan 50 is a separate illustrated back-cover advertisement
- scans 6–49 contain ten article units
- scan 49 carries the publication closing/imprint material after Article 10
- publication metadata/source record created
- source PDF remains outside the repository

Initial article-boundary observations:

1. `உணர்ச்சி மாலை` — scans **6–9**
2. `புரட்சி வளர்ந்த கதை` — scans **10–15**
3. `போகிறான்;போகிறான்..!` — scans **16–18**
4. `இராவணன் நம் பாட்டன்` — scans **19–29**
5. `இங்கல்ல! இரஷ்யாவில்` — scans **30–32**
6. `3, 57, 90.` — scans **33–38**
7. `30-1-1948` — scans **39–41**
8. `பத்தினியே உன்போல்...!` — scans **42–44**
9. `அன்னை நாகம்மையார்!` — scans **45–47**
10. `கவிதையல்ல - கண்ணீர்க்கடல்!` — scans **48–49**

P1 must re-record exact heading punctuation/spacing and every visible printed page number directly from the scans rather than inferring them from OCR.

## Publication-specific user instruction — Gemini lexical baseline

For Publication 3, the user explicitly instructed:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features.**

This is the controlling **workflow instruction for lexical tokens in the current Tamil pass**:

- Gemini word choices are the working lexical baseline;
- do not silently change Gemini word tokens from scan inspection;
- the scan is used to restore/verify headings, punctuation, spacing, paragraph boundaries, verse/quotation layout, indentation and other non-lexical structure;
- any apparent scan/Gemini lexical conflict must be logged for user decision, not silently resolved;
- this rule is a user-directed exception for this publication and does not convert OCR into authority for physical-copy evidence or publication structure.

Important non-regression distinction already visible: publication/title-page witness `உணர்ச்சிமாலை` vs Article 1 heading `உணர்ச்சி மாலை`; preserve them separately.

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + complete page map / article-boundary mapping: **NEXT**
- page records: **0 / 50**
- article assemblies: **0 / 10**
- P4 source audit: **NOT STARTED**
- P5 strict visual fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

Source records:

- `publications/unarchchimaalai/README.md`
- `publications/unarchchimaalai/metadata/source.md`

---

# Exact next activity

Publications 1 and 2 remain **COMPLETE / FROZEN / RELEASED**. Publication 3 `உணர்ச்சிமாலை` is now the active Tamil source publication after P0 intake.

Execute **P1 — metadata + complete 50-scan page map / contents-boundary mapping** for Publication 3:

1. inspect all 50 physical scans and create `publications/unarchchimaalai/indexes/page-map.md`;
2. classify every scan, including front matter, all ten article units, scan-49 closing/imprint matter and scan-50 advertisement;
3. create `indexes/contents.md`, explicitly recording that there is no printed contents page while separately mapping the ten scan-verified article headings/boundaries;
4. record visible printed-page-number behaviour exactly and do not invent missing numerals;
5. preserve publication/title/article-heading witness distinctions;
6. preserve the user-established Gemini lexical-baseline rule; do not perform lexical corrections in P1;
7. update the publication README/source record and this root handover after completing P1.

## Current blockers

**None.**