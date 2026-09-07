# P4 source / completeness audit — வேதனைச் சிறையினின்றும் விடுதலை பெற

Controlling source: `TVA_BOK_0064064_வேதனைச்_சிறையினின்றும்_விடுதலை_பெற.pdf`  
Physical scans: **8**  
Recorded SHA-256: `d6429304ca8e53324e41fbe6695a31d1411b12ec5e04bf5a35d8cc8a51d06651`

## Scope

This is the publication-level **P4 source / completeness audit**. It audits the completed P2 page layer and the single P3 canonical assembly for inventory, order, boundaries, provenance, exclusions, source-note separation and documentation consistency.

It is **not** the P5 strict word-by-word / punctuation-by-punctuation visual fidelity pass. P4 therefore does not use contextual expectation to rewrite any source-sensitive Tamil form. All lexical/glyph questions specifically queued for P5 remain deferred.

## Canonical inventory

| Layer | Expected | Present | Result |
|---|---:|---:|---|
| Physical source scans | 8 | 8 | **PASS** |
| Canonical P2 page records | 8 | 8 | **PASS** |
| Canonical P3 message assemblies | 1 | 1 | **PASS** |
| Duplicate / extra message assemblies | 0 | 0 | **PASS** |

The canonical `pages/` directory contains exactly one record for every physical scan:

1. `0001-cover.md` — scan 1 — VERIFIED;
2. `0002-title-page.md` — scan 2 — VERIFIED;
3. `0003-body-opening.md` — scan 3 — VERIFIED;
4. `0004-body.md` — scan 4 — VERIFIED;
5. `0005-body.md` — scan 5 — VERIFIED;
6. `0006-body.md` — scan 6 — VERIFIED;
7. `0007-body-close.md` — scan 7 — VERIFIED;
8. `0008-back-cover.md` — scan 8 — VERIFIED.

Canonical assembly:

- `articles/01-vedhanai-ch-siraiyinindrum-viduthalai-pera.md` — body scans **3–7** — status `verified`.

## Publication order / boundary audit

Source reading order remains:

`1 → 2 → 3 → 4 → 5 → 6 → 7 → 8`

| Source unit | Boundary | P4 result |
|---|---|---|
| front cover | scan 1 only | **PASS** |
| title page / issuing body | scan 2 only | **PASS** |
| Chief Minister's message body | scan 3 opening → scan 7 closing paragraph | **PASS** |
| printed source / occasion note | scan 7, after the message body | **PASS / kept outside body** |
| back cover / printer witness | scan 8 only | **PASS / excluded from body** |

Scan 3 remains without an inferred printed folio. Scans 4–7 retain the visible printed folios 4, 5, 6 and 7. There is no printed contents page and no second body unit.

## P3 assembly reconciliation

The P3 article was reconciled section-by-section against the verified P2 body records.

| Assembly segment | Canonical P2 source | Result |
|---|---|---|
| `<!-- Tamil source: scan 3 -->` segment | `pages/0003-body-opening.md` / `# அச்சு உரை` | **PASS** |
| `<!-- Tamil source: scan 4 -->` segment | `pages/0004-body.md` / `# அச்சு உரை` | **PASS** |
| `<!-- Tamil source: scan 5 -->` segment | `pages/0005-body.md` / `# அச்சு உரை` | **PASS** |
| `<!-- Tamil source: scan 6 -->` segment | `pages/0006-body.md` / `# அச்சு உரை` | **PASS** |
| `<!-- Tamil source: scan 7 -->` segment | `pages/0007-body-close.md` / message body only | **PASS** |

Ordered source comments present exactly once and in order: **3, 4, 5, 6, 7 — PASS**.

P4 found:

- omitted body scan: **0**;
- duplicated body scan: **0**;
- reordered body boundary: **0**;
- P3 lexical/body rewrite relative to P2: **0 found**;
- unresolved body-completeness block: **0**.

## Scan-7 source / occasion note audit

The printed bracketed note is preserved after a horizontal separation under:

`## அச்சிடப்பட்ட source / occasion note — scan 7`

It is **not** merged into Kalaignar's message body and is **not** treated as a second article. Its wording remains:

`1975-ஆம் ஆண்டு டிசம்பர் திங்கள் 15-ம் நாள் துவங்கிய ... அவர்கள் நாட்டு மக்களுக்கு விடுத்துள்ள செய்தி`

The date continues to establish the **start of the family-planning fortnight**, not a separately stated exact message/publication date.

**Source-note separation / date-discipline result: PASS.**

## Required exclusions audit

- scan 1 cover title/portrait/creator matter is not imported into the message body: **PASS**;
- scan 1 later blue library/physical-copy stamp is not imported into the message body: **PASS**;
- scan 2 title-page/issuing-body matter is not imported into the message body: **PASS**;
- scan 7 bracketed source note is outside the message body: **PASS**;
- scan 8 printer line / back-cover matter is not imported into the message body: **PASS**;
- physical-copy ageing, staining and show-through are not represented as source prose: **PASS**.

## Classification / metadata audit

The durable records agree on the following source-supported classification:

- publication form: **single-text government public-message pamphlet**;
- source wording for the item: **`செய்தி`**;
- it is not silently relabelled as `பேச்சு` or `உரை`;
- issuing body: `தமிழ்நாடு குடும்ப நலத்துறை வெளியீடு`;
- printer: `மாநில குடும்பநலத் திட்ட அச்சகம், சென்னை-6.`;
- event/fortnight start: **15 December 1975**;
- exact message date: **not separately stated**;
- publication date: **not separately stated**.

**Classification / date-discipline result: PASS.**

## Historical-glyph / lexical non-regression

P4 preserves the P2/P3 source forms without conventionalisation. High-attention witnesses remain:

- scan 3: `எங்கணும்`, `உறையுள்`, `விமானத்தைவிடப்`, `யானைப் பசிக்குப் போட்ட சோளப் பொறி`;
- scan 4: `உலகு`, `யந்திரங்களாகவே`;
- scan 5: `அறுவை சிகிச்சைகள்` versus later `அறுவைச் சிகிச்சைக்கென்று`;
- scan 5/6: `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே`;
- scan 7: `முன்பியக்கம்`, `முன்பியக்கக்`;
- source note: `டிசம்பர் திங்கள் 15-ம் நாள் துவங்கிய`;
- independent scan-1 / scan-2 title punctuation witnesses.

The `நாடாளு மன்ற...` forms remain explicitly **deferred to independent P5 visual recheck**. P4 neither confirms them as final-frozen nor normalises them.

## Open-marker / workflow-state sweep

Publication 9 durable records were checked for active workflow blockers.

- active `TODO`: **0**;
- active page `partial`: **0**;
- active page `needs-review`: **0**;
- active page `blocked`: **0**;
- unresolved body-text blocks: **0**;
- P4 source/completeness blockers: **0**.

References saying P5 or English are not started are expected workflow state, not blockers.

One documentation-state inconsistency was found during P4: `indexes/page-map.md` still carried the pre-P3 line `P3 single-text assembly: NOT STARTED` and named P3 as the next activity. The page map itself was structurally correct; only the workflow-status footer was stale. P4 corrects that footer and synchronizes the related current-state records. No Tamil page text or article-body text is changed by this correction.

## P4 checklist result

| Check | Result |
|---|---|
| 8 / 8 physical scans represented by canonical P2 records | **PASS** |
| 8 / 8 page records status `verified` | **PASS** |
| Exactly one canonical P3 body assembly | **PASS** |
| Body start scan 3 / body close scan 7 | **PASS** |
| Source comments 3 → 4 → 5 → 6 → 7 exactly once | **PASS** |
| Body omissions / duplications / reorder | **0 / 0 / 0** |
| Scan-7 bracketed note outside message body | **PASS** |
| Cover/title/back-cover matter excluded from body | **PASS** |
| Physical-copy marks excluded from body | **PASS** |
| Publication classification / date discipline | **PASS** |
| Silent lexical normalisation introduced during P3/P4 | **0 found** |
| Deferred P5 witness list preserved | **PASS** |
| Active P4 `needs-review` / `blocked` items | **0 / 0** |
| Unresolved body-completeness blockers | **0** |

## P4 result

**P4 SOURCE / COMPLETENESS AUDIT: PASS.**

Tamil archival structure is complete through P4:

- P0: **COMPLETE / PASS**;
- P1: **COMPLETE / PASS**;
- P2: **8 / 8 VERIFIED / COMPLETE**;
- P3: **1 / 1 COMPLETE / PASS**;
- P4: **COMPLETE / PASS**;
- P5: **NOT STARTED**.

P4 is not the final Tamil freeze.

## Exact next activity

Proceed with **P5 strict visual word/punctuation fidelity over all 8 physical scans**.

P5 must re-open the controlling scan images and independently compare every visible printed word, historical glyph, word boundary/spacing, punctuation mark, heading, date, number, paragraph boundary, physical-copy exclusion and independent source witness against the canonical page records. Any confirmed correction must be propagated to the P3 assembly and durable records with old-reading → source-visible-reading provenance.

P5 must pay particular attention to `நாடாளு மன்றத்தில்` / `நாடாளு மன்றமே` and the established historical-glyph watchlist. Do not begin English translation until P5 passes and the Tamil authority is frozen.