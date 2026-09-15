# NEXT CHAT PROMPT — துடிக்கும் இளமை / Article 1 T0 + T1

Continue directly in `pugazg/kalaignar-essays`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Publication 12 — frozen

`publications/aaru-maatha-kadungkaaval/` remains **RELEASE COMPLETE / FROZEN**.

Do not reopen it merely for stylistic polishing.

## Publication 13 — Tamil frozen / English E0 complete

Workspace:

`publications/thudikkum-ilamai/`

Durable state:

- Tamil P0–P5 — **COMPLETE / PASS**
- Tamil — **COMPLETE / STRICT-REVIEWED / FROZEN**
- English E0 — **COMPLETE / PASS**
- English article body files — **0/4**
- blockers — **0**

Translation plan:

`publications/thudikkum-ilamai/TRANSLATION_PLAN.md`

English tracker:

`publications/thudikkum-ilamai/translations/en/README.md`

Frozen source map:

`publications/thudikkum-ilamai/translations/en/SOURCE_MAP.md`

Living lexicon:

`publications/thudikkum-ilamai/translations/en/LEXICON.md`

Review ledger:

`publications/thudikkum-ilamai/translations/en/TRANSLATION_REVIEW.md`

Permanent policy:

`ESSAY_TRANSLATION_GUIDE.md`

> **Translate the language; do not neutralise the voice.**

## Frozen Tamil authorities

1. `articles/01-thudikkum-ilamai.md` — scans **5–12** — **`3b2f40df8f9b1f02aaac917276b7bcf374185f21`**
2. `articles/02-annamalaikku-arogara.md` — scans **13–19** — **`3740984e52a72b514dff4fc41f54a2938d7ce793`**
3. `articles/03-poompuhar.md` — scans **20–24** — **`9ec5a3fd12e342a92bc02dada6dcf4297214d69d`**
4. `articles/04-vetri-vilakku.md` — scans **25–29** — **`26ce57fe58a5327879155bf41c132180d71dd191`**

Translation order remains **1 → 2 → 3 → 4**.

## Exact activity — Article 1 T0 + T1 only

Article:

**`துடிக்கும் இளமை`**

Frozen Tamil authority:

`publications/thudikkum-ilamai/articles/01-thudikkum-ilamai.md`

Required blob:

**`3b2f40df8f9b1f02aaac917276b7bcf374185f21`**

Source scans:

**5–12**

### T0

Before drafting:

- fetch live `main`;
- fetch the Article-1 Tamil assembly;
- require exact blob SHA match;
- confirm `status: "strict-reviewed"`;
- confirm source scans **5–12**;
- if blob differs, stop and reconcile instead of translating a superseded source.

### T1

Create:

`publications/thudikkum-ilamai/translations/en/01-thudikkum-ilamai.md`

Translate the **entire Article 1** paragraph by paragraph and clause by clause from the frozen Tamil assembly.

Requirements:

- choose a working English title from the source, but keep it provisional until T4;
- metadata must record Tamil title, source Tamil path, frozen Tamil blob, scans **5–12**, language `en`, and `translation_status: "draft"`;
- preserve direct address: `தலைவரே! தாய்மாரே! திராவிட மாணவ மணிகளே!`;
- preserve rhetorical questions as questions;
- preserve repetition of `துடிக்கும் இளமை` / `இளமை துடிக்கிறது` rather than summarising it;
- preserve exclamations, accumulative lists, abrupt contrasts, sarcasm and polemical bite;
- preserve ideological vocabulary: `திராவிடம்`, `திராவிடர்`, `ஆரிய`, `அஹிம்ஸா`, `சமத்துவம்`, `சுயராஜ்யம்`, etc., according to the living lexicon and immediate context;
- do not sanitise harsh religious/caste polemic;
- do not insert present-day distancing language such as “Karunanidhi argues”;
- preserve quotations as quotations;
- do not silently identify source-specific references using outside knowledge;
- preserve complete paragraph coverage;
- add ordered source comments for scans **5, 6, 7, 8, 9, 10, 11, 12** in the form `<!-- Tamil source: scan N -->`;
- no Tamil body paragraph may be omitted;
- no substantive English claim may be added;
- no Tamil source change is allowed.

At T1 close, update:

- `translations/en/README.md`
- `translations/en/LEXICON.md` with choices actually established in Article 1
- `translations/en/TRANSLATION_REVIEW.md`
- `TRANSLATION_PLAN.md`
- publication `README.md`
- publication `audit.md`
- root `HANDOVER.md`
- this prompt

Expected T1 close:

- T0 — **PASS**
- T1 — **COMPLETE / draft**
- English Article-1 file — **1/4**
- source comments — **8/8 ordered**
- omitted Tamil paragraphs/clauses — **0**
- added substantive claims — **0**
- Tamil changes — **0**
- blockers — **0**

## Stop condition

Stop after T1.

**Do not begin T2 bilingual fidelity review unless the user explicitly says to proceed.**
