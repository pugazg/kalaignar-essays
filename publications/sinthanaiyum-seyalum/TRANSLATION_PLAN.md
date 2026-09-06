# English Translation Plan — சிந்தனையும் செயலும்

Publication: `சிந்தனையும் செயலும்`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/sinthanaiyum-seyalum/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Objective — ACTIVE

Translate all **50** frozen strict-reviewed Tamil article assemblies into readable English while preserving meaning, rhetorical action, source-page trace, quotation structure, repetition, commands, questions, irony, polemical force and literary lineation.

The frozen Tamil assemblies in `articles/` are the only translation authorities. Do not translate from OCR, web text, alternate editions, remembered wording or raw pre-fidelity transcriptions.

## Tamil prerequisite — COMPLETE / FROZEN

- P0–P5: **COMPLETE / STRICT-REVIEWED / FROZEN**
- P2 canonical scans: **226 / 226 VERIFIED**
- P3 Tamil assemblies: **50 / 50 VERIFIED**
- publication-wide P4: **PASS**
- publication-wide P5: **226 / 226 PASS**
- unresolved Tamil/source-fidelity blockers: **0**

Final Tamil records remain `PUBLICATION_WIDE_P4.md`, `VISUAL_TEXT_FIDELITY_REVIEW.md` and `PUBLICATION_COMPLETION_REVIEW.md`.

## Translation queue / authority

The canonical 50-unit order and scan spans are fixed by [`articles/README.md`](articles/README.md). T0 source pins are recorded article-by-article before drafting rather than inferred from filenames.

### Article 1 voice-baseline authority

| # | Tamil title | Scans | Frozen Tamil blob | T0 |
|---:|---|---|---|---|
| 1 | `பாசியும் - தூசியும்!` | `18–23` | `79791aad807179e85b4275539fff8283d2ff61b2` | **PASS** |

Working English title: **Moss and Dust!**

Article 1 is the publication's voice baseline. Complete its T1–T5 sequence before accelerating later articles.

## Current English gate status

- E0 translation planning/setup: **COMPLETE / PASS**
- T0 source prerequisite: **1 / 50 PASS**
- T1 close draft: **1 / 50 COMPLETE**
- T2 bilingual fidelity review: **0 / 50**
- T3 Kalaignar voice review: **0 / 50**
- T4 terminology / quotation / citation audit: **0 / 50**
- T5 article verification: **0 / 50**
- E6 publication-wide consistency review: **NOT STARTED**
- E7 release closeout: **NOT STARTED**
- English files: **1 / 50**, Article 1 status `draft`
- translation blockers: **0 source blockers**

## Article 1 T1 baseline decisions

These are working T1 choices, not release-frozen decisions. T2 must test them against the Tamil side by side:

- `உடன்பிறப்பே` → **Dear sibling,** as a source-bearing kinship salutation rather than silently substituting “Comrade” or a personal-name address;
- `பாசியும் - தூசியும்!` → **Moss and Dust!**, preserving the closing pond/eye image;
- Tirukkural Porutpaal division labels use close descriptive English, with `கூழியல்` provisionally **Resources**;
- `அய்யன் வள்ளுவர்` retains the source honorific as **Ayya Valluvar**;
- `புனுகு`, `சவ்வாது` retain source-bearing **punugu**, **javvadu** rather than speculative expansion;
- `மாயாண்டி`, `மன்னார்` remain **Mayandi**, **Mannar** without outside identification;
- embedded verse is translated from the frozen Tamil text, not imported from published English versions.

## Working method

For each article:

1. T0 — fetch the live frozen Tamil assembly and pin its blob SHA;
2. T1 — translate paragraph by paragraph, preserving ordered `<!-- Tamil source: scan ... -->` comments;
3. T2 — bilingual omission/addition/referent/number/logic review;
4. T3 — voice, directness, sarcasm, command/question/repetition review;
5. T4 — lexicon, proper-name, quotation, citation and source-comment audit;
6. T5 — mark `verified` only after T1–T4 pass;
7. after all 50 T5 passes, run E6 cross-article consistency and E7 release closeout.

The living lexicon and review ledger must be updated during the work, not reconstructed at the end.

## Exact next activity

**Article 1 `பாசியும் - தூசியும்!` — T2 bilingual fidelity review only.** Compare the frozen Tamil blob `79791aad807179e85b4275539fff8283d2ff61b2` against `translations/en/01-paasiyum-thoosiyum.md` paragraph by paragraph. Record every T2 correction in `TRANSLATION_REVIEW.md`, update the lexicon where required, then stop before T3.
