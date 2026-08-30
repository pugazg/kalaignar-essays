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

### P2 / retrospective correction provenance

A targeted recheck of the earlier assistant-origin corrections found one false correction and revalidated the other two formal P2 corrections:

- first pass `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டீர்களா!`** — scan 13 / printed p.12. The source line break is `தூக்குபோட்டுவிட்டீர்` + `களா!`; only the final OCR-like `1` needed correction to `!`. The earlier assistant change to `தூக்குபோட்டுவிட்டார்களா!` was incorrect and has been withdrawn.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — scan 13 / printed p.12; rechecked and retained.
- interim assistant `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — scan 12 / printed p.11; rechecked and retained.

### Source-supported readings retained

`உரைந்திருக்கும்`, `அடபாபமே!`, `கவலைப்பட வில்லை.`, `நேரமில்லை`, `சோறில்லை`, `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!`, `நெருக்கடியில்(!)` and final `அளிக்குமாக /` remain unnormalised.

## P3 — article assembly — COMPLETE

Single Tamil reading assembly:

[`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

- assembled strictly from verified page records for scans **6–15**;
- page-boundary comments retained for traceability;
- `பதிப்புரை`, cover/title/imprint/blank front matter and scans 16–17 advertisements are excluded from article body;
- the retrospective scan-13 correction above has been propagated to the assembly.

## P4 — source audit / completeness review — COMPLETE / PASS

Audit record: [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md)

P4 confirmed:

- **17 / 17** physical scans are represented exactly once;
- page-map and page-record file structure are complete and consistent;
- front matter / `பதிப்புரை` / blank / article / advertisement boundaries remain correct;
- scan 6 remains `printed_page: null`; scans 7–15 map to printed **6–14**;
- the **1 / 1** article assembly uses scans **6–15 only** and contains page-boundary comments through scan 15;
- front matter and advertisements are absent from the article body;
- unresolved body/source blockers: **0**.

P4 is a structural/completeness gate. It does **not** substitute for P5.

## Current Tamil archival status

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **COMPLETE — 17 / 17 verified**
- P3: **COMPLETE — 1 / 1 assembly**
- P4: **COMPLETE / PASS**
- **P5 strict word/punctuation visual-fidelity pass: NEXT — 0 / 17**
- Tamil source freeze: **NOT YET — blocked on P5**
- English translation: **NOT STARTED**

## Exact next activity

Execute **P5 — strict visual word/punctuation fidelity pass for all 17 physical scans in one activity**:

1. re-open the controlling scan independently of the P2 confidence state;
2. recheck every visible printed word, punctuation mark, heading, date, number and meaningful word boundary on scans **1–17**;
3. treat the existing verified transcription as the baseline and do **not** alter it unless the source gives clear character-level evidence;
4. recheck page-to-page continuations and scan 6's absent printed numeral;
5. recheck physical-copy marks remain separate from printed text;
6. recheck scans 16–17 as independent promotional witnesses;
7. for every genuine defect found, record old repository reading → source-visible reading provenance and update the affected page record;
8. propagate any article-body correction to `articles/01-kayittril-thongiya-kanapathi.md`;
9. create/update `VISUAL_TEXT_FIDELITY_REVIEW.md` and the P4/P5 completion review;
10. update dependent README/metadata/page-map/root README/HANDOVER;
11. only after **17 / 17** strict checks and assembly recheck pass may the Tamil source be marked frozen and translation planning become eligible.