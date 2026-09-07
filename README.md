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

A compatibility pointer for historical translation-review links is retained at [`publications/ESSAY_TRANSLATION_GUIDE.md`](publications/ESSAY_TRANSLATION_GUIDE.md); the root translation guide remains canonical.

## Publication status

Publications **1–8 are COMPLETE / FROZEN / RELEASED** in their established Tamil/English workflows.

### Publication 8 — சிந்தனையும் செயலும்

Workspace: [`publications/sinthanaiyum-seyalum/`](publications/sinthanaiyum-seyalum/)

**RELEASE COMPLETE / FROZEN.**

- Tamil P0–P5: **COMPLETE / STRICT-REVIEWED / RE-FROZEN**;
- P2: **226 / 226 VERIFIED**;
- P3: **50 / 50 VERIFIED**;
- P5: **226 / 226 PASS**;
- English T0–T5: **50 / 50 PASS**;
- E6: **COMPLETE / PASS**;
- E7: **COMPLETE / PASS**;
- blockers: **0**.

Canonical closeout records:

- [`publications/sinthanaiyum-seyalum/translations/en/E6_CONSISTENCY_REVIEW.md`](publications/sinthanaiyum-seyalum/translations/en/E6_CONSISTENCY_REVIEW.md)
- [`publications/sinthanaiyum-seyalum/translations/en/E7_RELEASE_CLOSEOUT.md`](publications/sinthanaiyum-seyalum/translations/en/E7_RELEASE_CLOSEOUT.md)

### Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற

Workspace: [`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/)

**TAMIL COMPLETE / STRICT-REVIEWED / FROZEN — ENGLISH E0/T0 COMPLETE; T1 NEXT.**

- controlling source: `TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`;
- SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- physical scans: **8**;
- source form: **image-only government public-message pamphlet**;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- body: scans **3–7**;
- source p.7 calls the text a `செய்தி` issued during the family-planning fortnight that began **15 December 1975**; exact message/publication date is not separately stated;
- P0–P5: **COMPLETE / PASS**;
- P5: **8 / 8 physical scans PASS**;
- unresolved Tamil fidelity discrepancies: **0**;
- Tamil workflow blockers: **0**;
- frozen Tamil authority: [`articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md), blob `1c5870212186b2bf7ff095b245e15cd875de76f0`;
- E0 English planning/setup: **COMPLETE / PASS**;
- T0 source prerequisite: **1 / 1 PASS**;
- English article files: **0 / 1**;
- T1 close draft: **NOT STARTED / NEXT**;
- English setup blockers: **0**.

English setup records:

- [`TRANSLATION_PLAN.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/TRANSLATION_PLAN.md)
- [`translations/en/README.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/README.md)
- [`translations/en/LEXICON.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/TRANSLATION_REVIEW.md)

Working English title: **Freedom from the Prison of Suffering**.

No English body was drafted during E0. The future T1 translation must use the frozen strict-reviewed Tamil assembly only, preserve the five source-page comments, and keep the scan-7 source/occasion note outside the message body.

Canonical Tamil audit records:

- [`SOURCE_COMPLETENESS_AUDIT.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/SOURCE_COMPLETENESS_AUDIT.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/VISUAL_TEXT_FIDELITY_REVIEW.md)

P5 source-supported corrections remain frozen:

1. scan 2 title page: `பெற........!` → `பெற..........!` — **10 printed dots** before `!`;
2. scan 7 final paragraph: `வெற்றிக் கனியினைக்` → `வெற்றிக்கனியினைக்`.

The independently rechecked source forms `நாடாளு மன்றத்தில்` and `நாடாளு மன்றமே` are confirmed from the source pixels and remain unchanged. Other flagged historical/source-sensitive forms, including `எங்கணும்`, `உறையுள்`, `உலகு`, `யந்திரங்களாகவே`, `முன்பியக்கம்` and `முன்பியக்கக்`, also passed P5 without conventionalisation.

### Permanent `உடன்பிறப்பே` rule

Every exact source `உடன்பிறப்பே` is retained as **`Udanpirappē`** in English; direct salutation **`Udanpirappē,`**. Related plural movement-address forms remain source-bearing.

## Current repository boundary

Publication 9 Tamil is **COMPLETE / STRICT-REVIEWED / FROZEN** and English **E0/T0 is COMPLETE / PASS**. Exact next activity: **T1 — close English draft for Article 1**, translating only from frozen Tamil blob `1c5870212186b2bf7ff095b245e15cd875de76f0` and stopping before T2.

Live `main` and root [`HANDOVER.md`](HANDOVER.md) remain authoritative.
