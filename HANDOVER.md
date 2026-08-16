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

For E7, fetch every release-facing file fresh from `main` before changing status or creating the release-closeout record.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Never silently modernise, correct, normalise, reconstruct or improve the Tamil. Preserve source-visible wording, spelling, punctuation, names, numbers, repetition, grammar and typographical forms. Separate physical-copy marks from printed text. **Source PDFs are never committed to this repository.**

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, physical imagery, exclamations and wordplay. Do not academicise or soften him. Unexplained source-specific forms remain source-bearing unless the user explicitly asks for outside research. Source punctuation anomalies that matter must be documented rather than silently repaired.

## Active publication

Workspace: `publications/sakkaravarththiyin-thirumagan/`  
Source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

- title: `சக்கரவர்த்தியின் திருமகன்`
- author: `கலைஞர் மு.கருணாநிதி`
- physical scans: **83**
- source SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- first edition visible in scan: **May 1956**
- supplied reprint: **2018**
- printed contents: **14 articles**

## Tamil archival status — COMPLETE / FROZEN

- **83 / 83** page records complete
- **83 / 83** strict word-level visual checks complete
- **14 / 14** Tamil article assemblies complete and strict-rechecked
- **0** unresolved `NEEDS-PIXEL-REVIEW`
- source PDF kept outside GitHub

Do not touch the Tamil body layer unless an explicit source-supported correction is found.

During Article 14 translation, one editorial audit-note correction was made in `pages/0008-contents.md`: the printed contents text was not changed; only a stale note that had incorrectly described the heading as `காலை பிடி!` was corrected to the strict heading witness `காலைக் பிடி !`.

## Source-witness distinctions that must not regress

- Article 5 contents: `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?`; heading: `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`.
- Article 10 contents/heading: `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!`; scan-63 body: `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Article 14 contents: `காரியமாகும் வரையில் காலைப் பிடி!`; heading: `காரியமாகும் வரையில் காலைப் பிடி !`.
- **Scan 83 is a separate promotional Article 12 witness and must never overwrite Article 12 body text.**
- Scan 82 contains the end of Article 14 followed by a separate printed *Viduthalai* advertisement; the advertisement is not Article 14 body.

Other high-value strict readings already verified include `மற்றுமுள்ள`, `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`, `எப்படி பெய்ப்படி`, `கல் சாசனமோ`, `சீறிப் பாய்ந்தார்கள்`, `சப்பைக் கட்டு போடும்`, `நந்திக் கிராமத்திலே யிருந்து`, `44ஆவது`, `அப்பேர்ப்பட்டவர்`, `மாள்வதைவிட`, `ஓகோ !`, `மாறடித்து`, scan-76 `துராசைப் பட்டுக்`, scan-80 `சவுந்தாயமும்`, and scan-82 `வர்ணிக்கிறான்`.

## English translation phase — COMPLETE / E7 NEXT

- Phase E0 setup: **COMPLETE**
- Phase E1 Article 1 calibration: **COMPLETE**
- Phase E2 Articles 2–4: **COMPLETE**
- Phase E3 Articles 5–8: **COMPLETE**
- Phase E4 Articles 9–11: **COMPLETE**
- Phase E5 Articles 12–14: **COMPLETE**
- Phase E6 publication-level cross-article consistency review: **COMPLETE / PASSED**
- English drafts: **14 / 14**
- T2 fidelity-reviewed: **14 / 14**
- T3 voice-reviewed: **14 / 14**
- T4 audited: **14 / 14**
- T5 verified: **14 / 14**
- unresolved translation questions: **0**
- English translation: **COMPLETE**
- Phase E7 English release closeout: **NEXT**
- English release gate: **OPEN pending E7**

E6 found **no translation-body correction requiring an edit to Articles 1–14**. Do not rewrite any verified English article merely for stylistic polish during E7.

## Publication-wide identity / label rule

The user explicitly established that `ஆச்சாரியார்` refers to **C. Rajagopalachari (Rajaji)** and chose **Achariyar** as the English body form.

- `ஆச்சாரியார்` → **Achariyar** whenever that is Kalaignar's source label.
- Do not mechanically substitute `Rajaji`.
- Article 7 explicit source `இராஜாஜி` → **Rajaji**.
- Article 11 source plural `ஆச்சாரியார்களுக்கு` → **the Achariyars**.

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
10. `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` → **To Rama, Who Is Said to Be Vishnu's Incarnation!** — `e7a2b2e1d3b703d672b0be7569440217ccb03d3e`
11. `நடப்பதெல்லாம் நாராயணன் செயலா?` → **Is Everything That Happens Narayana's Doing?** — `b324e995d580ee021577b998d193d005fa6446ad`
12. `மாரீசனைத் துரத்திச் சென்ற ராமனிடம்` → **To Rama Who Went Chasing Maricha** — `01aae57b137bfb3d762c4cb6a62e149bfdb78edb`
13. `துரோகிகள் சந்திப்பு!` → **Traitors Meet!** — `369c3f4e5030c5810e815d13692372ae73849837`
14. `காரியமாகும் வரையில் காலைப் பிடி !` → **Hold Their Feet Until Your Purpose Is Achieved!** — `e97314ada6b52c671742bb1526ed70acd1a26411`

## Non-regression translation decisions

### Articles 1–3
- **Achariyar** frozen for `ஆச்சாரியார்`.
- **Chakravarthi** remains where Rajagopalachari/Chakravarthi wordplay is active.
- Aryans / Dravidians / Aryanism and demons / Rakshasas / Devas remain source-distinct.
- Article 2 keeps body/feeling, body of flesh, anger and passion, Bhagavan/Ishvari, **plot / conspiracy**, and source `(August 154)`.
- Article 3 keeps burden-of-kingdom imagery, **through the back door**, **taint**, and rapid rhetorical questions.

### Article 4
- `காமராஜன்` → **Kama-Raja** in title and ending.
- Sexualised vocabulary and age-marked ridicule stay strong.
- `அப்பாவி / அப்-பாவி` → **innocent / Ah—sinner!** with separated translator note.

### Article 5
- Heading/contents Tamil witnesses stay distinct.
- Title remains **Bharadvaja's Ashram—or a Paris 'Bar'?**.
- Both Kambar passages remain sense-translated only from the supplied Tamil plus Kalaignar's glosses.
- Scan-33 unmatched quotation and scan-36 standalone `—Achariyar.` stay documented.

### Article 6
- **Mooli-Alangari** and **Brahmin Vambar** remain source-bearing.
- Keep sacrificial-altar image, horoscope/curse/anger/fate sequence, Moodevi punctuation anomaly, **splint**, **walk on their feet / On their feet!**, **Aryan guard forces**, and **take up the brief**.
- Source `காகபட்டர்` is represented as **Kakapattar**; do not change it merely to match Article 11.

### Article 7
- **Vibhishana / Vibhishana-ness / Vibhishana doctrine** remain the recurring frame.
- **Sivagnanam / Sivagnanams** preserves source name and mocking plural.
- **Rajaji** remains where source explicitly says `இராஜாஜி`.
- Source-bearing **thanda-kanda / Inithavayan / Argusis** remain unexpanded.
- Keep **tail-bearers**, **vow of one wife**, **demonic frenzy of colour-hatred**, **carrying kavadi for the North**, and **Time alone must give the answer!**.
- Scan-48 `கற்பு நிலையைப் பாதிக்கும்` difficulty remains documented.

### Article 8
- `நாதியற்று / நாதியில்லாமல்` → **with no one to tend him**.
- **Suta-Magadhars / Sayantan / paakkai** remain source-bearing.
- Keep sleeping-wives/deathbed sequence, **sixty thousand**, mastery-of-senses sarcasm, **intoxication of lust**, **bodily pleasure**, literal **tail**, **sacred-thread king Achariyar**, and scan-52 unmatched quotation note.

### Article 9
- `தருமம் / தர்மம்` → **dharma**; `சத்தியம்` → **truth / word of truth**; `நாஸ்திகம் / நாஸ்திகன்` → **atheism / atheist**.
- Source `ஜாம்பாலி` → **Jambali**; strict unusual `நாதிகமுள்ளவர்கள்` stays source-bearing through **naathigam**.
- Preserve sheep-flock / **Govinda!**, sandals-on-throne surrogate rule, Nehru–Governor Prakasa analogy, **“holy” sandals**, **the conspirator Rama**, and **audacious, conspiracy-laden speech**.

### Article 10
- Preserve heading/contents `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` separately from scan-63 `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`.
- Keep **Ramayana tigers**, **shraddha feast**, **mesha (goat) meat**, **human flesh**, **Rakshasa flesh**, **all three times**, unmatched parenthesis, **thirst of lust**, **gems among men**, **rasabhasa**, **splint**, and final **Aryan culture** jab.

### Article 11
- Keep May **1954 / 1955** contradiction, **backing orchestra**, **Chanakya**, direct **Brahmin leader**, Narayana/Rama contradiction, **dharma and justice**, **sinful act**, **Oh-ho!**, **Ayyo, Lakshmana!**, scan-69 unmatched quotation, Janaki insult cascade, **fourth-rate woman**, fate reversal, physical tongue image, and final livelihood line.
- Source `காக பட்டர்` remains **Kaga Pattar**; do not flatten it to Article 6 **Kakapattar**.
- Source plural remains **the Achariyars**.

### Article 12
- Title remains **To Rama Who Went Chasing Maricha**.
- **Scan 83 is only a separate promotional witness.** Never rewrite the body from it.
- `மேலுத்தரியம்` → **upper cloth**; `மேலாடை` → **upper garment**; `அம்சம்` → **aspect** distinct from `அவதாரம்` → **incarnation**.
- Scan-72 `அவனாகவே` stays frozen in Tamil; contextual English action remains explicitly documented.
- Keep **theist worthies**, **kings of the night**, **sisters who slipped and fell**, **Kakuthan**, **Ashadabhoothis**, market-street imagery and Sita/Draupadi ending.

### Article 13
- Title remains **Traitors Meet!**.
- `மாறடித்து ஒப்பாரி வைத்தான்` → **beat his chest and wailed an oppari**.
- `அரக்கன் / அசுரன்` → **demon / asura**; **Vanara / vimana / yojana** remain source-bearing.
- Scan-76 `துராசைப் பட்டுக்` remains frozen in Tamil; contextual English **driven by greed**.
- Keep **This Is the Story Achariyar Has Drawn Up!**, source quotation irregularities, repeated **they say**, **Here Achariyar dodges**, and **Why? Why, Achariyar; why?**.

### Article 14
- Title remains **Hold Their Feet Until Your Purpose Is Achieved!**.
- Contents `காரியமாகும் வரையில் காலைப் பிடி!` and heading `காரியமாகும் வரையில் காலைப் பிடி !` stay distinct.
- Keep Tara's **Ayyo!**, mountain-waterfall blood image, mountain-like body, and direct **look**.
- `பூஜனைப்பித்தர்கள்` → **worship-mad people**.
- `அந்தப்புர போகம்` → **sensual pleasures of the inner palace**.
- Strict `சவுந்தாயமும்` remains source-bearing **saundhayam**; do not guess or normalise it.
- `கிராமிய சுகம்` → **rustic pleasure**; `கயவன் / கயவர்கள்` → **scoundrel / scoundrels**; `சிருங்கார போகம்` → **sensual pleasure**.
- Keep Rama's threat, Lakshmana becoming a **storm**, Tara-beauty sarcasm, **Aryans will do anything—say anything—so that their purpose may be achieved!**, and final **Sons of Chakravarthi / hold the feet of scoundrels** echo.
- Scan-82 strict `வர்ணிக்கிறான்` remains source authority; lower *Viduthalai* advertisement is excluded.

## E6 publication-level cross-article consistency review — PASSED

E6 was completed after fetching all 14 current English files fresh from `main`. Full reviewed blob-SHA provenance is recorded in [`publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md`](publications/sakkaravarththiyin-thirumagan/translations/en/TRANSLATION_REVIEW.md).

E6 confirmed:

- publication-wide **Achariyar**, Article 7 **Rajaji**, and Article 11 **the Achariyars**;
- recurring epic names and ideological vocabulary;
- demon / Rakshasa / asura / Deva distinctions and source-bearing **Vanara** usage;
- title/body puns and rhetorical echoes, especially Articles 4, 5, 8, 13 and 14;
- commands, rhetorical questions, repetition, ridicule, insults and political/sexual polemic without accidental smoothing;
- source-bearing forms and documented source anomalies;
- source dates, issue references, *Kalki* attributions and page-boundary comments;
- Article 12 scan-83 separation and Article 14 scan-82 article/advertisement boundary.

### E6 source-sensitive differences intentionally retained

- Article 6 source `காகபட்டர்` → **Kakapattar**; Article 11 source `காக பட்டர்` → **Kaga Pattar**.
- Article 2 source `ராமச்சந்திரமூர்த்தி` → **Ramachandramurti**; Article 14 source `இராமசந்திர மூர்த்தி` → **Ramachandra Murti**.

These are source-witness differences, not inconsistencies to be mechanically harmonised.

### E6 corrections

- Translation-body edits: **none**.
- Unresolved translation questions: **none**.
- Result: **E6 PASSED; English translation COMPLETE.**

## Exact next activity — E7 English release closeout

Work only on release closeout; do not reopen article prose without a genuine source-supported defect.

1. Fetch the current root `README.md`, this `HANDOVER.md`, publication `README.md`, `TRANSLATION_PLAN.md`, `translations/en/README.md`, `LEXICON.md`, `TRANSLATION_REVIEW.md`, and all release-facing publication records fresh from `main`.
2. Inspect the publication directory for any established release/completion-report naming convention. Reuse the repository's workflow rather than inventing a conflicting parallel system.
3. Verify all 14 English article links/files exist, remain `translation_status: verified`, and point to the expected frozen Tamil source SHAs.
4. Verify release-facing counts and statuses are mutually consistent: **14/14 T5, E6 PASSED, 0 unresolved, English translation COMPLETE**.
5. Verify no source PDF is present in the repository and that Tamil archival state remains frozen/complete.
6. Verify the documented source-witness boundaries and source-bearing exceptions remain represented in the release records.
7. Create or update the English release-closeout record required by the established workflow. Record release checks, blockers, final status and provenance.
8. If no blocker remains, mark **E7 COMPLETE**, close the **English release gate**, and update root/publication READMEs, tracker, translation plan, review ledger and this `HANDOVER.md` accordingly.
9. If a blocker is found, leave the gate OPEN and make that exact blocker the next activity.

**Do not close the English release gate until E7 passes.**
