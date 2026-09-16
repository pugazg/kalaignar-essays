# P4 Source / Completeness Audit — விடுதலைக் கிளர்ச்சி

## Gate result

**P4 — COMPLETE / PASS.**

This is the publication-level source/completeness gate after P3. It reconciles source identity, all 69 canonical page records, structural boundaries, non-body matter, the introductory unit, the main prose assembly and durable source corrections. It does **not** replace P5, which remains the separate final strict visual word/punctuation fidelity pass.

## Source identity

- source — `TVA_BOK_0064066_விடுதலைக்கிளர்ச்சி.pdf`
- source identifier — `TVA_BOK_0064066`
- bytes — **101,127,153**
- SHA-256 — **`444ff76695154b5ee9d53f4647873fde72659a3d52a76aa833fdc502fb518809`**
- PDF version — **1.4**
- physical scans — **69**
- usable parsed text layer — **none**
- controlling authority — **supplied scan pixels**
- source PDF committed — **No**
- cover title — **`விடுதலைக்கிளர்ச்சி`**
- printed author — **`மு. கருணாநிதி`**
- publisher — **`திராவிடப் பண்ணை`**
- edition — **`இரண்டாம் பதிப்பு—1953`**

## 1. Physical-scan accounting

The live `pages/` directory and page map were reconciled against the 69-scan source.

- expected physical scans — **1–69**
- canonical page records present — **69/69**
- filename scan-number sequence — **0001–0069 contiguous**
- missing scan records — **0**
- duplicate scan numbers — **0**
- page records with status `verified` — **69/69**
- P2 needs-review — **0**
- P2 blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- terminal physical scan **69** — **REPRESENTED / VERIFIED**

Structural coverage:

- scan **1** — front cover — **VERIFIED**
- scan **2** — reverse / physical-copy donation label — **VERIFIED**
- scan **3** — imprint / edition / rights / price / printer — **VERIFIED**
- scans **4–7** — introductory unit `வேங்கையை விரட்டும் படலம்` — **4/4 VERIFIED**
- scans **8–68** — main prose `விடுதலைக் கிளர்ச்சி` — **61/61 VERIFIED**
- scan **69** — publisher catalogue / advertisement — **VERIFIED**

Printed-page behaviour:

- scan **8** main-work opening — no source-visible Arabic folio recorded
- scans **9–68** — visible Arabic folios **8–67**
- scans **5–7** carry source-visible Roman numerals **II–IV** in the printed text layer
- scan **4** has **no visible Roman numeral in the canonical P2 record**

## 2. P1/P2 structural reconciliation

P1's structural ranges agree with P2/P3 after one documentation repair:

| Unit | Physical scans | P2 records | Result |
|---|---:|---:|---|
| front matter | 1–3 | 3/3 | **PASS** |
| `வேங்கையை விரட்டும் படலம்` | 4–7 | 4/4 | **PASS** |
| `விடுதலைக் கிளர்ச்சி` | 8–68 | 61/61 | **PASS** |
| publisher catalogue | 69 | 1/1 | **PASS** |

P2 direct source review established that the introductory unit title is **`வேங்கையை விரட்டும் படலம்`**, not the provisional `வேங்கையை விரட்டும் பாடல்`.

P4 also reconciles the preliminary numbering description: the verified page records show **II–IV on scans 5–7**, while scan 4 does **not** carry a visible Roman numeral. Any older control wording implying a visible I–IV sequence is therefore corrected.

## 3. P3 assembly completeness

P4 rechecked the live assembly inventory against P2 ranges.

| # | Unit | P2 scans | P2 records | P3 assembly | P4 |
|---:|---|---:|---:|---|---|
| 0 | `வேங்கையை விரட்டும் படலம்` | 4–7 | 4/4 | `articles/00-vengaiyai-virattum-padalam.md` | **PASS** |
| 1 | `விடுதலைக் கிளர்ச்சி` | 8–68 | 61/61 | `articles/01-viduthalai-kilarcci.md` | **PASS** |

Assembly totals:

- live reading assemblies — **2/2**
- contributing article/intro page records — **65/65**
- verified boundary-word joins — **14**
- omitted canonical P2 lexical body text — **0**
- unsupported added body text — **0**
- normalization / paraphrase — **0**
- unresolved assembly issues — **0**

P3 closure authorities:

- introductory unit — **`5b0d9fcca4eff38bb7c1a51f98c28cc45ce57b9e`**
- main prose — **`4f1416db060a12d45ab67c069f4976af3dddc1f2`**

## 4. Boundary and non-body isolation

The structural map, canonical page records and P3 ranges agree at the publication-level boundaries:

- scan **3→4** — imprint → introductory unit — **PASS**
- scan **7→8** — introductory unit closes with star → main-work heading `விடுதலைக் கிளர்ச்சி` — **PASS**
- scan **68→69** — main work closes with **`இதுதான் வேறுபாடு. தேவையான துங்கூட!`** + star → publisher catalogue — **PASS**

Non-body isolation:

- scans **1–3** are represented in P2 but excluded from reading assemblies — **PASS**
- scan **69** is represented in P2 but excluded from prose assemblies — **PASS**
- catalogue heading **`கலைஞர் கருணாநிதி எழுதியவை`** remains catalogue matter only — **PASS**

## 5. Physical-copy marks / printed-text separation

P4 confirms the repository separation between printed publication text and later physical-copy evidence:

- scan **1** — later handwriting remains outside the printed cover layer
- scan **2** — donation label remains physical-copy evidence, not publication prose
- ageing / staining / show-through annotations remain outside the printed-text body
- P3 prose contamination from physical-copy marks — **0**

## 6. Durable source readings and propagation

P4 confirms the principal non-regression readings already established by direct P2 source review, including:

- **`வேங்கையை விரட்டும் படலம்`**
- **`இந்தோ சீனாவில்!`**
- **`கோமிண்டாங்`**
- **`மனோரம்மியமான`**
- **`நிகரா குவா`**
- **`பனமா`**
- **`சோப்பும் சீப்பும்`**
- **`மாசேதுங்கினுடைய`**
- source typo-like **`இரண்டாமிரம்`**
- **`மகேஸ்வரனின் அருளால்`**
- **`அரன், அயன், அரி`**
- terminal **`தேவையான துங்கூட!`**

User-confirmed scan-14 reading **`இந்தோ சீனாவில்!`** remains correctly propagated.

### P4 control-document repairs

P4 found **no canonical page-text or P3 body-text defect**.

Documentation repairs required:

1. `P1_SOURCE_STRUCTURE_REVIEW.md` — preliminary numbering wording corrected from visible **I–IV** to source-supported **II–IV on scans 5–7; scan 4 no visible Roman numeral**;
2. publication `README.md` — same numbering correction propagated;
3. `metadata/source.md` — same numbering correction propagated;
4. stale P1 downstream/next-gate wording updated to the live P4/P5 state.

Canonical page-text corrections made during P4 — **0**.  
P3 body-text corrections made during P4 — **0**.

## 7. Historical-type / unresolved state

- historical Tamil type workflow — **applied during P2**
- canonical page records — **69/69 verified**
- historical-glyph unresolved — **0**
- printed-text unresolved — **0**
- guessed readings — **0**
- P4 blockers — **0**

P4 does **not** claim the final strict visual reinspection required by `ESSAY_PROCESSING_GUIDE.md` section 12. P5 must independently reopen every physical scan and verify every visible word, punctuation mark, meaningful spacing, heading, number, folio and page continuation against the canonical record.

## P4 totals

- source coverage — **69/69**
- front matter — **3/3**
- introductory unit — **4/4**
- main prose — **61/61**
- terminal catalogue — **1/1**
- P3 assemblies — **2/2**
- P4 control/documentation repairs — **4**
- canonical body-text repairs — **0**
- unresolved issues — **0**
- blockers — **0**

## Next gate

**P5 — strict visual text-fidelity pass over all 69 physical scans.**
