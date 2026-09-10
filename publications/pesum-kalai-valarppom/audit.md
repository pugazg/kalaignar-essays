# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **COMPLETE / PASS** | **82/82 VERIFIED**; scans 1–82 contiguous |
| P3 assemblies | **COMPLETE / PASS** | **19/19 source-numbered assemblies**; main work scans 7–82 / pp.5–80 represented |
| P4 source/completeness audit | **COMPLETE / PASS** | **82/82 page records + 19/19 assemblies reconciled; discrepancies 0** |
| P5 strict visual fidelity | **IN PROGRESS — 40/82** | scans **1–40 PASS**; **16 corrections / 16 propagated / 0 unresolved in reviewed range** |
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

The numbered-section Tamil reading layer is complete under `articles/`:

- expected/live assemblies: **19 / 19**, `01-section-01.md` through `19-section-19.md`;
- main-work coverage: scans **7–82 / pp.5–80**;
- missing / unexpected extra assemblies: **0 / 0**;
- unexplained boundary gaps / overlaps: **0 / 0**;
- unresolved assembly body-text blocks: **0**;
- assembly normalization: **0**.

Full span validation: [`P3_ASSEMBLY_AUDIT.md`](P3_ASSEMBLY_AUDIT.md).

## P4 — COMPLETE / PASS

Source identity, canonical records, pagination, source-witness distinctions, **19/19** assemblies, shared transitions and correction propagation were reconciled. New P4 text corrections **0**; unresolved P4 discrepancies/blockers **0**. Dedicated record: [`P4_SOURCE_COMPLETENESS_REVIEW.md`](P4_SOURCE_COMPLETENESS_REVIEW.md).

## P5 — IN PROGRESS — 40 / 82

Completed strict visual batches:

| Batch | Scans | Printed span | Result | Corrections | Unresolved |
|---|---:|---|---|---:|---:|
| P5-001-010 | 1–10 | outside pagination + pp.1–8 | **PASS** | 2 | 0 |
| P5-011-020 | 11–20 | pp.9–18 | **PASS** | 3 | 0 |
| P5-021-030 | 21–30 | pp.19–28 | **PASS** | 2 | 0 |
| P5-031-040 | 31–40 | pp.29–38 | **PASS** | 9 | 0 |

Current P5 totals: **40/82 strict-reviewed; 16 corrections found; 16/16 propagated; 0 unresolved fidelity discrepancies in reviewed range**.

P5 corrections through scan 40:

1. scan 4 — `Kalaignar` → `Kalaingnar`;
2. scan 7 — opening `‘வெண்ணிலாவும்` → `“வெண்ணிலாவும்`;
3–5. scan 19 — `அப்படியிருக்குமேயானால்` → `அப்படி இருக்குமேயானால்`; `எப்படிப் பாலையும்` → `எப்படி பாலையும்`; `வைத்தால்,எப்படிக் எறும்பானது` → `வைத்தால்,எப்படி எறும்பானது`;
6. scan 24 — `எழுதி படிக்கும்` → `எழுதிப் படிக்கும்`;
7. scan 26 — `ஐயா` → `அய்யா`;
8–9. scan 31 — `பாணை` → `பானை`; `ஏனப்பா` → `ஏனய்யா`;
10. scan 32 — `என்றும்` → `என்றதும்`;
11. scan 33 — `உன் மனைவி உன்னை விடமாட்டாளா?` → `உன் மனைவி உன்னைவிட மூடமாக இருக்கிறாள்?`;
12–13. scan 35 — `எழும்பும்` → `எலும்பும்`; `மூந்நூறு` → `முந்நூறு`;
14–16. scan 39 — `பேச்சுப்பொழுது` → `பேசும்பொழுது`; `அடுக்கு முறைகளால்` → `அடக்கு முறைகளால்`; `நினைவுபடுத்துகிறேன்` → `நினைவு படுத்துகிறேன்`.

All corrections are propagated to affected page records and assemblies. Source-visible transitions rechecked through this range: **12 (1→2), 16 (2→3), 22 (3→4), 27 (4→5), 31 (5→6), 34 (6→7), 38 (7→8) — PASS**. Scan 41 was inspected only as scan-40 boundary evidence and is not counted.

Detailed running record: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

## Exact next activity

**P5 scans 41–50 / printed pp.39–48.** Directly re-inspect each source scan word-by-word and punctuation-by-punctuation. Preserve page-end/top section changes **41→42 (8→9)**, **44→45 (9→10)** and **47→48 (10→11)**, plus suppressed/inferred folios on scans **42,45,48**. Inspect scan 51 only as batch-boundary evidence if needed. Record and propagate every confirmed correction. English remains blocked while P5 is open.
