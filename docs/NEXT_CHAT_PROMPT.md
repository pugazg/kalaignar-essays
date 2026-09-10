# NEXT CHAT PROMPT — பேசும் கலை வளர்ப்போம் / P5 strict visual fidelity

Continue in `pugazg/kalaignar-essays`, branch `main`, active publication:

`publications/pesum-kalai-valarppom/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Root `HANDOVER.md` is the **single authoritative project handover**. Preserve Publications 1–10 as RELEASE COMPLETE / FROZEN.

## Controlling source

`TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`

- SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`
- size: `105698402` bytes
- physical scans: **82**
- image-only
- source PDF must **not** be committed

The supplied scan is controlling authority. OCR/parsed text is not authority. Never silently modernise, correct, normalize or reconstruct Tamil.

## Durable gate state

- P0 — **COMPLETE / PASS**;
- P1 — **COMPLETE / PASS**;
- P2 — **COMPLETE / PASS — 82 of 82 VERIFIED**;
- P3 — **COMPLETE / PASS — 19 of 19 assemblies**;
- P4 — **COMPLETE / PASS**;
- P5 — **NOT STARTED / NEXT**;
- English — **NOT STARTED / BLOCKED until Tamil freeze**;
- unresolved Tamil/source/assembly/completeness blockers entering P5 — **0**.

P4 dedicated record: `publications/pesum-kalai-valarppom/P4_SOURCE_COMPLETENESS_REVIEW.md`.

P4 found:

- canonical page records **82/82**, `0001–0082` contiguous;
- missing / duplicate scan records **0 / 0**;
- assemblies **19/19 source-complete**, `01-section-01.md` through `19-section-19.md`;
- source/section/page-map drift **0**;
- shared-transition duplication / omission defects **0**;
- new P4 text corrections **0**;
- unresolved P4 blockers **0**.

## Structural facts that must not regress

- scans 1–2 outside printed pagination;
- scans 3–82 = pp.1–80, `printed page = scan - 2`;
- source-numbered sections **1–19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- top-of-page section openings: `7,42,45,48,59,64,75`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- no printed contents page;
- no separate back-cover scan;
- scan 5 is physical-copy handwriting with **no printed publication text**.

## Source-witness distinctions / non-regression readings

- scan 1 cover: `பேசும் கலை வளர்ப்போம்`;
- scan 3 title page: `பேசும்கலை வளர்ப்போம்`;
- scan 6 `பதிப்புரை` date: `15—7—81`;
- scan 13 source correction: `வீடுதான்`;
- scan 74 source correction provenance: draft `வாரியிலே` / `வாரிக்கு` → source-visible `வரியிலே` / `வரிக்கு`; body phrases `ஒரே வரியிலே` / `ஒரு வரிக்கு மேல்`;
- scan 81 `முழுவாழ்வு வாழ` → scan 82 `விடாமல் நம்மிடமிருந்து பறித்துக்கொண்டு விட்டது.`;
- preserve `(Mannerism)`, `மேனரிசம்`, `தவிர்க்கவொண்ணாத`, `ஷம்சுதீன்`, `நாலுகால்`, `கி. ஆ. பெ. விசுவநாதம்`, `காயிதே மில்லத்`, `தேனினுமினிய`, `நாற்பத்தி ஆறு`, `1962-ல்`, `நாஞ்சில் கி. மனோகரன்`, `“வாலிபப் பெரியார்”`, `எ.வி.பி. ஆசைத்தம்பி`, `என். வி. நடராசனார்` without normalization.

## Mandatory startup

Read completely before P5 work:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `docs/FUTURE_WORK_GUIDELINES.md`
3. root `HANDOVER.md`
4. this prompt
5. publication `README.md`
6. `metadata/source.md`
7. `indexes/contents.md`
8. `indexes/page-map.md`
9. `audit.md`
10. `P3_ASSEMBLY_AUDIT.md`
11. `P4_SOURCE_COMPLETENESS_REVIEW.md`
12. canonical page records and affected assemblies during the strict review

## Exact next activity — P5

Perform the **final strict visual word-by-word / punctuation-by-punctuation fidelity pass over all 82 physical scans**.

1. inspect the controlling PDF pixels directly for every scan **1–82**;
2. compare each scan against its canonical `pages/` record for every visible word, meaningful spacing/word boundary, punctuation mark, quotation mark, heading, date, number and paragraph/page continuation;
3. include cover/front matter, scan 5, `பதிப்புரை`, every main-work page and the source end — no physical scan may be skipped;
4. recheck folio visibility and preserve all suppressed/inferred folios as inferred rather than printed;
5. keep later handwriting, stamps, show-through and copy-specific evidence separate from printed text;
6. preserve source-supported unusual forms; do not context-correct or modernise them;
7. for every discrepancy, record exact **old reading → source-visible reading** provenance;
8. update the affected canonical page record immediately after direct confirmation and propagate the same correction into the dependent `articles/` assembly and any affected indexes/trackers;
9. create/update `publications/pesum-kalai-valarppom/VISUAL_TEXT_FIDELITY_REVIEW.md` with scan coverage, correction ledger, propagation status and unresolved count;
10. continue until **82/82** physical scans have passed direct P5 review, or explicitly stop on a genuine unresolved source reading rather than guessing;
11. P5 closes only when corrections are fully propagated and unresolved fidelity discrepancies are **0**;
12. after P5 passes, synchronize `audit.md`, publication README, metadata/indexes as needed, root README, root `HANDOVER.md`, and this prompt;
13. **do not begin English in the same step**. English remains blocked until Tamil P5 is closed/frozen.

P5 is the required independent final direct visual source-fidelity gate. P4 completeness reconciliation is already closed and must not be repeated instead of direct scan inspection.
