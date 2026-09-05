# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, transcription, fidelity, translation or release activity.**

## Mandatory startup

Before changing anything:

1. read `ESSAY_PROCESSING_GUIDE.md` completely;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely when English is in scope;
3. read `docs/FUTURE_WORK_GUIDELINES.md` completely;
4. fetch live `main` and read this `HANDOVER.md` completely;
5. read `docs/NEXT_CHAT_PROMPT.md` only as a convenience summary;
6. read the selected publication's source/fidelity/translation records;
7. preserve released/verified work unless a genuine source-supported or release-blocking defect requires reopening it.

Source PDFs are never committed. English translation principle:

> **Translate the language; do not neutralise the voice.**

## Live-main rule

- **Live `main` is authoritative.**
- Never reset or repeat newer durable work because an older prompt records an earlier checkpoint.
- Re-fetch target files before writes.
- Publications 1–7 below are release-frozen. Reopen only for a genuine source-supported or release-blocking defect.

---

# Publications 1–7 — RELEASE COMPLETE / FROZEN

1. `சக்கரவர்த்தியின் திருமகன்` — Tamil strict fidelity complete; English T0–T5 **14 / 14**; E6/E7 **PASS / RELEASE COMPLETE**.
2. `கயிற்றில் தொங்கிய கணபதி` — Tamil P5 complete; released English blob `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`; **RELEASE COMPLETE / FROZEN**.
3. `உணர்ச்சிமாலை` — Tamil P5 **50 / 50**; English T0–T5 **10 / 10**; E6/E7 **PASS / RELEASE COMPLETE**.
4. `திராவிட சம்பத்து` — Tamil P0–P5 complete; English **2 / 2 VERIFIED**; E6/E7 **PASS / RELEASE COMPLETE**.
5. `இன முழக்கம்` — Tamil strict-reviewed/frozen; English **6 / 6 VERIFIED**; E6/E7 **PASS / RELEASE COMPLETE**.
6. `குடும்பத்தின் நல்விளக்கு` — Tamil strict-reviewed/frozen; English **1 / 1 VERIFIED**; E6/E7 **PASS / RELEASE COMPLETE**.
7. `கொலைக்களம்!` — Tamil P0–P5 **COMPLETE / STRICT-REVIEWED / FROZEN**; English **6 / 6 VERIFIED**; E6 **PASS**; E7 **PASS / RELEASE COMPLETE / FROZEN**.

Do not reopen publications 1–7 without a genuine source-supported or release-blocking defect.

---

# Publication 7 — கொலைக்களம்! — COMPLETE / RELEASED / FROZEN

Workspace: `publications/kolaikkalam/`  
Controlling source: `TVA_BOK_0063657_கொலைக்களம்.pdf`

Authoritative completion record: `publications/kolaikkalam/PUBLICATION_COMPLETION_REVIEW.md`.

## Source identity

- cover title: `கொலைக்களம்!`
- author: `கலைஞர். மு. கருணாநிதி`
- publisher: `முன்னேற்றப் பண்ணை`, `சென்னை-1`
- scan-2 edition witness: `முதற் பதிப்பு-52`
- scan-2 price: `விலை அணா எட்டு`
- distributor: `எம். எஸ். ராமுலு கம்பெனி`
- scan-4 signature: `மு. நமசிவாயம்` / `பண்ணையாளர்.`
- scan-40 printer: `ஸ்ரீமகள் பிரஸ், சென்னை—1`
- physical scans: **40**
- SHA-256: `674a534f6c29e5abed9c7ebf52c3cfd143f494d6a21341b5d0624871c187a96c`
- size: **55,495,728 bytes**
- source PDF committed: **No**

## Canonical units

1. `கொலைக்களம்!` — scans **5–9**
2. `‘அஸ்தி’ கரையட்டும்!` — scans **10–16**
3. `பலியை நிறுத்துங்கள்!` — scans **17–22**
4. `விழலுக்கு நீர் இறைத்து...` — scans **23–27**
5. `சோதனை!` — scans **28–33**
6. `வீரமுழக்கஞ் செய்திடுவீர்!` — scans **34–40**

Front matter scans **1–4** remain outside the six prose units. The separate scan-40 printer witness remains outside Unit-6 prose and outside its English translation.

## Tamil archival state — COMPLETE / STRICT-REVIEWED / FROZEN

- P0: **PASS**
- P1: **PASS**
- P2: **40 / 40 PASS**
- lexical reconciliation: **COMPLETE**
- P3: **6 / 6 PASS**
- P4: **6 / 6 PASS**
- P5: **40 / 40 scans; 6 / 6 assemblies PASS**
- unresolved fidelity discrepancies: **0**

User-reviewed damaged readings that remain controlling: scan 5 `யுத்தம்`; scan 8 `நமக்கெல்லாம்`; scan 23 `மனிதனான தப்பா`; scan 23 `கண்ணாடிக் கன்னத்தை`; scan 25 `இதற்குத்தானா`; scan 28 `சூத்திரர்களை`; scan 29 `புயலெனச்`; scan 30 `இதுதானா`; scan 34 `பலம்`.

Frozen Tamil authorities:

1. `bc22ad3acec0bacc70ef69e0fb46f85fa3fed274`
2. `c7e29e10bc9a7d9d2f0ff9b66bb47d663410bbc5`
3. `e9df22b14e6102c691fe4cc81417eda1051d8f25`
4. `91f764f73c9514b2ce1eefdd94d3a1320a0c228e`
5. `3eec6fa58a307cf1b0350a9a26f45a114908a9dd`
6. `9e0b9e437a7548ca31ce352ab485b1e342bedb95`

These six blobs remain the only Tamil authorities for any future English defect review.

## English release state — COMPLETE / RELEASED / FROZEN

- E0: **COMPLETE / PASS**
- T0: **6 / 6 PASS**
- T1: **6 / 6 PASS**
- T2: **6 / 6 PASS**
- T3: **6 / 6 PASS**
- T4: **6 / 6 PASS**
- T5: **6 / 6 PASS / VERIFIED**
- English files: **6 / 6**
- verified English articles: **6 / 6**
- E6 publication-wide consistency review: **PASS / COMPLETE**
- E7 release closeout: **PASS / RELEASE COMPLETE**
- ordered source-page comments: **36 / 36 PASS**
- Article-6 scan-40 printer witness in prose: **excluded / PASS**
- blockers: **0**

Released English authorities:

1. `கொலைக்களம்!` → **The Killing Field!** — `c0ca9a883720d51a2637b811b7f38ca1635ba848`
2. `‘அஸ்தி’ கரையட்டும்!` → **Let the ‘Ashes’ Dissolve!** — `d20e579836ff2749664d7ee1ed5def5237293e60`
3. `பலியை நிறுத்துங்கள்!` → **Stop the Sacrifice!** — `812c36b9e5350608dd1a951d08c2e48074549697`
4. `விழலுக்கு நீர் இறைத்து...` → **Watering the Weeds...** — `455e229bf216b21c8bc08c192be3b9e44c54940e`
5. `சோதனை!` → **Search!** — `fe5a7ea3c17c1bce940d4688365892aaa720285b`
6. `வீரமுழக்கஞ் செய்திடுவீர்!` → **Raise the Heroic Cry!** — `726217a73d55e573176b29da61a0c3dfb3cff611`

All six released English files retain `translation_status: verified`.

## E6 durable consistency decisions

E6 found **0** body corrections. Preserve deliberate source/context distinctions rather than homogenising them:

- **Dravidian land / Dravidian country** according to source sense;
- **nationalism / national / nationalist** according to grammar, with **cloak of nationalism** where the source uses that image;
- Article 2 **Jawahar** versus Article 6 **Pandit Jawaharlal**;
- Article 1 **Hindustan** versus Article 6 **India / united India**;
- Article 4 **pitch of valour** versus Article 6 **heroic cry**;
- Article 5 contextual **search / trial / test**;
- Article 6 `மத்ய சர்க்கார் / மத்திய சர்க்கார்` → functional **Central Government** while the frozen Tamil preserves its orthographic variation;
- source-bearing **Kuyyo! Muraiyo!**, **Neeli tears**, **Vibhishanas**, **Venganna**, **Chanakyan**, **kattai**, **Chandala-ness**, **Viveka (!) Chintamani**, **Brihaspatis**, **Rashtra Bhasha**, **Pathanistan**, **Kabar Khan**, and **Kaamaarkkung kudiyallom** remain intentionally unnormalised.

## E7 release closeout — PASS

E7 began from live `main` `6bee26a25b25e2d193838641de6c9f61d0afa567` and re-fetched the six E6 English candidates and six frozen Tamil authorities.

- English blobs match E6 baseline: **6 / 6 PASS**
- frozen Tamil blobs unchanged: **6 / 6 PASS**
- English metadata source pins: **6 / 6 PASS**
- `translation_status: verified`: **6 / 6 PASS**
- post-E6 English body drift: **0 / 6**
- post-E6 English metadata drift: **0 / 6**
- source-page comments: **36 / 36 PASS**
- Article-6 printer-witness exclusion: **PASS**
- source-sensitive E6 distinctions: **PASS**
- Tamil changes during E7: **0**
- release defects: **0**
- blockers: **0**

**E7 RESULT: PASS / ENGLISH TRANSLATION COMPLETE / RELEASE COMPLETE / FROZEN.**

## Permanent non-regression

- preserve frozen Tamil authority blobs exactly;
- preserve released English article blobs exactly unless a genuine source-supported defect is proven;
- preserve source-page comments, quotation status, source labels, rhetorical force and deliberate E6 contextual distinctions;
- do not use OCR, raw transcript, web text, memory or outside historical conventionalisation to overwrite the frozen source witness;
- do not reopen a released article merely for stylistic preference or terminology neatness.

## Exact next activity

No activity is pending for `கொலைக்களம்!`.

---

# Publication 8 — சிந்தனையும் செயலும் — P2 ACTIVE / SCANS 1–81 VERIFIED

Workspace: `publications/sinthanaiyum-seyalum/`

## Controlling source

The controlling witness is one **226-scan publication** supplied as five non-overlapping transfer PDFs under source identifier `TVA_BOK_0065568`.

| Part | Global scans | PDF pages | Bytes | SHA-256 |
|---:|---:|---:|---:|---|
| 001 | 1–55 | 55 | 139,200,528 | `55b55a445972248515c549c3c18223412f784220baf3e959367fe8d0a7f7c53d` |
| 002 | 56–109 | 54 | 137,950,874 | `f8f98c948b1c0bba3960905350a97bd6e68a5eeef9107bc0dd9dcf9ea03e578a` |
| 003 | 110–164 | 55 | 138,370,584 | `c05d1a108bff78d018ef542a0afadea62f9802ab7e982b0cf4d97cb789b702cd` |
| 004 | 165–219 | 55 | 138,940,454 | `7bcb93642b2291a575c82a10b08800ce8892e894e1807040da50d830102b60bc` |
| 005 | 220–226 | 7 | 18,787,263 | `d587cc69c41db3c8c2c34a8e4e41e28ef34fe47b7b5c0379df898ef603cf3228` |

- physical scans: **226**
- split-set size: **573,249,703 bytes**
- split continuity: **PASS — no gaps or overlaps**
- original unsplit-PDF SHA-256: **not available from the supplied split files; never fabricate it**
- source PDFs committed to repository: **No**

## Scan-verified printed identity

P2 direct visual review confirms title `சிந்தனையும் செயலும்`, author `கலைஞர் மு. கருணாநிதி`, publisher `தமிழ்க்கனி பதிப்பகம்`, first edition `ஜூன், 2006`, second edition `மார்ச், 2007`, third edition `ஜனவரி, 2010`, rights `ஆசிரியருக்கே`, price `ரூ. 120/-`, printer **`ஈகிள் பிரஸ், சென்னை - 600 013.`**, and the separate `பூம்புகார் பதிப்பகம்` sales-rights witness.

Front matter scans **1–17** are P2 verified.

## Verified body structure through Unit 17

1. `பாசியும் - தூசியும்!` — **18–23**, `27- 4 - 2005`
2. `அதிக உயரம் தாண்டுவதற்கு` — **24–27**, `29-4-2005`
3. heading `என் பெயர் புரட்சி!` — **28–32**, `1 - 5 - 2005`
4. `குருகுலம்!` — **33–35**, `3 - 5 - 2005`
5. `ஜனநாயக நெறி` — **36–38**, `7-5-2005`
6. heading `வாக்குச்சீட்டின் வலிமை` — **39–41**, `9-5-2005`
7. `சுயமரியாதைத் திருமணம்` — **42–45**, `13-5-2005`
8. `மனிதனின் மறுபக்கம்` — **46–48**, `15-5-2005`
9. heading `விண்ணைத் தொட்டு மண்ணில் புதைவதா?` — **49–51**, `16-5-2005`
10. `மனிதனும் மறுபிறவியும்` — **52–55**, `6-6-2005`
11. heading `வெற்றி தோல்வி!` — **56–58**, `8 - 6 - 2005`
12. `அழுக்காறு` — **59–61**, `10 - 6 - 2005`
13. `மிகுதிக்கண்...` — **62–65**, `1 - 7 - 2005`
14. `வலிவும், பொலிவும்!` — **66–68**, `8 - 7 - 2005`
15. heading `இன்பமும் துன்பமும்!` — **69–74**, `9 - 7 - 2005`
16. `ஒழுக்கம்` — **75–77**, `14 - 7 - 2005`
17. `வசிய மருந்து` — **78–81**, `18 - 7 - 2005`

Global scan **82** directly begins Unit 18 with heading `சோதிட சோகம்!`, confirming Unit 17 ends at scan 81.

## Independent witness distinctions / frozen non-regression

- Unit 3 contents `என் பெயர் புரட்சி` ↔ heading `என் பெயர் புரட்சி!`.
- Unit 6 contents `வாக்குச் சீட்டின் வலிமை` ↔ heading `வாக்குச்சீட்டின் வலிமை`.
- Unit 9 contents `விண்ணைத் தொட்டு மண்ணில் புதைவதோ?` ↔ heading `விண்ணைத் தொட்டு மண்ணில் புதைவதா?`.
- Unit 11 contents `வெற்றி - தோல்வி!` ↔ heading `வெற்றி தோல்வி!`.
- Unit 15 contents `இன்பமும் துன்பமும்` ↔ heading `இன்பமும் துன்பமும்!`.
- P1 printer `ஈகில் பிரஸ்` was corrected by scan to `ஈகிள் பிரஸ்`.
- contents Unit 18 is `சோதிட சோகம்!`; Unit 44 is `குரு பீடமும்; குறள் பீடமும்!`; Unit 41 preserves `வலி அறிவிக்கும் வாயில்லா மொழி !`.
- preserve earlier source-visible forms including `கருப்பாதை`, `‘ஜனநாயக’த்தில்`, `‘துறவு’ம்`, `எதிர் காலம்`, `விலங்கொடிக்க`, `காலிப் புட்டிகளாக`, `வழங்கப்பட்டோர் பெயர்கள்`, `பிடிப்பின்றித்`, `செயலாக்கம்`, `முதன்முதல்`, `அனைத்திந்திய`, `சித்ரவதை`, `உறுதிபட`, `போதாகி மலர்கின்ற`, `அங்கனமாயின்`, `கவிதைக்குப் பூசும் தங்க முலாம்.`, `உருமாற்றவும்தான்`, `கூடவேகூடாது`.
- preserve batch-56–81 source-visible forms including `தேறல்`, `தன்மான`, `அந்நாள்`, `ஒரு பகுதியில்`, `அல்வழிச்`, `உற்பத்தியாகக்`, `‘நகுதல்’ எனப்படும் சிரித்து மகிழ்ந்து பழகுவதே`, `மருத்துவ (டாக்டர்) நண்பர்`, `மருத்துவ நண்பருக்குரிய`, `நாகரிகமாக`, `நகுதற் பொருட்டுதான்`, `வீண் வெறுப்புக்கு`, `விளையாட்டு போலவே`, `ஓங்கி`, `ஓசை`, `ஒன்பது மணி`, `எதென்சிலும்`, `எதென்ஸ்`, `2000ஆம்`, `2004ஆம்`, `2012ஆம்`, `இஃதோர் தூண்டுதலாகட்டும்`, `நடைபெறுமேயானால்`, `காரணமானவர்களைச் சட்டத்தின்`, `வயிற்றுப் பிழைப்பு சார்`, `திருந்துவார்களோ?`, `பகுத்தறிவு பரப்புவதைத்`.

Do not modernise, silently correct or harmonise these witnesses.

## Tamil archival status

- P0: **COMPLETE / PASS**
- P1: **COMPLETE / PASS**
- physical scan records: **226 / 226 CREATED**
- P2 directly verified pages: **81 / 226**
- P2 verified range: **1–81**
- P2 verified body units: **17 / 50**
- P3 article assemblies: **17 / 50 VERIFIED**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation pass: **NOT STARTED**
- unresolved readings in verified scans 1–81: **0**
- Tamil archival phase: **P2 ACTIVE**

## English translation status

- English translation: **NOT STARTED**
- translation workspace: **NOT CREATED**
- prerequisite: complete/freeze Tamil through strict P5 first.

## Current unresolved source questions

- Units 18–50 remain pending direct P2 transcription/boundary verification.
- Original unsplit 574 MB PDF checksum remains unavailable; only the five transfer-part checksums are authoritative.
- No body-text reading may be imported from external bibliography or inferred from contents alone.

## Exact next activity

**P2 — directly transcribe and verify scans 82–111 in one coherent batch, covering Units 18–25 (`சோதிட சோகம்!` through `இங்கர்சால்`). Scans 82–109 are in Part 002 and scans 110–111 cross into Part 003. Verify each unit heading/start and the following heading/end directly from the scan, preserve contents-title versus heading-title differences as independent witnesses, record printed text and physical-copy marks separately, create article assemblies only after every included page is verified, propagate source corrections to indexes/README, and update this root handover.**

## Rules for the next session

1. Fetch live `main` and read this handover first.
2. Preserve Publications 1–7 as frozen.
3. Preserve all P2-verified scans 1–81 unless a genuine source-supported correction is found.
4. Treat Units 18–50 P1 spans as provisional until direct visual verification.
5. Resolve the supplied Part 003 source before final verification of global scans 110–111.
6. Do not begin English translation.
