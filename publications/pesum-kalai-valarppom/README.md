# பேசும் கலை வளர்ப்போம்

Publication 11 in the Kalaignar Essays / Articles archival project.  
Workspace: `publications/pesum-kalai-valarppom/`

## Current gate state

### Tamil archival layer

- P0 — **COMPLETE / PASS**;
- P1 — **COMPLETE / PASS**;
- P2 page-level transcription — **COMPLETE / PASS — 82/82 VERIFIED**;
- P3 assemblies — **COMPLETE / PASS — 19/19**;
- P4 source/completeness audit — **COMPLETE / PASS**;
- P5 strict visual word/punctuation fidelity — **COMPLETE / PASS — 82/82**;
- P5 corrections / propagated — **33/33**;
- unresolved Tamil fidelity discrepancies — **0**;
- Tamil archival layer — **FROZEN**.

### English layer

- E0 planning / workspace bootstrap — **COMPLETE / PASS**;
- T0 frozen-source prerequisite — **19/19 PASS**;
- exact Tamil assembly blob SHAs recorded — **19/19**;
- English article body files — **0/19**;
- T1 / T2 / T3 / T4 / T5 — **0/19**;
- unresolved English blockers — **0**;
- frozen Tamil edits during E0/T0 — **0**.

English controls:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)

## Controlling source

`TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf` — **82** image-only scans, **105,698,402 bytes**, SHA-256 **`73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`**. Source PDF is not committed. Source pixels are Tamil authority.

## Source identity / structure

- scan 1 cover: **`பேசும் கலை வளர்ப்போம்`**;
- scan 3 title page: **`பேசும்கலை வளர்ப்போம்`**;
- supplied edition: **எட்டாம் பதிப்பு — செப்டம்பர் 1996**;
- scan 6 `பதிப்புரை` date: **`15—7—81`**;
- scans 1–2 outside pagination;
- scans 3–82 = pp.1–80;
- source-numbered sections: **19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- no printed contents page or separate back-cover scan.

## Tamil closure

P5 re-read every physical scan directly against its canonical record and closed at **82/82 PASS**, **33/33 corrections propagated**, **0 unresolved**. The detailed correction provenance remains in [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md). Frozen Tamil `pages/` and `articles/` must not be changed for stylistic preference.

## English source baseline

E0/T0 used frozen Tamil baseline commit **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**. All **19** article blobs were enumerated and recorded in `TRANSLATION_PLAN.md` and the English review ledger. Before each draft, the live Tamil blob must match that recorded SHA exactly.

Permanent rule: exact source `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation **`Udanpirappē,`** only where the exact source form occurs.

The source supplies numeric sections only. Do not invent descriptive English section titles.

## Exact next activity

**E1 — Section 1 / T1 voice-calibration draft.** Reconfirm `articles/01-section-01.md` at frozen blob **`e5517b7cc344554d51af4092599059d481039c1e`**, then create `translations/en/01-section-01.md` as a complete paragraph-by-paragraph draft with source-page comments and rhetorical structure preserved. Leave it `draft`; T2–T5 remain separate review gates.