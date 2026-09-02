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

The supplied full transcription is therefore the lexical baseline for the current pass. The scan controls structure and physical evidence. No lexical word is silently modernised or substituted in this structural phase.

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
- [`transcription-intake/USER_CORRECTIONS.md`](transcription-intake/USER_CORRECTIONS.md) — user-authorised corrections that supersede conflicting staging notes during P2 transfer
- [`STRUCTURAL_REASSEMBLY_REVIEW.md`](STRUCTURAL_REASSEMBLY_REVIEW.md)

Important structural fixes include:

- front-matter edition/price moved to scan 3 and library/handwriting/OCR noise removed from printed text;
- `மாதவி`, `கண்ணகி`, `இளங்கோவடிகள்`, `புலவர் பிசிராந்தையார்`, `வடலூர் இராமலிங்கம்`, `சேரன் செங்குட்டுவன்`, `திருவள்ளுவர்`, `பாரிவள்ளல்` labels restored to their source positions;
- scan 10 `விசயர்` is **not noise**: the user corrected its placement to `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`; this correction supersedes the earlier removal decision;
- scan-22 trailing `2` removed as non-source transcription noise;
- scan-24 and scan-37 promotional matter separated from article bodies;
- `பழிக்குப் பழி` final lines moved from supplied scan 36 to source scan 37;
- `வா!` moved to scan 43; `யோசித்துப் பார்!` moved to scan 44;
- poetry lineation restored across scans 41–49;
- scan-50 catalogue restored as a structured catalogue rather than running prose.

## Current archival gates

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + contents + physical page map: **COMPLETE**
- structural reassembly of supplied transcription: **COMPLETE / STAGING**
- P2 canonical page records: **0 / 50**
- P3 article/section assemblies: **0 / 6**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**

## Non-regression

- do not treat stamps/handwriting as printed text;
- do not silently change user-supplied lexical tokens during structural processing;
- apply `transcription-intake/USER_CORRECTIONS.md` during P2 transfer; specifically retain and reposition scan-10 `விசயர்` rather than deleting it;
- preserve contents/body page-number witnesses separately;
- preserve promotional/catalogue matter outside article bodies;
- preserve poem headings on their actual scans;
- lexical disagreements with scan pixels belong to later source-fidelity review and must be documented rather than silently corrected.

## Exact next activity

Create and directly verify **P2 canonical page records for scans 1–25** from the structurally corrected staging transcription **plus the user-correction override file**, preserving printed text separately from physical-copy marks and recording every page continuation/boundary. Do not begin P3 article assemblies until the relevant page layer is durable.