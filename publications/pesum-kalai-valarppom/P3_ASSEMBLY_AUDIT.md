# P3 Assembly Audit — பேசும் கலை வளர்ப்போம்

Publication: `publications/pesum-kalai-valarppom/`  
Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`  
P3 starting baseline: live `main` at `c164785d6cf8451ef7306cdbd2f195d5ca7a3701`

## Result

**P3 — COMPLETE / PASS**

The source-numbered Tamil reading layer has been assembled from the fully verified canonical P2 page records. The live `articles/` directory now contains the complete numbered set `01-section-01.md` through `19-section-19.md`.

## Preconditions

- P0 — **COMPLETE / PASS**;
- P1 — **COMPLETE / PASS — 82/82 scans mapped, sections 19/19**;
- P2 — **COMPLETE / PASS — 82/82 canonical page records VERIFIED**;
- main-work source span — scans **7–82 / printed pp.5–80**;
- unresolved printed-text/source blockers entering P3 — **0**;
- P2 silent normalization — **0**.

## Assembly-set validation

Live directory: `publications/pesum-kalai-valarppom/articles/`

- expected source-numbered assemblies: **19**;
- live assemblies found: **19**;
- missing assemblies: **0**;
- unexpected extra assemblies: **0**;
- numbering/order: **01–19 contiguous**;
- source-numbered section coverage: **1–19 complete**;
- main-work scan coverage represented: **7–82**;
- printed main-work coverage represented: **pp.5–80**;
- unexplained section-boundary gaps: **0**;
- unexplained overlaps: **0**;
- intentional shared transition scans: **12** — `12,16,22,27,31,34,38,51,55,67,70,79`;
- unresolved assembly body-text blocks: **0**.

Shared transition scans are intentionally split between the adjacent numbered-section assemblies at the source-visible section numeral. They are not duplicate body text.

## Canonical spans validated

| Section | Assembly | Scans | Printed pages | Boundary |
|---:|---|---:|---:|---|
| 1 | `01-section-01.md` | 7–12 | 5–10 | scan 7 top → scan 12 before 2 |
| 2 | `02-section-02.md` | 12–16 | 10–14 | scan 12 mid → scan 16 before 3 |
| 3 | `03-section-03.md` | 16–22 | 14–20 | scan 16 mid → scan 22 before 4 |
| 4 | `04-section-04.md` | 22–27 | 20–25 | scan 22 mid → scan 27 before 5 |
| 5 | `05-section-05.md` | 27–31 | 25–29 | scan 27 mid → scan 31 before 6 |
| 6 | `06-section-06.md` | 31–34 | 29–32 | scan 31 mid → scan 34 before 7 |
| 7 | `07-section-07.md` | 34–38 | 32–36 | scan 34 mid → scan 38 before 8 |
| 8 | `08-section-08.md` | 38–41 | 36–39 | scan 38 mid → scan 41 page end |
| 9 | `09-section-09.md` | 42–44 | 40–42 | scan 42 top → scan 44 page end |
| 10 | `10-section-10.md` | 45–47 | 43–45 | scan 45 top → scan 47 page end |
| 11 | `11-section-11.md` | 48–51 | 46–49 | scan 48 top → scan 51 before 12 |
| 12 | `12-section-12.md` | 51–55 | 49–53 | scan 51 mid → scan 55 before 13 |
| 13 | `13-section-13.md` | 55–58 | 53–56 | scan 55 mid → scan 58 page end |
| 14 | `14-section-14.md` | 59–63 | 57–61 | scan 59 top → scan 63 page end |
| 15 | `15-section-15.md` | 64–67 | 62–65 | scan 64 top → scan 67 before 16 |
| 16 | `16-section-16.md` | 67–70 | 65–68 | scan 67 mid → scan 70 before 17 |
| 17 | `17-section-17.md` | 70–74 | 68–72 | scan 70 mid → scan 74 page end |
| 18 | `18-section-18.md` | 75–79 | 73–77 | scan 75 top → scan 79 before 19 |
| 19 | `19-section-19.md` | 79–82 | 77–80 | scan 79 mid → scan 82 source end |

The spans agree with `indexes/contents.md` and `indexes/page-map.md`.

## Assembly rules applied

- body text comes only from canonical VERIFIED page-record `# அச்சு உரை` material;
- only source-visible numbered headings `1`–`19` are used; no descriptive titles were invented;
- source wording, punctuation, quotations and paragraph order were preserved;
- page-boundary provenance comments were retained;
- true lexical/page continuations were joined without changing wording;
- front-matter handwriting, stamps and other physical-copy evidence were not imported into the reading layer;
- source-sensitive forms from P2, including `வீடுதான்`, `ஒரே வரியிலே`, `ஒரு வரிக்கு மேல்`, `(Mannerism)`, `மேனரிசம்`, `தவிர்க்கவொண்ணாத`, `1962-ல்`, `“வாலிபப் பெரியார்”`, `எ.வி.பி. ஆசைத்தம்பி`, and `என். வி. நடராசனார்`, remain unchanged.

The final section preserves the verified scan-81→82 continuation `முழுவாழ்வு வாழ` → `விடாமல் நம்மிடமிருந்து பறித்துக்கொண்டு விட்டது.` with the page-boundary provenance marker retained inside the continuous sentence.

## P3 gate decision

**PASS. P3 is COMPLETE.**

This gate closes the Tamil numbered-section assembly layer only. It does **not** claim P4 source/completeness audit, P5 strict visual fidelity, Tamil freeze, or English readiness.

## Next authorized phase

**P4 — source audit / completeness review.**

Reconcile the source record, all 82 canonical page records, the 19 assembled sections, section/page mapping, front-matter/source-witness distinctions, physical-copy evidence separation, and correction provenance. Record any discrepancy explicitly and propagate source-supported corrections before closing P4.

Do **not** begin P5 strict visual word/punctuation fidelity or English in the same step unless separately authorized. English remains blocked until the Tamil P0–P5 freeze.
