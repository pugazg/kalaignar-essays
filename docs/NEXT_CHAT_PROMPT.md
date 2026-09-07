# NEXT CHAT PROMPT — Kalaignar Essays / next publication intake

Continue directly in `pugazg/kalaignar-essays`, branch `main`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Root `HANDOVER.md` is the single authoritative project handover.

Publications **1–9 are RELEASE COMPLETE / FROZEN**. Do not reopen them from stale prompts, stylistic preference, terminology homogenisation or modernisation.

Publication 9 — `வேதனைச் சிறையினின்றும் விடுதலை பெற` — is fully closed:

- Tamil P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**;
- frozen Tamil blob: `1c5870212186b2bf7ff095b245e15cd875de76f0`;
- English T0–T5: **1 / 1 PASS / VERIFIED**;
- released English blob: `57bb332530e5e6de12c74f2cd40ceaccf22e41b9`;
- E6: **PASS / COMPLETE**;
- E7: **PASS / RELEASE COMPLETE**;
- blockers: **0**;
- overall status: **RELEASE COMPLETE / FROZEN**.

Canonical Publication 9 closeout records:

- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/E6_CONSISTENCY_REVIEW.md`;
- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/E7_RELEASE_CLOSEOUT.md`.

## Mandatory startup for the next publication

1. read `ESSAY_PROCESSING_GUIDE.md` completely;
2. read `docs/FUTURE_WORK_GUIDELINES.md`;
3. read root `HANDOVER.md`;
4. read this prompt;
5. inspect live repository state before creating anything;
6. use `ESSAY_TRANSLATION_GUIDE.md` only after the new Tamil archival layer is complete/frozen.

## Exact next activity — new source intake / P0

When the user supplies the next Kalaignar essay/article/pamphlet/publication source:

1. identify the source filename and source form;
2. establish physical scan/page count from the controlling source;
3. record source identity/hash/size when available;
4. determine whether the source or its individual article/text units are already represented in the repository;
5. determine source-labelled publication classification without silently relabelling a message, speech, essay, foreword, article or pamphlet;
6. record edition/date/publication evidence exactly as supported by the source; do not infer missing dates;
7. decide the correct publication workspace/slug only after duplicate checking and source classification;
8. create P0 intake records only for genuinely new authorized material;
9. never commit the source PDF;
10. stop at the next gate boundary required by `ESSAY_PROCESSING_GUIDE.md`, unless the user explicitly authorises a broader batch.

## Frozen-work rule

Do not modify Publications 1–9 unless one of these applies:

- the user explicitly requests a targeted correction/review; or
- controlling-source evidence proves a genuine archival/release-blocking defect.

If a frozen Tamil authority changes, explicitly reopen every affected downstream English gate rather than silently patching a released translation.

Permanent repository translation rule remains: exact Tamil `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation → **`Udanpirappē,`**.
