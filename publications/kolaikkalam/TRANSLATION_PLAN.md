# English Translation Plan — கொலைக்களம்!

Publication: `கொலைக்களம்!`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/kolaikkalam/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## E0 objective — COMPLETE / PASS

Prepare the English translation layer, pin the frozen Tamil authorities, establish article order and working English title witnesses, create the English tracker/lexicon/review records, and define the T0–T5 review sequence.

E0 itself created no English article body. Article 1 has subsequently completed **T0–T5 / VERIFIED**.

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**
- canonical page records: **40 / 40 verified**
- frozen article assemblies: **6 / 6 PASS**
- unresolved Tamil fidelity discrepancies: **0**
- blockers: **0**

The six strict-reviewed Tamil assemblies below are the sole translation authorities.

## Frozen Tamil translation authorities and article order

| # | Exact Tamil title witness | Source scans | Tamil assembly | Frozen Tamil blob | English title | Title status |
|---:|---|---:|---|---|---|---|
| 1 | `கொலைக்களம்!` | `5–9` | `articles/01-kolaikkalam.md` | `bc22ad3acec0bacc70ef69e0fb46f85fa3fed274` | **The Killing Field!** | **verified T4/T5** |
| 2 | `‘அஸ்தி’ கரையட்டும்!` | `10–16` | `articles/02-asthi-karaiyattum.md` | `c7e29e10bc9a7d9d2f0ff9b66bb47d663410bbc5` | **Let the ‘Ashes’ Dissolve!** | provisional |
| 3 | `பலியை நிறுத்துங்கள்!` | `17–22` | `articles/03-paliyai-niruththungal.md` | `e9df22b14e6102c691fe4cc81417eda1051d8f25` | **Stop the Sacrifice!** | provisional |
| 4 | `விழலுக்கு நீர் இறைத்து...` | `23–27` | `articles/04-vizhalukku-neer-iraiththu.md` | `91f764f73c9514b2ce1eefdd94d3a1320a0c228e` | **Watering the Weeds...** | provisional / image-sensitive |
| 5 | `சோதனை!` | `28–33` | `articles/05-sothanai.md` | `3eec6fa58a307cf1b0350a9a26f45a114908a9dd` | **Search!** | provisional / context-sensitive |
| 6 | `வீரமுழக்கஞ் செய்திடுவீர்!` | `34–40` | `articles/06-veeramuzhakkam-seythiduveer.md` | `9e0b9e437a7548ca31ce352ab485b1e342bedb95` | **Raise the Heroic Cry!** | provisional |

The exact Tamil title witness must always remain alongside any English title. Articles 2–6 may be refined during T1–T4 if completed context requires it.

## Frozen-source map

Permanent source pinning is recorded in [`translations/en/SOURCE_MAP.md`](translations/en/SOURCE_MAP.md). Translation must never use the raw `Kolaikalam.md`, OCR, superseded P2/P3 text, web transcriptions, later editions or memory in place of these blobs.

If a genuine source-supported Tamil correction ever changes one of the frozen blobs, every downstream English file based on that blob must be reopened.

## Publication-specific translation principles

In addition to the permanent guide:

- preserve the pamphlet's polemical temperature rather than converting it into detached historical prose;
- preserve direct address, accusation, sarcasm, ridicule, rhetorical questions, commands, repetition and exclamation;
- retain source-bearing ideological vocabulary such as `ஆரியம்`, `திராவிடர்`, `பார்ப்பனீயம்`, `தேசீயம்`, `பகுத்தறிவு`, and related compounds rather than flattening them into generic categories;
- preserve period political labels and source-chosen names/epithets; do not silently substitute modern full names;
- preserve quotation status and quoted labels such as `‘அஸ்தி’`;
- preserve page-boundary comments in every English article for bilingual traceability;
- do not import explanatory historical claims into the body text;
- use translator notes only when materially necessary and only for what the source/repository supports;
- keep the scan-40 printer witness outside Unit 6 English prose.

## Title/term review flags

- `கொலைக்களம்` — **The Killing Field!** verified at Article-1 T4/T5.
- `விழல்` in Unit 4 — working title uses `weeds`; confirm image/idiomatic force during T1/T4 before final verification.
- `சோதனை` in Unit 5 — context includes search/investigation/test senses; working title `Search!` remains provisional.
- `அஸ்தி` — retain its quoted/source-bearing character in Article-2 title/body; do not silently expand beyond what the Tamil supports.
- `மத்ய சர்க்கார்` / `மாகாணம்` — render period political terminology consistently while preserving the historical federal/provincial frame.

## English file structure

```text
publications/kolaikkalam/
  TRANSLATION_PLAN.md
  translations/
    en/
      README.md
      SOURCE_MAP.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-kolaikkalam.md
      02-asthi-karaiyattum.md
      03-paliyai-niruththungal.md
      04-vizhalukku-neer-iraiththu.md
      05-sothanai.md
      06-veeramuzhakkam-seythiduveer.md
```

Article 1 verified file exists; Articles 2–6 remain not started.

## Article gates

Each article must pass, in order:

- **T0 — source prerequisite:** confirm the frozen strict-reviewed Tamil blob and article span;
- **T1 — close draft:** translate the entire article paragraph by paragraph;
- **T2 — bilingual fidelity review:** verify no omission, addition, referent/date/number error or source-witness harmonisation;
- **T3 — Kalaignar voice review:** verify directness, sarcasm, rhetorical structure, repetition and polemical force;
- **T4 — terminology / quotation / citation audit:** reconcile against the living lexicon and source-page trace;
- **T5 — article verification:** mark `verified` only after T1–T4 pass.

After all six articles reach T5, run the repository-precedent publication-wide consistency/release gates before declaring English complete.

## Current English gate status

- E0: **COMPLETE / PASS**
- T0: **1 / 6 PASS**
- T1: **1 / 6 PASS**
- T2: **1 / 6 PASS**
- T3: **1 / 6 PASS**
- T4: **1 / 6 PASS**
- T5: **1 / 6 PASS / VERIFIED**
- English article files: **1 / 6**
- verified English articles: **1 / 6**
- blockers: **0**

Article 1 gate blobs:

- T1 draft: `546a4b075e794237dd6299bcbddc09c17f79583a`;
- T2 fidelity-reviewed: `d0534b8859fed307e7bfb0cfe174281f20418fc4`;
- T3 voice-reviewed: `83de20d819e6c9fe31402576fa277ad8001b08b3`;
- T4 body authority: `83de20d819e6c9fe31402576fa277ad8001b08b3`;
- T5 verified: `c0ca9a883720d51a2637b811b7f38ca1635ba848`.

## Exact next activity

Proceed with **Article 2 — `‘அஸ்தி’ கரையட்டும்!` — T0 source-pin confirmation followed by T1 complete English draft only**, using frozen Tamil blob `c7e29e10bc9a7d9d2f0ff9b66bb47d663410bbc5`. Preserve all ordered source-page comments, quotation status, source-bearing `‘அஸ்தி’`, polemical voice and living-lexicon decisions. Do not begin Article-2 T2 in the same activity unless the user explicitly changes the cadence.
