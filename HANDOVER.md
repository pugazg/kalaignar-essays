# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover document. Keep updating this file after every meaningful source, translation or review activity. Do not create competing handover files unless the user explicitly requests one.**

## Mandatory startup for future continuation

Before continuing work, read completely:

1. [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
3. this `HANDOVER.md`
4. the active publication's [`README.md`](publications/sakkaravarththiyin-thirumagan/README.md)
5. its [`TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)
6. [`translations/en/README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md)
7. [`translations/en/LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md)
8. [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md)

Then fetch the exact current Tamil article assembly before translating.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. Preserve source-supported historical spelling, punctuation, wording, names, numbers, repetition, unusual grammar and typographical forms.

**Source PDFs are not committed to this repository.**

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands to the reader, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, imagery, exclamations and argumentative rhythm. Do not turn his prose into detached academic English, soften harsh language, or silently replace his chosen labels with modern identifying names.

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

The completed Tamil layer remains frozen except for explicit source-supported corrections.

## Source-witness distinctions that must not regress

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body phrase: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: `காரியமாகும் வரையில் காலைப் பிடி !`.
- Scan 83 is a separate promotional Article 12 witness and must not overwrite the Article 12 body witness.

High-value Tamil corrections include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, `பரத்துவாஜ...`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, Article-14 title spacing, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — ACTIVE

### Progress

- Phase E0 planning/setup: **COMPLETE**
- Phase E1 Article 1 calibration: **COMPLETE**
- Phase E2 Articles 2–4: **ACTIVE**
- English article drafts: **2 / 14**
- English articles T2 fidelity-reviewed: **2 / 14**
- English articles T3 voice-reviewed: **2 / 14**
- English articles T4 audited: **2 / 14**
- English articles T5 verified: **2 / 14**
- final cross-article consistency review: **not started**
- English publication release gate: **OPEN**

## Translation gates

Each article must pass:

- **T0** — current strict-reviewed Tamil assembly confirmed + blob SHA recorded
- **T1** — complete close English draft
- **T2** — bilingual completeness/fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation audit
- **T5** — article marked verified

## Publication-wide identity and transliteration decision for `ஆச்சாரியார்`

The user explicitly established that **`ஆச்சாரியார்` refers to C. Rajagopalachari (Rajaji)** in this publication.

The user then chose **`Achariyar` instead of `Acharya`**. After confirming that Article 2 also addresses/refers to the same Rajaji referent through `ஆச்சாரியார்`, the user approved using the same form consistently across the publication.

**Frozen rule:**

- `ஆச்சாரியார்` → **`Achariyar`** in Articles **1–14** wherever that Tamil label appears, unless the source itself changes label.
- Articles 1 and 2 have already been revised to `Achariyar` throughout.
- Do not mechanically replace the label with `Rajaji`; the personal identity belongs in translator/editorial identification notes outside Kalaignar's body text.

## Article 1 — COMPLETE / VERIFIED

Tamil: `சக்கரவர்த்தியின் திருமகன்`  
English: **`Chakravarthi's Son`**  
Tamil blob SHA: `47a5b1fd0b28827bb098dda419b5bf864e9f3866`  
English: [`translations/en/01-sakkaravarththiyin-thirumagan.md`](publications/sakkaravarththiyin-thirumagan/translations/en/01-sakkaravarththiyin-thirumagan.md)

Article 1 passed T0–T5 and remains verified after the user-directed transliteration correction.

Decisions that must not regress:

- `ஆச்சாரியார்` → **Achariyar**.
- `சக்கரவர்த்தி` / `சக்கரவர்த்தியார்` → **Chakravarthi** where Rajagopalachari/Chakravarthi wordplay is active.
- `ஆரியர்` / `திராவிடர்` → **Aryans / Dravidians**; `ஆரியம்` → **Aryanism**; `ஆரிய சாம்ராஜ்யம்` → **Aryan Empire**.
- `அரக்கர்` / `ராட்சசர்` / `தேவர்கள்` → **demons / Rakshasas / Devas**, kept distinct.
- `அஸ்வமேதயாகம்` → **Ashvamedha sacrifice**; `தேவபாயசம்` → **divine payasam**; `கற்பு` → **chastity**.
- direct `Read!` / `Look!`, repetitions, sarcasm and harsh polemical language remain visible.
- scan-12 unmatched quotation is documented rather than repaired.

## Article 2 — COMPLETE / VERIFIED

Tamil: `தேகமும் உணர்வும்`  
English: **`Body and Feeling`**  
Tamil blob SHA: `bb9131b7856b528e527136be8f4f60dca2999850`  
English: [`translations/en/02-thegamum-unarvum.md`](publications/sakkaravarththiyin-thirumagan/translations/en/02-thegamum-unarvum.md)

Article 2 passed **T0–T5** and has now been revised post-T5 to use **Achariyar** throughout for `ஆச்சாரியார்`.

Decisions that must not regress:

- `ஆச்சாரியார்` → **Achariyar**.
- `தேகம்` / `உணர்வு` → **body / feeling**.
- `ஊனுடல்` → **body of flesh / bodies of flesh**.
- `கோபதாபம்` / `தாபம்` → **anger and passion / passion**.
- `பகவான்` / `ஈஸ்வரி` → **Bhagavan / Ishvari**.
- `சூழ்ச்சி` → **plot**; explicit `சதி` → **conspiracy** when both are distinguished.
- `பிராமணஜோதி` → **Brahmin luminary**; `பார்ப்பனகுல மகிபர்` → **lord of the Brahmin clan**; `வேதியப் பெருந்தகையார்` → **great Vedic worthy**.
- source `(ஆகஸ்டு 154)` remains **`(August 154)`** with an explicit source note.
- Vamana `மூன்றடி மண்` → **three paces of land**, paired with `two strides`.
- scans 18 and 20 have unmatched quotation openings; the English file documents them rather than silently supplying closing marks.
- final accusation remains **`And Rama too is an accomplice—that is the truth!`**

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md).

## Exact next activity — Article 3

Work only on **Article 3 — `சதி நிரூபிக்கப்படுகிறது`**.

1. Fetch the complete current Tamil assembly:
   `publications/sakkaravarththiyin-thirumagan/articles/03-sathi-nirupikkappadugirathu.md`
2. Record its current GitHub blob SHA as T0 provenance.
3. Read the complete article before choosing/finalising the English title.
4. Apply the Article 1–2 voice/lexicon baseline, including the frozen `ஆச்சாரியார்` → **Achariyar** rule.
5. Create `translations/en/03-sathi-nirupikkappadugirathu.md` with complete English translation and source page-boundary comments.
6. Perform T2 bilingual fidelity review.
7. Perform T3 Kalaignar-language/voice review.
8. Perform T4 terminology/quotation/citation audit.
9. Update `LEXICON.md`, `TRANSLATION_REVIEW.md`, tracker, plan, READMEs and **this `HANDOVER.md`** before ending the activity.

**Do not begin Article 4 until Article 3 has passed T2 and T3.**
