# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **COMPLETE / PASS** | **82/82 VERIFIED**; scans 1–82 contiguous |
| P3 assemblies | **COMPLETE / PASS** | **19/19 source-numbered assemblies**; main work scans 7–82 / pp.5–80 represented |
| P4 source/completeness audit | **COMPLETE / PASS** | **82/82 page records + 19/19 assemblies reconciled; discrepancies 0** |
| P5 strict visual fidelity | **COMPLETE / PASS** | **82/82 PASS; 33 corrections / 33 propagated / 0 unresolved** |
| English E0 workspace/planning | **COMPLETE / PASS** | plan + tracker + lexicon + review ledger initialized |
| English T0 source prerequisite | **COMPLETE / PASS — 19/19** | exact frozen Tamil blob SHAs recorded for every numbered section |
| English T1 close draft | **IN PROGRESS — 1/19** | Section 1 draft complete; English blob `d36aec208ea15b970795a7717dd770d2d27251d8` |
| English T2–T5 | **NOT STARTED — 0/19** | next: Section 1 T2 bilingual fidelity review |

## Source / structure authority

Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`, SHA-256 `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`, 105,698,402 bytes, **82 image-only scans**; source PDF is not committed.

- scan 1 cover: `பேசும் கலை வளர்ப்போம்`;
- scan 3 title page: `பேசும்கலை வளர்ப்போம்`;
- scans 1–2 outside pagination;
- scans 3–82 = printed pp.1–80, `printed page = scan - 2`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- source-numbered sections: **19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- no printed contents page; no separate back-cover scan;
- structural blockers: **0**.

## Tamil P0–P5 — COMPLETE / FROZEN

All **82 physical scans** have canonical page records and all **19** source-numbered assemblies are complete. P5 directly re-read all scans against the source pixels and closed with:

- strict-reviewed — **82/82**;
- source-supported P5 corrections — **33**;
- propagated — **33/33**;
- unresolved fidelity discrepancies — **0**.

Detailed correction provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md). Tamil `pages/` and `articles/` are frozen and must not be changed without genuinely new source evidence.

## English E0 / T0 — COMPLETE / PASS

English setup files:

- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md);
- [`translations/en/README.md`](translations/en/README.md);
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md);
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md).

T0 source baseline:

- frozen Tamil baseline commit — **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**;
- expected / recorded Tamil assemblies — **19 / 19**;
- exact assembly blob SHAs recorded — **19/19**;
- T0 PASS — **19/19**;
- missing / extra source units — **0 / 0**;
- unresolved source-prerequisite blockers — **0**.

## English E1 — Section 1 T1 COMPLETE

- frozen Tamil authority: `articles/01-section-01.md` — **`e5517b7cc344554d51af4092599059d481039c1e`**;
- source span: scans **7–12 / printed pp.5–10**;
- English draft: `translations/en/01-section-01.md` — **`d36aec208ea15b970795a7717dd770d2d27251d8`**;
- `translation_status`: **draft**;
- all six source-page boundary comments retained;
- publication-title draft: **Let Us Develop the Art of Speaking** — provisional until T3;
- T1 lexicon decisions recorded: **11**, all provisional pending later review;
- frozen Tamil changes during E1: **0**;
- unresolved English blockers: **0**.

T1 completion does **not** imply T2/T3/T4/T5 verification.

## English gate totals

| Gate | Complete |
|---|---:|
| T0 | **19/19** |
| T1 | **1/19** |
| T2 | **0/19** |
| T3 | **0/19** |
| T4 | **0/19** |
| T5 | **0/19** |

Permanent rule: exact source `உடன்பிறப்பே` → `Udanpirappē`; direct salutation `Udanpirappē,` only where the exact source form occurs.

## Exact next activity

**E1 — Section 1 / T2 bilingual fidelity review.** Re-read frozen Tamil blob **`e5517b7cc344554d51af4092599059d481039c1e`** against English T1 blob **`d36aec208ea15b970795a7717dd770d2d27251d8`** sentence by sentence and clause by clause. Check omissions/additions, names, dates/numbers, quotations, negatives, comparisons, logical connectors, deliberate repetition, source-witness distinctions and all six page-boundary comments. Record every correction transparently; do not start T3 until T2 passes.