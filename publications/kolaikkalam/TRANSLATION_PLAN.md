# English Translation Plan — கொலைக்களம்!

Publication: `கொலைக்களம்!`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/kolaikkalam/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## E0 objective — COMPLETE / PASS

Prepare the English translation layer without beginning article translation. Pin the frozen Tamil authorities, establish article order and working English title witnesses, create the English tracker/lexicon/review records, and define the T0–T5 review sequence.

No English body paragraph has been translated during E0.

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**
- canonical page records: **40 / 40 verified**
- frozen article assemblies: **6 / 6 PASS**
- unresolved Tamil fidelity discrepancies: **0**
- blockers: **0**

The six strict-reviewed Tamil assemblies below are the sole translation authorities.

## Frozen Tamil translation authorities and article order

| # | Exact Tamil title witness | Source scans | Tamil assembly | Frozen Tamil blob | Working English title | Title status |
|---:|---|---:|---|---|---|---|
| 1 | `கொலைக்களம்!` | `5–9` | `articles/01-kolaikkalam.md` | `bc22ad3acec0bacc70ef69e0fb46f85fa3fed274` | **The Killing Field!** | provisional |
| 2 | `‘அஸ்தி’ கரையட்டும்!` | `10–16` | `articles/02-asthi-karaiyattum.md` | `c7e29e10bc9a7d9d2f0ff9b66bb47d663410bbc5` | **Let the ‘Ashes’ Dissolve!** | provisional |
| 3 | `பலியை நிறுத்துங்கள்!` | `17–22` | `articles/03-paliyai-niruththungal.md` | `e9df22b14e6102c691fe4cc81417eda1051d8f25` | **Stop the Sacrifice!** | provisional |
| 4 | `விழலுக்கு நீர் இறைத்து...` | `23–27` | `articles/04-vizhalukku-neer-iraiththu.md` | `91f764f73c9514b2ce1eefdd94d3a1320a0c228e` | **Watering the Weeds...** | provisional / image-sensitive |
| 5 | `சோதனை!` | `28–33` | `articles/05-sothanai.md` | `3eec6fa58a307cf1b0350a9a26f45a114908a9dd` | **Search!** | provisional / context-sensitive |
| 6 | `வீரமுழக்கஞ் செய்திடுவீர்!` | `34–40` | `articles/06-veeramuzhakkam-seythiduveer.md` | `9e0b9e437a7548ca31ce352ab485b1e342bedb95` | **Raise the Heroic Cry!** | provisional |

The working English titles are planning witnesses only. They may be refined during T1–T4 if the completed article context shows that another rendering better preserves the Tamil title's rhetorical action. The exact Tamil title witness must always remain alongside any English title.

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

## Initial title/term review flags

The following require deliberate review rather than automatic dictionary substitution:

- `கொலைக்களம்` — working title `The Killing Field`; retain the violent field/arena image.
- `விழல்` in Unit 4 — working title uses `weeds`; confirm the image and idiomatic force during T1/T4 before final title verification.
- `சோதனை` in Unit 5 — context includes search/investigation/test senses; working title `Search!` is provisional and contextual renderings may differ inside the article.
- `அஸ்தி` — retain its quoted/source-bearing character in the title; do not silently expand it beyond what the Tamil supports.
- `மத்ய சர்க்கார்` / `மாகாணம்` — render period political terminology consistently while preserving the historical federal/provincial frame.

## English file structure

Use:

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

No article translation files are created during E0.

## Article gates

Each article must pass, in order:

- **T0 — source prerequisite:** confirm the frozen strict-reviewed Tamil blob and article span;
- **T1 — close draft:** translate the entire article paragraph by paragraph;
- **T2 — bilingual fidelity review:** verify no omission, addition, referent/date/number error or source-witness harmonisation;
- **T3 — Kalaignar voice review:** verify directness, sarcasm, rhetorical structure, repetition and polemical force;
- **T4 — terminology / quotation / citation audit:** reconcile against the living lexicon and source-page trace;
- **T5 — article verification:** mark `verified` only after T1–T4 pass.

After all six articles reach T5, run the repository-precedent publication-wide consistency/release gates before declaring English complete.

## E0 status

- E0: **COMPLETE / PASS**
- T0: **0 / 6**
- T1: **0 / 6**
- T2: **0 / 6**
- T3: **0 / 6**
- T4: **0 / 6**
- T5: **0 / 6**
- English article files: **0 / 6**
- blockers: **0**

## Exact next activity

Proceed with **Article 1 — `கொலைக்களம்!` — T0 source pin confirmation, then T1 close English draft** from frozen Tamil blob `bc22ad3acec0bacc70ef69e0fb46f85fa3fed274` only. Preserve source-page comments and update the living lexicon/review ledger while translating.
