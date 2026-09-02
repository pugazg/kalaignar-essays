# இன முழக்கம் — P5 page-by-page execution policy

User directives recorded: **2026-09-02**.

## Permanent rule for the remainder of this publication's P5

P5 must proceed **two consecutive physical scans per activity**.

When the user says `Proceed with next activity` while `இன முழக்கம்` P5 is active:

1. fetch live `main` first and preserve any newer durable state;
2. identify the **next two unclosed physical scans** in sequence;
3. visually compare those two scans only against their canonical page records and the user-supplied lexical baseline;
4. preserve the supplied lexical words; do not silently substitute a scan-appearing lexical variant;
5. correct only source-supported structure, punctuation, spacing, quotation boundaries, headings, page/paragraph placement, lineation and analogous non-lexical matters;
6. explicitly document any lexical scan/baseline disagreement rather than silently changing the word;
7. apply each scan's confirmed corrections to its canonical page record and, when necessary, the directly affected P3 assembly/provenance record;
8. commit the two-scan result durably;
9. update P5 progress/status as needed;
10. **stop after those two physical scans**. Do not process a third scan in the same activity.

If only one physical scan remains before scan 50, process that final scan alone. After scan 50 is closed, perform the separate P5 closeout activity described below.

## Non-regression

- Scan 10 remains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`.
- Physical-copy marks remain separate from printed text.
- Contents-page numbers remain separate source witnesses from visible body numerals.
- Promotions/catalogue/front matter remain outside body assemblies according to the established boundaries.
- P5 is not permission to normalise lexical wording.

## Current durable frontier

- P5 page-level processing is durably completed through **scan 44**.
- **Scan 43 PASS:** source headings, mixed quotation punctuation and verse lineation restored; lexical scan/baseline disagreements **0**.
- **Scan 44 PASS:** source headings and verse lineation restored, including `நரிகளின் ஊளை! நாட்டு` / `வெறி பிடித்த காளைகளே!`; lexical scan/baseline disagreements **0**.
- Scan 43–44 corrections have been propagated to the canonical page records and the corresponding `கவிதைகள்` assembly portion.
- **Next P5 activity: scans 45–46 only.**
- Thereafter proceed in two-scan batches: **47–48**, then **49–50**.

After scan 50 is closed, perform a **separate P5 closeout activity** for the 6/6 assembly recheck, final fidelity report, frozen Tamil blob SHAs and Tamil freeze. English translation starts only after that closeout passes.
