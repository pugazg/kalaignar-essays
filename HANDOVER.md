# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

Handoff refreshed after **Batch 029 / P2 scans 141–145** reached the durable state **145/224 canonical records; 137 verified / 8 needs-review**. Do not rely on a copied SHA: fetch live `main` first, preserve any newer durable work, and continue from that state.

## Repository state

Publications **1–11 are RELEASE COMPLETE / FROZEN**.

Publication 12 **`ஆறுமாதக் கடுங்காவல்` is ACTIVE — P0 PASS; P1 PASS 224/224; P2 IN PROGRESS 145/224**.

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
- P2 — **IN PROGRESS — 145/224 records; 137 verified / 8 needs-review**
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
- scans 10–65 — main text;
- scan 66 — illustrated main-work intertitle / `தடை` / `கல்லக்குடி`;
- scan 67 — blank / reverse / show-through;
- scans 68–106 — main text;
- scan 107 — blank / reverse / show-through;
- scan 108 — illustrated main-work intertitle / `சிறை`;
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

### Batch 012 — scans 56–60

Completed from direct native/enlarged attached-PDF pixels:

- scan 56 — `pages/0056-murasu.md` — **verified** — printed folio 53
- scan 57 — `pages/0057-murasu.md` — **verified** — printed folio 54
- scan 58 — `pages/0058-murasu.md` — **verified** — printed folio 55
- scan 59 — `pages/0059-murasu.md` — **verified** — printed folio 56
- scan 60 — `pages/0060-murasu.md` — **verified** — printed folio 57 — heading `முரசு முழங்கியது`

Batch 012 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 55 `வளர்ந்துவரும்` → scan 56 `எம்மைப் பார்!` continuation was read directly from source pixels.
- scan 56 `வாடகைக்கார் ஒன்றில்,` → scan 57 `நான் -` was read directly.
- source-visible unusual forms including `எசனே`, `அம்பிலையும்`, `டடடட`, `மாதம் போம் காத வழி`, `என்ஜினுக்கு`, `மல்லக்கொம்பையெனும்`, `நாகை வட்டாரக் கழகத்தின்`, `வறட்டு தத்துவத்தின்`, `வாணிப்பர்`, `கேத்திரத்தைப்பற்றி`, `அண்ணுமலை`, `கண்ணென`, `பண் பாடும்`, and `நாட்டுக்களித்த` were preserved.
- scan 60 ends with complete `திருக்கோயில்.`; scan 61 remains intentionally unopened.

### Batch 013 — scans 61–65

Completed from direct native/enlarged attached-PDF pixels:

- scan 61 — `pages/0061-murasu.md` — **verified** — printed folio 58
- scan 62 — `pages/0062-murasu.md` — **verified** — printed folio 59
- scan 63 — `pages/0063-murasu.md` — **verified** — printed folio 60
- scan 64 — `pages/0064-murasu.md` — **verified** — printed folio 61
- scan 65 — `pages/0065-murasu.md` — **verified** — printed folio 62

Batch 013 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 62 `விழியோட்டும் -` → scan 63 `கோமான்!` continuation was read directly.
- difficult scan 63 closing cluster was resolved from enlarged source pixels as `தரணியில்`; no contextual reconstruction was used.
- source-visible unusual forms including `வேங்கை யெனத்`, `இயக்க மாம்`, `பாவியது`, `நாட்டுக் குழைக்கும்`, `தலைவனிய`, `பணி யேற்றேன்`, `நான்சென்ஸ்`, `ரயில் நிறுத்த’ மென்றது`, `முரசதிர்ந்தது`, `தொடோம்`, and `இதயங் கொண்டோர்` were preserved.
- scan 65 closes with `அதிர்ந்தது முரசு!`, `அதிர்ந்தது முரசு!!`, `அதிர்ந்தது முரசு!!!` and a printed star; scan 66 remains intentionally unopened.

### Batch 014 — scans 66–70

Completed from direct native/enlarged attached-PDF pixels:

- scan 66 — `pages/0066-murasu-illustration.md` — **verified** — no visible printed folio — illustrated `தடை` / `கல்லக்குடி`
- scan 67 — `pages/0067-blank-reverse.md` — **verified** — blank/reverse/show-through — no visible printed folio
- scan 68 — `pages/0068-murasu.md` — **verified** — no visible printed folio — heading `களம்`
- scan 69 — `pages/0069-murasu.md` — **verified** — printed folio 66
- scan 70 — `pages/0070-murasu.md` — **verified** — printed folio 67

Batch 014 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- direct P2 inspection refined P1 structural wording for scan 66 from generic main text to illustrated main-work intertitle; P1 remains COMPLETE / PASS.
- scan 68 `எதையும் முடியாது` → scan 69 `என்று என்னிடம் கூறமாட்டார்` continuation was confirmed directly.
- scan 69 phrase `தில்லையிலே அண்ணா கொட்டிய முரசின் எதிரொலியாக இருந்தது` was resolved from enlarged pixels.
- source-visible unusual forms including `பாப்பிரம்மம்`, `இடையூறுகளுக்காளாகி`, `என்பால்`, `முறைகூட`, `மகஜர்`, `கருணாமிக்க`, and `நாலைந்துபேர்கூட` were preserved.
- scan 70 ends with complete `குடிசை வீடுகள் தான் எங்களுக்குக் காட்டப்பட்டன.`; scan 71 remains intentionally unopened.

### Batch 015 — scans 71–75

Completed from direct native/enlarged attached-PDF pixels:

- scan 71 — `pages/0071-murasu.md` — **verified** — printed folio 68
- scan 72 — `pages/0072-murasu.md` — **verified** — printed folio 69
- scan 73 — `pages/0073-murasu.md` — **verified** — printed folio 70
- scan 74 — `pages/0074-murasu.md` — **verified** — printed folio 71
- scan 75 — `pages/0075-murasu.md` — **verified** — printed folio 72

Batch 015 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 71 `கிடக்கிறது` → scan 72 `வடநாட்டு முதலாளியால்!` continuation was confirmed directly.
- scan 73 terminal `வட நாட்` → scan 74 `டானின்` was preserved as a physical page split while directly establishing the continuation `வட நாட்டானின்`.
- source-visible unusual forms including `மிகமிஞ்சிய`, `தாறுமாறாய்ப்`, `சூடான பெருமூச்சாலேயே`, `வெள்ளிப் பணமாக்கி`, `நிலத்துக்குடையோர்`, `உறிஞ்சும் கூட்டுறவிலிருந்து`, `கொள்ளையடித்தது மில்லாமல்`, `அவதிக்குள்ளாயினர்`, `மைனுதீன்`, and `கொச்சைத் தமிழால்` were preserved.
- scan 75 historical `ணா` identity was encoded as `அண்ணா` in modern Unicode.
- scan 75 ends with complete `வெளிவந்தன.`; scan 76 remains intentionally unopened.

### Batch 016 — scans 76–80

Completed from direct native/enlarged attached-PDF pixels:

- scan 76 — `pages/0076-murasu.md` — **verified** — printed folio 73
- scan 77 — `pages/0077-murasu.md` — **verified** — printed folio 74
- scan 78 — `pages/0078-murasu.md` — **verified** — printed folio 75
- scan 79 — `pages/0079-murasu.md` — **verified** — printed folio 76
- scan 80 — `pages/0080-murasu.md` — **verified** — printed folio 77

Batch 016 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 76 `அவர்` → scan 77 `களிடத்திலே` continuation was directly confirmed.
- scan 77 `பெற்ற` → scan 78 `சட்டசபை உறுப்பினர்களும்` continuation was directly confirmed.
- scan 78 `உல்லா` → scan 79 `சம், உற்சாகம்.` directly establishes `உல்லாசம்` while preserving the physical page split.
- source-visible unusual forms including `கிழப் பருவமும்`, `செய்திகேட்டு`, `இளைஞர்கட்கும்-ஒளிப்பாதையைக்`, `போர்முனையிலேதான்`, `ஆசையினில்`, `மருத்துவ மனையில்`, `நண்பர் பாரவிடம்`, `குளுரைக்கும்`, `நெஞ்சுமுத்தம்`, `இனித்து நிற்கும்`, `வென்றே மென்று!`, `உறைவிட்டெழும்`, `சிமண்டு`, `கடைசிக்கூட்டம்`, `பிணமாகப்போன`, `கழகத்தின்பால்`, `ஒக்கு யாரும்`, `பொன்னிக் மொழிகள்`, and `ஊராள வந்தவர்!` were preserved.
- scan 80 ends inside an open continuation at `கலந்துகொள்ளவேண்டிய`; scan 81 remains intentionally unopened.

### Batch 017 — scans 81–85

Completed from direct native/enlarged attached-PDF pixels:

- scan 81 — `pages/0081-murasu.md` — **verified** — printed folio 78
- scan 82 — `pages/0082-murasu.md` — **verified** — printed folio 79
- scan 83 — `pages/0083-murasu.md` — **verified** — printed folio 80
- scan 84 — `pages/0084-murasu.md` — **verified** — printed folio 81
- scan 85 — `pages/0085-murasu.md` — **verified** — printed folio 82

Batch 017 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 80 `கலந்துகொள்ளவேண்டிய` → scan 81 `வர்கள் 14ம் தேதி...` continuation was directly confirmed.
- scan 81 `நெருக்கடியான` → scan 82 `நிலைகளுக்கிடையிலும்` continuation was directly confirmed.
- source-visible unusual forms including `கவ்விக் கொண்டு போலவே`, `கப்பிக்கொண்டிருந்தது`, `வெங்கு நதி தனிற்`, `முத்துப்பந்தாக்கள்`, `ஊழியவரையில்`, `ஒண்டவந்த பிடாரிகள்`, `ஒதிய மிலர்கள்`, `களங் காண`, `விலங்கொடிக்கும்`, `கிளம்பிற்றுக்காண்`, `தேடுதுகாண்`, `புழுதி யெழுப்பியவாறு`, `கண்களுக் குத்தியிருக்கும்`, and `பலகை இளித்தபடி` were preserved without normalization.
- scan 85 ends at the physical fragment `மாணிக்க`; scan 86 remains intentionally unopened.

### Batch 018 — scans 86–90

Completed from direct native/enlarged attached-PDF pixels:

- scan 86 — `pages/0086-murasu.md` — **verified** — printed folio 83
- scan 87 — `pages/0087-murasu.md` — **verified** — printed folio 84
- scan 88 — `pages/0088-murasu.md` — **verified** — printed folio 85
- scan 89 — `pages/0089-murasu.md` — **verified** — printed folio 86
- scan 90 — `pages/0090-murasu.md` — **verified** — printed folio 87

Batch 018 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 85 `மாணிக்க` → scan 86 `குறள் ஒலிக்கும் மாதா...` continuation was directly confirmed.
- scan 89 `இருபத்தைந்துபேரும்` → scan 90 `போலீஸ் வண்டியில் ஏற்றப்பட்டோம்.` continuation was directly confirmed.
- source-visible unusual forms including `புடைகுழ்ந்து`, `மோழைகள்`, `வாழைக்குக் கன்றல்ல - ஆளுக்கு விழுதுகள்`, `நாங்களுந்தான்`, `மக்களுந்தான்`, `திட்டிய கடிதங்கள்`, `கிரீச்`, `மரக் மரக்`, `ஊளையிட்டது`, `தேசத்தொண்டர்கள்`, `என் உடலே ஒட்டினாற்போல்`, `அணையுடைத்தெழும் நித்தம் போலக்`, `கிளிக்கூண்டு`, and `கைது செய்யப்பட்டவில்லை` were preserved.
- scan 90 ends with complete `அவர் தலைமையிலே படை போகிறது!`; scan 91 remains intentionally unopened.

### Batch 019 — scans 91–95

Completed from direct native/enlarged attached-PDF pixels:

- scan 91 — `pages/0091-murasu.md` — **verified** — printed folio 88
- scan 92 — `pages/0092-murasu.md` — **verified** — printed folio 89
- scan 93 — `pages/0093-murasu.md` — **verified** — printed folio 90
- scan 94 — `pages/0094-murasu.md` — **verified** — printed folio 91
- scan 95 — `pages/0095-murasu.md` — **verified** — printed folio 92

Batch 019 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- scan 93 `அவர்போல் ஒரு` → scan 94 `அறிஞரைக் காண முடியாதென...` continuation was directly confirmed.
- scan 94 open quotation ending `கும்பாபிஷேகம்` → scan 95 `செய்யும் செட்டிமார் நாட்டிலே பிறந்தவன் நான்.”` continuation was directly confirmed.
- source-visible unusual forms including `வாணிக்கக்`, `என்னற்கோ`, `முப்பத்திஆறு`, `அரசோச்சும்`, `தியேட்டர்ஸ்க்கு`, `நடப்படுகிறதே`, `அவரவர்க்கட்கு`, `வீணை குழப்பம்`, `அட பரமசிவம்`, `வியப்பாகவேயிருந்தது`, `கூசாமல் சந்நியாசங்கொள்`, and `ராஜபோகமானது` were preserved.
- scan 95 ends with complete `நாரண துரைக்கண்ணன் தலைமையில் நாங்கள் பேசினோம்.`; scan 96 remains intentionally unopened.

### Batch 020 — scans 96–100

Completed from direct native/enlarged attached-PDF pixels:

- scan 96 — `pages/0096-murasu.md` — **verified** — printed folio 93
- scan 97 — `pages/0097-murasu.md` — **verified** — printed folio 94
- scan 98 — `pages/0098-murasu.md` — **verified** — printed folio 95 — heading `கேசவன்`
- scan 99 — `pages/0099-murasu.md` — **verified** — printed folio 96
- scan 100 — `pages/0100-murasu.md` — **verified** — printed folio 97 — printed star separator

Batch 020 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 1**
- a post-batch enlarged-pixel recheck corrected source readings in scans 96–100; totals and hold counts are unchanged.
- scan 96 `சிஷ்யனை` → scan 97 `யும் தாக்கட்டும்’` continuation was directly confirmed.
- scan 97 personal name is source-resolved as `தருமு`: `தருமுவும்` / `தருமு முதலியோரை`.
- scan 98 source recheck confirms `பெண்ணாகவா`, `வாழ்க்கைக்குத் துணை`, `தொடமுடியும்`, `காராக்கிரகத்துக்குக் கிடைக்கிற இரவும்`, `கற்பனையூறுகிறது`, `கலவி நடுப்பாதையிலே`, and `வர்ணித்த`.
- scan 99 source recheck confirms `வியாபாரத்துக்குப்போன மகனே`, historical `லை` identity in `தலை சுழல சுழல`, and source-visible `வைத்தாலென்னால்`.
- scan 99 `திரும்பினால் காதலி நிற` → scan 100 `பாள்.` continuation was directly confirmed.
- scan 100 source recheck confirms `வரப்போகும் இல்லாள்`, `என்ன சொல்வதற்காகப் பிளந்தானே?`, `கடைசிச் சேதி சொன்னே`, `என்னையேன்`, `பிணக்கோலம்`, and `யானைத்தீப் பசி`.
- scan 100 closes with a printed star separator; scan 101 remains intentionally unopened.

### Batch 021 — scans 101–105

Completed by direct re-audit of the attached PDF pixels. Live `main` already contained the five page-record commits when this batch was resumed; those records were preserved, rechecked, corrected where source pixels required, and then synchronized with all dependent controls.

- scan 101 — `pages/0101-murasu.md` — **verified** — printed folio 98 — heading `நடராசன்`
- scan 102 — `pages/0102-murasu.md` — **verified** — printed folio 99 — printed star separator
- scan 103 — `pages/0103-murasu.md` — **verified** — printed folio 100 — heading `கோரத் தாண்டவம்!`
- scan 104 — `pages/0104-murasu.md` — **verified** — printed folio 101
- scan 105 — `pages/0105-murasu.md` — **verified** — printed folio 102

Batch 021 result:

- canonical records finalized — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- mandatory 13-family historical-glyph check — **performed on all five pages**
- historical-glyph corrections added by this recheck — **8**
- cumulative historical-glyph corrections — **9**
- scan 101 source-pixel corrections: `களப்பலியானை` → `களப்பலியானான்`; `ஓடோடிவந்தானும்` → `ஓடோடிவந்தானாம்`; `பிணமானை` → `பிணமானான்`; `படித்தானே` → `படித்தானோ`; `தாறுமாறுக்குக்` → `தாறுமாறாகக்`.
- scan 102 source-pixel corrections: `பெற்றுய` → `பெற்றாய்`; `திராவிடத்தாணி` → `திராவிடத்தாய்`; `கிடக்கிறனை` → `கிடக்கிறானை`; `நன்றுக` → `நன்றாக`; `ஆசையாதம்மா` → `அசையாதம்மா`; `புது மழை` → `புது மொழி`.
- scan 103 source-pixel corrections: `நாம்புகள்` → `நரம்புகள்`; `வயதேரிய` → `வயதேறிய`; `உடலக்` → `உடலைக்`.
- scan 105 historical reading: `பதினுறு` → `பதினாறு`.
- historical-family correction events in this batch are the `னா / னோ / றா / லை` identity corrections documented above; ordinary source-reading corrections remain separate from that count.
- scan 101 terminal `வாரி வழங்கும்` → scan 102 `அன்னை திராவிடமே!` continuation was confirmed directly.
- scan 102 closes with a printed star separator.
- scan 103 terminal `அவனை நா நா` → scan 104 `வென்று மென்று...` continuation was confirmed directly.
- scan 105 ends at the physical fragment `ஆகி`; scan 106 was **not opened**.


### Batch 022 — scans 106–110

Completed from direct native/enlarged attached-PDF pixels:

- scan 106 — `pages/0106-murasu.md` — **verified** — printed folio 103
- scan 107 — `pages/0107-blank-reverse.md` — **verified** — blank/reverse/show-through — no visible folio
- scan 108 — `pages/0108-sirai-illustration.md` — **verified** — illustrated intertitle `சிறை` — no visible folio
- scan 109 — `pages/0109-blank-reverse.md` — **verified** — blank/reverse/show-through — no visible folio
- scan 110 — `pages/0110-sirai.md` — **verified** — heading `சிறை` — no visible folio

Batch 022 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on scans 106 and 110; stylized scan 108 lettering was also directly checked.
- scan 105 terminal `ஆகி` → scan 106 `யோரிடம்` continuation was confirmed directly, establishing `ஆகியோரிடம்` while preserving the physical page split.
- scan 106 source-visible unusual forms including `சாப்பிட்டானபிறகுதான்`, `அகிம்சாப் ‘பிடாரி’`, `நின்றுளா`, `அநேகர்`, `ஐயாயிரம்பேர்`, and `ஐயாயிரவர்` were preserved without contextual normalization.
- scans 107 and 109 contain only faint reverse-side show-through / paper toning and no independent printed text.
- scan 108 directly resolves the P1 generic transition as an illustrated `சிறை` intertitle with a barred/padlocked prison gate; P1 remains COMPLETE / PASS.
- scan 110 repeats heading `சிறை`, has no visible folio, and begins the continuous prison-section body text.
- scan 110 source-visible forms including `முப்பத்தாறுபேரும்`, `துப்பாக்கி சகிதம்`, `நடுநிசியில்`, and `எண்ணிட` were preserved.
- scan 110 ends with complete `என்ற செய்தி கிடைத்தது.`; scan 111 was **not opened**.


### Batch 023 — scans 111–115

Completed from direct native/enlarged attached-PDF pixels:

- scan 111 — `pages/0111-sirai.md` — **verified** — printed folio 108
- scan 112 — `pages/0112-sirai.md` — **verified** — printed folio 109
- scan 113 — `pages/0113-sirai.md` — **verified** — printed folio 110
- scan 114 — `pages/0114-sirai.md` — **verified** — printed folio 111
- scan 115 — `pages/0115-sirai.md` — **verified** — printed folio 112 — heading `எங்கள் கூண்டு :`

Batch 023 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 111 terminal `வடாற்காடு மாவட்டத்` → scan 112 `தில்` continuation was confirmed directly.
- scan 112 historical `லை` identity was directly resolved as `இலைபோட்டு`; source-visible `செல்வில்` was preserved rather than context-corrected.
- scan 113 source-visible unusual `என் அப்போதே` and terminal `என் தான்` were preserved without normalization.
- scan 113 terminal `எனக்கு நானே` → scan 114 `ஆச்சரியப்படுவேன்` continuation was confirmed directly.
- scan 114 source-visible `வேடந்தாங்கி`, `இருபதுக்குட்பட்ட`, `நாலந்து`, and `இருக்கமுடியும்` were preserved.
- scan 115 heading `எங்கள் கூண்டு :` and source-visible `எத்திராஜ்`, `சிறுநீர் கழிக்கப் பட்டு`, `மலஜலம்`, `‘கக்கூஸ்’`, `“லாங் ஜம்ப்”`, and `கூளமும்` were preserved.
- scan 115 ends with complete `பிறகுதான் உணவு வந்தது.`; scan 116 was **not opened**.


### Batch 024 — scans 116–120

Completed from direct native/enlarged attached-PDF pixels:

- scan 116 — `pages/0116-sirai.md` — **verified** — printed folio 113
- scan 117 — `pages/0117-sirai.md` — **verified** — printed folio 114
- scan 118 — `pages/0118-sirai.md` — **verified** — printed folio 115
- scan 119 — `pages/0119-sirai.md` — **verified** — printed folio 116
- scan 120 — `pages/0120-sirai.md` — **verified** — printed folio 117

Batch 024 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 116 preserves source-visible `கேள்விப்பட்டிருப்பீர்கள்-`, `சுவை அறுந்துபோன`, `சோராமல் சுயேச்சையாக`, `சுழலுதண்ணே`, and `அடிவயிற்றிலேயிருந்து`.
- scan 117 source-visible `வராதவைகளில்`, `தொளைக்கிறது`, `ஆபாசமாயிருந்த`, `என் நிற்கிறீர்கள்`, and `குடிக்க காயவிடாமல்` were preserved without contextual correction.
- scan 117 terminal `மறுபடியும்` → scan 118 `அடைத்துவிட்டார்கள்.` continuation was confirmed directly.
- scan 118 historical `ளை` identity was directly resolved as `கைதிகளை`; source-visible `நாலைந்து` and `கட்டுமஸ்தான` were preserved.
- scan 119 historical `லை` identity was directly resolved as `தலையிலே`; source-visible `பழுப்புத்தளிர்`, `லிங்கப்பெருமாள்`, `சோளக்களியை`, and `மணிலாக் கொட்டையைக்` were preserved.
- scan 119 terminal `மாஜிஸ்` → scan 120 `டிரேட் வந்தார்.` continuation was confirmed directly, establishing `மாஜிஸ்டிரேட்` across the physical page boundary.
- scan 120 source-visible `நீதி மன்றம்`, `வரி கொடுக்கும்`, `செக்ஷனோ`, `ஆட்சி பீடம்`, and `கோரிக்கை யனுப்பலாம்` were preserved.
- scan 120 ends with complete `சட்டத்திற்கு இருக்கிறது!`; scan 121 was **not opened**.


### Batch 025 — scans 121–125

Completed from direct native/enlarged attached-PDF pixels:

- scan 121 — `pages/0121-sirai.md` — **verified** — printed folio 118
- scan 122 — `pages/0122-sirai.md` — **verified** — printed folio 119
- scan 123 — `pages/0123-sirai.md` — **verified** — printed folio 120
- scan 124 — `pages/0124-sirai.md` — **verified** — printed folio 121
- scan 125 — `pages/0125-sirai.md` — **verified** — printed folio 122

Batch 025 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 121 preserves source-visible `முறைதானிது`, `மழைக்கிடையிலேயுங்கூட`, first `முப்பத்தி ஐந்து`, and later `முப்பத்திஐந்து`.
- scan 122 preserves source-visible `படைவரிசை யென்ற`, `மூணுமாதம்`, `ஆறுமாதம்தான்`, `என் அப்படி?`, and `திட்டத்துடனே-என்னவோ`.
- scan 123 preserves source-visible `ஆகாகா!`, `ஆறுவருடமே போட்டும்`, `ஒலித்த குற்றத்திற்கு`, `பிடியுங்கள் சாபம்!`, and `அவர்கள்மட்டும்`.
- scan 123 terminal `எப்படியென்கிறீர்களா -` → scan 124 `பெய்த மழை முழுதும்...` continuation was confirmed directly.
- scan 124 preserves `தார்ரோடுதான்`, bracketed `தார்` note, `பீர்க்காக்கள்`, `காராக்கிரகத்தையும்`, `கக்கூசையும்`, `குடேறியிருந்த`, and `பன்னீர்போல`.
- scan 124 historical `லை` identity was directly resolved in `தலைமுழுகி`; source line-wrap `பீர்க் / காக்கள்` was joined as `பீர்க்காக்கள்`.
- scan 125 same-edition comparison confirmed historical `லை` in `ஆலை` and `மலைக்கோட்டையின்`; source-visible `ஆலை தெளிந்த உள்ளம்` was preserved without contextual correction.
- scan 125 ends at physical fragment `கோட்டைபோன்ற`; scan 126 was **not opened**.


### Batch 026 — scans 126–130

Source pages were opened directly from the attached controlling PDF and structurally gated, but full word-for-word archival transcription could not be completed with sufficient source-pixel fidelity in the available high-resolution inspection route. The batch was therefore recorded conservatively as **needs-review**, with no contextual reconstruction.

- scan 126 — `pages/0126-sirai.md` — **needs-review** — printed folio 123
- scan 127 — `pages/0127-sirai.md` — **needs-review** — printed folio 124
- scan 128 — `pages/0128-sirai.md` — **needs-review** — printed folio 125
- scan 129 — `pages/0129-sirai.md` — **needs-review** — printed folio 126
- scan 130 — `pages/0130-sirai.md` — **needs-review** — printed folio 127

Batch 026 result:

- records created — **5/5**
- verified — **0**
- needs-review — **5**
- new verification holds — **5**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- all five physical scans were opened from the controlling attached PDF.
- exact body wording was **not** filled from OCR, context, model memory, alternate editions, TVA web text, or Wikisource.
- mandatory 13-family historical-glyph gate remains **OPEN** on scans 126–130 until a stable high-resolution source-pixel re-read completes each page.
- scan 125 terminal `கோட்டைபோன்ற` is preserved in scan 125; scan 126 is its continuation page, but no missing continuation text was inferred.
- printed folios **123–127** were directly identified for scans 126–130.
- scan 131 was **not opened**.


### Batch 027 — scans 131–135

Completed from direct native/enlarged attached-PDF pixels:

- scan 131 — `pages/0131-sirai.md` — **verified** — printed folio 128
- scan 132 — `pages/0132-sirai.md` — **verified** — printed folio 129
- scan 133 — `pages/0133-sirai.md` — **verified** — printed folio 130
- scan 134 — `pages/0134-sirai.md` — **verified** — printed folio 131
- scan 135 — `pages/0135-sirai.md` — **verified** — printed folio 132

Batch 027 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 131 terminal `அணு` → scan 132 `வும் நழுவாதவர்.` continuation was confirmed directly, establishing `அணுவும்` across the physical page boundary.
- scan 131 source-visible `‘சிங்கங்’ களில்`, `மன்னைப் பகுதியில்`, and `உடல் வளர்த்திற்கேற்ற` were preserved without normalization.
- scan 132 source-visible `ஆளவந்தவுடன்`, `துவங்கி யிருக்கிறோம்`, `சிறுசிறு`, and `கையினில்` were preserved.
- scan 133 preserves the five-line quoted prison song and source-visible `வெண்ணை எடுக்கா மோரே`, `முன்னூறு`, `நானூறைத்தாண்டிய`, and `நாறுகி- ஐம்பதாகி - ஐந்தாக`.
- scan 134 preserves `C. P. பிளாக்`, `ஒரேவிதமான`, `வசதியிருக்கும்`, `மாளமுடியாது`, and quoted `“மாதிரி திராவிட நாட்டில்”`.
- scan 135 preserves `“ஜல ஸ்தாபன மந்திரி”`, `உள்நாட்டிலாகா`, `மருத்துவ மனைக்கு`, `மந்திரி யொருவர்`, and `தலைமை நிலையத்திலிருந்து - இல்ல - ஆட்சி பீடத்திலிருந்து`.
- scan 135 ends with complete `ஒரு பிரதம செயலாளர் உண்டு.`; scan 136 was **not opened**.
- existing needs-review holds at scans 126–130 were left unchanged and were not reconstructed from context.


### Batch 028 — scans 136–140

Completed from direct native/enlarged attached-PDF pixels:

- scan 136 — `pages/0136-sirai.md` — **verified** — printed folio 133
- scan 137 — `pages/0137-sirai.md` — **verified** — printed folio 134
- scan 138 — `pages/0138-sirai.md` — **verified** — printed folio 135
- scan 139 — `pages/0139-sirai.md` — **verified** — printed folio 136
- scan 140 — `pages/0140-sirai.md` — **verified** — printed folio 137

Batch 028 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 136 preserves the printed office-holder list, including source-visible `மூன்றும் பிளாக் தலைவர்`, `உள்நாட்டிலாகா`, and `‘ஜல ஸ்தாபன’ மந்திரி`.
- scan 137 preserves source-visible `மூன்றும் பிளாக்`, `தொண்டனை இருந்தே`, `உள்ளங்கை—நெல்லிக்கை`, and `பழங் காலத்`.
- scan 137 terminal `அடைக்கலத்தின்` → scan 138 `ஆர்வமிக்க உழைப்பையும்...` continuation was confirmed directly.
- scan 138 preserves `பயந்த சுபாவமும்`, `முட்டவரும்`, `எழுச்சிக்காளை`, and `என்றும்தான்`.
- scan 139 preserves source-visible `தோழமைக்கோர் பிசிரானது`, `நல்ல தொரு`, `அடக்கொணா`, `போட்டோஸ்டுடியோ`, and `சோர்விலாளன்`.
- scan 139 terminal `எங்கள்` → scan 140 `ராஜ்யத்தில்மட்டும்` continuation was confirmed directly.
- scan 140 preserves `இன்றையதினம்`, `அண்டாக்கள்`, `‘க்யூ’`, `நாலு பிளாக் தலைவரும்`, `ஜெயில் அதிகாரம்`, and `ஐம்பதுபேர்தான்`.
- scan 140 ends at physical fragment `எல்லோரும் குளிக்கக்`; scan 141 was **not opened**.
- existing needs-review holds at scans 126–130 were left unchanged and were not reconstructed from context.


### Batch 029 — scans 141–145

Completed from direct native/enlarged attached-PDF pixels:

- scan 141 — `pages/0141-sirai.md` — **verified** — printed folio 138
- scan 142 — `pages/0142-sirai.md` — **verified** — printed folio 139
- scan 143 — `pages/0143-sirai.md` — **verified** — printed folio 140
- scan 144 — `pages/0144-sirai.md` — **verified** — printed folio 141
- scan 145 — `pages/0145-sirai.md` — **verified** — printed folio 142

Batch 029 result:

- records created — **5/5**
- verified — **5**
- needs-review — **0**
- new printed-text holds — **0**
- guessed readings — **0**
- historical-glyph correction count — **unchanged at 9**
- mandatory 13-family historical-glyph check was performed on all five pages.
- scan 140 terminal `எல்லோரும் குளிக்கக்` → scan 141 `கூடிய அளவுக்கு...` continuation was confirmed directly.
- scan 141 preserves source-visible `குளியலுக்கு மிடையிலே`, `கால்முதல்`, `இரு கலர்`, `விலே கூறுகிறாராக்கும்`, and `ஒலிவேறு`; historical `றா` identity in `என்றால்` was directly decoded.
- scan 142 preserves `முக்யமான`, `தாரைப்பூசி`, `நான்கூட`, and the irregular printed quotation punctuation around the `கோதாவரி` passage.
- scan 143 preserves `தாப்படும்`, `அளவுக் களியும்`, `சிரஞ்சீவிப் பொருள்கள்`, `துவரை`, `களைப்பாறுபடலம்`, and `உள் நாட்டு`.
- scan 143 terminal `புத்தகமளித்து` → scan 144 `படித்தவைகளை...` continuation was confirmed directly.
- scan 144 preserves `வாசக சாலையில்`, `நண்பர்களோ-உறவினர்களோ-வருவர்`, `கண்டு பிடித்து`, and `தலைவரின் - தலைமையிலே`.
- scan 144 terminal `அரிசிச்சோறு` → scan 145 `சிறிது அளவில் பெரிதாய்விடும்.` continuation was confirmed directly.
- scan 145 preserves headings `கணக்கு வருது!` and `கெடிகாரம் போவது!`, plus source-visible `ஆண் குயில்கள்`, `மகுடித் தொணிகேட்டு`, `பாம்புகளுக்குவேறு`, and `கணக்குவந்துவிட்டது`.
- scan 145 ends at physical fragment `தன்னிட்`; scan 146 was **not opened**.
- existing needs-review holds at scans 126–130 were left unchanged and were not reconstructed from context.


## Durable P2 totals

- canonical page records — **145/224**
- verified — **137**
- needs-review — **8**
- blocked — **0**
- guessed readings — **0**
- historical-glyph corrections — **9**
- open transcription / printed-text holds — **8**:
  - scan 3 — small imprint/printer text;
  - scan 4 — exact publisher-note transcription;
  - scan 18 — one physically obscured cluster after `ஒருவராக ஆ`;
  - scans 126–130 — exact full-page transcription / historical-glyph verification pending stable high-resolution source re-read.

## Exact next activity

**P2 scans 146–150.**

Process exactly scans **146–150** as one five-scan batch from the attached PDF:

- P1 classifies scans 146–150 as main text;
- preserve Batch 026 scans 126–130 as explicit needs-review holds until a focused source re-read finishes them; do not reconstruct them from context;
- inspect every physical scan 146–150 directly rather than relying on the structural map alone;
- perform the mandatory historical-glyph family checks on every text-bearing page;
- record visible printed folios only;
- preserve source spelling, punctuation, paragraphing and meaningful spacing;
- separate physical-copy marks from printed text;
- never fill uncertain readings from context;
- synchronize controls and commit immediately after the five pages;
- stop before scan 151 unless explicitly asked to continue.

Do not reopen P1 unless genuinely new structural source evidence appears.

---

# Frozen prior boundary

Publications **1–11 remain RELEASE COMPLETE / FROZEN**.
