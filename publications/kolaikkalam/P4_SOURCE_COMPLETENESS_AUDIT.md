# P4 Source / Completeness Audit — கொலைக்களம்!

Controlling source publication: `TVA_BOK_0063657_கொலைக்களம்.pdf`

P4 audited the six P3 article assemblies against the reconciled canonical page-record layer. This was a structural/source-completeness gate; it did not substitute for the later P5 strict visual pass.

## P4 checks

For every assembly, P4 checked:

1. correct canonical scan span and start/end boundary;
2. every expected scan represented once in source order;
3. page-boundary continuation preserved;
4. source-supported unit heading/internal heading retained;
5. no physical-copy marks, page-record audit notes or YAML metadata imported into prose;
6. no front matter imported into the six main units;
7. no following-unit text crossed an end boundary;
8. scan-40 printer witness excluded from Unit 6 prose;
9. reconciled wording retained without assembly-time normalization.

## Unit results

| Unit | Assembly | Source scans | P4 result |
|---:|---|---:|---|
| 1 | `articles/01-kolaikkalam.md` | 5–9 | **PASS** |
| 2 | `articles/02-asthi-karaiyattum.md` | 10–16 | **PASS** |
| 3 | `articles/03-paliyai-niruththungal.md` | 17–22 | **PASS** |
| 4 | `articles/04-vizhalukku-neer-iraiththu.md` | 23–27 | **PASS** |
| 5 | `articles/05-sothanai.md` | 28–33 | **PASS** |
| 6 | `articles/06-veeramuzhakkam-seythiduveer.md` | 34–40 | **PASS** |

## P4 result

- assemblies audited: **6 / 6**;
- canonical main-unit scans covered: **36 / 36 (5–40)**;
- missing assembly scans: **0**;
- duplicate/out-of-order assembly scans: **0**;
- boundary defects: **0**;
- physical-copy/audit contamination: **0**;
- assembly-only text corrections required during P4: **0**;
- blockers: **0**;
- P4: **COMPLETE / PASS**.

## Subsequent P5 closeout

P5 subsequently reopened **all 40 / 40 physical scans** and performed the separate strict word/punctuation fidelity gate required by `ESSAY_PROCESSING_GUIDE.md`.

The later P5 findings do **not** change the historical P4 result; they are strict visual fidelity corrections discovered only after P4. P5 propagated:

- source-visible short printed rules on scans 5, 9, 10, 17 and 28;
- scan-22 isolated dark `1`-like mark classified as physical-copy/non-body evidence;
- scan-40 `போலிசோ` → `போலீசோ`;
- scan-40 `டாட்டாவோ` → `டாடாவோ`;
- scan-40 `காமார்க்கங் குடியல்லோம்` → `காமார்க்குங் குடியல்லோம்`;
- scan-40 closing witness confirmed as `திராவிடநாடு திராவிடருக்கே!`.

After propagation, all six assemblies were rechecked:

- P5 physical scans: **40 / 40 PASS**;
- final assembly strict recheck: **6 / 6 PASS**;
- unresolved fidelity discrepancies: **0**;
- blockers: **0**;
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**.

Final frozen Tamil blob SHAs are recorded in `VISUAL_TEXT_FIDELITY_REVIEW.md`.

## Exact next activity

**E0 — English translation planning/setup only**, from the six frozen strict-reviewed Tamil assemblies. Do not begin article translation in the same activity.
