# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**

## Repository state

Publications **1–8 are RELEASE COMPLETE / FROZEN**.

Publication **9 — `வேதனைச் சிறையினின்றும் விடுதலை பெற` — is ACTIVE** at P0/P1 complete, with P2 page transcription next.

Source PDFs are never committed.

## Mandatory startup

1. fetch live `main` first;
2. read `ESSAY_PROCESSING_GUIDE.md`;
3. read `docs/FUTURE_WORK_GUIDELINES.md`;
4. read this handover and `docs/NEXT_CHAT_PROMPT.md`;
5. for Publication 9 read its `README.md`, `metadata/source.md`, `indexes/page-map.md`, `indexes/contents.md`, and `audit.md`;
6. read `ESSAY_TRANSLATION_GUIDE.md` only when English work becomes in scope after Tamil freeze;
7. preserve released/frozen Publications 1–8 unless controlling-source evidence proves a genuine defect or the user explicitly requests a targeted correction.

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

- scan 1 cover: title + `முதல்வர் டாக்டர் கலைஞர்` + portrait;
- scan 2 title page: same lexical title, different final punctuation treatment, `தமிழ்நாடு முதல்வர் மாண்புமிகு டாக்டர் கலைஞர் மு. கருணாநிதி`, and the issuing body;
- scan 7 printed p.7: bracketed note describes the body as a **`செய்தி`** issued to the people during the family-planning fortnight;
- scan 8: printer line.

Repository-placement decision: keep this in `kalaignar-essays` as a **standalone pamphlet/public-message publication**. The source does not label it `பேச்சு` or `உரை`; do not silently convert it into a speech record.

Duplicate check at intake:

- exact title / source ID in `kalaignar-essays`: **none found**;
- exact title / source ID in `kalaignar-public-speeches`: **none found**.

## Date / occasion discipline

The bracketed source note says the `குடும்ப நலத்திட்ட இருவார விழா` began on **15 December 1975** and identifies this as a message issued during that fortnight.

Therefore:

- fortnight/event start: **15 December 1975 — source-supported**;
- exact message date: **not separately stated**;
- publication date: **not separately stated**.

Do not silently set the message/publication date to 15 December 1975.

## Page map

| Scan | Printed folio | Role |
|---:|---|---|
| 1 | — | front cover / portrait / title |
| 2 | — | title page / creator / issuing body |
| 3 | no visible folio | body start |
| 4 | 4 | body |
| 5 | 5 | body |
| 6 | 6 | body |
| 7 | 7 | body close + bracketed source/occasion note |
| 8 | — | back cover / printer line |

Body scans: **3–7 / 5 scans**.  
Printed contents page: **none**.  
Body units: **one continuous text**.

## Physical / typography condition

- ageing and staining throughout;
- cover wear/abrasion;
- circular blue library/physical-copy stamp on scan 1, not printed text;
- light reverse-side show-through on body pages;
- traditional/pre-reform Tamil glyph forms throughout the body.

Historical glyph handling:

- use direct visual comparison;
- resolve the scan-supported **underlying Tamil character** represented by the historical glyph;
- preserve genuine source spelling, wording, punctuation and irregularities;
- do not modernize from OCR/memory/context;
- flag unresolved readings rather than guessing.

## Current gate state

- P0 source intake / publication identification: **COMPLETE / PASS**;
- P1 metadata + page map + contents mapping: **COMPLETE / PASS**;
- P2 page-level transcription: **NOT STARTED — 0 / 8**;
- P3 single-text assembly: **NOT STARTED**;
- P4 source/completeness audit: **NOT STARTED**;
- P5 strict visual word/punctuation fidelity: **NOT STARTED**;
- English: **NOT STARTED / BLOCKED until Tamil freeze**.

No Publication 9 page or body text has yet been marked P5/final-verified.

## Exact next activity — P2 scans 1–8

Perform **P2 direct-visual page transcription for all eight scans in one iteration**:

1. create one canonical `pages/*.md` record for each physical scan 1–8;
2. preserve separate printed-text vs physical-copy-mark layers;
3. scan 1: record cover title/creator/portrait and the later library stamp separately;
4. scan 2: transcribe title-page witnesses and issuing body;
5. scans 3–7: transcribe the complete Tamil message body directly from the scan, preserving paragraph boundaries, punctuation, numbers, source wording and historical-glyph underlying characters;
6. scan 3 remains without a printed folio unless a folio becomes visibly demonstrable;
7. scan 7: preserve the bracketed source/occasion note as printed matter, separate from the main message body where structurally appropriate;
8. scan 8: record the printer line;
9. update `indexes/page-map.md`, `README.md`, `audit.md`, this handover and `docs/NEXT_CHAT_PROMPT.md` after the P2 batch;
10. **do not** perform P3/P4/P5 or English in the same activity unless the handover is explicitly advanced after P2 and the user separately says to proceed.

---

# Publication 8 — சிந்தனையும் செயலும் — RELEASE COMPLETE / FROZEN

Workspace: `publications/sinthanaiyum-seyalum/`

Final durable state:

- Tamil P0–P5: **COMPLETE / PASS / STRICT-REVIEWED / RE-FROZEN**;
- P2: **226 / 226 VERIFIED**;
- P3: **50 / 50 VERIFIED**;
- P5: **226 / 226 PASS**;
- English T0–T5: **50 / 50 PASS**;
- E6: **COMPLETE / PASS**;
- E7: **COMPLETE / PASS**;
- release status: **RELEASE COMPLETE / FROZEN**;
- blockers: **0**.

Permanent Publication 8 non-regression remains binding, including exact source `உடன்பிறப்பே` → `Udanpirappē`, independent contents/heading witnesses, Article 29 unusual Kural witness, Article 44 `Kannan`, Article 45 source title/`Valiyuruthal`, Article 46 conservative non-numeric rendering, Article 47 `thalagaani urai`, Article 49 `Sengattu Nangai`, and Article 50 restored scan-222 reflection.

Do not reopen Publication 8 because of a stale prompt.
