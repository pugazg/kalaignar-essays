# உணர்ச்சிமாலை

**ஆசிரியர்:** மு. கருணாநிதி  
**Source-visible edition statement:** முதற்பதிப்பு—1951  
**வெளியீடு:** கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied scan ஒரு **10-கட்டுரைத் தொகுப்பு / multi-article publication**. Front matter-க்கு பிறகு பத்து தனித்தலைப்புடைய கட்டுரைகள் தொடர்ச்சியாக வருகின்றன; printed contents page இந்த scan-ல் இல்லை. Scan 49 இறுதியில் `முரசொலி` / `மாலைமணி`யில் வெளிவந்த கட்டுரைகள் என்பதைச் சுட்டும் parenthetical source note உள்ளது; scan 50 தனி back-cover film advertisement.

## P0 — source intake / publication identification — COMPLETE

- Source filename: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`
- physical scans: **50**
- source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- source file size: **79,471,633 bytes**
- source PDF committed to repository: **No**
- prior publication/work for this title was not present in the current `publications/` tree when P0 began
- user supplied a Gemini OCR transcription covering the publication body

## Publication-specific transcription instruction — USER ESTABLISHED

For this publication, the user has explicitly instructed:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features from the source.**

Operationally:

- Gemini word choices are the **working lexical baseline** for the current Tamil transcription pass;
- do **not** silently replace a Gemini word with a different scan reading;
- use the controlling scan to restore/verify headings, punctuation, spacing, paragraph boundaries, verse/quotation layout, indentation and other non-lexical structure;
- if a future scan check appears to conflict with a Gemini lexical token, log the conflict for user decision rather than silently changing the word;
- this is a user-directed workflow exception for lexical tokens; it is **not** a claim that OCR is source authority for the physical edition.

The scan remains the controlling witness for publication identity, page/section boundaries, physical-copy marks and the structural features the user has asked us to correct.

## Source-visible front matter observed at intake

- scan 1: illustrated front cover; title displayed as `உணர்ச்சி` / `மாலை`; author name at lower right
- scan 2: title/publisher page; title witness `உணர்ச்சிமாலை`; author witness `மு. கருணாநிதி`; publisher `கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.`; library/accession stamps and handwriting are physical-copy marks
- scan 3: `முதற்பதிப்பு—1951`; `விலை அணா 8`
- scan 4: `நன்றி`, ending with `எஸ். பி. நாதன், பதிப்பகத்தார்.`
- scan 5: blank / reverse-side bleed-through only
- scan 50: separate back-cover advertisement for `மணமகள்`

## Article structure observed at intake

The scan directly shows ten article-heading starts:

| # | Heading witness | Scan span observed at P0 |
|---:|---|---:|
| 1 | `உணர்ச்சி மாலை` | 6–9 |
| 2 | `புரட்சி வளர்ந்த கதை` | 10–15 |
| 3 | `போகிறான்;போகிறான்..!` | 16–18 |
| 4 | `இராவணன் நம் பாட்டன்` | 19–29 |
| 5 | `இங்கல்ல! இரஷ்யாவில்` | 30–32 |
| 6 | `3, 57, 90.` | 33–38 |
| 7 | `30-1-1948` | 39–41 |
| 8 | `பத்தினியே உன்போல்...!` | 42–44 |
| 9 | `அன்னை நாகம்மையார்!` | 45–47 |
| 10 | `கவிதையல்ல - கண்ணீர்க்கடல்!` | 48–49 |

These P0 spans identify article boundaries from visible heading transitions. Exact printed-page-number behaviour, exact heading punctuation/spacing and the scan-49 closing note must be recorded/rechecked in P1/P2 rather than inferred from OCR.

## Important source-witness distinction already visible

The publication title witness is `உணர்ச்சிமாலை`, while Article 1 begins with the heading `உணர்ச்சி மாலை`. Preserve these witnesses separately; do not normalize one from the other.

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + complete 50-scan page map / contents-boundary mapping: **NEXT**
- P2 page-level transcription: **NOT STARTED in repository**
- P3 article assemblies: **NOT STARTED — 0 / 10**
- P4 source audit: **NOT STARTED**
- P5 strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**; Tamil layer must reach its required closed state first

## Exact next activity

Execute **P1 — metadata + complete 50-scan page map / boundary mapping**:

1. create `metadata/source.md` if not already present and complete source-condition details;
2. create `indexes/page-map.md` covering all 50 physical scans;
3. create `indexes/contents.md` recording that no printed contents page is present while separately mapping the ten scan-verified article headings/boundaries;
4. record visible printed-page-number behaviour without inventing numbers that are not visible;
5. preserve the user-established Gemini lexical-baseline rule;
6. update the single root `HANDOVER.md` after P1.