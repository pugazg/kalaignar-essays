# English Translation Plan — கயிற்றில் தொங்கிய கணபதி

Publication: `கயிற்றில் தொங்கிய கணபதி`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/kayittril-thongiya-kanapathi/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

## Objective

Translate the single frozen Tamil article into readable English while retaining Kalaignar's direct address, accusation, sarcasm, rhetorical questions, repetition, exclamations, political labels, physical imagery and argumentative rhythm. This is not a summary, adaptation, explanatory rewrite or ideological neutralisation.

> **Translate the language; do not neutralise the voice.**

## Source prerequisite — PASSED / FROZEN

- P0–P5: **COMPLETE**
- strict visual-text-fidelity: **17 / 17 PASS**
- Tamil article assemblies: **1 / 1 strict-rechecked**
- unresolved Tamil body/source blockers: **0**
- Tamil source layer: **COMPLETE / FROZEN**
- source PDF committed to repository: **No**

Immediate translation authority:

- Tamil article: `articles/01-kayittril-thongiya-kanapathi.md`
- frozen Tamil article blob SHA: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- source scans represented by article: **6–15**
- printed pages: **6–14**, with scan 6 carrying no visible printed numeral

If the Tamil article blob changes because of a genuine future source-supported correction, every downstream English gate must be reopened.

## Article tracker

| # | Tamil title | English file | Status | Gates |
|---:|---|---|---|---|
| 1 | கயிற்றில் தொங்கிய கணபதி | [`translations/en/01-kayittril-thongiya-kanapathi.md`](translations/en/01-kayittril-thongiya-kanapathi.md) | **draft** | **T0–T1 passed; T2 next** |

Working T1 English title: **Ganapathi Who Hung from the Rope**.

## T1 result — COMPLETE

The complete Article 1 body was translated paragraph by paragraph from the frozen Tamil assembly and committed as a close English draft.

T1 preserves:

- scan-boundary comments for scans **6–15**;
- paragraph order and article completeness;
- quotation-heavy sections and direct speech;
- gallows/body/blood imagery;
- rhetorical questions, repeated exclamations and abrupt contrasts;
- direct address to Mother Tamil / Tamil land;
- anti-imperialist and political polemical force;
- final source terminal `/` rather than silently normalising it.

Recurring terminology and working title decisions are recorded in [`translations/en/LEXICON.md`](translations/en/LEXICON.md). T1 source-sensitive questions are recorded in [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md).

T1 introduced **no Tamil source change**.

## Translation baseline

1. Translate paragraph by paragraph from the frozen Tamil assembly, not from OCR or memory.
2. Preserve commands, rhetorical questions, repetitions, exclamations and abrupt contrasts.
3. Do not soften descriptions of imperialism, political actors, death, hanging, class or social conditions.
4. Preserve source-chosen names and labels rather than replacing them with modern explanatory forms.
5. Do not silently identify or expand a source-specific expression from outside knowledge.
6. Preserve meaningful source punctuation anomalies and document them when they affect English meaning or quotation scope.
7. Retain source scan-boundary comments in the English article as `<!-- Tamil source: scan N / printed ... -->`.
8. Translation may use normal English spacing, but must not edit away rhetorical force.

## Current gate sequence

- **T0 — source prerequisite / setup:** COMPLETE / PASSED
- **T1 — complete close English draft:** **COMPLETE / PASSED**
- **T2 — bilingual fidelity review:** **NEXT**
- **T3 — Kalaignar voice review:** NOT STARTED
- **T4 — terminology / quotation / citation / source audit:** NOT STARTED
- **T5 — translation verification:** NOT STARTED
- **E6 — publication-level English consistency review:** NOT STARTED
- **E7 — English release closeout:** NOT STARTED

For this one-article publication, E6 remains a publication-level consistency/source-bearing review even though there is only one article.

## Exact next activity

Execute **T2 — bilingual fidelity review for Article 1 only**:

1. re-fetch the frozen Tamil assembly and the complete English draft;
2. confirm `source_tamil_blob_sha` still matches `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
3. compare every English paragraph and clause against the Tamil source;
4. check for omissions, additions, altered negatives, names, numbers, quotation scope, rhetorical questions, repetition and page-boundary comments;
5. recheck all source-sensitive items recorded in the lexicon/review ledger;
6. make only fidelity-driven English corrections;
7. set `translation_status: fidelity-reviewed` only after the whole article passes;
8. do not perform T3 in the same activity unless the authoritative handover has first advanced to T3.
