# P4 source / completeness audit — இன முழக்கம்

Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`  
Physical scans: **50**  
Recorded SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`

## Scope

This is the publication-level **P4 source / completeness audit**. It audits the completed canonical P2 page layer and the six P3 reading assemblies. It is **not** the P5 strict word-by-word / punctuation-by-punctuation visual fidelity pass.

Publication-specific user rule remains controlling:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Accordingly, this audit checks completeness, source order, boundaries, provenance, exclusions and non-regression without silently replacing user-supplied lexical tokens with alternate scan-appearing readings.

## Canonical layer inventory

| Layer | Expected | Present | Result |
|---|---:|---:|---|
| Physical source scans | 50 | 50 | **PASS** |
| Canonical P2 page records | 50 | 50 | **PASS** |
| Contents-listed P3 assemblies | 6 | 6 | **PASS** |
| Duplicate / extra body assemblies | 0 | 0 | **PASS** |

The canonical `pages/` directory runs continuously from scan record `0001` through `0050`, with every source scan represented exactly once.

The canonical `articles/` directory contains exactly:

1. `01-ina-muzhakkam.md` — `இன முழக்கம்` — scans **6–13** — blob `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`;
2. `02-sorgga-logaththil.md` — `சொர்க்க லோகத்தில்` — scans **14–24** — blob `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`;
3. `03-murasaraivai.md` — `முரசறைவாய்` — scans **25–29** — blob `698c178ee5a65e9fe53543be2136e6691f5a8dad`;
4. `04-pazhikku-pazhi.md` — `பழிக்குப் பழி` — scans **30–37** — blob `d9c57a7a55ab33310b512c34322186cc55a04ef8`;
5. `05-aariyam-pesugirathu.md` — `ஆரியம் பேசுகிறது` — scans **38–39** — blob `651063d641ddbc53c1688e92b13d976b169d04ee`;
6. `06-kavithaigal.md` — `கவிதைகள்` — scans **41–49** — blob `a11dfc65bfd83c316e090c793f1ede102a72ac21`.

## Assembly boundary audit

| Assembly | Source-supported start | Source-supported close | P4 result |
|---|---|---|---|
| `இன முழக்கம்` | scan 6 heading/opening | scan 13 close + ornament | **PASS** |
| `சொர்க்க லோகத்தில்` | scan 14 heading/opening | scan 24 article close before promotion | **PASS** |
| `முரசறைவாய்` | scan 25 heading/opening | scan 29 `போர் முரசறைவாய்` + ornament | **PASS** |
| `பழிக்குப் பழி` | scan 30 heading/opening | scan 37 final appeal before promotion | **PASS** |
| `ஆரியம் பேசுகிறது` | scan 38 heading/opening | scan 39 close + ornament | **PASS** |
| `கவிதைகள்` | scan 41 / printed 40 | scan 49 / printed 48 | **PASS** |

No front matter, promotion, poetry-front-matter or catalogue unit is counted as one of the six contents-listed body assemblies.

## Page-continuation / provenance audit

P3 retains source-page comments in source order and preserves the established page-boundary continuations, including:

- scan 6 `காதலுக்காக` → scan 7 `வாழ்வையே...`;
- scan 9 `அல்லலுற்` → scan 10 `றோமே......`;
- scan 11 `என்று` → scan 12 `கேட்டுப் பாருங்கள்...`;
- scan 14 `ஈடுபட்டிருந்` → scan 15 `தார்கள்.`;
- scan 15 `மஞ்சள் நிறத்` → scan 16 `துண்டுத் துணி...`;
- scan 18 Kodpuli testimony → scan 19 continuation;
- scan 19 Iyer speech → scan 20 continuation;
- scan 21 `நாயன்மார்கள்` → scan 22 `ஸ்தம்பித்து விட்டார்கள்.`;
- scan 25 `மணவாளன் மார்பினி` → scan 26 `லே...`;
- scan 28 `குள்ள` → scan 29 `நரிக்...`;
- scan 31 `அதன்` → scan 32 `ஆணிவேர்...`;
- scan 34 clause → scan 35 continuation;
- scan 35 `மூன்று` → scan 36 `குண்டுகளை...`;
- scan 38 `குலச்` → scan 39 `சிறை...`;
- scan 41 poem continuation → scan 42;
- scan 45 `ஏற்படட்டும் பின்,` → scan 46 `பேச்சுக்குத்...`;
- scan 47 `மகன்` → scan 48 `பிறந்த போதும்...`.

**Page-order / provenance result: PASS.**

## Required exclusions audit

- scans **1–5** front matter are absent from all six body assemblies: **PASS**;
- scan **24** `திராவிட சம்பத்து` promotion is absent from `சொர்க்க லோகத்தில்`: **PASS**;
- scan **37** `இரண்டு சிறந்த நாவல்கள்!` promotion is absent from `பழிக்குப் பழி`: **PASS**;
- scan **40** `கவிதைகளைப் பற்றி` + `மதிப்புரை` is absent from `கவிதைகள்`: **PASS**;
- scan **50** catalogue / advertisement is absent from all six body assemblies: **PASS**;
- physical-copy marks / library stamps / handwriting are not imported into article body text: **PASS**.

## User-correction non-regression

Scan 10 retains the user-established misplaced-word correction exactly:

`கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில் கல்லேற்றி...`

`விசயர்` remains a retained supplied lexical token in its corrected source-supported position; it is not deleted or replaced.

**User-correction result: PASS.**

## Contents / printed-page witness audit

The printed contents witness remains independent:

1. `இன முழக்கம்` — `4`
2. `சொர்க்க லோகத்தில்` — `13`
3. `முரசறைவாய்` — `24`
4. `பழிக்குப் பழி` — `29`
5. `ஆரியம் பேசுகிறது` — `37`
6. `கவிதைகள்` — `40`

Heading scans **6, 14, 25, 30 and 38** continue to use no inferred visible printed numeral. Their contents-page start numbers remain separate source witnesses. Scan 41 visibly begins printed page `40` for the poetry body; scan 40 remains separate poetry front matter.

**Contents / page-number witness result: PASS.**

## Poetry assembly audit

`கவிதைகள்` contains scans **41–49** only and retains source page comments and verse lineation. Source-visible poem headings are preserved in order:

1. `நியாயத் திராசு!`
2. `ஏற்றமே!`
3. `சைவரே!`
4. `வா!`
5. `பொதுவுடைமையே!`
6. `யோசித்துப் பார்!`
7. `மாணவர் எழுச்சி.`
8. `வாளிங்கே!`
9. `தோல்வி எப்பொழுது?`
10. `இன்னுமா கூச்சல்?`
11. `வருணமா? மானமா?`

Durable heading-placement decisions remain intact: `வா!` begins scan **43**, and `யோசித்துப் பார்!` begins scan **44**.

**Poetry structure result: PASS.**

## Lexical-normalisation audit

P4 found no evidence that P3 introduced lexical rewriting beyond the user-authorised structural placement rule.

- silent lexical normalisations introduced by P3: **0**;
- user-supplied lexical tokens deliberately retained despite source-witness questions: **retained / deferred to P5**;
- source wording manufactured from context: **0**.

Known deferred source/baseline points remain explicitly open for P5 classification rather than being silently changed here:

1. **cover-author witness** — the scan visibly carries an abbreviated `மு. கருணாநிதி` form while the supplied baseline uses `கலைஞர் கருணாநிதி`; current P2 record preserves the user baseline and documents the differing witness;
2. **scan-50 catalogue** — several author/price lexical or numeric differences/omissions remain deliberately unresolved under the lexical-baseline rule, including the already documented `அழகு நிலா` / `செல்வ குமாரி` price forms and the missing `நாடறிந்த நட்சத்திரங்கள்` price.

These are **not P4 completeness blockers**; they must be explicitly checked and classified in P5.

## P4 checklist result

| Check | Result |
|---|---|
| 50 / 50 physical scans represented by canonical P2 records | **PASS** |
| Six contents-listed assemblies exist exactly once | **PASS** |
| Assembly start/end boundaries agree with page map | **PASS** |
| Page continuations / provenance comments retained | **PASS** |
| Scan-10 `விசயர்` placement | **PASS** |
| Scan-24 promotion excluded from Article 2 | **PASS** |
| Scan-37 promotion excluded from Article 4 | **PASS** |
| Scan-40 author/review matter excluded from poetry body | **PASS** |
| Scan-50 catalogue excluded from body assemblies | **PASS** |
| Poetry headings / lineation agree with P2 | **PASS** |
| Contents-page numbers kept distinct from visible body numerals | **PASS** |
| Physical-copy marks excluded from body text | **PASS** |
| Silent lexical normalisation introduced during P2/P3 | **0** |
| Deferred lexical/number witness issues explicitly classified for P5 | **PASS** |
| P4 `needs-review` items | **0** |
| P4 blocked items | **0** |
| Unresolved body-completeness blockers | **0** |

## P4 result

**P4 SOURCE / COMPLETENESS AUDIT: PASS.**

The Tamil archival structure is complete through P4. P2 remains **50 / 50 VERIFIED**, P3 remains **6 / 6 COMPLETE**, and no completeness blocker was found.

## Exact next activity

Proceed with **P5 strict visual word/punctuation fidelity** over all **50 physical scans**. P5 must re-check every visible printed word, punctuation mark, heading, number, quotation boundary, paragraph continuation, source-witness distinction, promotion/catalogue entry and physical-copy exclusion against the controlling scan under the publication-specific user rule.

P5 must explicitly resolve or classify the deferred cover-author witness and scan-50 catalogue differences without silently replacing the user lexical baseline. Any P5 correction must be propagated to affected page records, P3 assemblies, indexes and status records with provenance.

Do not begin English translation before P5 is complete and the Tamil authority is frozen.