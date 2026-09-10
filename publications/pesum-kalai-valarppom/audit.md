# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **IN PROGRESS** | **40/82 VERIFIED**; batches 1–4 / scans 1–40 PASS |
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

## P2 batches 1–3 — COMPLETE / PASS

Scans **1–30** were directly transcribed/verified before this batch. Durable prior state:

- scans **1–30 / through printed p.28 — VERIFIED**;
- shared transitions already preserved: scan 12 `1→2`, scan 16 `2→3`, scan 22 `3→4`, scan 27 `4→5`;
- unresolved readings **0**;
- assemblies **0**;
- one documented P2 correction: scan 13 draft `வீட்டான்` → source-visible `வீடுதான்` after enlarged direct reinspection.

## P2 batch 4 — scans 31–40

**COMPLETE / PASS.**

- new canonical page records: **10**;
- cumulative canonical records / direct verification: **40 / 82**;
- contiguous verified range: scans **1–40**;
- batch printed coverage: pp.**29–38**;
- cumulative printed coverage: through **p.38**;
- scan **31** section `5→6` — **VERIFIED / PRESERVED**;
- scan **34** section `6→7` — **VERIFIED / PRESERVED**;
- scan **38** section `7→8` — **VERIFIED / PRESERVED**;
- unresolved printed-text readings: **0**;
- unresolved source/structure distinctions: **0**;
- section assemblies created: **0**;
- batch blockers: **0**.

Direct continuation checks include:

- scan 30 `அந்தப்` → scan 31 `பாணியில்`;
- scan 31 `மாட்டைக்` → scan 32 `கொடுத்துவிட்டு`;
- scan 33 `நன்னிலம் நடராசன்` → scan 34 `இந்தக் கதையைச்`;
- scan 34 `விளம்பரப்படுத்தப்பட்டு` → scan 35 `நடைபெற்ற`;
- scan 38 `தொடக்கக் காலத்திலே` → scan 39 `அவரது பேச்சில்`;
- scan 40 `பொருள்` → scan 41 `என்றால், அதனை`.

Scan 41 was inspected only to close the batch boundary and is **not yet counted** as a P2 canonical record.

Source-sensitive readings secured directly during batch 4:

- scan 31 — `அங்கு மிங்கும்`;
- scan 34 — unusual source-visible `மாவது`;
- scan 35 — source spacing `ஏழை களுக்காகப்`, source-visible `கோபைடுகிறான்`, and printed gathering/signature mark `பே—3` kept separate from prose;
- scan 37 — `கிடக்கு : வெங்காயம்!`;
- scan 39 — exact quoted-letter spacing `“அ” வுக்கு “அ”, “க” வுக்கு “க”`;
- scan 40 — `எடுத்துவரச்சொன்னால்`, `பிர்மாண்ட`, `வேலையற்றதுகள்`.

Batch-4 page-record corrections after direct verification: **0**. Silent normalization: **0**.

## Source-witness distinctions that must not regress

1. scan 1 cover `பேசும் கலை வளர்ப்போம்`; scan 3 title page `பேசும்கலை வளர்ப்போம்` — preserve independently.
2. scan 5 is later handwriting, not printed publication text.
3. scan 6 `பதிப்புரை` date is source-visible `15—7—81`; do not normalize to 1996.
4. numbered openings `1–19` are source-visible; descriptive section titles must not be invented.
5. physical-copy marks remain separate from printed text.
6. twelve section changes occur mid-page and must retain dual membership on shared page records.

## Corrections / normalization

- P0 source-text corrections: **0**;
- P1 source-text corrections: **0**;
- P2 silent normalization: **0**;
- P2 page records: **40 / 82 VERIFIED**;
- documented P2 page-record source corrections: **1 total** (`வீட்டான்` → `வீடுதான்`, scan 13);
- batch-4 corrections: **0**;
- unresolved P2 readings: **0**.

## Exact next activity

**P2 batch 5 — scans 41–50 / printed pp.39–48.** Scan 41 finishes section 8 at page end; section 9 opens scan 42, section 10 opens scan 45, and section 11 opens scan 48, all at page top. Scans **42,45,48** carry suppressed/inferred folios, not directly printed numerals. Check scan 50→51 where needed and **do not build assemblies during P2**.
