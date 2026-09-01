# English Translation Plan — திராவிட சம்பத்து

Publication: `திராவிட சம்பத்து`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/thiraavida-sampaththu/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## Objective

Translate the two frozen Kalaignar article assemblies into readable English while preserving direct address, sarcasm, ridicule, rhetorical questions, repetitions, exclamations, ideological vocabulary, source-chosen labels, quotation structure and the pamphlet's deliberately polemical cadence.

English must translate the **frozen strict-reviewed Tamil assemblies**, not OCR, the user-supplied pre-P5 transcription, memory, alternate scan-appearing lexical readings or later editions.

## Tamil source prerequisite — PASSED / FROZEN

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **16 / 16 COMPLETE**
- P3 article assemblies: **2 / 2 COMPLETE**
- P4 source/completeness audit: **PASS**
- P5 strict visual fidelity: **16 / 16 PASS**
- Tamil archival layer: **COMPLETE / STRICT-REVIEWED / FROZEN**
- unresolved workflow blockers: **0**

Frozen translation authorities:

1. `articles/01-thiraavida-sampaththu.md` — `திராவிட சம்பத்து` — scans **5–6, 13–16** — blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.
2. `articles/02-aiyar-arivikkirar.md` — `ஐயர் அறிவிக்கிறார்!` — scans **12, 3** — blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`.

If either frozen Tamil blob changes because of a genuine source-supported correction, all affected downstream English gates must explicitly reopen.

## E0 — planning / setup — COMPLETE

E0 established the English workspace, living lexicon, translation-review ledger and article tracker. Both frozen Tamil assemblies were re-fetched from live `main`, confirmed `status: strict-reviewed`, and registered as the T0 source authorities above.

## Article tracker

| # | Tamil title | English file | Translation status | Gates |
|---:|---|---|---|---|
| 1 | `திராவிட சம்பத்து` | [`translations/en/01-thiraavida-sampaththu.md`](translations/en/01-thiraavida-sampaththu.md) | **draft** | **T0 PASS; T1 PASS; T2 next** |
| 2 | `ஐயர் அறிவிக்கிறார்!` | `translations/en/02-aiyar-arivikkirar.md` | **not-started** | **T0 PASS** |

Article 1 working English title: **Dravidian Wealth**. The title is not frozen and remains subject to T2/T4 review.

## Article 1 T1 — COMPLETE / PASS

T1 created a complete close English draft from frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.

T1 draft blob: `06958bc15d198de42eb63f5a2cb33b64453134cc`.

The draft preserves:

- every surviving Tamil paragraph in order;
- source-page comments for scans **5, 6, 13, 14, 15, 16**;
- opening `*` and all source section boundaries;
- direct address, sarcasm, ridicule, rhetorical questions, exclamations and repeated imagery;
- quotation structure;
- scan-15/16 `SOURCE DAMAGE` positions and visibly incomplete wording without contextual reconstruction;
- frozen source-bearing Tamil choices, including the scan-16 anomaly `பேச்சுல`, carried provisionally as `pechchul` rather than silently repaired.

T1 made **0 changes to the frozen Tamil source**. It is a close draft only and has not yet passed bilingual fidelity review.

## Publication-specific translation constraints

1. Preserve the permanent principle: **Translate the language; do not neutralise the voice.**
2. Preserve the distinction between source labels and generic explanation. Do not replace `விகடனார்`, `நகைச்சுவை குரங்கார்`, `ஆரிய ஆஞ்சநேயர்`, `ஏனோதானோ` or similar polemical forms with detached academic prose.
3. Preserve direct commands and direct address as commands/direct address.
4. Preserve quotation boundaries and the source's repeated rhetorical punctuation where meaningful.
5. Preserve every Tamil source-page boundary in the English articles using comments such as `<!-- Tamil source: scan 5 -->`.
6. Preserve documented `SOURCE DAMAGE` positions. Do **not** translate or reconstruct wording physically absent from the surviving copy.
7. Translate from the frozen Tamil lexical witness even where P5 recorded a scan/baseline conflict. In particular, do not silently substitute scan-appearing `கல்லூரி`, `கண்ணை` or `பேச்சை` for frozen `கல்லுரி`, `கண்னை` or `பேச்சுல`.
8. Scan-3 frozen `அயம்` is damaged/ambiguous. Article 2 T1 must not guess a repaired Tamil word; use a source-bearing English strategy and record it in the review ledger if necessary.
9. Scan-4 advertisement material is outside both Kalaignar article bodies and is not to be imported into either English article.
10. Publisher foreword `மன்றத்தில்` and publisher note `முக்கிய குறிப்பு` remain outside the two article translations unless a later activity explicitly creates separate translated front/back-matter records.

## Terminology / voice state after Article 1 T1

The living lexicon now records working Article 1 choices including:

- `திராவிடம்` → **Dravidam**;
- `திராவிடர்` → **Dravidians**;
- adjectival `திராவிட` → **Dravidian**;
- `திராவிட சம்பத்து` → working **Dravidian Wealth**;
- `ஆனந்த விகடன்` → **Ananda Vikatan**;
- `விகடனார்` → **Vikatanar**;
- `நகைச்சுவை குரங்கார்` → **Comedy Monkey**;
- `ஆரிய ஆஞ்சநேயர்` → **Aryan Anjaneyar**;
- `இனவெறி` / `இனப்பற்று` → **racial hatred** / **attachment to one's race**;
- `ஆப்பசைத்த குரங்கு` → **wedge-meddling monkey**;
- `குப்பை மேட்டுக் குயில்கள்` → **cuckoos of the garbage heap**;
- frozen anomalous `பேச்சுல` → provisional source-bearing **pechchul**.

These are **not release-frozen at T1**. T2 must test them for semantic fidelity; T3 for voice; T4 for terminology/source handling.

## Gate sequence

For each article:

- **T0** — strict-reviewed Tamil source prerequisite + blob SHA — **2 / 2 PASS**
- **T1** — complete close English draft — **1 / 2 PASS**
- **T2** — bilingual fidelity review — **0 / 2**
- **T3** — Kalaignar voice review — **0 / 2**
- **T4** — terminology / quotation / citation / source audit — **0 / 2**
- **T5** — final article verification — **0 / 2**

After both articles reach T5:

- **E6** — publication-wide English consistency review
- **E7** — English release closeout

## Exact next activity

Execute **Article 1 T2 — bilingual fidelity review** from frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015` against T1 draft blob `06958bc15d198de42eb63f5a2cb33b64453134cc`.

Compare every paragraph and clause for omissions, additions, logic, negatives, comparisons, names, quotations, repetitions, page-boundary comments and source-damage handling. Make only fidelity-required English corrections, record them in `translations/en/TRANSLATION_REVIEW.md`, update `translations/en/LEXICON.md` where necessary, and stop after T2.

Do **not** perform T3 in the same activity.