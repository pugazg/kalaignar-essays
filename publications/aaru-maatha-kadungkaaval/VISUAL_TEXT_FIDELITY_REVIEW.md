# P5 Final Strict Visual Text-Fidelity Review — ஆறுமாதக் கடுங்காவல்

## Gate purpose

This is the repository-mandated final independent **word-by-word / punctuation-by-punctuation visual fidelity pass** after P4.

Controlling source: `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

Rules:

- inspect every physical scan directly from source pixels;
- verify every visible word, meaningful spacing, punctuation mark, quotation mark, heading, date, number and page continuation;
- explicitly check historical Tamil character identity;
- no OCR, web copies, alternate editions, contextual completion, grammar-based normalization or silent correction;
- propagate any canonical correction to article assemblies and controls.

## Progress

- physical scans — **224**
- P5 checked — **30/224**
- completed range — **1–30**
- next range — **31–45**
- current needs-review — **0**
- current blocked — **0**
- guessed readings — **0**
- new P5 canonical corrections — **0**
- new P5 historical-glyph correction events — **0**
- pre-P5 cumulative historical-glyph correction-event count — **20**

## Batch P5-01 — scans 1–15

Result: **15/15 PASS / no canonical correction**.

| Scan | Role | P5 result |
|---:|---|---|
| 1 | physical-copy front layer | PASS — no publication text |
| 2 | title page | PASS |
| 3 | imprint | PASS |
| 4 | publisher note | PASS |
| 5 | blank/reverse | PASS |
| 6 | dedication 1 | PASS |
| 7 | dedication 2 | PASS |
| 8 | illustrated `முரசு` front matter | PASS |
| 9 | blank/reverse | PASS |
| 10 | `முரசு` body opening | PASS |
| 11 | `முரசு` body | PASS |
| 12 | `முரசு` body | PASS |
| 13 | `முரசு` body | PASS |
| 14 | `முரசு` body | PASS |
| 15 | `முரசு` body | PASS |

Notable reconfirmations:

- title-page wording and punctuation remain exactly as canonical;
- imprint long-dash price punctuation remains `விலை ரூ. 2—0—0`;
- publisher-note lexical line-wrap handling remains source-supported;
- dedication star and page-boundary continuation remain source-supported;
- scan 13 historical `றா` identity in `பொற்சுரங்கமென்றாளோ` remains correct;
- scan 14 → 15 lexical continuation `தொட்டுவிட்` + `டது.` remains a physical page-boundary continuation and is not rewritten inside either page record;
- scan 15 terminal `அத்` remains preserved exactly.

No P5 correction was required in scans 1–15.

## Batch P5-02 — scans 16–30

Result: **15/15 PASS / no canonical correction**.

| Scan | P5 result | Key reconfirmation |
|---:|---|---|
| 16 | PASS | duplicate physical witness of printed folio 13; source short-hyphen punctuation retained |
| 17 | PASS | duplicate physical witness of printed folio 14; source spacing / punctuation retained |
| 18 | PASS under user-confirmed obscured-reading authority | all visible source print matches canonical; physically hidden cluster remains unreadable from pixels, while the user-confirmed canonical reading remains **`ஆகிவிடக்கூடிய`** |
| 19 | PASS | full text / punctuation / page-boundary wording reconfirmed |
| 20 | PASS | `முதல் நாள் :`, dates, punctuation and ending fragment reconfirmed |
| 21 | PASS | full word / punctuation / spacing review reconfirmed |
| 22 | PASS | `அடுத்த நாள் :`, body text and terminal `பெற்ற` reconfirmed |
| 23 | PASS | full text and terminal open quotation reconfirmed |
| 24 | PASS | full text and terminal open quotation reconfirmed |
| 25 | PASS | `மூன்றாம் நாள் :`, numerals and terminal fragment reconfirmed |
| 26 | PASS | full word / punctuation / spacing / boundary review reconfirmed |
| 27 | PASS | unusual source forms and punctuation reconfirmed without normalization |
| 28 | PASS | full text and exact terminal fragment `மறந்` reconfirmed |
| 29 | PASS | scan-28 `மறந்` + scan-29 `திடக்` physical continuation reconfirmed |
| 30 | PASS | full text / punctuation / line-wrap joins reconfirmed; source period in `என்னையும். உங்களையும்` retained |

Historical-family verification for this batch reconfirmed the source identities already established in P2R, including representative forms `அண்ணாவின்`, `பண்ணை`, `தலையணைகூட`, `கண்ணாடி`, `மாலை`, `இளைஞர்கள்`, `மூன்றாம்`, `காளை`, `வளைந்து`, `வலை`, `அணைக்க` / `அணைக்கும்`, and `அலைந்து`.

Batch P5-02 totals:

- scans checked — **15**
- canonical corrections — **0**
- new historical-glyph correction events — **0**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- P5 cumulative progress — **30/224**

Important source anomaly remains preserved exactly:

- scans **16–17** independently repeat printed folios **13–14**;
- scan **18** resumes printed folio **15**;
- no physical scan was deduplicated.

Scan 18 note: the source obstruction still prevents direct pixel recovery of the hidden cluster. P5 therefore does **not** claim pixel recovery for those hidden letters; the canonical reading **`ஆகிவிடக்கூடிய`** remains explicitly user-confirmed and is not a guessed completion.

## Exact next activity

**P5 Batch P5-03 — physical scans 31–45.**

Continue the same direct-source, no-OCR, no-web, no-normalization protocol. Stop after scan 45.
