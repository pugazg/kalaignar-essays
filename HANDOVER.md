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
- the printed contents lists 14 articles

See [`publications/sakkaravarththiyin-thirumagan/metadata/source.md`](publications/sakkaravarththiyin-thirumagan/metadata/source.md).

## Completed work

Front matter / navigation:

- scans 1–8 archived and verified
- printed contents transcribed
- source metadata created
- scan/printed-page map created

Article 1 — `சக்கரவர்த்தியின் திருமகன்`:

- source scans: **9–15**
- printed pages: **7–13**
- page records: **7 / 7 VERIFIED**
- `blocked`: **0**
- `needs-review`: **0**
- assembled article: [`publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md`](publications/sakkaravarththiyin-thirumagan/articles/01-sakkaravarththiyin-thirumagan.md)
- status: **source-complete**

Detailed audit: [`publications/sakkaravarththiyin-thirumagan/audit.md`](publications/sakkaravarththiyin-thirumagan/audit.md).

## Important verified source readings in Article 1

Do not regress these to plausible but non-source variants:

- scan 9: `பொய்ப்படி வளைவான பாதைகளில்`
- scan 12: `காண்கிறோமோ?`
- scan 12 heading: `குடிசை நுழைந்த பூமான்!`
- scan 13: `உண்மை பேதப்படுமேயானால் அப்படி பேதமுண்டாக்கி`
- scan 14: `அம்சுமான்` in both occurrences
- scan 14: source-visible `சாபவிமோசனம் பெறதும்` is retained

## Exact next activity

Process Article 2 — **`தேகமும் உணர்வும்`**.

Its boundaries have already been directly checked:

- scan **16** / printed page **14** begins `தேகமும் உணர்வும்`
- scan **22** / printed page **20** begins the next article, `சதி நிரூபிக்கப்படுகிறது`
- therefore Article 2 source range is scans **16–21**, printed pages **14–19**

Next steps:

1. Directly inspect scans 16–21.
2. Create one page record for each scan under `pages/`.
3. Do not infer unclear readings from context; apply the escalation process in the guide.
4. Mark a page `verified` only after direct visual comparison.
5. When all six are verified, assemble `articles/02-thegamum-unarvum.md` from those page records.
6. Update `indexes/page-map.md`, publication `README.md`, root `README.md`, and `audit.md`.

Do not begin English translation until the Tamil source layer for the relevant article has passed its completion gate.

## Future publications

For each new Kalaignar essay/article PDF:

- inspect the actual scan before metadata;
- check whether the work is a standalone article or a multi-article publication;
- for multi-article books, keep one source publication workspace and create separate article assemblies inside it;
- do not commit the PDF itself;
- preserve all physical pages, including front/back matter and advertisements, as page records while keeping them distinct from article text.
