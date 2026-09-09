# P4 Visual Text-Fidelity Review — மீசை முளைத்த வயதில்

Publication: `publications/meesai-mulaiththa-vayathil/`  
Controlling source: `TVA_BOK_0065746_மீசை_முளைத்த_வயதில்.pdf`  
Source SHA-256: `9054aa8ed82c68050b82ffe57d772c32fdcad0605f72d7983de490162669527d`  
Physical scans: **146**

## Gate state

**P4 — IN PROGRESS — 20 / 146 physical scans strict-reviewed**

Contiguous strict-reviewed range: **scans 1–20**.  
Next strict-review batch: **scans 21–30**.

P4 follows `ESSAY_PROCESSING_GUIDE.md` section 12: every physical scan is re-inspected directly, word-by-word and punctuation-by-punctuation, against the canonical page record. Source pixels remain authority; context, OCR and secondary editions are not authority.

## Batch P4-001-010

**RESULT: PASS after corrective strict review — 10 / 10 scans; 2 corrections; 0 unresolved fidelity discrepancies.**

| Scan | Section | Result | P4 action |
|---:|---|---|---|
| 1 | front cover | PASS | title, author, printed design and later accession-label separation rechecked |
| 2 | title page | PASS | title, author, publisher, portrait/design and library-stamp separation rechecked |
| 3 | imprint | PASS | edition/price/imprint witnesses and stamp-obscured region rechecked; obscured characters remain explicitly unreconstructed |
| 4 | `என்னுரை` 1/3 | PASS | prose, verse, punctuation and continuation rechecked |
| 5 | `என்னுரை` 2/3 | PASS after correction | `கூறிய` → source-visible `கூரிய` |
| 6 | `என்னுரை` 3/3 | PASS | prose, punctuation, source quotation/continuation and facsimile date rechecked |
| 7 | `முன்னுரை` 1/10 | PASS | heading, prose, punctuation and paragraph boundaries rechecked |
| 8 | `முன்னுரை` 2/10 | PASS after correction | `மூத்தோர்` → source-visible `முதியோர்` |
| 9 | `முன்னுரை` 3/10 | PASS | verse/prose wording, punctuation and continuation rechecked |
| 10 | `முன்னுரை` 4/10 | PASS | quoted verse, bullet, punctuation and page-end continuation rechecked |

### Correction provenance

1. **Scan 5 — `என்னுரை`**  
   Old canonical reading: `கூறிய வேல் வாள்`  
   Source-visible reading: **`கூரிய வேல் வாள்`**  
   Action: corrected `pages/0005-ennurai-2.md`.  
   Dependency impact: front matter only; no P3 main-work article assembly is affected.

2. **Scan 8 — `முன்னுரை`**  
   Old canonical reading: `அறிவுரையே கவிதை என்றால் மூத்தோர் முதுமொழி போதும்.`  
   Source-visible reading: **`அறிவுரையே கவிதை என்றால் முதியோர் முதுமொழி போதும்.`**  
   Action: corrected `pages/0008-munnurai-2.md`.  
   Dependency impact: front matter only; no P3 main-work article assembly is affected.

Both corrections were determined from the controlling 2006 scan pixels. Neither was inferred from language/context or imported from another witness.

### Scan-3 obscuration status

A later physical-copy library stamp obscures part of the publisher-address line on scan 3. The canonical page record already preserves this as an explicitly obscured source region and does not reconstruct hidden characters. P4 therefore records **no fidelity discrepancy** for that region; the physical limitation remains documented rather than guessed through.

## Batch P4-011-020

**RESULT: PASS — 10 / 10 scans; 0 new corrections; 0 unresolved fidelity discrepancies.**

| Scan | Section | Result | P4 action |
|---:|---|---|---|
| 11 | `முன்னுரை` 5/10 | PASS | prose, quoted verse, punctuation and page-end continuation rechecked |
| 12 | `முன்னுரை` 6/10 | PASS | prose, hyphen-separated sequence, spacing and paragraph boundaries rechecked |
| 13 | `முன்னுரை` 7/10 | PASS | prose, printed bullet, quoted verse and punctuation rechecked |
| 14 | `முன்னுரை` 8/10 | PASS | all four quoted passages, ellipses and prose wording rechecked |
| 15 | `முன்னுரை` 9/10 | PASS | prose and source-visible grammatical form `நாடக ஆசிரியராகவு` rechecked and retained |
| 16 | `முன்னுரை` 10/10 | PASS | Nannūl quotation, split source forms, punctuation, closing salutation and signature facsimile rechecked |
| 17 | blank / show-through | PASS | no printed text; reverse-side show-through remains correctly excluded from transcription |
| 18 | `பிறையே` 1/3 / p.17 | PASS | opening title, illustration, prose, punctuation and printed folio rechecked |
| 19 | `பிறையே` 2/3 / p.18 | PASS | running head, prose, repeated `நானும் கைதி! / நீயும் கைதி!`, punctuation and continuation rechecked |
| 20 | `பிறையே` 3/3 / p.19 | PASS | running head, semicolon/hyphen punctuation, final repeated lines and bullet `●` rechecked |

### Batch findings

- No canonical wording, spacing or punctuation correction was required on scans **11–20**.
- `முன்னுரை` closes cleanly on scan **16**; scan **17** remains a genuine blank/show-through physical page.
- Unit 1 `பிறையே` remains scans **18–20 / printed pp.17–19** with its P3 assembly unchanged.
- P3 propagation required for this batch: **0 files**.

## Progress totals

- physical scans strict-reviewed: **20 / 146**;
- contiguous reviewed range: **1–20**;
- P4 corrections found: **2**;
- P4 corrections propagated to canonical page records: **2 / 2**;
- affected P3 article assemblies requiring propagation so far: **0**;
- unresolved fidelity discrepancies: **0**;
- blocked / needs-review scans in reviewed range: **0**;
- P4 gate: **OPEN / IN PROGRESS**.

## Non-regression

P0–P3 remain complete. The strict pass does not reopen frozen mappings or assemblies except where direct controlling-source evidence proves a defect. Permanent source-title readings `அகப்பை சித்தர்`, `தளிர்`, and `மயிலிறகு` remain unchanged.

## Exact next activity

**P4 scans 21–30.** Re-inspect all ten physical scans directly against their canonical records, record every old reading → source-visible reading correction, propagate any affected text into dependent records, and then advance this report only if the whole batch is reconciled.

Do not mark P4 complete before **146 / 146** physical scans are strict-reviewed. English remains **BLOCKED until Tamil P5 freeze**.
