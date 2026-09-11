# Audit — ஆறுமாதக் கடுங்காவல்

## Tamil archival gates

| Gate | Result |
|---|---|
| P0 | **IN PROGRESS — SHA-256 / publication-level source extent unresolved** |
| P1 | **COMPLETE / PASS FOR SUPPLIED 150-PAGE PDF ARTIFACT** |
| P2 | **IN PROGRESS — 25/150 records; 22 verified / 3 needs-review** |
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

## P2 batch 004 — scans 16–20

| Scan | Printed folio | Record | Status | Open issue |
|---:|:---:|---|---|---|
| 16 | 13 | `0016-murasu.md` | verified | repeated printed-page witness of scan 14 |
| 17 | 14 | `0017-murasu.md` | verified | repeated printed-page witness of scan 15 |
| 18 | 15 | `0018-murasu.md` | needs-review | physical obstruction hides one cluster after `ஒருவராக ஆ` |
| 19 | 16 | `0019-murasu.md` | verified | none |
| 20 | 17 | `0020-murasu.md` | verified | none |

Batch 004 totals:

- records — **5/5**
- verified — **4**
- needs-review — **1**
- blocked — **0**
- guessed readings — **0**
- new unresolved printed-text holds — **1**
- historical-glyph correction count — **unchanged at 1**

Source-artifact anomaly:

- scans 16–17 repeat printed folios/text 13–14;
- scan 18 resumes printed folio 15 and the narrative continuation;
- scan 15 boundary metadata was corrected accordingly;
- physical scans were not deduplicated.

## P2 batch 005 — scans 21–25

| Scan | Printed folio | Record | Status | Open issue |
|---:|:---:|---|---|---|
| 21 | 18 | `0021-murasu.md` | verified | none |
| 22 | 19 | `0022-murasu.md` | verified | none |
| 23 | 20 | `0023-murasu.md` | verified | none |
| 24 | 21 | `0024-murasu.md` | verified | none |
| 25 | 22 | `0025-murasu.md` | verified | none |

Batch 005 totals:

- records — **5/5**
- verified — **5**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- new unresolved printed-text holds — **0**
- historical-glyph correction count — **unchanged at 1**
- source-decoded historical identities include scan 22 `அம்பிலை` (`லை`) and scan 25 `மூன்றாம்` (`றா`).

## P2 cumulative totals through scan 25

- canonical page records — **25/150**
- verified — **22**
- needs-review — **3**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- unresolved printed-text holds — **3**:
  - scan 3 small imprint/printer text;
  - scan 4 exact publisher-note transcription;
  - scan 18 one physically obscured cluster after `ஒருவராக ஆ`.

## Exact next activity

**P2 scans 26–30.** Keep scans 3–4 and scan 18 open; do not normalize or guess them.
