# Source audit — திராவிட சம்பத்து

## Scope

Controlling source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`  
Recorded source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`  
Physical scans: **16**  
Kalaignar article assemblies: **2**

This ledger records **P4 — source audit / completeness review**. P5 strict word-by-word / punctuation-by-punctuation visual fidelity is deliberately **not** performed in this activity.

Publication-specific authority remains:

> **The user-supplied transcription is the lexical baseline for surviving words. The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, boundaries and physical-copy evidence. Text physically lost under torn-away paper is not reconstructed from context.**

## P4 — source completeness / assembly consistency — PASS

P4 was executed after both article assemblies were created from the verified P2 page layer.

### Physical-source accounting

Every physical scan is represented exactly once in the reconstructed publication sequence:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

| Reading unit | Physical scans | P4 result |
|---|---|---|
| cover / publication identity | 1 | **PASS** |
| imprint / edition / publisher / printer | 2 | **PASS** |
| publisher foreword `மன்றத்தில்` | 9–10 | **PASS** |
| Article 1 `திராவிட சம்பத்து` | 5–6, 13–16 | **PASS** |
| publisher note `முக்கிய குறிப்பு` | 7–8, 11 | **PASS** |
| Article 2 `ஐயர் அறிவிக்கிறார்!` | 12, 3 | **PASS** |
| promotional advertisements | 4 | **PASS / outside article bodies** |

- unrepresented physical scans: **0**;
- duplicate physical scans in reading map: **0**;
- printed contents page: **none**;
- pencil folio marks `2`–`8`: **physical-copy marks only / not printed page numerals**.

### Reading-order / continuation audit

The non-linear physical scan order remains mandatory. Direct continuation witnesses were rechecked against the page layer and assemblies:

- scan 6 `...என்று` → scan 13 `கூறினோம்.`: **PASS**;
- scan 15 `...திராவிடம், திராவிட` → scan 16 surviving `மொழி. திராவிட...`: **PASS**;
- scan 7 `...முத` → scan 8 `லாவது...`: **PASS**;
- scan 8 publisher note → scan 11 conclusion/cue: **PASS**;
- scan 12 `...வாயிலிலே நின்று` → scan 3 `கொண்டிருக்கிறார்...`: **PASS**;
- scan 3 closes Article 2 before scan 4 advertisements: **PASS**.

No page-order correction was required during P4.

## P3 article assembly audit

### Article 1 — `திராவிட சம்பத்து`

Assembly: `articles/01-thiraavida-sampaththu.md`  
Current blob: `43c1123a0bdb14dc20dc351a581b1e46c9df04fa`

- mapped scans **5, 6, 13, 14, 15, 16** all present once and in reconstructed order: **PASS**;
- source headings retained: `அரசியல் நோயாளிகள்`, `வால் ஆடுகிறது`, `புராணம் புகுந்து விட்டது`, `விஷம வேலை`, `இனவெறி - இனப்பற்று`, `ஆப்பசைத்த குரங்கு`, `குப்பை மேட்டுக் குயில்கள்`: **PASS**;
- opening `*` retained: **PASS**;
- page-boundary comments: **6 / 6 PASS**;
- scan-15 and scan-16 torn-text gaps remain explicit `SOURCE DAMAGE` comments: **PASS**;
- scan-16 source-visible recovery `மொழி.` retained and documented: **PASS**;
- no hidden torn text reconstructed: **PASS**;
- supplied lexical baseline silently replaced: **0**.

### Article 2 — `ஐயர் அறிவிக்கிறார்!`

Assembly: `articles/02-aiyar-arivikkirar.md`  
Current blob: `357b7c7f7431b33e9c465956227337631550e2c1`

- mapped scans **12, 3** both present once and in reconstructed order: **PASS**;
- article heading retained: **PASS**;
- scan-12 → scan-3 sentence continuation retained: **PASS**;
- page-boundary comments: **2 / 2 PASS**;
- scan-3 supplied damaged/ambiguous lexical fragments, including `அயம்`, remain user-baseline readings: **PASS / not silently normalised**;
- no hidden torn text reconstructed: **PASS**.

## Publisher matter / advertisement boundary audit

- `மன்றத்தில்` remains publisher foreword, outside the two Kalaignar article assemblies: **PASS**;
- `முக்கிய குறிப்பு` remains publisher note, outside the two article assemblies: **PASS**;
- its explicit cue to the following U. V. Saminatha Iyer article supports the Article 2 boundary: **PASS**;
- scan 4 remains promotional back matter, outside both article bodies: **PASS**;
- scan-4 supplied advertisement-title reading `ரூசோ` remains unchanged under the user lexical-baseline rule; the visible lexical disagreement remains **provisional for P5**, not a P4 structural correction.

## Damage / loss audit

The source is materially incomplete because paper is physically absent. This is **documented source loss**, not an archival-completeness failure and not permission to invent text.

- major/severe tears are recorded on scans **3–4, 7–8, 11–16**;
- tears intersect printed lines on several pages;
- surviving supplied-transcription tokens remain represented;
- known torn-away passages are not contextually reconstructed;
- inline `SOURCE DAMAGE` markers in Article 1 remain preserved;
- physical-copy pencil marks, ageing, stains and show-through remain separated from printed text.

P4 does **not** claim that the physically missing original wording is recoverable from this copy.

## P4 discrepancy ledger

- missing mapped source units: **0**;
- duplicate mapped source units: **0**;
- out-of-order source units: **0**;
- missing article page-boundary comments: **0**;
- article start/end boundary defects: **0**;
- publisher matter leaked into article assemblies: **0**;
- advertisement leaked into article assemblies: **0**;
- lexical substitutions made during P3/P4: **0**;
- Tamil body edits made during P4: **0**;
- unresolved workflow blockers: **0**;
- durable physical-source-loss gaps: **present / documented / unreconstructed**.

**P4 SOURCE AUDIT / COMPLETENESS REVIEW: PASS.**

## Current Tamil archival state

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **COMPLETE — 2 / 2 article assemblies**
- P4: **PASS**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

## Exact next activity

Execute **P5 — strict visual text-fidelity review** across all **16 physical scans**, word by word and punctuation by punctuation, under the publication-specific user lexical-baseline rule.

P5 must:

1. recheck every physical scan, including cover, imprint, `மன்றத்தில்`, both articles, `முக்கிய குறிப்பு`, and scan-4 advertisements;
2. correct only source-supported structure/punctuation/spacing/layout issues without silently replacing the user's surviving lexical tokens;
3. record every correction as old reading → source-supported reading;
4. explicitly log scan/transcription lexical conflicts instead of silently resolving them;
5. preserve every torn-away gap without contextual reconstruction;
6. propagate any permitted corrections into article assemblies, indexes, README, metadata, audit and handover;
7. create `VISUAL_TEXT_FIDELITY_REVIEW.md` and, if P5 passes, `PUBLICATION_COMPLETION_REVIEW.md`;
8. do **not** begin English translation in the same P5 activity.
