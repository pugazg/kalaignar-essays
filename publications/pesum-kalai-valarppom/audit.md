# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **IN PROGRESS** | **50/82 VERIFIED**; batches 1–5 / scans 1–50 PASS |
| P3 assemblies | **NOT STARTED** | — |
| P4 source/completeness audit | **NOT STARTED** | — |
| P5 strict visual fidelity | **NOT STARTED** | — |
| English E0–E7 | **NOT STARTED** | blocked until Tamil freeze |

## P0 / P1 durable gates

**P0 PASS.** Controlling source `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`, SHA-256 `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`, 105,698,402 bytes, 82 image-only scans; source PDF not committed.

**P1 COMPLETE / PASS.** Direct inspection established:

- scans **1–2** outside printed pagination;
- scans **3–82 = pp.1–80** continuously;
- `printed page = scan - 2`;
- section starts/ends **19/19 / 19/19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- no printed contents page and no separate back-cover scan;
- unresolved P1 blockers **0**.

## P2 batches 1–4 — durable prior state

Scans **1–40 / through printed p.38** are VERIFIED. Shared transitions already preserved: scan 12 `1→2`, 16 `2→3`, 22 `3→4`, 27 `4→5`, 31 `5→6`, 34 `6→7`, 38 `7→8`. Earlier documented page-record correction remains scan 13 draft `வீட்டான்` → source-visible `வீடுதான்`. Unresolved readings **0**; assemblies **0**.

## P2 batch 5 — scans 41–50

**COMPLETE / PASS.**

- new canonical page records: **10**;
- cumulative canonical records / direct verification: **50 / 82**;
- contiguous verified range: scans **1–50**;
- batch printed coverage: pp.**39–48**;
- cumulative printed coverage: through **p.48**;
- scan **41** closes section 8 at page end;
- scan **42** opens section 9 at page top — p.40 folio **suppressed / inferred**;
- scan **44** closes section 9 at page end;
- scan **45** opens section 10 at page top — p.43 folio **suppressed / inferred**;
- scan **47** closes section 10 at page end;
- scan **48** opens section 11 at page top — p.46 folio **suppressed / inferred**;
- unresolved printed-text readings: **0**;
- unresolved source/structure distinctions: **0**;
- section assemblies created: **0**;
- batch blockers: **0**.

Direct continuation / boundary checks include:

- scan 40 `பொருள்` → scan 41 `என்றால், அதனை`;
- scan 46 `சிக்கவைக்க` → scan 47 `வேண்டுமென்று`;
- scan 47 section 10 ends at page end; scan 48 opens section `11` at page top;
- scan 49 `மதிப்புக்குரிய தோழர்` → scan 50 `களுக்குப் பதிலாக`;
- scan 50 ends `“கருவுற்றிருக்கிறேன்” என்றும் பொருள் உண்டு!`; scan 51 starts a new paragraph `அடிசன் இப்படித் திணறிக் கொண்டிருந்தபோது,`.

Source-sensitive readings secured during batch 5 include:

- scan 47 — `திருவல்லுவரை`, `தமிஷ்`, `வாலை! வாலைவிடு`, and source ellipsis/punctuation sequences;
- scan 48 — `தாக்குமுறைக்கு`, `அழகுபடக்`, and the suppressed/inferred p.46 folio;
- scan 49 — source spacing distinction `செத்து விட்டார்கள்` / `செத்துவிட்டார்கள்` and cross-page `மதிப்புக்குரிய தோழர்`;
- scan 50 — `அயோத்தியாபுரியா? அஸ்தினாபுரியா?`, `மிதிலாபுரி`, `புகழ்மேணியில்`, `I conceive, conceive, conceive`, and `மூச்சுத்திணற`.

Batch-5 page-record corrections after final direct verification: **0**. Silent normalization: **0**.

## Source-witness distinctions that must not regress

1. scan 1 cover `பேசும் கலை வளர்ப்போம்`; scan 3 title page `பேசும்கலை வளர்ப்போம்` — preserve independently.
2. scan 5 is later handwriting, not printed publication text.
3. scan 6 `பதிப்புரை` date is source-visible `15—7—81`; do not normalize to 1996.
4. numbered openings `1–19` are source-visible; descriptive section titles must not be invented.
5. physical-copy marks remain separate from printed text.
6. twelve section changes occur mid-page and must retain dual membership on shared page records.
7. suppressed/inferred folios must never be represented as directly printed numerals.

## Corrections / normalization

- P0 source-text corrections: **0**;
- P1 source-text corrections: **0**;
- P2 silent normalization: **0**;
- P2 page records: **50 / 82 VERIFIED**;
- documented P2 page-record source corrections: **1 total** (`வீட்டான்` → `வீடுதான்`, scan 13);
- batch-5 corrections: **0**;
- unresolved P2 readings: **0**.

## Exact next activity

**P2 batch 6 — scans 51–60 / printed pp.49–58.** Preserve the section **11→12** mid-page transition on scan 51 and **12→13** transition on scan 55. Section 13 ends at scan 58 page end; section 14 opens at scan 59 page top. Scan **59 / inferred p.57** has a suppressed/inferred folio and must not be represented as visibly printed. Check scan 60→61 where needed and **do not build assemblies during P2**.
