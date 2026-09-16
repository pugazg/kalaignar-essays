# P5 Visual Text Fidelity Review — பெருமூச்சு

## Status

**IN PROGRESS — 78 / 83 physical scans directly rechecked.**

Controlling source: `TVA_BOK_0064124_பெருமூச்சு.pdf`  
Source SHA-256: `18947f2deb1ece71b03b59c1e52d9f483a45baa5bf436ab2c3e89a48b5f2dc38`  
Physical scans: **83**

P5 is the final strict source-pixel review. The rendered scan remains controlling. The user-supplied `perumoochu.md` remains an alignment aid only.

Tamil is **not frozen** while this file is IN PROGRESS. English remains blocked.

## Direct visual coverage

- scans **1–23** — directly rechecked;
- scans **24–52** — directly rechecked against the repaired physical boundaries;
- scans **53–78** — directly rechecked;
- scans **79–83** — **PENDING final strict line-by-line reconciliation**.

Current coverage: **78 / 83**.

## Correction state through scan 78

P5 has so far committed **75 canonical printed-text page-record correction events**:

- scans **1–23** — **42**;
- scans **24–52** — **28**;
- scans **53–78** — **5 confirmed page-record corrections committed in the current sync**.

The scans 1–52 corrections are already present in live `main` page records and dependent article assemblies. Their final consolidated old→source-visible ledger remains a P5-closure task; the current repository diffs remain authoritative until that consolidation is complete.

### Current-sync confirmed corrections — scans 53–78

| Scan | Old canonical reading | Source-visible reading |
|---:|---|---|
| 59 | `திருப்பியழைத்து` | **`திருப்பியமைத்து`** |
| 61 | `ஒரே கண்ணால்` | **`ஒரே கண்ணில்`** |
| 62 | `நம் குரல் எழும்பினால்` | **`நம் குரல் எழும் பின்பு`** |
| 75 | scan ended with `ஆதரிக்கவும்` | scan ends with **`ஆதரிக்க`** |
| 76 | scan began with spurious `⚬ பெரியாருடன்` | scan begins with continuation **`வும்—பெரியாருடன்`** |

The scan 75→76 repair preserves the physical source boundary: `ஆதரிக்க / வும்—பெரியாருடன்`.

### Printed page furniture

- scan **19** — printed gathering/signature mark **`[2]`** recorded;
- scan **35** — printed gathering/signature mark **`[3]`** recorded;
- scan **51** — printed gathering/signature mark **`[4]`** recorded;
- scan **67** — printed gathering/signature mark **`[5]`** recorded.

These are printed page furniture and are not article body text.

## Earlier P5 durable source corrections already on live main

P5 has already propagated source-visible front-matter and body fidelity corrections including:

- cover author — **`மு.கருணாநிதி`**;
- title-page label — **`விற்பனை உரிமை:-`**;
- imprint label — **`வெளியீடு:-`**;
- source punctuation / dash / spacing distinctions in scans 7–23;
- source-exact spacing, initials, dash forms and wording distinctions in scans 24–52.

Permanent source readings remain in force, including **`மந்திரிகள் குலை நடுக்கம்`** with historical `லை`.

## Article propagation / reconstruction state

Earlier P5 batches already propagated corrections through Articles **1–8**.

Current sync propagated the confirmed scans 53–78 body corrections to:

- Article 10 — `articles/10-maadottigal.md`;
- Article 12 — `articles/12-sindhiththunarga-seetramuraadheer.md`.

Post-propagation exact reconstruction against current canonical page records:

- Article 10 / scans 57–62 — **PASS**;
- Article 12 / scans 71–76 — **PASS**.

Article 9 / scans 53–56 and Article 11 / scans 63–70 were directly reviewed in this P5 run with no currently recorded body-text correction from the durable findings set.

Article 13 is **not P5-closed**: scans 77–78 were inspected, while scans 79–80 remain pending.

## Gate state

- P0 — **COMPLETE / PASS**
- P1 — **COMPLETE / PASS — 83/83**
- P2 — **COMPLETE / PASS — 83/83 VERIFIED**
- P3 — **COMPLETE / PASS — 13/13**
- P4 — **COMPLETE / PASS**
- P5 — **IN PROGRESS — 78/83**
- English — **BLOCKED**
- Tamil archival layer — **NOT YET FROZEN**

## Scan 83 user-confirmed non-regression reading

- source heading — **`ஊடுருவி தீட்டியவை:-`**
- the attempted P5 reading `உருகி தீட்டியவை:-` was incorrect and has been reverted.
- future review must preserve **`ஊடுருவி தீட்டியவை:-`** exactly as printed.

## Exact continuation point

Continue P5 with **scans 79–83**:

1. strict word-by-word / punctuation-by-punctuation review of scans 79–80 and terminal catalogue scans 81–83;
2. commit any remaining page-record corrections;
3. propagate scan 79–80 body corrections, if any, into Article 13;
4. re-run final exact reconstruction for all 13 article assemblies as required;
5. consolidate the complete P5 old→source-visible correction ledger;
6. update README / audit / HANDOVER to P5 COMPLETE only if all **83/83** pass with zero unresolved fidelity discrepancies.

Do **not** begin English or Publication 15 before Publication 14 P5 closure unless explicitly redirected.
