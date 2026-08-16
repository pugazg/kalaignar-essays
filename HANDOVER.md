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

- **83 / 83** physical page records complete
- **83 / 83** strict word-level visual checks complete
- **14 / 14** Tamil article assemblies complete and strict-rechecked
- **0** unresolved `NEEDS-PIXEL-REVIEW` items
- Tamil source/fidelity completion gate: **PASSED**
- source PDF kept outside GitHub

The completed Tamil layer should remain frozen except for explicit source-supported corrections.

Detailed source fidelity provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/VISUAL_TEXT_FIDELITY_REVIEW.md).

## Source-witness distinctions that must not regress

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body phrase: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: **`காரியமாகும் வரையில் காலைப் பிடி !`**.
- Scan 83 is a separate promotional Article 12 witness and must not overwrite the Article 12 body-page witness.

High-value Tamil corrections that must not regress include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, source-visible `பரத்துவாஜ...`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, scan-79 heading `காரியமாகும் வரையில் காலைப் பிடி !`, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — ACTIVE

All **14 articles** are to be translated into English while retaining Kalaignar's language and rhetorical force.

Publication plan: [`publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)

English workspace:

- tracker: [`translations/en/README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md)
- living lexicon: [`translations/en/LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md)
- review ledger: [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md)

### Translation progress

- Phase E0 planning/setup: **COMPLETE**
- Phase E1 Article 1 calibration: **COMPLETE**
- Phase E2 Articles 2–4: **ACTIVE**
- English article drafts: **1 / 14**
- English articles T2 fidelity-reviewed: **1 / 14**
- English articles T3 voice-reviewed: **1 / 14**
- English articles T4 audited: **1 / 14**
- English articles T5 verified: **1 / 14**
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

## Article 1 — COMPLETE / VERIFIED

Tamil: **`சக்கரவர்த்தியின் திருமகன்`**  
English: **`Chakravarthi's Son`**  
Tamil source blob SHA: **`47a5b1fd0b28827bb098dda419b5bf864e9f3866`**  
English file: [`translations/en/01-sakkaravarththiyin-thirumagan.md`](publications/sakkaravarththiyin-thirumagan/translations/en/01-sakkaravarththiyin-thirumagan.md)

Article 1 passed **T0–T5**.

### Article 1 decisions that must not regress

- The user explicitly established **`ஆச்சாரியார்` = C. Rajagopalachari (Rajaji)** for this publication.
- Body rendering is now frozen as **`Acharya`**. Do not mechanically substitute `Rajaji` in Kalaignar's body; use the personal identity only in translator/editorial identification notes.
- `சக்கரவர்த்தி` / `சக்கரவர்த்தியார்` → **Chakravarthi** where Kalaignar's Rajagopalachari/Chakravarthi wordplay is active.
- Article 1 title → **Chakravarthi's Son**, rather than flattening the wordplay to `The Emperor's Son`.
- `ஆரியர்` / `திராவிடர்` → **Aryans / Dravidians**.
- `ஆரியம்` → **Aryanism**; `ஆரிய சாம்ராஜ்யம்` → **Aryan Empire**.
- `அரக்கர்` → **demons**; `ராட்சசர்` → **Rakshasas**; `தேவர்கள்` → **Devas**. Keep these lexically distinct when the Tamil does.
- `அஸ்வமேதயாகம்` → **Ashvamedha sacrifice**.
- `தேவபாயசம்` → **divine payasam**.
- `கற்பு` → **chastity**, retaining the source-era moral vocabulary rather than rewriting it.
- `சப்பைக்கட்டு` in the Article 1 Aryanism metaphor is preserved physically as **`fastens a splint onto sagging Aryanism`**.
- `படியுங்கள்!` / `பாருங்கள்!` remain direct **`Read!` / `Look!`** imperatives.
- Repetitions such as **`Ignorance, comrades, ignorance!`**, **`Shame! Shame!`**, **`contradicting himself, contradicting himself`**, and **`will not come true—it certainly will not come true`** must not be edited away.
- The source-visible irregular phrase `எப்படி பெய்ப்படி வளைவான பாதைகளில் போகிறார்` remains untouched in Tamil; Article 1 renders its argumentative force as **`how he takes one crooked path after another`**.
- The scan-12 quotation opens without a visible closing quotation mark. The English file documents that source anomaly instead of silently repairing it.

### Article 1 review corrections

T2 caught and fixed an early draft error that made it sound as though Acharya was following his own `son`; the corrected English now preserves the Tamil relationship: **Murasoli follows Acharya while examining Acharya's/Chakravarthi's `son`**.

T2/T3 also refined `அவதார புருஷன்` to **`an incarnation`**, Amsuman's `சீலமும் அறிவும்` to **`virtue and wisdom`**, and the final `தீயவராக்குகிறார்` to **`makes all the Devas wicked!`** to retain source force.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md).

## Exact next activity — Article 2

Work only on **Article 2 — `தேகமும் உணர்வும்`**.

1. Fetch the complete current Tamil assembly:
   `publications/sakkaravarththiyin-thirumagan/articles/02-thegamum-unarvum.md`
2. Record its current GitHub blob SHA as T0 provenance.
3. Read the complete article before choosing/finalising the English title.
4. Apply the Article 1 lexicon/voice baseline, but document genuine contextual variants instead of forcing mechanical consistency.
5. Create `translations/en/02-thegamum-unarvum.md` with the complete English translation and Tamil source page-boundary comments.
6. Perform T2 bilingual fidelity review.
7. Perform T3 Kalaignar-language/voice review.
8. Perform T4 terminology/quotation/citation audit.
9. Record all corrections/decisions in `TRANSLATION_REVIEW.md` and update `LEXICON.md` as needed.
10. Update `translations/en/README.md`, publication/root README if counts change, `TRANSLATION_PLAN.md`, and **this `HANDOVER.md` before ending the activity**.

**Do not begin Article 3 until Article 2 has passed T2 and T3.**
