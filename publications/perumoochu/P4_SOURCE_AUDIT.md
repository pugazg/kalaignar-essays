# P4 Source / Completeness Audit — பெருமூச்சு

## Gate result

**P4 — COMPLETE / PASS.**

This is the publication-level source/completeness gate after P3. It reconciles the controlling source identity, all canonical page records, structural boundaries, title/metadata propagation and all 13 article assemblies. It does **not** replace P5, which remains the separate final strict visual word/punctuation fidelity pass.

## Source identity

- source — `TVA_BOK_0064124_பெருமூச்சு.pdf`
- source identifier — `TVA_BOK_0064124`
- bytes — **122,052,025**
- SHA-256 — **`18947f2deb1ece71b03b59c1e52d9f483a45baa5bf436ab2c3e89a48b5f2dc38`**
- PDF version — **1.4**
- physical scans — **83**
- usable parsed text layer — **none**
- controlling authority — **supplied scan pixels**
- source PDF committed — **No**
- source title form — **`பெருமூச்சு!`**
- printed author — **`மு. கருணாநிதி`**
- publisher — **`இளங்கோ பதிப்பகம், மாயூரம்`**
- edition — **`இரண்டாம் பதிப்பு—'53`**

## 1. Physical-scan accounting

The live `pages/` directory was reconciled against the expected source sequence.

- expected physical scans — **1–83**
- canonical page records present — **83/83**
- filename scan-number sequence — **0001–0083 contiguous**
- missing scan records — **0**
- duplicate scan numbers — **0**
- page records with status `verified` — **83/83**
- P2 needs-review — **0**
- P2 blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- terminal physical scan **83** — **REPRESENTED / VERIFIED**

Structural coverage:

- scans **1–4** — cover / reverse / title / imprint — **4/4 VERIFIED**
- scans **5–6** — publisher preface `மூச்சினிடையே!` — **2/2 VERIFIED**
- scans **7–80** — article body — **74/74 VERIFIED**
- scans **81–83** — advertisements / publisher catalogue — **3/3 VERIFIED**

Printed folio metadata is internally consistent:

- scan **6** — printed page **4**
- scans **6–80** — continuous printed-page sequence **4–78**
- scans **1–5** and **81–83** — no source-visible printed folio recorded

## 2. Article-assignment audit

Canonical P2 article labels and the P3 article ranges agree across all **74** body scans.

| # | Canonical title | P2 scans | P2 records | P3 assembly | P4 |
|---:|---|---:|---:|---|---|
| 1 | `பெருமூச்சு` | 7–10 | 4/4 | `articles/01-perumoochu.md` | **PASS** |
| 2 | `மாளிகை அமைத்திட வாரீர்!` | 11–16 | 6/6 | `articles/02-maaligai-amaiththida-vareer.md` | **PASS** |
| 3 | `மந்திரிகள் குலை நடுக்கம்` | 17–20 | 4/4 | `articles/03-manthirigal-kulai-nadukkam.md` | **PASS** |
| 4 | `வாபஸ் வீரர்கள்!` | 21–23 | 3/3 | `articles/04-vaapas-veerargal.md` | **PASS** |
| 5 | `பொது மக்களுக்குத் தனி எச்சரிக்கை` | 24–36 | 13/13 | `articles/05-podhu-makkalukku-thani-echarikkai.md` | **PASS** |
| 6 | `சிறுவர்கள்` | 37–40 | 4/4 | `articles/06-siruvargal.md` | **PASS** |
| 7 | `“அஹிம்சா விலாசம்”` | 41–48 | 8/8 | `articles/07-ahimsa-vilasam.md` | **PASS** |
| 8 | `திண்டிவனம் தீரர்காள்!` | 49–52 | 4/4 | `articles/08-thindivanam-theerargaal.md` | **PASS** |
| 9 | `சேவல் கூவுகிறது!` | 53–56 | 4/4 | `articles/09-seval-koovugirathu.md` | **PASS** |
| 10 | `மாடோட்டிகள்!` | 57–62 | 6/6 | `articles/10-maadottigal.md` | **PASS** |
| 11 | `தேர்தல் கோவலன்!` | 63–70 | 8/8 | `articles/11-therthal-kovalan.md` | **PASS** |
| 12 | `சிந்தித்துணர்க! சீற்றமுறாதீர்!` | 71–76 | 6/6 | `articles/12-sindhiththunarga-seetramuraadheer.md` | **PASS** |
| 13 | `பூம்! பூம்! பூம்!` | 77–80 | 4/4 | `articles/13-boom-boom-boom.md` | **PASS** |

Across the 13 articles:

- article-body P2 records — **74/74**
- records assigned to exactly one article — **74/74**
- overlapping article ranges — **0**
- missing article-body records — **0**
- live P3 article assemblies — **13/13**
- wrong source ranges — **0**
- wrong current source titles after P4 control repair — **0**

## 3. P3 assembly completeness

P4 rechecked every live article file for its current source filename, article heading, ordered scan markers and ordered page-record provenance.

- article files checked — **13/13**
- `status: "verified"` — **13/13**
- controlling source filename correct — **13/13**
- canonical article heading correct — **13/13**
- ordered scan-marker ranges correct — **13/13**
- ordered page-record provenance complete — **74/74**
- scan markers outside each canonical article range — **0**
- front matter / preface markers imported into article assemblies — **0**
- catalogue markers imported into article assemblies — **0**

P3's exact reconstruction audit remains authoritative for body-text assembly:

- exact P2→P3 reconstruction comparisons — **13/13 PASS**
- omitted canonical P2 body text — **0**
- unsupported added body text — **0**
- normalization / paraphrase — **0**
- unresolved assembly issues — **0**

## 4. Boundary and non-body isolation

The structural map, P2 page metadata and article scan markers agree at every article transition:

- 6→7 — preface→Article 1 — **PASS**
- 10→11 — Article 1→2 — **PASS**
- 16→17 — Article 2→3 — **PASS**
- 20→21 — Article 3→4 — **PASS**
- 23→24 — Article 4→5 — **PASS**
- 36→37 — Article 5→6 — **PASS**
- 40→41 — Article 6→7 — **PASS**
- 48→49 — Article 7→8 — **PASS**
- 52→53 — Article 8→9 — **PASS**
- 56→57 — Article 9→10 — **PASS**
- 62→63 — Article 10→11 — **PASS**
- 70→71 — Article 11→12 — **PASS**
- 76→77 — Article 12→13 — **PASS**
- 80→81 — final article→publisher catalogue — **PASS**

Scans **81–83** remain publication catalogue / advertisement matter only. They are fully represented by P2 records but excluded from the 13 article reading copies.

## 5. Physical-copy marks / printed-text separation

P4 rechecked representative non-print evidence records:

- scan **2** — donation label `பேராசிரியர். தி.வ. மெய்கண்டார் அவர்களின் அன்பளிப்பு` remains under the physical-copy layer; canonical printed layer explicitly records no printed publication text;
- scan **3** — handwriting/stamps crossing the title page remain outside the printed title / sales-rights layer;
- scan **4** — ageing/show-through remains non-text evidence;
- scan **83** — later purple ownership / handwriting marks remain outside the printed catalogue layer.

Physical-copy/audit contamination of P3 article prose — **0**.

## 6. Durable source readings and propagation

P4 confirmed the permanent non-regression headings in the canonical opening page records and P3 assemblies:

- `மந்திரிகள் குலை நடுக்கம்`
- `வாபஸ் வீரர்கள்!`
- `“அஹிம்சா விலாசம்”`
- `திண்டிவனம் தீரர்காள்!`
- `சேவல் கூவுகிறது!`
- `மாடோட்டிகள்!`
- `தேர்தல் கோவலன்!`
- `சிந்தித்துணர்க! சீற்றமுறாதீர்!`

The scans **24–52** physical-boundary repair remains authoritative from:

`ebe8b2146eef22ac203f8014367cb78dea2d4b76`

### P4 control-document repairs

P4 found no canonical body-text defect, but it found three control/documentation propagation gaps and repaired them:

1. `P1_SOURCE_STRUCTURE_REVIEW.md` — Article 7 title now preserves the canonical source quotation marks: `“அஹிம்சா விலாசம்”`;
2. `indexes/page-map.md` — the same Article 7 title punctuation is now propagated into the structural table;
3. `P2_TRANSCRIPTION_PROGRESS.md` — the missing Batch-002 closure summary for scans **24–52** was restored from the current verified records and repair authority.

Canonical page-text corrections made during P4 — **0**.

## 7. Historical-type / unresolved state

- historical Tamil type workflow — **applied during P2**
- canonical page records — **83/83 verified**
- historical-glyph unresolved — **0**
- printed-text unresolved — **0**
- guessed readings — **0**
- P4 blockers — **0**

P4 does **not** claim the final strict visual reinspection required by `ESSAY_PROCESSING_GUIDE.md` section 12. P5 must independently reopen every physical scan and verify every visible word, punctuation mark, meaningful spacing, heading, number, folio and page continuation against the canonical record.

## P4 totals

- source coverage — **83/83**
- front matter — **4/4**
- publisher preface — **2/2**
- article-body coverage — **74/74**
- catalogue / advertisement matter — **3/3**
- article assemblies — **13/13**
- terminal scan — **PASS**
- missing / duplicate scan records — **0 / 0**
- article-range defects — **0**
- assembly provenance defects — **0**
- non-body leakage into article assemblies — **0**
- physical-copy-mark contamination — **0**
- canonical text corrections required by P4 — **0**
- control-document propagation repairs — **3**
- unresolved blockers — **0**

## Final P4 status

**COMPLETE / PASS**

## Downstream P5 status

P4 remains historically **COMPLETE / PASS**. Downstream P5 is now:

- **IN PROGRESS — 78/83 directly rechecked**;
- current P5 authority — `VISUAL_TEXT_FIDELITY_REVIEW.md`;
- scans **79–83** remain pending;
- Tamil archival layer — **NOT YET FROZEN**.

## Exact next activity

**Continue P5 with scans 79–83.** Then propagate any remaining corrections, consolidate the full P5 ledger, re-run final article reconstruction and close P5 only if 83/83 pass.

Do **not** begin English translation until P5 closes and the Tamil archival layer is frozen.

Publication 15 `விடுதலைக் கிளர்ச்சி` remains queued at **P0–P1 COMPLETE / P2 NOT STARTED** unless explicitly redirected.
