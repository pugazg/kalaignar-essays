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

All **50 / 50** physical scans now have canonical records under [`pages/`](pages/) and have been directly checked against the controlling PDF for the P2 scope.

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

## Current archival gates

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + physical page map: **COMPLETE**
- structural reassembly of supplied transcription: **COMPLETE / STAGING**
- P2 canonical page records: **50 / 50 VERIFIED / COMPLETE**
- P3 article/section assemblies: **0 / 6**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

## Non-regression

- do not treat stamps/handwriting as printed text;
- do not silently change user-supplied lexical tokens during archival processing;
- preserve contents/body page-number witnesses separately;
- preserve promotional/catalogue matter outside article bodies;
- preserve poem headings on their actual scans;
- scan 10 must retain `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
- scan 37, scan 40 and scan 50 boundaries must not regress;
- lexical disagreements with scan pixels belong to later source-fidelity review and must be documented rather than silently corrected.

## Exact next activity

Proceed to **P3 article/section assembly** from the verified P2 page layer. Create the six contents-listed reading assemblies — `இன முழக்கம்`, `சொர்க்க லோகத்தில்`, `முரசறைவாய்`, `பழிக்குப் பழி`, `ஆரியம் பேசுகிறது`, and `கவிதைகள்` — preserving page-boundary comments, source wording, the scan-10 `விசயர்` correction, article/promotion exclusions, and poem headings/lineation. Do not begin P4 in the same activity.