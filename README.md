# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் கட்டுரைத் தொகுப்புகளை source-first முறையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

Source PDFs repository-யில் commit செய்யப்படாது. Source-visible wording மற்றும் source-witness வேறுபாடுகள் அமைதியாக modernise/normalise செய்யப்படக்கூடாது.

## Permanent workflow documents

- [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
- [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)
- [`docs/NEXT_CHAT_PROMPT.md`](docs/NEXT_CHAT_PROMPT.md)

## Publication status

Publications **1–9 are COMPLETE / FROZEN / RELEASED** in their established Tamil/English workflows.

### Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற

Workspace: [`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/)

**RELEASE COMPLETE / FROZEN.** Tamil P0–P5 complete/frozen; English T0–T5 verified; E6/E7 PASS; blockers 0.

Frozen Tamil blob: `1c5870212186b2bf7ff095b245e15cd875de76f0`.  
Released English blob: `57bb332530e5e6de12c74f2cd40ceaccf22e41b9`.

### Publication 10 — மீசை முளைத்த வயதில்

Workspace: [`publications/meesai-mulaiththa-vayathil/`](publications/meesai-mulaiththa-vayathil/)

**P0–P1 COMPLETE / PASS — P2 PAGE TRANSCRIPTION NEXT.**

- controlling source: `TVA_BOK_0065746_மீசை_முளைத்த_வயதில்.pdf`;
- source SHA-256: `9054aa8ed82c68050b82ffe57d772c32fdcad0605f72d7983de490162669527d`;
- file size: **374,123,900 bytes**;
- physical scans: **146**;
- source form: image-only multi-piece youthful literary/prose collection;
- source self-description: **`எழுத்தோவியங்கள்`**;
- title: `மீசை முளைத்த வயதில்`;
- author: `கலைஞர் மு.கருணாநிதி`;
- publisher: `தமிழ்க்கனி பதிப்பகம்`;
- first-edition witness: `கலைஞர் பிறந்த நாள் 3.6.2002`;
- supplied edition: **இரண்டாம் பதிப்பு — அக்டோபர் 2006**;
- printed price: `ரூ.70/-`.

P1 mapping result:

- physical scans mapped: **146 / 146**;
- scans 18–145 visible printed folios: **17–144 / 128 of 128 continuous**;
- verified relation scans 18–145: `printed page = scan page - 1`;
- source-titled main units: **26 / 26**;
- unit boundary overlaps: **0**;
- unmapped scans/pages: **0**;
- printed contents page: **none**;
- `indexes/contents.md`: **repository editorial/source map, not a printed contents witness**;
- unit-level duplicate searches: **26 / 26**;
- exact pre-existing unit-title hits returned: **0**;
- duplicate blockers: **0**;
- P1 blockers: **0**.

Canonical P1 records:

- [`metadata/source.md`](publications/meesai-mulaiththa-vayathil/metadata/source.md)
- [`indexes/page-map.md`](publications/meesai-mulaiththa-vayathil/indexes/page-map.md)
- [`indexes/contents.md`](publications/meesai-mulaiththa-vayathil/indexes/contents.md)
- [`audit.md`](publications/meesai-mulaiththa-vayathil/audit.md)

Main-unit sequence begins with `பிறையே` at scan 18 / printed p.17 and ends with `மயிற்கு` at scans 136–145 / printed pp.135–144.

English remains **BLOCKED until Tamil P5 freeze**.

## Current repository boundary

Publication 10 has **P0–P1 COMPLETE / PASS**.

Exact next activity: **P2 — begin canonical page-level transcription from scan 1, creating one page record per physical scan and keeping printed text separate from physical-copy marks.**

Do not begin P3 assemblies or English translation before the required Tamil gates.

### Permanent `உடன்பிறப்பே` rule

Every exact source `உடன்பிறப்பே` is retained as **`Udanpirappē`** in English; direct salutation **`Udanpirappē,`**.

Live `main` and root [`HANDOVER.md`](HANDOVER.md) remain authoritative.