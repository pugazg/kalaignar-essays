# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

## Repository state

Publications **1–11 are RELEASE COMPLETE / FROZEN**.

Publication 12 **`ஆறுமாதக் கடுங்காவல்` is ACTIVE — P0 PASS; P1 IN PROGRESS 150/224; P2 IN PROGRESS 30/224**.

Do not reopen Publications 1–11 merely for stylistic polishing. Source PDFs are never committed.

---

# Publication 12 — ஆறுமாதக் கடுங்காவல்

Workspace: `publications/aaru-maatha-kadungkaaval/`

## User-confirmed publication identity

- title — **`ஆறுமாதக் கடுங்காவல்`**
- author — **`கலைஞர் மு. கருணாநிதி`**
- publisher — **`திராவிடப் பண்ணை`**
- edition — **`முதல் பதிப்பு, 1953`**

User-supplied description:

> **ஆறு மாத காலம் சிறைத்தண்டனை பெற்ற கலைஞர், பாளையங்கோட்டை சிறைச்சாலையில் தனிக் கொட்டடியில் அடைக்கப்பட்டிருந்தார். அந்தக் காலத்தில் கலைஞர் அனுபவித்த சிறை வாழ்க்கை குறித்த நினைவுப் பதிவு இது.**

Treat that paragraph as metadata/context unless directly confirmed in the physical PDF.

## Controlling source / corrected physical identity

Attached source:

`TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

Direct native inspection of the attached PDF established:

- physical file size — **282020019 bytes**
- SHA-256 — **`8d4b227547144dd16a78d3f7e22edc3d955d754788ba96317c0c6ddd68d0ca69`**
- total physical PDF scans — **224**
- PDF version — **1.4**
- source PDF committed — **No**

The earlier 150-page value came from the page-renderer exposure boundary, not from the native PDF's true physical extent. The former **150-vs-224 source-completeness discrepancy is RESOLVED**.

Source wording remains controlled only by direct source pixels. Do not consult TVA/Wikisource/OCR/alternate editions unless the user explicitly authorises comparison.

## Current gate state

- P0 — **COMPLETE / PASS**
- P1 — **IN PROGRESS — 150/224 structurally mapped**
  - scans 1–150 retain their already-established structural classifications;
  - scans **151–224 remain structurally unmapped**;
  - scan 150 is **not** the source-artifact end.
- P2 — **IN PROGRESS — 30/224 records; 27 verified / 3 needs-review**
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

## P1 durable structural evidence through scan 150

The existing direct visual structural review remains valid for scans **1–150**:

- scans 1–9 — front matter;
- scans 10–66 — main text;
- scan 67 — blank/reverse;
- scans 68–106 — main text;
- scan 107 — blank/reverse;
- scan 108 — nonblank intertitle / structural transition;
- scan 109 — blank/reverse;
- scans 110–150 — main text.

Separate contents page in scans 1–150 — **not found**.

P1 is now reopened because the native attached PDF has **224** scans. Scans **151–224** must be structurally inspected before P1 can pass.

## P2 batch history

### Batch 001 — scans 1–5

- scan 1 — verified
- scan 2 — verified
- scan 3 — **needs-review** — unresolved small imprint/printer text
- scan 4 — **needs-review** — exact publisher-note transcription
- scan 5 — verified

### Batch 002 — scans 6–10

- **5/5 verified**
- new holds — **0**

### Batch 003 — scans 11–15

- **5/5 verified**
- historical-glyph correction — scan 13: apparent `பொற்சுரங்கமென்டாளோ` → source-supported `பொற்சுரங்கமென்றாளோ` (historical `றா`)

### Batch 004 — scans 16–20

- scan 16 — verified — repeated printed folio 13 / second physical witness of scan 14 text
- scan 17 — verified — repeated printed folio 14 / second physical witness of scan 15 text
- scan 18 — **needs-review** — one physically obscured cluster after `ஒருவராக ஆ`
- scans 19–20 — verified

Source-artifact anomaly: scans **16–17 repeat printed folios 13–14**; scan 18 resumes printed folio 15. Every physical scan remains separately represented.

### Batch 005 — scans 21–25

- **5/5 verified**
- printed folios — 18–22
- scan 22 — `அடுத்த நாள் :`
- scan 25 — `மூன்றாம் நாள் :`
- new holds — **0**

### Batch 006 — scans 26–30

Completed from direct native/enlarged attached-PDF pixels:

- scan 26 — `pages/0026-murasu.md` — **verified** — printed folio 23
- scan 27 — `pages/0027-murasu.md` — **verified** — printed folio 24
- scan 28 — `pages/0028-murasu.md` — **verified** — printed folio 25
- scan 29 — `pages/0029-murasu.md` — **verified** — printed folio 26
- scan 30 — `pages/0030-murasu.md` — **verified** — printed folio 27

Batch 006 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- guessed readings — **0**
- new printed-text holds — **0**
- historical-glyph correction count — **unchanged at 1**
- unusual source-visible forms such as `சிலங்கொண்டவர்`, `குறை நோயிலிருந்து`, `நீங்கள் சிரி விழவேண்டாம்`, and `என்னையும். உங்களையும்` were preserved rather than normalized.

## Durable P2 totals

- canonical page records — **30/224**
- verified — **27**
- needs-review — **3**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- open printed-text holds — **3**:
  - scan 3 — small imprint/printer text;
  - scan 4 — exact publisher-note transcription;
  - scan 18 — one physically obscured cluster after `ஒருவராக ஆ`.

## Exact next activity

**P1 structural extension — scans 151–224.**

Visually inspect and structurally classify all remaining physical scans **151–224** from the attached 224-page PDF. Record page types, blank/reverse pages, body/intertitle/end matter boundaries, printed-pagination behaviour where visible, and the true physical final-page role. Do not transcribe body text during this P1 activity except where exact visible wording is necessary to identify a structural heading/intertitle.

After scans 151–224:

- update `P1_SOURCE_STRUCTURE_REVIEW.md`, page map, source metadata, audit, README, handover and next prompt;
- mark P1 PASS only if all 224 scans are structurally accounted for;
- then resume P2 from scan 31.

**P2 scans 31 onward are paused until this P1 extension is complete.**

---

# Frozen prior boundary

Publications **1–11 remain RELEASE COMPLETE / FROZEN**.
