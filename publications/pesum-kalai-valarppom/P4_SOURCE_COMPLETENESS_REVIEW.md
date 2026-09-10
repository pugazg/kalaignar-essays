# P4 Source / Completeness Review — பேசும் கலை வளர்ப்போம்

Publication: `publications/pesum-kalai-valarppom/`  
Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`  
P4 baseline: live `main` at `71673e15eea7a3606d4b43285dbc7872d9298e97`

## Result

**P4 — COMPLETE / PASS**

This gate reconciles the completed source, page-record, structural-index and Tamil assembly layers. It is a source/completeness audit; it is **not** the separate P5 publication-wide direct word-by-word / punctuation-by-punctuation visual fidelity pass.

## Preconditions

- P0 — **COMPLETE / PASS**;
- P1 — **COMPLETE / PASS — 82/82 scans mapped, 19/19 numbered sections**;
- P2 — **COMPLETE / PASS — 82/82 canonical page records VERIFIED**;
- P3 — **COMPLETE / PASS — 19/19 source-numbered assemblies**;
- unresolved Tamil/source/assembly blockers entering P4 — **0**.

## Source identity reconciliation

The source record, publication README, page map, contents index and root handover agree on the controlling witness:

- filename: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`;
- SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`;
- file size: **105,698,402 bytes**;
- physical scans: **82**;
- image-only source;
- source PDF committed: **No**;
- supplied edition: **எட்டாம் பதிப்பு — செப்டம்பர் 1996**;
- scan 1 cover witness: **`பேசும் கலை வளர்ப்போம்`**;
- scan 3 title-page witness: **`பேசும்கலை வளர்ப்போம்`**;
- scan 6 `பதிப்புரை` retains source-visible date **`15—7—81`**;
- printed contents page: **none**;
- separate back-cover scan: **none**.

The two title witnesses remain intentionally distinct. The 1981 `பதிப்புரை` date is not normalized to the 1996 edition date.

## Canonical page-record inventory

The live `pages/` directory reconciles to the physical source without a missing or duplicate scan record:

- expected physical scans: **82**;
- canonical page records found: **82**;
- scan-number coverage: **0001–0082 contiguous**;
- missing scan records: **0**;
- duplicate scan-number records: **0**;
- scans 1–2: outside printed pagination;
- scans 3–82: printed pp.1–80 continuously;
- pagination relation: `printed page = scan - 2` for scans 3–82;
- suppressed/inferred folios: **3,4,5,6,7,42,45,48,59,64,75**.

The suppressed/inferred folios remain recorded as inferred rather than as source-visible printed numerals.

## Front matter / physical-copy evidence reconciliation

The front-matter page records preserve printed publication text separately from later copy-specific evidence:

- scan 1 — printed cover title/body separated from the later red handwritten mark;
- scan 2 — inside-cover / near-blank physical-copy evidence retained as its own record;
- scan 3 — printed title-page text separated from later handwriting/date and library stamp;
- scan 4 — printed edition/imprint text separated from library stamp/show-through;
- scan 5 — **no printed publication text**; full-page later handwriting remains only physical-copy evidence;
- scan 6 — printed `பதிப்புரை`, including `15—7—81`, separated from show-through / scan noise.

No front-matter handwriting, stamp or copy-specific mark has been imported into the numbered-section reading layer.

## Numbered-section / assembly reconciliation

The structural indexes and P3 assembly layer agree exactly:

- expected numbered sections: **19**;
- live assemblies: **19** — `01-section-01.md` through `19-section-19.md`;
- numbering/order: **01–19 contiguous**;
- assemblies with `status: "source-complete"`: **19 / 19**;
- main-work scan coverage: **7–82**;
- printed main-work coverage: **pp.5–80**;
- missing / unexpected assemblies: **0 / 0**;
- unexplained section-boundary gaps / overlaps: **0 / 0**.

The 19 assembly spans remain exactly those recorded in `indexes/contents.md`, `indexes/page-map.md` and `P3_ASSEMBLY_AUDIT.md`.

### Shared transition scans

The 12 source-visible mid-page transition scans remain:

`12,16,22,27,31,34,38,51,55,67,70,79`

Each is divided between adjacent assemblies at the source-visible numbered-section numeral. The P3 provenance comments and boundary structure show no duplicated or omitted body text caused by those shared scans.

Top-of-page section openings remain `7,42,45,48,59,64,75`.

## Correction provenance / propagation

Two documented P2 source corrections were explicitly rechecked through their dependent reading assemblies:

1. scan 13 draft `வீட்டான்` → source-visible **`வீடுதான்`**. The canonical scan-13 record and `articles/02-section-02.md` both carry **`வீடுதான்`**.
2. scan 74 draft `வாரியிலே` / `வாரிக்கு` → source-visible **`வரியிலே` / `வரிக்கு`**. The canonical scan-74 record and `articles/17-section-17.md` both preserve the resulting source phrases **`ஒரே வரியிலே`** and **`ஒரு வரிக்கு மேல்`**.

The final scan-81→82 continuation remains represented in section 19 as `முழுவாழ்வு வாழ` → `விடாமல் நம்மிடமிருந்து பறித்துக்கொண்டு விட்டது.`

## P4 discrepancy ledger

- source-identity discrepancies: **0**;
- missing / duplicate canonical page records: **0 / 0**;
- structural-map discrepancies: **0**;
- missing / extra assemblies: **0 / 0**;
- assembly boundary gaps / overlaps: **0 / 0**;
- front-matter / physical-copy separation defects: **0**;
- suppressed/inferred folio regressions: **0**;
- correction-propagation defects: **0**;
- new text corrections required by P4: **0**;
- unresolved P4 blockers: **0**.

## Gate decision

**PASS. P4 is COMPLETE.**

The source, canonical page-record, structural-index and 19-section assembly layers are internally reconciled with no outstanding completeness discrepancy.

## Next authorized phase

**P5 — strict visual word/punctuation fidelity pass.**

Re-inspect all **82 physical source scans directly** against the canonical page records, word-by-word and punctuation-by-punctuation, including cover/front matter, suppressed/inferred folio distinctions, all numbered-section body text, quotations, dates, numbers, headings, paragraph/page continuations and physical-copy marks. Record every P5 correction as old reading → source-visible reading and propagate any correction into dependent assemblies/indexes/trackers. Create `VISUAL_TEXT_FIDELITY_REVIEW.md` (or the guide-equivalent report) before P5 can close.

English remains **BLOCKED until Tamil P5 freeze**.