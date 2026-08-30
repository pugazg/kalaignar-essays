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

# Exact next activity

Publications 1 and 2 are both **COMPLETE / FROZEN / RELEASED**.

The exact next normal activity is **P0 intake of the next supplied Kalaignar essay/article publication**:

1. obtain/attach the next controlling source PDF;
2. fetch live `main` first;
3. read `ESSAY_PROCESSING_GUIDE.md`, `docs/FUTURE_WORK_GUIDELINES.md`, this `HANDOVER.md`, and the future-publication handover template;
4. inspect the source directly before creating the new publication workspace;
5. register source identity, SHA-256, physical scan count, publication metadata and initial structure conservatively;
6. do not infer or normalise unreadable Tamil; scan pixels control;
7. do not start English translation until the new Tamil source layer reaches its required frozen state.

## Current blockers

**None.**