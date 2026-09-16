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
- P5 — **COMPLETE / PASS — 83/83 STRICT-REVIEWED**
- English — **E0 COMPLETE / PASS; Articles 1–11 T0–T5 VERIFIED; Article 12 T0 NEXT**

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

## P5 strict visual-text-fidelity audit — final state

**COMPLETE / PASS — 83/83 physical scans directly rechecked.**

- canonical page records — **83/83 VERIFIED**
- article assemblies — **13/13 STRICT-REVIEWED**
- article body records — **74/74**
- unresolved P5 fidelity discrepancies — **0**
- unresolved historical-glyph ambiguities — **0**
- needs-review / blocked / guessed — **0 / 0 / 0**
- printed gathering/signature marks `[2]`–`[5]` — recorded as page furniture
- physical-copy contamination — **0**
- scan 83 source heading — **`ஊடுருவி தீட்டியவை:-`** — user-confirmed / non-regression
- complete correction ledger and frozen article blobs — `VISUAL_TEXT_FIDELITY_REVIEW.md`

## P5 gate result

**PASS — Tamil archival layer COMPLETE / STRICT-REVIEWED / FROZEN.**

## English audit checkpoint — Articles 1–11

- E0 — **COMPLETE / PASS**
- T0 — **11/13 PASS**
- T1 — **11/13 COMPLETE**
- T2 — **11/13 PASS**
- T3 — **11/13 PASS**
- T4 — **11/13 PASS**
- T5 — **11/13 VERIFIED**
- ordered source comments in verified English articles — **64/64 PASS**
- untranslated Tamil body leakage — **0**
- omitted Tamil clauses after bilingual review — **0**
- added substantive English claims after bilingual review — **0**
- Tamil source changes — **0**
- blockers — **0**

Verified English blobs:

1. `8a441b0c4d33aacd2e61795800de2f95c4804e81` — **A Deep Sigh**
2. `ef0be10af34519b868634de64fc67bfde53bc5fb` — **Come, Let Us Build the Mansion!**
3. `3d0e2718db290159e717db23890611f461af1149` — **Ministers Tremble in Fear**
4. `47510c75833b1abd6990871ebc45c9e9eb8ba1db` — **Heroes of Retreat!**
5. `637fd7fb72126b4b677846839191459616971d60` — **A Special Warning to the Public**
6. `b2694657339a42c84d932e67ee63684a588245d2` — **Youngsters**
7. `9a55d55bef9e68c893c42546ac7dac1bb84ffb18` — **“Ahimsa Vilasam”**
8. `557927643d1df347e2f8c03971bd501439973863` — **O Heroes of Tindivanam!**
9. `b4e203789117dba4de9c08f2bc25766e807e2160` — **The Rooster Crows!**
10. `3f96803c1d0b08d287da2e961298c18e4491ea3f` — **Cattle-Drivers!**
11. `470e034d7e2bd977dc6e70d61159814090f4110b` — **Election Kovalan!**

Authorities:

- `TRANSLATION_PLAN.md`
- `translations/en/README.md`
- `translations/en/SOURCE_MAP.md`
- `translations/en/LEXICON.md`
- `translations/en/TRANSLATION_REVIEW.md`

## Exact next activity

**Article 12 `சிந்தித்துணர்க! சீற்றமுறாதீர்!` — T0 source prerequisite.**

Require exact live-main Tamil blob **`122f5320d683c35267e23b5a667bfd27100fdd3e`** before creating Article 12 English body text.
