# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Repository: `pugazg/kalaignar-essays`  
Branch: `main`  
Active publication: `publications/ina-muzhakkam/` — **இன முழக்கம்**  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable state; never reset or repeat completed work because this prompt contains an older checkpoint.

The last confirmed durable handover synchronization before this prompt update is:

`b788f4b57c5800b36ada823197d6080ba92e0bd3` — `Record Ina Muzhakkam page-by-page P5 policy`

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. this prompt
6. `publications/ina-muzhakkam/README.md`
7. `publications/ina-muzhakkam/P5_PAGE_BY_PAGE_POLICY.md`
8. active source metadata/indexes/audits
9. the single next P5 page record and directly affected P3 assembly

## User lexical rule

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The supplied transcription remains the lexical baseline. Scan/baseline lexical differences are documented, not silently substituted.

## Current durable state

- physical scans: **50**
- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **50 / 50 COMPLETE**
- P3: **6 / 6 COMPLETE**
- P4: **PASS / COMPLETE**
- P5: **IN PROGRESS**
- durable P5 page frontier: **scan 38 / 50**
- English translation: **NOT STARTED**
- blockers: **0**

Important non-regression:

- retain scan 10 exactly: `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 21→22 `நாயன்மார்கள்` placement remains corrected;
- scan 36→37 boundary remains `இந்த மதத்தைப் பழிக்குப்` / `பழி வாங்க வேண்டாமா?`;
- physical-copy marks remain outside printed text;
- promotions/catalogue/front matter remain outside body assemblies as established;
- do not apply later-scan findings out of sequence.

## PAGE-BY-PAGE P5 RULE — USER DIRECTIVE

For the remainder of `இன முழக்கம்` P5, **one physical scan equals one activity**.

When the user says `Proceed with next activity`:

1. process only the single next unclosed physical scan;
2. visually verify that scan against its canonical page record and lexical baseline;
3. document lexical disagreements without silently changing the words;
4. apply only that scan's source-supported structural/punctuation/spacing/heading/placement/lineation corrections;
5. update only its directly affected P3 assembly/provenance where necessary;
6. commit the page-specific result;
7. update progress;
8. **stop after that one scan**. Never batch the following scan into the same activity.

After scan 50, run a separate P5 closeout activity for the 6/6 assembly recheck, final fidelity report, frozen Tamil blob SHAs and Tamil freeze. Do not begin English before that closeout passes.

## EXACT NEXT ACTIVITY

**P5 — physical scan 39 only.**

- re-fetch live `main`;
- inspect scan 39 directly;
- compare every visible word boundary, spacing, punctuation mark, paragraph/continuation and source witness against `pages/0039-...md`;
- retain the supplied lexical tokens;
- apply scan-39 non-lexical source corrections only;
- propagate any required scan-39 change to `articles/05-aariyam-pesugirathu.md`;
- commit scan 39;
- set scan 40 as next;
- **stop. Do not process scan 40 in the same activity.**
