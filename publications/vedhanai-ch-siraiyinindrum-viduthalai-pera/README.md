# வேதனைச் சிறையினின்றும் விடுதலை பெற

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Workspace: `publications/vedhanai-ch-siraiyinindrum-viduthalai-pera/`  
Controlling source: `TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`  
Source PDF committed: **No**

## Publication identity

This is an **8-scan, image-only government public-message pamphlet** issued by the `தமிழ்நாடு குடும்ப நலத்துறை`.

The source itself describes the text on printed p.7 as a **`செய்தி`** issued by Tamil Nadu Chief Minister Kalaignar M. Karunanidhi to the people during a family-planning fortnight. It is archived here as a standalone pamphlet/public-message publication; it is not silently relabelled as a conventional essay or delivered speech.

Lexical title: `வேதனைச் சிறையினின்றும் விடுதலை பெற`.

Cover and title-page punctuation are independent source witnesses and remain separate in the page layer.

## Source identity

- source ID: `TVA_BOK_0064064`;
- SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`;
- size: **11,408,976 bytes**;
- scans: **8**;
- OCR/text layer: **none**;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- printer: `மாநில குடும்பநலத் திட்ட அச்சகம், சென்னை-6.`;
- separate edition statement / price / publication date: **not visibly stated in the supplied scans**.

Detailed source record: [`metadata/source.md`](metadata/source.md).

## Source-described occasion

Printed p.7 says the message was issued during the `குடும்ப நலத்திட்ட இருவார விழா` that began on **15 December 1975**.

That date is the source-supported **start date of the fortnight**. The exact message/publication date is not separately stated and must not be inferred as 15 December merely from the occasion note.

## Page layer

- scan 1 — front cover — [`pages/0001-cover.md`](pages/0001-cover.md);
- scan 2 — title page — [`pages/0002-title-page.md`](pages/0002-title-page.md);
- scan 3 — body opening, no visible folio — [`pages/0003-body-opening.md`](pages/0003-body-opening.md);
- scan 4 / printed p.4 — [`pages/0004-body.md`](pages/0004-body.md);
- scan 5 / printed p.5 — [`pages/0005-body.md`](pages/0005-body.md);
- scan 6 / printed p.6 — [`pages/0006-body.md`](pages/0006-body.md);
- scan 7 / printed p.7 — body close + bracketed source note — [`pages/0007-body-close.md`](pages/0007-body-close.md);
- scan 8 — back cover / printer line — [`pages/0008-back-cover.md`](pages/0008-back-cover.md).

No printed contents page is present. One continuous message body runs through scans **3–7**.

## Canonical P3 assembly

- [`articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md`](articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md)
- assembled only from P2-verified body records scans **3–7**;
- ordered `<!-- Tamil source: scan ... -->` comments retained for all five body scans;
- scan-7 bracketed occasion/source note retained outside the message body;
- assembly omissions / duplications / reordered boundaries: **0 / 0 / 0**.

## P4 source/completeness audit

Canonical record: [`SOURCE_COMPLETENESS_AUDIT.md`](SOURCE_COMPLETENESS_AUDIT.md).

**P4 RESULT: PASS.**

- physical source scans represented by canonical P2 records: **8 / 8 PASS**;
- page statuses: **8 / 8 `verified`**;
- canonical P3 body assemblies: **1 / 1 PASS**;
- body order: **scan 3 → 4 → 5 → 6 → 7 PASS**;
- ordered assembly source comments: **5 / 5 PASS**;
- body omission / duplication / reorder: **0 / 0 / 0**;
- scan-7 printed source note remains outside message body: **PASS**;
- scans 1, 2 and 8 remain outside body assembly: **PASS**;
- P4 `needs-review` / `blocked`: **0 / 0**;
- unresolved body-completeness blockers: **0**.

P4 found one stale documentation footer in `indexes/page-map.md` that still described P3 as not started. That workflow footer has been synchronized; no page text or article-body text changed.

## Historical Tamil typography / non-regression

Traditional/pre-reform glyphs are encoded as their scan-supported underlying Tamil characters while preserving genuine historical/source wording, punctuation and irregularities.

Preserve through P5 at minimum:

- scan 3 `எங்கணும்`, `உறையுள்`, `விமானத்தைவிடப்`, `யானைப் பசிக்குப் போட்ட சோளப் பொறி`;
- scan 4 `உலகு`, `யந்திரங்களாகவே`;
- scan 5 `அறுவை சிகிச்சைகள்` versus later `அறுவைச் சிகிச்சைக்கென்று`;
- scan 5/6 `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே` — independently recheck in P5; do not silently normalise;
- scan 7 `முன்பியக்கம்`, `முன்பியக்கக்`;
- source-note `டிசம்பர் திங்கள் 15-ம் நாள் துவங்கிய`;
- independent cover/title-page punctuation witnesses.

## Workflow state

### Tamil archival layer

- P0 — source intake / publication identification: **COMPLETE / PASS**
- P1 — metadata + page map + contents mapping: **COMPLETE / PASS**
- P2 — page-level transcription: **COMPLETE / PASS — 8 / 8 VERIFIED**
- P3 — single-text assembly: **COMPLETE / PASS — 1 / 1**
- P4 — source/completeness audit: **COMPLETE / PASS**
- P5 — strict visual word/punctuation fidelity: **NOT STARTED**
- unresolved body-completeness blockers: **0**

P4 completion is not P5/final Tamil freeze.

### English

**NOT STARTED.** English translation must not begin until the Tamil archival layer is P5-complete and frozen.

## Exact next activity

**P5 — strict visual word/punctuation fidelity over all 8 physical scans.**

Re-open the controlling source and compare every visible printed word, historical glyph, spacing/word boundary, punctuation mark, heading, date, number, paragraph continuation, physical-copy exclusion and independent source witness against the canonical page records. Propagate any confirmed correction to the P3 assembly and durable records with provenance.
