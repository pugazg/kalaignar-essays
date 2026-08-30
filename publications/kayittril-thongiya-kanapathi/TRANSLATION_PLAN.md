# English Translation Plan — கயிற்றில் தொங்கிய கணபதி

Publication: `கயிற்றில் தொங்கிய கணபதி`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/kayittril-thongiya-kanapathi/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

## Objective

Translate the single frozen Tamil article into readable English while retaining Kalaignar's direct address, accusation, sarcasm, rhetorical questions, repetition, exclamations, political labels, physical imagery and argumentative rhythm.

> **Translate the language; do not neutralise the voice.**

## Source prerequisite — PASSED / FROZEN

- P0–P5: **COMPLETE**
- strict visual-text-fidelity: **17 / 17 PASS**
- Tamil article assemblies: **1 / 1 strict-rechecked**
- unresolved Tamil blockers: **0**
- Tamil source layer: **COMPLETE / FROZEN**
- source PDF committed: **No**

Translation authority:

- Tamil article: `articles/01-kayittril-thongiya-kanapathi.md`
- frozen Tamil article blob SHA: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- source scans: **6–15**

If the Tamil article changes because of a genuine source-supported correction, all affected English gates must reopen.

## Article tracker

| # | Tamil title | English file | Status | Gates |
|---:|---|---|---|---|
| 1 | கயிற்றில் தொங்கிய கணபதி | [`translations/en/01-kayittril-thongiya-kanapathi.md`](translations/en/01-kayittril-thongiya-kanapathi.md) | **verified** | **T0–T5 passed** |

Verified English title: **Ganapathi Who Hung from the Rope**.

## Article-level gate results

- **T0 — source prerequisite / setup:** COMPLETE / PASS
- **T1 — complete close English draft:** COMPLETE / PASS
- **T2 — bilingual fidelity review:** COMPLETE / PASS
- **T3 — Kalaignar voice review:** COMPLETE / PASS
- **T4 — terminology / quotation / citation / source audit:** COMPLETE / PASS
- **T5 — final article translation verification:** **COMPLETE / PASS**

T5 confirmed the frozen Tamil article blob remains `b7c6d02cd7bc041318693306b8658e18c3f8fa5b` and verified all T2 fidelity corrections, T3 voice decisions and T4 terminology/source decisions without regression. Scan-boundary comments **6–15**, documented quotation anomalies, source-bearing terms and final `/` remain intact. T5 made no English body-text change.

## E6 — publication-level English consistency review — COMPLETE / PASS

Although this publication contains only one article, E6 separately reviewed consistency across the verified article, metadata, lexicon, review ledger and this plan.

E6 confirmed:

- verified English article blob reviewed: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`;
- article remains `translation_status: verified`;
- English still points to frozen Tamil blob `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
- title style is consistent;
- names/referents and ideological vocabulary are consistent;
- `mangu`, `Rani`, `Mukari`, `adhirasam`, `akkāra vadisal`, `pallu`, `Achariyar` and other source-bearing/cultural terms remain restrained and unexpanded;
- source `Jawahar` versus `Nehru` remains intentionally distinct;
- rhetorical directness, sarcasm, questions, exclamations, physical imagery and final Dravidam crescendo remain intact;
- documented quotation/source anomalies remain documented rather than silently normalised;
- scan comments **6–15** remain complete and ordered;
- no front matter/advertisement text entered the English body;
- E6 body corrections: **0**;
- E6 unresolved blockers: **0**.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md) and [`translations/en/LEXICON.md`](translations/en/LEXICON.md).

## Publication-level gates

- **E6 — publication-level English consistency review:** **COMPLETE / PASS**
- **E7 — English release closeout:** **NEXT**
- English release: **NOT YET CLOSED**

## Exact next activity

Execute **E7 — English release closeout** for this publication only:

1. re-fetch live `main`, the verified English article, frozen Tamil authority, translation records and release-facing publication/root records;
2. verify the English article still exists, remains `verified`, and points to the current frozen Tamil blob;
3. verify counts, links, gate statuses, source-anomaly/non-regression records and source-PDF exclusion;
4. create/update `translations/en/RELEASE_REPORT.md` with the final release matrix and checks;
5. close the English release gate only if all release checks pass;
6. update publication/root README and authoritative `HANDOVER.md`;
7. after successful E7, advance the repository to the next normal **P0 intake** activity;
8. do not reopen verified prose during E7 unless a genuine release blocker is found.