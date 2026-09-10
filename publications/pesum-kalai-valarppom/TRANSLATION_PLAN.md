# English Translation Plan — பேசும் கலை வளர்ப்போம்

Publication: `publications/pesum-kalai-valarppom/`  
Permanent policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Frozen Tamil prerequisite

- Tamil P0–P5 — **COMPLETE / PASS / FROZEN**;
- canonical page records — **82/82 VERIFIED**;
- numbered Tamil assemblies — **19/19 source-complete**;
- P5 strict visual fidelity — **82/82 PASS**;
- P5 corrections — **33/33 propagated**;
- unresolved Tamil source/fidelity blockers — **0**;
- frozen baseline commit used for E0/T0 — **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**.

English work must never alter the frozen Tamil authority. If genuinely new source evidence later changes Tamil, every affected English gate must be reopened explicitly.

## E0 / T0 source matrix

All 19 strict-reviewed Tamil assemblies were enumerated directly from the frozen baseline and their exact Git blob SHAs recorded below. **T0 is PASS for all 19.**

| # | Frozen Tamil assembly | Scans / printed pages | Frozen Tamil blob SHA | T0 |
|---:|---|---|---|---|
| 1 | `articles/01-section-01.md` | 7–12 / 5–10 | `e5517b7cc344554d51af4092599059d481039c1e` | **PASS** |
| 2 | `articles/02-section-02.md` | 12–16 / 10–14 | `b10894b911393239e57446687c34030aff88a8e3` | **PASS** |
| 3 | `articles/03-section-03.md` | 16–22 / 14–20 | `21904dd457bb3455230de06421ff2d906ac4958d` | **PASS** |
| 4 | `articles/04-section-04.md` | 22–27 / 20–25 | `b938be21e198d69548e45ae96cb0e9802b8d7079` | **PASS** |
| 5 | `articles/05-section-05.md` | 27–31 / 25–29 | `7fbb055e1f7f2630d39f5a3e203de5e2547b93b9` | **PASS** |
| 6 | `articles/06-section-06.md` | 31–34 / 29–32 | `7303356861196c1d98951c651c38c42b4d07ac90` | **PASS** |
| 7 | `articles/07-section-07.md` | 34–38 / 32–36 | `722e66535b9c1503f574e0adf8362e6b2c020653` | **PASS** |
| 8 | `articles/08-section-08.md` | 38–41 / 36–39 | `1bfc1752ccc8217e14fe527cd49ab0362d4484a0` | **PASS** |
| 9 | `articles/09-section-09.md` | 42–44 / 40–42 | `d0e18d25b0e3ae4a8585d8fa117d07f118dabf5c` | **PASS** |
| 10 | `articles/10-section-10.md` | 45–47 / 43–45 | `32dd5cf5bf4ec73e9c0cdb4c0f1eeead2f3a7055` | **PASS** |
| 11 | `articles/11-section-11.md` | 48–51 / 46–49 | `427a9ef35cd8ff1ffd873d5d2c9afccdcb7b2375` | **PASS** |
| 12 | `articles/12-section-12.md` | 51–55 / 49–53 | `91f08b6cf0de84cc3a1b58120b1702d355f4c683` | **PASS** |
| 13 | `articles/13-section-13.md` | 55–58 / 53–56 | `97dd9dc2f5ae10828ff68095ca87dd2cb484e745` | **PASS** |
| 14 | `articles/14-section-14.md` | 59–63 / 57–61 | `4c611fa7a2b6d91bfa4c767bfdb8c9fcfff8316c` | **PASS** |
| 15 | `articles/15-section-15.md` | 64–67 / 62–65 | `682c68cdc0db1899749f2943c9d311ecb1061eb8` | **PASS** |
| 16 | `articles/16-section-16.md` | 67–70 / 65–68 | `1ab092b3b7bcdc0efd23f08e49799e7c3fda8d5f` | **PASS** |
| 17 | `articles/17-section-17.md` | 70–74 / 68–72 | `bd4cb1d4e631e19de0e5cc62f0aecf176d7e2fe2` | **PASS** |
| 18 | `articles/18-section-18.md` | 75–79 / 73–77 | `060e72d9ec61e491343c948c2db9371312b7e3a8` | **PASS** |
| 19 | `articles/19-section-19.md` | 79–82 / 77–80 | `aa3eb2b5311f8ad1a705f606bd4ace3f2059ec6c` | **PASS** |

These SHAs are the source authority to record in each future English article's `source_tamil_blob_sha` metadata. Before writing an English article, re-check that its live Tamil blob still equals the recorded frozen SHA. Any mismatch is a hard stop until reconciled.

## English workspace

Required controls:

- `translations/en/README.md` — progress tracker;
- `translations/en/LEXICON.md` — living terminology decisions;
- `translations/en/TRANSLATION_REVIEW.md` — T0–T5 provenance and corrections;
- future body files `translations/en/01-section-01.md` through `19-section-19.md`.

The source has only numbered sections. Do **not** invent descriptive English section titles. A publication-level English title is not frozen during E0; establish it deliberately during the first T1/T3 calibration rather than guessing now.

## Translation gates per section

1. **T0 — source prerequisite:** frozen Tamil blob matches this matrix.
2. **T1 — close draft:** translate every Tamil paragraph; preserve quotation structure, repetitions, rhetorical force and source-page comments.
3. **T2 — bilingual fidelity:** check omissions, additions, logic, numbers, names, quotations and source-witness distinctions.
4. **T3 — Kalaignar voice:** ensure directness, irony, polemical force, commands, questions and cadence were not softened.
5. **T4 — terminology / quotation / citation:** update the living lexicon and audit names, source-bearing terms and quotations.
6. **T5 — verification:** only after T1–T4 pass may the section be marked `verified`.

## Binding translation rules at startup

- exact source `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation **`Udanpirappē,`**;
- translate source text, not remembered or modernized wording;
- preserve numbered section identity `1`–`19`;
- preserve source-page boundary comments for bilingual traceability;
- do not soften polemics or replace source-chosen labels with modern explanatory names in body text;
- do not import published English translations unless separately authorized.

## Voice-calibration rule

Section 1 is the first calibration unit. Complete its T1 draft and then T2/T3/T4/T5 review before accelerating across later sections. Use decisions established there to seed the publication lexicon, but do not force them mechanically where later context differs.

## Current English state

- E0 workspace/planning — **COMPLETE / PASS**;
- T0 frozen-source prerequisites — **19/19 PASS**;
- English body files — **0/19**;
- T1 / T2 / T3 / T4 / T5 — **0/19** at each gate;
- unresolved English blockers — **0**;
- frozen Tamil changes during English startup — **0**.

## Exact next activity

**E1 — Section 1 / T1 voice-calibration draft.** Reconfirm `articles/01-section-01.md` is still blob `e5517b7cc344554d51af4092599059d481039c1e`, then translate it paragraph by paragraph into `translations/en/01-section-01.md`. Preserve all source-page comments and rhetorical structure. Do not mark it verified until T2–T5 are separately completed.