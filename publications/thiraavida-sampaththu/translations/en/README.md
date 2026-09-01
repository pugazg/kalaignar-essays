# English Translation — திராவிட சம்பத்து

Permanent policy: [`../../../../ESSAY_TRANSLATION_GUIDE.md`](../../../../ESSAY_TRANSLATION_GUIDE.md)  
Publication plan: [`../../TRANSLATION_PLAN.md`](../../TRANSLATION_PLAN.md)

> **Translate the language; do not neutralise the voice.**

## Current status

- Tamil source/fidelity prerequisite: **PASSED / FROZEN**
- Tamil articles: **2 / 2 strict-reviewed**
- E0 translation planning/setup: **COMPLETE**
- T0 source prerequisite/setup: **2 / 2 PASS**
- T1 close English drafts: **2 / 2**
- T2 fidelity-reviewed: **2 / 2**
- T3 voice-reviewed: **2 / 2**
- T4 audited: **2 / 2**
- T5 verified: **1 / 2**
- E6 publication consistency review: **NOT STARTED**
- E7 release closeout: **NOT STARTED**
- unresolved translation blockers: **0**

## Article tracker

| # | Tamil article | Frozen Tamil blob | English file | Status | Gates |
|---:|---|---|---|---|---|
| 1 | `திராவிட சம்பத்து` | `6e9759aff9bc4801ee66b3b8c76a814be3e98015` | [`01-thiraavida-sampaththu.md`](01-thiraavida-sampaththu.md) | **verified** | **T0 PASS; T1 PASS; T2 PASS; T3 PASS; T4 PASS; T5 PASS** |
| 2 | `ஐயர் அறிவிக்கிறார்!` | `80b5bfd27953e55255ac4f015c3e7b965ee70ab6` | [`02-aiyar-arivikkirar.md`](02-aiyar-arivikkirar.md) | **voice-reviewed** | **T0 PASS; T1 PASS; T2 PASS; T3 PASS; T4 PASS; T5 next** |

Article 1 English title: **Dravidian Wealth — VERIFIED**.  
Article 2 English title: **Iyer Announces! — T4 audited / final verification pending T5**.

## Translation authority

English uses only the strict-reviewed Tamil assemblies:

1. `../../articles/01-thiraavida-sampaththu.md`
2. `../../articles/02-aiyar-arivikkirar.md`

If a genuine source-supported Tamil correction changes either frozen blob, the affected English gates must reopen explicitly.

## Article 1 final verified state

- T1 baseline blob: `bb5937921ab00d532d91bc89c5a9df57dc8acaa2`
- T2 fidelity-reviewed blob: `155299ac2b71b0aaba431f63d3c882191a3c710b`
- T3 voice-reviewed blob: `1d2e7dae1c00200ab402fa43722167e73e8568a4`
- T4 terminology/source-audited blob: `961ca3f724238ed699dba2607fa2d1be681f0ec4`
- T5 final verified blob: `10dca72882043db491fe8c6ad3f858bc4c9c584f`
- metadata status: `verified`
- T5 body corrections: **0**

## Article 2 T4 source-audited state

- frozen Tamil authority: `80b5bfd27953e55255ac4f015c3e7b965ee70ab6`
- T1 English draft blob: `1b70952ae377668162fcb35eb045e142a0597190`
- T2 fidelity-reviewed English blob: `b7361d26a711d61938da24d33b3512ddf5653e53`
- T3 voice-reviewed English blob: `ace9ff13b1c45bfe6d7c4c99571bc9b9b7b7ac7c`
- T4 source-audited English blob: `9b2795e6c66dea08fdf46fcf7903550001e1a401`
- metadata status: `voice-reviewed` — T5 alone may set `verified`
- source-page comments: scans **12, 3 — 2 / 2 present and ordered**
- title: **Iyer Announces! — T4 audited**
- damaged/ambiguous frozen `அயம்`: **ayam**, unrepaired
- `ஐயர்` / `அய்யர்`: **Iyer / Ayyar**, distinction retained
- `ஏனோதானோ` / `ஏனோதானோக்கள்`: **Enothano / Enothanos**, source-bearing ridicule retained
- normal `கல்லூரி`: **College**; frozen anomalous `கல்லுரி`: **kalluri**
- narrative fused `சாமிநாதய்யர்`: **Saminathayyar**; inscription `சாமிநாத அய்யர்`: **Saminatha Ayyar**
- inscription: **Maha Mahopadhyaya Dravida Vidya Bhushana Dr. Saminatha Ayyar**; no outside version imported
- first-paragraph irregular quotation punctuation: two evident English quoted units retained and formally documented at T4
- T4 English body corrections: **0**
- T4 metadata/provenance updates: **1**
- frozen Tamil body changes: **0**
- unresolved T4 blockers: **0**

Full provenance: [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md).  
Living terminology decisions: [`LEXICON.md`](LEXICON.md).

## Source-sensitive non-regression

- physical-source tears remain genuine source loss; never reconstruct hidden wording in English;
- retain source-page comments in every English article;
- translate the frozen Tamil witness, not alternate scan-appearing lexical forms recorded during P5;
- frozen anomalous `பேச்சுல` remains verified as Article 1 source-bearing `pechchul`;
- frozen scan-3 `அயம்` remains ambiguous and may not be silently repaired in Article 2;
- frozen scan-3 `கல்லுரி` must not be silently normalised during Article 2 review;
- preserve `ஐயர்` / `அய்யர்` and `சாமிநாதய்யர்` / `சாமிநாத அய்யர்` source-form distinctions established through T4;
- preserve T3 voice changes and T4 source/quotation decisions; do not use T5 for stylistic polishing;
- `மன்றத்தில்`, `முக்கிய குறிப்பு` and scan-4 advertisements remain outside the two Kalaignar article translations.

## Gate legend

- **T0** — strict-reviewed Tamil source prerequisite confirmed + blob SHA recorded
- **T1** — complete close English draft
- **T2** — bilingual fidelity review
- **T3** — Kalaignar voice review
- **T4** — terminology / quotation / citation / source audit
- **T5** — translation verified
- **E6** — publication-level English consistency review
- **E7** — English release closeout

## Exact next activity

Execute **Article 2 T5 — final article verification** against frozen Tamil blob `80b5bfd27953e55255ac4f015c3e7b965ee70ab6` and T4 source-audited English blob `9b2795e6c66dea08fdf46fcf7903550001e1a401`.

Re-verify complete surviving coverage, title **Iyer Announces!**, all T4-established terminology/source-bearing forms, the documented first-paragraph quotation treatment, final inscription wording, metadata and both source-page comments. If PASS, set `translation_status: verified` and record the final verified English blob.

**Stop after Article 2 T5. Do not perform E6 in the same activity.**