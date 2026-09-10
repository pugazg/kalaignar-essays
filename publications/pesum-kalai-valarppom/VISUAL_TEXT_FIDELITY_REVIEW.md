# P5 Visual Text Fidelity Review — பேசும் கலை வளர்ப்போம்

Publication: `publications/pesum-kalai-valarppom/`  
Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`  
Source SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`

## Gate status

**P5 — IN PROGRESS — 10 / 82 physical scans strict-reviewed.**

This is the final direct visual fidelity gate. Source pixels are controlling authority. Every reviewed scan is compared word-by-word and punctuation-by-punctuation against its canonical page record, including visible headings, dates, numbers, quotation marks, meaningful spacing / word boundaries, folios and physical-copy marks.

## Coverage

| Batch | Physical scans | Printed-page span | Result | Corrections | Unresolved |
|---|---:|---|---|---:|---:|
| P5-001-010 | 1–10 | outside pagination + pp.1–8 | **PASS** | **2** | **0** |

Contiguous strict-reviewed range: **scans 1–10 / 10 of 82**.

## P5-001-010 — direct visual findings

- scan 1 — front cover: printed title / author and later red physical-copy mark remain correctly separated; **PASS**;
- scan 2 — near-blank inside cover with partial library/copy stamp only; no printed publication text; **PASS**;
- scan 3 / inferred p.1 — title-page form `பேசும்கலை வளர்ப்போம்`, author/status, publisher/address and later handwriting/stamp distinctions rechecked; **PASS**;
- scan 4 / inferred p.2 — edition/imprint block re-read directly; **1 correction**;
- scan 5 / inferred p.3 — later full-page handwriting only, printed publication text **0**; **PASS**;
- scan 6 / inferred p.4 — `பதிப்புரை`, names, quotations, publisher statement and source-visible date `15—7—81` re-read directly; **PASS**;
- scan 7 / inferred p.5 — section heading/number, body text and quotations re-read directly; **1 correction**;
- scans 8–10 / pp.6–8 — section 1 body, folios, quotations, Kural, punctuation and page-fragment continuations re-read directly; **PASS**.

Suppressed/inferred folios in this reviewed range remain correctly non-visible on scans **3,4,5,6,7**. Scans 1–2 remain outside printed pagination.

## Correction ledger

### P5-001 — scan 4 / inferred p.2

Canonical old reading:

`By : Kalaignar M. Karunanidhi`

Direct source-visible reading:

`By : Kalaingnar M. Karunanidhi`

Action:

- corrected `pages/0004-imprint.md` to preserve the source-visible English spelling **`Kalaingnar`**;
- no numbered-section assembly is affected because scan 4 is front matter.

### P5-002 — scan 7 / inferred p.5

Canonical old opening punctuation:

`‘வெண்ணிலாவும் ...`

Direct source-visible opening punctuation:

`“வெண்ணிலாவும் ...`

Action:

- corrected `pages/0007-section-01-1.md` from a single opening quotation mark to the source-visible double opening quotation mark;
- propagated the same correction to `articles/01-section-01.md`.

## Boundary / continuity checks in this batch

The existing source-fragment continuations remain valid after strict review:

- scan 7 `கவிஞரின்` → scan 8 `கவிதைச்`;
- scan 8 `பிரச்` → scan 9 `சினைகளைப்`;
- scan 9 `சிந்தித்` → scan 10 `துப் பார்த்து`;
- scan 10 `கொண்` → scan 11 `டிருப்பார்.` — scan 11 is boundary evidence only for this batch and is not counted as P5-reviewed yet.

## Current P5 totals

- physical scans in source: **82**;
- strict-reviewed: **10 / 82**;
- corrections found: **2**;
- corrections propagated: **2 / 2**;
- unresolved fidelity discrepancies in reviewed range: **0**;
- next strict-review batch: **scans 11–20 / printed pp.9–18**.

P5 remains open until **82 / 82** scans are directly strict-reviewed and every source-supported correction is propagated with **0 unresolved fidelity discrepancies**.