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

A compatibility pointer for historical translation-review links is retained at [`publications/ESSAY_TRANSLATION_GUIDE.md`](publications/ESSAY_TRANSLATION_GUIDE.md); the root translation guide above remains canonical.

## Publication status

Publications **1–8 are COMPLETE / FROZEN / RELEASED** in their established Tamil/English workflows.

### Publication 8 — சிந்தனையும் செயலும்

Workspace: [`publications/sinthanaiyum-seyalum/`](publications/sinthanaiyum-seyalum/)

**RELEASE COMPLETE / FROZEN.**

- controlling source: `TVA_BOK_0065568`, **226 scans**;
- Tamil P0–P5: **COMPLETE / STRICT-REVIEWED / RE-FROZEN**;
- P2: **226 / 226 VERIFIED**;
- P3: **50 / 50 VERIFIED**;
- P5: **226 / 226 PASS**;
- unresolved Tamil/source discrepancies: **0**;
- English T0–T5: **50 / 50 PASS at every gate**;
- verified English: **50 / 50**;
- drafts: **0 / 50**;
- E6: **COMPLETE / PASS**;
- E7: **COMPLETE / PASS**;
- release blockers: **0**.

Canonical release records:

- [`publications/sinthanaiyum-seyalum/translations/en/E6_CONSISTENCY_REVIEW.md`](publications/sinthanaiyum-seyalum/translations/en/E6_CONSISTENCY_REVIEW.md)
- [`publications/sinthanaiyum-seyalum/translations/en/E7_RELEASE_CLOSEOUT.md`](publications/sinthanaiyum-seyalum/translations/en/E7_RELEASE_CLOSEOUT.md)

### Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற

Workspace: [`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/)

**ACTIVE — P0/P1/P2 COMPLETE; P3 NEXT.**

- controlling source: `TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`;
- SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- physical scans: **8**;
- source form: **image-only government public-message pamphlet**;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- body: scans **3–7**;
- visible printed folios: **4–7** on scans 4–7; scan 3 has no visible folio;
- source p.7 calls the text a `செய்தி` issued during the family-planning fortnight that began **15 December 1975**; the exact message/publication date is not separately stated;
- P0 source intake: **COMPLETE / PASS**;
- P1 metadata/page-map/contents mapping: **COMPLETE / PASS**;
- P2 direct-visual page transcription: **8 / 8 VERIFIED / COMPLETE**;
- P3/P4/P5: **NOT STARTED**;
- English: **NOT STARTED; blocked until Tamil freeze**.

P2 preserved traditional-glyph underlying characters and source-specific forms without silent modernisation. The scan-5/6 `நாடாளு மன்ற...` witnesses are retained for an independent P5 recheck rather than conventionally corrected.

Current records:

- [`metadata/source.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/metadata/source.md)
- [`indexes/page-map.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/indexes/page-map.md)
- [`audit.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/audit.md)
- [`pages/`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/pages/)

### Permanent `உடன்பிறப்பே` rule

Every exact source `உடன்பிறப்பே` is retained as **`Udanpirappē`** in English; direct salutation **`Udanpirappē,`**. Related plural movement-address forms remain source-bearing.

## Current repository boundary

Publication 9 is the **active publication**. Exact next activity: **P3 single-text assembly from verified P2 scans 3–7**. Keep scan 7's bracketed source/occasion note outside the body and do not begin P4/P5/English in the same activity unless separately authorised.

Live `main` and root [`HANDOVER.md`](HANDOVER.md) remain authoritative.
