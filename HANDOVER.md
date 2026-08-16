# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover document. Keep updating this file after every meaningful source, translation or review activity. Do not create competing handover files unless the user explicitly requests one.**

## Mandatory startup for future continuation

Before continuing work, read completely:

1. [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
3. this `HANDOVER.md`
4. the active publication's `README.md`
5. the active publication's `TRANSLATION_PLAN.md`
6. `translations/en/README.md`
7. `translations/en/LEXICON.md`
8. `translations/en/TRANSLATION_REVIEW.md`

Then fetch the exact current Tamil article assembly before translating.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. Preserve source-supported historical spelling, punctuation, wording, names, numbers, repetition, unusual grammar and typographical forms.

Distinguish printed text from library stamps, handwriting, accession marks, later annotations, damage and bleed-through.

**Source PDFs are not committed to this repository.**

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands to the reader, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, imagery, exclamations and argumentative rhythm.

Do not turn his prose into detached academic English. Do not soften harsh language. Do not silently replace his chosen labels with modern identifying names. Do not add explanatory claims inside the translated body.

Full policy: [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md).

## Active publication

Workspace: `publications/sakkaravarththiyin-thirumagan/`

Source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

- scans: **83**
- SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- title: `சக்கரவர்த்தியின் திருமகன்`
- author: `கலைஞர் மு.கருணாநிதி`
- source-visible edition: first edition May 1956; supplied reprint 2018
- printed contents: **14 articles**

## Tamil archival status — COMPLETE / FROZEN

### Source layer

- **83 / 83** physical page records complete
- **14 / 14** Tamil article assemblies complete
- source PDF kept outside GitHub

### Strict visual-text-fidelity layer

- **83 / 83** physical scans strict-rechecked
- **14 / 14** Tamil article assemblies strict-rechecked
- **0** unresolved `NEEDS-PIXEL-REVIEW` items
- Tamil source/fidelity completion gate: **PASSED**

Detailed provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/VISUAL_TEXT_FIDELITY_REVIEW.md).

The completed Tamil layer should remain frozen except for explicit source-supported corrections.

## Source-witness distinctions that must not regress

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body phrase: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: **`காரியமாகும் வரையில் காலைப் பிடி !`**.
- Scan 83 is a separate promotional Article 12 witness and must not overwrite the Article 12 body-page witness.

High-value strict corrections include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, source-visible `பரத்துவாஜ...`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, scan-79 heading `காரியமாகும் வரையில் காலைப் பிடி !`, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — ACTIVE

The user has requested English translations of **all 14 articles**, retaining Kalaignar's language and rhetorical force.

Publication-specific plan: [`publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)

English workspace:

- tracker: [`translations/en/README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md)
- living lexicon: [`translations/en/LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md)
- review ledger: [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md)

### Translation progress

- Phase E0 planning/setup: **COMPLETE**
- English article drafts: **0 / 14**
- English articles T2 fidelity-reviewed: **0 / 14**
- English articles T3 voice-reviewed: **0 / 14**
- English articles T4 audited: **0 / 14**
- English articles T5 verified: **0 / 14**
- final cross-article consistency review: **not started**
- English publication release gate: **OPEN**

## Translation gates

Each article must pass:

- **T0** — current strict-reviewed Tamil assembly confirmed and its blob SHA recorded
- **T1** — complete close English draft
- **T2** — bilingual completeness/fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation audit
- **T5** — article marked verified

A first draft must not be called verified merely because it is complete.

## Key translation principles for this publication

- Preserve direct imperatives such as `படியுங்கள்!`, `பாருங்கள்!`, `கேளுங்கள்!` as direct English commands.
- Preserve rhetorical questions instead of summarising them.
- Preserve emphatic repetition instead of editing it as redundancy.
- Preserve sarcasm and ridicule; do not academicise them.
- Preserve source-chosen referential labels. In particular, do not silently replace `ஆச்சாரியார்` with a modern personal name; establish the English rendering from context and record it in the lexicon.
- Translate quoted `கல்கி` passages as quotations and retain dates/citations.
- Preserve `ஆரியர்` / `திராவிடர்` and other ideological vocabulary without neutralising it.
- Do not pre-translate all titles mechanically. Choose each English title after reading the full article.
- Retain source scan/printed-page boundary comments in each English file for bilingual traceability.

## Planning documents created

Phase E0 created:

1. root [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md) — permanent future-work translation policy
2. publication [`TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)
3. English [`README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md) — article status tracker
4. English [`LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md) — living term ledger
5. English [`TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md) — T0–T5 review provenance

The root and publication READMEs now identify the English translation phase as active.

## Exact next activity — Article 1 calibration

Work only on **Article 1 — `சக்கரவர்த்தியின் திருமகன்`**.

1. Fetch the complete current Tamil assembly:
   `publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md`
2. Record its current GitHub blob SHA as T0 provenance.
3. Read the complete article before finalising the English title.
4. Bootstrap actual recurring translation decisions in `translations/en/LEXICON.md` from Article 1 context; do not rely on pre-filled dictionary guesses.
5. Create `translations/en/01-sakkaravarththiyin-thirumagan.md` with the complete English translation and Tamil source page-boundary comments.
6. Perform T2 bilingual fidelity review.
7. Perform T3 Kalaignar-language/voice review.
8. Perform T4 terminology/quotation/citation audit.
9. Record all review corrections in `TRANSLATION_REVIEW.md`.
10. Update `translations/en/README.md`, publication README, root README if counts change, and **this `HANDOVER.md` before ending the activity**.

**Do not begin Article 2 until Article 1 has passed T2 and T3.**
