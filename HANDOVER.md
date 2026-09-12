# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

Handoff refreshed for a new chat after **Batch 011 / P2 scans 51–55** reached the durable state **55/224 canonical records; 52 verified / 3 needs-review**. Do not rely on a copied SHA: fetch live `main` first, preserve any newer durable work, and continue from that state.

## Repository state

Publications **1–11 are RELEASE COMPLETE / FROZEN**.

Publication 12 **`ஆறுமாதக் கடுங்காவல்` is ACTIVE — P0 PASS; P1 PASS 224/224; P2 IN PROGRESS 55/224**.

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

## Controlling source

Attached source:

`TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

Direct native inspection established:

- physical file size — **282020019 bytes**
- SHA-256 — **`8d4b227547144dd16a78d3f7e22edc3d955d754788ba96317c0c6ddd68d0ca69`**
- total physical PDF scans — **224**
- PDF version — **1.4**
- source PDF committed — **No**

The earlier 150-page value was only a renderer exposure boundary. The physical source is 224 scans and that discrepancy is closed.

Only attached-source pixels control transcription. Do not consult TVA/Wikisource/OCR/alternate editions unless the user explicitly authorises comparison.

## Current gate state

- P0 — **COMPLETE / PASS**
- P1 — **COMPLETE / PASS — 224/224 structurally mapped**
- P2 — **IN PROGRESS — 55/224 records; 52 verified / 3 needs-review**
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

## P1 — full-source structural result

Direct visual structural inspection is now complete for **224/224 physical scans**.

Full source structure:

- scan 1 — physical-copy / ownership-donation mark;
- scan 2 — title page;
- scan 3 — imprint / edition page;
- scan 4 — publisher note;
- scan 5 — blank / reverse / show-through;
- scans 6–7 — `காணிக்கை` dedication;
- scan 8 — illustrated front-matter page / `முரசு`;
- scan 9 — blank / reverse / show-through;
- scans 10–66 — main text;
- scan 67 — blank / reverse / show-through;
- scans 68–106 — main text;
- scan 107 — blank / reverse / show-through;
- scan 108 — nonblank intertitle / structural transition;
- scan 109 — blank / reverse / show-through;
- scans **110–223 — main text**;
- scan **224 — back cover / publisher device**.

P1 extension scans **151–224** findings:

- scans **151–223** — continuous main-text run;
- visible printed folios run **148–220** continuously across scans 151–223;
- scan 218 / printed 215 contains an embedded section transition headed **`சிறை திறந்தது`** after a star separator;
- scan 220 / printed 217 closes that section with a star separator;
- scan 221 / printed 218 begins the next section headed **`வெற்றி! வெற்றி!!`**;
- scan 223 / printed 220 is the **final text-bearing page**, ending with a quoted slogan block and star;
- scan 224 is the **physical back cover**, carrying the `திராவிடப் பண்ணை` publisher device and no printed folio;
- no blank/reverse, advertisement, or separate colophon page occurs in scans 151–224.

Separate printed contents page in the whole source — **not found**.

P1 blockers — **0**.

Authority: `publications/aaru-maatha-kadungkaaval/P1_SOURCE_STRUCTURE_REVIEW.md`.

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

- **5/5 verified**
- printed folios — 23–27
- new holds — **0**
- cumulative historical-glyph corrections — **1**

### Batch 007 — scans 31–35

Completed from direct native/enlarged attached-PDF pixels:

- scan 31 — `pages/0031-murasu.md` — **verified** — printed folio 28 — `ஜூன் 19`
- scan 32 — `pages/0032-murasu.md` — **verified** — printed folio 29
- scan 33 — `pages/0033-murasu.md` — **verified** — printed folio 30
- scan 34 — `pages/0034-murasu.md` — **verified** — printed folio 31
- scan 35 — `pages/0035-murasu.md` — **verified** — printed folio 32 — `விடிந்தது:`

Batch 007 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- source-visible unusual forms including `அனிபா`, `சுறுப்புக்கும்`, `இருவருக்கு மிடையே`, `வால்களையும்`, `பர்ஸ் காணும் சார்`, `குழந்தையா`, `புட்டுப் போட்டுக்கொண்டு`, and `தஞ்சைமா நகரம்` were preserved.
- scan 35 ends at `வேலாயுதம்`; scan 36 is intentionally unopened.

### Batch 008 — scans 36–40

Completed from direct native/enlarged attached-PDF pixels:

- scan 36 — `pages/0036-murasu.md` — **verified** — printed folio 33
- scan 37 — `pages/0037-murasu.md` — **verified** — printed folio 34
- scan 38 — `pages/0038-murasu.md` — **verified** — printed folio 35
- scan 39 — `pages/0039-murasu.md` — **verified** — printed folio 36
- scan 40 — `pages/0040-murasu.md` — **verified** — printed folio 37 — `திருச்சியிலே :`

Batch 008 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- first-pass historical identities were resolved from source pixels, including scan 36 `தலைவரால்` (`லை`), scan 37 `காளை` (`ளை`), and scan 40 `கலைவர்கள்` (`லை`).
- source-visible forms including `அதை யொட்டியே`, `கரைகள் இணைக்கும்`, `ரத்தினவேல்கள் மனைகளை`, `திருத்தணிகளிலும்`, `திராவிட மெங்கும்`, and `தரணி யெங்கும்` were preserved.
- scan 40 ends at `கற்றுக்`; scan 41 is intentionally unopened.

### Batch 009 — scans 41–45

Completed from direct native/enlarged attached-PDF pixels:

- scan 41 — `pages/0041-murasu.md` — **verified** — printed folio 38
- scan 42 — `pages/0042-murasu.md` — **verified** — printed folio 39
- scan 43 — `pages/0043-murasu.md` — **verified** — printed folio 40
- scan 44 — `pages/0044-murasu.md` — **verified** — printed folio 41
- scan 45 — `pages/0045-murasu.md` — **verified** — printed folio 42

Batch 009 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- source-visible unusual forms including `வயதுக் குட்பட்டவர்கள்`, `தறிந்து`, `குலத்தொழிலில்`, `கொண்டாட்ட முடன்`, `ஸ்திரீலோலனைக்`, `துணிவுடை நெஞ்சு`, and `ஆசி தேவை` were preserved.
- historical identities on scan 43 included `படித்தானா?` (`னா`), `சென்றாரா?` (`றா`), `அவனை` (`னை`), and `சேலைகளைத்` (`லை / ளை`).
- scan 45 ends inside an open quotation at the physical fragment `காய`; scan 46 is intentionally unopened.

### Batch 010 — scans 46–50

Completed from direct native/enlarged attached-PDF pixels:

- scan 46 — `pages/0046-murasu.md` — **verified** — printed folio 43
- scan 47 — `pages/0047-murasu.md` — **verified** — printed folio 44
- scan 48 — `pages/0048-murasu.md` — **verified** — printed folio 45
- scan 49 — `pages/0049-murasu.md` — **verified** — printed folio 46
- scan 50 — `pages/0050-murasu.md` — **verified** — printed folio 47

Batch 010 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 45 `காய` + scan 46 `வதேன்` was resolved directly as physical continuation `காய்வதேன்`, with same-line `பாய்வதேன்` used only as a source-pixel glyph comparison.
- source-visible unusual forms including `பொறுமையை`, `பய முறுத்தி`, `ஒதுங்கற`, `கெளதமர்`, `பரந்தாமன்`, and `இறையாகக்கப்பட்டது` were preserved.
- scan 50 ends at `பாதை தவறியதின்`; scan 51 is intentionally unopened.

### Batch 011 — scans 51–55

Completed from direct native/enlarged attached-PDF pixels:

- scan 51 — `pages/0051-murasu.md` — **verified** — printed folio 48 — heading `அரியலூர் :`
- scan 52 — `pages/0052-murasu.md` — **verified** — printed folio 49
- scan 53 — `pages/0053-murasu.md` — **verified** — printed folio 50
- scan 54 — `pages/0054-murasu.md` — **verified** — printed folio 51
- scan 55 — `pages/0055-murasu.md` — **verified** — printed folio 52

Batch 011 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- source-visible forms including `எத்திராஜ்`, `அப்படி யொன்றும்`, `கடமை யுணர்ச்சி`, `குட்டப்படுகிற`, `போவோர் வருவாரை`, `திரா படையைத்`, `நெளூர்`, `எசனே`, and `இளைஞரேறுகள்` were preserved.
- page-boundary continuations directly confirmed: scan 51 `புறப்` → scan 52 `பட்டோம்`; scan 52 `வந்திருக்க` → scan 53 `குமே!`; scan 53 `அவர்` → scan 54 `பிரச்சாரப் பணியில்`.
- scan 55 ends inside an open quotation at `வளர்ந்துவரும்`; scan 56 is intentionally unopened.

## Durable P2 totals

- canonical page records — **55/224**
- verified — **52**
- needs-review — **3**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **1**
- open printed-text holds — **3**:
  - scan 3 — small imprint/printer text;
  - scan 4 — exact publisher-note transcription;
  - scan 18 — one physically obscured cluster after `ஒருவராக ஆ`.

## Exact next activity

**P2 scans 56–60.**

Process exactly scans **56–60** as one five-scan batch from the attached PDF:

- visually transcribe each whole page from source pixels;
- preserve source spelling, punctuation, paragraphing and meaningful spacing;
- perform the mandatory historical-glyph family checks;
- record visible printed folios only;
- separate physical-copy marks from printed text;
- never fill uncertain readings from context;
- synchronize controls and commit immediately after the five pages;
- stop before scan 61 unless explicitly asked to continue.

Do not reopen P1 unless genuinely new structural source evidence appears.

---

# Frozen prior boundary

Publications **1–11 remain RELEASE COMPLETE / FROZEN**.
