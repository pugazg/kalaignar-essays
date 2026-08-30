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
| 1 | கயிற்றில் தொங்கிய கணபதி | [`translations/en/01-kayittril-thongiya-kanapathi.md`](translations/en/01-kayittril-thongiya-kanapathi.md) | **voice-reviewed** | **T0–T4 passed; T5 next** |

English title retained through T4: **Ganapathi Who Hung from the Rope**.

## T1 — COMPLETE / PASSED

The complete article was translated paragraph by paragraph from scans **6–15**, with all source scan-boundary comments retained and no Tamil source change.

## T2 — COMPLETE / PASSED

T2 compared every English paragraph/clause against the frozen Tamil assembly and corrected only fidelity defects. It restored source conditionality, number, naming/relationship details, quotation attachment, `உணர்வைத் தொடுவதில்லை`, source-bearing `மங்கு`, singular `ஆலை`, `பெண்தெய்வ மாநாடு`, and other source-alignment points.

## T3 — COMPLETE / PASSED

T3 read the entire fidelity-reviewed English article against the Tamil for Kalaignar's voice without reopening T2 factual decisions. It made only meaning-neutral cadence corrections and retained the title, `Cry well!`, source-bearing terms, political labels, punctuation anomalies and final `/`.

## T4 — COMPLETE / PASSED

T4 formally audited names/referents, recurring terminology, political labels, cultural/source-bearing terms, quotation scope, source punctuation anomalies, scan traceability and the final `/`.

Key T4 results:

- `Dravidam`, `Dravidians`, `Mother Tamil`, `Commonwealth`, `Dravidar Kazhagam` and `Achariyar` are consistent;
- source `ஜவகர்` → `Jawahar` and source `நேரு` → `Nehru` remain intentionally distinct;
- `mangu`, `Mukari`, `adhirasam`, `akkāra vadisal` and `pallu` remain restrained source-bearing/cultural forms;
- source `இராணி` remains `Rani` without an external identity claim;
- irregular quotation scope around `சுதந்திர பூமியில்...` is documented while English keeps readable closure;
- irregular quoted syntax beginning `மிகவும் உயர்ந்த நிலையில்...` is documented and not externally repaired;
- `in this crisis(!)`, `Have you hanged him!` and final `/` remain preserved;
- scan-boundary comments for scans **6–15** are complete and ordered;
- English body corrections during T4: **0**;
- unresolved T4 blockers: **0**.

Detailed provenance: [`translations/en/TRANSLATION_REVIEW.md`](translations/en/TRANSLATION_REVIEW.md) and [`translations/en/LEXICON.md`](translations/en/LEXICON.md).

### Status-vocabulary rule clarified at T4

The permanent translation guide defines article statuses as `not-started`, `draft`, `fidelity-reviewed`, `voice-reviewed`, and `verified`. Therefore T4 does **not** create an `audited` article metadata status. Article 1 correctly remains `voice-reviewed` after T4 PASS; T5 may advance it to `verified`.

## Current gate sequence

- **T0 — source prerequisite / setup:** COMPLETE / PASS
- **T1 — complete close English draft:** COMPLETE / PASS
- **T2 — bilingual fidelity review:** COMPLETE / PASS
- **T3 — Kalaignar voice review:** COMPLETE / PASS
- **T4 — terminology / quotation / citation / source audit:** **COMPLETE / PASS**
- **T5 — translation verification:** **NEXT**
- **E6 — publication-level English consistency review:** NOT STARTED
- **E7 — English release closeout:** NOT STARTED

## T5 scope

T5 is the final article-level verification gate. It must re-fetch the current article and frozen Tamil authority and confirm that all T0–T4 decisions/provenance remain intact, with no omission, terminology regression, source-bearing smoothing, quotation regression or scan-traceability loss.

## Exact next activity

Execute **T5 — final article translation verification for Article 1 only**:

1. re-fetch live `main`, frozen Tamil authority, English article, lexicon and review ledger;
2. confirm `source_tamil_blob_sha` still equals `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`;
3. verify all T2 fidelity corrections, T3 voice decisions and T4 terminology/source decisions remain present;
4. verify scans 6–15 comments, quotation handling and final `/`;
5. confirm unresolved translation blockers remain zero;
6. only if all checks pass, set `translation_status: verified` and update trackers/plan/README/HANDOVER;
7. make **E6** the next gate;
8. do **not** perform E6 in the same activity.