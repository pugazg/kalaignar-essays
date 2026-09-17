# English Translation Plan — விடுதலைக் கிளர்ச்சி

Publication: `விடுதலைக் கிளர்ச்சி`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/viduthalai-kilarcci/`  
Target language: **English**  
Translation identity: **project-created English translation**

Permanent policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5 — **COMPLETE / PASS**
- physical scans — **69/69 STRICT-REVIEWED**
- canonical page records — **69/69 VERIFIED**
- article assemblies — **2/2 STRICT-REVIEWED / FROZEN**
- contributing article records — **65/65**
- unresolved Tamil fidelity discrepancies — **0**
- unresolved historical-glyph ambiguities — **0**
- guessed readings — **0**
- Tamil status — **COMPLETE / STRICT-REVIEWED / FROZEN**

The two frozen Tamil assemblies below are the sole normal translation authorities.

## Frozen Tamil authorities and order

| # | Tamil title | Structural scans | Tamil assembly | Frozen Tamil blob | English title / status |
|---:|---|---:|---|---|---|
| 0 | `வேங்கையை விரட்டும் படலம்` | 4–7 | `articles/00-vengaiyai-virattum-padalam.md` | `c5be16582c2c3bb238cc1bf1ae47f8301173352f` | **The Chapter of Driving Away the Tiger / T5 VERIFIED** |
| 1 | `விடுதலைக் கிளர்ச்சி` | 8–68 | `articles/01-viduthalai-kilarcci.md` | `ec7b713d6516d75c1f36eb7e86f9ce5788d25036` | **pending T1/T4** |

Translation order is fixed to source structure: **0 → 1**.

Scans **1–3** are cover / reverse / imprint matter. Scan **69** is publisher catalogue matter. These ranges do not belong to English article bodies.

Expected ordered Tamil-source boundary comments in complete English article translations:

- Article 0 — scans 4–7 — **4**
- Article 1 — scans 8–68 — **61**
- total — **65**

The frozen Tamil reading assemblies do not carry inline scan comments. During T1, source-boundary comments must therefore be inserted from the verified canonical page/provenance layer without changing Tamil wording.

## Durable Tamil provenance relevant to translation

Do not regress these frozen source controls:

- introductory unit title — **`வேங்கையை விரட்டும் படலம்`**;
- scan 3 printer — **`கலைமகள் பிரஸ், பெரியகடைவீதி, திருச்சி.`**;
- scan 14 — **`இந்தோ சீனாவில்!`**;
- scan 31 — **`வெற்றிபெற்ற நாடுகளின் வழிகாட்டியாகக் கொண்டு`**;
- scan 32 — **`உ. வெ. சாமிநாத அய்யர்`**;
- scan 39 — **`இருந்தாலும்,`** and **`பாரதமணித்திருநாடு!`**;
- scan 43 — **`சொல்லப் போகிறது`**;
- scan 46 — **`முடிந்து விடக் கூடியதல்லவே`**;
- scan 55 — **`ரஷ்யா நிற்கிறது—ஆகவேதான்`**;
- scan 60 — **`அணுகுண்டு`**;
- scan 60→61 — **`நாடக / மேடை`**;
- scan 64→65 — **`நடத்தியவர் / களை`**;
- scan 68 closes the prose work with **`இதுதான் வேறுபாடு. தேவையான துங்கூட!`** and a printed star;
- scan 69 catalogue is outside article bodies.

All P5 old→source-visible corrections are controlled by `VISUAL_TEXT_FIDELITY_REVIEW.md` and the canonical page records.

## Publication-specific translation principles

In addition to the repository-wide guide:

- preserve the mother-cow / tiger analogy in Article 0 without turning it into explanatory commentary;
- preserve the repeated rhetorical force of `விடுதலை` and `கிளர்ச்சி`; do not mechanically force one English equivalent where context changes the sense;
- preserve direct political address, rhetorical questions, exclamations, repetition, satire, ridicule and abrupt contrasts;
- preserve source-chosen labels such as `திராவிடம்`, `திராவிடர்`, `ஆரியர்`, organisation names, epithets and movement vocabulary; do not replace them with broader modern categories;
- preserve source geographic and historical naming rather than silently modernising it; publication-specific forms such as `இந்தோ சீனா` must remain source-bearing;
- preserve quotation scope and source-visible slogans; do not import published translations of quoted material;
- preserve literary references such as `புறநானூறு`, `சேரன் செங்குட்டுவன்`, `பரமசிவன்`, `கண்ணபிரான்` and `ஆரிய மாயை` without adding outside explanation inside the body;
- preserve source political comparisons and accusations as translation, without adding present-day claims or translator agreement;
- use verified page records / scans only when needed to resolve punctuation, page boundaries, quotation scope or source-witness questions;
- retain page-boundary comments in English as `<!-- Tamil source: scan ... -->`.

## English file layout

```text
publications/viduthalai-kilarcci/
  TRANSLATION_PLAN.md
  translations/
    en/
      README.md
      SOURCE_MAP.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      00-vengaiyai-virattum-padalam.md
      01-viduthalai-kilarcci.md
```

Article body files are created only when their T1 drafts begin.

## Article gates

Each article must pass:

- **T0** — frozen Tamil source prerequisite / blob pin
- **T1** — close paragraph-by-paragraph draft
- **T2** — bilingual fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation audit
- **T5** — article verification

After both articles are T5 verified:

- **E6** — publication-wide English consistency review
- **E7** — English release closeout

## E0 planning/setup — COMPLETE / PASS

Date: **2026-09-17**

- permanent repository translation policy reviewed;
- frozen Tamil article blobs pinned — **2/2**;
- canonical translation order fixed — **0 → 1**;
- scans **1–3** excluded from English article bodies;
- scan **69** excluded from English article bodies;
- expected ordered source comments fixed — **65**;
- `translations/en/README.md`, `SOURCE_MAP.md`, `LEXICON.md`, and `TRANSLATION_REVIEW.md` initialized;
- translation identity recorded as **project-created English translation**;
- English article body files created during E0 — **0/2**;
- English body prose created during E0 — **0**;
- Tamil source changes during E0 — **0**;
- blockers — **0**.

## Article 0 — `வேங்கையை விரட்டும் படலம்` — T0–T5 COMPLETE / VERIFIED

- T0 frozen Tamil source-pin revalidation — **PASS**
- T1 close English draft — **COMPLETE** — blob `02b3f03c2f6b3c91d040064297645bbfb3659929`
- T2 bilingual fidelity review — **PASS** — blob `535be98ee158f6b697591afd982aede24b46fc6e`
- T3 Kalaignar voice review — **PASS** — blob `36aab78e955117f4fefe14759ca8dac46bac99a5`
- T4 terminology / quotation / citation audit — **PASS** — blob `7ee1a711aff55b99c1047f204cf837395f279077`
- T5 final verification — **PASS / VERIFIED**
- verified English title — **The Chapter of Driving Away the Tiger**
- verified English blob — **`67c942bb8e1a631379834fe9757f5378085ccb58`**
- ordered source comments — **4/4 PASS**
- untranslated Tamil body leakage — **0**
- omitted Tamil clauses after review — **0**
- added substantive English claims — **0**
- Tamil source changes — **0**
- blockers — **0**

## Exact next activity

**Article 1 — `விடுதலைக் கிளர்ச்சி` — T0 source-pin revalidation → T1 complete English draft.**
