# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **COMPLETE / PASS** | **82/82 VERIFIED**; scans 1–82 contiguous |
| P3 assemblies | **COMPLETE / PASS** | **19/19 source-numbered assemblies**; main work scans 7–82 / pp.5–80 represented |
| P4 source/completeness audit | **COMPLETE / PASS** | **82/82 page records + 19/19 assemblies reconciled; discrepancies 0** |
| P5 strict visual fidelity | **NOT STARTED / NEXT** | — |
| English E0–E7 | **NOT STARTED** | blocked until Tamil freeze |

## Source / P1 durable facts

Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`, SHA-256 `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`, 105,698,402 bytes, **82 image-only scans**; source PDF is not committed.

- scan 1 cover: `பேசும் கலை வளர்ப்போம்`;
- scan 3 title page: `பேசும்கலை வளர்ப்போம்`;
- scans 1–2 outside pagination;
- scans 3–82 = printed pp.1–80, `printed page = scan - 2`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- section starts/ends: **19/19 / 19/19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- no printed contents page; no separate back-cover scan;
- structural blockers: **0**.

## P2 — COMPLETE / PASS

All **82 physical scans** have canonical page records and were directly compared with source pixels.

- canonical records / direct verification: **82 / 82**;
- contiguous verified range: scans **1–82**;
- printed coverage: **pp.1–80 COMPLETE**;
- final main-work/source boundary: scan **82 / p.80**;
- unresolved printed-text readings: **0**;
- unresolved source/structure distinctions: **0**;
- assemblies created during P2: **0**;
- silent normalization: **0**.

### Final scans 71–82

- scans **71–74 / pp.69–72** — section 17; scan **74 closes section 17 at page end**;
- scan **75 / inferred p.73** — source-visible section `18` opens at page top; folio **suppressed / inferred**;
- scans **76–78 / pp.74–76** — section 18;
- scan **79 / p.77** — section **18→19** mid-page transition preserved;
- scans **80–82 / pp.78–80** — section 19;
- scan **82** — section 19 and source end.

Direct continuation checks include scan 71 `கலந்து` → scan 72 `கொண்டிருக்கிறேன்.` and scan 81 `முழுவாழ்வு வாழ` → scan 82 `விடாமல் நம்மிடமிருந்து பறித்துக்கொண்டு விட்டது.`

Final source-sensitive readings retained include `ஷம்சுதீன்`, `நாலுகால்`, `ஒரே வரியிலே`, `ஒரு வரிக்கு மேல்`, `(Mannerism)`, `மேனரிசம்`, `தவிர்க்கவொண்ணாத`, `சொல்மாரிபொழிவது`, `கி. ஆ. பெ. விசுவநாதம்`, `காயிதே மில்லத்`, `தேனினுமினிய`, `நாற்பத்தி ஆறு`, `1962-ல்`, `நாஞ்சில் கி. மனோகரன்`, `“வாலிபப் பெரியார்”`, `எ.வி.பி. ஆசைத்தம்பி`, and `என். வி. நடராசனார்`.

## P3 — COMPLETE / PASS

The numbered-section Tamil reading layer is complete under `articles/`.

- expected assemblies: **19**;
- live assemblies: **19** — `01-section-01.md` through `19-section-19.md`;
- missing / unexpected extra assemblies: **0 / 0**;
- numbering: **01–19 contiguous**;
- main-work coverage: scans **7–82 / pp.5–80**;
- source-numbered section coverage: **1–19 COMPLETE**;
- unexplained boundary gaps / overlaps: **0 / 0**;
- intentional shared transition scans: **12** — `12,16,22,27,31,34,38,51,55,67,70,79`;
- unresolved assembly body-text blocks: **0**;
- assembly normalization: **0**.

Shared transition scans are split only at the source-visible numbered-section boundary; their text is not duplicated between adjacent assemblies. Page-boundary provenance comments are retained, including the final scan-81→82 continuation inside section 19.

Full P3 coverage and span validation: [`P3_ASSEMBLY_AUDIT.md`](P3_ASSEMBLY_AUDIT.md).

## P4 — COMPLETE / PASS

The source/completeness reconciliation was performed against the live source record, canonical page-record inventory, structural indexes and all 19 P3 assemblies.

- controlling source identity/checksum/size/scan count: **reconciled / PASS**;
- distinct title witnesses: **preserved / PASS**;
- canonical physical-scan records: **82 / 82**, scan numbers `0001–0082` contiguous;
- missing / duplicate scan records: **0 / 0**;
- pagination rule and suppressed/inferred folio set: **reconciled / PASS**;
- front-matter printed text vs handwriting/stamps/physical-copy marks: **separated / PASS**;
- live numbered-section assemblies: **19 / 19 source-complete**;
- section/assembly map drift: **0**;
- shared transition duplication/omission defects: **0**;
- scan 13 `வீடுதான்` propagation: **PASS**;
- scan 74 `வரியிலே` / `வரிக்கு` propagation: **PASS**;
- new P4 text corrections: **0**;
- unresolved P4 discrepancies / blockers: **0 / 0**.

Dedicated record: [`P4_SOURCE_COMPLETENESS_REVIEW.md`](P4_SOURCE_COMPLETENESS_REVIEW.md).

P4 is a reconciliation/completeness gate and does **not** substitute for the separate P5 direct strict visual word/punctuation pass.

## Corrections / normalization ledger

- documented P2 correction: scan 13 draft `வீட்டான்` → source-visible `வீடுதான்`;
- final-batch direct re-read correction: scan 74 draft `வாரியிலே` / `வாரிக்கு` → source-visible **`வரியிலே` / `வரிக்கு`**;
- P2 silent normalization: **0**;
- P3 silent normalization: **0**;
- P4 new corrections: **0**;
- unresolved Tamil/source readings entering P5: **0**.

## Exact next activity

**P5 — strict visual word/punctuation fidelity pass over all 82 physical scans.** Re-inspect every physical source scan directly against its canonical page record — cover/front matter, body, suppressed/inferred folio distinctions, words, spacing, punctuation, quotations, dates, numbers, headings and continuations. Record every old reading → source-visible correction and propagate any correction to dependent assemblies/indexes/trackers. Create `VISUAL_TEXT_FIDELITY_REVIEW.md` (or guide-equivalent report) before closing P5. English remains blocked until Tamil P5 freeze.