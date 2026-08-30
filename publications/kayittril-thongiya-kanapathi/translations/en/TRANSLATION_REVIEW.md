# English Translation Review Ledger — கயிற்றில் தொங்கிய கணபதி

Permanent guide: [`../../../../ESSAY_TRANSLATION_GUIDE.md`](../../../../ESSAY_TRANSLATION_GUIDE.md)  
Publication plan: [`../../TRANSLATION_PLAN.md`](../../TRANSLATION_PLAN.md)

## Review rule

A first draft is never automatically verified. Article 1 must pass T0 source confirmation, T1 complete close draft, T2 bilingual fidelity review, T3 Kalaignar-voice review, T4 terminology/quotation/source audit and T5 final verification. The publication must then pass E6 and E7 before English release is closed.

> **Translate the language; do not neutralise the voice.**

## T0 source record — PASSED

- Tamil source layer: **COMPLETE / FROZEN**
- strict source scans: **17 / 17 PASS**
- Tamil article assemblies: **1 / 1 strict-rechecked**
- unresolved Tamil readings: **0**
- translation authority: `../../articles/01-kayittril-thongiya-kanapathi.md`
- frozen Tamil blob SHA: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- article source scans: **6–15**
- T0 result: **PASS**

## T1 complete close draft — PASSED

English article:

[`01-kayittril-thongiya-kanapathi.md`](01-kayittril-thongiya-kanapathi.md)

T1 translated the complete article from scans **6–15**, retained every scan-boundary comment and preserved the quotation-heavy, rhetorical and polemical structure. The file was correctly left at `translation_status: draft` pending T2.

## T2 bilingual fidelity review — COMPLETE / PASSED

The frozen Tamil assembly and current English article were re-fetched from `main`. The English `source_tamil_blob_sha` still matches the frozen Tamil blob:

`b7c6d02cd7bc041318693306b8658e18c3f8fa5b`

T2 compared the article clause by clause for omissions, additions, altered negatives, names/referents, numbers, quotation scope, rhetorical questions, repetitions and scan-boundary traceability.

### Fidelity-driven corrections made in T2

1. `நமது நாட்டு கணபதி` — T1 `our Ganapathi` → **`Ganapathi of our land`**, retaining the source's explicit land/country relation.
2. `பாராள பாரத புத்ரர் வந்தால்` — T1 `once the sons of Bharat came to rule` → **`if the sons of Bharat came to rule`**, restoring the source conditional `வந்தால்`.
3. `கணபதியின் தண்டனை தமிழ் நாட்டிற்கு முக்கியத்துவம் கொடுக்கிறது` — T1 `has a special importance for Tamil Nadu` → **`assumes importance for Tamil Nadu`**, removing the added `special`.
4. scan-9/10 continuation `உணர்` + `வைத் தொடுவதில்லை` = `உணர்வைத் தொடுவதில்லை` — T1 `they do not even begin to feel it` → **`does not touch their sensibility`**, restoring the source's `touch` image.
5. `மங்கு` — T1 `mangu vessels` → **`mangu`**, removing the unsupported added gloss `vessels`.
6. `அவர்தம் ஆத்மா சாந்தி அடைக!` — T1 `May their souls attain peace!` → **`May his soul attain peace!`**, restoring the source honorific/singular construction.
7. `மரணவஸ்தைக்காளாகும்` — T1 `are being driven into mortal peril` → **`are falling into mortal peril`**, removing an added external agent.
8. `ஆலை` — T1 plural `factories` → **`a factory`**, restoring source number.
9. `பெண்தெய்வ மாநாடு` — T1 `women's divine conference` → **`conference of goddesses`**, restoring the source's female-deity meaning.
10. `“அடிப்பியோ? உங்க அப்பன் மவனே! சிங்கண்டா” என்று அடிவாங்கியபிறகு அழுகிற நகைச்சுவைப் பகுதியாக இருக்கிறது` — T2 repositioned the English comic taunt so it is explicitly what the beaten man **cries in the comic bit**, rather than leaving its quotation attachment ambiguous.

A source-aligned full stop was also restored after the scan-9/10 `உணர்வைத் தொடுவதில்லை` sentence in English; the scan-boundary comment remains present.

### Seven T1 watch-items resolved

1. **Title:** `Ganapathi Who Hung from the Rope` is accepted at T2 as a close, concrete rendering. T3 may still assess rhetorical English cadence.
2. **`சுதந்திர பூமியில்...` quote scope:** the frozen Tamil has an opening quotation mark without a clearly matched closing mark before `என மனத்தைத் திடப்படுத்திக்கொண்டோம்`. The English keeps a readable closed quotation. This is an explicitly documented translation-layer regularisation, not a claim that the Tamil punctuation is regular.
3. **`மிகவும் உயர்ந்த நிலையில்...` irregular quote:** T1's contextual rendering was checked against every clause and retained; no new factual claim was found.
4. **`மங்கு`:** unsupported `vessels` removed; source-bearing `mangu` retained without guessed identification.
5. **`அடிப்பியோ? உங்க அப்பன் மவனே! சிங்கண்டா`:** literal colloquial wording retained and its source quotation attachment clarified. T3 is limited to cadence/voice, not source reinterpretation.
6. **`நன்றுக அழு!`:** `Cry well!` retained because it preserves the unusual frozen source rather than silently normalising it.
7. **Final `/`:** retained in the English article. Its formal source-anomaly handling remains a T4 audit item.

### T2 completeness checks

- article paragraphs/clauses: **complete; no omission found**
- added factual claims after T2 corrections: **0 identified**
- altered negatives: **0**
- source names/naming distinctions: **PASS**
- scan-boundary comments scans 6–15: **PASS**
- front matter/ads imported: **No**
- Tamil source changed during T2: **No**
- unresolved T2 fidelity blockers: **0**

**T2 RESULT: PASS.** Article 1 is now `translation_status: fidelity-reviewed`.

## Article review tracker

| # | Tamil title | Translation status | T0 | T1 | T2 | T3 | T4 | T5 |
|---:|---|---|---|---|---|---|---|---|
| 1 | கயிற்றில் தொங்கிய கணபதி | **fidelity-reviewed** | PASS | PASS | **PASS** | — | — | — |

## T3 voice-review watch-list

T3 must now read the English as English while comparing against the frozen Tamil and ask whether fidelity survived without flattening Kalaignar's voice. High-value passages:

- the opening gallows/imperialism blood imagery;
- `Mother Tamil` and gallows dialogue;
- the flower/fragrance argument;
- direct accusations against Tamil land and ministers;
- `Cry well!` repetition;
- Kamaraj ridicule and the colloquial `அடிப்பியோ?...` comic taunt;
- the final separate-Dravidam argument and repeated `They can live. They are going to live.` cadence.

T3 must not change factual content, Tamil readings or source-bearing terms merely to make the prose more polished.

## Current translation questions

- blocking T2 questions: **0**
- T4 source-anomaly item carried forward: final terminal `/`

## Exact next activity

Execute **T3 — Kalaignar voice review for Article 1 only**. Re-fetch the fidelity-reviewed English file and frozen Tamil authority, preserve all T2 factual decisions, and review directness, sarcasm, ridicule, rhetorical questions, repetition, imagery, exclamations and argumentative rhythm. Make only voice/cadence changes that do not alter meaning. Mark `voice-reviewed` only after the full article passes. Do not perform T4 in the same activity.