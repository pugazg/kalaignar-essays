# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **NOT STARTED** | 0/82; next activity scans 1–10 |
| P3 assemblies | **NOT STARTED** | — |
| P4 source/completeness audit | **NOT STARTED** | — |
| P5 strict visual fidelity | **NOT STARTED** | — |
| English E0–E7 | **NOT STARTED** | blocked until Tamil freeze |

## P0 source gate

**PASS.**

- source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`;
- SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`;
- size: `105698402` bytes;
- physical scans: **82**;
- image-only: **Yes**;
- source PDF committed: **No**;
- source title: `பேசும் கலை வளர்ப்போம்`;
- publisher: `பாரதி பதிப்பகம்`;
- supplied edition: **எட்டாம் பதிப்பு — செப்டம்பர் 1996**;
- numbered units: **19**;
- printed contents page: **not present**;
- unresolved P0 identity blockers: **0**.

## P1 canonical mapping gate

**COMPLETE / PASS.**

Direct source inspection results:

- physical scans inspected: **82 / 82**;
- canonical map rows: **82 / 82**;
- scans outside printed pagination: **1–2**;
- printed sequence: scans **3–82 = pp.1–80**;
- printed pages mapped: **80 / 80**;
- section starts verified: **19 / 19**;
- section ends verified: **19 / 19**;
- shared mid-page section-transition scans: **12** (`12,16,22,27,31,34,38,51,55,67,70,79`);
- no printed contents page;
- no separate back-cover scan;
- unresolved mapping / pagination / section-boundary blockers: **0**.

Suppressed folios are not represented as printed evidence. `indexes/page-map.md` explicitly labels the sequence-inferred folios on scans **3,4,5,6,7,42,45,48,59,64,75**.

## Source-witness distinctions that must not regress

1. Title page uses `மாண்புமிகு டாக்டர் கலைஞர் மு.கருணாநிதி / தமிழக முதல்-அமைச்சர்`; English imprint separately uses `By: Kalaignar M. Karunanidhi`.
2. Scan 5 is a later handwritten physical-copy note, not printed publication text.
3. `பதிப்புரை` is dated `15-7-81`; retain that date in this 1996 eighth-edition witness.
4. User-supplied `முத்தாரம்` compilation description remains contextual metadata unless independently source-visible.
5. Numbered openings `1–19` are source-visible; descriptive section titles must not be invented.
6. Twelve section changes occur **mid-page**; later transcription/assembly must preserve both section memberships on those shared scans.

## Corrections / normalization

- P0 source-text corrections: **0**;
- P1 source-text corrections: **0** — P1 did not transcribe body text;
- silent normalization: **0**;
- P2 page records: **0 / 82**;
- Tamil body transcription begun: **No**.

## Exact next activity

**P2 batch 1 — scans 1–10.** Create canonical page records for the front cover through printed p.8, directly transcribe/verify source-visible printed text, keep handwriting/stamps/physical-copy marks in separate sections, follow the P1 folio map, and **do not build section assemblies during this batch**.
