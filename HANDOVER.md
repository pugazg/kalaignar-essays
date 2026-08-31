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

# Publication 3 — உணர்ச்சிமாலை — TAMIL SOURCE ACTIVE / P2 29 OF 50

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
- printed contents page: **none**

## P0 intake — COMPLETE

- live `main` checked before intake; no existing publication tree was present
- scans 1–5 front matter; scans 6–49 ten article units; scan 50 separate illustrated advertisement
- source PDF remains outside the repository

## P1 metadata + complete page / boundary mapping — COMPLETE

P1 directly inspected and classified all **50 / 50** physical scans.

Created:

- `publications/unarchchimaalai/indexes/page-map.md`
- `publications/unarchchimaalai/indexes/contents.md`

Verified article spans / heading witnesses:

1. `உணர்ச்சி மாலை` — scans **6–9**
2. `புரட்சி வளர்ந்த கதை` — scans **10–15**
3. `போகிறான்;போகிறான்..!` — scans **16–18**
4. `இராவணன் நம் பாட்டன்` — scans **19–29**; heading physically two lines
5. `இங்கல்ல! இரஷ்யாவில்` — scans **30–32**
6. `3, 57, 90.` — scans **33–38**
7. `30-1-1948` — scans **39–41**
8. `பத்தினியே உன்போல்...!` — scans **42–44**; heading physically two lines
9. `அன்னை நாகம்மையார்!` — scans **45–47**
10. `கவிதையல்ல - கண்ணீர்க்கடல் !` — scans **48–49**; heading physically `கவிதையல்ல -` / `கண்ணீர்க்கடல் !`

No printed contents page exists. Article-opening scans have no visible printed page numeral. Scan 20 preserves only the visible page-position `1`; an unseen `19` must never be invented.

Important non-regression distinction: publication/title-page witness `உணர்ச்சிமாலை` vs Article 1 heading `உணர்ச்சி மாலை`; preserve separately.

## Publication-specific user instruction — Gemini lexical baseline

For Publication 3, the user explicitly instructed:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features.**

Controlling workflow rule for this Tamil pass:

- Gemini word choices are the working lexical baseline wherever Gemini supplied text;
- do not silently change Gemini word tokens from scan inspection;
- use the scan to restore/verify headings, punctuation, spacing, paragraph boundaries, verse/quotation layout, indentation and other non-lexical structure;
- any apparent scan/Gemini lexical conflict must be logged for user decision, not silently resolved;
- physical-copy evidence and page/section boundaries remain scan-controlled;
- if Gemini omits a whole paragraph/page, source recovery is permitted only under the user's explicit missing-paragraph instruction and must be labelled as scan-derived rather than Gemini-derived.

## P2 page-level transcription — ACTIVE

Completed and directly compared for the authorised structural layer:

- scans **1–5** — front matter: **5 / 5**
- Article 1 `உணர்ச்சி மாலை`, scans **6–9**: **4 / 4**
- Article 2 `புரட்சி வளர்ந்த கதை`, scans **10–15**: **6 / 6**
- Article 3 `போகிறான்;போகிறான்..!`, scans **16–18**: **3 / 3**
- Article 4 `இராவணன் நம் பாட்டன்`, scans **19–29**: **11 / 11**
- total page records: **29 / 50 verified**

P2 non-regression notes:

- every page record separates `# அச்சு உரை` from `## அச்சு அல்லாத / physical-copy marks`;
- Gemini letters/word choices remain unchanged as the lexical baseline wherever present;
- only scan-supported punctuation, spacing, paragraph breaks, headings and quotation/lineation are restored;
- scan 6, scan 10, scan 16 and scan 19 remain `printed_page: null`;
- scan 20 records only the visible incomplete page-number witness `1`; no `19` is inferred;
- **scan 19 Gemini omission:** Gemini's supplied transcription omits the entire page body. Under the user's explicit missing-paragraph instruction, the scan-19 body was recovered directly from the controlling scan and its page record clearly identifies it as source-recovered rather than Gemini-derived;
- retained Gemini-specific forms in Article 4 include `உணாந்துவிட்டால்`, `வாணனையை`, `விவாதத்தை வளர்த்த முடியாமல்`, and `ஏது மறியாத`;
- Article 1 through Article 4 page layers are complete;
- article assemblies remain **0 / 10** because P3 has not begun;
- P4/P5 and English translation remain **NOT STARTED**.

Source/progress records:

- `publications/unarchchimaalai/README.md`
- `publications/unarchchimaalai/metadata/source.md`
- `publications/unarchchimaalai/indexes/page-map.md`
- `publications/unarchchimaalai/indexes/contents.md`
- `publications/unarchchimaalai/pages/0001-...` through scan-29 page records

---

# Exact next activity

Continue **P2 — page-level transcription, scans 30–38**, completing Article 5 `இங்கல்ல! இரஷ்யாவில்` (scans **30–32**) and Article 6 `3, 57, 90.` (scans **33–38**) as the next coherent page-layer batch.

1. create page records for scans **30–38**;
2. preserve scans 30 and 33 as unnumbered article openings;
3. preserve Article 5 heading `இங்கல்ல! இரஷ்யாவில்` and Article 6 heading `3, 57, 90.` exactly as scan witnesses;
4. retain Gemini word tokens unchanged wherever supplied;
5. restore only scan-supported punctuation, spacing, paragraph breaks, quotation/verse layout and other user-authorised structural features;
6. keep physical-copy marks outside printed text;
7. if Gemini omits a source block, recover it only with explicit source-recovery provenance;
8. update publication README, source metadata and this handover after the batch.

## Current blockers

**None.**