# Audit — பேசும் கலை வளர்ப்போம்

## Gate tracker

| Gate | Status | Durable result |
|---|---|---|
| P0 source intake / publication identification | **PASS** | source identity + edition + 82-scan structure established |
| P1 metadata + page map + section mapping | **PASS** | **82/82** scans mapped; pp.1–80; sections **19/19** |
| P2 page-level transcription | **IN PROGRESS** | **60/82 VERIFIED**; batches 1–6 / scans 1–60 PASS |
| P3 assemblies | **NOT STARTED** | — |
| P4 source/completeness audit | **NOT STARTED** | — |
| P5 strict visual fidelity | **NOT STARTED** | — |
| English E0–E7 | **NOT STARTED** | blocked until Tamil freeze |

## P0 / P1 durable gates

**P0 PASS.** Controlling source `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`, SHA-256 `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`, 105,698,402 bytes, 82 image-only scans; source PDF not committed.

**P1 COMPLETE / PASS.** Scans **1–2** are outside printed pagination; scans **3–82 = pp.1–80** continuously with `printed page = scan - 2`. Section starts/ends are **19/19 / 19/19**. Shared mid-page transitions are `12,16,22,27,31,34,38,51,55,67,70,79`. Suppressed/inferred folio scans are `3,4,5,6,7,42,45,48,59,64,75`. No printed contents page or separate back-cover scan. P1 blockers **0**.

## P2 batches 1–5 — durable prior state

Scans **1–50 / through printed p.48** are VERIFIED. Earlier transitions through scan 38 and the page-boundary section closures/openings on scans 41–48 remain preserved. Earlier documented correction remains scan 13 draft `வீட்டான்` → source-visible `வீடுதான்`. Unresolved readings **0**; assemblies **0**.

## P2 batch 6 — scans 51–60

**COMPLETE / PASS.**

- new canonical page records: **10**;
- cumulative canonical records / direct verification: **60 / 82**;
- contiguous verified range: scans **1–60**;
- batch printed coverage: pp.**49–58**;
- cumulative printed coverage: through **p.58**;
- scan **51** section `11→12` — **VERIFIED / PRESERVED**;
- scan **55** section `12→13` — **VERIFIED / PRESERVED**;
- scan **58** closes section 13 at page end;
- scan **59** opens section 14 at page top — p.57 folio **suppressed / inferred**, not visibly printed;
- scan **60** remains section 14;
- unresolved printed-text readings: **0**;
- unresolved source/structure distinctions: **0**;
- section assemblies created: **0**;
- batch blockers: **0**.

Direct continuation / boundary checks include:

- scan 51 `ஆகிவிடுமென` → scan 52 `வள்ளுவர் கூறியது`;
- scan 53 `ஆற்றைக் கடக்க மக்கள்` → scan 54 `ஒரு பால வசதியின்றிக்`;
- scan 55 `ஒரு மாநில ஆட்சியைக்` → scan 56 `கவிழ்க்க முடியும் என்பதையும்`;
- scan 57 `வைத்துக்` → scan 58 `கொள்வோம்.`;
- scan 58 section 13 closes; scan 59 source-visible section `14` opens at page top;
- scan 60 `அரசியல் கட்சி மேடையில்` → scan 61 `அதற்குப் பதில் அளிக்கும்போது` directly checked; scan 61 is not yet counted.

Source-sensitive readings secured during batch 6 include:

- scan 51 — `போர்களம்`, `அரங்கின்றி வட்டாடுவதுபோல`, printed gathering mark `பே—4` kept separate from prose;
- scan 52 — `அவைக்கணம்`, `இயலாதோர் வர்க்கத்தைக் கசக்கிப் பிழிந்த`, `ஒளவைக்குக்`;
- scan 53 — `ஒலிபெருக்கியாளர்கள்`, `வீணுக் குழைத்தோமடா`;
- scan 54 — `கட்டுபடியான`, `குக்கிராமத்துப் பொதுக்கூட்டம்`;
- scan 55 — `கிரேக்கத்து`, `ஆபிரகாம் லிங்கன்`, `விபரங்களையும்`;
- scan 56 — `மாங்கொல்லையிலோ`, `புரசை வெள்ளாளர்`, `நியாயந்தானே!`;
- scan 57 — `எழுவயது`, `சுற்றடைப்புக்குள்`;
- scan 58 — `மது பார்மிட்`, `உத்திரவிட்டேன்`, and the distinct `‘போன்’` / `“போன்”` punctuation witnesses;
- scan 59 — source-visible `களித்திருமளவுக்கு`; p.57 folio suppressed/inferred;
- scan 60 — `சொற்பெருக்காற்றக்`, `தாற்குறையாகத்`, and spaced dash sequence `தாற்குறையாக — ஆபாசமாக — அருவருக்கத்தக்க`.

Batch-6 page-record corrections after final direct verification: **0**. Silent normalization: **0**.

## Source-witness distinctions that must not regress

1. scan 1 cover `பேசும் கலை வளர்ப்போம்`; scan 3 title page `பேசும்கலை வளர்ப்போம்` — preserve independently.
2. scan 5 is later handwriting, not printed publication text.
3. scan 6 `பதிப்புரை` date is source-visible `15—7—81`; do not normalize to 1996.
4. numbered openings `1–19` are source-visible; descriptive section titles must not be invented.
5. physical-copy marks remain separate from printed text.
6. twelve section changes occur mid-page and must retain dual membership on shared page records.
7. suppressed/inferred folios must never be represented as directly printed numerals.

## Corrections / normalization

- P0 source-text corrections: **0**;
- P1 source-text corrections: **0**;
- P2 silent normalization: **0**;
- P2 page records: **60 / 82 VERIFIED**;
- documented P2 page-record source corrections: **1 total** (`வீட்டான்` → `வீடுதான்`, scan 13);
- batch-6 corrections: **0**;
- unresolved P2 readings: **0**.

## Exact next activity

**P2 batch 7 — scans 61–70 / printed pp.59–68.** Scans 61–63 remain section 14, with section 14 ending at scan 63 page end. Scan **64 / inferred p.62** opens section 15 at page top and has a suppressed/inferred folio. Preserve the section **15→16** mid-page transition on scan **67** and **16→17** transition on scan **70**. Check scan 70→71 where needed and **do not build assemblies during P2**.
