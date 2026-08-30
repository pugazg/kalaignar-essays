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
| 1 | கயிற்றில் தொங்கிய கணபதி | [`translations/en/01-kayittril-thongiya-kanapathi.md`](translations/en/01-kayittril-thongiya-kanapathi.md) | **voice-reviewed** | **T0–T3 passed; T4 next** |

English title retained through T3: **Ganapathi Who Hung from the Rope**.

## T1 — COMPLETE / PASSED

The complete article was translated paragraph by paragraph from scans **6–15**, with all source scan-boundary comments retained and no Tamil source change.

## T2 — COMPLETE / PASSED

T2 compared every English paragraph/clause against the frozen Tamil assembly and corrected only fidelity defects. It restored source conditionality, number, naming/relationship details, quotation attachment, `உணர்வைத் தொடுவதில்லை`, source-bearing `மங்கு`, singular `ஆலை`, `பெண்தெய்வ மாநாடு`, and other source-alignment points. The final `/` remained untouched for T4.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md).

## T3 — COMPLETE / PASSED

T3 read the entire fidelity-reviewed English article against the Tamil for Kalaignar's voice without reopening T2 factual decisions.

Meaning-neutral cadence work included:

- tightening the opening cruel-teeth image;
- restoring declarative force in `So many people die every day in the world.`;
- repairing awkward English in the flower/fragrance argument while keeping its repetition;
- tightening the `Ganapathi's loud voice` sentence;
- strengthening the Kamaraj ridicule sentence without changing its claim;
- `a tragic serial in the life of the Tamils`;
- final `a separate Dravidam` / `self-respect will bloom and flourish` cadence.

T3 retained the title, `Cry well!`, `mangu`, `Mukari`, all political/source labels, the Kamaraj comic taunt, `Have you hanged him!`, and the final `/` unchanged.

**T3 RESULT: PASS — 0 unresolved voice blockers.**

## Current gate sequence

- **T0 — source prerequisite / setup:** COMPLETE / PASS
- **T1 — complete close English draft:** COMPLETE / PASS
- **T2 — bilingual fidelity review:** COMPLETE / PASS
- **T3 — Kalaignar voice review:** **COMPLETE / PASS**
- **T4 — terminology / quotation / citation / source audit:** **NEXT**
- **T5 — translation verification:** NOT STARTED
- **E6 — publication-level English consistency review:** NOT STARTED
- **E7 — English release closeout:** NOT STARTED

## T4 scope

T4 must formally audit names/referents, recurring terminology, source-bearing/cultural terms, quotation scope, punctuation anomalies and scan traceability. High-value items include `mangu`, `Mukari`, `Achariyar`, `Dravidam`, `Dravidar Kazhagam`, food terms, the irregular `சுதந்திர பூமியில்...` quotation, `நெருக்கடியில்(!)`, `தூக்குபோட்டுவிட்டீர்களா!`, the irregular Ganapathi-letter quotation, and final `/`.

## Exact next activity

Execute **T4 — terminology / quotation / citation / source audit for Article 1 only**:

1. re-fetch the voice-reviewed English article, frozen Tamil authority, lexicon and review ledger;
2. confirm the English `source_tamil_blob_sha` still matches `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
3. audit names, political labels, cultural/source-bearing terms and recurring terminology;
4. audit quotation boundaries, source punctuation anomalies, scan comments and final `/`;
5. make only audit-driven corrections;
6. set `translation_status: audited` only after the complete article passes;
7. update review/tracker/plan/README/HANDOVER;
8. **do not perform T5 in the same activity**.