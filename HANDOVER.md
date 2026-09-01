# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, translation, review or release activity.**

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. this `HANDOVER.md`
5. `docs/NEXT_CHAT_PROMPT.md` when continuing current work in a fresh window
6. active publication README / metadata / fidelity / completion records
7. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Fresh-window continuation rule

- **Fetch live `main` first. Live `main` is authoritative.**
- `docs/NEXT_CHAT_PROMPT.md` is a convenience summary only and never overrides live `main` or this handover.
- Any checkpoint SHA means “last confirmed when prepared”; it is **not** a rollback target.
- If `main` has advanced, preserve the newer durable state. Never reset, overwrite, repeat or reopen later completed work merely because an older prompt records an earlier boundary.
- Re-fetch target files before writing when another chat/window may also be active.
- Last confirmed live HEAD immediately before this handover synchronization: `68f1966c87c6a53690d8e753aa973b1f5be331c2` — `Refresh Article 1 T1 draft authority in publication README`.

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14 complete**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

- Tamil page records: **17 / 17 verified**
- P5: **17 / 17 PASS**
- frozen Tamil authority: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- verified English blob: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`
- English release: **COMPLETE**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 3 — உணர்ச்சிமாலை — RELEASE COMPLETE / FROZEN

Workspace: `publications/unarchchimaalai/`

## Tamil archival state — COMPLETE / FROZEN

- physical scans: **50**
- P2 page records: **50 / 50 verified**
- P3 assemblies: **10 / 10**
- P4: **PASS**
- P5 strict visual fidelity: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- P5 structural/punctuation/spacing/layout corrections: **236 propagated**
- documented Gemini/source lexical conflicts retained: **18**
- blockers: **0**

Publication-specific rule: Gemini word tokens remain the frozen Tamil lexical baseline wherever supplied; scan/Gemini lexical disagreements are documented rather than silently substituted. English translates the frozen Tamil assemblies.

Durable non-regression includes scan-19 source recovery, scan-20 visible numeral `1` only, frozen scan-32 word/order sequence, corrected scan-33/34 boundary, Article 7 ending on scan 41 at `வரலாற்றை வீணாக்கிய`, recovered scan-42 `பதில் இல்லை.`, scan-43 `* * *`, frozen scan-48 `ப்ழச்சளை`, frozen scan-49 `விட்டாய்.` placement, scan-49 publication-close matter outside Article 10, and scan-50 advertisement outside all articles.

## Frozen Tamil translation authorities

1. `c63837a9f7c02d6f3a18171a512d46788f66ad92`
2. `dda81363f512ee2f829c367ae929ce3610604fe9`
3. `92eb1a68d65f65dd71274e5e79f3209e63359d9a`
4. `006f2f75dbc3eea796170a29aee0befd162522e7`
5. `c8ac4d7c241832e07bbb24c5cee935588673f4ac`
6. `f3634a63bff94f5647dbbdfa7dfe9b1b0a2479d8`
7. `bac121257d24477bc3c7e8c65f4b3f7b8a419bad`
8. `2e57a4c7c53ae4354942b5e64c5a2c4a33f3be2f`
9. `4dd0bbc03f278c9bfc02b189b285a1891aa44d2d`
10. `f856664d86695237a23d0ffc0bef088d32a82fe9`

## Final English progress

- T0 setup: **PASS**
- T1 drafts: **10 / 10**
- T2 fidelity-reviewed: **10 / 10**
- T3 voice-reviewed: **10 / 10**
- T4 audited: **10 / 10**
- T5 verified: **10 / 10**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- English body corrections in E6: **0**
- English body corrections in E7: **0**
- frozen Tamil changes in E6/E7: **0**
- source/fidelity defects discovered in E6/E7: **0**
- source/translation gates reopened: **No**
- translation/release blockers: **0**
- **English translation: COMPLETE / RELEASED / FROZEN**

## Released Articles 1–10

1. `உணர்ச்சி மாலை` — **Garland of Emotion** — `4246c9f1e206d5703fe50297657bb0af2a8e57e6`
2. `புரட்சி வளர்ந்த கதை` — **The Story of How the Revolution Grew** — `f1599a8e7cae4ba749b9be2857705b152887f9f8`
3. `போகிறான்;போகிறான்..!` — **He Goes; He Goes..!** — `1134185bc21478775419adb3560b110c001d2b75`
4. `இராவணன் நம் பாட்டன்` — **Ravana Is Our Grandfather** — `03ac3b0fc25f38a4b56c352f53bf73915b1f33fb`
5. `இங்கல்ல! இரஷ்யாவில்` — **Not Here! In Russia** — `c689ff90f08d389a5e7ebc4849c30d58dfe81766`
6. `3, 57, 90.` — **3, 57, 90.** — `cf9187b40bc1bc64806a1df84e45c884b1b8d9a8`
7. `30-1-1948` — **30-1-1948** — `6cfb28e2d83ba84ee2daa54606561479b61498b0`
8. `பத்தினியே உன்போல்...!` — **O Chaste Woman, Like You...!** — `6b12e6b3cc09b6de402998bb3824e7a98808f885`
9. `அன்னை நாகம்மையார்!` — **Mother Nagammaiyar!** — `204ffed012f4bd91b3077065f031d6b2db747854`
10. `கவிதையல்ல - கண்ணீர்க்கடல் !` — **Not a Poem — an Ocean of Tears!** — `cee8ea3c33495615ffc988a1875d71e40f8224a3`

E7 re-confirmed the ten live English article blobs exactly match this E6-passed baseline and the ten frozen Tamil authorities remain unchanged.

## Article 10 durable boundary

- English title: **Not a Poem — an Ocean of Tears!**
- frozen Tamil: `f856664d86695237a23d0ffc0bef088d32a82fe9`
- source scans: **48–49**
- final English: `cee8ea3c33495615ffc988a1875d71e40f8224a3`
- T2 corrections: **4**
- T3 meaning-neutral voice/cadence interventions: **12**
- T4 body corrections: **1** — `you hide away without watching—` → `you hid away without watching—`
- T5 body corrections: **0**
- frozen `ப்ழச்சளை`: retained verbatim; no guessed repair
- frozen `விட்டாய்.`: `You left.` retained at frozen source position
- scan-49 publication-close note/imprint and scan-50 advertisement: excluded from Article 10
- blockers: **0**

## E6 — publication-wide English consistency review — PASS

E6 audited all ten T5-verified articles for recurring names/epithets, epic-name conventions, ideological and socially/religiously loaded vocabulary, source-bearing transliterations/puns/insults, source/publication titles, quotation treatment, English title style, voice and rhetorical temperature, accidental smoothing/harmonisation/modernisation, completeness/page-boundary comments and all durable source anomalies.

### E6 consistent recurring decisions

- `திராவிடம்` → `Dravidam` remains stable in Articles 2, 5 and 7.
- `ஆரியம்` → `Aryanism` remains stable in Articles 6 and 10.
- `Tiruvitaththar` remains stable in Articles 1 and 10.
- `Oman Sea` remains stable in Articles 7 and 10.
- proletarian vocabulary, `God-ism`, `syrupy speech` and `javvadu` remain consistent where their source function recurs.

### E6 deliberate contextual/source-witness exceptions — PERMANENT NON-REGRESSION

Do **not** mechanically harmonise these:

- `Dravidam` / `Dravidians` / adjectival `Dravidian` according to immediate frozen Tamil form;
- Article 4 `Kambar` / `Kamban` according to `கம்பர்` / `கம்பன்`;
- Article 7 `Gandhiyar`, `revered Gandhi`, `Mohan Das Gandhi...` versus Article 8 `Gandhiji` according to immediate source label/epithet;
- `Brahmin` / `non-Brahmin` versus source-bearing `Parppanar` / `Parppanan` / `Parppanars` / `non-Parppanar`; `Vediyars` stays separate;
- noun `Vaidheegam` versus contextual `Vaidheega madmen`;
- Article 6 `Harijan` versus Article 8 `Arijan journal`;
- Article 6 `Oriental College` versus frozen later `Oriyantal College` witness;
- Article 5 translated `Soviet Union Hero` versus source-English `(Hero of the Soviet union)`;
- Article 9 `Ramasami` / `Ramasamiyar`, `Nagammaiyar` / `Nagamma`, `Ammaiyar`, `Periyar` according to immediate source label;
- Article 8 epic-name forms and all established source-bearing oddities/transliterations, including raw frozen `ப்ழச்சளை`, remain unrepaired unless source policy is explicitly reopened.

### E6/E7 anomaly and completeness result

- scan 19 source recovery / scan 20 numeral `1`: **PASS**
- scan 32 frozen irregular order: **PASS / unreconstructed**
- scan 33/34 boundary: **PASS**
- Article 7 deliberately incomplete ending: **PASS**
- scan 42 `No answer.` / scan 43 `* * *`: **PASS**
- scan 48 `ப்ழச்சளை` / scan 49 `You left.` placement: **PASS**
- scan 49 publication-close exclusion / scan 50 advertisement exclusion: **PASS**
- all ten article units and required source-page comments: **PASS**
- quotation boundaries, directness, sarcasm, ridicule, commands, rhetorical questions, exclamations and repetition: **PASS**
- E7 article-body changes: **0**
- E7 release blockers: **0**

Canonical release provenance is recorded in:

- `publications/unarchchimaalai/PUBLICATION_COMPLETION_REVIEW.md`
- `publications/unarchchimaalai/TRANSLATION_PLAN.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

## Documentation reconciliation — COMPLETE / NON-DESTRUCTIVE

The Article 9/10 documentation reconciliation remains durable:

- pre-reconciliation lexicon history through Article 9 T4 is preserved byte-for-byte as `publications/unarchchimaalai/translations/en/LEXICON_HISTORY_THROUGH_ARTICLE9_T4.md`;
- pre-reconciliation review history through Article 9 T4 is preserved byte-for-byte as `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW_HISTORY_THROUGH_ARTICLE9_T4.md`;
- canonical `LEXICON.md` and `TRANSLATION_REVIEW.md` are the current release records;
- history sidecars remain provenance only and must not replace canonical records.

## Release boundary

**உணர்ச்சிமாலை is COMPLETE / FROZEN / RELEASED in Tamil and English.** Do not reopen it for stylistic polishing, conventionalisation or terminology homogenisation. Reopen only for a genuine source-supported or release-blocking defect.

---

# Publication 4 — திராவிட சம்பத்து — ACTIVE / ARTICLE 1 T1 PASS

Workspace: `publications/thiraavida-sampaththu/`  
Supplied source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`

- source title as printed: **திராவிட சம்பத்து**
- author as printed: **கலைஞர் மு. கருணாநிதி**
- physical scans: **16**
- source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- file size: **26,071,193 bytes**
- edition: **முதல பதிப்பு, செப்டம்பர் 1951**
- publisher: **அறிவு மன்றம், சென்னை-1**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை-1**
- source PDF committed: **No**
- printed contents page: **none**

## Publication-specific source authority — USER ESTABLISHED

The user-supplied transcription remains the lexical baseline for surviving Tamil words. The scan controls structure, punctuation, quotation marks, spacing, paragraphing, headings, reading order, boundaries and physical-copy evidence. Scan/baseline lexical disagreements are documented rather than silently substituted. Text physically lost under torn-away paper is never reconstructed from context.

## Frozen Tamil archival state — COMPLETE / STRICT-REVIEWED / FROZEN

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3 article assemblies: **2 / 2 COMPLETE**
- P4: **PASS**
- P5 strict visual fidelity: **16 / 16 PASS**
- hidden torn text reconstructed: **0**
- silent lexical substitutions: **0**
- Tamil workflow blockers: **0**

Frozen English-translation authorities:

1. `திராவிட சம்பத்து` — scans **5–6, 13–16** — blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

P5 retained lexical-witness conflicts on scans **3, 4, 5 and 16**, preserved damaged scan-3 `அயம்`, retained the earlier scan-16 source-visible recovery `மொழி.`, and added the directly visible scan-15 recovery `கிரேக்க மொழி`. These are frozen source decisions for downstream translation.

The physical reading order remains:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

Publisher foreword `மன்றத்தில்`, publisher note `முக்கிய குறிப்பு` and scan-4 advertisements remain outside the two Kalaignar article bodies.

## English translation state

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 drafts: **1 / 2 PASS**
- T2 fidelity-reviewed: **0 / 2**
- T3 voice-reviewed: **0 / 2**
- T4 audited: **0 / 2**
- T5 verified: **0 / 2**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- English article bodies: **1 / 2**
- translation blockers: **0**

Canonical English workspace:

- `publications/thiraavida-sampaththu/TRANSLATION_PLAN.md`
- `publications/thiraavida-sampaththu/translations/en/README.md`
- `publications/thiraavida-sampaththu/translations/en/LEXICON.md`
- `publications/thiraavida-sampaththu/translations/en/TRANSLATION_REVIEW.md`
- `publications/thiraavida-sampaththu/translations/en/01-thiraavida-sampaththu.md`

## Article 1 T1 — COMPLETE / PASS

- Tamil title: `திராவிட சம்பத்து`
- working English title: **Dravidian Wealth** — not frozen
- frozen Tamil authority: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`
- T1 English draft blob: `bb5937921ab00d532d91bc89c5a9df57dc8acaa2`
- English metadata status: `draft`
- source scans: **5, 6, 13, 14, 15, 16**
- source-page comments: **6 / 6 present**
- scan-15/16 `SOURCE DAMAGE` gaps: **preserved / unreconstructed**
- frozen Tamil changes during T1: **0**

T1 translated every surviving Tamil paragraph in order and retained the article's directness, questions, sarcasm, insults, monkey/tail/poison imagery, quotation structure and page tracing. It deliberately did not perform T2 bilingual correction or T3 voice polishing.

Working Article 1 choices include `திராவிட சம்பத்து` → **Dravidian Wealth**, `விகடனார்` → **Vikatanar**, `நகைச்சுவை குரங்கார்` → **Comedy Monkey**, `ஆரிய ஆஞ்சநேயர்` → **Aryan Anjaneyar**, `இனவெறி` / `இனப்பற்று` → **racial hatred** / **attachment to one's race**, `ஆப்பசைத்த குரங்கு` → **wedge-meddling monkey**, `குப்பை மேட்டுக் குயில்கள்` → **cuckoos of the garbage heap**, and frozen anomalous `பேச்சுல` → provisional source-bearing **pechchul**. These are not release-frozen and must be tested at T2/T3/T4.

## Non-regression for English work

- preserve direct address, sarcasm, ridicule, rhetorical questions, repetition and exclamation;
- preserve source-page trace comments;
- retain Article 1 scan-15/16 `SOURCE DAMAGE` gaps without reconstruction;
- do not silently repair frozen `கல்லுரி`, `கண்னை`, `பேச்சுல` or damaged `அயம்` using alternate scan readings/context;
- do not import publisher matter or scan-4 advertisements into the two English article bodies;
- if a genuine source-supported Tamil correction changes a frozen blob, explicitly reopen affected translation gates.

## Current blockers

**None.** Irreversible physical source loss is documented and does not block translation of the surviving frozen Tamil witness.

---

# Exact next activity

Execute **Article 1 T2 — bilingual fidelity review** against frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015` and T1 English blob `bb5937921ab00d532d91bc89c5a9df57dc8acaa2`.

1. Re-fetch both blobs and compare every Tamil paragraph/clause with the T1 English draft.
2. Check for omitted or added claims, negatives, comparisons, logical connectors, repetitions, names/referents and quotation scope.
3. Confirm source-page comments for scans **5, 6, 13, 14, 15, 16** remain complete and ordered.
4. Audit both scan-15 and scan-16 damaged passages without reconstructing hidden Tamil wording.
5. Test every T1 working term against context; make only fidelity-required English corrections.
6. Record every T2 correction and unresolved source-sensitive choice in `translations/en/TRANSLATION_REVIEW.md` and update `LEXICON.md` where necessary.
7. Synchronize the English tracker, translation plan, publication README and this handover.
8. **Stop after T2. Do not perform T3 in the same activity.**

## Current blockers

**None.**