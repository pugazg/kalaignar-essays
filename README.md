# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் பல கட்டுரைகள் அடங்கிய தொகுப்பு வெளியீடுகளை **மூல ஸ்கேனை controlling source ஆகக் கொண்டு** Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் தெரியும் எழுத்து, பழைய எழுத்துப்பாங்கு, punctuation, பெயர்கள், எண்கள், மீளுரைகள், வழக்கத்திற்கு மாறான இலக்கணம் ஆகியவை அமைதியாகச் சீர்திருத்தப்படவோ நவீனப்படுத்தப்படவோ கூடாது. தெளிவில்லாத இடம் பொருள் பார்த்து ஊகித்து நிரப்பப்படாது.

Library stamp, accession number, handwriting, bleed-through, சேதம், பின்னர் சேர்க்கப்பட்ட குறிப்பு போன்ற physical-copy marks அச்சு உரையிலிருந்து தனியாகப் பதிவு செய்யப்படும்.

**மூல PDF கோப்புகள் repository-யில் commit செய்யப்படாது.** Filename, checksum, file size, scan page count, edition identity, publication details, page mapping மற்றும் scan anomalies மட்டும் metadata-வில் பதிவு செய்யப்படும்.

## களஞ்சிய அமைப்பு

பல கட்டுரைகள் அடங்கிய ஒரு நூல்/தொகுப்பு முதலில் `publications/` கீழ் source edition ஆகப் பதிவு செய்யப்படும். அதன் உள்ளேயே scan-page records மற்றும் தனித்தனி கட்டுரை assembly-கள் வைக்கப்படும்.

```text
README.md
ESSAY_PROCESSING_GUIDE.md
HANDOVER.md
publications/
  <publication-slug>/
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
    audit.md
```

Standalone article scan ஒன்றும் இதே source-first விதியில் ஒரு publication unit ஆகப் பதிவு செய்யலாம்.

## முதல் source publication

### சக்கரவர்த்தியின் திருமகன் — கலைஞர் மு. கருணாநிதி

வழங்கப்பட்ட scan-ல் இது **2018 மறுபதிப்பு**; `நூல் குறிப்பு` பக்கம் முதல் பதிப்பை **மே 1956 (வேலூர் திராவிடன் பதிப்பகம்)** என்று பதிவு செய்கிறது. பொருளடக்கத்தில் **14 கட்டுரைகள்** உள்ளன.

Current status:

- source identity / checksum / edition metadata: **registered**
- scans **1–8** front matter + contents: **8 / 8 VERIFIED**
- Article 1 — **சக்கரவர்த்தியின் திருமகன்**, scans **9–15**, printed pp. **7–13**: **7 / 7 VERIFIED / source-complete**
- Article 1 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md`](publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md)
- Article 2 — **தேகமும் உணர்வும்** begins at scan **16** / printed p. **14**; this is the next transcription unit.

Publication workspace: [`publications/sakkaravarththiyin-thirumagan/`](publications/sakkaravarththiyin-thirumagan/)

Audit: [`publications/sakkaravarththiyin-thirumagan/audit.md`](publications/sakkaravarththiyin-thirumagan/audit.md)

விரிவான நிரந்தர workflow: [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md).
