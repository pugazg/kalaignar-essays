# Audit — ஆறுமாதக் கடுங்காவல்

## Tamil archival gates

| Gate | Result |
|---|---|
| P0 | **COMPLETE / PASS — 224-page native source verified** |
| P1 | **IN PROGRESS — 150/224 structurally mapped** |
| P2 | **IN PROGRESS — 30/224 records; 27 verified / 3 needs-review** |
| P3 | **NOT STARTED** |
| P4 | **NOT STARTED** |
| P5 | **NOT STARTED** |

## P0 audit

Direct native attached-file verification:

- filename — `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`
- bytes — **282020019**
- SHA-256 — **`8d4b227547144dd16a78d3f7e22edc3d955d754788ba96317c0c6ddd68d0ca69`**
- physical scans — **224**
- PDF version — **1.4**
- source PDF committed — **No**
- old 150-vs-224 discrepancy — **RESOLVED**; 150 was a renderer exposure boundary.

## P1 audit

- source physical scans — **224**
- scans structurally inspected — **150**
- remaining structural review — **151–224 / 74 scans**
- known blank/reverse pages in scans 1–150 — **5, 9, 67, 107, 109**
- front matter — **mapped**
- established body runs — **10–66, 68–106, 110–150**
- intertitle / transition — **scan 108**
- separate contents page found in scans 1–150 — **No**
- scan 150 proven source end — **No**
- P1 — **IN PROGRESS**

Authority: `P1_SOURCE_STRUCTURE_REVIEW.md`.

## Historical glyph gate

P2/P5 follow `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Minimum explicit family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## P2 batches

| Batch | Scans | Verified | Needs-review | New holds |
|---:|---:|---:|---:|---:|
| 001 | 1–5 | 3 | 2 | 2 |
| 002 | 6–10 | 5 | 0 | 0 |
| 003 | 11–15 | 5 | 0 | 0 |
| 004 | 16–20 | 4 | 1 | 1 |
| 005 | 21–25 | 5 | 0 | 0 |
| 006 | 26–30 | 5 | 0 | 0 |

### Batch 006 — scans 26–30

| Scan | Printed folio | Record | Status | Open issue |
|---:|:---:|---|---|---|
| 26 | 23 | `0026-murasu.md` | verified | none |
| 27 | 24 | `0027-murasu.md` | verified | none |
| 28 | 25 | `0028-murasu.md` | verified | none |
| 29 | 26 | `0029-murasu.md` | verified | none |
| 30 | 27 | `0030-murasu.md` | verified | none |

Batch 006 checks:

- direct native/enlarged source-pixel comparison — **PASS**
- historical 13-family check — **performed on all five pages**
- guessed readings — **0**
- new unresolved printed-text holds — **0**
- cumulative historical-glyph corrections — **1**
- unusual source-visible forms were preserved rather than context-corrected.

## P2 cumulative totals through scan 30

- canonical page records — **30/224**
- verified — **27**
- needs-review — **3**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- unresolved printed-text holds — **3**:
  - scan 3 — small imprint/printer text;
  - scan 4 — exact publisher-note transcription;
  - scan 18 — physically obscured cluster after `ஒருவராக ஆ`.

## Durable physical anomaly

Direct source review established:

- scan 14 — printed folio 13;
- scan 15 — printed folio 14;
- scan 16 — printed folio 13 again;
- scan 17 — printed folio 14 again;
- scan 18 — printed folio 15.

No physical scan is deduplicated.

## Exact next activity

**P1 structural extension scans 151–224.**

Complete structural mapping to 224/224 before resuming P2 at scan 31.
