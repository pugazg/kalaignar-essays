# Audit — ஆறுமாதக் கடுங்காவல்

## Tamil archival gates

| Gate | Result |
|---|---|
| P0 | **IN PROGRESS — SHA-256 / publication-level source extent unresolved** |
| P1 | **COMPLETE / PASS FOR SUPPLIED 150-PAGE PDF ARTIFACT** |
| P2 | **IN PROGRESS — 15/150 records; 13 verified / 2 needs-review** |
| P3 | **NOT STARTED** |
| P4 | **NOT STARTED** |
| P5 | **NOT STARTED** |

## P1 audit

- supplied PDF artifact pages rendered/inspected — **150 / 150**
- structurally unmapped pages — **0**
- blank/reverse pages — **5**: scans **5, 9, 67, 107, 109**
- front matter — **mapped**
- body runs — **10–66, 68–106, 110–150**
- distinct intertitle/transition — **scan 108**
- separate contents page found — **No**
- supplied-artifact final page — **scan 150, text-bearing**
- proven complete-publication final boundary — **No**
- historical-glyph transcription performed in P1 — **No**
- P1 blockers within supplied artifact — **0**

Authority: `P1_SOURCE_STRUCTURE_REVIEW.md`.

## Source-completeness caveat

P0 remains open:

- raw file size — **282020019 bytes**
- SHA-256 — **PENDING**
- supplied artifact page count — **150**
- user-reported complete extent — **224**
- discrepancy — **UNRESOLVED**

## Historical glyph gate

P2/P5 follow `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

For every text-bearing page the known set was explicitly checked:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## P2 batch 001 — scans 1–5

| Scan | Record | Status | Open issue |
|---:|---|---|---|
| 1 | `0001-physical-copy-mark.md` | verified | none |
| 2 | `0002-title-page.md` | verified | none |
| 3 | `0003-imprint.md` | needs-review | unresolved small imprint/printer text |
| 4 | `0004-publisher-note.md` | needs-review | exact publisher-note transcription pending |
| 5 | `0005-blank-reverse.md` | verified | none |

## P2 batch 002 — scans 6–10

| Scan | Record | Status | Open issue |
|---:|---|---|---|
| 6 | `0006-dedication-1.md` | verified | none |
| 7 | `0007-dedication-2.md` | verified | none |
| 8 | `0008-murasu-illustration.md` | verified | none |
| 9 | `0009-blank-reverse.md` | verified | none |
| 10 | `0010-murasu.md` | verified | none |

Batch 002 totals:

- records — **5/5**
- verified — **5**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **0**
- new unresolved printed-text holds — **0**

## P2 batch 003 — scans 11–15

| Scan | Record | Status | Open issue |
|---:|---|---|---|
| 11 | `0011-murasu.md` | verified | none |
| 12 | `0012-murasu.md` | verified | none |
| 13 | `0013-murasu.md` | verified | none |
| 14 | `0014-murasu.md` | verified | none |
| 15 | `0015-murasu.md` | verified | none |

Batch 003 totals:

- records — **5/5**
- verified — **5**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
  - scan 13: apparent `பொற்சுரங்கமென்டாளோ` → source-supported Unicode `பொற்சுரங்கமென்றாளோ` (`றா` family)
- new unresolved printed-text holds — **0**

## P2 cumulative totals through scan 15

- canonical page records — **15/150**
- verified — **13**
- needs-review — **2**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- unresolved printed-text holds — **2**, both inherited:
  - scan 3 small imprint/printer text;
  - scan 4 exact publisher-note transcription.

## Exact next activity

**P2 scans 16–20.** Keep scans 3–4 open for a later targeted high-resolution re-read; do not normalize or guess them.
