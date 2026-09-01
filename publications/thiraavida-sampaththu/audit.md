# Source audit — திராவிட சம்பத்து

## Scope

Controlling source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`  
Recorded source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`  
Physical scans: **16**  
Kalaignar article assemblies: **2**

This ledger records **P4 — source audit / completeness review** and the completed **P5 — strict visual word/punctuation fidelity review**.

Publication-specific authority remains:

> **The user-supplied transcription is the lexical baseline for surviving words. The scan controls structure, punctuation, spacing, paragraphing, headings, reading order, boundaries and physical-copy evidence. Text physically lost under torn-away paper is not reconstructed from context. Scan/transcription lexical disagreements are documented rather than silently substituted.**

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

No page-order correction was required during P4 or P5.

## P3/P5 article assembly audit

### Article 1 — `திராவிட சம்பத்து`

Assembly: `articles/01-thiraavida-sampaththu.md`  
Final strict-reviewed blob: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`

- mapped scans **5, 6, 13, 14, 15, 16** all present once and in reconstructed order: **PASS**;
- source headings retained, including P5-corrected `இனவெறி—இனப்பற்று`: **PASS**;
- opening `*` retained: **PASS**;
- page-boundary comments: **6 / 6 PASS**;
- scan-15 and scan-16 torn-text gaps remain explicit `SOURCE DAMAGE` comments: **PASS**;
- scan-16 source-visible recovery `மொழி.` retained and documented: **PASS**;
- scan-15 source-visible recovery `கிரேக்க மொழி` propagated: **PASS**;
- no hidden torn text reconstructed: **PASS**;
- user-baseline lexical conflicts silently replaced: **0**.

### Article 2 — `ஐயர் அறிவிக்கிறார்!`

Assembly: `articles/02-aiyar-arivikkirar.md`  
Final strict-reviewed blob: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`

- mapped scans **12, 3** both present once and in reconstructed order: **PASS**;
- article heading retained: **PASS**;
- scan-12 → scan-3 sentence continuation retained: **PASS**;
- page-boundary comments: **2 / 2 PASS**;
- scan-3 source paragraph break and dash punctuation propagated: **PASS**;
- scan-3 supplied damaged/ambiguous lexical fragments, including `அயம்`, remain user-baseline readings: **PASS / not silently normalised**;
- no hidden torn text reconstructed: **PASS**.

## Publisher matter / advertisement boundary audit

- `மன்றத்தில்` remains publisher foreword, outside the two Kalaignar article assemblies: **PASS**;
- `முக்கிய குறிப்பு` remains publisher note, outside the two article assemblies: **PASS**;
- its explicit cue to the following U. V. Saminatha Iyer article supports the Article 2 boundary: **PASS**;
- scan 4 remains promotional back matter, outside both article bodies: **PASS**;
- scan-4 supplied advertisement-title reading `ரூசோ` remains unchanged under the user lexical-baseline rule; the scan-visible `ஜூலி` witness is now explicitly documented in P5.

## Damage / loss audit

The source is materially incomplete because paper is physically absent. This is **documented source loss**, not an archival-completeness failure and not permission to invent text.

- major/severe tears are recorded on scans **3–4, 7–8, 11–16**;
- tears intersect printed lines on several pages;
- surviving supplied-transcription tokens remain represented;
- known torn-away passages are not contextually reconstructed;
- inline `SOURCE DAMAGE` markers in Article 1 remain preserved;
- physical-copy pencil marks, ageing, stains and show-through remain separated from printed text.

P5 does **not** claim that the physically missing original wording is recoverable from this copy.

## P5 strict visual fidelity — PASS

All **16 physical scans** were rechecked word by word and punctuation by punctuation under the publication-specific lexical-baseline rule.

Detailed correction provenance is in [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

P5 outcomes:

- physical scans checked: **16 / 16**;
- page records with propagated source-supported corrections: **15 / 16**;
- scan 9 body correction required: **0**;
- article assemblies rechecked after propagation: **2 / 2**;
- user-baseline lexical conflicts silently substituted: **0**;
- hidden torn text reconstructed: **0**;
- unresolved workflow blockers: **0**.

Documented retained lexical-witness conflicts:

- scan 3 `கல்லுரி` retained vs scan-appearing `கல்லூரி`;
- scan 4 `ரூசோ` retained vs scan-visible `ஜூலி`;
- scan 5 `கண்னை` retained vs scan-appearing `கண்ணை`;
- scan 16 `பேச்சுல` retained vs scan-appearing `பேச்சை`.

Source-visible recoveries:

- scan 16 `மொழி.` — earlier recovery retained;
- scan 15 `கிரேக்க மொழி` — P5 recovery of directly visible omitted `ழி` from supplied `கிரேக்க மொ`.

**P5 STRICT VISUAL TEXT-FIDELITY REVIEW: PASS.**

## Current Tamil archival state

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3: **COMPLETE — 2 / 2 article assemblies**
- P4: **PASS**
- P5 strict visual word/punctuation fidelity: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- English translation: **NOT STARTED**

Publication completion record: [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md).

## Exact next activity

Execute **E0 — English translation planning/setup** from the two final strict-reviewed Tamil blobs:

- Article 1: `6e9759aff9bc4801ee66b3b8c76a814be3e98015`;
- Article 2: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

Create the translation plan/tracker/lexicon/review scaffolding and register these frozen Tamil authorities. Do not reopen the Tamil bodies for stylistic polishing, lexical conventionalisation or terminology homogenisation.