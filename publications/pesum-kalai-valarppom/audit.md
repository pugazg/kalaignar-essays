# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **IN PROGRESS** | **10/82 VERIFIED**; batch 1 scans 1–10 PASS |
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
- workspace/publication label: `பேசும் கலை வளர்ப்போம்`;
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

## P2 batch 1 — scans 1–10

**COMPLETE / PASS.**

- canonical page records created: **10 / 82**;
- directly verified against source pixels: **10 / 82**;
- covered through physical scan **10 / printed p.8**;
- unresolved printed-text readings: **0**;
- unresolved physical-copy/source distinction issues: **0**;
- section assemblies created: **0**;
- batch blockers: **0**.

Front-matter handling:

- scan 1 — colour front cover, printed cover text transcribed;
- scan 2 — substantially blank inside cover, physical-copy/library mark kept separate;
- scan 3 — title page, handwriting + library stamp kept separate from print;
- scan 4 — edition/imprint page, partial library stamp kept separate;
- scan 5 — full-page later handwritten note, retained strictly as physical-copy evidence with **no printed publication text**;
- scan 6 — printed `பதிப்புரை`, source-visible date retained as `15—7—81`;
- scans 7–10 — section 1 body transcribed and verified.

Direct cross-page checks completed:

- scan 7 `கவிஞரின்` → scan 8 `கவிதைச்`;
- scan 8 `பிரச்` → scan 9 `சினைகளைப்`;
- scan 9 `சிந்தித்` → scan 10 `துப் பார்த்து`;
- scan 10 `கொண்` → scan 11 `டிருப்பார்.`.

Scan 11 was inspected only to close the scan-10 boundary; it is not counted as a P2 page record yet.

## Source-witness distinctions that must not regress

1. **Title-form distinction established during P2:** scan 1 front cover prints `பேசும் கலை வளர்ப்போம்`; scan 3 title page prints `பேசும்கலை வளர்ப்போம்`. Preserve both source witnesses exactly; do not silently normalize one to the other.
2. Title page uses `மாண்புமிகு டாக்டர் கலைஞர் மு.கருணாநிதி / தமிழக முதல்-அமைச்சர்`; English imprint separately uses `By : Kalaignar M. Karunanidhi`.
3. Scan 5 is a later handwritten physical-copy note, not printed publication text.
4. `பதிப்புரை` carries the source-visible date `15—7—81`; retain that 1981 date in this 1996 eighth-edition witness.
5. User-supplied `முத்தாரம்` compilation description remains contextual metadata unless independently source-visible.
6. Numbered openings `1–19` are source-visible; descriptive section titles must not be invented.
7. Twelve section changes occur **mid-page**; later transcription/assembly must preserve both section memberships on those shared scans.

## Corrections / normalization

- P0 source-text corrections: **0**;
- P1 source-text corrections: **0** — P1 did not transcribe body text;
- P2 silent normalization: **0**;
- P2 page records: **10 / 82 VERIFIED**;
- P2 source-visible title-witness distinction documented: **1** (`பேசும் கலை...` cover vs `பேசும்கலை...` title page);
- Tamil body transcription begun: **Yes**;
- unresolved P2 readings: **0**.

## Exact next activity

**P2 batch 2 — scans 11–20.** Create canonical page records for printed pp.9–18, directly transcribe and verify source-visible printed text, preserve source punctuation and cross-page fragments, respect the section 1→2 transition on scan 12 and section 2→3 transition on scan 16, and **do not build section assemblies during P2**.
