# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, transcription, fidelity, translation or release activity.**

## Mandatory startup

Before changing anything:

1. read `ESSAY_PROCESSING_GUIDE.md` completely;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely when English is in scope;
3. read `docs/FUTURE_WORK_GUIDELINES.md` completely;
4. fetch live `main` and read this `HANDOVER.md` completely;
5. read `docs/NEXT_CHAT_PROMPT.md` only as a convenience summary;
6. read the active publication README / metadata / indexes / audit / fidelity records;
7. for active `இன முழக்கம்` P5, also read `publications/ina-muzhakkam/P5_PAGE_BY_PAGE_POLICY.md`.

Source PDFs are never committed. English translation follows: **Translate the language; do not neutralise the voice.**

## Live-main rule

- **Live `main` is authoritative.**
- Never reset, overwrite, repeat or reopen later durable work because an older prompt records an earlier checkpoint.
- Re-fetch target files before writes.
- Last confirmed live HEAD immediately before this handover synchronization: `41ee22d297bedfa93e641398915ffad34c8dbd3c` — `Lock Ina Muzhakkam P5 page-by-page policy`.

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
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 3 — உணர்ச்சிமாலை — RELEASE COMPLETE / FROZEN

- physical scans: **50**
- Tamil P2: **50 / 50**
- Tamil P3: **10 / 10**
- P4: **PASS**
- P5: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- English T0–T5: **10 / 10 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 4 — திராவிட சம்பத்து — RELEASE COMPLETE / FROZEN

Workspace: `publications/thiraavida-sampaththu/`

- Tamil P0–P5: **COMPLETE / FROZEN**
- English T0–T5: **2 / 2 PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- blockers: **0**

Released English authorities:

1. **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`.
2. **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`.

Do not reopen without a genuine source-supported or release-blocking defect.

---

# Publication 5 — இன முழக்கம் — ACTIVE / P5 IN PROGRESS

Workspace: `publications/ina-muzhakkam/`  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## Source identity

- title: **இன முழக்கம்**
- title-page author: **கலைஞர் கருணாநிதி**
- first edition: **செப்டம்பர் 1951**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- price: **அணா 0-8-0**
- printer: **கே. ஜி. பிரஸ், சென்னை—1**
- physical scans: **50**
- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- source PDF committed: **No**

## Publication-specific source rule — USER ESTABLISHED

The user supplied the full transcription and instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Therefore:

- the supplied transcription is the lexical baseline;
- scan controls structure, punctuation, quotation scope, page/paragraph placement, headings, speaker labels, poetry lineation and physical-copy evidence;
- scan/baseline lexical disagreements are documented, not silently substituted;
- stamps, handwriting and other physical-copy marks remain outside printed text.

## Printed contents witness

1. `இன முழக்கம்` — `4`
2. `சொர்க்க லோகத்தில்` — `13`
3. `முரசறைவாய்` — `24`
4. `பழிக்குப் பழி` — `29`
5. `ஆரியம் பேசுகிறது` — `37`
6. `கவிதைகள்` — `40`

Keep these contents-page numbers separate from directly visible body-page numerals.

## Publication boundaries

- scans 1–5 — cover/title/imprint/contents/`பதிப்புரை`
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

## Durable pre-P5 gates

- P0: **COMPLETE**
- P1: **COMPLETE**
- structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4 source/completeness audit: **PASS / COMPLETE**
- English translation: **NOT STARTED**

P3 assembly blobs before P5:

1. `01-ina-muzhakkam.md` — `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`
2. `02-sorgga-logaththil.md` — `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`
3. `03-murasaraivai.md` — `698c178ee5a65e9fe53543be2136e6691f5a8dad`
4. `04-pazhikku-pazhi.md` — `d9c57a7a55ab33310b512c34322186cc55a04ef8`
5. `05-aariyam-pesugirathu.md` — `651063d641ddbc53c1688e92b13d976b169d04ee`
6. `06-kavithaigal.md` — `a11dfc65bfd83c316e090c793f1ede102a72ac21`

## P5 current durable state

P5 is **IN PROGRESS**.

- strict visual inspection has reached the full source, but durable page-layer propagation is intentionally sequenced page by page;
- page-specific P5 corrections have been durably committed through **scan 38**;
- current durable frontier: **38 / 50 scans**;
- next unclosed scan: **39**;
- English remains blocked until P5 closeout freezes the Tamil authorities.

Durable P5 corrections already include:

- contents-page layout/punctuation alignment;
- scan 21→22 placement correction for `நாயன்மார்கள்`;
- scan 22 marginal/source-witness handling corrected from the earlier simplistic OCR-noise classification;
- scan 24 source punctuation alignment;
- scan 31–35 spacing/punctuation/paragraph fidelity corrections;
- scan 36→37 page boundary restored as `இந்த மதத்தைப் பழிக்குப்` / `பழி வாங்க வேண்டாமா?`;
- scan 38 heading/spacing/pause punctuation fidelity corrections.

## Non-regression

- **retain scan 10 exactly:** `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- do not silently normalise user-supplied lexical tokens;
- physical-copy marks remain separate from printed text;
- preserve page-boundary continuations;
- promotions/catalogue remain outside body assemblies;
- scan 40 remains poetry front matter outside `கவிதைகள்`;
- poem headings and source lineation remain source-controlled;
- cover-author witness and scan-50 catalogue disagreements are fidelity classifications, not licences to rewrite the lexical baseline.

Known later visual findings must **not** be applied out of sequence merely because they were noticed during the full visual inspection. In particular, the scan-49 heading issue is handled only when scan 49 becomes the next page-level activity.

## P5 page-by-page execution rule — USER DIRECTIVE

Permanent policy: `publications/ina-muzhakkam/P5_PAGE_BY_PAGE_POLICY.md`.

For the remainder of this publication's P5:

- one physical scan = one activity;
- when the user says `Proceed with next activity`, process only the single next unclosed scan;
- visually verify that scan, document lexical conflicts, apply only that scan's source-supported non-lexical corrections, propagate only its directly affected assembly/provenance changes, commit durably, then **stop**;
- do not batch the following scan into the same activity even when the current scan needs no correction.

After scan 50 is closed, run a **separate P5 closeout activity** for:

1. 6 / 6 P3 assembly strict recheck against the P5 page layer;
2. final `VISUAL_TEXT_FIDELITY_REVIEW.md` completion;
3. frozen Tamil article blob SHAs;
4. Tamil P5 COMPLETE / FROZEN status;
5. synchronized README / metadata / indexes / root handover / root README / continuation prompt.

Only after that closeout passes may English translation begin.

## Current blockers

**None.**

---

# Exact next activity

**P5 — scan 39 only.**

For physical scan 39:

1. fetch live `main`;
2. directly compare scan 39 against its canonical page record under the user lexical-baseline rule;
3. verify every visible word boundary, spacing, punctuation mark, paragraph break, continuation and source witness;
4. document any lexical scan/baseline disagreement without silently substituting it;
5. apply scan-39 source-supported non-lexical corrections to the scan-39 page record and directly affected `ஆரியம் பேசுகிறது` assembly/provenance if required;
6. commit the scan-39 result;
7. update progress so scan 40 becomes next;
8. **stop after scan 39. Do not process scan 40 in the same activity.**
