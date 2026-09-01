# Next Chat Prompt — Continue Kalaignar Essays / உணர்ச்சிமாலை

Use this prompt when continuing the **current active work** in a fresh chat/window. This file is a convenience handoff only; live `main` and the root `HANDOVER.md` are authoritative.

## Copy/paste prompt

Continue the Kalaignar Essays / Articles archival and English-translation project directly in:

`pugazg/kalaignar-essays`

Branch: `main`

Active publication:

`publications/unarchchimaalai/` — **உணர்ச்சிமாலை**

### LIVE MAIN IS AUTHORITATIVE

Fetch live `main` **first**. The last confirmed live HEAD immediately before this continuation prompt was synchronized was:

`ab36f6255069ca79b79d78e0ccaae0b7555e88c9` — `Prepare Kalaignar essays fresh-window handover`

If `main` has advanced beyond that checkpoint, preserve the newer durable state and continue from it. **Do not reset, overwrite, repeat or reopen later completed work merely because this prompt contains an older checkpoint.**

Before every write, re-fetch the target file and current live state as needed. Work directly on `main`.

### Mandatory startup

Before making any repository change, read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. `HANDOVER.md`
5. this `docs/NEXT_CHAT_PROMPT.md`
6. `publications/unarchchimaalai/README.md`
7. `publications/unarchchimaalai/metadata/source.md`
8. `publications/unarchchimaalai/VISUAL_TEXT_FIDELITY_REVIEW.md`
9. `publications/unarchchimaalai/PUBLICATION_COMPLETION_REVIEW.md`
10. `publications/unarchchimaalai/TRANSLATION_PLAN.md`
11. `publications/unarchchimaalai/translations/en/README.md`
12. `publications/unarchchimaalai/translations/en/LEXICON.md`
13. `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

The canonical lexicon/review records contain the current durable translation state. History sidecars should be consulted only when provenance before the Article 9/10 reconciliation is needed; do not replace canonical records with historical snapshots.

### Current durable boundary

Tamil archival layer is **COMPLETE / FROZEN**:

- physical scans: **50**
- P2 page records: **50/50 verified**
- P3 article assemblies: **10/10**
- P4: **PASS**
- P5 strict visual fidelity: **50/50 PASS**
- structural/punctuation/spacing/layout corrections propagated: **236**
- documented Gemini/source lexical conflicts retained under the publication-specific rule: **18**
- Tamil/body blockers: **0**

English article translation is complete through **T5 for all 10 articles**:

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

Progress:

- T0: **PASS**
- T1: **10/10**
- T2: **10/10**
- T3: **10/10**
- T4: **10/10**
- T5: **10/10**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- blockers: **0**

All ten articles are individually verified. Do not reopen an article unless E6 finds a genuine cross-article consistency defect or a source-supported problem.

### Publication-specific source rule — do not regress

For `உணர்ச்சிமாலை`, the user explicitly established that Gemini lexical tokens remain the working/frozen lexical baseline wherever Gemini supplied wording. The scan controls structure, punctuation, spacing, paragraphing, headings, page/article boundaries and documented physical/source witnesses. Scan/Gemini lexical disagreements are **logged, not silently substituted**.

English authority is the frozen Tamil assembly. Do not use an alternate scan-appearing lexical reading to “improve” English during E6.

Durable non-regression includes, among other recorded witnesses:

- scan 19 source-recovered Article 4 text;
- scan 20 visible printed numeral `1` only;
- frozen scan 32 irregular lexical/order sequence — deliberately unreconstructed;
- corrected scan 33/34 physical boundary;
- Article 7 frozen ending on scan 41 at `வரலாற்றை வீணாக்கிய`, with deliberately incomplete English ending;
- scan 42 source-recovered `பதில் இல்லை.`;
- scan 43 `* * *`;
- scan 48 frozen `ப்ழச்சளை` — never guess a repaired form;
- scan 49 frozen `விட்டாய்.` placement;
- scan 49 publication-source note/printer imprint outside Article 10;
- scan 50 advertisement outside all articles.

Source PDF is never committed.

### Permanent English rule

> **Translate the language; do not neutralise the voice.**

E6 must preserve Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, emotional temperature, imagery, exclamations and source-bearing oddities. Do not turn consistency review into stylistic homogenisation.

### EXACT NEXT ACTIVITY

Execute **E6 — publication-wide English consistency review** across all ten T5-verified articles.

Audit systematically:

- recurring names and author-chosen epithets;
- epic-name conventions and deliberate source-form differences;
- `Aryan`, `Aryanism`, `Dravidian`, `Dravidians`, `Dravidam` and related ideological vocabulary;
- `Brahmin`, `Parppanar`, `Parppaniyam`, `Vaidheegam` / contextual forms and other socially/religiously loaded terminology;
- recurring source-bearing transliterations, unexplained forms, puns and insults;
- source/publication titles, periodical titles and citation treatment;
- quotation boundaries and quoted-passage treatment;
- English title style across all ten articles;
- tone, directness, sarcasm, ridicule, commands, rhetorical questions, exclamations and repetition;
- accidental smoothing, harmonisation, modernisation or academic distancing introduced in later articles;
- all ten article units for completeness and retained page-boundary comments;
- all durable source anomalies listed above and in `HANDOVER.md`, `LEXICON.md` and `TRANSLATION_REVIEW.md`.

Pay particular attention to **deliberate contextual exceptions**. A different English form is not automatically an inconsistency. Preserve a difference when the frozen Tamil/source label or rhetorical function differs, and record the exception rather than mechanically harmonising it.

### E6 correction discipline

For every E6 finding:

- classify it as **consistent / deliberate contextual exception / correction required**;
- make a body change only when a genuine consistency defect is established against the frozen Tamil and established publication policy;
- never change frozen Tamil during E6;
- never import web wording, external history, alternate scan lexical forms or published translations;
- if an English body changes, update that article's final English blob SHA and record the exact E6 correction in the lexicon/review records;
- if a finding reveals an actual source/fidelity defect rather than a consistency issue, stop and reopen the affected source/translation gate explicitly instead of silently fixing it under E6;
- synchronize `translations/en/LEXICON.md`, `translations/en/TRANSLATION_REVIEW.md`, `translations/en/README.md`, `TRANSLATION_PLAN.md` and root `HANDOVER.md`.

After E6 passes, record **E6 PASS** and set the exact next activity to **E7 — English release closeout**.

**Do not execute E7 in the same activity.**

### Fresh-window execution rule

When the user says **“Proceed with next activity”**, do not ask them to restate context. Fetch live `main`, read the authoritative handover and current records, then execute the exact next activity completely.

At the end, report the E6 result, corrections/contextual exceptions, updated article SHAs if any, latest live `main` commit, blockers and exact next activity.
