# P4 source audit / completeness review — கயிற்றில் தொங்கிய கணபதி

## Scope

Controlling source: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`  
Physical scans: **17**  
Recorded SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`

This document records **P4 — source audit / completeness review** only. It does **not** certify the later P5 strict every-word / every-punctuation visual-fidelity gate.

The supplied scan remains the controlling source. P4 checks archival completeness, structure, page↔assembly consistency, known correction propagation and blocker status; it does not replace the independent P5 re-audit.

## P4 completion gates

| Check | Result |
|---|---|
| Physical scans in controlling source | **17** |
| Physical page records present | **17 / 17 PASS** |
| Every physical scan represented exactly once | **PASS** |
| Page-map ↔ page-record file mapping | **17 / 17 PASS** |
| Front matter boundary | **PASS — scans 1–5** |
| `பதிப்புரை` boundary | **PASS — scan 4** |
| Blank physical scan | **PASS — scan 5** |
| Article boundary | **PASS — scans 6–15** |
| Advertisements / promotional matter | **PASS — scans 16–17, outside article** |
| Scan 6 printed-page metadata | **PASS — `printed_page: null`; no invented 5** |
| Scans 7–15 printed-page sequence | **PASS — 6–14** |
| Article assemblies | **1 / 1 PASS** |
| Article assembly source range | **PASS — scans 6–15 only** |
| Page-boundary comments in assembly | **PASS — scans 6–15 traceable** |
| Front matter imported into article | **No** |
| Advertisements imported into article | **No** |
| Known correction provenance propagated | **PASS after retrospective amendment** |
| Known unusual/source-specific readings retained | **PASS** |
| Unresolved article-body blockers | **0** |
| Hidden `needs-review` / blocker carried into P4 | **0 recorded** |
| Source PDF committed to repository | **No** |
| P5 strict visual fidelity completed | **No — NEXT gate** |

**P4 RESULT: PASS — SOURCE STRUCTURE / COMPLETENESS GATE CLOSED.**

Tamil archival completion is **not yet final** because P5 remains mandatory.

## Physical-page completeness audit

The repository tree contains exactly one page record for each source scan:

1. `pages/0001-cover.md`
2. `pages/0002-title-page.md`
3. `pages/0003-imprint.md`
4. `pages/0004-pathippurai.md`
5. `pages/0005-blank.md`
6. `pages/0006-article-opening.md`
7. `pages/0007-article-p06.md`
8. `pages/0008-article-p07.md`
9. `pages/0009-article-p08.md`
10. `pages/0010-article-p09.md`
11. `pages/0011-article-p10.md`
12. `pages/0012-article-p11.md`
13. `pages/0013-article-p12.md`
14. `pages/0014-article-p13.md`
15. `pages/0015-article-p14.md`
16. `pages/0016-advertisement-01.md`
17. `pages/0017-advertisement-02.md`

No duplicate or missing scan-number record was found.

## Source-boundary audit

Direct source review confirms the publication model used by the archive:

- scans **1–3**: cover / title-publisher / imprint material;
- scan **4**: `பதிப்புரை`;
- scan **5**: blank paper surface;
- scan **6**: article heading/opening with **no visible printed page numeral**;
- scans **7–15**: article continuation through visible printed pages **6–14**;
- scan **15**: article conclusion followed by printed ending ornament and a lower physical-copy/library stamp;
- scans **16–17**: separate printed advertisements / promotional matter.

The assembly boundary therefore remains **scans 6–15 only**.

## Article-assembly audit

Assembly:

[`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

P4 confirmed:

- front matter and `பதிப்புரை` do not occur in the article assembly;
- advertisement witness `அறிவுப் புதையல்கள்` does not occur in the article assembly;
- page-boundary comments run from scan **6** through scan **15**;
- scan 6 is explicitly identified as having no visible printed numeral;
- the final article sentence remains `கணபதியின் கொலை இந்த உறுதியை திராவிடர்க்கு அளிக்குமாக /` before the article-end comment;
- the printed ending ornament and lower library stamp are not imported as article prose.

## Correction propagation audit — retrospectively amended

A later targeted recheck of the assistant-origin P2 corrections found one false correction. The source-backed record is now:

- first-pass `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டீர்களா!`** — scan 13 / printed p.12. The source itself breaks the word as `தூக்குபோட்டுவிட்டீர்` at the line end and `களா!` at the next line. Therefore the verb/person ending from the first pass was correct; only `1` → `!` needed correction. The earlier assistant form `தூக்குபோட்டுவிட்டார்களா!` was wrong and has been removed from both page record and article assembly.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — scan 13 / printed p.12; directly rechecked again and retained.
- interim `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — scan 12 / printed p.11; directly rechecked again and retained.

This retrospective amendment does not reopen P4's structural findings. It corrects the textual provenance record before P5.

## Source-specific non-regression audit

The assembly retains source-supported forms including:

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நேரமில்லை`
- `சோறில்லை`
- `நன்றுக`
- `அவர்கட்கு`
- `அக்கரை`
- `தங்கந் தோண்டுமிடமாயிற்றே!`
- `நெருக்கடியில்(!)`
- final `அளிக்குமாக /`

No such form should be changed merely because a more familiar spelling seems plausible.

## Blocker audit

- unresolved article-body blockers: **0**
- unresolved source-boundary blockers: **0**
- unresolved printed-page-mapping blockers: **0**

The partially obscured/crossed library-stamp wording on scan 2 remains a physical-copy issue only and is correctly not reconstructed into printed publication text.

## Gate boundary

P4 closes only the **source completeness / structure / assembly consistency** gate.

The publication must **not** yet be called strict visual-text-fidelity complete or Tamil-frozen. The mandatory next gate is **P5**, a new direct pass over all **17 scans**, rechecking every visible word, punctuation mark, heading, number, meaningful word boundary, continuation and non-body witness distinction. Existing verified text is the baseline; any P5 change requires clear source-pixel evidence and must be propagated to both page records and the article assembly with old-reading → source-visible-reading provenance.