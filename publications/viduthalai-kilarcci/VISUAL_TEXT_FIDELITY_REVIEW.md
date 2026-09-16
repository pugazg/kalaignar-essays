# P5 Visual Text Fidelity Review — விடுதலைக் கிளர்ச்சி

## Scope

Controlling source: `TVA_BOK_0064066_விடுதலைக்கிளர்ச்சி.pdf`  
Source SHA-256: `444ff76695154b5ee9d53f4647873fde72659a3d52a76aa833fdc502fb518809`  
Physical scans: **69**

P5 is the independent final strict visual word-by-word / punctuation-by-punctuation / meaningful-spacing recheck. Source pixels remain controlling.

## Current state

**IN PROGRESS — 40/69 physical scans STRICT-REVIEWED**

- Batch 001 — scans **1–10** — **COMPLETE / PASS**
- Batch 002 — scans **11–20** — **COMPLETE / PASS**
- Batch 003 — scans **21–30** — **COMPLETE / PASS**
- Batch 004 — scans **31–40** — **COMPLETE / PASS**
- unresolved P5 readings — **0**
- guessed readings — **0**
- next range — **41–50**

## Batch 001 — scans 1–10

| Scan | Result | Canonical correction |
|---:|---|---|
| 1 | PASS after correction | restore omitted first printed `★` |
| 2 | PASS | none |
| 3 | PASS after follow-up correction | `கலிமகள்` → **`கலைமகள்`** |
| 4 | PASS | none |
| 5 | PASS after correction | 3 source-fidelity corrections |
| 6 | PASS | none |
| 7 | PASS | none |
| 8 | PASS | none |
| 9 | PASS after correction | source hyphen restored |
| 10 | PASS | none |

## P5 correction ledger — scans 1–10

| Scan | Old canonical reading | Source-visible reading |
|---:|---|---|
| 1 | one represented printed `★` device | **two printed `★` devices**, one before and one after author |
| 5 | `கதறிக் கதறித் தொண்டையும்` | **`கதறிக் கதறி தொண்டையும்`** |
| 5 | `கிழித்து எரிந்திருக்கின்றன` | **`கிழித்து எறிந்திருக்கின்றன`** |
| 5 | `அழுத்தப்பட்ட-பிறகு` | **`அழுத்தப்பட்ட - பிறகு`** |
| 9 | `இப்படி அங்கிங்கெனாதபடி` | **`இப்படி-அங்கிங்கெனாதபடி`** |

## Batch 002 — scans 11–20

| Scan | Result | Canonical correction |
|---:|---|---|
| 11 | PASS | none |
| 12 | PASS | none |
| 13 | PASS after correction | `வீடற்றவராய்` → **`வீட்டற்றவராய்`** |
| 14 | PASS | none; **`இந்தோ சீனாவில்!`** revalidated |
| 15 | PASS | none |
| 16 | PASS | none |
| 17 | PASS | none |
| 18 | PASS | none |
| 19 | PASS | none |
| 20 | PASS | none |

Batch-002 canonical corrections — **1**.  
Batch-001 follow-up correction — scan 3 printer **`கலைமகள் பிரஸ்`**.

## Batch 003 — scans 21–30

| Scan | Result | Canonical correction |
|---:|---|---|
| 21 | PASS | none |
| 22 | PASS | none |
| 23 | PASS | none |
| 24 | PASS | none |
| 25 | PASS | none |
| 26 | PASS | none |
| 27 | PASS | none |
| 28 | PASS after correction | `நாம்சொல்வதை` → **`நாம் சொல்வதை`** |
| 29 | PASS | none |
| 30 | PASS after correction | `குலாவிட வேண்டுமாம்` → **`குலாவிடவேண்டுமாம்`** |

Batch-003 canonical corrections — **2**.

## Batch 004 — scans 31–40

| Scan | Result | Canonical correction |
|---:|---|---|
| 31 | PASS after correction | `நாடுகளை` → **`நாடுகளின்`** in opening phrase |
| 32 | PASS after correction | `உ, வெ.` → **`உ. வெ.`** |
| 33 | PASS | none |
| 34 | PASS | none |
| 35 | PASS | none |
| 36 | PASS | none |
| 37 | PASS | none |
| 38 | PASS | none |
| 39 | PASS after correction | source punctuation repaired in two places |
| 40 | PASS | none |

Batch-004 canonical corrections — **4**.

## Historical Tamil glyph audit

Mandatory historical families were explicitly rechecked where present:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Batch-001/002/003/004 cumulative result:

- unresolved historical-glyph ambiguity — **0**
- global modernization / normalization — **0**
- source-visible wording preserved — **PASS**

## Propagation state

Corrected canonical page blobs include:
- scan 3 — `7188216c7f9f3597dbbedc7d5d6297d5bd913918`
- scan 13 — `145c28daaef6e4e3966bdbe4a284c3b0283e5d93`

Earlier Batch-001 corrected canonical page blobs:
- scan 1 — `1505ab4f95d3715304bd9af37b2d4a68ce44b337`
- scan 5 — `0ddbde56884c89a499dae15305fd2f7c839a384d`
- scan 9 — `5ffa57c44a854b333ed737257fe533662d2f4560`

Assembly propagation:
- `articles/00-vengaiyai-virattum-padalam.md` — scans 4–7 fully rechecked; **STRICT-REVIEWED** — blob `c5be16582c2c3bb238cc1bf1ae47f8301173352f`
- `articles/01-viduthalai-kilarcci.md` — scans 8–40 strict-reviewed with all P5 corrections propagated; P5 is still partial — blob `ab1fc1d83b60b79088faa679904c1eb71057a64c`

## Exact next activity

**P5 scans 41–50.**
