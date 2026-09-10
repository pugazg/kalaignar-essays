# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **COMPLETE / PASS** | **82/82 VERIFIED**; scans 1–82 contiguous |
| P3 assemblies | **COMPLETE / PASS** | **19/19 source-numbered assemblies**; main work scans 7–82 / pp.5–80 represented |
| P4 source/completeness audit | **COMPLETE / PASS** | **82/82 page records + 19/19 assemblies reconciled; discrepancies 0** |
| P5 strict visual fidelity | **IN PROGRESS — 70/82** | scans **1–70 PASS**; **29 corrections / 29 propagated / 0 unresolved in reviewed range** |
| English E0–E7 | **NOT STARTED** | blocked until Tamil freeze |

## Source / P1 durable facts

Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`, SHA-256 `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`, 105,698,402 bytes, **82 image-only scans**; source PDF is not committed.

- scan 1 cover: `பேசும் கலை வளர்ப்போம்`;
- scan 3 title page: `பேசும்கலை வளர்ப்போம்`;
- scans 1–2 outside pagination;
- scans 3–82 = printed pp.1–80, `printed page = scan - 2`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- section starts/ends: **19/19 / 19/19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- no printed contents page; no separate back-cover scan;
- structural blockers: **0**.

## P2 — COMPLETE / PASS

All **82 physical scans** have canonical page records and were directly compared with source pixels. Printed pp.1–80 are complete; unresolved printed-text/source/structure readings **0**; silent normalization **0**.

Documented P2 corrections:

- scan 13 draft `வீட்டான்` → source-visible `வீடுதான்`;
- scan 74 draft `வாரியிலே` / `வாரிக்கு` → source-visible `வரியிலே` / `வரிக்கு`.

## P3 — COMPLETE / PASS

- expected/live assemblies: **19 / 19**, `01-section-01.md` through `19-section-19.md`;
- main-work coverage: scans **7–82 / pp.5–80**;
- missing / unexpected extra assemblies: **0 / 0**;
- unexplained boundary gaps / overlaps: **0 / 0**;
- unresolved assembly body-text blocks: **0**;
- assembly normalization: **0**.

Full span validation: [`P3_ASSEMBLY_AUDIT.md`](P3_ASSEMBLY_AUDIT.md).

## P4 — COMPLETE / PASS

Source identity, canonical records, pagination, source-witness distinctions, **19/19** assemblies, shared transitions and correction propagation reconcile with **0 unresolved P4 discrepancies/blockers**. Dedicated record: [`P4_SOURCE_COMPLETENESS_REVIEW.md`](P4_SOURCE_COMPLETENESS_REVIEW.md).

## P5 — IN PROGRESS — 70 / 82

Completed strict visual batches:

| Batch | Scans | Printed span | Result | Corrections | Unresolved |
|---|---:|---|---|---:|---:|
| P5-001-010 | 1–10 | outside pagination + pp.1–8 | **PASS** | 2 | 0 |
| P5-011-020 | 11–20 | pp.9–18 | **PASS** | 3 | 0 |
| P5-021-030 | 21–30 | pp.19–28 | **PASS** | 2 | 0 |
| P5-031-040 | 31–40 | pp.29–38 | **PASS** | 9 | 0 |
| P5-041-050 | 41–50 | pp.39–48 | **PASS** | 10 | 0 |
| P5-051-060 | 51–60 | pp.49–58 | **PASS** | 1 | 0 |
| P5-061-070 | 61–70 | pp.59–68 | **PASS** | 2 | 0 |

Current P5 totals: **70/82 strict-reviewed; 29 corrections found; 29/29 propagated; 0 unresolved fidelity discrepancies in reviewed range**.

Batch 7 corrections:

1. scan 65 `அவைகளை ஓட்டிக் கம்பங்களிலும்` → `அவைகளை ஒட்டி கம்பங்களிலும்`;
2. scan 70 `நாவன்மையென்பதும்` → `நாவன்மையெனப்படும்`.

Both batch-7 corrections are propagated to their canonical page records and affected section assemblies. Scan 64 suppressed/inferred p.62 and section 15 page-top opening passed strict review; scan 67 section **15→16** and scan 70 section **16→17** mid-page transitions passed strict review. Unresolved batch-7 discrepancies: **0**.

Detailed running record: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

## Exact next activity

**P5 scans 71–80 / printed pp.69–78.** Preserve scan **75** suppressed/inferred p.73 and source-visible section **18** opening, and scan **79** section **18→19** mid-page transition. Inspect scan **81** only as batch-boundary evidence if needed. English remains blocked while P5 is open.