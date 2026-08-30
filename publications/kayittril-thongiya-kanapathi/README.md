# கயிற்றில் தொங்கிய கணபதி

**ஆசிரியர்:** மு. கருணாநிதி  
**Source-visible publication date:** ஜூலை 1949  
**வெளியீடு:** அறிவுப்பண்ணை  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied scan ஒரு **standalone single-article pamphlet / சிறுநூல்**. Source scan-இல் title/front matter, `பதிப்புரை`, ஒரு தொடர்ச்சியான கட்டுரை, பின்னணி விளம்பரப் பக்கங்கள் உள்ளன; printed contents page இல்லை.

## P0 — source intake / publication identification — COMPLETE

- Source filename: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source file size: **26,750,146 bytes**
- source PDF committed to repository: **No**
- prior publication/work for this title was not present in the current `publications/` tree when P0 began
- user supplied a Gemini first-pass OCR transcription; it is navigation/draft assistance only and is **not source authority**

## Source authority

> **மூல ஸ்கேன் தான் controlling source.**

Old Tamil glyph shapes must be read from the source pixels, not silently converted to a modern-looking or contextually expected form. Spelling, punctuation, word boundaries, names, numbers and unusual forms must remain source-visible. Library stamps / handwritten marks are physical-copy evidence and must not be merged into printed text.

### Old-glyph correction note — user recheck

After P0, the user manually rechecked the PDF and confirmed that the Gemini first-pass readings I had challenged were correct. The preliminary assistant-side “corrections” are therefore **withdrawn**. In particular, preserve the first-pass readings unless a fresh direct visual check proves otherwise, including:

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நேரமில்லை`
- `சோறில்லை`
- `தூக்குபோட்டுவிட்டீர்களா 1`
- `கொண்டிருக்கின்றார்.`
- final `அளிக்குமாக /`

The key non-regression lesson for this source is: **do not reinterpret an old Tamil glyph into a more familiar modern word merely because the modern reading looks semantically plausible.** P2 must compare the supplied first-pass transcription word by word against the scan and change it only when the pixels clearly support the change.

## Physical scan structure observed at intake

| Scan | Source-visible role | Printed-page behaviour |
|---:|---|---|
| 1 | front cover | no printed page number |
| 2 | title / publisher page | no printed page number |
| 3 | publication date / price / printer | no printed page number |
| 4 | `பதிப்புரை` | no printed page number |
| 5 | blank / paper surface | no printed page number |
| 6 | article opening | no visible printed numeral; sequence implies the page before printed 6, but this must not be invented as a visible number |
| 7–15 | article continuation / conclusion | printed pages **6–14** visible |
| 16 | advertisement / other publications | no printed page number |
| 17 | advertisement / back matter | no printed page number |

The article concludes on scan 15 at the printed ornament after the final `கணபதியின் கொலை...` sentence. Scans 16–17 are separate promotional witnesses, not article body.

## Current Tamil archival status

- P0 source intake / publication identification: **COMPLETE**
- P1 metadata + full page map / boundary mapping: **NOT YET COMPLETE**
- P2 page-level transcription: **NOT STARTED in repository**
- P3 article assembly: **NOT STARTED**
- P4 source audit: **NOT STARTED**
- P5 strict word/punctuation visual-fidelity pass: **NOT STARTED**
- English translation: **NOT STARTED**; Tamil source must be frozen first

## Exact next activity

Execute **P1 — metadata + complete 17-scan page map / boundary mapping**: create `indexes/page-map.md`, classify every physical scan, record printed-page-number behaviour and the article/ad boundaries from the controlling scan, and update the root `HANDOVER.md`. Do not mark the Gemini OCR as verified source text, but do not change its old-glyph readings merely because a modern alternative looks more familiar.