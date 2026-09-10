# English Translation — பேசும் கலை வளர்ப்போம்

Permanent policy: [`../../../../ESSAY_TRANSLATION_GUIDE.md`](../../../../ESSAY_TRANSLATION_GUIDE.md)  
Publication plan: [`../../TRANSLATION_PLAN.md`](../../TRANSLATION_PLAN.md)

> **Translate the language; do not neutralise the voice.**

## Current status

- Tamil archival prerequisite — **COMPLETE / STRICT-REVIEWED / FROZEN**;
- frozen Tamil assemblies — **19/19**;
- E0 planning / workspace bootstrap — **COMPLETE / PASS**;
- T0 source prerequisite — **19/19 PASS**;
- English article body files — **1/19**;
- T1 close draft — **1/19**;
- T2 bilingual fidelity — **1/19**;
- T3 Kalaignar voice — **1/19**;
- T4 terminology / quotation / citation — **1/19**;
- T5 — **0/19**;
- unresolved English blockers — **0**;
- frozen Tamil edits during English work — **0**.

Frozen baseline commit used for E0/T0: **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**. Exact per-section Tamil blob SHAs are frozen in [`../../TRANSLATION_PLAN.md`](../../TRANSLATION_PLAN.md) and duplicated in [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) for review provenance.

English work must never modify the frozen Tamil `pages/` or `articles/` layers.

## Section tracker

The source supplies numeric sections only. No descriptive English section titles are invented.

| # | Tamil authority | T0 | T1 | T2 | T3 | T4 | T5 | English status |
|---:|---|---|---|---|---|---|---|---|
| 1 | `articles/01-section-01.md` | **PASS** | **PASS** | **PASS** | **PASS** | **PASS** | — | **voice-reviewed** |
| 2 | `articles/02-section-02.md` | **PASS** | — | — | — | — | — | not-started |
| 3 | `articles/03-section-03.md` | **PASS** | — | — | — | — | — | not-started |
| 4 | `articles/04-section-04.md` | **PASS** | — | — | — | — | — | not-started |
| 5 | `articles/05-section-05.md` | **PASS** | — | — | — | — | — | not-started |
| 6 | `articles/06-section-06.md` | **PASS** | — | — | — | — | — | not-started |
| 7 | `articles/07-section-07.md` | **PASS** | — | — | — | — | — | not-started |
| 8 | `articles/08-section-08.md` | **PASS** | — | — | — | — | — | not-started |
| 9 | `articles/09-section-09.md` | **PASS** | — | — | — | — | — | not-started |
| 10 | `articles/10-section-10.md` | **PASS** | — | — | — | — | — | not-started |
| 11 | `articles/11-section-11.md` | **PASS** | — | — | — | — | — | not-started |
| 12 | `articles/12-section-12.md` | **PASS** | — | — | — | — | — | not-started |
| 13 | `articles/13-section-13.md` | **PASS** | — | — | — | — | — | not-started |
| 14 | `articles/14-section-14.md` | **PASS** | — | — | — | — | — | not-started |
| 15 | `articles/15-section-15.md` | **PASS** | — | — | — | — | — | not-started |
| 16 | `articles/16-section-16.md` | **PASS** | — | — | — | — | — | not-started |
| 17 | `articles/17-section-17.md` | **PASS** | — | — | — | — | — | not-started |
| 18 | `articles/18-section-18.md` | **PASS** | — | — | — | — | — | not-started |
| 19 | `articles/19-section-19.md` | **PASS** | — | — | — | — | — | not-started |

## Section 1 authority

- Tamil: `../../articles/01-section-01.md` — **`e5517b7cc344554d51af4092599059d481039c1e`**;
- T1 historical English blob — `d36aec208ea15b970795a7717dd770d2d27251d8`;
- post-T2 English blob — `d185b201c1113d99400d31579e773ae167cbb8a0`;
- post-T3 / post-T4 English blob — **`bede85599ff634ef8ce7d6bd85aa6b9a9e035289`**;
- source span — scans **7–12 / printed pp.5–10**;
- T2 corrections — **6**;
- T3 corrections — **4**;
- T4 body corrections — **0**;
- source-page comments — **6/6 retained**;
- English publication title — **Let Us Develop the Art of Speaking — T4 approved**;
- Section 1 T4-approved lexicon decisions — **16**;
- T5 — **pending**.

The English status remains `voice-reviewed` after T4 because the repository status model advances to `verified` only at T5.

## Binding repository rule

Exact source `உடன்பிறப்பே` → **`Udanpirappē`**; as direct salutation use **`Udanpirappē,`**. Apply only where the exact Tamil source form occurs. Section 1 contains no occurrence.

## Exact next activity

**E1 — Section 1 / T5 article verification.** Reconfirm the frozen Tamil blob `e5517b7cc344554d51af4092599059d481039c1e` and current English blob `bede85599ff634ef8ce7d6bd85aa6b9a9e035289`; reconcile T0–T4 provenance, metadata, source span, all six page-boundary comments, T4-approved lexicon decisions and unresolved counts. If no regression is found, set `translation_status: "verified"`, record the final English blob SHA and mark T5 PASS. Do not start Section 2 in the same activity.