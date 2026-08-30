# English Release Report — கயிற்றில் தொங்கிய கணபதி

Release gate: **E7 — English release closeout**  
Release date: **2026-08-30**  
Repository: `pugazg/kalaignar-essays`  
Branch: `main`

## Result

**E7 PASSED. ENGLISH RELEASE GATE CLOSED.**

The single English article remains `translation_status: "verified"`, points to the current frozen Tamil article blob, and has already passed T0–T5 plus the publication-level E6 consistency review. No release blocker was found.

No Tamil or English article body was changed during E7.

## Release prerequisites

| Check | Result |
|---|---|
| Tamil physical scan records | **17 / 17 COMPLETE** |
| Strict visual word/punctuation fidelity | **17 / 17 PASS** |
| Tamil article assemblies | **1 / 1 COMPLETE / FROZEN** |
| Unresolved Tamil fidelity items | **0** |
| English drafts | **1 / 1** |
| T2 fidelity-reviewed | **1 / 1** |
| T3 voice-reviewed | **1 / 1** |
| T4 audited | **1 / 1** |
| T5 verified | **1 / 1** |
| E6 publication-level consistency | **PASSED** |
| Unresolved translation questions | **0** |
| Source PDF in Git repository | **No** |
| E7 release blockers | **0** |

## Repository state reviewed for E7

E7 was performed against live `main` at commit:

`69f353e07d7bc5a525416e8444408b7f1611e584`

The recursive Git tree reviewed had tree SHA:

`06b72c1c4239f1e5efb0add19c167a7e18373580`

Release-facing records fetched fresh from `main` before E7 closeout included:

| Record | Pre-E7 blob SHA |
|---|---|
| root `README.md` | `617dce37b14a6bf5bb97241bc6736bd422655f53` |
| root `HANDOVER.md` | `5e9484f6815da51380febfb52836ebb02164c6b7` |
| publication `README.md` | `10087bbf7aeac9dff0c94f33cdedf17a8d83e274` |
| `TRANSLATION_PLAN.md` | `79baef54c6e0425ef3e5b328b7def296e8b43a7f` |
| `PUBLICATION_COMPLETION_REVIEW.md` | `efdd26444f56290eb0c2d648aaf1b7f5b83b033b` |
| `VISUAL_TEXT_FIDELITY_REVIEW.md` | `7d81f157dce40676de0250faa768d2759dd3044f` |
| `metadata/source.md` | `cc39b0903bc7ea5e17df6230e9700efca88be44c` |
| `indexes/page-map.md` | `cfb9789c32cbeff8afd5843bd710dfb91d9a0223` |
| English tracker `README.md` | `30078153aad0c82663bee99f8d48f4273ef4c48f` |
| `LEXICON.md` | `850d357bf95ba58706c1b288a3a0154f4c76956f` |
| `TRANSLATION_REVIEW.md` | `92cedcc68c9b9ec15ccdbabac738586b04f0bed8` |

The recursive repository tree contains **no `.pdf` file**. The controlling source PDF therefore remains outside GitHub as required.

## Released English article

| # | English file | English blob SHA reviewed | Frozen Tamil source SHA | Status |
|---:|---|---|---|---|
| 1 | `01-kayittril-thongiya-kanapathi.md` | `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba` | `b7c6d02cd7bc041318693306b8658e18c3f8fa5b` | verified |

The English front-matter `source_tamil_blob_sha` exactly matches the current frozen Tamil article blob.

## Link and tracker checks

- the English file listed by `translations/en/README.md` exists;
- its linked Tamil `source_tamil` article exists;
- the English front-matter status remains `verified`;
- the English `source_tamil_blob_sha` matches the current Tamil blob;
- tracker, plan and review ledger agree on **1 / 1 T5**, **E6 PASSED**, and **0 unresolved blockers**;
- the publication/root records point to the same Publication 2 workspace and release state.

## Source-boundary / non-regression checks

E7 reconfirmed that release bookkeeping has not altered the frozen source or verified English decisions:

- scans **1–5** remain front matter, with scan 4 `பதிப்புரை` and scan 5 blank;
- scans **6–15** remain the single article; scan 6 has no visible printed numeral and scans 7–15 carry printed pages 6–14;
- scans **16–17** remain advertisements/promotional matter outside the article body;
- the earlier false assistant readings remain withdrawn; frozen Tamil is unchanged;
- source `Jawahar` versus `Nehru` remains intentionally distinct in English;
- `Achariyar`, `mangu`, `Rani`, `Mukari`, `adhirasam`, `akkāra vadisal`, `pallu`, `Cry well!`, `in this crisis(!)`, `Have you hanged him!`, and final `/` remain release-frozen source-bearing decisions;
- the irregular `சுதந்திர பூமியில்...` quotation scope and irregular Ganapathi-letter syntax remain documented rather than silently normalised;
- all English scan-boundary comments for scans **6–15** remain present and ordered.

## Voice / translation release rule

The released English layer remains governed by:

> **Translate the language; do not neutralise the voice.**

E7 does not reopen verified prose for stylistic polishing. Future bookkeeping must not soften Kalaignar's direct address, questions, commands, sarcasm, ridicule, political labels, exclamations, physical imagery or argumentative rhythm.

## Blockers

**None.**

## Final release state

- Tamil archival layer: **COMPLETE / FROZEN**
- English article translations: **1 / 1 VERIFIED**
- T0–T5: **PASSED**
- E6: **PASSED**
- E7: **PASSED / COMPLETE**
- English translation: **COMPLETE**
- English release gate: **CLOSED**
- unresolved release or translation questions: **0**

Publication 2 is now frozen. Do not reopen `கயிற்றில் தொங்கிய கணபதி` unless a genuine source-supported or release-blocking defect is discovered. The next normal project activity is **P0 intake of the next supplied Kalaignar essay/article publication**.