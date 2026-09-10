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
- English body files — **1/19**;
- T1 close draft — **1/19**;
- T2 bilingual fidelity — **1/19**;
- T3 Kalaignar voice — **1/19**;
- T4 terminology / quotation / citation — **1/19**;
- T5 — **0/19**;
- unresolved English blockers — **0**;
- frozen Tamil edits during English work — **0**.

Section 1 is **voice-reviewed with T4 PASS**. Tamil authority remains `e5517b7cc344554d51af4092599059d481039c1e`; current English remains **`bede85599ff634ef8ce7d6bd85aa6b9a9e035289`** because T4 required **0** body corrections. T2 made **6** fidelity corrections and T3 made **4** voice corrections.

English controls:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)
- [`translations/en/01-section-01.md`](translations/en/01-section-01.md)

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

P5 closed at **82/82 PASS**, **33/33 corrections propagated**, **0 unresolved**. Frozen Tamil `pages/` and `articles/` must not be changed without genuinely new source evidence.

## Section 1 T4 closure

T4 independently audited all **11** pre-existing Section 1 lexical decisions plus proper names, source labels, both quotations, the Valluvar explanation/chapter label, `1970`, Hyde Park / `(HydePark)`, V. K. Krishna Menon, U.N. Assembly and all six page-boundary comments.

Result:

- T4 — **PASS**;
- English body corrections — **0**;
- post-T4 English blob — **`bede85599ff634ef8ce7d6bd85aa6b9a9e035289`**;
- Section 1 T4-approved lexicon/proper-name/source-label decisions — **16**;
- Bharathidasan quotation — **PASS / source-based**;
- Valluvar quotation + explanation — **PASS / source-based**;
- external published quotation wording imported — **No**;
- source-page comments — **6/6**;
- unresolved T4 issues — **0**;
- frozen Tamil edits — **0**.

The publication title **Let Us Develop the Art of Speaking** is now **T4 approved**. `U.N. Assembly` is retained without unsupported expansion to `U.N. General Assembly`. The source-specific `(HydePark)` parenthetical remains visible at its first occurrence.

Permanent rule: exact source `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation **`Udanpirappē,`** only where the exact source form occurs. Section 1 contains no occurrence. The source supplies numeric sections only; do not invent descriptive English section titles.

## Exact next activity

**E1 — Section 1 / T5 article verification.** Reconfirm frozen Tamil blob `e5517b7cc344554d51af4092599059d481039c1e` and current English blob `bede85599ff634ef8ce7d6bd85aa6b9a9e035289`; reconcile T0–T4 provenance, metadata/status, scans 7–12 / pp.5–10, all six page-boundary comments, T4-approved lexicon state and unresolved counts. If no regression is found, set `translation_status: "verified"`, record the final verified English blob SHA and mark Section 1 T5 PASS. Do not start Section 2 in the same activity.