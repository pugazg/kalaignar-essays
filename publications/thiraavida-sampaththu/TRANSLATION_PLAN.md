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

No English article body was drafted during E0.

## Article tracker

| # | Tamil title | English file | Translation status | Gates |
|---:|---|---|---|---|
| 1 | `திராவிட சம்பத்து` | `translations/en/01-thiraavida-sampaththu.md` | **not-started** | **T0 PASS; T1 next** |
| 2 | `ஐயர் அறிவிக்கிறார்!` | `translations/en/02-aiyar-arivikkirar.md` | **not-started** | **T0 PASS** |

English titles remain **unfrozen** until the relevant article reaches translation review. Do not choose a smoother title by ignoring the source's rhetorical function.

## Publication-specific translation constraints

1. Preserve the permanent principle: **Translate the language; do not neutralise the voice.**
2. Preserve the distinction between source labels and generic explanation. Do not replace `விகடனார்`, `நகைச்சுவை குரங்கார்`, `ஆரிய ஆஞ்சநேயர்`, `ஏனோதானோ` or similar polemical forms with detached academic prose.
3. Preserve direct commands and direct address as commands/direct address.
4. Preserve quotation boundaries and the source's repeated rhetorical punctuation where meaningful.
5. Preserve every Tamil source-page boundary in the English articles using comments such as `<!-- Tamil source: scan 5 -->`.
6. Preserve documented `SOURCE DAMAGE` positions. Do **not** translate or reconstruct wording physically absent from the surviving copy.
7. Translate from the frozen Tamil lexical witness even where P5 recorded a scan/baseline conflict. In particular, do not silently substitute scan-appearing `கல்லூரி`, `கண்ணை` or `பேச்சை` for frozen `கல்லுரி`, `கண்னை` or `பேச்சுல`.
8. Scan-3 frozen `அயம்` is damaged/ambiguous. T1 must not guess a repaired Tamil word; use a source-bearing English strategy and record it in the review ledger if necessary.
9. Scan-4 advertisement material is outside both Kalaignar article bodies and is not to be imported into either English article.
10. Publisher foreword `மன்றத்தில்` and publisher note `முக்கிய குறிப்பு` remain outside the two article translations unless a later activity explicitly creates separate translated front/back-matter records.

## Initial terminology / voice setup

The living lexicon begins with conservative source-bearing decisions rather than exhaustive pre-translation normalisation:

- `திராவிடம்` → **Dravidam** when used as the source political/civilisational noun;
- `திராவிடர்` → **Dravidians**;
- adjectival `திராவிட` → contextual **Dravidian** where English grammar requires an adjective;
- adjectival `ஆரிய` → **Aryan**; do not broaden into a different ideological label without source support;
- `ஆனந்த விகடன்` → **Ananda Vikatan**;
- `மகிஷாசுரமர்த்தனி` → **Mahishasura Mardini** unless a source-specific reason during T1–T4 requires another rendering;
- source-specific mock labels / insults remain rhetorically marked; exact English wording is established article by article during T1–T4;
- `ஐயர்` / `அய்யர்` source-form variation must not be mechanically homogenised before context review.

The article title `திராவிட சம்பத்து`, the Article 2 title `ஐயர் அறிவிக்கிறார்!`, and difficult compounds such as `ஆரிய சம்பத்து` remain subject to contextual T1/T2/T4 review before final English forms are frozen.

## Gate sequence

For each article:

- **T0** — strict-reviewed Tamil source prerequisite + blob SHA — **2 / 2 PASS**
- **T1** — complete close English draft
- **T2** — bilingual fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation / source audit
- **T5** — final article verification

After both articles reach T5:

- **E6** — publication-wide English consistency review
- **E7** — English release closeout

## Exact next activity

Execute **T1 — complete close English draft for Article 1 `திராவிட சம்பத்து` only** from frozen Tamil blob `6e9759aff9bc4801ee66b3b8c76a814be3e98015`.

Create `translations/en/01-thiraavida-sampaththu.md`, translate every surviving Tamil paragraph in order, preserve source-page comments for scans **5, 6, 13, 14, 15, 16**, retain explicit source-damage gaps without reconstruction, and update the tracker / lexicon / review ledger / root handover.

Stop after Article 1 T1. Do **not** perform T2 in the same activity.