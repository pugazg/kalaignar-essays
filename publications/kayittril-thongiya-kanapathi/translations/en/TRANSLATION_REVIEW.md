# English Translation Review Ledger — கயிற்றில் தொங்கிய கணபதி

Permanent guide: [`../../../../ESSAY_TRANSLATION_GUIDE.md`](../../../../ESSAY_TRANSLATION_GUIDE.md)  
Publication plan: [`../../TRANSLATION_PLAN.md`](../../TRANSLATION_PLAN.md)  
Release report: [`RELEASE_REPORT.md`](RELEASE_REPORT.md)

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

## T1 complete close draft — PASSED

The complete article was translated from scans **6–15**, every scan-boundary comment was retained, and the English file was left at `translation_status: draft` pending review.

## T2 bilingual fidelity review — PASSED

T2 compared the English clause by clause against the frozen Tamil and corrected only fidelity defects. Important T2 corrections included:

- `நமது நாட்டு கணபதி` → `Ganapathi of our land`;
- `பாராள பாரத புத்ரர் வந்தால்` → `if the sons of Bharat came to rule`;
- removal of unsupported `special` from the Tamil-Nadu-importance sentence;
- scan-9/10 `உணர்வைத் தொடுவதில்லை` → `does not touch their sensibility`;
- `மங்கு` retained as source-bearing `mangu`, removing unsupported `vessels`;
- `அவர்தம் ஆத்மா சாந்தி அடைக!` → `May his soul attain peace!`;
- removal of an added agent from `மரணவஸ்தைக்காளாகும்`;
- source singular `ஆலை` → `a factory`;
- `பெண்தெய்வ மாநாடு` → `conference of goddesses`;
- the Kamaraj comic-taunt quotation attachment clarified without changing its wording.

The irregular source quotation beginning `சுதந்திர பூமியில்...` remains documented; English uses readable quotation closure. Final `/` remained preserved for formal source audit.

## T3 Kalaignar voice review — PASSED

T3 re-read the complete fidelity-reviewed English article against the frozen Tamil while preserving every T2 factual/source-bearing decision. Meaning-neutral cadence corrections included:

1. `caught and destroyed between its cruel teeth` → **`caught between its cruel teeth and destroyed`**;
2. `How many people die every day in the world.` → **`So many people die every day in the world.`**;
3. flower-argument grammar tightened to **`A flower blooms and withers away—these are the examples...`**;
4. **`This is what rings out, with fervour, in Ganapathi's loud voice.`**;
5. Kamaraj sentence tightened to **`cannot find enough days or hours...`**;
6. **`a tragic serial in the life of the Tamils`**;
7. final **`a separate Dravidam`** and **`self-respect will bloom and flourish`** cadence.

T3 retained the title, `Cry well!`, `mangu`, `Mukari`, `Dravidam`, `Achariyar`, `Dravidar Kazhagam`, cultural terms, the Kamaraj comic taunt, `Have you hanged him!`, source quotation notes and final `/`.

## T4 terminology / quotation / citation / source audit — PASSED

T4 formally audited terminology consistency, proper names/referents, political labels, cultural/source-bearing terms, quotation boundaries, source punctuation anomalies, scan traceability and the final terminal `/`.

Key T4 findings:

- `தூக்குமேடை` → **the gallows**;
- `ஏகாதிபத்தியம்` → **imperialism**;
- `திராவிடம்` / `திராவிடர்` → **Dravidam / Dravidians**;
- `தமிழ்த்தாய்` → **Mother Tamil**;
- `காமன் வெல்த்` → **Commonwealth**;
- `திராவிடர் கழகம்` → **Dravidar Kazhagam**;
- `ஆச்சாரியார்` → **Achariyar**, without outside identity substitution;
- source `ஜவகர்` remains **Jawahar** while source `நேரு` remains **Nehru**;
- source `இராணி` remains source-bearing **Rani**;
- `mangu`, `Mukari`, `adhirasam`, `akkāra vadisal`, and `pallu` remain restrained/source-bearing;
- irregular quotation scope around `சுதந்திர பூமியில்...` is documented while English uses readable closure;
- irregular `மிகவும் உயர்ந்த நிலையில்...` quotation syntax is documented without importing an outside version;
- `நெருக்கடியில்(!)` remains **`in this crisis(!)`**;
- `தூக்குபோட்டுவிட்டீர்களா!` remains **`Have you hanged him!`**;
- final `அளிக்குமாக /` remains **`May Ganapathi's murder give the Dravidians this resolve /`**.

T4 made **0 English body-text corrections** and left **0 unresolved audit blockers**.

### T4 status-vocabulary finding

The permanent `ESSAY_TRANSLATION_GUIDE.md` defines article statuses as `not-started`, `draft`, `fidelity-reviewed`, `voice-reviewed`, and `verified`. It does not define `audited`. T4 therefore remained a gate result while article metadata stayed `voice-reviewed` until T5.

## T5 final article translation verification — COMPLETE / PASSED

T5 re-fetched live `main`, the frozen Tamil authority, current English article, lexicon and this review ledger.

### T5 verification results

- live frozen Tamil article blob SHA: **`b7c6d02cd7bc041318693306b8658e18c3f8fa5b`** — unchanged;
- English `source_tamil_blob_sha`: **matches frozen Tamil authority**;
- all T2 fidelity corrections listed above remain present: **PASS**;
- all T3 meaning-neutral voice decisions remain present without factual drift: **PASS**;
- all T4-audited terminology, names/referents and source-bearing decisions remain consistent: **PASS**;
- scan-boundary comments for scans **6–15** remain complete and ordered: **PASS**;
- scan 6 still records **no visible printed numeral**: **PASS**;
- irregular `சுதந்திர பூமியில்...` quotation handling remains documented and not misrepresented as regular Tamil punctuation: **PASS**;
- irregular Ganapathi-letter quotation remains translation-layer contextual rendering only: **PASS**;
- `in this crisis(!)` and `Have you hanged him!` remain intact: **PASS**;
- final `/` remains intentionally preserved: **PASS**;
- front matter / `பதிப்புரை` / advertisements imported into English body: **No**;
- Tamil source changed during T5: **No**;
- English body changed during T5: **No**; only metadata status advanced;
- unresolved translation blockers: **0**.

**T5 RESULT: PASS.** Article 1 is `translation_status: verified`.

## Article review tracker

| # | Tamil title | Translation status | T0 | T1 | T2 | T3 | T4 | T5 |
|---:|---|---|---|---|---|---|---|---|
| 1 | கயிற்றில் தொங்கிய கணபதி | **verified** | PASS | PASS | PASS | PASS | PASS | **PASS** |

## E6 — publication-level English consistency review — COMPLETE / PASSED

E6 was performed against live `main` after Article 1 had passed T5. This publication contains one article, so the publication-level review tested consistency across the verified article, its metadata, the publication lexicon, the review ledger and translation plan rather than across multiple article bodies.

### E6 repository/source checks

- verified English article blob reviewed: **`bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`**;
- frozen Tamil source blob: **`b7c6d02cd7bc041318693306b8658e18c3f8fa5b`** — unchanged;
- English `source_tamil_blob_sha` still matches the frozen Tamil authority: **PASS**;
- article metadata remains `translation_status: verified`: **PASS**;
- article count: **1 / 1 verified**.

### E6 publication-wide consistency findings

- title style: **PASS** — `Ganapathi Who Hung from the Rope` remains the verified title and matches the source's concrete rope/hanging image;
- repeated ideological vocabulary: **PASS** — `imperialism`, `Dravidam`, `Dravidians`, `Mother Tamil`, `Commonwealth`, and `Dravidar Kazhagam` remain consistent;
- names/referents: **PASS** — `Ganapathi`, `Kamaraj`, `Jawahar`, `Nehru`, `Patel`, `Veerasenan`, `Sambasivam`, `Sargunam`, `Achariyar`, and other recorded names agree with the lexicon; source `Jawahar` and `Nehru` remain intentionally distinct;
- source-bearing/cultural terms: **PASS** — `mangu`, `Rani`, `Mukari`, `adhirasam`, `akkāra vadisal`, and `pallu` remain restrained and are not externally expanded;
- rhetorical/voice consistency: **PASS** — direct address, repeated questions, commands, sarcasm, ridicule, physical gallows/blood imagery, exclamations and the final Dravidam crescendo remain intact;
- quotation handling: **PASS** — the documented irregular `சுதந்திர பூமியில்...` quotation and irregular Ganapathi-letter syntax remain treated as translation-layer anomalies rather than silently normalised Tamil;
- punctuation/source anomalies: **PASS** — `in this crisis(!)`, `Have you hanged him!`, and final `/` remain unchanged and documented;
- scan traceability: **PASS** — scan-boundary comments for scans **6–15** remain complete and ordered, with scan 6 explicitly unnumbered;
- source boundaries: **PASS** — no cover/front matter, `பதிப்புரை`, blank-page or advertisement material entered the English article;
- external additions: **0** — no outside identification, published English quotation, explanatory gloss or research citation has been inserted into the body.

### E6 corrections to English body

**None.**

### E6 unresolved items

**None.**

**E6 RESULT: PASS.**

## E7 — English release closeout — PASSED / COMPLETE

E7 re-fetched live release-facing state and verified:

- verified English article exists at the recorded path: **PASS**;
- English article blob reviewed: **`bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`**;
- English metadata remains `translation_status: verified`: **PASS**;
- live Tamil authority remains **`b7c6d02cd7bc041318693306b8658e18c3f8fa5b`**;
- English `source_tamil_blob_sha` exactly matches that Tamil blob: **PASS**;
- article counts/statuses agree across tracker, plan and review ledger: **PASS — 1 / 1 verified**;
- T0–T5 and E6 gate statuses agree: **PASS**;
- source/advertisement boundaries remain unchanged: **PASS**;
- the recursive pre-E7 tree `06b72c1c4239f1e5efb0add19c167a7e18373580` contains **no `.pdf` file**: **PASS**;
- source-bearing decisions and documented source anomalies remain intact: **PASS**;
- English body changed during E7: **No**;
- Tamil body changed during E7: **No**;
- unresolved release blockers: **0**.

Full release provenance and the final English/Tamil SHA matrix are recorded in [`RELEASE_REPORT.md`](RELEASE_REPORT.md).

**E7 RESULT: PASS / COMPLETE. ENGLISH RELEASE GATE CLOSED.**

## Final translation state

- Article 1: **verified**
- verified articles: **1 / 1**
- T0–T5: **PASSED**
- E6: **PASSED**
- E7: **PASSED / COMPLETE**
- unresolved translation/release blockers: **0**
- English translation: **COMPLETE**
- English release gate: **CLOSED**

## Next activity

Do **not** reopen this released publication for stylistic polishing. The next normal project activity is **P0 intake of the next supplied Kalaignar essay/article publication**. Reopen Publication 2 only if a genuine source-supported or release-blocking defect is discovered.