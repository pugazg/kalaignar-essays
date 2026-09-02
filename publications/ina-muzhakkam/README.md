# இன முழக்கம்

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`  
Physical scans: **50**  
Source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`  
Source PDF committed: **No**

## User-established lexical rule

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The supplied transcription is the lexical baseline. The scan controls structure and physical evidence. Scan/baseline lexical or numeric disagreements are documented rather than silently normalised.

## Publication structure

- scans 1–5 — front matter / `பதிப்புரை`
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

## Gate status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **50 / 50 COMPLETE**
- P3: **6 / 6 COMPLETE**
- P4: **PASS / COMPLETE**
- P5 page-level strict review: **50 / 50 PASS**
- P5 assembly recheck: **6 / 6 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- E0 English translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisites: **6 / 6 PASS**
- T1 close drafts: **1 / 6 PASS**
- T2–T5: **0 / 6**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- blockers: **0**

Canonical P5 review: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).  
English plan: [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md).

## Frozen Tamil authorities

1. `இன முழக்கம்` — `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
2. `சொர்க்க லோகத்தில்` — `8fea1497ed2dcbdb395418590c1b9875e6066b8c`
3. `முரசறைவாய்` — `27ab358ac7cd06bc3c072e4bca425a1269f2c6b8`
4. `பழிக்குப் பழி` — `e140df7f6234e8362b9139793706533fec0c62d8`
5. `ஆரியம் பேசுகிறது` — `e5bf851cd8384dfd9a84c1607c5f22cc5fa59675`
6. `கவிதைகள்` — `6f0f6fc7ac0ed3132172d92bc1fa0378528c790c`

All six were re-fetched and matched exactly at E0.

## English Article 1 — T1 COMPLETE

- Tamil title: `இன முழக்கம்`
- working English title: **The Clarion Call of the Race**
- English file: `translations/en/01-ina-muzhakkam.md`
- frozen Tamil blob: `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010`
- T1 English blob: `b3022e69387662584064d51133e24f4f97e976b2`
- status: `draft`
- source comments: **8 / 8 preserved**
- T1 blockers: **0**

The T1 title/terminology choices are working decisions and remain subject to T2–T5 review.

## Permanent non-regression

- scan 10 remains `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 21→22 `நாயன்மார்கள்` boundary remains corrected;
- scan 36→37 remains `இந்த மதத்தைப் பழிக்குப்` / `பழி வாங்க வேண்டாமா?`;
- scan 41 heading remains `ஏற்பரோ!`;
- scan 49 heading remains `வருணமா? மரணமா?`;
- promotions/catalogue/front matter remain outside the six body assemblies and therefore outside the six English translation bodies unless separately authorised;
- no supplied lexical token is silently normalised;
- English translation must use the frozen Tamil assemblies, not raw transcription/OCR or scan-alternate lexical readings;
- `கவிதைகள்` English must preserve source poem headings and lineation.

## Important records

- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- [`translations/en/README.md`](translations/en/README.md)
- [`translations/en/LEXICON.md`](translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md)
- [`P5_PAGE_BY_PAGE_POLICY.md`](P5_PAGE_BY_PAGE_POLICY.md)
- [`SOURCE_COMPLETENESS_AUDIT.md`](SOURCE_COMPLETENESS_AUDIT.md)
- [`STRUCTURAL_REASSEMBLY_REVIEW.md`](STRUCTURAL_REASSEMBLY_REVIEW.md)
- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`indexes/contents.md`](indexes/contents.md)

## Exact next activity

**Article 1 — `இன முழக்கம்` — T2 bilingual fidelity review only.** Re-fetch frozen Tamil blob `df5907d3d6fa4981a2377fe621bf6f2d7ecc1010` and T1 English blob `b3022e69387662584064d51133e24f4f97e976b2`, compare every paragraph/clause and all eight source-page comments, correct fidelity defects only, record the resulting T2 blob and findings, then stop before T3.