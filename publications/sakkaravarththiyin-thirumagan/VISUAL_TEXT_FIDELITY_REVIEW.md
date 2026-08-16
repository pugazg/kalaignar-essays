# Visual text fidelity review — சக்கரவர்த்தியின் திருமகன்

## Purpose

This is a second, stricter layer above the earlier source transcription / `VERIFIED` workflow.

Controlling source: `TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`  
Source scans: **83**  
Recorded SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`

Each physical page is reopened and compared directly with the scan for every readable printed word, word boundary/spacing, punctuation mark, quotation mark, numeral, date, heading, paragraph boundary and cross-page continuation. Physical-copy marks remain separate from printed text. OCR, context, modern usage and remembered wording do not override scan pixels.

## Verdicts

- `FIDELITY-PASS` — every readable printed token checked; no discrepancy found.
- `CORRECTED` — one or more earlier transcription discrepancies corrected from scan pixels and propagated.
- `CORRECTED (revalidated)` — a correction already present before the staged batch was reopened and visually reconfirmed.
- `NEEDS-PIXEL-REVIEW` — a glyph/mark remains unresolved after enlargement; no contextual guess is allowed.
- `PENDING` — not yet processed in this stricter pass.

## Progress

| Scan range | Section | Result |
|---|---|---|
| 1–8 | front matter + contents | **8 / 8 COMPLETE** |
| 9–16 | Article 1 + Article 2 start | **8 / 8 COMPLETE** |
| 17–24 | Article 2 / Article 3 | **8 / 8 COMPLETE** |
| 25–32 | Article 3 / Article 4 / Article 5 | **8 / 8 COMPLETE** |
| 33–40 | Article 5 / Article 6 | **8 / 8 COMPLETE** |
| 41–48 | Article 6 / Article 7 | **8 / 8 COMPLETE** |
| 49–56 | Article 7 / Article 8 / Article 9 | **PENDING — next batch** |
| 57–64 | Article 9 / Article 10 | PENDING |
| 65–72 | Article 11 / Article 12 | PENDING |
| 73–80 | Article 12 / Article 13 / Article 14 | PENDING |
| 81–83 | Article 14 close, advertisement, back cover | PENDING |

Current strict-fidelity progress: **48 / 83 physical scans complete**.

The publication remains source-layer complete, but must not be described as strict visual-text-fidelity complete until all 83 scans and all article assemblies have passed this staged review.

## Batches 1–4 summary

- **1–8:** scans 1–6 pass; scan 7 corrected `மற்றும் உள்ள` → `மற்றுமுள்ள`; scan 8 Article 12 contents corrected `மார்ச்சனைத்...` → `மாரீசனைத் துரத்திச் சென்ற ராமனிடம்`.
- **9–16:** revalidated scan 9 `பத்து முரண்பட்ட அவதாரங்களைப் போலவே` and `எப்படி பெய்ப்படி`; scans 11–12 source spacing `கல் சாசனமோ`; remaining pages pass.
- **17–24:** **8 / 8 FIDELITY-PASS**, no new discrepancy. Article 2 fully strict-rechecked.
- **25–32:** **8 / 8 FIDELITY-PASS**, no new discrepancy. Articles 3 and 4 fully strict-rechecked; Article 5 checked through scan 32.

## Batch 5 — scans 33–40

**8 / 8 COMPLETE.** No new discrepancy was discovered; already-propagated source corrections were revalidated on scans 33–36.

- scans 33–36 reconfirm `பரத்துவாஜ...`, `போடுகிறவன் போட்டாலும்`, `சீறிப் பாய்ந்தார்கள்`, and other source-visible forms
- scans 37–40 are fidelity passes
- Article 5, scans **30–37**, is fully strict-rechecked
- Article 6 scans **38–40** agreed with its assembly

## Batch 6 — scans 41–48

All eight scans were reopened at readable/enlarged scale. Three genuine fidelity discrepancies were found and corrected; the other five pages passed without alteration.

| Scan | Printed page / section | Verdict | Findings |
|---:|---|---|---|
| 41 | p.39 — Article 6 | **CORRECTED** | Earlier `என்பதாகுவது` remains source-confirmed. The final phrase was punctuation-normalized in Markdown; the scan actually opens with a single curly quote and closes with a double curly quote: `‘மூதேவி அடி எடுத்து வைத்த நேரம் அப்படி!”`. The mixed source punctuation is now preserved. |
| 42 | p.40 — Article 6 conclusion | **CORRECTED** | Enlarged scan pixels read **`சப்பைக் கட்டு போடும்`**, not earlier `சாயைக் கட்டு போடும்`. Page and Article 6 assembly corrected. `அனுமாருக்குத்தான்`, `அந்தப்பாவி`, `ஆரியக்காவல்`, `இலக்கியமய்யா இலக்கியம்` and the final ornament agree. |
| 43 | p.41 — Article 7 begins | **FIDELITY-PASS** | Heading `விபீஷணருக்கு விடை யளிப்போம்!`, `சமீபகாலமாக`, `முப்புரியை உருவிப் புறப்பட்ட`, `சூதின் உருவம்`, `தண்ட கண்ட கடவுள் கொள்கை` and continuation agree. |
| 44 | p.42 — Article 7 | **CORRECTED** | Source spacing is **`தன் இனம்,தன் சமுதாயம்,அந்த சமுதாயத்தின்`** with no spaces after the first two commas; earlier Markdown inserted spaces. `எச்சரிக்கையாகயிருந்து`, `நேரமிது வென்போம்`, `கபோதிகளாக்கி`, `நாடொறுமேனியும்`, `அக்கரை`, and `மான் மீதும் மற்றுகள்` agree. |
| 45 | p.43 — Article 7 | **FIDELITY-PASS** | `விபீஷணப்பட்டத்தை`, `வாலேந்திகள்`, source quotation forms around `சக்கரவர்த்தித்திருமகன்`, `கல்கி`, and `அவதார` agree. |
| 46 | p.44 — Article 7 | **FIDELITY-PASS** | `விண்ணுறையும்`, `அறுபதினாயிரம்`, `வற்புறுத்தப்பட்டதேயன்றி`, `கற்புக்கேடு காட்டிலே` agree. The long quotation beginning `அயோத்தி வேந்தன் தசரதன்...` still has no visible closing quotation after `ராமாயணம்.` and remains unrepaired. |
| 47 | p.45 — Article 7 | **FIDELITY-PASS** | `இனித்தவாயனும்`, `விஷ்ணு அவதார மென்றீர்கள்`, `இப்படி யெல்லாம்`, `கற்பு சம்மாக்கப்பட்டு`, `அய்வருக்கும்` and quotation boundaries agree. |
| 48 | p.46 — Article 7 | **FIDELITY-PASS** | `சாப விமோசனம்`, `பொன்னான(?)`, `வழிபடுதற்குரியவனாகிறான்`, `ஸ்ரீராமுலு`, `ஆர்குஸிஸ்`, joined `நிறவெறிப் பேயாட்டமே` versus later spaced `நிற வெறிப் பேயாட்டம்`, and the bold interjection agree. |

### Assembly check after Batch 6

- Article 6, scans **38–42 / printed pp.36–40**, is now **fully strict-rechecked**. Its assembly carries the source-correct mixed quotation on scan 41 and **`சப்பைக் கட்டு போடும்`** on scan 42.
- Article 7 assembly content for scans **43–48 / printed pp.41–46** agrees with the strict-reviewed page layer after the scan-44 spacing correction.
- Scan 49 remains pending before Article 7 receives full strict closeout.
- No `NEEDS-PIXEL-REVIEW` item remains in this batch.

## Corrections confirmed/revalidated so far

1. scan 7: `மற்றும் உள்ள` → `மற்றுமுள்ள`
2. scan 8 contents: `மார்ச்சனைத்...` → `மாரீசனைத் துரத்திச் சென்ற ராமனிடம்`
3. scan 9: `பத்து மூர்த்த அவதாரங்களைப் போலவே` → `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`
4. scan 9: `பொய்ப்படி` → `எப்படி பெய்ப்படி`
5. scans 11–12: `கல்சாசனமோ` → `கல் சாசனமோ`
6. scans 33–36: earlier `பரத்வாஜ...` forms → source-visible `பரத்துவாஜ...`
7. scan 34: `போடுகிறவன் போட்டாலும்` revalidated after earlier provisional correction
8. scan 36: `சிரிப் பாய்ந்தார்கள்` → `சீறிப் பாய்ந்தார்கள்`
9. scan 41: normalized closing single quotation corrected to source-visible mixed close in `‘மூதேவி அடி எடுத்து வைத்த நேரம் அப்படி!”`
10. scan 42: `சாயைக் கட்டு போடும்` → `சப்பைக் கட்டு போடும்`
11. scan 44: `தன் இனம், தன் சமுதாயம், அந்த...` → source spacing `தன் இனம்,தன் சமுதாயம்,அந்த...`

## Next batch

Proceed with **scans 49–56** in physical scan order:

- scan **49** — conclude Article 7
- scans **50–54** — Article 8 `நாடாண்ட மன்னன் நாதியற்று செத்தான்`
- scans **55–56** — first two pages of Article 9 `தந்தை மகனும் தருமம் தவறியவர்கள்!`

For every page, compare each visible token directly with the scan, enlarge uncertain glyphs rather than infer from context, propagate any correction into the relevant article assembly, and advance the count only after the full batch is closed.
