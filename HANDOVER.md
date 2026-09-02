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
- Last confirmed live HEAD immediately before this P2-completion handover synchronization: `55c934729b2318c37e4320e93454e4d96ad4f159` — `Mark Ina Muzhakkam P2 complete`.

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

# Publication 5 — இன முழக்கம் — ACTIVE / P2 COMPLETE

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

- supplied words are the lexical baseline for the archival transfer;
- scan controls page placement, paragraph order, punctuation/quotation structure, headings, speaker labels, poetry lineation and physical-copy evidence;
- library stamps, handwriting, accession marks and OCR garbage are excluded from printed text and recorded separately when useful;
- no lexical token may be silently modernised/substituted;
- scan/baseline lexical disagreements must be documented for fidelity handling rather than silently corrected.

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

Canonical records:

- `publications/ina-muzhakkam/README.md`
- `publications/ina-muzhakkam/metadata/source.md`
- `publications/ina-muzhakkam/indexes/contents.md`
- `publications/ina-muzhakkam/indexes/page-map.md`
- `publications/ina-muzhakkam/STRUCTURAL_REASSEMBLY_REVIEW.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0001-0020.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0021-0040.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0041-0050.md`
- `publications/ina-muzhakkam/transcription-intake/USER_CORRECTIONS.md`
- `publications/ina-muzhakkam/pages/` — **50 / 50 canonical P2 page records present and verified**

## Structural corrections already established

- front-matter edition/date/price restored to scan 3; stamp/handwriting/OCR garbage removed from printed text;
- source speaker labels and `* * *` ornaments reattached correctly in `இன முழக்கம்`;
- **scan 10 correction:** `விசயர்` is not stray/noise. The user established that it is a misplaced supplied token and belongs after `கர்வத்தால் கனத்துப்போன கனக`, yielding `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில் கல்லேற்றி...`; this is present in canonical P2 scan 10;
- stray trailing `2` removed from scan 22;
- scan-24 `திராவிட சம்பத்து` promotion separated from `சொர்க்க லோகத்தில்`;
- `பழிக்குப் பழி` final lines moved from supplied scan 36 to canonical scan 37;
- scan-37 two-novel promotion separated from article body;
- scan-40 author note/review separated from the poems;
- poetry lineation restored for scans 41–49;
- heading `வா!` placed on scan 43;
- heading `யோசித்துப் பார்!` placed on scan 44;
- scan-50 catalogue restored as a structured catalogue rather than running prose.

## P2 durable result — COMPLETE

- scans 1–25: **25 / 25 VERIFIED**;
- scans 26–50: **25 / 25 VERIFIED**;
- P2 total: **50 / 50 VERIFIED / COMPLETE**;
- printed text and physical-copy marks are separated on all page records;
- printed numerals are recorded only when directly visible;
- heading scans **6, 14, 25, 30 and 38** use `printed_page: null`; contents-page start numbers remain separate witnesses;
- page-boundary continuations are documented;
- scan 24 and scan 37 promotion boundaries are explicit;
- scan 40 remains outside the poetry body;
- scans 41–49 retain source-supported poem headings and lineation;
- scan 50 remains a catalogue outside body units; structural row/column placement was corrected without silently manufacturing missing/different lexical tokens;
- P2 blockers: **0**.

Known source/baseline points deliberately deferred rather than silently rewritten include the cover-author witness and scan-50 catalogue lexical/number differences or omissions. These belong to later fidelity documentation under the user-established lexical rule.

## Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + page map: **COMPLETE**
- full supplied transcription structural reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 article/section assemblies: **0 / 6**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- blocked body readings: **0 known**

## English translation status

- English translation: **NOT STARTED**
- prerequisite: complete/freeze Tamil P3–P5 first

## Non-regression

- do not treat physical-copy marks as printed text;
- do not silently correct supplied lexical words;
- **retain scan-10 `விசயர்` after `கர்வத்தால் கனத்துப்போன கனக`; never delete it as noise**;
- apply all entries in `transcription-intake/USER_CORRECTIONS.md` downstream;
- preserve contents/page-number witnesses separately from directly visible printed numerals;
- preserve page-boundary word continuations;
- keep promotions/catalogue outside the five prose article bodies and poetry body;
- preserve poem headings and source lineation;
- preserve scan 40 as poetry front matter, outside the `கவிதைகள்` assembly unless separately represented as front matter;
- if scan pixels conflict lexically with the baseline, document the conflict and follow the publication-specific rule rather than silently substituting.

## Current blockers

**None.**

---

# Exact next activity

Proceed with **P3 article/section assembly** from the verified P2 page layer.

Create exactly the six contents-listed reading assemblies:

1. `இன முழக்கம்` — scans 6–13;
2. `சொர்க்க லோகத்தில்` — scans 14–24, excluding the scan-24 `திராவிட சம்பத்து` promotion;
3. `முரசறைவாய்` — scans 25–29;
4. `பழிக்குப் பழி` — scans 30–37, excluding the scan-37 two-novel promotion;
5. `ஆரியம் பேசுகிறது` — scans 38–39;
6. `கவிதைகள்` — scans 41–49, preserving every source-visible poem heading and verse lineation.

Requirements:

- assemble from canonical P2 records, not the original staging transcript;
- preserve source wording and punctuation as represented in P2;
- preserve page-boundary comments/provenance;
- retain scan-10 `விசயர்` placement exactly;
- do not import front matter, scan 40 author/review matter, promotions or scan-50 catalogue into the six body assemblies;
- update README/handover/index records after all six assemblies;
- **stop after P3**; do not begin P4 in the same activity.

## Current blockers

**None.**