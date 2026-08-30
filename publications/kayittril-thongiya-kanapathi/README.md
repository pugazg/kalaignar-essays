# கயிற்றில் தொங்கிய கணபதி

**ஆசிரியர்:** மு. கருணாநிதி  
**Source-visible publication date:** ஜூலை 1949  
**வெளியீடு:** அறிவுப்பண்ணை  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied scan ஒரு **standalone single-article pamphlet / சிறுநூல்**. Source scan-இல் title/front matter, `பதிப்புரை`, ஒரு தொடர்ச்சியான கட்டுரை, பின்னணி விளம்பரப் பக்கங்கள் உள்ளன; printed contents page இல்லை.

## Source identity

- Source filename: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source file size: **26,750,146 bytes**
- source PDF committed to repository: **No**
- Gemini first-pass OCR: **comparison aid only; not authority**

## Source authority

> **மூல ஸ்கேன் தான் controlling source.**

Old Tamil glyph shapes, spelling, punctuation, word boundaries, names, numbers and unusual forms remain source-visible. Library stamps / handwritten marks stay outside printed text. A plausible modern word is **not** evidence.

## P0 — source intake / publication identification — COMPLETE

Standalone single-article pamphlet structure confirmed directly from the supplied scan; source identity/checksum/size/scan count recorded; PDF remains outside GitHub.

## P1 — metadata + complete page map / boundary mapping — COMPLETE

Page map: [`indexes/page-map.md`](indexes/page-map.md)

- scans **1–5**: front matter (`பதிப்புரை` scan 4; scan 5 blank)
- scan **6**: article opening; **no visible printed numeral**
- scans **7–15**: visible printed pages **6–14**
- scans **6–15**: single article
- scan **15**: article conclusion
- scans **16–17**: separate promotional / advertisement witnesses
- printed contents page: **none**

The archive does **not** infer a visible page 5 for scan 6.

## P2 — page-level transcription — COMPLETE

All **17 / 17** physical scans have verified page records under [`pages/`](pages/). Printed text and physical-copy marks are separated, page continuations are preserved, and scan 6 remains `printed_page: null`.

### P2 direct-pixel correction provenance

Clear enlarged source-pixel evidence established:

- `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டார்களா!`** — scan 13 / printed p.12; both the verb ending and `!` are visible.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — scan 13 / printed p.12.
- interim assistant `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — scan 12 / printed p.11.

These are source-supported corrections, not modernisation.

### Source-supported readings retained

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நேரமில்லை`
- `சோறில்லை`
- final `அளிக்குமாக /`

Other unusual forms including `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!` and `நெருக்கடியில்(!)` remain unnormalised.

## P3 — article assembly — COMPLETE

Single Tamil reading assembly:

[`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

- assembled strictly from verified page records for scans **6–15**;
- page-boundary comments retained for traceability;
- `பதிப்புரை`, cover/title/imprint/blank front matter and scans 16–17 advertisements are excluded from article body;
- no new OCR wording or editorial normalization was introduced during assembly.

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + full page map / boundary mapping: **COMPLETE**
- P2 page-level transcription: **COMPLETE — 17 / 17 verified**
- P3 article assembly: **COMPLETE — 1 / 1**
- **P4 source audit / completeness review: NEXT**
- P5 strict word/punctuation visual-fidelity pass: **NOT STARTED — 0 / 17**
- English translation: **NOT STARTED**; Tamil source must be frozen first

## Exact next activity

Execute **P4 — source audit / completeness review** for the whole 17-scan publication:

1. confirm every physical scan 1–17 has exactly one correct page record and the page-map matches it;
2. confirm cover/title/imprint/`பதிப்புரை`/blank/article/advertisement boundaries against the source;
3. confirm the single article assembly matches the verified page layer for scans 6–15 and excludes front matter/ads;
4. confirm scan 6 remains `printed_page: null` and scans 7–15 map to printed 6–14;
5. confirm all known P2 correction provenance and unusual source readings are carried consistently into the assembly;
6. record any unresolved source/body blockers explicitly;
7. produce the P4 completion/audit record and update dependent status files + root `HANDOVER.md`;
8. do **not** collapse P4 into P5: the separate strict every-word/every-punctuation visual-fidelity pass remains P5.