# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

## Permanent source rule

The supplied scan is the controlling source. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. Preserve source-supported historical spelling, punctuation, wording, names, numbers, repetition, unusual grammar and typographical forms.

Distinguish printed text from library stamps, handwriting, accession marks, later annotations, damage and bleed-through.

**Source PDFs are not committed to this repository.**

Before processing any future source, read [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md) completely.

## Current publication

Workspace:

`publications/sakkaravarththiyin-thirumagan/`

Supplied source filename:

`TVA_BOK_0065662_சக்கரவர்த்தியின்_திருமகன்.pdf`

Source identity:

- 83 scan pages
- SHA-256: `5d7f8404a53c0766df896ddedf9978a3fd31f97b8e98625b70a93366412eb90d`
- title: `சக்கரவர்த்தியின் திருமகன்`
- author: `கலைஞர் மு.கருணாநிதி`
- source-visible edition statement: `முதற்பதிப்பு மே 1956 (வேலூர் திராவிடன் பதிப்பகம்)`; `மறு பதிப்பு - 2018`
- printed contents lists 14 articles

See [`publications/sakkaravarththiyin-thirumagan/metadata/source.md`](publications/sakkaravarththiyin-thirumagan/metadata/source.md).

## Completed work

Front matter / navigation:

- scans **1–8** archived and verified
- printed contents transcribed
- source metadata created
- scan/printed-page map maintained

Article 1 — `சக்கரவர்த்தியின் திருமகன்`:

- source scans: **9–15**
- printed pages: **7–13**
- page records: **7 / 7 VERIFIED**
- `blocked`: **0**
- `needs-review`: **0**
- assembled article: [`publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md`](publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md)
- status: **source-complete**

Article 2 — `தேகமும் உணர்வும்`:

- source scans: **16–21**
- printed pages: **14–19**
- page records: **6 / 6 VERIFIED**
- `blocked`: **0**
- `needs-review`: **0**
- assembled article: [`publications/sakkaravarththiyin-thirumagan/articles/02-thegamum-unarvum.md`](publications/sakkaravarththiyin-thirumagan/articles/02-thegamum-unarvum.md)
- scan **22** / printed p. **20** directly begins the next article
- status: **source-complete**

Detailed audit: [`publications/sakkaravarththiyin-thirumagan/audit.md`](publications/sakkaravarththiyin-thirumagan/audit.md).

## Important verified source readings

### Article 1

Do not regress these to plausible but non-source variants:

- scan 9: `பொய்ப்படி வளைவான பாதைகளில்`
- scan 12: `காண்கிறோமோ?`
- scan 12 heading: `குடிசை நுழைந்த பூமான்!`
- scan 13: `உண்மை பேதப்படுமேயானால் அப்படி பேதமுண்டாக்கி`
- scan 14: `அம்சுமான்` in both occurrences
- scan 14: `சாபவிமோசனம் பெறதும்`

### Article 2

- scan 16: source prints `(ஆகஸ்டு 154)`; do not normalize it
- scan 17: `எப்படி பெய்ப்படி`, `அவர்கட்கு`, `தையல் சீதை`
- scan 18 subsection: `பட்டாபிஷேகம்`
- scan 18: `ஏற்றதொரு நாள்`
- scan 20: enlarged scan confirms `தாம்பிரபு`
- scan 18 and scan 20 contain source-visible unmatched opening quotation punctuation; do not silently repair it
- scan 21 ends with `அதற்கு ராமனும் உடந்தை, என்கிற உண்மைதான் அது!` followed by the printed ornament

## Exact next activity

Process Article 3 — **`சதி நிரூபிக்கப்படுகிறது`**.

Known source facts:

- scan **22** / printed page **20** directly shows the Article 3 heading and start boundary
- printed contents says Article 4 — **`காமராஜன் ஆட்கொண்ட தசரதராஜன்!`** — starts on printed page **24**
- if the current +2 scan/page relation continues, that would place the next boundary around scan **26**, but this is only a navigation projection

Next steps:

1. Directly inspect scans beginning at **22**.
2. Directly inspect the projected scan **26** and confirm the Article 4 heading before declaring Article 3's end boundary.
3. Create one verified page record per Article 3 scan.
4. Apply the difficult-reading escalation protocol wherever necessary; do not infer from context.
5. Assemble `articles/03-sathi-nirupikkappadugirathu.md` only after every Article 3 page is verified and its end boundary is source-confirmed.
6. Update `indexes/page-map.md`, publication/root README, audit and this handover.

Do not begin English translation until the Tamil source layer for the relevant article has passed its completion gate.

## Future publications

For each new Kalaignar essay/article PDF:

- inspect the actual scan before metadata;
- check whether the work is a standalone article or a multi-article publication;
- for multi-article books, keep one source publication workspace and create separate article assemblies inside it;
- do not commit the PDF itself;
- preserve all physical pages, including front/back matter and advertisements, as page records while keeping them distinct from article text.
