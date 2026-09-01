# Publication Completion Review — திராவிட சம்பத்து

## Publication

- Title: **திராவிட சம்பத்து**
- Author: **கலைஞர் மு. கருணாநிதி**
- Edition: **முதல பதிப்பு, செப்டம்பர் 1951**
- Publisher: **அறிவு மன்றம், சென்னை-1**
- Source: `TVA_BOK_0064196_திராவிட_சம்பத்து.pdf`
- Source SHA-256: `09d567abb30a0beacc1efd1e1fb757f01da93968f5582c9b1b8859b87dac2165`
- Physical scans: **16**
- Printed contents page: **none**

## Tamil archival gates

| Gate | Status |
|---|---|
| P0 — source intake / publication identification | **COMPLETE** |
| P1 — metadata + page map + reconstructed reading order | **COMPLETE** |
| P2 — page-level transcription / structural review | **16 / 16 COMPLETE** |
| P3 — article assemblies | **2 / 2 COMPLETE** |
| P4 — source/completeness audit | **PASS** |
| P5 — strict visual word/punctuation fidelity | **16 / 16 PASS** |

## Final Tamil authorities

1. `திராவிட சம்பத்து` — scans **5–6, 13–16** — final strict-reviewed blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — final strict-reviewed blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

These two assemblies are the downstream English-translation authorities.

## Source-order closure

The physical PDF remains non-linear. The publication reading sequence is frozen as:

`1 → 2 → 9 → 10 → 5 → 6 → 13 → 14 → 15 → 16 → 7 → 8 → 11 → 12 → 3 → 4`

All **16** physical scans are represented exactly once. Publisher matter and the advertisement remain outside the two Kalaignar article bodies.

## Fidelity / lexical-rule closure

The user-established lexical rule remains permanent for this publication:

- supplied words are the lexical baseline for surviving text;
- the scan controls punctuation, quotation marks, spacing, paragraphing, headings, reading order, boundaries and physical-copy evidence;
- scan/baseline lexical disagreements are documented rather than silently substituted;
- directly visible supplied omissions may be restored with provenance;
- text physically lost under torn-away paper is not reconstructed.

P5 retained documented lexical-witness conflicts on scans **3, 4, 5 and 16** and preserved damaged scan-3 `அயம்` without unsupported correction. P5 also preserved the earlier scan-16 source recovery `மொழி.` and added the directly visible scan-15 recovery `கிரேக்க மொழி` from supplied `கிரேக்க மொ`.

Detailed P5 provenance: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

## Physical source loss

The surviving copy is materially damaged. Large tears intersect printed text, especially on scans **3–4, 7–8, 11–16**. This irreversible loss is fully documented and does not block archival closure because missing wording has not been invented.

- hidden torn text reconstructed: **0**;
- silent lexical substitutions: **0**;
- unresolved workflow blockers: **0**.

## Tamil completion result

**TAMIL ARCHIVAL / STRICT-FIDELITY STATUS: COMPLETE / FROZEN.**

The publication is source-complete for the surviving supplied copy, with irreversible physical-source-loss gaps and the documented user-baseline lexical exceptions preserved as part of the archival record.

## English translation setup — E0 COMPLETE / PASS

E0 created the publication English translation workspace and registered both frozen Tamil authorities as T0 sources.

- `TRANSLATION_PLAN.md`: **created**;
- `translations/en/README.md`: **created**;
- `translations/en/LEXICON.md`: **created**;
- `translations/en/TRANSLATION_REVIEW.md`: **created**;
- Article 1 T0: **PASS** — Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`;
- Article 2 T0: **PASS** — Tamil blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`;
- T0 overall: **2 / 2 PASS**;
- English article bodies created: **0 / 2**;
- T1 drafts: **0 / 2**;
- English titles frozen: **0 / 2**;
- E0 Tamil body changes: **0**;
- unresolved translation blockers: **0**.

English must translate from the two strict-reviewed Tamil blobs above, not OCR, the pre-P5 user transcription, alternate scan-appearing lexical readings, remembered wording or later editions.

The translation workspace also carries forward the non-reconstruction rule for torn source gaps, the scan-3 damaged `அயம்`, and the P5 lexical-witness exceptions without silently correcting the frozen Tamil source.

## Exact next activity

Execute **Article 1 T1 — complete close English draft for `திராவிட சம்பத்து` only** from frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.

Create `translations/en/01-thiraavida-sampaththu.md`, translate every surviving Tamil paragraph in order, preserve source-page comments for scans **5, 6, 13, 14, 15, 16**, preserve all explicit `SOURCE DAMAGE` gaps without reconstruction, and synchronize the tracker, lexicon, translation-review ledger and root handover.

Stop after T1. Do **not** perform T2 in the same activity. **Do not reopen the frozen Tamil bodies for stylistic polishing or lexical conventionalisation.**