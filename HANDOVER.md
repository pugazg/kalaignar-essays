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
- Last confirmed live HEAD immediately before this P4 handover synchronization: `2e7b684b1a88dd5e6707dc0f9a09fbbcd9df777f` — `Advance root status through Ina Muzhakkam P4 completion`.

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

# Publication 5 — இன முழக்கம் — ACTIVE / P4 COMPLETE

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
- `publications/ina-muzhakkam/SOURCE_COMPLETENESS_AUDIT.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0001-0020.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0021-0040.md`
- `publications/ina-muzhakkam/transcription-intake/scans-0041-0050.md`
- `publications/ina-muzhakkam/transcription-intake/USER_CORRECTIONS.md`
- `publications/ina-muzhakkam/pages/` — **50 / 50 canonical P2 page records present and verified**
- `publications/ina-muzhakkam/articles/` — **6 / 6 P3 reading assemblies present**

## Structural corrections already established

- front-matter edition/date/price restored to scan 3; stamp/handwriting/OCR garbage removed from printed text;
- source speaker labels and `* * *` ornaments reattached correctly in `இன முழக்கம்`;
- **scan 10 correction:** `விசயர்` is not stray/noise. The user established that it is a misplaced supplied token and belongs after `கர்வத்தால் கனத்துப்போன கனக`, yielding `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில் கல்லேற்றி...`; this is present in canonical P2 scan 10 and the P3 assembly;
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

## P3 durable result — COMPLETE

Exactly six contents-listed assemblies were created directly from canonical P2 records:

1. `articles/01-ina-muzhakkam.md` — `இன முழக்கம்` — scans 6–13 — blob `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`;
2. `articles/02-sorgga-logaththil.md` — `சொர்க்க லோகத்தில்` — scans 14–24 — blob `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`;
3. `articles/03-murasaraivai.md` — `முரசறைவாய்` — scans 25–29 — blob `698c178ee5a65e9fe53543be2136e6691f5a8dad`;
4. `articles/04-pazhikku-pazhi.md` — `பழிக்குப் பழி` — scans 30–37 — blob `d9c57a7a55ab33310b512c34322186cc55a04ef8`;
5. `articles/05-aariyam-pesugirathu.md` — `ஆரியம் பேசுகிறது` — scans 38–39 — blob `651063d641ddbc53c1688e92b13d976b169d04ee`;
6. `articles/06-kavithaigal.md` — `கவிதைகள்` — scans 41–49 — blob `a11dfc65bfd83c316e090c793f1ede102a72ac21`.

P3 checks:

- page-boundary comments/provenance preserved;
- no assembly was built from the staging transcript;
- scan-10 `விசயர்` placement retained exactly;
- scan-24 `திராவிட சம்பத்து` promotion excluded from Article 2;
- scan-37 two-novel promotion excluded from Article 4;
- scan-40 author/review matter excluded from the poetry body;
- scan-50 catalogue excluded from all six assemblies;
- poem headings and source lineation from scans 41–49 preserved;
- lexical normalisation introduced: **0**;
- P3 blockers: **0**.

## P4 durable result — PASS / COMPLETE

Audit record: `publications/ina-muzhakkam/SOURCE_COMPLETENESS_AUDIT.md`.

P4 audited the full canonical P2 layer and all six P3 assemblies and confirmed:

- physical scans represented by canonical P2 records: **50 / 50 PASS**;
- contents-listed P3 assemblies: **6 / 6 present exactly once**;
- source-supported start/end boundaries: **6 / 6 PASS**;
- page-to-page continuations and provenance comments: **PASS**;
- scan-10 `விசயர்` placement: **PASS**;
- scan-24 and scan-37 promotional matter excluded from article bodies: **PASS**;
- scan-40 `கவிதைகளைப் பற்றி` / `மதிப்புரை` excluded from `கவிதைகள்`: **PASS**;
- scan-50 catalogue excluded from all body assemblies: **PASS**;
- poetry headings and verse lineation: **PASS**;
- contents-page start-number witnesses kept distinct from directly visible body numerals: **PASS**;
- physical-copy marks imported into printed/body text: **0**;
- silent lexical normalisations introduced during P2/P3: **0**;
- P4 `needs-review` items: **0**;
- P4 blocked items: **0**;
- unresolved body-completeness blockers: **0**.

Deferred for explicit P5 source-fidelity classification rather than silent correction:

1. **cover-author witness** — visible scan witness `மு. கருணாநிதி` versus supplied lexical baseline `கலைஞர் கருணாநிதி`;
2. **scan-50 catalogue** — documented lexical/number differences or omissions, including `அழகு நிலா` / `செல்வ குமாரி` price forms and the missing `நாடறிந்த நட்சத்திரங்கள்` price.

These are not P4 completeness blockers. They must be checked and classified explicitly during P5 under the user-established lexical rule.

## Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + page map: **COMPLETE**
- full supplied transcription structural reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 article/section assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4 source/completeness audit: **PASS / COMPLETE**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- blocked body readings: **0 known**

## English translation status

- English translation: **NOT STARTED**
- prerequisite: complete/freeze Tamil P5 first

## Non-regression

- do not treat physical-copy marks as printed text;
- do not silently correct supplied lexical words;
- **retain scan-10 `விசயர்` after `கர்வத்தால் கனத்துப்போன கனக`; never delete it as noise**;
- apply all entries in `transcription-intake/USER_CORRECTIONS.md` downstream;
- preserve contents/page-number witnesses separately from directly visible printed numerals;
- preserve page-boundary word continuations;
- keep promotions/catalogue outside the five prose article bodies and poetry body;
- preserve poem headings and source lineation;
- preserve scan 40 as poetry front matter, outside the `கவிதைகள்` assembly;
- if scan pixels conflict lexically with the baseline, document the conflict and follow the publication-specific rule rather than silently substituting;
- preserve the P4 classification of the cover-author and scan-50 catalogue issues as deferred P5 fidelity items, not completeness blockers.

## Current blockers

**None.**

---

# Exact next activity

Proceed with **P5 strict visual word/punctuation fidelity** over all **50 physical scans**.

P5 must:

1. directly re-check every physical scan, including cover, front matter, contents, all body pages, promotions, poetry front matter and catalogue;
2. compare every visible printed word, word boundary, punctuation mark, quotation mark, heading, date, number, paragraph continuation and source witness against the canonical page record;
3. preserve the user-supplied lexical baseline and **not silently substitute alternate scan-appearing lexical tokens**;
4. explicitly classify every scan/baseline lexical disagreement found;
5. retain scan-10 `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...` exactly;
6. explicitly inspect and classify the deferred cover-author witness;
7. explicitly inspect and classify the deferred scan-50 catalogue lexical/number differences and omissions;
8. re-confirm scan-24/37 promotion boundaries, scan-40 poetry-front-matter boundary and scan-50 body exclusion;
9. preserve all poetry headings and verse lineation;
10. record every P5 source-supported structural/punctuation/spacing correction with old reading → source-visible reading provenance;
11. propagate every P5 correction to affected page records, P3 assemblies, indexes and documentation;
12. create/update `publications/ina-muzhakkam/VISUAL_TEXT_FIDELITY_REVIEW.md` with physical scans checked, corrections, source/baseline conflicts, blocked/needs-review counts and final result;
13. recheck all six P3 assemblies against the P5-corrected page layer before freezing Tamil;
14. mark P5 complete/freeze Tamil only when all 50 scans and all six assemblies pass with no unresolved body-text blocker.

**Stop after P5. Do not begin English translation in the same activity.**

## Current blockers

**None.**