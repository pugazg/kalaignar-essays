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
5. `docs/NEXT_CHAT_PROMPT.md` when continuing the current active work in a fresh window
6. active publication README / metadata / fidelity / completion records
7. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Fresh-window continuation rule

- **Fetch live `main` first. Live `main` is authoritative.**
- `docs/NEXT_CHAT_PROMPT.md` is the current copy/paste continuation prompt, but it is a convenience summary only.
- Any checkpoint SHA in a prompt means “last confirmed when prepared”; it is **not** a rollback target.
- If `main` has advanced, preserve the newer durable state. Never reset, overwrite, repeat or reopen later completed work merely because an older prompt records an earlier boundary.
- Re-fetch target files before writing when another chat/window may also be active.
- Last confirmed live HEAD immediately before this handover synchronization: `eb97e85b35cc7b857291f2ed3772f2377ff098c8` — `Advance Unarchchimaalai translation plan to E7`.

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

# Publication 3 — உணர்ச்சிமாலை — TAMIL FROZEN / ENGLISH E6 PASS

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

## English progress

- T0 setup: **PASS**
- T1 drafts: **10 / 10**
- T2 fidelity-reviewed: **10 / 10**
- T3 voice-reviewed: **10 / 10**
- T4 audited: **10 / 10**
- T5 verified: **10 / 10**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **NOT STARTED**
- translation/body blockers: **0**

## Verified Articles 1–10 — unchanged by E6

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

All ten article bodies remain individually T5-verified. E6 required **0 English body corrections**, so all ten final English blob SHAs remain unchanged.

## Article 10 durable T5 boundary

- English title: **Not a Poem — an Ocean of Tears!**
- frozen Tamil: `f856664d86695237a23d0ffc0bef088d32a82fe9`
- source scans: **48–49**
- final T5 English: `cee8ea3c33495615ffc988a1875d71e40f8224a3`
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

### E6 correction result

- English body corrections required: **0**
- final article blob changes: **0 / 10**
- frozen Tamil changes: **0**
- source/fidelity defects discovered: **0**
- source/translation gates reopened: **No**
- blockers: **0**

### E6 consistent recurring decisions

- `திராவிடம்` → `Dravidam` remains stable in Articles 2, 5 and 7.
- `ஆரியம்` → `Aryanism` remains stable in Articles 6 and 10.
- `Tiruvitaththar` remains stable in Articles 1 and 10.
- `Oman Sea` remains stable in Articles 7 and 10.
- proletarian vocabulary, `God-ism`, `syrupy speech` and `javvadu` remain consistent where their source function recurs.

### E6 deliberate contextual/source-witness exceptions — NON-REGRESSION

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

### E6 anomaly/completeness result

- scan 19 source recovery / scan 20 numeral `1`: **PASS**
- scan 32 frozen irregular order: **PASS / unreconstructed**
- scan 33/34 boundary: **PASS**
- Article 7 deliberately incomplete ending: **PASS**
- scan 42 `No answer.` / scan 43 `* * *`: **PASS**
- scan 48 `ப்ழச்சளை` / scan 49 `You left.` placement: **PASS**
- scan 49 publication-close exclusion / scan 50 advertisement exclusion: **PASS**
- all ten article units and required source-page comments: **PASS**
- quotation boundaries, directness, sarcasm, ridicule, commands, rhetorical questions, exclamations and repetition: **PASS**

Canonical E6 provenance is recorded in:

- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/TRANSLATION_PLAN.md`

## Documentation reconciliation — COMPLETE / NON-DESTRUCTIVE

The Article 9/10 documentation reconciliation remains durable:

- pre-reconciliation lexicon history through Article 9 T4 is preserved byte-for-byte as `publications/unarchchimaalai/translations/en/LEXICON_HISTORY_THROUGH_ARTICLE9_T4.md`;
- pre-reconciliation review history through Article 9 T4 is preserved byte-for-byte as `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW_HISTORY_THROUGH_ARTICLE9_T4.md`;
- canonical `LEXICON.md` and `TRANSLATION_REVIEW.md` remain the current records and now include E6;
- history sidecars remain provenance only and must not replace canonical records.

## Fresh-window handoff

The repository contains:

- `docs/NEXT_CHAT_PROMPT.md` — current active-work continuation prompt;
- `docs/START_NEW_ESSAY_WORK_PROMPT.md` — reusable prompt for a genuinely new supplied work;
- `docs/FUTURE_WORK_GUIDELINES.md` — live-main continuation and E6/E7 gate discipline.

A fresh window must begin from live `main`, not conversational memory. The Tamil layer remains frozen. E6 found no source/fidelity defect and did not require source-PDF reopening.

---

# Exact next activity

Execute **E7 — English release closeout** for `உணர்ச்சிமாலை`.

Use the ten unchanged E6-passed English article blobs and the canonical lexicon/review records. Perform the release-closeout checks required by `ESSAY_TRANSLATION_GUIDE.md`, synchronize the release/tracker/handover records, and mark the English publication release complete only if E7 passes. Do not reopen or rewrite individual article bodies unless E7 identifies a genuine release-blocking or source-supported defect.

## Current blockers

**None.**