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
- Last confirmed live HEAD immediately before this P2 handover synchronization: `7f2051bfbb4d67ba810cf6a5cce041228402aa89` — `Attach Ina Muzhakkam P2 scans 1-25 canonical pages`.

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

# Publication 5 — இன முழக்கம் — ACTIVE / P2 25 OF 50 VERIFIED

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

- supplied words are the lexical baseline for the current structural/P2 transfer;
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
- `publications/ina-muzhakkam/transcription-intake/USER_CORRECTIONS.md`
- `publications/ina-muzhakkam/pages/` — canonical P2 page records; scans 1–25 currently present/verified

## Structural corrections already established

- front-matter edition/date/price restored to scan 3; stamp/handwriting/OCR garbage removed from printed text;
- source speaker labels and `* * *` ornaments reattached correctly in `இன முழக்கம்`;
- **scan 10 correction:** `விசயர்` is not stray/noise. The user established that it is a misplaced supplied token and belongs after `கர்வத்தால் கனத்துப்போன கனக`, yielding `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில் கல்லேற்றி...`; this supersedes the earlier removal decision and is present in canonical P2 scan 10;
- stray trailing `2` removed from scan 22;
- scan-24 `திராவிட சம்பத்து` promotion separated from `சொர்க்க லோகத்தில்`;
- `பழிக்குப் பழி` final lines moved from supplied scan 36 to source scan 37;
- scan-37 two-novel promotion separated from article body;
- scan-40 author note/review separated from the poems;
- poetry lineation restored for scans 41–49;
- heading `வா!` moved to scan 43;
- heading `யோசித்துப் பார்!` moved to scan 44;
- scan-50 catalogue restored as a table/advertisement unit.

## P2 scans 1–25 durable result

- canonical page records: **25 / 25 created and direct-scan verified for this batch**;
- P2 total: **25 / 50 VERIFIED**;
- front matter scans 1–5 separated printed text from physical-copy marks;
- scan 6 article heading page carries `printed_page: null` because no numeral is directly visible;
- scans 7–13 visible printed numerals 6–12 recorded;
- scan 14 article heading page carries `printed_page: null`; contents witness `13` is not silently promoted to a visible numeral;
- scans 15–24 visible printed numerals 14–23 recorded;
- scan 25 article heading page carries `printed_page: null`; contents witness `24` is not silently promoted to a visible numeral;
- page-boundary continuations are recorded in audit notes;
- scan 24 article/promotion boundary is explicitly separated;
- scan 10 canonical text retains exact user correction `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 22 trailing `2` remains excluded as non-source noise;
- blockers found in scans 1–25: **0**.

## Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + page map: **COMPLETE**
- full supplied transcription structural reassembly: **COMPLETE / STAGING**, with `USER_CORRECTIONS.md` as a durable override for user-established placement corrections
- P2 canonical page records: **25 / 50 VERIFIED**
- P3 article/section assemblies: **0 / 6**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- unresolved lexical/source conflicts: **not yet classified; structural/P2 transfer intentionally does not silently alter words**
- blocked body readings: **0 known**

## English translation status

- English translation: **NOT STARTED**
- prerequisite: complete/freeze Tamil P2–P5 first

## Non-regression

- do not treat physical-copy marks as printed text;
- do not silently correct supplied lexical words during P2 structural transfer;
- **retain scan-10 `விசயர்` after `கர்வத்தால் கனத்துப்போன கனக`; never delete it as noise**;
- apply all entries in `transcription-intake/USER_CORRECTIONS.md` before canonical P2 text is written;
- preserve contents/page-number witnesses separately from directly visible printed numerals;
- preserve page-boundary word continuations;
- keep promotions/catalogue outside the five prose article bodies and poetry body;
- preserve poem headings on source scans;
- if scan pixels conflict lexically with the baseline, document the conflict and follow the publication-specific rule rather than silently substituting.

## Current blockers

**None.**

---

# Exact next activity

Create and directly verify **P2 canonical page records for scans 26–50** of `இன முழக்கம்` from the corrected staging transcription and `transcription-intake/USER_CORRECTIONS.md`.

Requirements:

1. inspect each scan directly;
2. create one `pages/` record per physical scan;
3. separate `# அச்சு உரை` from `## அச்சு அல்லாத / physical-copy marks`;
4. preserve the user lexical baseline while applying established structural corrections and user-correction overrides;
5. record printed page numerals only when directly visible;
6. preserve page-to-page continuations, article boundaries, promotional matter and catalogue boundaries;
7. preserve poetry headings and source lineation on scans 41–49;
8. update page map/README/handover after the batch;
9. **stop after scans 26–50 P2**; do not begin P3 assemblies in the same activity.

## Current blockers

**None.**