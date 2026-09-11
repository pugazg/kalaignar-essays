# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

## Repository state

Publications **1–11 are RELEASE COMPLETE / FROZEN**.

Publication 12 **`ஆறுமாதக் கடுங்காவல்` is ACTIVE — P0 IN PROGRESS; P1 PASS for supplied artifact; P2 IN PROGRESS 25/150**.

Do not reopen Publications 1–11 merely for stylistic polishing. Source PDFs are never committed.

---

# Publication 12 — ஆறுமாதக் கடுங்காவல்

Workspace: `publications/aaru-maatha-kadungkaaval/`

## User-confirmed publication identity

- title — **`ஆறுமாதக் கடுங்காவல்`**
- author — **`கலைஞர் மு. கருணாநிதி`**
- publisher — **`திராவிடப் பண்ணை`**
- edition — **`முதல் பதிப்பு, 1953`**
- expected complete physical PDF extent — **224 pages**

User-supplied description:

> **ஆறு மாத காலம் சிறைத்தண்டனை பெற்ற கலைஞர், பாளையங்கோட்டை சிறைச்சாலையில் தனிக் கொட்டடியில் அடைக்கப்பட்டிருந்தார். அந்தக் காலத்தில் கலைஞர் அனுபவித்த சிறை வாழ்க்கை குறித்த நினைவுப் பதிவு இது.**

Treat that paragraph as metadata/context unless directly confirmed in the physical PDF.

## Source-authority correction

The attachment **preview/parser is not controlling source evidence** for page count, source extent, P1 structure, pagination, or page boundaries.

For this publication, source-dependent archival claims must come from direct inspection of the supplied artifact and direct visual inspection of rendered source pages.

## Current gate state

- P0 — **IN PROGRESS**
- raw physical-file byte size — **282020019 bytes — CONFIRMED**
- physical-file SHA-256 — **PENDING**
- user-reported complete extent — **224 pages**
- supplied artifact available to this workflow — **150 pages**
- source-completeness discrepancy — **OPEN**
- P1 — **COMPLETE / PASS FOR SUPPLIED 150-PAGE PDF ARTIFACT**
- P2 — **IN PROGRESS — 25/150 records; 22 verified / 3 needs-review**
- P3 — **NOT STARTED**
- P4 — **NOT STARTED**
- P5 — **NOT STARTED**
- English — **BLOCKED until Tamil freezes**

## Mandatory startup

Read fresh/completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. this root `HANDOVER.md`
5. `docs/NEXT_CHAT_PROMPT.md`
6. publication `README.md`
7. `metadata/source.md`
8. `indexes/page-map.md`
9. `P1_SOURCE_STRUCTURE_REVIEW.md`
10. `audit.md`

## Historical Tamil glyph rule

This 1953 source uses older Tamil type. Follow `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Core rule:

> **Read character identity, not modern visual resemblance.**

## P1 supplied-artifact result

P1 has been completed for the supplied PDF artifact:

- physical pages structurally inspected — **150/150**;
- front matter — scans **1–9**;
- main text runs — **10–66**, **68–106**, **110–150**;
- blank/reverse scans — **5, 9, 67, 107, 109**;
- intertitle/transition — **108**;
- separate contents page found — **No**;
- scan 150 — **text-bearing artifact end, not claimed as complete-publication end**;
- P1 blockers within supplied artifact — **0**.

Authority: `publications/aaru-maatha-kadungkaaval/P1_SOURCE_STRUCTURE_REVIEW.md`.

P0 remains open for SHA-256 and the user-reported 224-page completeness discrepancy. Do not erase that caveat.

## P2 batch 001 — scans 1–5

- scan 1 — `pages/0001-physical-copy-mark.md` — **verified**
- scan 2 — `pages/0002-title-page.md` — **verified**
- scan 3 — `pages/0003-imprint.md` — **needs-review**
- scan 4 — `pages/0004-publisher-note.md` — **needs-review**
- scan 5 — `pages/0005-blank-reverse.md` — **verified**

Open holds remain:

- scan 3 — unresolved small imprint/printer text;
- scan 4 — exact publisher-note transcription.

## P2 batch 002 — scans 6–10

Completed from direct visual source review:

- scan 6 — `pages/0006-dedication-1.md` — **verified**
- scan 7 — `pages/0007-dedication-2.md` — **verified**
- scan 8 — `pages/0008-murasu-illustration.md` — **verified**
- scan 9 — `pages/0009-blank-reverse.md` — **verified**
- scan 10 — `pages/0010-murasu.md` — **verified**

Batch 002 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- guessed readings — **0**
- historical-glyph corrections — **0**
- new printed-text holds — **0**

## P2 batch 003 — scans 11–15

Completed from direct visual source review:

- scan 11 — `pages/0011-murasu.md` — **verified**
- scan 12 — `pages/0012-murasu.md` — **verified**
- scan 13 — `pages/0013-murasu.md` — **verified**
- scan 14 — `pages/0014-murasu.md` — **verified**
- scan 15 — `pages/0015-murasu.md` — **verified**

Batch 003 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- guessed readings — **0**
- historical-glyph corrections — **1** (scan 13: `பொற்சுரங்கமென்டாளோ` → `பொற்சுரங்கமென்றாளோ`, historical `றா`)
- new printed-text holds — **0**

## P2 batch 004 — scans 16–20

Completed from the attached PDF only:

- scan 16 — `pages/0016-murasu.md` — **verified** — repeated printed folio 13 / second source witness of scan 14 text
- scan 17 — `pages/0017-murasu.md` — **verified** — repeated printed folio 14 / second source witness of scan 15 text
- scan 18 — `pages/0018-murasu.md` — **needs-review** — one physically obscured cluster after `ஒருவராக ஆ`
- scan 19 — `pages/0019-murasu.md` — **verified**
- scan 20 — `pages/0020-murasu.md` — **verified**

New source-artifact finding:

- physical scans **16–17 repeat printed folios 13–14**;
- scan **18 resumes printed folio 15** and the textual continuation after scan 15;
- scan 15 boundary metadata was corrected to record this duplicate-page insertion;
- no physical scan was deduplicated or dropped.

Batch 004 result:

- records created — **5/5**
- verified — **4**
- needs-review — **1**
- new printed-text holds — **1**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**; scan 20 includes a positively decoded historical `னா` occurrence in `பொன்னாக்கிவிட்டது`.

## P2 batch 005 — scans 21–25

Completed from the attached PDF only:

- scan 21 — `pages/0021-murasu.md` — **verified** — printed folio 18
- scan 22 — `pages/0022-murasu.md` — **verified** — printed folio 19 / `அடுத்த நாள் :`
- scan 23 — `pages/0023-murasu.md` — **verified** — printed folio 20
- scan 24 — `pages/0024-murasu.md` — **verified** — printed folio 21
- scan 25 — `pages/0025-murasu.md` — **verified** — printed folio 22 / `மூன்றாம் நாள் :`

Batch 005 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 22 `அம்பிலை` (`லை`) and scan 25 `மூன்றாம்` (`றா`) were decoded by historical character identity during first-pass transcription.

Durable P2 totals:

- canonical page records — **25/150**
- verified — **22**
- needs-review — **3**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- open printed-text holds — **3**:
  - scan 3 small imprint/printer text;
  - scan 4 exact publisher-note transcription;
  - scan 18 one physically obscured cluster after `ஒருவராக ஆ`.

P0 SHA-256 / 224-page source-completeness discrepancy remains open and must not be silently resolved.

## Exact next activity

**P2 scans 26–30.**

Process exactly scans 26–30 as one batch, continue direct source transcription and historical-glyph checks, preserve the scans 3–4 / 18 source holds, synchronize controls, commit immediately after the five-page batch, then set the next boundary from live source/repository state.

Scan 25 ends at `முடிவைச்சொல்ல`; read scan 26 directly for the continuation. Do not reopen earlier pages unless genuinely new source evidence affects them.

---

# Frozen prior boundary

Publications **1–11 remain RELEASE COMPLETE / FROZEN**.
