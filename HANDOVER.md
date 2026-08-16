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

If a pun cannot be carried naturally in English, preserve the source-bearing form in the translation and use a clearly separated translator note rather than rewriting Kalaignar's body. Embedded classical verse must be translated only to the sense supported by the supplied Tamil witness and Kalaignar's own explanation unless the user explicitly authorises an external translation.

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
- Phase E3 Articles 5–8: **ACTIVE — Article 5 complete; Article 6 next**
- English article drafts: **5 / 14**
- English articles T2 fidelity-reviewed: **5 / 14**
- English articles T3 voice-reviewed: **5 / 14**
- English articles T4 audited: **5 / 14**
- English articles T5 verified: **5 / 14**
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
- Articles 1–5 now use `Achariyar` throughout.
- Do not mechanically replace the label with `Rajaji`; the personal identity belongs in translator/editorial identification notes outside Kalaignar's body text.

## Verified articles

### Article 1 — COMPLETE / VERIFIED

Tamil: `சக்கரவர்த்தியின் திருமகன்`  
English: **`Chakravarthi's Son`**  
Tamil blob SHA: `47a5b1fd0b28827bb098dda419b5bf864e9f3866`

Key decisions: **Achariyar**, **Chakravarthi** where wordplay is active, Aryans / Dravidians / Aryanism, source-distinct demons / Rakshasas / Devas, Ashvamedha sacrifice, divine payasam, chastity, direct `Read!` / `Look!`, repetitions and sarcasm. Scan-12 unmatched quotation is documented rather than repaired.

### Article 2 — COMPLETE / VERIFIED

Tamil: `தேகமும் உணர்வும்`  
English: **`Body and Feeling`**  
Tamil blob SHA: `bb9131b7856b528e527136be8f4f60dca2999850`

Key decisions: **Achariyar**; body / feeling; body of flesh; anger and passion; Bhagavan / Ishvari; plot / conspiracy; polemical caste epithets retained; source `(August 154)` preserved; Vamana `three paces of land`; scans 18 and 20 unmatched quotations documented.

### Article 3 — COMPLETE / VERIFIED

Tamil: `சதி நிரூபிக்கப்படுகிறது`  
English: **`The Conspiracy Is Proven`**  
Tamil blob SHA: `903dbb0a2b74bc1ffa173469bfdb3dfa6ce9b4b4`

Key decisions: burden of the kingdom / burden of rule; office of Crown Prince; Vishnu-share contradiction retained; rapid Bharata questions retained; `கொல்லைப்புறமாக...` → **through the back door**; `கல்மஷம்` → **taint**; final **`Why only us? Everyone with a brain...`** cadence retained.

### Article 4 — COMPLETE / VERIFIED

Tamil: `காமராஜன் ஆட்கொண்ட தசரதராஜன்!`  
English: **`Dasaratha Raja in the Grip of Kama-Raja!`**  
Tamil blob SHA: `9151694c1c473fd4c225aa8076d086e01931bc1e`

Key decisions: **Kama-Raja / Raja** title-to-ending wordplay retained; `போகம்` → **sensual pleasure**; `பிரகிருதி வேகம்` → **physical urge**; `காதல் வேகம்` → **surge of passion**; `காம மோகம்` → **lustful infatuation**; repeated `கிழவர்` ridicule remains age-marked; `அப்பாவி` / `அப்-பாவி` → **innocent / “Ah—sinner!”** with separated translator note; dates 8 and 22 August 1954 preserved.

### Article 5 — COMPLETE / VERIFIED

Tamil: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`  
English: **`Bharadvaja's Ashram—or a Paris 'Bar'?`**  
Tamil blob SHA: `f0b527ed76e10072c5875f0998add33cf09e6647`  
English: [`translations/en/05-paraththuvaja-aasramama-paris-nagarathu-para.md`](publications/sakkaravarththiyin-thirumagan/translations/en/05-paraththuvaja-aasramama-paris-nagarathu-para.md)

Article 5 passed **T0–T5**.

Decisions that must not regress:

- Keep the Tamil source-witness distinction explicit: contents `பரத்துவாஜர் ... பாரீஸ் ...`; heading `பரத்துவாஜா ... பாரிஸ் ...`.
- English title → **Bharadvaja's Ashram—or a Paris 'Bar'?**; `‘பாரா’?` is treated as the source's **bar + Tamil interrogative** wordplay.
- `ஆச்சாரியார்` → **Achariyar** throughout.
- Opening/closing refrain remains clipped and rhetorical: **`An ashram—and Apsaras there?`**, **`faces swollen from kisses?`**, **`pleasure beyond all bounds?`**.
- `அனலிடைப் புழு` → **a worm in fire**.
- First Kambar boat verse is translated only to the sense supported by Kalaignar's prose gloss; T2 corrected draft `hidden beauty` to **hidden parts** to avoid beautifying the source.
- Scan-33 Achariyar quotation has **no visible closing quotation mark** before Kalaignar resumes; English documents the unmatched opening rather than repairing it.
- `கதம்ப ராமன்` → **motley Rama**; `காலட்சேபம்` → **religious discourse**; mud/floundering image retained.
- Bharadvaja-feast satire preserves Arya Bhavan comparison, American-government comparison, triple **Ah! Ah! Ah!**, four-item word pile-up, and intoxication imagery.
- Source-specific `கொத்தவாலை கொழுமண்டபம்` is conservatively **Kothavalai Kozhumandapam**; do not externally normalise it without user direction.
- Standalone scan-36 `— ஆச்சாரியார்.` is retained as **`—Achariyar.`**.
- Second Kambar verse is translated only from the Tamil witness plus Kalaignar's own prose gloss.
- `வேதியப் பெருங்கிழவர்` → **grand old Vedic man**; `பார்ப்பன குலமகிபர்` retains **lord of the Brahmin clan**.
- Final sweet/bitter taste rhetoric remains direct.

T2 corrections recorded in the review ledger include fixing the self-referential Bharata draft, restoring the scan-33 unclosed quote, changing `hidden beauty` to **hidden parts**, retaining `போடுகிறவன் போட்டாலும்` closely, and restoring the standalone scan-36 `—Achariyar.`. No unresolved meaning-level item remains.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md).

## Exact next activity — Article 6

Work only on **Article 6 — `இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா?`**.

1. Fetch the complete current Tamil assembly:
   `publications/sakkaravarththiyin-thirumagan/articles/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md`
2. Record its current GitHub blob SHA as T0 provenance.
3. Read the entire article before finalising the English title; do not mechanically choose among `forest exile`, `went to the forest`, `curse`, or `anger` until the complete argument is understood.
4. Apply the Article 1–5 voice/lexicon baseline, including frozen **Achariyar** and existing epic-name conventions.
5. Create `translations/en/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md` with all source page-boundary comments.
6. Complete T2 bilingual fidelity review, T3 Kalaignar-language/voice review and T4 terminology/quotation/citation audit.
7. Update `LEXICON.md`, `TRANSLATION_REVIEW.md`, tracker, plan, READMEs and **this `HANDOVER.md`** before ending the activity.

**Do not begin Article 7 until Article 6 has passed T2 and T3.**
