# P4 Source Audit / Completeness Review — ஆறுமாதக் கடுங்காவல்

## Gate result

**P4 — COMPLETE / PASS.**

This gate audits publication-level completeness and consistency after P3. It does **not** replace P5, which remains the formal final strict visual word/punctuation fidelity gate.

## Source identity

- source — `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`
- bytes — **282020019**
- SHA-256 — **`8d4b227547144dd16a78d3f7e22edc3d955d754788ba96317c0c6ddd68d0ca69`**
- physical scans — **224**
- source PDF committed — **No**

## 1. Physical-scan accounting

Repository page-record audit:

- numbered page records present — **224**
- expected physical scans — **1–224**
- missing scan records — **0**
- duplicate scan records — **0**
- P2 final status — **224/224 verified**
- needs-review — **0**
- guessed readings — **0**

Structural coverage is complete:

- scans **1–9** — front matter / physical-copy layers;
- scans **10–65** — **முரசு** body;
- scan **66** — illustrated **களம்** title-transition with station-board `கல்லக்குடி`;
- scan **67** — blank/reverse;
- scans **68–106** — **களம்** body;
- scan **107** — blank/reverse article separator;
- scan **108** — illustrated **சிறை** intertitle;
- scan **109** — blank/reverse;
- scans **110–223** — **சிறை** body;
- scan **224** — back cover / `திராவிடப்பண்ணை` publisher device.

Known blank/reverse scans remain **5, 9, 67, 107, 109**.

## 2. Three-article assembly audit

### 01 — முரசு

- assembly — `articles/01-murasu.md`
- scan markers — **56**
- expected range — **10–65**
- missing markers — **0**
- duplicate markers — **0**
- closing boundary — scan **65**, ending with the three `அதிர்ந்தது முரசு` lines and printed star.

### 02 — களம்

- assembly — `articles/02-kalam.md`
- structural scan markers — **41**
- expected markers — scan **66**, scan **67**, scans **68–106**
- missing markers — **0**
- duplicate markers — **0**
- canonical scan-66 title — **`களம்`**, not `தடை`;
- station-board text — **`கல்லக்குடி`**;
- scan 68 repeats the heading **`களம்`** at body start;
- all `களம்` page-record filenames use the `*-kalam.md` pattern; stale `*-murasu.md` filenames in this range — **0**.

### 03 — சிறை

- assembly — `articles/03-sirai.md`
- structural scan markers — **116**
- expected markers — scan **108**, scan **109**, scans **110–223**
- missing markers — **0**
- duplicate markers — **0**
- final text-bearing scan — **223**.

Across all three assemblies:

- duplicate scan markers between article files — **0**;
- omitted expected article-structure markers — **0**;
- front matter, scan-107 separator, and back cover are deliberately outside article reading bodies as structural publication material.

## 3. Boundary / metadata consistency

Boundary page records were rechecked at P4:

- scan 8 — front-matter `முரசு` illustration;
- scan 9 — blank/reverse;
- scan 65 — `article: "murasu"`, verified closing page;
- scan 66 — `article: "kalam"`, `section: "kalam-intertitle"`, canonical body `களம் / கல்லக்குடி`;
- scan 67 — blank/reverse;
- scan 68 — `article: "kalam"`, body heading `களம்`;
- scan 106 — `article: "kalam"`, final `களம்` body page;
- scan 107 — blank/reverse;
- scan 108 — `article: "sirai"` illustrated intertitle;
- scan 109 — blank/reverse;
- scan 110 — `article: "sirai"` body opening;
- scan 223 — final verified `சிறை` text page;
- scan 224 — verified back cover.

The page map and P3 review use the same **முரசு / களம் / சிறை** structure.

## 4. Resolved readings

The two former source-obscured P2 holds remain resolved in canonical page text and article assemblies:

- scan **18** — **`ஆகிவிடக்கூடிய`**
- scan **198** — **`அடைந்தார்`**

Historical audit prose may still mention the earlier `[…]` placeholders as before→after provenance. Those historical notes are **not** current canonical holds.

## 5. Historical-glyph / P2R state

- P2R — **224/224 COMPLETE**
- cumulative historical-glyph correction events — **20**
- current P2 needs-review — **0**
- current guessed readings — **0**

Older batch sections in README/audit/handover preserve then-current intermediate counts as provenance. They do not override the final gate state recorded here and in the current summaries.

## P4 blockers

**0**

## Exact next activity

**P5 — final strict visual text-fidelity pass.**

P5 must follow the repository guide: inspect every physical scan again, verify every visible word / punctuation / meaningful spacing / heading / number / page continuation against the canonical record, propagate any correction to article assemblies and controls, and produce the final publication-level visual fidelity report.

Do **not** begin English until P5 closes and Tamil is frozen.
