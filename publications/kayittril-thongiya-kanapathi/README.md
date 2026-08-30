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
- user supplied Gemini first-pass OCR: **comparison aid only; not source authority**

## Source authority

> **மூல ஸ்கேன் தான் controlling source.**

Old Tamil glyph shapes must be read from source pixels, not silently converted to a modern-looking or contextually expected form. Spelling, punctuation, word boundaries, names, numbers and unusual forms remain source-visible. Library stamps / handwritten marks are physical-copy evidence and are kept outside printed text.

A plausible modern word is **not** evidence.

## P0 — source intake / publication identification — COMPLETE

- One publication unit created for this supplied edition.
- Standalone single-article pamphlet structure confirmed from the scan.
- Source identity/checksum/size/scan count recorded; PDF remains outside GitHub.

## P1 — metadata + complete page map / boundary mapping — COMPLETE

Page map: [`indexes/page-map.md`](indexes/page-map.md)

- scans **1–5**: front matter (`பதிப்புரை` scan 4; scan 5 blank)
- scan **6**: article opening; **no visible printed numeral**
- scans **7–15**: visible printed pages **6–14**
- scans **6–15**: single article
- scan **15**: article ends at printed ornament
- scans **16–17**: separate promotional / advertisement witnesses
- printed contents page: **none**

The archive does **not** assign a visible printed page `5` to scan 6 merely from sequence inference.

## P2 — page-level transcription — COMPLETE

All **17 / 17** physical scans now have page records under [`pages/`](pages/), and every record was compared directly with the controlling scan before receiving `status: verified`.

P2 includes:

- cover/title/imprint/front matter;
- `பதிப்புரை`;
- blank scan;
- all ten article scans **6–15**;
- both advertisements **16–17**;
- printed text separated from physical-copy/library marks;
- page-to-page continuations preserved;
- scan 6 kept as `printed_page: null`.

### P2 direct-pixel correction provenance

The earlier P0 working list was deliberately provisional and subject to P2/P5 scan verification. P2 found clear source-pixel evidence for the following corrections:

- earlier working `தூக்குபோட்டுவிட்டீர்களா 1` → source-visible **`தூக்குபோட்டுவிட்டார்களா!`** on scan 13 / printed p.12. Enlarged pixels confirm both the `விட்டார்களா` ending and the exclamation mark.
- earlier working `கொண்டிருக்கின்றார்.` → source-visible **`கொண்டிருக்கிறார்.`** on scan 13 / printed p.12.
- interim assistant punctuation reading `உரத்தகுரலில்;` → source-visible **`உரத்தகுரலில்,`** on scan 12 / printed p.11.

These are **source-supported corrections**, not modernisation.

### User-rechecked readings retained after P2

The following earlier user-rechecked forms remain source-supported and are retained:

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நேரமில்லை`
- `சோறில்லை`
- final `அளிக்குமாக /`

Other unusual P2 readings such as `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!` and `நெருக்கடியில்(!)` are preserved rather than normalised.

## Physical scan structure

| Scan | Source-visible role | Printed-page behaviour | P2 page record |
|---:|---|---|---|
| 1 | front cover | none | `pages/0001-cover.md` |
| 2 | title / publisher page | none | `pages/0002-title-page.md` |
| 3 | date / price / printer | none | `pages/0003-imprint.md` |
| 4 | `பதிப்புரை` | none | `pages/0004-pathippurai.md` |
| 5 | blank / paper surface | none | `pages/0005-blank.md` |
| 6 | article opening | **no visible numeral** | `pages/0006-article-opening.md` |
| 7 | article continuation | 6 | `pages/0007-article-p06.md` |
| 8 | article continuation | 7 | `pages/0008-article-p07.md` |
| 9 | article continuation | 8 | `pages/0009-article-p08.md` |
| 10 | article continuation | 9 | `pages/0010-article-p09.md` |
| 11 | article continuation | 10 | `pages/0011-article-p10.md` |
| 12 | article continuation | 11 | `pages/0012-article-p11.md` |
| 13 | article continuation | 12 | `pages/0013-article-p12.md` |
| 14 | article continuation | 13 | `pages/0014-article-p13.md` |
| 15 | article conclusion + ending ornament | 14 | `pages/0015-article-p14.md` |
| 16 | advertisement / other publications | none | `pages/0016-advertisement-01.md` |
| 17 | advertisement / back matter | none | `pages/0017-advertisement-02.md` |

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + full page map / boundary mapping: **COMPLETE**
- P2 page-level transcription: **COMPLETE — 17 / 17 verified page records**
- P3 article assembly: **NEXT — 0 / 1**
- P4 source audit: **NOT STARTED**
- P5 separate strict word/punctuation visual-fidelity pass: **NOT STARTED — 0 / 17**
- English translation: **NOT STARTED**; Tamil source must be frozen first

## Exact next activity

Execute **P3 — assemble the single Tamil article** as `articles/01-kayittril-thongiya-kanapathi.md` strictly from verified page records **scans 6–15**:

1. preserve source wording and punctuation exactly;
2. retain page-boundary comments for traceability;
3. do not import `பதிப்புரை`, cover/front matter or advertisements into the article body;
4. preserve the source-supported P2 corrections and unusual forms above;
5. update dependent records and root `HANDOVER.md` after assembly;
6. do not begin P4/P5 or English translation in the same activity unless the handover explicitly advances to them.