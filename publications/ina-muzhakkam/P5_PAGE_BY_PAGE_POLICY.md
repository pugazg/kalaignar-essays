# இன முழக்கம் — P5 page-by-page execution policy

User directives recorded: **2026-09-02**.

## Permanent rule for the remainder of this publication's P5

P5 normally proceeds **two consecutive physical scans per activity**.

When the user says `Proceed with next activity` while `இன முழக்கம்` P5 is active:

1. fetch live `main` first and preserve any newer durable state;
2. identify the next unclosed physical scans in sequence;
3. visually compare those scans only against their canonical page records and the user-supplied lexical baseline;
4. preserve the supplied lexical words; do not silently substitute a scan-appearing lexical variant;
5. correct only source-supported structure, punctuation, spacing, quotation boundaries, headings, page/paragraph placement, lineation and analogous non-lexical matters;
6. explicitly document any lexical scan/baseline disagreement rather than silently changing the word;
7. apply each scan's confirmed corrections to its canonical page record and, when necessary, the directly affected P3 assembly/provenance record;
8. commit the activity result durably;
9. update P5 progress/status as needed;
10. stop at the requested activity boundary.

An explicit user instruction naming a different set or count of consecutive pages overrides the normal two-scan cadence for that activity only.

## Non-regression

- Scan 10 remains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`.
- Physical-copy marks remain separate from printed text.
- Contents-page numbers remain separate source witnesses from visible body numerals.
- Promotions/catalogue/front matter remain outside body assemblies according to the established boundaries.
- P5 is not permission to normalise lexical wording.

## Current durable frontier

- P5 **page-level** processing is now durably completed through **scan 50 / 50**.
- **Scan 48 PASS:** source long-dash punctuation and verse lineation restored, including `எல்லையுண்டு—அவன்`, `கண்டாள்—இதயங்`, `அவன் குடித்த மார்பை அடடா!`, and `நரியைப்போல்—ஆரிய`; lexical scan/baseline disagreements **0**.
- **Scan 49 PASS:** P2-introduced heading error `வருணமா? மானமா?` corrected to source-and-baseline `வருணமா? மரணமா?`; source verse lineation retained; lexical scan/baseline disagreements **0**.
- **Scan 50 PASS:** catalogue row/column structure directly rechecked; supplied lexical/number baseline retained against source-visible conflicts/omissions, including `அழகு நிலா` price, `செல்வ குமாரி` price, omitted `நாடறிந்த நட்சத்திரங்கள்` price, and omitted `ம. ரா.` author token for `தமிழ் வாத்தியார்`; no silent lexical/number substitution.
- Scan 48–49 corrections have been propagated to the `கவிதைகள்` assembly; scan 50 remains outside all body assemblies.
- The three-scan 48–50 activity was an explicit user override of the normal two-scan cadence.

## Exact next activity

Perform the **separate P5 closeout only**:

1. recheck all **6/6** P3 assemblies against the now-final P5 canonical page layer;
2. create/finalize `VISUAL_TEXT_FIDELITY_REVIEW.md` with page-level corrections and lexical-witness conflict ledger;
3. confirm blockers = 0 or record any blocker explicitly;
4. if PASS, record final frozen Tamil assembly blob SHAs and freeze the Tamil archival layer;
5. synchronize publication README, metadata, indexes/completion records, root README, `HANDOVER.md`, and `docs/NEXT_CHAT_PROMPT.md` as required;
6. stop before English translation setup.

English translation starts only after this P5 closeout passes.
