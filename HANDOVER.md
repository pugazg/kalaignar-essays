# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**

## Repository state

Publications **1–8 are RELEASE COMPLETE / FROZEN**.

Publication **9 — `வேதனைச் சிறையினின்றும் விடுதலை பெற` — is ACTIVE** with P0/P1/P2/P3/P4 complete. Exact next gate: **P5 strict visual word/punctuation fidelity**.

Source PDFs are never committed.

## Mandatory startup

1. fetch live `main` first;
2. read `ESSAY_PROCESSING_GUIDE.md`;
3. read `docs/FUTURE_WORK_GUIDELINES.md`;
4. read this handover and `docs/NEXT_CHAT_PROMPT.md`;
5. for Publication 9 read its `README.md`, `metadata/source.md`, `indexes/page-map.md`, `indexes/contents.md`, `audit.md`, `SOURCE_COMPLETENESS_AUDIT.md`, all `pages/*.md`, and the P3 article assembly;
6. resolve/attach the controlling source before P5 source-level visual work;
7. read `ESSAY_TRANSLATION_GUIDE.md` only when English work becomes in scope after Tamil freeze;
8. preserve released/frozen Publications 1–8 unless controlling-source evidence proves a genuine defect or the user explicitly requests a targeted correction.

---

# Publication 9 — வேதனைச் சிறையினின்றும் விடுதலை பெற — ACTIVE

Workspace: `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`

## Controlling source

`TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`

Recorded identity:

- source ID: `TVA_BOK_0064064`;
- SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- size: **11,408,976 bytes**;
- physical scans: **8**;
- PDF text layer: **none / image-only**;
- publication form: **single-text government public-message pamphlet**;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- printer: `மாநில குடும்பநலத் திட்ட அச்சகம், சென்னை-6.`;
- source PDF committed: **No**.

## Printed identity / classification

Lexical title: `வேதனைச் சிறையினின்றும் விடுதலை பெற`.

Source witnesses:

- scan 1 cover: shorter final punctuation `... !`, `முதல்வர் டாக்டர் கலைஞர்`, portrait;
- scan 2 title page: same lexical title with longer dotted run before `!`, `தமிழ்நாடு முதல்வர் மாண்புமிகு டாக்டர் கலைஞர் மு. கருணாநிதி`, issuing body;
- scan 7 / printed p.7: bracketed note calls the body a **`செய்தி`** issued during the family-planning fortnight;
- scan 8: printer line.

Repository classification remains a standalone pamphlet/public-message publication, not a source-labelled speech.

## Date / occasion discipline

The scan-7 note says the `குடும்ப நலத்திட்ட இருவார விழா` began on **15 December 1975**.

- fortnight/event start: **15 December 1975 — source-supported**;
- exact message date: **not separately stated**;
- publication date: **not separately stated**.

Do not silently set the message/publication date to 15 December 1975.

## P2 page layer — COMPLETE / PASS

All **8 / 8** physical scans have verified direct-visual page records:

- scans 1–2: cover/title page;
- scans 3–7: complete body sequence;
- scan 8: back cover/printer.

Scan 3 has no inferred printed folio. Scan 7's bracketed source/occasion note is separated from the message body. P2 unresolved body-text blocks: **0**.

## P3 assembly — COMPLETE / PASS

Canonical assembly:

`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`

P3 result:

- assembled only from verified P2 body records scans **3–7**;
- ordered `<!-- Tamil source: scan ... -->` comments preserved for scans 3, 4, 5, 6, 7;
- body order / boundaries cross-checked;
- scan-7 bracketed source note kept outside the message body;
- omissions: **0**;
- duplicated body scans: **0**;
- reordered boundaries: **0**;
- P3 changes to P2 wording: **0**;
- unresolved P3 body-text blocks: **0**.

## P4 source/completeness audit — COMPLETE / PASS

Canonical record:

`publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/SOURCE_COMPLETENESS_AUDIT.md`

P4 confirmed:

- source inventory: **8 / 8 physical scans represented**;
- page records: **8 / 8 present, all `verified`**;
- P3 assemblies: **1 / 1 present**;
- body source comments: **3 → 4 → 5 → 6 → 7**, exactly once each;
- body omission / duplication / reorder: **0 / 0 / 0**;
- scan-7 source note outside body: **PASS**;
- scans 1, 2 and 8 excluded from body assembly: **PASS**;
- classification/date discipline: **PASS**;
- active P4 `needs-review` / `blocked`: **0 / 0**;
- unresolved body-completeness blockers: **0**;
- Tamil page/article-body changes during P4: **0**.

P4 found one stale workflow footer in `indexes/page-map.md` that still named P3 as pending. That footer and current-state documents were synchronized; this was not a source-text defect.

## Historical glyph / lexical non-regression

Traditional/pre-reform glyph shapes are encoded as scan-supported underlying Tamil characters without lexical modernisation.

Preserve and independently verify in P5 at minimum:

- scan 3 `எங்கணும்`, `உறையுள்`, `விமானத்தைவிடப்`, `யானைப் பசிக்குப் போட்ட சோளப் பொறி`;
- scan 4 `உலகு`, `யந்திரங்களாகவே`;
- scan 5 `அறுவை சிகிச்சைகள்` versus later `அறுவைச் சிகிச்சைக்கென்று`;
- scan 5/6 `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே` — **mandatory independent P5 recheck; do not silently normalise**;
- scan 7 `முன்பியக்கம்`, `முன்பியக்கக்`;
- source-note `டிசம்பர் திங்கள் 15-ம் நாள் துவங்கிய`;
- independent cover/title-page punctuation witnesses.

## Current gate state

- P0 source intake / publication identification: **COMPLETE / PASS**;
- P1 metadata + page map + contents mapping: **COMPLETE / PASS**;
- P2 page-level transcription: **COMPLETE / PASS — 8 / 8 VERIFIED**;
- P3 single-text assembly: **COMPLETE / PASS — 1 / 1**;
- P4 source/completeness audit: **COMPLETE / PASS**;
- P5 strict visual word/punctuation fidelity: **NOT STARTED**;
- English: **NOT STARTED / BLOCKED until Tamil freeze**.

P4 completion does not equal final Tamil freeze.

## Exact next activity — P5 strict visual word/punctuation fidelity

When authorised:

1. fetch live `main` and re-read this handover plus `SOURCE_COMPLETENESS_AUDIT.md`;
2. resolve/attach the controlling PDF and verify its recorded identity where possible;
3. visually inspect **all 8 physical scans**, including cover, title page, all five body scans and back cover;
4. compare every visible word, historical glyph, word boundary/spacing, punctuation mark, heading, number/date, paragraph boundary and source-witness distinction against the canonical page record;
5. keep print and physical-copy marks separate;
6. independently recheck the full historical-glyph/source-form watchlist, especially `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே`;
7. do not modernise or conventionalise a source-supported form;
8. record every confirmed correction as old reading → source-visible reading with scan provenance;
9. propagate confirmed page corrections to the P3 article and dependent metadata/index/readme/audit/handover records;
10. create/update `VISUAL_TEXT_FIDELITY_REVIEW.md` with the full 8 / 8 result;
11. only if all scans pass and blockers are 0, freeze the Tamil archival layer and then make English the next gate;
12. stop after P5. Do not begin English in the same iteration unless the user separately authorises it after Tamil freeze.

---

# Publication 8 — சிந்தனையும் செயலும் — RELEASE COMPLETE / FROZEN

Final durable state remains unchanged: Tamil P0–P5 complete/re-frozen, 50/50 English T5 verified, E6/E7 PASS, blockers 0. Preserve its permanent `உடன்பிறப்பே` → `Udanpirappē` rule and other frozen source-witness decisions. Do not reopen it from a stale prompt.
