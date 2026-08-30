# English Translation Plan — கயிற்றில் தொங்கிய கணபதி

Publication: `கயிற்றில் தொங்கிய கணபதி`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/kayittril-thongiya-kanapathi/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

## Objective

Translate the single frozen Tamil article into readable English while retaining Kalaignar's direct address, accusation, sarcasm, rhetorical questions, repetition, exclamations, political labels, physical imagery and argumentative rhythm. This is not a summary, adaptation, explanatory rewrite or ideological neutralisation.

> **Translate the language; do not neutralise the voice.**

## T0 source prerequisite — PASSED

Tamil archival prerequisite:

- P0–P5: **COMPLETE**
- strict visual-text-fidelity: **17 / 17 PASS**
- Tamil article assemblies: **1 / 1 strict-rechecked**
- unresolved `NEEDS-PIXEL-REVIEW`: **0**
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

| # | Tamil title | Planned English file | Status | Gates |
|---:|---|---|---|---|
| 1 | கயிற்றில் தொங்கிய கணபதி | `translations/en/01-kayittril-thongiya-kanapathi.md` | **not-started** | **T0 passed; T1 next** |

No English article body exists yet.

## Translation baseline

1. Translate paragraph by paragraph from the frozen Tamil assembly, not from OCR or memory.
2. Preserve commands, rhetorical questions, repetitions, exclamations and abrupt contrasts.
3. Do not soften descriptions of imperialism, political actors, death, hanging, class or social conditions.
4. Preserve source-chosen names and labels rather than replacing them with modern explanatory forms.
5. Do not silently identify or expand a source-specific expression from outside knowledge.
6. Preserve meaningful source punctuation anomalies and document them when they affect English meaning or quotation scope.
7. Retain source scan-boundary comments in the English article as `<!-- Tamil source: scan N / printed ... -->`.
8. Translation may use normal English spacing, but must not edit away rhetorical force.

## Known source-sensitive items to carry into T1/T2

These Tamil forms are frozen and must be translated from their actual source context rather than 'corrected' first:

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நன்றுக`
- `அவர்கட்கு`
- `அக்கரை`
- `நெருக்கடியில்(!)`
- `தூக்குபோட்டுவிட்டீர்களா!`
- `கொண்டிருக்கிறார்.`
- `உரத்தகுரலில்,`
- `சாவின் முனையிலே`
- final `அளிக்குமாக /`

The title's final English rendering is **not yet frozen at T0**; choose it during T1 from the article's rhetorical context and record it in the English file and lexicon/review ledger.

## Translation gates

- **T0 — source prerequisite / setup:** **COMPLETE / PASSED**
- **T1 — complete close English draft:** **NEXT**
- **T2 — bilingual fidelity review:** NOT STARTED
- **T3 — Kalaignar voice review:** NOT STARTED
- **T4 — terminology / quotation / citation / source audit:** NOT STARTED
- **T5 — translation verification:** NOT STARTED
- **E6 — publication-level English consistency review:** NOT STARTED
- **E7 — English release closeout:** NOT STARTED

For this one-article publication, E6 remains a publication-level consistency/source-bearing review even though there is only one article.

## Exact next activity

Execute **T1 — complete close English draft for Article 1 only**:

1. re-fetch the frozen Tamil article and confirm blob SHA `b7c6d02cd7bc041318693306b8658e18c3f8fa5b` still matches;
2. create `translations/en/01-kayittril-thongiya-kanapathi.md`;
3. translate the complete article paragraph by paragraph;
4. preserve page-boundary comments, quotation structure, questions, exclamations, repetition and polemical force;
5. record any terminology/title decisions in `translations/en/LEXICON.md` and any source/translation issue in `translations/en/TRANSLATION_REVIEW.md`;
6. mark the article `draft` only after the complete body exists;
7. do not claim T2/T3/T4/T5 in the same activity unless the handover has first advanced to those gates.