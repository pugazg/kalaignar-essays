# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

## Repository state

Publications **1–11 are RELEASE COMPLETE / FROZEN**.

Publication 12 **`ஆறுமாதக் கடுங்காவல்` is ACTIVE — P0 IN PROGRESS; P1 PASS for supplied artifact; P2 IN PROGRESS 5/150**.

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

The earlier preview-derived 150-page assumption and preview-derived P1 reconnaissance have been **withdrawn and deleted**.

For this publication, all source-dependent archival claims must come from:

1. direct inspection of the actual uploaded PDF bytes / PDF structure; and
2. direct visual inspection of pages rendered from that physical file.

## Current gate state

- P0 — **IN PROGRESS**
- direct physical-file page-count verification — **PENDING**
- raw physical-file byte size — **282020019 bytes — CONFIRMED**
- physical-file SHA-256 — **PENDING**
- P1 — **COMPLETE / PASS FOR SUPPLIED 150-PAGE PDF ARTIFACT**
- P2 — **IN PROGRESS — 5/150 records; 3 verified / 2 needs-review**
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
9. `audit.md`

## Historical Tamil glyph rule

This 1953 source uses older Tamil type. Follow `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Core rule:

> **Read character identity, not modern visual resemblance.**

## P1 user-authorised override

The user explicitly instructed: **ignore the unresolved P0 page-count/hash issue and proceed with P1 for this PDF**.

P1 has therefore been completed for the supplied PDF artifact:

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

Completed and committed:

- scan 1 — physical-copy mark — **verified**
- scan 2 — title page — **verified**
- scan 3 — imprint — **needs-review**
- scan 4 — publisher note — **needs-review**
- scan 5 — blank/reverse — **verified**

Durable totals:

- canonical page records — **5/150**
- verified — **3**
- needs-review — **2**
- guessed readings — **0**
- historical-glyph corrections — **0**
- open printed-text holds — **2**
  - scan 3 small imprint/printer text;
  - scan 4 exact publisher-note transcription.

P0 SHA-256 / 224-page source-completeness discrepancy remains open and must not be silently resolved.

## Exact next activity

**P2 scans 6–10.**

Process exactly scans 6–10 as one batch:

1. inspect each page directly;
2. create one canonical page record per scan;
3. preserve source wording/punctuation/spacing;
4. separate printed text from physical-copy marks;
5. apply historical-glyph checks to every text-bearing Tamil page;
6. leave uncertainty `needs-review`;
7. synchronize controls;
8. commit immediately after scans 6–10;
9. set next activity to scans 11–15;
10. stop before scan 11 unless explicitly asked to continue.

Do not reopen scans 1–5 except for the targeted holds on scans 3–4.

---

# Frozen prior boundary

Publications **1–11 remain RELEASE COMPLETE / FROZEN**.
