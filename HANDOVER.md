# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, transcription, fidelity, translation or release activity.**

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. this `HANDOVER.md`
5. `docs/NEXT_CHAT_PROMPT.md` when continuing current work in a fresh window
6. the active publication README / metadata / indexes / staging / fidelity records
7. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Fresh-window continuation rule

- **Fetch live `main` first. Live `main` is authoritative.**
- `docs/NEXT_CHAT_PROMPT.md` is a convenience summary only and never overrides live `main` or this handover.
- Any checkpoint SHA is the last confirmed state when written; it is **not** a rollback target.
- If `main` has advanced, preserve the newer durable state. Never reset, overwrite, repeat or reopen later completed work because an older prompt records an earlier boundary.
- Re-fetch target files immediately before writes when another window may also be active.
- Last confirmed live HEAD immediately before this new-publication handover synchronization: `57e29b27d3360f7ac3b215d6873760b25d71d822` — `Create Ina Muzhakkam publication workspace`.

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

- Tamil P0–P5: **COMPLETE / FROZEN**
- English T0–T5: **2 / 2 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- English translation: **COMPLETE / RELEASED / FROZEN**
- blockers: **0**

Released English authorities:

1. **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 5 — இன முழக்கம் — ACTIVE / P1 COMPLETE / STRUCTURAL INTAKE COMPLETE

Workspace: `publications/ina-muzhakkam/`  
Supplied source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## Source identity

- source title: **இன முழக்கம்**
- title-page author: **கலைஞர் கருணாநிதி**
- cover author witness: visibly different abbreviated form; lexical resolution deferred rather than silently normalised
- first edition: **செப்டம்பர் 1951**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- price: **அணா 0-8-0**
- printer: **கே. ஜி. பிரஸ், சென்னை—1**
- physical scans: **50**
- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- file size: **68,109,788 bytes**
- source PDF committed: **No**

## Publication-specific source rule — USER ESTABLISHED

The user supplied a complete word-to-word transcription and instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Therefore:

- supplied words are the lexical baseline for the current structural pass;
- scan controls page placement, paragraph order, punctuation/quotation structure, headings, speaker labels, poetry lineation and physical-copy evidence;
- library stamps, handwriting, accession marks and OCR garbage are excluded from printed text and recorded separately when useful;
- no lexical token may be silently modernised/substituted during structural work;
- scan/baseline lexical disagreements discovered during review must be documented for P2/P5 rather than silently corrected.

## Printed contents witness

1. `இன முழக்கம்` — `4`
2. `சொர்க்க லோகத்தில்` — `13`
3. `முரசறைவாய்` — `24`
4. `பழிக்குப் பழி` — `29`
5. `ஆரியம் பேசுகிறது` — `37`
6. `கவிதைகள்` — `40`

Preserve this contents witness independently from body-page numerals.

## Publication structure / boundaries

- scans 1–5 — cover/title/imprint/contents/`பதிப்புரை`
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

Canonical intake records:

- `publications/ina-muzhakkam/README.md`
- `publications/ina-muzhakkam/metadata/source.md`
- `publications/ina-muzhakkam/indexes/contents.md`
- `publications/ina-muzhakkam/indexes/page-map.md`
- `publications/ina-muzhakkam/STRUCTURAL_REASSEMBLY_REVIEW.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0001-0020.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0021-0040.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0041-0050.md`

## Structural corrections already applied to staging transcription

- front-matter edition/date/price restored to scan 3; stamp/handwriting/OCR garbage removed from printed text;
- source speaker labels and `* * *` ornaments reattached correctly in `இன முழக்கம்`;
- stray `விசயர்` removed from scan 10;
- stray trailing `2` removed from scan 22;
- scan-24 `திராவிட சம்பத்து` promotion separated from `சொர்க்க லோகத்தில்`;
- `பழிக்குப் பழி` final lines moved from supplied scan 36 to source scan 37;
- scan-37 two-novel promotion separated from article body;
- scan-40 author note/review separated from the poems;
- poetry lineation restored for scans 41–49;
- heading `வா!` moved to scan 43;
- heading `யோசித்துப் பார்!` moved to scan 44;
- scan-50 catalogue restored as a table/advertisement unit.

## Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + page map: **COMPLETE**
- full supplied transcription structural reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **0 / 50**
- P3 article/section assemblies: **0 / 6**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- unresolved lexical/source conflicts: **not yet classified; structural pass intentionally did not alter words**
- blocked body readings: **0 known at intake**

## English translation status

- English translation: **NOT STARTED**
- prerequisite: complete/freeze Tamil P2–P5 first

## Non-regression

- do not treat physical-copy marks as printed text;
- do not silently correct supplied lexical words during P2 structural transfer;
- preserve contents/page-number witnesses separately;
- preserve page-boundary word continuations;
- keep promotions/catalogue outside the five prose article bodies and poetry body;
- preserve poem headings on source scans;
- if scan pixels conflict lexically with the baseline, document the conflict and follow the publication-specific rule rather than silently substituting.

## Current blockers

**None.**

---

# Exact next activity

Create and directly verify **P2 canonical page records for scans 1–25** of `இன முழக்கம்` from the corrected staging transcription.

Requirements:

1. inspect each scan directly;
2. create one `pages/` record per physical scan;
3. separate `# அச்சு உரை` from `## அச்சு அல்லாத / physical-copy marks`;
4. preserve the user lexical baseline while applying the already-established structural corrections;
5. record printed page numerals only when directly visible;
6. preserve continuations and article/promotion boundaries;
7. update page map/README/handover after the batch;
8. **stop after scans 1–25 P2**; do not begin P3 assemblies in the same activity.

## Current blockers

**None.**