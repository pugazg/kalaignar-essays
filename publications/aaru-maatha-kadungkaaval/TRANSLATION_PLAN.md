# English Translation Plan — ஆறுமாதக் கடுங்காவல்

Publication: `ஆறுமாதக் கடுங்காவல்`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/aaru-maatha-kadungkaaval/`  
Target language: **English**  
Translation identity: **project-created English translation**

Permanent policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5 — **COMPLETE / PASS**
- physical scans — **224/224**
- canonical page records — **224/224 verified**
- frozen article assemblies — **3/3 PASS**
- unresolved Tamil fidelity discrepancies — **0**
- needs-review / blocked / guessed readings — **0 / 0 / 0**
- P5 canonical corrections — **3**
- P5 historical-glyph correction events — **0**
- Tamil status — **VISUAL-TEXT-FIDELITY COMPLETE / FROZEN**

The three strict-reviewed Tamil assemblies below are the sole translation authorities.

## Frozen Tamil authorities and order

| # | Tamil title | Structural scans | Tamil assembly | Frozen Tamil blob | English title/status |
|---:|---|---:|---|---|---|
| 1 | `முரசு` | 10–65 | `articles/01-murasu.md` | `7a41617cd48f8507bc12074fb48d6016fae5cead` | **The Drum — T0–T5 PASS / VERIFIED** |
| 2 | `களம்` | 66–106 | `articles/02-kalam.md` | `60c155dc93a4543e267ccbca5573d6f5b70e5672` | **title to be established at T1/T4 — not started** |
| 3 | `சிறை` | 108–223 | `articles/03-sirai.md` | `0d860d48bcd666148c0a312ad296953f015225c2` | **title to be established at T1/T4 — not started** |

Translation order is fixed to the source structure: **1 → 2 → 3**.

Scan **224** is the terminal back cover / publisher device and is outside the three English article bodies.

## Source-sensitive Tamil provenance

The frozen Tamil layer includes three P5 source-fidelity corrections:

1. scan 110 — `அந்த வானத்தையும்` → **`அந்தி வானத்தையும்`**
2. scan 121 — `போராட்டத் தலைவர்` → **`போராட்டத் தலைவன்`**
3. scan 159 — `ஜெயில் சூப்பிரின்டெண்டு:` → **`ஜெயில் சூப்பிரின்டெண்ட்:`**

Two source-obscured readings remain valid by explicit user confirmation rather than contextual guessing:

- scan 18 — **`ஆகிவிடக்கூடிய`**
- scan 198 — **`அடைந்தார்`**

English work must translate these frozen Tamil authorities as they stand. Do not reopen or silently normalize them.

## Publication-specific translation principles

In addition to the repository-wide guide:

- preserve the memoir's alternating modes: movement history, battlefield narration, prison recollection, political argument, humour, satire and direct address;
- preserve the rhetorical continuity among the three structural units **முரசு / களம் / சிறை**;
- preserve dates, numbers, slogans, quotations, repeated cries, embedded headings and named political organisations;
- preserve source-chosen labels such as `ஆச்சாரியார்` according to the permanent **Achariyar** rule;
- do not modernise period political terminology merely for smoother English;
- source-specific names and spellings must remain traceable to the frozen Tamil rather than being silently conventionalised from outside knowledge;
- verse / slogans embedded in prose must preserve lineation and rhetorical repetition;
- page-boundary comments must be retained in the English files as `<!-- Tamil source: scan ... -->`;
- scan 224 publisher-device text is source metadata / back-cover matter, not Article 3 English prose.

## English file layout

```text
publications/aaru-maatha-kadungkaaval/
  TRANSLATION_PLAN.md
  translations/
    en/
      README.md
      SOURCE_MAP.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-murasu.md
      02-kalam.md
      03-sirai.md
```

The three article files are created only when their T1 drafts begin.

## Article gates

Each article must pass:

- **T0** — frozen Tamil source prerequisite / blob pin
- **T1** — close paragraph-by-paragraph draft
- **T2** — bilingual fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation audit
- **T5** — article verification

After all 3/3 articles are T5 verified:

- **E6** — publication-wide English consistency review
- **E7** — English release closeout

## E0 planning/setup — COMPLETE / PASS

- repository translation policy reviewed;
- completed-publication conventions reviewed, especially `கொலைக்களம்!`;
- frozen Tamil article blobs pinned — **3/3**;
- canonical translation order fixed — **1 → 2 → 3**;
- `translations/en/README.md`, `SOURCE_MAP.md`, `LEXICON.md`, and `TRANSLATION_REVIEW.md` initialized;
- translation identity recorded as **project-created English translation**;
- English body text created during E0 — **0**;
- blockers — **0**.

## Article 1 progress — `முரசு`

- T0 — **PASS**
- frozen Tamil blob — **`7a41617cd48f8507bc12074fb48d6016fae5cead`**
- source scans — **10–65**
- T1 — **COMPLETE**
- T1 English blob — **`a94630638fa194290e0761259131cc4548d429e4`**
- T2 — **PASS** — 8 body corrections
- T2 English blob — **`ffea867e2163d8a87763bb3fba798d467268da84`**
- T3 — **PASS** — 4 voice corrections
- T3 English blob — **`fcd98ef6c92d14b10f69f0fcda76fe8507e14331`**
- T4 — **PASS** — 1 source-term correction
- T4 body authority — **`bbf4de306e1d0f8442237ee654abbbdb7244d7d5`**
- T5 — **PASS / VERIFIED**
- verified title — **The Drum**
- verified English blob — **`d629c2b13c6d01170bd96bd5e88409a4352f61c5`**
- source comments — **56/56 PASS**
- omitted Tamil clauses — **0**
- added substantive English claims — **0**
- Tamil changes — **0**
- blockers — **0**

## Exact next activity

**Article 2 — `களம்` — T0 source pin + T1 close draft.**

Require frozen Tamil blob `60c155dc93a4543e267ccbca5573d6f5b70e5672`, create `translations/en/02-kalam.md`, establish the working English title, preserve source-page comments, and translate the complete article without altering frozen Tamil.
