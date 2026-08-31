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
5. active publication README / metadata / fidelity / completion records
6. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows the permanent rule: **Translate the language; do not neutralise the voice.**

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14 complete**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is found.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

- Tamil page records: **17 / 17 verified**
- P5 strict visual fidelity: **17 / 17 PASS**
- Tamil source: **COMPLETE / FROZEN**
- frozen Tamil authority: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- verified English article blob: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`
- English release: **COMPLETE**
- unresolved blockers: **0**

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is found.

---

# Publication 3 — உணர்ச்சிமாலை — TAMIL FROZEN / ENGLISH ACTIVE

Workspace: `publications/unarchchimaalai/`

## Publication-specific lexical rule

For this publication only, the user established that Gemini word tokens are the Tamil lexical baseline wherever supplied. Scan/Gemini disagreements are documented rather than silently substituted. English translates the **frozen Tamil assemblies**, not an alternate scan reading.

## Tamil archival state — COMPLETE / FROZEN

- physical scans: **50**
- P2 page records: **50 / 50 verified**
- P3 assemblies: **10 / 10**
- P4: **PASS**
- P5 strict visual fidelity: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- P5 structural/punctuation/spacing/layout corrections: **236 propagated**
- documented Gemini/source lexical conflicts retained: **18**
- unresolved Tamil blockers: **0**

Durable non-regression includes scan-19 source recovery, frozen scan-32 word/order sequence, corrected scan-33/34 boundary, Article 7 ending on scan 41, recovered scan-42 `பதில் இல்லை.`, scan-43 `* * *`, frozen scan-48 `ப்ழச்சளை`, frozen scan-49 `விட்டாய்.` placement, scan-49 publication-close matter outside Article 10, and scan-50 advertisement outside all articles.

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

Any later Tamil correction reopens affected English gates.

## English setup — T0 COMPLETE / PASS

Active files:

- `publications/unarchchimaalai/TRANSLATION_PLAN.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

## Article 1 — `உணர்ச்சி மாலை`

Frozen Tamil authority: `c63837a9f7c02d6f3a18171a512d46788f66ad92`  
English file: `publications/unarchchimaalai/translations/en/01-unarchchi-maalai.md`  
English title: **Garland of Emotion**

### T1 — COMPLETE / PASS

Complete close draft from scans 6–9; scan comments and quoted lineation retained; no outside/web translation imported.

### T2 — COMPLETE / PASS

- metadata status: **`fidelity-reviewed`**
- title **Garland of Emotion**: T2-confirmed
- `Aththaan`: retained source-bearing without unsupported relationship gloss
- frozen `திருவிடத்தார்`: `Tiruvitaththar` retained source-sensitively
- frozen `இளைக் காத எழுத்துக்கள்`: `writings that do not tire`
- source `தெம்மாங்கு`: source-bearing `themmangu`
- `வெள்ளம்போல் தமிழர்...` stanza: revised and checked line by line
- invented T1 quotation marks around the Rama/Kali prose: removed
- documented T2 fidelity corrections: **11**
- scan comments 6–9 / verse lineation: **PASS**
- Tamil source changed: **No**
- outside/web wording imported: **No**
- unresolved T2 blockers: **0**

Detailed correction provenance: `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`.

## English progress

- T0: **PASS**
- T1 drafts: **1 / 10**
- T2 fidelity-reviewed: **1 / 10**
- T3 voice-reviewed: **0 / 10**
- T4 audited: **0 / 10**
- T5 verified: **0 / 10**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- unresolved translation blockers: **0**

---

# Exact next activity

Execute **Article 1 T3 — Kalaignar voice review** for `Garland of Emotion` against frozen Tamil blob `c63837a9f7c02d6f3a18171a512d46788f66ad92`.

T3 must preserve every T2 meaning/source decision while checking cadence, directness, commands, rhetorical questions, repetition, exclamations, imagery and argumentative force. Make only meaning-neutral voice/cadence corrections. Retain scan comments 6–9 and verse lineation. Advance to `translation_status: voice-reviewed` only if T3 passes. **Stop before T4.**

## Current blockers

**None.**
