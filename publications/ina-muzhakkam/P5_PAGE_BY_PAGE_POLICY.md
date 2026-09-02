# இன முழக்கம் — P5 page-by-page execution policy

User directives recorded: **2026-09-02**.

## Permanent rule for the remainder of this publication's P5

P5 normally proceeds **two consecutive physical scans per activity**.

When the user says `Proceed with next activity` while `இன முழக்கம்` P5 is active:

1. fetch live `main` first and preserve any newer durable state;
2. identify the **next two unclosed physical scans** in sequence;
3. visually compare those scans only against their canonical page records and the user-supplied lexical baseline;
4. preserve the supplied lexical words; do not silently substitute a scan-appearing lexical variant;
5. correct only source-supported structure, punctuation, spacing, quotation boundaries, headings, page/paragraph placement, lineation and analogous non-lexical matters;
6. explicitly document any lexical scan/baseline disagreement rather than silently changing the word;
7. apply each scan's confirmed corrections to its canonical page record and, when necessary, the directly affected P3 assembly/provenance record;
8. commit the activity result durably;
9. update P5 progress/status as needed;
10. stop at the requested activity boundary.

An explicit user instruction naming a different set or count of consecutive pages overrides the normal two-scan cadence for that activity only. If only one physical scan remains before scan 50, process that final scan alone. After scan 50 is closed, perform the separate P5 closeout activity described below.

## Non-regression

- Scan 10 remains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`.
- Physical-copy marks remain separate from printed text.
- Contents-page numbers remain separate source witnesses from visible body numerals.
- Promotions/catalogue/front matter remain outside body assemblies according to the established boundaries.
- P5 is not permission to normalise lexical wording.

## Current durable frontier

- P5 page-level processing is durably completed through **scan 47**.
- **Scan 45 PASS:** source long-dash punctuation and verse lineation restored; lexical scan/baseline disagreements **0**.
- **Scan 46 PASS:** source long-dash punctuation and verse lineation restored; baseline retained against scan-visible `முடுக்கினள்` / baseline `முடுக்கினாள்` and scan-visible `போர் வீரனும்` / baseline `போர் வீரனாம்`; lexical scan/baseline disagreements **2**.
- **Scan 47 PASS:** source long-dash punctuation and verse lineation restored; baseline retained against scan-visible `கதறினள்` / baseline `கதறினாள்`; lexical scan/baseline disagreements **1**.
- Scan 45–47 corrections have been propagated to the canonical page records and the corresponding `கவிதைகள்` assembly portion.
- The three-scan 45–47 activity was an explicit user override of the normal two-scan cadence.
- **Next P5 activity under the standing cadence: scans 48–49 only.**
- Then process **scan 50 alone**, unless the user explicitly requests another activity boundary.

After scan 50 is closed, perform a **separate P5 closeout activity** for the 6/6 assembly recheck, final fidelity report, frozen Tamil blob SHAs and Tamil freeze. English translation starts only after that closeout passes.
