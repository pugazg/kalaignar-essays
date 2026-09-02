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
6. the active publication README / metadata / fidelity / completion records
7. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Fresh-window continuation rule

- **Fetch live `main` first. Live `main` is authoritative.**
- `docs/NEXT_CHAT_PROMPT.md` is a convenience summary only and never overrides live `main` or this handover.
- Any checkpoint SHA is the last confirmed state when written; it is **not** a rollback target.
- If `main` has advanced, preserve the newer durable state. Never reset, overwrite, repeat or reopen later completed work because an older prompt records an earlier boundary.
- Re-fetch target files immediately before writes when another window may also be active.
- Last confirmed live HEAD immediately before this E7 handover synchronization: `b2f18870ff4ba01e8851453b26a57f29da9ea245` — `Finalize Thiraavida Sampaththu metadata at release`.

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

- physical scans: **50**
- Tamil P2: **50 / 50**
- Tamil P3: **10 / 10**
- P4: **PASS**
- P5: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- English T0–T5: **10 / 10 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 4 — திராவிட சம்பத்து — RELEASE COMPLETE / FROZEN

Workspace: `publications/thiraavida-sampaththu/`  
Source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`

## Source identity

- title: **திராவிட சம்பத்து**
- author: **கலைஞர் மு. கருணாநிதி**
- edition: **முதல பதிப்பு, செப்டம்பர் 1951**
- publisher: **அறிவு மன்றம், சென்னை-1**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை-1**
- physical scans: **16**
- source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- source PDF committed: **No**

## Publication-specific source rule — USER ESTABLISHED

The user-supplied transcription is the lexical baseline for surviving Tamil words. The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, boundaries and physical-copy evidence. Scan/baseline lexical disagreements are documented rather than silently substituted. Text physically lost under torn-away paper is never reconstructed from context.

Reconstructed publication reading order:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

## Frozen Tamil archival state — COMPLETE / FROZEN

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **2 / 2 COMPLETE**
- P4: **PASS**
- P5: **16 / 16 PASS**
- hidden torn text reconstructed: **0**
- silent lexical substitutions: **0**
- Tamil blockers: **0**

Frozen Tamil authorities:

1. `திராவிட சம்பத்து` — scans **5–6, 13–16** — `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

## Final English translation / release state

- E0: **COMPLETE / PASS**
- T0: **2 / 2 PASS**
- T1: **2 / 2 PASS**
- T2: **2 / 2 PASS**
- T3: **2 / 2 PASS**
- T4: **2 / 2 PASS**
- T5: **2 / 2 PASS**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- translation/release blockers: **0**

Released English authorities:

1. **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Both English article files retain `translation_status: verified`; E7 is the publication-level release closeout.

## E7 durable release checks

- E6-passed English blobs still match live article authorities: **2 / 2 PASS**
- frozen Tamil blobs unchanged: **2 / 2 PASS**
- T0–T5 remain durable: **PASS**
- E6 remains durable: **PASS**
- English body changes after E6: **0 / 2**
- English metadata changes after E6: **0 / 2**
- frozen Tamil changes during E7: **0**
- source/translation gates reopened: **No**
- source/release defects discovered: **0**
- release blockers: **0**

## Publication 4 non-regression

- do not reconstruct torn-away source wording;
- preserve the frozen Tamil lexical witness and documented source-witness distinctions;
- preserve source-page trace comments and documented damage boundaries;
- do not import publisher matter or the final advertisement into the two Kalaignar article translations;
- do not reopen released English articles for stylistic preference, conventionalisation or cross-article homogenisation;
- reopen only for a genuine source-supported or release-blocking defect.

**Publication 4 status: COMPLETE / FROZEN / RELEASED in Tamil and English.**

---

# Current project state / next activity

Publications **1–4 are COMPLETE / FROZEN / RELEASED**. There is no pending review gate in the current active publication.

**Next project activity:** intake of the next supplied Kalaignar essay/article publication. When a new source is supplied, fetch live `main`, follow the permanent processing guide, create the new publication workspace and source intake records, and do not reopen Publications 1–4 absent a genuine source-supported or release-blocking defect.

## Current blockers

**None.**