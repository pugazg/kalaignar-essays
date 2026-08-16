# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover document. Update this file after every meaningful source, translation or review activity. Do not create competing handover files unless the user explicitly asks.**

## Mandatory startup for future continuation

Read completely before making changes:

1. [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
3. this `HANDOVER.md`
4. [`publications/sakkaravarththiyin-thirumagan/README.md`](publications/sakkaravarththiyin-thirumagan/README.md)
5. [`publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md`](publications/sakkaravarththiyin-thirumagan/TRANSLATION_PLAN.md)
6. [`publications/sakkaravarththiyin-thirumagan/translations/en/README.md`](publications/sakkaravarththiyin-thirumagan/translations/en/README.md)
7. [`publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md`](publications/sakkaravarththiyin-thirumagan/translations/en/LEXICON.md)
8. [`publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md)

Then fetch the exact current Tamil article assembly before translating.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Never silently modernise, correct, normalise, reconstruct or improve the Tamil. Preserve source-visible wording, spelling, punctuation, names, numbers, repetition, grammar and typographical forms. Separate physical-copy marks from printed text. **Source PDFs are never committed to this repository.**

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, physical imagery, exclamations and wordplay. Do not academicise or soften him. Unexplained source-specific forms should remain source-bearing unless the user explicitly asks for outside research. Source punctuation anomalies that matter must be documented rather than silently repaired.

## Active publication

Workspace: `publications/sakkaravarththiyin-thirumagan/`  
Source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

- scans: **83**
- source SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- title: `சக்கரவர்த்தியின் திருமகன்`
- author: `கலைஞர் மு.கருணாநிதி`
- first edition visible in scan: **May 1956**
- supplied reprint: **2018**
- printed contents: **14 articles**

## Tamil archival status — COMPLETE / FROZEN

- **83 / 83** page records complete
- **83 / 83** strict word-level visual checks complete
- **14 / 14** Tamil article assemblies complete and strict-rechecked
- **0** unresolved `NEEDS-PIXEL-REVIEW`
- source PDF kept outside GitHub

Do not touch the Tamil layer unless an explicit source-supported correction is found.

## Source-witness distinctions that must not regress

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: `காரியமாகும் வரையில் காலைப் பிடி !`.
- **Scan 83 is a separate promotional Article 12 witness and must never overwrite Article 12 body text.**

Other high-value source readings already verified include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — ACTIVE

- Phase E0 setup: **COMPLETE**
- Phase E1 Article 1 calibration: **COMPLETE**
- Phase E2 Articles 2–4: **COMPLETE**
- Phase E3 Articles 5–8: **COMPLETE**
- Phase E4 Articles 9–11: **COMPLETE**
- Phase E5 Articles 12–14: **ACTIVE — Article 12 complete; Article 13 next**
- English drafts: **12 / 14**
- T2 fidelity-reviewed: **12 / 14**
- T3 voice-reviewed: **12 / 14**
- T4 audited: **12 / 14**
- T5 verified: **12 / 14**
- final cross-article consistency review: **not started**
- English release gate: **OPEN**

## Publication-wide identity / label rule

The user explicitly established that `ஆச்சாரியார்` refers to **C. Rajagopalachari (Rajaji)** and chose **Achariyar** as the English body form.

- `ஆச்சாரியார்` → **Achariyar** whenever that is Kalaignar's source label.
- Do not mechanically substitute `Rajaji`.
- Preserve Kalaignar's own label switches: Article 7 explicit `இராஜாஜி` → **Rajaji**.
- Preserve source number as well: Article 11 `ஆச்சாரியார்களுக்கு` is plural and therefore remains **the Achariyars**.

## Verified English articles

1. `சக்கரவர்த்தியின் திருமகன்` → **Chakravarthi's Son** — `47a5b1fd0b28827bb098dda419b5bf864e9f3866`
2. `தேகமும் உணர்வும்` → **Body and Feeling** — `bb9131b7856b528e527136be8f4f60dca2999850`
3. `சதி நிரூபிக்கப்படுகிறது` → **The Conspiracy Is Proven** — `903dbb0a2b74bc1ffa173469bfdb3dfa6ce9b4b4`
4. `காமராஜன் ஆட்கொண்ட தசரதராஜன்!` → **Dasaratha Raja in the Grip of Kama-Raja!** — `9151694c1c473fd4c225aa8076d086e01931bc1e`
5. `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?` → **Bharadvaja's Ashram—or a Paris 'Bar'?** — `f0b527ed76e10072c5875f0998add33cf09e6647`
6. `இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா?` → **Why Did Rama Go to the Forest? A Rishi's Curse? Kaikeyi's Anger?** — `07ae8741f3b06fa9208a6478ebabea87d53a93f5`
7. `விபீஷணருக்கு விடை யளிப்போம்!` → **Let Us Answer Vibhishana!** — `1ae5db95c88df7ccdbd74b180c4427f8ee81d022`
8. `நாடாண்ட மன்னன் நாதியற்று செத்தான்` → **The King Who Ruled the Land Died with No One to Tend Him** — `87d10ed53e55fdf6a1eb60f86517cc245644a71a`
9. `தந்தை மகனும் தருமம் தவறியவர்கள்!` → **Father and Son—Both Strayed from Dharma!** — `d8b6b6cba29bb35e70d2009ebccad4b64cfffa9d`
10. `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` → **To Rama, Who Is Said to Be Vishnu's Incarnation!** — `e7a2b2e1d3b703d672b0be7569440217ccb03d3e`
11. `நடப்பதெல்லாம் நாராயணன் செயலா?` → **Is Everything That Happens Narayana's Doing?** — `b324e995d580ee021577b998d193d005fa6446ad`
12. `மாரீசனைத் துரத்திச் சென்ற ராமனிடம்` → **To Rama Who Went Chasing Maricha** — `01aae57b137bfb3d762c4cb6a62e149bfdb78edb`

## Non-regression translation decisions

### Articles 1–3
- **Achariyar** frozen for `ஆச்சாரியார்`.
- **Chakravarthi** retained where Rajagopalachari/Chakravarthi wordplay is active.
- Aryans / Dravidians / Aryanism and demons / Rakshasas / Devas remain source-distinct.
- Article 2 keeps body/feeling, body of flesh, anger and passion, Bhagavan/Ishvari, **plot / conspiracy**.
- Article 3 keeps burden-of-kingdom imagery, **through the back door**, **taint**, and rapid rhetorical questions.

### Article 4
- `காமராஜன்` → **Kama-Raja** in title and ending.
- Sexualised vocabulary and age-marked ridicule remain strong.
- `அப்பாவி / அப்-பாவி` → **innocent / Ah—sinner!** with separated note.

### Article 5
- Keep heading/contents Tamil witnesses distinct.
- English title remains **Bharadvaja's Ashram—or a Paris 'Bar'?**.
- Both Kambar passages are sense-translated only from supplied Tamil + Kalaignar's glosses.
- Scan-33 unmatched quotation and scan-36 standalone `—Achariyar.` remain documented/preserved.

### Article 6
- **Mooli-Alangari** and **Brahmin Vambar** remain source-bearing.
- Kaikeyi's sacrificial-altar image and horoscope/curse/anger/fate sequence remain direct.
- Moodevi quote anomaly documented.
- Keep **splint**, **walk on their feet / On their feet!**, **Aryan guard forces**, **take up the brief**, `ayya, literature!`.

### Article 7
- **Vibhishana / Vibhishana-ness / Vibhishana doctrine** remain the recurring polemical frame.
- **Sivagnanam / Sivagnanams** preserves the mocking plural without external identification.
- Source-bearing **thanda-kanda / Inithavayan / Argusis** remain unexpanded.
- Keep **tail-bearers**, **vow of one wife**, **demonic frenzy of colour-hatred**, **carrying kavadi for the North**, and final **Time alone must give the answer!**.
- Scan-48 `கற்பு நிலையைப் பாதிக்கும்` difficulty remains explicitly noted.

### Article 8
- Title/body `நாதியற்று / நாதியில்லாமல்` → **with no one to tend him**.
- Source-bearing **Suta-Magadhars / Sayantan / paakkai** remain unexpanded.
- Keep sleeping-wives/deathbed sequence, **sixty thousand**, mastery-of-senses sarcasm, **intoxication of lust**, **bodily pleasure**, literal **tail**, and **sacred-thread king Achariyar**.
- Scan-52 unmatched quotation opening remains documented.

### Article 9
- `தருமம் / தர்மம்` → **dharma**; `சத்தியம்` → **truth / word of truth**; `நாஸ்திகம் / நாஸ்திகன்` → **atheism / atheist**.
- Source `ஜாம்பாலி` → **Jambali**; unusual verified `நாதிகமுள்ளவர்கள்` → source-bearing **naathigam**.
- Preserve sheep-flock / **Govinda!**, sandals-on-throne surrogate rule, Nehru–Governor Prakasa analogy, **“holy” sandals**, **the conspirator Rama**, and **audacious, conspiracy-laden speech**.

### Article 10
- Title → **To Rama, Who Is Said to Be Vishnu's Incarnation!**.
- Preserve heading/contents `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` separately from scan-63 body `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Keep **Ramayana tigers**, **shraddha feast**, **mesha (goat) meat**, **human flesh**, **Rakshasa flesh**, **all three times**, scan-63 unmatched opening parenthesis, **thirst of lust**, **business trouble**, **second wife**, **gems among men**, **rasabhasa**, reused **splint**, and closing **Aryan culture** jab.

### Article 11
- Title → **Is Everything That Happens Narayana's Doing?**.
- Preserve May **1954 / 1955** contradiction, **backing orchestra**, **Chanakya**, direct **Brahmin leader**, Narayana/Rama contradiction, **dharma and justice**, **sinful act**, **Oh-ho!**, **Ayyo, Lakshmana!**, scan-69 unmatched outer quotation, Janaki insult cascade, **fourth-rate woman**, fate reversal, physical tongue image, **Kaga Pattar**, source plural **the Achariyars**, and final livelihood line.

### Article 12 — COMPLETE / VERIFIED

English: [`translations/en/12-maarisanai-thuraththi-sendra-ramanidam.md`](publications/sakkaravarththiyin-thirumagan/translations/en/12-maarisanai-thuraththi-sendra-ramanidam.md)

- Title → **To Rama Who Went Chasing Maricha**.
- Tamil SHA `01aae57b137bfb3d762c4cb6a62e149bfdb78edb`; controlling body scans **71–73 / printed 69–71**.
- **Scan 83 is only a separate back-cover promotional Article 12 witness.** It must never overwrite, normalise or silently correct the body witness. Its visible `அறி குறி?` and `தலைகாட்டுகிறது. சொந்தக்...` forms remain independent from scan-72 body wording.
- Keep both dated *Kalki* quotations: **30.1.1955** and **6.2.1955**.
- `மேலுத்தரியம்` → **upper cloth**; recurring `மேலாடை` → **upper garment**.
- Scan-72 source-visible `அவனாகவே` remains untouched in Tamil. The surrounding argument still attributes the garment-dropping act to Sita; English therefore uses **she drops her upper garment down on her own**, with the source difficulty explicitly documented rather than silently repaired.
- `அம்சம்` → **aspect**, distinct from `அவதாரம்` → **incarnation**.
- Retain Jatayu/Ravana bodily-force sequence, **Poor thing** sarcasm, repeated modesty/chastity questions, and the Lakshmana/Sita comparison.
- `ஆஸ்திகப் பெருமக்கள்` → **theist worthies**; `இரவு ராஜாக்கள்` → **kings of the night**; `வழுக்கி விழுந்த சகோதரிகள்` → **sisters who slipped and fell**.
- Keep the prostitution/anguish image **volcanoes of anguish with tears flooding their eyes**, **Pitiful—most pitiful!**, market-street woman comparison, **flowering vines born into noble families**, and **immense nerve**.
- `காகுத்தன்` → source-bearing **Kakuthan**; `ஆஷாடபூதிகள்` → source-bearing **Ashadabhoothis**; neither receives an outside identification.
- Keep the final rubbish-on-head dance and **incarnations of Sita / incarnations of Draupadi!** escalation.
- No unresolved Article 12 meaning-level blocker remains. The `அவனாகவே` form is a documented source difficulty, not an unresolved Tamil transcription item.

## Exact next activity — Article 13

Work only on **Article 13 — `துரோகிகள் சந்திப்பு!`**.

1. Fetch `publications/sakkaravarththiyin-thirumagan/articles/13-thurogigal-santhippu.md` fresh from `main` and record its current blob SHA as T0.
2. Read the **entire** Tamil article before choosing the English title.
3. Apply the publication-wide **Achariyar** rule and existing lexicon only where context supports it.
4. Create `translations/en/13-thurogigal-santhippu.md` with all source-page comments (Article 13 body is scans **74–78 / printed pp.72–76** according to the established page map; verify fresh before use).
5. Complete T2 bilingual fidelity review, T3 Kalaignar-voice review and T4 terminology/source audit; mark T5 only after all pass.
6. Update `LEXICON.md`, `TRANSLATION_REVIEW.md`, tracker, plan, publication/root READMEs and **this `HANDOVER.md`** before ending.

**Do not begin Article 14 until Article 13 has passed T2 and T3; ideally complete Article 13 through T5 first.**
