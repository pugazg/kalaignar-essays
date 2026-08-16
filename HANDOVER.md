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
- Scan 83 is a separate promotional Article 12 witness and must never overwrite Article 12 body text.

Other high-value source readings already verified include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — ACTIVE

- Phase E0 setup: **COMPLETE**
- Phase E1 Article 1 calibration: **COMPLETE**
- Phase E2 Articles 2–4: **COMPLETE**
- Phase E3 Articles 5–8: **COMPLETE**
- Phase E4 Articles 9–11: **ACTIVE — Article 9 complete; Article 10 next**
- English drafts: **9 / 14**
- T2 fidelity-reviewed: **9 / 14**
- T3 voice-reviewed: **9 / 14**
- T4 audited: **9 / 14**
- T5 verified: **9 / 14**
- final cross-article consistency review: **not started**
- English release gate: **OPEN**

## Publication-wide identity / label rule

The user explicitly established that `ஆச்சாரியார்` refers to **C. Rajagopalachari (Rajaji)** and chose **Achariyar** as the English body form.

- `ஆச்சாரியார்` → **Achariyar** whenever that is Kalaignar's source label.
- Do not mechanically substitute `Rajaji`.
- Preserve Kalaignar's own label switches: Article 7 explicit `இராஜாஜி` → **Rajaji**.

## Verified English articles

1. `சக்கரவர்த்தியின் திருமகன்` → **Chakravarthi's Son** — Tamil SHA `47a5b1fd0b28827bb098dda419b5bf864e9f3866`
2. `தேகமும் உணர்வும்` → **Body and Feeling** — `bb9131b7856b528e527136be8f4f60dca2999850`
3. `சதி நிரூபிக்கப்படுகிறது` → **The Conspiracy Is Proven** — `903dbb0a2b74bc1ffa173469bfdb3dfa6ce9b4b4`
4. `காமராஜன் ஆட்கொண்ட தசரதராஜன்!` → **Dasaratha Raja in the Grip of Kama-Raja!** — `9151694c1c473fd4c225aa8076d086e01931bc1e`
5. `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?` → **Bharadvaja's Ashram—or a Paris 'Bar'?** — `f0b527ed76e10072c5875f0998add33cf09e6647`
6. `இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா?` → **Why Did Rama Go to the Forest? A Rishi's Curse? Kaikeyi's Anger?** — `07ae8741f3b06fa9208a6478ebabea87d53a93f5`
7. `விபீஷணருக்கு விடை யளிப்போம்!` → **Let Us Answer Vibhishana!** — `1ae5db95c88df7ccdbd74b180c4427f8ee81d022`
8. `நாடாண்ட மன்னன் நாதியற்று செத்தான்` → **The King Who Ruled the Land Died with No One to Tend Him** — `87d10ed53e55fdf6a1eb60f86517cc245644a71a`
9. `தந்தை மகனும் தருமம் தவறியவர்கள்!` → **Father and Son—Both Strayed from Dharma!** — `d8b6b6cba29bb35e70d2009ebccad4b64cfffa9d`

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

### Article 9 — COMPLETE / VERIFIED

English: [`translations/en/09-thanthai-maganum-tharumam-thavariyavargal.md`](publications/sakkaravarththiyin-thirumagan/translations/en/09-thanthai-maganum-tharumam-thavariyavargal.md)

- Title → **Father and Son—Both Strayed from Dharma!**.
- `தருமம் / தர்மம்` → **dharma**; `சத்தியம்` → **truth / word of truth**; `நாஸ்திகம் / நாஸ்திகன்` → **atheism / atheist**.
- `தர்ம ராஜன்` → **Dharma Raja**.
- Source `ஜாம்பாலி` → **Jambali**; unusual verified `நாதிகமுள்ளவர்கள்` → source-bearing **naathigam**, explicitly kept distinct from `நாஸ்திகம்`.
- Opening Chitrakuta quotation uses mixed source quote forms; English normalises typography only because scope is clear, and the anomaly is documented.
- Preserve sheep-flock / **Govinda!** jab and the escalating direct challenge.
- `சூட்சமம்` → **the catch!**; `ராஜ்ய பாரம்` → **burden of rule** by context; `சதி` remains **conspiracy**.
- `அவதார புருஷன் அயோத்தி ராமன்` → **Rama of Ayodhya—the incarnation**; do not revert to the awkward draft `incarnation-man`.
- Preserve Rama's **the country given by me** claim, Vasishta's **administer the kingdom** instruction, and the sandal/throne surrogate-rule sequence.
- Preserve the Nehru/Delhi–Governor Prakasa/Chennai analogy exactly as the source's political comparison.
- `“புனிதமான” பாதுகைகள்` → **“holy” sandals**; `சதிகார ராமன்` → **the conspirator Rama**; final `சதி நிறைந்த சாகசப் பேச்சு` → **audacious, conspiracy-laden speech**.
- No unresolved Article 9 meaning-level blocker remains.

## Exact next activity — Article 10

Work only on **Article 10 — `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`**.

1. Fetch `publications/sakkaravarththiyin-thirumagan/articles/10-vishnu-avatharam-enbathum-ramanidam.md` fresh from `main` and record its current blob SHA as T0.
2. Read the **entire** Tamil article before choosing the English title.
3. Preserve the known source-witness distinction: contents/heading `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` versus scan-63 body phrase `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
4. Apply the publication-wide **Achariyar** rule and established lexicon only where context supports it.
5. Create `translations/en/10-vishnu-avatharam-enbathum-ramanidam.md` with all source-page comments.
6. Complete T2 bilingual fidelity review, T3 Kalaignar-voice review and T4 terminology/source audit.
7. Update `LEXICON.md`, `TRANSLATION_REVIEW.md`, tracker, plan, publication/root READMEs and **this `HANDOVER.md`** before ending.

**Do not begin Article 11 until Article 10 has passed T2 and T3.**
