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

English must retain Kalaignar's directness, commands to the reader, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, imagery, exclamations, wordplay and argumentative rhythm. Do not turn his prose into detached academic English, soften harsh language, or silently replace his chosen labels with modern identifying names.

If a pun or source-specific expression cannot be carried naturally, preserve a source-bearing form and use a clearly separated translator/source note. Do not identify an unexplained expression from memory or outside knowledge unless the user explicitly asks for research. Embedded classical verse must be translated only to the sense supported by the supplied Tamil witness and Kalaignar's own explanation unless the user explicitly authorises an external translation.

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
- Phase E2 Articles 2–4: **COMPLETE**
- Phase E3 Articles 5–8: **ACTIVE — Articles 5–6 complete; Article 7 next**
- English article drafts: **6 / 14**
- English articles T2 fidelity-reviewed: **6 / 14**
- English articles T3 voice-reviewed: **6 / 14**
- English articles T4 audited: **6 / 14**
- English articles T5 verified: **6 / 14**
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

The user explicitly established that **`ஆச்சாரியார்` refers to C. Rajagopalachari (Rajaji)** in this publication and chose **`Achariyar` instead of `Acharya`**.

**Frozen rule:**

- `ஆச்சாரியார்` → **`Achariyar`** in Articles **1–14** wherever that Tamil label appears, unless the source itself changes label.
- Articles 1–6 now use `Achariyar` throughout.
- Do not mechanically replace the label with `Rajaji`; the personal identity belongs in translator/editorial identification notes outside Kalaignar's body text.

## Verified articles

1. `சக்கரவர்த்தியின் திருமகன்` → **`Chakravarthi's Son`** — Tamil SHA `47a5b1fd0b28827bb098dda419b5bf864e9f3866`.
2. `தேகமும் உணர்வும்` → **`Body and Feeling`** — Tamil SHA `bb9131b7856b528e527136be8f4f60dca2999850`.
3. `சதி நிரூபிக்கப்படுகிறது` → **`The Conspiracy Is Proven`** — Tamil SHA `903dbb0a2b74bc1ffa173469bfdb3dfa6ce9b4b4`.
4. `காமராஜன் ஆட்கொண்ட தசரதராஜன்!` → **`Dasaratha Raja in the Grip of Kama-Raja!`** — Tamil SHA `9151694c1c473fd4c225aa8076d086e01931bc1e`.
5. `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?` → **`Bharadvaja's Ashram—or a Paris 'Bar'?`** — Tamil SHA `f0b527ed76e10072c5875f0998add33cf09e6647`.
6. `இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா?` → **`Why Did Rama Go to the Forest? A Rishi's Curse? Kaikeyi's Anger?`** — Tamil SHA `07ae8741f3b06fa9208a6478ebabea87d53a93f5`.

Detailed T2–T4 provenance for all six articles lives in [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md).

## Decisions that must not regress

### Articles 1–3

- **Achariyar** is frozen for `ஆச்சாரியார்`.
- **Chakravarthi** preserves the Rajagopalachari/Chakravarthi wordplay where active.
- Aryans / Dravidians / Aryanism, demons / Rakshasas / Devas remain source-distinct.
- body / feeling, body of flesh, anger and passion, Bhagavan / Ishvari, plot / conspiracy remain established.
- Article 3 keeps **burden of the kingdom / burden of rule**, **through the back door**, **taint**, and the rapid Bharata questions.

### Article 4

- `காமராஜன்` → **Kama-Raja** in title and ending; retain the paired **Raja** play.
- `போகம்` → **sensual pleasure**; `பிரகிருதி வேகம்` → **physical urge**; `காம மோகம்` → **lustful infatuation**.
- age-marked `கிழவர்` ridicule must remain age-marked.
- `அப்பாவி` / `அப்-பாவி` → **innocent / “Ah—sinner!”** with separated note.

### Article 5

- Keep the Tamil contents/heading title witnesses distinct.
- English title remains **`Bharadvaja's Ashram—or a Paris 'Bar'?`**.
- Both Kambar passages are sense-translated only from the supplied Tamil plus Kalaignar's own glosses; no external verse translation.
- Keep the scan-33 unmatched quote, standalone scan-36 `—Achariyar.`, **Kothavalai Kozhumandapam**, feast satire, intoxication imagery and final sweet/bitter rhetoric.

### Article 6

English file: [`translations/en/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md`](publications/sakkaravarththiyin-thirumagan/translations/en/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md)

- Title → **`Why Did Rama Go to the Forest? A Rishi's Curse? Kaikeyi's Anger?`**.
- `மூலி அலங்காரி` → **Mooli-Alangari**; source does not explain it, so do not invent an external identification.
- `பிராமணவம்பர்` → **Brahmin Vambar**, preserving the **Kambar / Vambar** sound-play.
- `சூழ்ச்சி` / `சதி` remain **plot / conspiracy**.
- Kaikeyi's youth remains on the **old man's sacrificial altar**.
- Sita's sequence remains: **horoscope / rishi's curse / Kaikeyi's anger / power of fate**.
- Source mixed quotation marks around the Moodevi phrase are documented rather than silently regularised.
- `பழமைக்கு சப்பைக் கட்டு போடும்` → **fastening a splint onto the old order**, reusing the established physical `splint` image.
- Preserve the closing **walk on their feet / On their feet!** repetition; do not smooth it away.
- `ஆரியக்காவல் படைகள்` → **Aryan guard forces**; `வக்காலத்து வாங்கி` → **take up the brief**; final **`ayya, literature!`** cadence remains colloquial and mocking.
- No unresolved meaning-level item remains.

## Permanent guide refinement from Article 6

`ESSAY_TRANSLATION_GUIDE.md` was updated after Article 6 so future works explicitly follow this rule: when Kalaignar uses an unexplained source-specific nickname, coinage, pun or culturally specific reference, prefer a source-bearing transliteration/wordplay-preserving form plus a clearly separated note over an unsupported identification from memory or outside knowledge.

## Exact next activity — Article 7

Work only on **Article 7 — `விபீஷணருக்கு விடை யளிப்போம்!`**.

1. Fetch the complete current Tamil assembly:
   `publications/sakkaravarththiyin-thirumagan/articles/07-vibishanarukku-vidai-yalippom.md`
2. Record its current GitHub blob SHA as T0 provenance.
3. Read the entire article before finalising the English title; determine from the full argument whether `விடை யளிப்போம்` is best carried as **answer**, **reply**, **response**, or another source-faithful English form.
4. Apply the Article 1–6 voice/lexicon baseline, including frozen **Achariyar**.
5. Create `translations/en/07-vibishanarukku-vidai-yalippom.md` with all source page-boundary comments.
6. Complete T2 bilingual fidelity review, T3 Kalaignar-language/voice review and T4 terminology/quotation/citation audit.
7. Update `LEXICON.md`, `TRANSLATION_REVIEW.md`, tracker, plan, READMEs and **this `HANDOVER.md`** before ending the activity.

**Do not begin Article 8 until Article 7 has passed T2 and T3.**
