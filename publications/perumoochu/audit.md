# Audit — பெருமூச்சு

## Source intake

- source identity — **PASS**
- physical scans — **83 / 83**
- file size — **122,052,025 bytes**
- SHA-256 — **`18947f2deb1ece71b03b59c1e52d9f483a45baa5bf436ab2c3e89a48b5f2dc38`**
- PDF version — **1.4**
- source pixels — **controlling authority**
- source PDF committed — **No**
- usable parsed text layer — **none**

## Classification

**ESSAYS / ARTICLES — PASS**

The publication contains a publisher preface followed by **13** distinct political prose article units.

## P1 structure

- scans 1–4 — cover / title / imprint / physical-copy evidence
- scans 5–6 — `மூச்சினிடையே!` publisher preface
- scans 7–80 — **13 article units / 74 body scans**
- scans 81–83 — advertisements / catalogue matter
- separate printed contents page — **none**
- article-boundary checks — **PASS**
- terminal physical scan — **83 VERIFIED**
- P1 blockers — **0**

## Tamil workflow

- historical Tamil typeforms — **present**
- historical-glyph guide — **mandatory**
- P2 — **COMPLETE / PASS — 83/83 VERIFIED**
- P3 — **COMPLETE / PASS — 13/13**
- P4 — **COMPLETE / PASS**
- P5 — **NOT STARTED**
- English — **BLOCKED until Tamil P5 / frozen**

## P2 final audit

**COMPLETE / PASS — 83/83**

- canonical physical-scan records — **83/83**
- source scans covered — **83/83**
- missing records — **0**
- duplicate records — **0**
- verified — **83**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- physical-copy marks separated from printed text — **PASS**
- source PDF terminal scan 83 — **VERIFIED**
- baseline `perumoochu.md` — **non-authoritative alignment aid only**
- rendered source pixels — **controlling authority**

### Article/body coverage

1. scans 7–10 — **`பெருமூச்சு`**
2. scans 11–16 — **`மாளிகை அமைத்திட வாரீர்!`**
3. scans 17–20 — **`மந்திரிகள் குலை நடுக்கம்`**
4. scans 21–23 — **`வாபஸ் வீரர்கள்!`**
5. scans 24–36 — **`பொது மக்களுக்குத் தனி எச்சரிக்கை`**
6. scans 37–40 — **`சிறுவர்கள்`**
7. scans 41–48 — **`“அஹிம்சா விலாசம்”`**
8. scans 49–52 — **`திண்டிவனம் தீரர்காள்!`**
9. scans 53–56 — **`சேவல் கூவுகிறது!`**
10. scans 57–62 — **`மாடோட்டிகள்!`**
11. scans 63–70 — **`தேர்தல் கோவலன்!`**
12. scans 71–76 — **`சிந்தித்துணர்க! சீற்றமுறாதீர்!`**
13. scans 77–80 — **`பூம்! பூம்! பூம்!`**

### Durable fidelity findings

- historical **`லை`** in **`மந்திரிகள் குலை நடுக்கம்`** is authoritative;
- retired P1 title readings have been replaced by the source-visible P2 readings listed above;
- scans **24–52** were rebuilt to exact physical scan boundaries after heuristic segmentation was detected during closure review;
- repair authority — **`ebe8b2146eef22ac203f8014367cb78dea2d4b76`**;
- scans 81–83 catalogue text was read directly from source pixels rather than copying baseline price-column noise.

## P2 gate result

**PASS — P3 completed without reopening P2.**

## P3 final audit

**COMPLETE / PASS — 13/13 article assemblies / 74/74 body records**

- canonical P2 page-record coverage — **74/74**
- exact reconstruction comparison — **13/13 PASS**
- omitted canonical P2 body text — **0**
- unsupported added body text — **0**
- normalization / paraphrase events — **0**
- unresolved assembly issues — **0**
- page-boundary comments / provenance — **present**
- scans 24–52 repair authority preserved — **`ebe8b2146eef22ac203f8014367cb78dea2d4b76`**
- progress authority — `P3_PROGRESS.md`

## P3 gate result

**PASS — P4 may begin.**

## P4 source/completeness audit

**COMPLETE / PASS**

- source coverage — **83/83**
- page-record sequence — **1–83 contiguous**
- missing / duplicate records — **0 / 0**
- article-body coverage — **74/74**
- article assemblies — **13/13**
- scan-marker / provenance defects — **0**
- front matter / preface / catalogue isolation — **PASS**
- physical-copy-mark contamination — **0**
- canonical text corrections required by P4 — **0**
- control-document propagation repairs — **3**
- unresolved blockers — **0**
- authority — `P4_SOURCE_AUDIT.md`

### P4 propagation repairs

- canonical Article-7 title `“அஹிம்சா விலாசம்”` propagated into `P1_SOURCE_STRUCTURE_REVIEW.md`;
- the same quoted title propagated into `indexes/page-map.md`;
- missing P2 Batch-002 closure summary for scans 24–52 restored in `P2_TRANSCRIPTION_PROGRESS.md`.

## P4 gate result

**PASS — P5 may begin.**

## Exact next activity

**P5 — final strict visual text-fidelity pass over all 83 physical scans.**

Do not begin English until P5 closes and Tamil is frozen.
