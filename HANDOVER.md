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

# Publication 8 — சிந்தனையும் செயலும் — P0/P1 COMPLETE / P2 NEXT

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

Direct P0/P1 visual inspection establishes:

- cover/title: `சிந்தனையும் செயலும்`
- author: `கலைஞர் மு. கருணாநிதி`
- publisher witness on scan 5: `தமிழ்க்கனி பதிப்பகம்`
- first edition: `ஜூன், 2006`
- second edition: `மார்ச், 2007`
- third edition: `ஜனவரி, 2010`
- rights: `ஆசிரியருக்கே`
- price: `ரூ. 120/-`
- printer: `ஈகில் பிரஸ், சென்னை - 600 013.`
- title/back-cover sales-rights witness: `பூம்புகார் பதிப்பகம்`, Chennai.

Front matter also contains `பதிப்புரை` on scans 6–7 and `அணிந்துரை` by `டாக்டர் வா. செ. குழந்தைசாமி` on scans 8–12. Printed `பொருளடக்கம்` occupies scans 14–15.

## Publication structure — P1

- scans 1–17: cover/front matter/contents/internal-title/blank-verso witnesses;
- scans 18–225: body area;
- scan 226: back-cover/promotional witness;
- printed contents: **50 numbered units total**;
- Unit 1 `பாசியும் - தூசியும்!` — contents start printed page 17; expected scans 18–23; directly visible closing date **27-4-2005**;
- Unit 2 `அதிக உயரம் தாண்டுவதற்கு` — contents start printed page 23; expected scans 24–27; directly visible closing date **29-4-2005**;
- Units 3–50: P1 contents-derived expected spans are recorded in `indexes/page-map.md`; final boundaries remain pending direct P2 visual verification.

The separate user/older bibliographic description says “two letters and 50 articles.” Preserve that statement as a separate bibliographic witness only. The controlling scan's own contents numbers **50 units total**, with Units 1–2 being the two letter-form pieces. Do **not** silently turn the scan into 52 units.

## Source-witness distinctions that must not regress

- `தமிழ்க்கனி பதிப்பகம்` publisher witness and `பூம்புகார் பதிப்பகம்` sales-rights witness serve different printed functions; do not collapse them.
- contents titles and article-heading titles are independent witnesses; P2 must preserve punctuation/spelling differences instead of normalising them.
- scan 226 promotional/back-cover excerpts are not body authorities.
- the external “2 letters + 50 articles” description is not authority over the scan's 50-entry contents.
- cover, title page, internal title page and back cover remain separate source witnesses.

## Physical-copy condition

Intake inspection shows circular library stamps on front matter, yellow/brown spotting/foxing, handling stains and bleed-through on blank/verso leaves. Printed text and physical-copy marks must remain in separate sections.

## Tamil archival status

- P0 source intake / split resolution: **COMPLETE / PASS**
- P1 metadata + contents + page map: **COMPLETE / PASS**
- physical scan records: **226 / 226 CREATED**
- front/back records structurally inspected but not source-complete: **18 partial** (scans 1–17 and 226)
- body page records: **208 not-started** (scans 18–225)
- pages marked `verified`: **0 / 226**
- P2 direct transcription/verification: **NOT STARTED / NEXT**
- P3 article assemblies: **0 / 50; NOT STARTED**
- P4 source/completeness audit: **NOT STARTED**
- P5 strict visual word/punctuation pass: **NOT STARTED**
- Tamil archival phase: **P0/P1 COMPLETE / P2 ACTIVE NEXT**

## English translation status

- English translation: **NOT STARTED**
- translation workspace: **NOT CREATED**
- prerequisite: complete/freeze Tamil through strict P5 before English begins.

## Current unresolved source questions

- Exact article-heading punctuation/spelling and final start/end boundaries for most Units 3–50 remain unverified at P1; the contents-derived spans are navigation hints only.
- Original unsplit 574 MB PDF checksum is unavailable from the five supplied transfer parts; only the exact five part hashes above are authoritative for the received source.
- No body-text reading is being guessed from contents or outside bibliography.

## Exact next activity

**P2 — directly transcribe and verify scans 1–27 in one coherent batch: front matter scans 1–17 plus Unit 1 `பாசியும் - தூசியும்!` scans 18–23 and Unit 2 `அதிக உயரம் தாண்டுவதற்கு` scans 24–27. Record every source-visible word/punctuation and physical-copy mark, directly verify Unit-1/Unit-2 starts and endings, preserve contents-title versus heading-title differences as separate witnesses, create/refresh dependent records only from the verified page layer, and update this root handover.**

## Rules for the next session

1. Fetch live `main` and read this handover first.
2. Preserve Publications 1–7 as frozen.
3. Read `publications/sinthanaiyum-seyalum/README.md`, `metadata/source.md`, `indexes/contents.md`, and `indexes/page-map.md` before P2 writes.
4. Treat all P1 unit spans as provisional until directly verified from scan headings/endings.
5. Do not mark a page verified without complete direct visual comparison.
6. Do not begin English translation.
