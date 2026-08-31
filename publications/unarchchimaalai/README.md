# உணர்ச்சிமாலை

**ஆசிரியர்:** மு. கருணாநிதி  
**Source-visible edition statement:** முதற்பதிப்பு—1951  
**வெளியீடு:** கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied scan ஒரு **10-கட்டுரைத் தொகுப்பு / multi-article publication**. Front matter-க்கு பிறகு பத்து தனித்தலைப்புடைய கட்டுரைகள் தொடர்ச்சியாக வருகின்றன; printed contents page இந்த scan-ல் இல்லை. Scan 49 இறுதியில் publication-source note + printer imprint உள்ளது; scan 50 தனி back-cover film advertisement.

## Source identity

- Source filename: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`
- physical scans: **50**
- source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- source file size: **79,471,633 bytes**
- source PDF committed to repository: **No**
- printed contents page: **none**

## Publication-specific transcription instruction — USER ESTABLISHED

For this publication, the user has explicitly instructed:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features from the source.**

Operationally:

- Gemini word choices are the **working lexical baseline** for the current Tamil transcription pass;
- do **not** silently replace a Gemini word with a different scan reading;
- use the controlling scan to restore/verify headings, punctuation, spacing, paragraph boundaries, verse/quotation layout, indentation and other non-lexical structure;
- if a scan check appears to conflict with a Gemini lexical token, log the conflict for user decision rather than silently changing the word;
- this is a user-directed workflow exception for lexical tokens; it is **not** a claim that OCR is source authority for the physical edition.

The scan remains the controlling witness for publication identity, page/section boundaries, physical-copy marks and the structural features the user has asked us to correct.

## P0 — source intake / publication identification — COMPLETE

- live `main` checked before intake; no duplicate publication tree existed;
- source identity/checksum/file size/scan count recorded;
- ten-article collection identified;
- scans 1–5 front matter, scans 6–49 article region, scan 50 advertisement;
- source PDF remains outside GitHub.

## P1 — metadata + complete page / boundary mapping — COMPLETE

All **50 / 50** physical scans were inspected and mapped.

Created:

- [`metadata/source.md`](metadata/source.md)
- [`indexes/page-map.md`](indexes/page-map.md)
- [`indexes/contents.md`](indexes/contents.md)

P1 confirmed:

- scans **1–5** — front matter;
- scans **6–9** — Article 1 `உணர்ச்சி மாலை`;
- scans **10–15** — Article 2 `புரட்சி வளர்ந்த கதை`;
- scans **16–18** — Article 3 `போகிறான்;போகிறான்..!`;
- scans **19–29** — Article 4 `இராவணன் நம் பாட்டன்`;
- scans **30–32** — Article 5 `இங்கல்ல! இரஷ்யாவில்`;
- scans **33–38** — Article 6 `3, 57, 90.`;
- scans **39–41** — Article 7 `30-1-1948`;
- scans **42–44** — Article 8 `பத்தினியே உன்போல்...!`;
- scans **45–47** — Article 9 `அன்னை நாகம்மையார்!`;
- scans **48–49** — Article 10 `கவிதையல்ல - கண்ணீர்க்கடல் !`;
- scan **50** — separate illustrated `மணமகள்` back-cover advertisement.

No printed contents page exists in the supplied scan. `indexes/contents.md` is therefore explicitly an editorial scan-derived article map, not a transcription of a printed contents page.

## Printed-page-number behaviour

Every article-opening scan has **no visible printed page numeral**. Continuation-page numerals are recorded exactly in `indexes/page-map.md` without back-filling implied start numbers.

Notable anomaly: on **scan 20**, only a single visible `1` is legible at the page-number position. The map and page record do not reconstruct an unseen `19`.

## Source-witness distinctions that must not regress

- publication/title-page witness: **`உணர்ச்சிமாலை`**;
- Article 1 heading witness: **`உணர்ச்சி மாலை`**;
- Article 3 heading: **`போகிறான்;போகிறான்..!`**;
- Article 4 heading lineation: `இராவணன்` / `நம் பாட்டன்`;
- Article 8 heading lineation: `பத்தினியே` / `உன்போல்...!`;
- Article 10 heading lineation: `கவிதையல்ல -` / `கண்ணீர்க்கடல் !`.

Preserve these independent witnesses separately; do not normalize one from another.

## P2 — page-level transcription — ACTIVE

- page records: **38 / 50 verified**
- scans **1–5** front matter: **complete**
- Article 1 `உணர்ச்சி மாலை`, scans **6–9**: **4 / 4 complete**
- Article 2 `புரட்சி வளர்ந்த கதை`, scans **10–15**: **6 / 6 complete**
- Article 3 `போகிறான்;போகிறான்..!`, scans **16–18**: **3 / 3 complete**
- Article 4 `இராவணன் நம் பாட்டன்`, scans **19–29**: **11 / 11 complete**
- Article 5 `இங்கல்ல! இரஷ்யாவில்`, scans **30–32**: **3 / 3 complete**
- Article 6 `3, 57, 90.`, scans **33–38**: **6 / 6 complete**
- Gemini lexical baseline retained throughout all portions where Gemini supplied wording; scan-supported punctuation, spacing, paragraphing, headings and quotation/lineation restored
- **scan 19 exception:** Gemini omitted the entire page body; because the user explicitly authorised correction of missing paragraphs, scan 19 was recovered directly from the controlling scan and clearly documented as source-recovered rather than Gemini-derived
- **scan 32 lexical-order conflict:** the Gemini stream supplies `அறிவு, நாட்டில் அடுப்பங்கரை இந் எதிரிகளின் நிஜுலினா...`, while the scan visibly distributes that wording differently. The Gemini token sequence is retained and the conflict is explicitly logged rather than silently reordered or substituted
- intrusive OCR artefacts such as scan-31 `ID` and Gemini page-number intrusions are excluded only where the scan confirms they are not printed body text
- article-opening scans 30 and 33 remain unnumbered; visible continuation numbers 30–31 and 33–37 are preserved
- printed-text and physical-copy layers kept separate
- P3 article assemblies: **NOT STARTED — 0 / 10**
- P4 source audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**; Tamil layer must reach its required closed state first

## Exact next activity

Finish **P2 — page-level transcription for scans 39–50** in one closing page-layer batch: Articles 7–10 plus the separate scan-50 back-cover advertisement. Preserve unnumbered article-opening scans 39, 42, 45 and 48; preserve all visible continuation numerals and the scan-49 mixed article-close/publication-imprint role; retain Gemini words unchanged except for explicitly source-recovered missing blocks, and correct only the user-authorised structural/punctuation/spacing features.