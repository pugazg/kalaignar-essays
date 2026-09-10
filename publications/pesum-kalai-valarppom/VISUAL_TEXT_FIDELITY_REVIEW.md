# P5 Visual Text Fidelity Review — பேசும் கலை வளர்ப்போம்

Publication: `publications/pesum-kalai-valarppom/`  
Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`  
Source SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`

## Gate status

**P5 — IN PROGRESS — 20 / 82 physical scans strict-reviewed.**

This is the final direct visual fidelity gate. Source pixels are controlling authority. Every reviewed scan is compared word-by-word and punctuation-by-punctuation against its canonical page record, including visible headings, dates, numbers, quotation marks, meaningful spacing / word boundaries, folios and physical-copy marks.

## Coverage

| Batch | Physical scans | Printed-page span | Result | Corrections | Unresolved |
|---|---:|---|---|---:|---:|
| P5-001-010 | 1–10 | outside pagination + pp.1–8 | **PASS** | **2** | **0** |
| P5-011-020 | 11–20 | pp.9–18 | **PASS** | **3** | **0** |

Contiguous strict-reviewed range: **scans 1–20 / 20 of 82**.

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

## P5-011-020 — direct visual findings

- scan 11 / p.9 — section 1 body, `ரிக்கார்டையே`, `வி. கே. கிருஷ்ண மேனன்`, `“ஹைட் பார்க்”கில்`, folio and scan-10 continuation re-read directly; **PASS**;
- scan 12 / p.10 — section **1→2** source-visible mid-page transition, section numeral `2`, quotations and body text re-read directly; **PASS**;
- scan 13 / p.11 — section 2 body and prior source correction **`வீடுதான்`** re-confirmed directly; **PASS**;
- scan 14 / p.12 — section 2 body, `நாக் குழற`, `‘நட்பு’`, names and page continuation re-read directly; **PASS**;
- scan 15 / p.13 — section 2 quotations, `‘கடவுள்’`, `‘கொல்’லென்று`, `“கட்டபொம்மன்”` and `“தம்பி! நீ எங்கிருந்தாலும் வாழ்க!”` re-read directly; **PASS**;
- scan 16 / p.14 — section **2→3** source-visible mid-page transition, `தமிழகத்துக்`, ellipsis-bearing quotation and section numeral `3` re-read directly; **PASS**;
- scans 17–18 / pp.15–16 — section 3 body, quotation marks, punctuation, word boundaries and folios re-read directly; **PASS**;
- scan 19 / p.17 — section 3 body, two quotations, meaningful spacing and printed `பே—2` gathering mark re-read directly; **3 corrections**;
- scan 20 / p.18 — section 3 body, quotations, names, punctuation and scan-21 lexical continuation re-read directly; **PASS**.

No folio in scans 11–20 is suppressed/inferred; printed folios **9–18** are source-visible.

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

### P5-003 — scan 19 / p.17

Canonical old reading:

`அப்படியிருக்குமேயானால்`

Direct source-visible reading:

`அப்படி இருக்குமேயானால்`

Action:

- corrected the meaningful source-visible word boundary in `pages/0019-section-03-4.md`;
- propagated the same correction to `articles/03-section-03.md`.

### P5-004 — scan 19 / p.17

Canonical old reading:

`எப்படிப் பாலையும்`

Direct source-visible reading:

`எப்படி பாலையும்`

Action:

- removed the non-source `ப்` in `pages/0019-section-03-4.md`;
- propagated the same correction to `articles/03-section-03.md`.

### P5-005 — scan 19 / p.17

Canonical old reading:

`வைத்தால்,எப்படிக் எறும்பானது`

Direct source-visible reading:

`வைத்தால்,எப்படி எறும்பானது`

Action:

- removed the non-source `க்` while preserving the source-visible no-space comma boundary in `pages/0019-section-03-4.md`;
- propagated the same correction to `articles/03-section-03.md`;
- the later phrase `வைத்தால்,எப்படிக் காந்தமானது` remains unchanged because its `க்` is source-visible.

## Boundary / continuity checks

Reviewed source-fragment continuations remain valid:

- scan 7 `கவிஞரின்` → scan 8 `கவிதைச்`;
- scan 8 `பிரச்` → scan 9 `சினைகளைப்`;
- scan 9 `சிந்தித்` → scan 10 `துப் பார்த்து`;
- scan 10 `கொண்` → scan 11 `டிருப்பார்.`;
- scan 13 `உயர்நிலைப்பள்ளியில்` → scan 14 `நடைபெற்ற`;
- scan 14 `வீட்டில்` → scan 15 `உள்ள`;
- scan 15 `ஒலிபெருக்கியின்` → scan 16 `முன்னால்`;
- scan 16 `சொற்களை` → scan 17 `அடிப்படையாகக்`;
- scan 20 `அவர் உதடுகள்` → scan 21 `உச்சரிக்கிற வார்த்தைகளுக்கும்` — scan 21 was inspected only as boundary evidence and is **not** counted as P5-reviewed yet.

The source-visible mid-page transitions at scans **12 (1→2)** and **16 (2→3)** remain correctly divided in the reading assemblies.

## Current P5 totals

- physical scans in source: **82**;
- strict-reviewed: **20 / 82**;
- corrections found: **5**;
- corrections propagated: **5 / 5**;
- unresolved fidelity discrepancies in reviewed range: **0**;
- next strict-review batch: **scans 21–30 / printed pp.19–28**.

P5 remains open until **82 / 82** scans are directly strict-reviewed and every source-supported correction is propagated with **0 unresolved fidelity discrepancies**.