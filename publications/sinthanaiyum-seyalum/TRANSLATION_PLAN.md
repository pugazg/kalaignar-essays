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
- T2 bilingual fidelity review: **1 / 50 PASS**
- T3 Kalaignar voice review: **0 / 50**
- T4 terminology / quotation / citation audit: **0 / 50**
- T5 article verification: **0 / 50**
- E6 publication-wide consistency review: **NOT STARTED**
- E7 release closeout: **NOT STARTED**
- English files: **1 / 50**, Article 1 status `draft`
- translation blockers: **0**

## Article 1 T2 result

Article 1 was compared sentence-by-sentence and clause-by-clause against frozen Tamil blob `79791aad807179e85b4275539fff8283d2ff61b2`.

T2 made **8 fidelity corrections**, all recorded with old → corrected wording in `translations/en/TRANSLATION_REVIEW.md`. They remove or narrow T1 over-interpretation/addition while preserving the source's rhetorical structure. Key corrections include:

- `swells through the whole day` → `matures through the whole day`;
- `spectacle of jumping from branch to branch` → `an amusing game of jumping from branch to branch`;
- removal of unsupported first-person `betrayed us`;
- removal of added `day` in the Parliament/adjournment sentence;
- `upstairs house` / `easy splendour` → `storeyed house` / `live in comfort`;
- removal of added `reserved for them` from `உரிமை ஆவணம்`;
- clarification of the purity/wearer dependency;
- `destroying democracy` → `undermine democracy` for source `சீர்குலைக்கும்`.

After correction: omitted source claims **0**, added substantive claims **0**, numbers/dates/quotations **PASS**, ordered source comments **6/6 PASS**, unresolved T2 fidelity blockers **0**. Tamil changed **0**.

Article 1 remains `translation_status: draft`; T3–T5 are still pending.

## Article 1 source-bearing choices retained through T2

- `உடன்பிறப்பே` → **Dear sibling,**;
- title `பாசியும் - தூசியும்!` → **Moss and Dust!**;
- `கூழியல்` → **Resources** pending T4 terminology audit;
- Bharathidasan `கருப்பாதை` → **the path to conception**;
- `புனுகு`, `சவ்வாது` → **punugu**, **javvadu**;
- `மந்தகாச வாழ்வினர்` → **those who live in comfort**;
- `மாயாண்டி`, `மன்னார்` → **Mayandi**, **Mannar**;
- `அறநெறி தானிய விளைச்சல்` retains its grain/harvest image.

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

**Article 1 `பாசியும் - தூசியும்!` — T3 Kalaignar voice review only.** Read the corrected English as English while comparing with the frozen Tamil. Check directness, sarcasm/polemical bite, rhetorical questions, commands, repetition, abrupt contrasts and vivid images; record every T3 correction in `TRANSLATION_REVIEW.md`, then stop before T4.

Do not begin Article 2 yet.
