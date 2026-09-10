# Page Map — பேசும் கலை வளர்ப்போம்

Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`  
Physical scans: **82**  
Tamil archival gate: **P5 COMPLETE / PASS — 82/82 — FROZEN**  
English gate: **E0 COMPLETE / T0 19/19 PASS**

## Canonical pagination rule

- scans **1–2** are outside printed pagination;
- scans **3–82 = printed pp.1–80** continuously;
- for scans 3–82, `printed page = physical scan - 2`;
- suppressed/inferred folio scans: **3,4,5,6,7,42,45,48,59,64,75**;
- all other pp.6–80 folios are source-visible according to the P1 map;
- no separate back-cover scan.

A suppressed/inferred folio must never be represented as a source-visible printed numeral.

## Page-type map

- scan 1 — front cover — outside pagination;
- scan 2 — inside cover / near-blank — outside pagination;
- scan 3 / p.1 inferred — title page;
- scan 4 / p.2 inferred — edition / imprint;
- scan 5 / p.3 inferred — physical-copy annotation, **no printed publication text**;
- scan 6 / p.4 inferred — `பதிப்புரை`, source-visible date `15—7—81`;
- scans **7–82 / pp.5–80** — main work, source-numbered sections `1–19`.

## Canonical section spans

| Section | Scan / printed-page span | Start | End | Tamil assembly |
|---:|---|---|---|---|
| 1 | 7–12 / pp.5–10 | scan 7 top | scan 12 before 2 | `articles/01-section-01.md` |
| 2 | 12–16 / pp.10–14 | scan 12 mid | scan 16 before 3 | `articles/02-section-02.md` |
| 3 | 16–22 / pp.14–20 | scan 16 mid | scan 22 before 4 | `articles/03-section-03.md` |
| 4 | 22–27 / pp.20–25 | scan 22 mid | scan 27 before 5 | `articles/04-section-04.md` |
| 5 | 27–31 / pp.25–29 | scan 27 mid | scan 31 before 6 | `articles/05-section-05.md` |
| 6 | 31–34 / pp.29–32 | scan 31 mid | scan 34 before 7 | `articles/06-section-06.md` |
| 7 | 34–38 / pp.32–36 | scan 34 mid | scan 38 before 8 | `articles/07-section-07.md` |
| 8 | 38–41 / pp.36–39 | scan 38 mid | scan 41 page end | `articles/08-section-08.md` |
| 9 | 42–44 / pp.40–42 | scan 42 top | scan 44 page end | `articles/09-section-09.md` |
| 10 | 45–47 / pp.43–45 | scan 45 top | scan 47 page end | `articles/10-section-10.md` |
| 11 | 48–51 / pp.46–49 | scan 48 top | scan 51 before 12 | `articles/11-section-11.md` |
| 12 | 51–55 / pp.49–53 | scan 51 mid | scan 55 before 13 | `articles/12-section-12.md` |
| 13 | 55–58 / pp.53–56 | scan 55 mid | scan 58 page end | `articles/13-section-13.md` |
| 14 | 59–63 / pp.57–61 | scan 59 top | scan 63 page end | `articles/14-section-14.md` |
| 15 | 64–67 / pp.62–65 | scan 64 top | scan 67 before 16 | `articles/15-section-15.md` |
| 16 | 67–70 / pp.65–68 | scan 67 mid | scan 70 before 17 | `articles/16-section-16.md` |
| 17 | 70–74 / pp.68–72 | scan 70 mid | scan 74 page end | `articles/17-section-17.md` |
| 18 | 75–79 / pp.73–77 | scan 75 top | scan 79 before 19 | `articles/18-section-18.md` |
| 19 | 79–82 / pp.77–80 | scan 79 mid | scan 82 source end | `articles/19-section-19.md` |

Shared mid-page transition scans: **12,16,22,27,31,34,38,51,55,67,70,79**.  
Top-of-page openings: **7,42,45,48,59,64,75**.

## Tamil archival overlay — COMPLETE / FROZEN

- P2 canonical page records / direct verification — **82/82 COMPLETE / PASS**;
- P3 assemblies — **19/19 COMPLETE / PASS**;
- P4 source/completeness reconciliation — **COMPLETE / PASS**;
- P5 strict visual fidelity — **82/82 COMPLETE / PASS**;
- P5 corrections found / propagated — **33/33**;
- unresolved Tamil fidelity discrepancies — **0**;
- missing/duplicate scan records — **0/0**;
- missing/extra assemblies — **0/0**;
- pagination, transition and suppressed-folio drift — **0**.

## English overlay

- E0 workspace/planning — **COMPLETE / PASS**;
- T0 frozen-source prerequisites — **19/19 PASS**;
- frozen baseline commit — **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**;
- exact Tamil assembly blob SHAs — **19/19 recorded**;
- English body files — **0/19**;
- T1 / T2 / T3 / T4 / T5 — **0/19**.

Translation follows the frozen Tamil **article assemblies** as primary authority. Page records/source scans are consulted only when a punctuation, page-boundary, source-witness or reading question must be checked. English work does not alter this page map or frozen Tamil.

## Exact next activity

**E1 — Section 1 / T1 voice-calibration draft.** Reconfirm frozen `articles/01-section-01.md` blob **`e5517b7cc344554d51af4092599059d481039c1e`**, then create `translations/en/01-section-01.md` as a complete draft preserving all source-page boundary comments. T2–T5 follow independently.