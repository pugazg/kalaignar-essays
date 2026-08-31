# மூலப் பதிவு — உணர்ச்சிமாலை

## Source identity

- Source filename: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`
- Source PDF committed to repository: **No**
- SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- File size: **79,471,633 bytes**
- Physical scan pages: **50**
- Language: Tamil
- Script: Tamil
- Controlling source: supplied scanned PDF
- Publication type: **10-article collection / multi-article publication**
- P0: **COMPLETE**
- P1: **COMPLETE**
- P2 page-level transcription: **COMPLETE — 50 / 50 verified**
- P3 article assembly: **COMPLETE — 10 / 10**
- P4 source audit / completeness review: **NOT STARTED**
- P5 strict visual text-fidelity pass: **NOT STARTED**
- English translation: **NOT STARTED**

Page map: [`../indexes/page-map.md`](../indexes/page-map.md)  
Article/content map: [`../indexes/contents.md`](../indexes/contents.md)

## Title / authorship witnesses

- scan 1 front cover: title laid out as `உணர்ச்சி` / `மாலை`; author `மு.கருணாநிதி`
- scan 2 title page: title `உணர்ச்சிமாலை`; author `மு. கருணாநிதி`
- Article 1 opening on scan 6: heading `உணர்ச்சி மாலை`

Publication/title-page witness and Article 1 heading witness remain separate; never normalize one from the other.

## Publication details visible in scan

- scan 2: publisher `கருணாநிதி பதிப்பகம்`; address `சிந்தாதிரிப்பேட்டை, சென்னை-2.`; library/accession marks are physical-copy evidence
- scan 3: `முதற்பதிப்பு—1951`; `விலை அணா 8`
- scan 4: `நன்றி`; closing `எஸ். பி. நாதன், பதிப்பகத்தார்.`
- scan 49: Article 10 conclusion followed by printed publication-source note referring to `முரசொலி` / `மாலைமணி`, then `அன்பன் அச்சகம், சென்னை -1.`
- scan 50: separate illustrated `மணமகள்` back-cover film advertisement

## Publication / article boundaries — VERIFIED

- scans **1–5**: front matter
- scans **6–9**: Article 1 — `உணர்ச்சி மாலை`
- scans **10–15**: Article 2 — `புரட்சி வளர்ந்த கதை`
- scans **16–18**: Article 3 — `போகிறான்;போகிறான்..!`
- scans **19–29**: Article 4 — `இராவணன் நம் பாட்டன்`
- scans **30–32**: Article 5 — `இங்கல்ல! இரஷ்யாவில்`
- scans **33–38**: Article 6 — `3, 57, 90.`
- scans **39–41**: Article 7 — `30-1-1948`
- scans **42–44**: Article 8 — `பத்தினியே உன்போல்...!`
- scans **45–47**: Article 9 — `அன்னை நாகம்மையார்!`
- scans **48–49**: Article 10 — `கவிதையல்ல - கண்ணீர்க்கடல் !`
- scan **50**: separate advertisement
- printed contents page: **none**

`indexes/contents.md` is an editorial scan-derived article map, not a transcription of a printed contents page.

## Printed-page-number behaviour — VERIFIED

Every article-opening scan has no visible printed numeral. Continuation numbers are preserved exactly. Scan 20 contains only a single visible `1` at the page-number position; no unseen `19` is reconstructed.

## Heading-format witnesses — NON-REGRESSION

- Article 3: `போகிறான்;போகிறான்..!`
- Article 4 physically two lines: `இராவணன்` / `நம் பாட்டன்`
- Article 8 physically two lines: `பத்தினியே` / `உன்போல்...!`
- Article 10 physically two lines: `கவிதையல்ல -` / `கண்ணீர்க்கடல் !`

## Publication-specific user instruction — Gemini lexical baseline

The user explicitly supplied Gemini OCR and instructed that its **words be retained**. Therefore:

- Gemini word tokens remain the working lexical baseline wherever supplied;
- corrections are limited to indentation, punctuation, spaces, missing paragraphs, headings, quotation/verse layout and analogous structural features supported by the scan;
- scan/Gemini lexical conflicts are logged instead of silently resolved;
- whole omitted source blocks may be scan-recovered only under the user's explicit missing-paragraph instruction, with clear provenance.

## P2 result — COMPLETE

All **50 / 50** page records are verified. Printed text and physical-copy marks are separated. Durable exceptions/conflicts:

- scan 19 whole-page Gemini omission was source-recovered and labelled;
- scan 32 Gemini lexical/order sequence `அறிவு, நாட்டில் அடுப்பங்கரை இந் எதிரிகளின் நிஜுலினா...` remains retained despite scan disagreement;
- scan 41 ends Article 7 at `வரலாற்றை வீணாக்கிய`;
- scan 48 Gemini `ப்ழச்சளை` remains retained despite scan disagreement;
- scan 49 Gemini placement of `விட்டாய்.` remains retained despite scan order disagreement;
- non-source OCR artefacts (`ID`, `1-48-1-30`, `e`, `செளே`, leading scan-50 `C`, and standalone page-number intrusions) are excluded only after direct scan confirmation;
- scan 49 publication-close note/imprint and scan 50 advertisement are outside Article 10 body.

## P3 result — COMPLETE

All **10 / 10** article assemblies were built exclusively from the verified page records:

- `../articles/01-unarchchi-maalai.md`
- `../articles/02-puratchi-valarntha-kathai.md`
- `../articles/03-pogiran-pogiran.md`
- `../articles/04-iravanan-nam-pattan.md`
- `../articles/05-ingalla-irashyavil.md`
- `../articles/06-3-57-90.md`
- `../articles/07-30-1-1948.md`
- `../articles/08-paththiniye-unpol.md`
- `../articles/09-annai-nagammaiyar.md`
- `../articles/10-kavithaiyalla-kannirkkadal.md`

P3 guarantees at this checkpoint:

- assembly changed no Gemini lexical decision;
- all logged P2 conflicts were propagated unchanged;
- scan 19 source-recovered text remains marked by provenance;
- physical scan-boundary comments trace every assembly;
- source-supported heading/quotation/verse structure was retained;
- scan-49 publication-source note/imprint was not included in Article 10 body;
- scan 50 advertisement was not included in any article.

## Exact next gate

**P4 — source audit / completeness review.** Compare all ten assemblies against the verified page layer for completeness, order, boundaries and non-regression. Confirm every mapped page-body segment appears exactly once, logged conflicts remain unchanged, and publication-close/advertisement material remains outside article bodies. Do not begin P5 or English translation until P4 is explicitly completed.

## Source authority / user-baseline rule

Never silently modernise or normalize source structure. For lexical wording, continue the user-established Gemini-baseline rule until the user changes it. Any lexical discrepancy against the scan must remain explicit rather than silently resolved.