# P4 Source / Completeness Audit — கொலைக்களம்!

Controlling source publication: `TVA_BOK_0063657_கொலைக்களம்.pdf`

P4 audits the six P3 article assemblies against the reconciled canonical page-record layer. This is a structural/source-completeness gate; it is **not** the separate P5 strict visual word/punctuation recheck of the PDF.

## Authority used

- canonical page records: `pages/0005-...` through `pages/0040-...` for the six main prose units;
- post-P2 reconciliation: `LEXICAL_RECONCILIATION_2026-09-04.md`;
- user-reviewed controlling damaged-print readings, including scan 34 `பலம்`;
- P3 assemblies under `articles/`.

## Audit checks

For every assembly, P4 checked:

1. correct canonical scan span and start/end boundary;
2. every expected scan represented once in source order;
3. page-boundary continuation preserved with scan comments;
4. source-supported unit heading and any internal source heading retained;
5. no `அச்சு அல்லாத / physical-copy marks`, page-record audit notes, YAML page-record metadata, or source-record comments imported into prose;
6. no front matter from scans 1–4 imported into the six main units;
7. no text from the following unit imported across an end boundary;
8. scan-40 printer witness excluded from Unit 6 prose body;
9. reconciled wording retained without assembly-time normalization.

## Unit results

| Unit | Assembly | Source scans | Boundary / coverage result | P4 result |
|---:|---|---:|---|---|
| 1 | `articles/01-kolaikkalam.md` | 5–9 | scans 5, 6, 7, 8, 9 present once and in order; scan 6→7 continuation preserved | **PASS** |
| 2 | `articles/02-asthi-karaiyattum.md` | 10–16 | scans 10–16 present once and in order; ending rule retained; scan 17 excluded | **PASS** |
| 3 | `articles/03-paliyai-niruththungal.md` | 17–22 | scans 17–22 present once and in order; ending rule retained; scan 23 excluded | **PASS** |
| 4 | `articles/04-vizhalukku-neer-iraiththu.md` | 23–27 | scans 23–27 present once and in order; `குரல்`→`கம்ம` and `தகராறு`→`கள்` page continuations preserved | **PASS** |
| 5 | `articles/05-sothanai.md` | 28–33 | scans 28–33 present once and in order; `தரணியாண்`→`டோம்` page continuation preserved | **PASS** |
| 6 | `articles/06-veeramuzhakkam-seythiduveer.md` | 34–40 | scans 34–40 present once and in order; `இருக்`→`கின்றன.` and scan 37→38 quotation continuation preserved; printer witness excluded | **PASS** |

## Heading / witness checks

- Unit 1 heading: `கொலைக்களம்!` — retained.
- Unit 2 heading: `‘அஸ்தி’ கரையட்டும்!` — retained with quoted `அஸ்தி` witness.
- Unit 3 heading: `பலியை நிறுத்துங்கள்!` — retained.
- Unit 4 source-visible decorative two-line heading witness `விழலுக்கு : : / : : : நீர் இறைத்து...` — retained in the assembly rather than silently normalized in the body.
- Unit 5 heading: `சோதனை!` — retained.
- Unit 6 heading: `வீரமுழக்கஞ் செய்திடுவீர்!` — retained.
- Unit 6 internal source heading `பெயர் மாற்றமே ஒழிய கருத்து ஒன்றுதான்` — retained.

## Reconciled-reading non-regression spot checks

P4 confirmed that the assemblies retain the controlling reconciled/manual readings relevant to assembly integrity, including:

- scan 5 `யுத்தம்`;
- scan 8 `நமக்கெல்லாம்`;
- scan 23 `மனிதனான தப்பா`;
- scan 23 `கண்ணாடிக் கன்னத்தை`;
- scan 25 `இதற்குத்தானா`;
- scan 28 `சூத்திரர்களை`;
- scan 29 `புயலெனச்`;
- scan 30 `இதுதானா`;
- scan 34 `பலம்`.

## Assembly-only defects

**None found.**

No P3 article body required correction during P4.

## Result

- assemblies audited: **6 / 6**;
- canonical scan spans covered: **36 / 36 main-unit scans (5–40)**;
- missing assembly scans: **0**;
- duplicate/out-of-order assembly scans: **0**;
- boundary defects: **0**;
- physical-copy/audit contamination in article prose: **0**;
- assembly-only text corrections required: **0**;
- blockers: **0**;
- P4: **COMPLETE / PASS**.

## Exact next activity

**P5 — strict visual word-by-word / punctuation-by-punctuation fidelity pass over all 40 physical scans, followed by recheck/propagation into all six article assemblies and creation of the publication-level visual-text-fidelity report.**

P5 must return to the controlling PDF scan itself. Do not treat this P4 structural pass as a substitute for P5. English translation remains out of scope until the Tamil archival gates are complete/frozen.
