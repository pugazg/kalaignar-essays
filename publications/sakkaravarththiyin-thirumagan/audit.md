# Source audit — சக்கரவர்த்தியின் திருமகன்

## Source-layer state

The original archival/source layer is complete for the supplied 83-scan edition:

- physical scan page records: **83 / 83**
- printed-content articles identified: **14 / 14**
- article assemblies: **14 / 14**
- source PDF committed to repository: **No**
- controlling source: the supplied scan

See [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md) for the source-layer completion gate.

## Strict visual-text-fidelity layer

A second, stricter word-by-word / punctuation-by-punctuation review is in progress and remains separate from the earlier `VERIFIED` page status.

Detailed ledger: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

Current progress: **48 / 83 scans strict-reviewed**.

| Scope | Source-layer status | Strict fidelity status |
|---|---|---|
| Scans 1–8 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 9–16 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 17–24 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 25–32 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 33–40 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 41–48 | VERIFIED | **8 / 8 COMPLETE** |
| Scans 49–56 | VERIFIED | **PENDING — next batch** |
| Scans 57–83 | VERIFIED | PENDING |

The publication is source-complete, but strict visual-text-fidelity review is not yet complete.

## Earlier strict corrections/revalidations

- scan 7: `மற்றும் உள்ள` → `மற்றுமுள்ள`
- scan 8 Article 12 contents: `மார்ச்சனைத்...` → `மாரீசனைத் துரத்திச் சென்ற ராமனிடம்`
- scan 9: `பத்து மூர்த்த அவதாரங்களைப் போலவே` → `பத்து முரண்பட்ட அவதாரங்களைப் போலவே`
- scan 9: `பொய்ப்படி` → `எப்படி பெய்ப்படி`
- scans 11–12: `கல்சாசனமோ` → `கல் சாசனமோ`
- scans 33–36: earlier source-layer corrections revalidated, including `பரத்துவாஜ...`, `போடுகிறவன் போட்டாலும்`, `சீறிப் பாய்ந்தார்கள்`

## Batch 6 — scans 41–48

**8 / 8 COMPLETE. Three new strict-fidelity corrections were found and propagated.**

- scan 41 — **CORRECTED:** source mixed quotation is `‘மூதேவி அடி எடுத்து வைத்த நேரம் அப்படி!”`; earlier Markdown normalized the closing mark. `என்பதாகுவது`, `பிராப்த விஷயத்தை`, `புத்திரப்பிரிவு`, and `நாணயமாகாது` agree.
- scan 42 — **CORRECTED:** `சாயைக் கட்டு போடும்` → source-visible **`சப்பைக் கட்டு போடும்`**. `அனுமாருக்குத்தான்`, `அந்தப்பாவி`, `ஆரியக்காவல்`, `இலக்கியமய்யா இலக்கியம்` and the article-ending ornament agree.
- scan 43 — **FIDELITY-PASS:** Article 7 heading/opening and `முப்புரியை உருவிப் புறப்பட்ட`, `சூதின் உருவம்`, `தண்ட கண்ட கடவுள் கொள்கை` agree.
- scan 44 — **CORRECTED:** source spacing is **`தன் இனம்,தன் சமுதாயம்,அந்த சமுதாயத்தின்`**; earlier Markdown inserted spaces after the first two commas. Other unusual forms including `எச்சரிக்கையாகயிருந்து`, `நேரமிது வென்போம்`, `கபோதிகளாக்கி`, `நாடொறுமேனியும்`, `மான் மீதும் மற்றுகள்` agree.
- scan 45 — **FIDELITY-PASS:** `விபீஷணப்பட்டத்தை`, `வாலேந்திகள்` and quotation forms agree.
- scan 46 — **FIDELITY-PASS:** `விண்ணுறையும்`, `அறுபதினாயிரம்`, `வற்புறுத்தப்பட்டதேயன்றி`, `கற்புக்கேடு காட்டிலே`; source-visible unclosed quotation after `ராமாயணம்.` remains unrepaired.
- scan 47 — **FIDELITY-PASS:** `இனித்தவாயனும்`, `விஷ்ணு அவதார மென்றீர்கள்`, `கற்பு சம்மாக்கப்பட்டு`, `அய்வருக்கும்` agree.
- scan 48 — **FIDELITY-PASS:** `சாப விமோசனம்`, `பொன்னான(?)`, `ஸ்ரீராமுலு`, `ஆர்குஸிஸ்`, and the distinct joined/spaced `நிறவெறி` forms agree.

### Assembly state after Batch 6

- Article 6, scans **38–42**, is fully strict-rechecked; the scan-41 punctuation and scan-42 `சப்பைக் கட்டு போடும்` corrections are propagated into its assembly.
- Article 7 scans **43–48** agree with its assembly after the scan-44 spacing correction.
- scan 49 remains pending before Article 7 strict closeout.
- no unresolved `NEEDS-PIXEL-REVIEW` item remains in Batch 6.

## No-silent-correction rule

Later editions, web transcriptions, remembered wording, modern spelling, grammatical expectation and contextual inference must not replace the supplied scan. Difficult glyphs must be visually rechecked and, if unresolved, marked for pixel review rather than guessed.

## Next strict-fidelity unit

Proceed in physical scan order with **scans 49–56**: scan 49 concludes Article 7; scans 50–54 cover Article 8 `நாடாண்ட மன்னன் நாதியற்று செத்தான்`; scans 55–56 begin Article 9 `தந்தை மகனும் தருமம் தவறியவர்கள்!`.
