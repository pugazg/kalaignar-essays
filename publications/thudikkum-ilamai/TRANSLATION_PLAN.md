# English Translation Plan — துடிக்கும் இளமை

Publication: `துடிக்கும் இளமை`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/thudikkum-ilamai/`  
Target language: **English**  
Translation identity: **project-created English translation**

Permanent policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5 — **COMPLETE / PASS**
- physical scans — **33/33**
- canonical page records — **33/33 verified**
- frozen article assemblies — **4/4 PASS**
- unresolved Tamil fidelity discrepancies — **0**
- needs-review / blocked / guessed readings — **0 / 0 / 0**
- P5 canonical text corrections — **0**
- P5 historical-glyph correction events — **0**
- Tamil status — **COMPLETE / STRICT-REVIEWED / FROZEN**

The four strict-reviewed Tamil assemblies below are the sole normal translation authorities.

## Frozen Tamil authorities and order

| # | Tamil title | Structural scans | Tamil assembly | Frozen Tamil blob | English title/status |
|---:|---|---:|---|---|---|
| 1 | `துடிக்கும் இளமை` | 5–12 | `articles/01-thudikkum-ilamai.md` | `3b2f40df8f9b1f02aaac917276b7bcf374185f21` | title **TBD** / not started |
| 2 | `அண்ணாமலைக்கு அரோகரா!` | 13–19 | `articles/02-annamalaikku-arogara.md` | `3740984e52a72b514dff4fc41f54a2938d7ce793` | title **TBD** / not started |
| 3 | `பூம்புகார்` | 20–24 | `articles/03-poompuhar.md` | `9ec5a3fd12e342a92bc02dada6dcf4297214d69d` | title **TBD** / not started |
| 4 | `வெற்றி விளக்கு!` | 25–29 | `articles/04-vetri-vilakku.md` | `26ce57fe58a5327879155bf41c132180d71dd191` | title **TBD** / not started |

Translation order is fixed to source structure: **1 → 2 → 3 → 4**.

Scans **1–4** are front matter. Scans **30–33** are advertisements / promotional matter. Neither range belongs to an English article body.

## Durable Tamil provenance relevant to translation

Do not regress the following frozen readings:

- scan 2 price — **`ஆறணா`**;
- scan 3 date — **`16—12—'51`**;
- scan 4 — **`எழுச்சியூட்டும் எழுத்தோவியங்களே`**;
- scan 9 — **`விந்தை`**;
- scan 10 — **`உ.வே.சாமிநாத அய்யர்`**;
- scan 13 title — **`அண்ணாமலைக்கு அரோகரா!`**;
- scan 27 — **`அரசாங்கம்`**.

The retired readings `ஆறணை` and `அண்ணனுக்கு அரசா!` are correction-history only and are not translation authority.

## Publication-specific translation principles

In addition to the repository-wide guide:

- preserve the youthful polemical heat, ridicule, direct address and repeated rhetorical questions;
- do not turn the anti-caste / anti-religious polemic into detached academic prose;
- preserve ideological vocabulary such as `திராவிடம்`, `திராவிடர்`, `ஆரிய` / `ஆரியர்`, and `பகுத்தறிவு` without neutralising it;
- preserve explicit labels, insults and mythological references chosen by the source;
- do not insert modern explanatory identifications for source-specific people, epithets or references unless the Tamil itself supplies them;
- in Article 2, preserve the chant/heading `அரோகரா` as a source-bearing form until T4 settles its final English treatment;
- in Article 3, preserve quotation status and lineation of the Silappathikaram verse across scans 23–24; do not import a published English translation;
- in Article 3, titles/names such as `கம்பராமாயணம்`, `சிலப்பதிகாரம்`, `திருக்குறள்`, `கம்பன்`, `இளங்கோவடிகள்` must remain traceable to source choices;
- in Article 4, preserve the accumulative martyr/reformer rhetoric, sarcasm and repeated contrast between superstition and reform;
- normal English spacing may replace purely typographic Tamil spacing, but rhetorical punctuation, repetition and paragraph structure must remain visible;
- source-page traceability comments must be retained in English article files.

## English file layout

```text
publications/thudikkum-ilamai/
  TRANSLATION_PLAN.md
  translations/
    en/
      README.md
      SOURCE_MAP.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-thudikkum-ilamai.md       # created at T1, not E0
      02-annamalaikku-arogara.md   # created at T1, not E0
      03-poompuhar.md               # created at T1, not E0
      04-vetri-vilakku.md           # created at T1, not E0
```

## Article gates

Each article must pass:

- **T0** — frozen Tamil source prerequisite / blob pin
- **T1** — complete close paragraph-by-paragraph English draft
- **T2** — bilingual fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation audit
- **T5** — article verification

After all **4/4** articles are T5 verified:

- **E6** — publication-wide English consistency review
- **E7** — English release closeout

## E0 planning/setup — COMPLETE / PASS

- repository translation policy reviewed;
- frozen Tamil article blobs pinned — **4/4**;
- canonical translation order fixed — **1 → 2 → 3 → 4**;
- front matter / advertisement exclusion from English article bodies recorded;
- `translations/en/README.md`, `SOURCE_MAP.md`, `LEXICON.md`, and `TRANSLATION_REVIEW.md` initialized;
- translation identity recorded as **project-created English translation**;
- English article body files created during E0 — **0/4**;
- English body prose created during E0 — **0**;
- Tamil source changes during E0 — **0**;
- blockers — **0**.

## Exact next activity

**Article 1 `துடிக்கும் இளமை` — T0 source-pin revalidation + T1 close English draft.**

Before drafting, refetch live `main` and confirm frozen Tamil blob **`3b2f40df8f9b1f02aaac917276b7bcf374185f21`** exactly.

Do not advance to T2 in the same activity unless the user explicitly asks.
