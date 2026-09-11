# Page Map — ஆறுமாதக் கடுங்காவல்

Controlling supplied artifact: `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

Current gate:

- P0 — **IN PROGRESS / SHA-256 and complete-source extent unresolved**
- P1 — **COMPLETE / PASS FOR SUPPLIED PDF ARTIFACT**
- mapped physical pages — **150 / 150**
- P2 — **IN PROGRESS — 20/150 canonical records**

Full P1 review: [`../P1_SOURCE_STRUCTURE_REVIEW.md`](../P1_SOURCE_STRUCTURE_REVIEW.md)

## Canonical structural map for supplied artifact

| Scan(s) | Page type / structural role |
|---:|---|
| 1 | physical-copy / ownership-donation mark |
| 2 | title page |
| 3 | imprint / first-edition page |
| 4 | publisher note |
| 5 | blank / reverse / show-through |
| 6–7 | `காணிக்கை` dedication |
| 8 | illustrated front-matter page / `முரசு` |
| 9 | blank / reverse / show-through |
| 10–66 | main text |
| 67 | blank / reverse / show-through |
| 68–106 | main text |
| 107 | blank / reverse / show-through |
| 108 | nonblank intertitle / structural transition |
| 109 | blank / reverse / show-through |
| 110–150 | main text |

## P1 rules carried into P2

- exact printed folio must be read from each scan; do not infer a global offset;
- suppressed page number -> `null`, not inferred;
- exact heading/intertitle wording belongs in page records only after direct visual transcription;
- scan 150 is the end of the supplied artifact, **not proven publication end**;
- user-reported complete extent **224 pages** remains an unresolved completeness discrepancy;
- source PDF is never committed.

## P2 record status

| Scan | Canonical record | Status |
|---:|---|---|
| 1 | `../pages/0001-physical-copy-mark.md` | verified |
| 2 | `../pages/0002-title-page.md` | verified |
| 3 | `../pages/0003-imprint.md` | needs-review |
| 4 | `../pages/0004-publisher-note.md` | needs-review |
| 5 | `../pages/0005-blank-reverse.md` | verified |
| 6 | `../pages/0006-dedication-1.md` | verified |
| 7 | `../pages/0007-dedication-2.md` | verified |
| 8 | `../pages/0008-murasu-illustration.md` | verified |
| 9 | `../pages/0009-blank-reverse.md` | verified |
| 10 | `../pages/0010-murasu.md` | verified |
| 11 | `../pages/0011-murasu.md` | verified |
| 12 | `../pages/0012-murasu.md` | verified |
| 13 | `../pages/0013-murasu.md` | verified |
| 14 | `../pages/0014-murasu.md` | verified |
| 15 | `../pages/0015-murasu.md` | verified |
| 16 | `../pages/0016-murasu.md` | verified |
| 17 | `../pages/0017-murasu.md` | verified |
| 18 | `../pages/0018-murasu.md` | needs-review |
| 19 | `../pages/0019-murasu.md` | verified |
| 20 | `../pages/0020-murasu.md` | verified |

Current P2 coverage: **20/150** canonical records.

Current totals:

- verified — **17**
- needs-review — **3**
- blocked — **0**

Open holds:

- scan 3 — small imprint/printer text;
- scan 4 — full publisher-note transcription;
- scan 18 — one physically obscured cluster after `ஒருவராக ஆ`.

## P2 printed-folio anomaly

Direct source review established:

- scan 14 — printed 13;
- scan 15 — printed 14;
- scan 16 — printed 13 again;
- scan 17 — printed 14 again;
- scan 18 — printed 15.

Scans 16–17 are retained as independent physical page records rather than deduplicated.

## Exact next activity

**P2 scans 21–25.**
