# இன முழக்கம் — P5 page-by-page execution policy

User directive recorded: **2026-09-02**.

## Permanent rule for the remainder of this publication's P5

P5 must proceed **one physical scan per activity**.

When the user says `Proceed with next activity` while `இன முழக்கம்` P5 is active:

1. fetch live `main` first and preserve any newer durable state;
2. identify the **single next unclosed physical scan**;
3. visually compare only that scan against its canonical page record and the user-supplied lexical baseline;
4. preserve the supplied lexical words; do not silently substitute a scan-appearing lexical variant;
5. correct only source-supported structure, punctuation, spacing, quotation boundaries, headings, page/paragraph placement, lineation and analogous non-lexical matters;
6. explicitly document any lexical scan/baseline disagreement rather than silently changing the word;
7. apply that scan's confirmed corrections to its canonical page record and, when necessary, the directly affected P3 assembly/provenance record;
8. commit the page-specific result durably;
9. update P5 progress/status as needed;
10. **stop after that one physical scan**. Do not batch the following scan into the same activity, even if the current scan requires no correction.

## Non-regression

- Scan 10 remains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`.
- Physical-copy marks remain separate from printed text.
- Contents-page numbers remain separate source witnesses from visible body numerals.
- Promotions/catalogue/front matter remain outside body assemblies according to the established boundaries.
- P5 is not permission to normalise lexical wording.

## Current durable frontier

- P5 page-level processing is durably completed through **scan 40**.
- Scan 40 strict visual fidelity: **PASS**; lexical scan/baseline disagreements: **0**.
- Scan 40 source-supported spacing, dash punctuation and paragraph structure have been propagated to its canonical page record.
- Scan 40 remains poetry introductory/review matter outside the `கவிதைகள்` body; no P3 body assembly update was required.
- **Next page-level activity: scan 41 only.**
- Scans **42–50** must then follow one scan per activity in sequence.

After scan 50 is closed, perform a **separate P5 closeout activity** for the 6/6 assembly recheck, final fidelity report, frozen Tamil blob SHAs and Tamil freeze. English translation starts only after that closeout passes.
