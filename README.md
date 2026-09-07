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

### Publication 8 — சிந்தனையும் செயலும்

**RELEASE COMPLETE / FROZEN.** Tamil P0–P5 complete/re-frozen; English T0–T5 **50 / 50 PASS**; E6/E7 **PASS**; blockers **0**.

### Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற

Workspace: [`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/)

**RELEASE COMPLETE / FROZEN.**

- controlling source: `TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`;
- source SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- physical scans: **8**;
- source type: **image-only government public-message pamphlet**;
- Tamil P0–P5: **COMPLETE / PASS / FROZEN**;
- Tamil P5 scans: **8 / 8 PASS**;
- frozen Tamil authority: [`articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md) — blob `1c5870212186b2bf7ff095b245e15cd875de76f0`;
- English title: **Freedom from the Prison of Suffering**;
- English T0–T5: **1 / 1 PASS / VERIFIED**;
- released English authority: [`translations/en/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md) — blob `57bb332530e5e6de12c74f2cd40ceaccf22e41b9`;
- E6: **COMPLETE / PASS**;
- E7: **COMPLETE / PASS / RELEASE COMPLETE**;
- unresolved Tamil blockers: **0**;
- unresolved English/release blockers: **0**.

English gate history:

- T1 `9a1f1fcc60104b561909380addbcbae422688fb2`;
- T2 `5377b7b90f87247dc910741b92244772a07bdf56`;
- T3 `df9750cfc46ac1f3519ff2d40bbe8bb3b69073a6`;
- T4 `943be32674cb3952c655f6bfed9f8b1fc0410969`;
- T5 verified/released `57bb332530e5e6de12c74f2cd40ceaccf22e41b9`;
- E6 **PASS / COMPLETE**;
- E7 **PASS / RELEASE COMPLETE**.

Canonical records:

- [`SOURCE_COMPLETENESS_AUDIT.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/SOURCE_COMPLETENESS_AUDIT.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`TRANSLATION_PLAN.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/TRANSLATION_PLAN.md)
- [`translations/en/LEXICON.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/LEXICON.md)
- [`translations/en/TRANSLATION_REVIEW.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/TRANSLATION_REVIEW.md)
- [`translations/en/E6_CONSISTENCY_REVIEW.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/E6_CONSISTENCY_REVIEW.md)
- [`translations/en/E7_RELEASE_CLOSEOUT.md`](publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/E7_RELEASE_CLOSEOUT.md)

E7 confirmed the frozen Tamil and verified English blobs were unchanged from the E6 baseline, the English source pin still matched the Tamil authority, post-E6 body/metadata drift was **0 / 0**, Tamil changes were **0**, and release blockers were **0**.

P5 source-supported corrections remain frozen: scan 2 `பெற........!` → `பெற..........!`; scan 7 `வெற்றிக் கனியினைக்` → `வெற்றிக்கனியினைக்`. P5-confirmed unusual Tamil forms such as `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே` remain unchanged.

### Permanent `உடன்பிறப்பே` rule

Every exact source `உடன்பிறப்பே` is retained as **`Udanpirappē`** in English; direct salutation **`Udanpirappē,`**.

## Current repository boundary

Publications **1–9 are RELEASE COMPLETE / FROZEN**. No further Publication 9 activity is pending absent a genuine source-supported or release-blocking defect.

Exact next project activity: **intake/onboarding of the next supplied Kalaignar essay/article publication**.

Live `main` and root [`HANDOVER.md`](HANDOVER.md) remain authoritative.
