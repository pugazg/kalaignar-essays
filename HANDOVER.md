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
- Last confirmed live HEAD immediately before this handover synchronization: `f32cdeae2742d0ad6e7a87522e3591572afab1a5` — `Advance Thiraavida Sampaththu metadata through Article 2 T5`.

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
- E6 publication-wide English consistency review: **PASS**
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

## Release boundary

**உணர்ச்சிமாலை is COMPLETE / FROZEN / RELEASED in Tamil and English.** Do not reopen it for stylistic polishing, conventionalisation or terminology homogenisation. Reopen only for a genuine source-supported or release-blocking defect.

---

# Publication 4 — திராவிட சம்பத்து — ACTIVE / ARTICLE 2 T5 PASS

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

P5 retained lexical-witness conflicts on scans **3, 4, 5 and 16**, preserved damaged scan-3 `அயம்`, retained the scan-16 source-visible recovery `மொழி.`, and added the directly visible scan-15 recovery `கிரேக்க மொழி`. These remain frozen source decisions.

## English translation state

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **2 / 2 PASS**
- T1 drafts: **2 / 2 PASS**
- T2 fidelity-reviewed: **2 / 2 PASS**
- T3 voice-reviewed: **2 / 2 PASS**
- T4 audited: **2 / 2 PASS**
- T5 verified: **2 / 2 PASS**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- English article bodies: **2 / 2**
- translation blockers: **0**

Canonical English workspace:

- `publications/thiraavida-sampaththu/TRANSLATION_PLAN.md`
- `publications/thiraavida-sampaththu/translations/en/README.md`
- `publications/thiraavida-sampaththu/translations/en/LEXICON.md`
- `publications/thiraavida-sampaththu/translations/en/TRANSLATION_REVIEW.md`
- `publications/thiraavida-sampaththu/translations/en/01-thiraavida-sampaththu.md`
- `publications/thiraavida-sampaththu/translations/en/02-aiyar-arivikkirar.md`

## Article 1 verified durable boundary

- Tamil title: `திராவிட சம்பத்து`
- English title: **Dravidian Wealth — VERIFIED**
- frozen Tamil authority: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`
- final verified English blob: `10dca72882043db491fe8c6ad3f858bc4c9c584f`
- English metadata status: `verified`
- unresolved Article 1 blockers: **0**

## Article 2 verified durable boundary

- Tamil title: `ஐயர் அறிவிக்கிறார்!`
- English title: **Iyer Announces! — VERIFIED**
- frozen Tamil authority: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`
- source scans: **12, 3**
- T0–T5: **COMPLETE / PASS**
- T1 English draft blob: `1b70952ae377668162fcb35eb045e142a0597190`
- T2 fidelity-reviewed English blob: `b7361d26a711d61938da24d33b3512ddf5653e53`
- T3 voice-reviewed English blob: `ace9ff13b1c45bfe6d7c4c99571bc9b9b7b7ac7c`
- T4 source-audited English blob: `9b2795e6c66dea08fdf46fcf7903550001e1a401`
- final T5 verified English blob: `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`
- English metadata status: `verified`
- source-page comments: **2 / 2 present and ordered**
- `ஐயர்` / `அய்யர்`: **Iyer / Ayyar** distinction retained
- damaged/ambiguous frozen `அயம்`: source-bearing **ayam**, not repaired
- `ஏனோதானோ` / `ஏனோதானோக்கள்`: **Enothano / Enothanos**, source-bearing / no outside identification
- normal `கல்லூரி`: **College**; frozen scan-3 `கல்லுரி`: source-bearing **kalluri**
- narrative fused `சாமிநாதய்யர்`: **Saminathayyar**; inscription `சாமிநாத அய்யர்`: **Saminatha Ayyar**
- quoted inscription: source-bearing **Maha Mahopadhyaya Dravida Vidya Bhushana Dr. Saminatha Ayyar**
- first-paragraph irregular quotation punctuation: two evident English quoted units formally audited at T4 and re-verified at T5; no missing Tamil punctuation reconstructed
- T5 English body corrections: **0**
- frozen Tamil changes during T5: **0**
- external inscription wording imported: **No**
- unresolved T5 blockers: **0**

## Non-regression for English work

- both articles are individually verified; do not alter either merely for stylistic preference;
- preserve direct address, sarcasm, ridicule, rhetorical questions, repetition and exclamation;
- preserve source-page trace comments;
- never reconstruct torn-away source wording;
- do not silently repair frozen `கல்லுரி`, `கண்னை`, `பேச்சுல` or damaged `அயம்` using alternate scan readings/context;
- do not import publisher matter or scan-4 advertisements into the two English article bodies;
- preserve Article 2 verified source-form distinctions, including `Iyer` / `Ayyar`, `ayam`, `Enothano(s)`, `kalluri`, `Saminathayyar` / `Saminatha Ayyar`;
- preserve the documented two-unit quotation treatment and source-bearing inscription wording;
- E6 may reopen an article only for a genuine publication-level consistency or source/release defect, and any reopened gate must be explicitly documented;
- if a genuine source-supported Tamil correction changes a frozen blob, explicitly reopen affected translation gates.

## Current blockers

**None.** Irreversible physical source loss is documented and does not block translation of the surviving frozen Tamil witness.

---

# Exact next activity

Execute **E6 — publication-wide English consistency review** across both verified English articles.

1. Re-fetch both verified English article blobs and both frozen Tamil authorities.
2. Review recurring `Dravidam` / Dravidian terminology and source-bearing name forms across both articles.
3. Review title style, quotation treatment, source-page comments and source-anomaly preservation.
4. Check rhetorical consistency and ensure no accidental cross-article harmonisation has flattened source distinctions.
5. Do not alter verified text merely for stylistic preference; change only a genuine publication-level consistency or source/release defect and explicitly document any reopened article gate.
6. Synchronize the translation review, lexicon/tracker/plan, publication records, root handover and continuation prompt.
7. **Stop after E6. Do not perform E7 in the same activity.**

## Current blockers

**None.**