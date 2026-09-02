# இன முழக்கம்

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`  
Physical scans: **50**  
Source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`  
Source PDF committed: **No**

## Source / edition identity

- printed title witnesses: **இன முழக்கம்**
- title-page author: **கலைஞர் கருணாநிதி**
- cover author witness differs in form and is reserved for lexical fidelity review rather than silently normalised during the structural pass
- first edition: **செப்டம்பர் 1951**
- price: **அணா 0-8-0**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- seller: **பாரி நிலையம், 59, பிராட்வே, சென்னை**
- printer: **கே. ஜி. பிரஸ், சென்னை—1**

## User-established rule for this publication

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

The supplied full transcription is therefore the lexical baseline for the current archival pass. The scan controls structure and physical evidence. No lexical word is silently modernised or substituted.

## Publication structure established at intake

Printed contents witness:

1. `இன முழக்கம்` — `4`
2. `சொர்க்க லோகத்தில்` — `13`
3. `முரசறைவாய்` — `24`
4. `பழிக்குப் பழி` — `29`
5. `ஆரியம் பேசுகிறது` — `37`
6. `கவிதைகள்` — `40`

Operational source units:

- scans 1–5 — cover/front matter/contents/publisher preface
- scans 6–13 — `இன முழக்கம்`
- scans 14–24 — `சொர்க்க லோகத்தில்`
- scans 25–29 — `முரசறைவாய்`
- scans 30–37 — `பழிக்குப் பழி`
- scans 38–39 — `ஆரியம் பேசுகிறது`
- scan 40 — `கவிதைகளைப் பற்றி` + `மதிப்புரை`
- scans 41–49 — `கவிதைகள்`
- scan 50 — catalogue / advertisement

Full map: [`indexes/page-map.md`](indexes/page-map.md).  
Contents witness: [`indexes/contents.md`](indexes/contents.md).

## Structural transcription intake — COMPLETE

The user's complete 50-scan transcription has been reassembled against the PDF for source-supported structure without silently changing lexical tokens.

Staging files:

- [`transcription-intake/scans-0001-0020.md`](transcription-intake/scans-0001-0020.md)
- [`transcription-intake/scans-0021-0040.md`](transcription-intake/scans-0021-0040.md)
- [`transcription-intake/scans-0041-0050.md`](transcription-intake/scans-0041-0050.md)
- [`transcription-intake/USER_CORRECTIONS.md`](transcription-intake/USER_CORRECTIONS.md)
- [`STRUCTURAL_REASSEMBLY_REVIEW.md`](STRUCTURAL_REASSEMBLY_REVIEW.md)

Important structural fixes include:

- front-matter edition/price moved to scan 3 and library/handwriting/OCR noise removed from printed text;
- `மாதவி`, `கண்ணகி`, `இளங்கோவடிகள்`, `புலவர் பிசிராந்தையார்`, `வடலூர் இராமலிங்கம்`, `சேரன் செங்குட்டுவன்`, `திருவள்ளுவர்`, `பாரிவள்ளல்` labels restored to their source positions;
- **scan 10 `விசயர்` correction:** retain the misplaced supplied word after `கர்வத்தால் கனத்துப்போன கனக`, yielding `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan-22 trailing `2` removed as non-source transcription noise;
- scan-24 and scan-37 promotional matter separated from article bodies;
- `பழிக்குப் பழி` final lines moved from supplied scan 36 to source scan 37;
- `வா!` moved to scan 43; `யோசித்துப் பார்!` moved to scan 44;
- poetry lineation restored across scans 41–49;
- scan-50 catalogue restored as a structured catalogue rather than running prose.

## P2 canonical page layer — COMPLETE

All **50 / 50** physical scans have canonical records under [`pages/`](pages/) and were directly checked against the controlling PDF for the P2 scope.

P2 decisions now durable:

- printed text is separated from physical-copy marks on every page record;
- visible printed numerals are recorded only when directly visible;
- heading scans **6, 14, 25, 30 and 38** do not receive inferred printed numerals;
- page-to-page word continuations are recorded in audit notes;
- scan 24 and scan 37 article/promotion boundaries are explicit;
- scan 10 preserves the user correction `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 22 trailing `2` remains excluded as non-source noise;
- scan 40 remains poetry introductory/review matter outside the poem body;
- scans 41–49 retain source-supported poem headings and verse lineation;
- scan 50 remains a separate catalogue and does not silently repair lexical/number differences in the supplied baseline.

P2 batch result:

- scans 1–25: **25 / 25 VERIFIED**
- scans 26–50: **25 / 25 VERIFIED**
- total P2: **50 / 50 VERIFIED / COMPLETE**
- blockers: **0**

## P3 article / section assemblies — COMPLETE

The six contents-listed reading assemblies have been created under [`articles/`](articles/) directly from the canonical P2 page layer:

1. [`01-ina-muzhakkam.md`](articles/01-ina-muzhakkam.md) — scans 6–13 — blob `60e5247f54b3c96e66079bf4b34740fa5ccb1ad1`
2. [`02-sorgga-logaththil.md`](articles/02-sorgga-logaththil.md) — scans 14–24 — blob `adff0de00c120e0c737aca0cd0bc9ed6adcaecd1`
3. [`03-murasaraivai.md`](articles/03-murasaraivai.md) — scans 25–29 — blob `698c178ee5a65e9fe53543be2136e6691f5a8dad`
4. [`04-pazhikku-pazhi.md`](articles/04-pazhikku-pazhi.md) — scans 30–37 — blob `d9c57a7a55ab33310b512c34322186cc55a04ef8`
5. [`05-aariyam-pesugirathu.md`](articles/05-aariyam-pesugirathu.md) — scans 38–39 — blob `651063d641ddbc53c1688e92b13d976b169d04ee`
6. [`06-kavithaigal.md`](articles/06-kavithaigal.md) — scans 41–49 — blob `a11dfc65bfd83c316e090c793f1ede102a72ac21`

P3 non-regression checks:

- assemblies were copied from canonical P2 records, not the staging transcription;
- page-boundary comments/provenance are retained;
- scan 10 retains exactly `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 24 `திராவிட சம்பத்து` promotion is excluded from `சொர்க்க லோகத்தில்`;
- scan 37 two-novel promotion is excluded from `பழிக்குப் பழி`;
- scan 40 `கவிதைகளைப் பற்றி` / `மதிப்புரை` author-review matter is excluded from the `கவிதைகள்` body;
- scan 50 catalogue is excluded from all six assemblies;
- every source-visible poetry heading and P2 verse lineation is retained in the poetry assembly;
- no lexical normalisation was introduced during assembly;
- P3 blockers: **0**.

## P4 source / completeness audit — PASS

Audit record: [`SOURCE_COMPLETENESS_AUDIT.md`](SOURCE_COMPLETENESS_AUDIT.md).

P4 confirmed:

- canonical P2 coverage: **50 / 50 physical scans**;
- P3 assemblies: **6 / 6, exactly once**;
- all six source-supported start/end boundaries: **PASS**;
- page-boundary order/provenance: **PASS**;
- scan-10 `விசயர்` placement: **PASS**;
- scan-24 / scan-37 promotions excluded from article bodies: **PASS**;
- scan-40 author/review matter excluded from `கவிதைகள்`: **PASS**;
- scan-50 catalogue excluded from all body assemblies: **PASS**;
- poetry headings and source lineation: **PASS**;
- contents-page number witnesses kept distinct from directly visible body numerals: **PASS**;
- physical-copy marks imported into body text: **0**;
- silent lexical normalisations introduced during P2/P3: **0**;
- P4 `needs-review`: **0**;
- P4 blocked items: **0**;
- completeness blockers: **0**.

Deferred for explicit P5 source-fidelity classification rather than silent correction:

- cover-author witness (`மு. கருணாநிதி` visible witness vs supplied `கலைஞர் கருணாநிதி` baseline);
- scan-50 catalogue lexical/number differences or omissions already documented in the page record.

## Current archival gates

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + physical page map: **COMPLETE**
- structural reassembly of supplied transcription: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 article/section assemblies: **6 / 6 COMPLETE / VERIFIED AGAINST P2**
- P4 source/completeness audit: **PASS / COMPLETE**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

## Non-regression

- do not treat stamps/handwriting as printed text;
- do not silently change user-supplied lexical tokens during archival processing;
- preserve contents/body page-number witnesses separately;
- preserve promotional/catalogue matter outside article bodies;
- preserve poem headings on their actual scans;
- scan 10 must retain `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 37, scan 40 and scan 50 boundaries must not regress;
- lexical disagreements with scan pixels must be explicitly classified during P5 rather than silently corrected.

## Exact next activity

Proceed to **P5 strict visual word/punctuation fidelity** across all **50 physical scans**. Re-check every visible printed word, punctuation mark, heading, number, quotation boundary, paragraph continuation, source-witness distinction, promotion/catalogue entry and physical-copy exclusion against the controlling scan under the user-established lexical rule. Propagate every source-supported P5 correction with provenance to page records, assemblies, indexes and status records. Explicitly classify the deferred cover-author and scan-50 catalogue differences. **Do not begin English translation in the same activity.**