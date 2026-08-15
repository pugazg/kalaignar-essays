# Essay / Article Processing Guide

இந்த repository-யில் கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் கட்டுரைத் தொகுப்புகளை ஒரே **source-first** முறையில் மின்னாக்குவதற்கான நிரந்தர வழிகாட்டி.

## 1. அடிப்படை விதி

> **மூல ஸ்கேன் தான் controlling source.**

Markdown உரை மூலத்தைப் பாதுகாக்க வேண்டும்; புதிய/திருத்தப்பட்ட பதிப்பை உருவாக்கக் கூடாது.

அமைதியாக செய்யக்கூடாதவை:

- எழுத்துப்பிழை என்று தோன்றுவதைத் திருத்துதல்;
- பழைய சொல்/எழுத்து வடிவங்களை நவீனப்படுத்துதல்;
- இலக்கணம், punctuation, sandhi, பெயர்கள், எண்களை standardize செய்தல்;
- வரலாற்றுப் பெயர்/தேதி/மேற்கோளை memory அல்லது இணையப் பதிப்பால் மாற்றுதல்;
- தெளிவில்லாத எழுத்தை sentence பொருளை வைத்து ஊகித்தல்;
- scan-ல் இல்லாத heading/section label-ஐ body text-க்குள் silently சேர்த்தல்.

## 2. PDF policy

Source PDF repository-க்குள் commit செய்யப்படாது.

ஒவ்வொரு source publication-க்கும் `metadata/source.md`-ல் குறைந்தது பின்வருவன பதிவு செய்ய வேண்டும்:

- source filename;
- SHA-256 checksum;
- file size;
- scan page count;
- title / author as printed;
- edition / publication details visible in scan;
- printed-page numbering behaviour;
- scan condition;
- handwritten notes, library stamps, accession marks, bleed-through, illustrations, advertisements போன்ற anomalies.

## 3. Publication-first structure

ஒரே PDF-ல் பல கட்டுரைகள் இருப்பின் source-ஐ 14 அல்லது 20 முறை duplicate செய்யக் கூடாது. முதலில் publication edition ஒன்றை பதிவு செய்து, அதன் கீழ் தனித்தனி article assemblies உருவாக்க வேண்டும்.

```text
publications/<publication>/
  README.md
  metadata/
    source.md
  indexes/
    contents.md
    page-map.md
  pages/
    0001-....md
  articles/
    01-....md
```

Standalone article scan ஒன்றும் இதே வடிவில் ஒரு publication unit ஆகக் கொள்ளலாம்.

## 4. ஒவ்வொரு scan page-க்கும் record

Cover, title page, imprint, preface, contents, article body, advertisement, blank page, back cover ஆகிய **ஒவ்வொரு scan page-க்கும்** Markdown record இருக்க வேண்டும்.

```yaml
---
scan_page: 1
printed_page: null
publication: "publication-slug"
article: null
section: "cover"
page_type: "cover"
status: "verified"
language: "ta"
source_filename: "...pdf"
transcription_method: "direct visual comparison with source scan"
---
```

Status values:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` என்பது scan-ஐ நேரடியாகப் பார்த்து text, punctuation, paragraph structure மற்றும் non-text marks அனைத்தையும் உறுதிப்படுத்திய பின்னரே பயன்படுத்த வேண்டும்.

## 5. அச்சு உரை vs physical-copy marks

Page record-ல் இரண்டு அடுக்குகள் தெளிவாகப் பிரிக்கப்பட வேண்டும்:

- `# அச்சு உரை` — publication-ல் அச்சிடப்பட்ட உரை மட்டும்;
- `## அச்சு அல்லாத / physical-copy marks` — library stamp, handwriting, accession number, damage, stain, bleed-through போன்றவை.

Stamp அல்லது handwriting அச்சு எழுத்தை மறைத்தால், மறைந்த பகுதியை context பார்த்து நிரப்பக்கூடாது.

## 6. கடின வாசிப்புகள்

**No stones should be left unturned.** ஒரு வாசிப்பு முதலில் தெளிவில்லாமல் தெரிகிறது என்பதற்காக உடனே `blocked` என்று முடிக்கக்கூடாது.

தேவைக்கேற்ப:

1. PDF native scan image-ஐ நேரடியாகப் பாருங்கள்;
2. enlarged crops மற்றும் வேறு resampling முறைகள் பயன்படுத்துங்கள்;
3. contrast/gamma/sharpening/grayscale போன்ற non-destructive variants முயற்சி செய்யுங்கள்;
4. அதே font-இல் அருகிலுள்ள glyph-களுடன் ஒப்பிடுங்கள்;
5. முன்/பின் பக்க continuation-ஐச் சரிபாருங்கள்;
6. user வழங்கும் reading-ஐ source pixels-க்கு எதிராக எழுத்துருவாரியாக verify செய்யுங்கள்;
7. அவசியமானபோது provenance-உடைய independent secondary witness-ஐ corroboration-க்காக மட்டும் பயன்படுத்துங்கள்.

Secondary witness wording-ஐ controlling scan-க்கு silently import செய்யக்கூடாது.

## 7. பொருளடக்கம் மற்றும் article boundaries

Printed contents page source evidence ஆகப் பாதுகாக்கப்பட வேண்டும். அதிலுள்ள தொடக்கப் பக்க எண்களை `indexes/contents.md`-ல் verbatim பதிவு செய்ய வேண்டும்.

Article boundary-கள் scan-ல் நேரடியாக உறுதிப்படுத்தப்பட வேண்டும். Printed page sequence மூலம் மட்டும் முடிவைக் கணிக்க வேண்டாம்; அடுத்த article heading-ஐ பார்த்து boundary-ஐ verify செய்ய வேண்டும்.

## 8. Article assembly

`articles/NN-slug.md` என்பது page records-லிருந்து சேர்க்கப்பட்ட reading copy. Assembly செய்யும்போது:

- source wording மாற்றப்படக்கூடாது;
- page boundary comments வைத்திருக்கலாம்;
- source-supported headings மட்டும் body-ல் இருக்க வேண்டும்;
- editorial notes article body-க்கு வெளியே இருக்க வேண்டும்;
- unresolved source readings இருந்தால் வெளிப்படையாகக் குறிக்க வேண்டும்.

## 9. Errata / corrections

ஒரு edition-ல் printed errata இருந்தால் அது தனி source layer ஆகப் பதிவு செய்யப்படும். Errata-வை page transcription-க்கு silently apply செய்யக்கூடாது.

## 10. Translation

Translation என்பது source transcription முழுமையாக audit செய்யப்பட்ட பிறகு தனி கட்டமாக மட்டுமே தொடங்க வேண்டும். Translation source wording-ஐ விளக்கலாம்; Tamil archival layer-ஐ மாற்றக்கூடாது.

## 11. Completion gate

ஒரு article `source-complete` எனக் கூறுவதற்கு முன்:

- அதன் எல்லா source scan pages-மும் direct visual audit செய்யப்பட்டிருக்க வேண்டும்;
- start/end boundaries உறுதிப்படுத்தப்பட்டிருக்க வேண்டும்;
- unresolved body-text blocks documented ஆக இருக்க வேண்டும்;
- assembled article page records-க்கு ஒத்திருக்க வேண்டும்;
- silent normalization இல்லை என்பதை final review உறுதிப்படுத்த வேண்டும்.
