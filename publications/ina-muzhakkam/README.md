# இன முழக்கம்

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`  
Physical scans: **50**  
Source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`  
Source PDF committed: **No**

## Source / edition identity

- printed title: **இன முழக்கம்**
- title-page author: **கலைஞர் கருணாநிதி**
- first edition: **செப்டம்பர் 1951**
- price: **அணா 0-8-0**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- printer: **கே. ஜி. பிரஸ், சென்னை—1**

## User-established lexical rule

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The supplied transcription is the lexical baseline. The scan controls structure and physical evidence. Scan/baseline lexical disagreements are documented rather than silently normalised.

## Printed contents witness

1. `இன முழக்கம்` — `4`
2. `சொர்க்க லோகத்தில்` — `13`
3. `முரசறைவாய்` — `24`
4. `பழிக்குப் பழி` — `29`
5. `ஆரியம் பேசுகிறது` — `37`
6. `கவிதைகள்` — `40`

## Publication structure

- scans 1–5 — cover/title/imprint/contents/`பதிப்புரை`
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

## Durable gates

- P0: **COMPLETE**
- P1: **COMPLETE**
- structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 reading assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4 source/completeness audit: **PASS / COMPLETE**
- P5 strict visual fidelity: **IN PROGRESS**
- durable P5 page frontier: **scan 38 / 50**
- English translation: **NOT STARTED**
- blockers: **0**

## P5 page-by-page policy — USER DIRECTIVE

Permanent rule: [`P5_PAGE_BY_PAGE_POLICY.md`](P5_PAGE_BY_PAGE_POLICY.md).

For the remainder of P5, **one physical scan equals one activity**. A `Proceed with next activity` request processes only the next unclosed scan, commits its result, updates its directly affected assembly/provenance if necessary, and stops. The following scan must not be batched into the same activity.

Current next page-level activity: **scan 39 only**.

After scan 50, a separate P5 closeout activity will perform the 6/6 assembly recheck, final fidelity report, frozen Tamil blob recording and Tamil freeze. English begins only after that closeout passes.

## Durable P5 corrections through scan 38

- contents-page layout/punctuation aligned to the source;
- scan 21→22 `நாயன்மார்கள்` placement corrected;
- scan 22 marginal/source-witness handling corrected;
- scan 24 punctuation aligned;
- scans 31–35 source spacing/punctuation/paragraph structure aligned;
- scan 36→37 boundary restored as `இந்த மதத்தைப் பழிக்குப்` / `பழி வாங்க வேண்டாமா?`;
- scan 38 source spacing and pause punctuation aligned.

## Non-regression

- scan 10 remains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- no supplied lexical token is silently changed;
- physical-copy marks remain outside printed text;
- contents start-page numbers remain independent source witnesses;
- promotions/catalogue/front matter remain outside body assemblies at the established boundaries;
- scan 40 remains outside `கவிதைகள்`;
- poetry headings and lineation remain source-controlled;
- later-scan findings must not be applied before their own page-level turn.

## Important records

- [`P5_PAGE_BY_PAGE_POLICY.md`](P5_PAGE_BY_PAGE_POLICY.md)
- [`STRUCTURAL_REASSEMBLY_REVIEW.md`](STRUCTURAL_REASSEMBLY_REVIEW.md)
- [`SOURCE_COMPLETENESS_AUDIT.md`](SOURCE_COMPLETENESS_AUDIT.md)
- [`transcription-intake/USER_CORRECTIONS.md`](transcription-intake/USER_CORRECTIONS.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`indexes/contents.md`](indexes/contents.md)
- [`pages/`](pages/)
- [`articles/`](articles/)

## Exact next activity

**P5 scan 39 only.** Verify scan 39 directly, preserve the lexical baseline, apply only scan-39 source-supported non-lexical corrections, propagate any required change to `articles/05-aariyam-pesugirathu.md`, commit the scan-39 result, set scan 40 as next, and stop.
