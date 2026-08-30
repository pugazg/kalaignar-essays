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
| 1 | கயிற்றில் தொங்கிய கணபதி | [`translations/en/01-kayittril-thongiya-kanapathi.md`](translations/en/01-kayittril-thongiya-kanapathi.md) | **fidelity-reviewed** | **T0–T2 passed; T3 next** |

English title accepted through T2: **Ganapathi Who Hung from the Rope**.

## T1 — COMPLETE / PASSED

The complete article was translated paragraph by paragraph from scans **6–15**, with all source scan-boundary comments retained and no Tamil source change.

## T2 — COMPLETE / PASSED

T2 compared every English paragraph/clause against the frozen Tamil assembly and found no missing source passage after review. Fidelity-driven corrections included:

- `நமது நாட்டு கணபதி` → `Ganapathi of our land`;
- source conditional `வந்தால்` restored as `if ... came to rule`;
- unsupported `special` removed from the Tamil-Nadu importance sentence;
- scan-9/10 `உணர்வைத் தொடுவதில்லை` restored as `does not touch their sensibility`;
- unsupported gloss `mangu vessels` reduced to source-bearing `mangu`;
- `அவர்தம் ஆத்மா` restored to singular/honorific `his soul`;
- added agent removed from `மரணவஸ்தைக்காளாகும்`;
- source singular `ஆலை` restored as `a factory`;
- `பெண்தெய்வ மாநாடு` corrected to `conference of goddesses`.

T2 also resolved the seven T1 watch-items. The irregular `சுதந்திர பூமியில்...` source quotation is documented as a source-punctuation anomaly while the English keeps readable quotation closure. The final source `/` remains preserved for formal T4 audit.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md).

## Current gate sequence

- **T0 — source prerequisite / setup:** COMPLETE / PASS
- **T1 — complete close English draft:** COMPLETE / PASS
- **T2 — bilingual fidelity review:** **COMPLETE / PASS**
- **T3 — Kalaignar voice review:** **NEXT**
- **T4 — terminology / quotation / citation / source audit:** NOT STARTED
- **T5 — translation verification:** NOT STARTED
- **E6 — publication-level English consistency review:** NOT STARTED
- **E7 — English release closeout:** NOT STARTED

## T3 scope

T3 must preserve all T2 factual/fidelity decisions while reviewing the English for Kalaignar's voice: directness, sarcasm, ridicule, rhetorical questions, repeated imperatives/exclamations, physical imagery and argumentative rhythm. It may improve cadence only where meaning and source-bearing choices remain unchanged.

High-value voice passages include the opening gallows personification, Mother Tamil dialogue, flower/fragrance argument, `Cry well!` sequence, Kamaraj ridicule, colloquial comic taunt and the final Dravidam/self-rule crescendo.

## Exact next activity

Execute **T3 — Kalaignar voice review for Article 1 only**:

1. re-fetch the fidelity-reviewed English article and frozen Tamil authority;
2. confirm the recorded Tamil blob still matches;
3. review the complete English article for directness, sarcasm, ridicule, rhetorical questions, repetition, imagery, exclamations and cadence;
4. preserve all T2 fidelity decisions and source-bearing terms;
5. make only meaning-neutral voice/cadence corrections;
6. set `translation_status: voice-reviewed` only after the complete article passes;
7. update review/tracker/plan/README/HANDOVER;
8. do **not** perform T4 in the same activity.