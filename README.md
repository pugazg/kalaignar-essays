# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் பல கட்டுரைகள் அடங்கிய தொகுப்பு வெளியீடுகளை **மூல ஸ்கேனை controlling source ஆகக் கொண்டு** Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

மூலத்தில் தெரியும் எழுத்து, பழைய எழுத்துப்பாங்கு, punctuation, பெயர்கள், எண்கள், மீளுரைகள், வழக்கத்திற்கு மாறான இலக்கணம் ஆகியவை அமைதியாகச் சீர்திருத்தப்படவோ நவீனப்படுத்தப்படவோ கூடாது. தெளிவில்லாத இடம் பொருள் பார்த்து ஊகித்து நிரப்பப்படாது.

Library stamp, accession number, handwriting, bleed-through, சேதம், பின்னர் சேர்க்கப்பட்ட குறிப்பு போன்ற physical-copy marks அச்சு உரையிலிருந்து தனியாகப் பதிவு செய்யப்படும்.

**மூல PDF கோப்புகள் repository-யில் commit செய்யப்படாது.** Filename, checksum, file size, scan page count, edition identity, publication details, page mapping மற்றும் scan anomalies மட்டும் metadata-வில் பதிவு செய்யப்படும்.

## களஞ்சிய அமைப்பு

பல கட்டுரைகள் அடங்கிய ஒரு நூல்/தொகுப்பு முதலில் `publications/` கீழ் source edition ஆகப் பதிவு செய்யப்படும். அதன் உள்ளேயே scan-page records மற்றும் தனித்தனி article assembly-கள் வைக்கப்படும்.

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
- Article 2 — **தேகமும் உணர்வும்**, scans **16–21**, printed pp. **14–19**: **6 / 6 VERIFIED / source-complete**
- Article 2 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/02-thegamum-unarvum.md`](publications/sakkaravarththiyin-thirumagan/articles/02-thegamum-unarvum.md)
- Article 3 — **சதி நிரூபிக்கப்படுகிறது**, scans **22–25**, printed pp. **20–23**: **4 / 4 VERIFIED / source-complete**
- Article 3 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/03-sathi-nirupikkappadugirathu.md`](publications/sakkaravarththiyin-thirumagan/articles/03-sathi-nirupikkappadugirathu.md)
- Article 4 — **காமராஜன் ஆட்கொண்ட தசரதராஜன்!**, scans **26–29**, printed pp. **24–27**: **4 / 4 VERIFIED / source-complete**
- Article 4 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/04-kamarajan-aadkonda-dasaratharajan.md`](publications/sakkaravarththiyin-thirumagan/articles/04-kamarajan-aadkonda-dasaratharajan.md)
- Article 5 — **பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?**, scans **30–37**, printed pp. **28–35**: **8 / 8 VERIFIED / source-complete**
- Article 5 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/05-paraththuvaja-aasramama-paris-nagarathu-para.md`](publications/sakkaravarththiyin-thirumagan/articles/05-paraththuvaja-aasramama-paris-nagarathu-para.md)
- Article 6 — **இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா?**, scans **38–42**, printed pp. **36–40**: **5 / 5 VERIFIED / source-complete**
- Article 6 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md`](publications/sakkaravarththiyin-thirumagan/articles/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md)
- Article 7 — **விபீஷணருக்கு விடை யளிப்போம்!**, scans **43–49**, printed pp. **41–47**: **7 / 7 VERIFIED / source-complete**
- Article 7 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/07-vibishanarukku-vidai-yalippom.md`](publications/sakkaravarththiyin-thirumagan/articles/07-vibishanarukku-vidai-yalippom.md)
- Article 8 — **நாடாண்ட மன்னன் நாதியற்று செத்தான்**, scans **50–54**, printed pp. **48–52**: **5 / 5 VERIFIED / source-complete**
- Article 8 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/08-naadaanda-mannan-naathiyatru-seththaan.md`](publications/sakkaravarththiyin-thirumagan/articles/08-naadaanda-mannan-naathiyatru-seththaan.md)
- Article 9 — **தந்தை மகனும் தருமம் தவறியவர்கள்!**, scans **55–60**, printed pp. **53–58**: **6 / 6 VERIFIED / source-complete**
- Article 9 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/09-thanthai-maganum-tharumam-thavariyavargal.md`](publications/sakkaravarththiyin-thirumagan/articles/09-thanthai-maganum-tharumam-thavariyavargal.md)
- Article 10 — **விஷ்ணு அவதாரம் என்பதும் ராமனிடம்!**, scans **61–64**, printed pp. **59–62**: **4 / 4 VERIFIED / source-complete**
- Article 10 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/10-vishnu-avatharam-enbathum-ramanidam.md`](publications/sakkaravarththiyin-thirumagan/articles/10-vishnu-avatharam-enbathum-ramanidam.md)
- Article 11 — **நடப்பதெல்லாம் நாராயணன் செயலா?**, scans **65–70**, printed pp. **63–68**: **6 / 6 VERIFIED / source-complete**
- Article 11 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/11-nadappathellam-narayanan-seyala.md`](publications/sakkaravarththiyin-thirumagan/articles/11-nadappathellam-narayanan-seyala.md)
- Article 12 — **மாரீசனைத் துரத்திச் சென்ற ராமனிடம்**, scans **71–73**, printed pp. **69–71**: **3 / 3 VERIFIED / source-complete**
- Article 12 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/12-maarisanai-thuraththi-sendra-ramanidam.md`](publications/sakkaravarththiyin-thirumagan/articles/12-maarisanai-thuraththi-sendra-ramanidam.md)
- Article 13 — **துரோகிகள் சந்திப்பு!**, scans **74–78**, printed pp. **72–76**: **5 / 5 VERIFIED / source-complete**
- Article 13 assembled reading: [`publications/sakkaravarththiyin-thirumagan/articles/13-thurogigal-santhippu.md`](publications/sakkaravarththiyin-thirumagan/articles/13-thurogigal-santhippu.md)
- scan **79** directly begins Article 14 — **காரியமாகும் வரையில் காலை பிடி!**; this is the next transcription unit.

Publication workspace: [`publications/sakkaravarththiyin-thirumagan/`](publications/sakkaravarththiyin-thirumagan/)

Audit: [`publications/sakkaravarththiyin-thirumagan/audit.md`](publications/sakkaravarththiyin-thirumagan/audit.md)

விரிவான நிரந்தர workflow: [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md).
