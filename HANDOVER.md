# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**

## Repository state

Publications **1–8 are RELEASE COMPLETE / FROZEN**.

Publication **9 — `வேதனைச் சிறையினின்றும் விடுதலை பெற` — has Tamil P0–P5 COMPLETE / STRICT-REVIEWED / FROZEN and English E0/T0 COMPLETE / PASS.** Exact next gate: **T1 — close English draft for Article 1**.

Source PDFs are never committed.

## Mandatory startup

1. fetch live `main` first;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely before English drafting;
3. read `docs/FUTURE_WORK_GUIDELINES.md`;
4. read this handover and `docs/NEXT_CHAT_PROMPT.md`;
5. for Publication 9 read its `README.md`, `TRANSLATION_PLAN.md`, `translations/en/README.md`, `translations/en/LEXICON.md`, and `translations/en/TRANSLATION_REVIEW.md`;
6. re-fetch the frozen Tamil authority `articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md` and confirm its live blob SHA before T1;
7. consult `VISUAL_TEXT_FIDELITY_REVIEW.md` or page records only when a source-witness/punctuation question genuinely requires it;
8. translate from the frozen strict-reviewed Tamil article, never OCR, raw PDF, web text, another edition, memory, or a pre-P5 transcription;
9. preserve released/frozen Publications 1–8 unless controlling-source evidence proves a genuine defect or the user explicitly requests a targeted correction.

---

# Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற

Workspace: `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`

## Controlling source / classification

`TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`

- source ID: `TVA_BOK_0064064`;
- SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- size: **11,408,976 bytes**;
- physical scans: **8**;
- image-only / no PDF text layer;
- source form: **single-text government public-message pamphlet**;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- printer: `மாநில குடும்பநலத் திட்ட அச்சகம், சென்னை-6.`;
- source p.7 calls the body a **`செய்தி`**, not `பேச்சு` / `உரை`.

The bracketed scan-7 source note says the family-welfare fortnight began on **15 December 1975**. It does **not** separately state an exact message date or publication date.

## Tamil archival authority — COMPLETE / FROZEN

Canonical frozen article:

`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`

Frozen strict-reviewed blob SHA confirmed at E0:

`1c5870212186b2bf7ff095b245e15cd875de76f0`

Source provenance:

- body scans: **3 → 4 → 5 → 6 → 7**;
- scan 3: no visible printed folio;
- scans 4–7: visible printed folios 4–7;
- scan-7 bracketed source/occasion note: **outside the message body**;
- article status: **`strict-reviewed`**.

Tamil gate state:

- P0: **COMPLETE / PASS**;
- P1: **COMPLETE / PASS**;
- P2: **8 / 8 VERIFIED / COMPLETE**;
- P3: **1 / 1 COMPLETE / PASS**;
- P4: **COMPLETE / PASS**;
- P5: **8 / 8 COMPLETE / PASS**;
- unresolved Tamil fidelity discrepancies: **0**;
- Tamil blockers: **0**.

P5 source-supported corrections remain frozen:

1. scan 2: `பெற........!` → `பெற..........!` — 10 printed dots before `!`;
2. scan 7: `வெற்றிக் கனியினைக்` → `வெற்றிக்கனியினைக்` — propagated to the article.

P5 independently confirmed unusual/source-sensitive Tamil forms including `எங்கணும்`, `உறையுள்`, `உலகு`, `யந்திரங்களாகவே`, `நாடாளு மன்றத்தில்`, `நாடாளு மன்றமே`, `முன்பியக்கம்`, and `முன்பியக்கக்`. Do not alter the frozen Tamil layer for translation convenience.

## English E0 / T0 — COMPLETE / PASS

Created:

- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/TRANSLATION_PLAN.md`
- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/README.md`
- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/LEXICON.md`
- `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/translations/en/TRANSLATION_REVIEW.md`

E0 result:

- frozen Tamil authority re-fetched live: **PASS**;
- T0 source prerequisite: **1 / 1 PASS**;
- English article files: **0 / 1**;
- English body drafted during E0: **No**;
- setup blockers: **0**.

Future English article file:

`translations/en/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`

Working English title:

**Freedom from the Prison of Suffering**

Planned T1 frontmatter must include:

- `source_tamil: "../../articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md"`;
- `source_tamil_blob_sha: "1c5870212186b2bf7ff095b245e15cd875de76f0"`;
- `source_scan_pages: "3-7"`;
- `source_printed_pages: "scan 3 unnumbered; scans 4-7 visibly 4-7"`;
- `translation_status: "draft"`;
- `translation_method: "close rhetorical translation preserving Kalaignar's voice"`.

## T1 non-regression / risk register

The living lexicon and review ledger are authoritative for setup history. High-attention passages include:

- title/central metaphor `வேதனைச் சிறை` — preserve prison + suffering imagery;
- `யானைப் பசிக்குப் போட்ட சோளப் பொறி` — preserve elephant-hunger/tiny-food image, not a substitute English idiom;
- `பிள்ளை உற்பத்தி` and `பிள்ளை பெறும் யந்திரங்களாகவே` — preserve deliberately stark production/machine imagery;
- `பேறுகாலம்` — contextual choice still open;
- `சிறு குடும்ப நெறி` — provisional `small-family norm`;
- `உலக மக்கள் தொகை ஆண்டு` / `உலக மகளிர் ஆண்டு` — translate source labels as printed; do not silently import outside official English titles;
- source-confirmed `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே` — English referent is Parliament; do not edit Tamil to conventional spelling;
- `முன்பியக்கம்` / `முன்பியக்கக் காலம்` — provisional administrative/campaign rendering requires T1/T2 review;
- scan-6 repeated dash-ended parallel clauses — preserve accumulative cadence;
- `நத்தையென` — preserve snail image;
- closing `வெற்றிக்கனியினைக் கொய்திட` — preserve fruit/harvest metaphor;
- preserve all numbers/dates and their relationships exactly in meaning.

Source-page comments required in the English draft, in order:

1. `<!-- Tamil source: scan 3 -->`
2. `<!-- Tamil source: scan 4 -->`
3. `<!-- Tamil source: scan 5 -->`
4. `<!-- Tamil source: scan 6 -->`
5. `<!-- Tamil source: scan 7 -->`

The scan-7 printed source/occasion note must remain outside Kalaignar's message body if translated.

Permanent repository rule remains: exact Tamil `உடன்பிறப்பே` → `Udanpirappē`; direct salutation → `Udanpirappē,`.

## Current gate state

- Tamil P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**;
- E0 translation planning/setup: **COMPLETE / PASS**;
- T0 source prerequisite: **1 / 1 PASS**;
- T1 close English draft: **NOT STARTED / NEXT**;
- T2: **NOT STARTED**;
- T3: **NOT STARTED**;
- T4: **NOT STARTED**;
- T5: **NOT STARTED**;
- E6/E7: **NOT STARTED**;
- English article files: **0 / 1**;
- blockers: **0**.

## Exact next activity — T1 close English draft

When authorised:

1. fetch live `main` first;
2. re-fetch the frozen Tamil article and confirm blob `1c5870212186b2bf7ff095b245e15cd875de76f0` still controls;
3. read the translation plan, living lexicon, and translation review ledger;
4. create `translations/en/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md` with the planned metadata;
5. translate the **entire** frozen Tamil message paragraph by paragraph;
6. preserve all five ordered source-page comments, rhetorical questions, exclamations, dashes, repetitions, images, numbers and dates;
7. keep the scan-7 source/occasion note clearly separated outside the message body;
8. update `LEXICON.md` and `TRANSLATION_REVIEW.md` with actual T1 decisions and any material title/terminology choice;
9. mark the English article `translation_status: draft` and T1 complete only after the full body is present;
10. stop after T1. Do **not** begin T2 in the same activity unless separately authorised.

---

# Publication 8 — சிந்தனையும் செயலும் — RELEASE COMPLETE / FROZEN

Final durable state remains unchanged: Tamil P0–P5 complete/re-frozen, 50/50 English T5 verified, E6/E7 PASS, blockers 0. Preserve its permanent `உடன்பிறப்பே` → `Udanpirappē` rule and other frozen source-witness decisions. Do not reopen it from a stale prompt.
