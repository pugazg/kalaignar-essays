# கொலைக்களம்!

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling source: `TVA_BOK_0063657_கொலைக்களம்.pdf`  
Physical scans: **40**  
Source SHA-256: `674a534f6c29e5abed9c7ebf52c3cfd143f494d6a21341b5d0624871c187a96c`  
File size: **55,495,728 bytes**  
Source PDF committed: **No**

## P0 source identity

The supplied scan is a small multi-piece Kalaignar publication whose cover prints:

- title: **`கொலைக்களம்!`**;
- author: **`கலைஞர். மு. கருணாநிதி`**;
- imprint/publisher line: **`முன்னேற்றப் பண்ணை`**, **`சென்னை-1`**.

Scan 2 prints `பதிப்புரிமை`, `முதற் பதிப்பு-52`, and `விலை அணா எட்டு`. The source prints only the abbreviated edition year `52`; this workspace must not silently expand the printed witness in diplomatic transcription. The same page carries a sales-rights/distributor line for `எஸ். எம். ராஜமுத்து கம்பெனி`; its full address is left for page-level transcription rather than normalized at intake.

The final scan (scan 40 / printed `40`) carries the printer line **`ஸ்ரீமகள் பிரஸ், சென்னை-1`**.

## Publication form — P0 assessment

This is **not a single standalone article**. The scan contains front matter followed by a sequence of separately headed prose units.

Preliminary source-visible structure for P1 confirmation:

- scan 1 — front cover;
- scan 2 — copyright / edition / price / sales-rights page;
- scans 3–4 — introductory/prefatory piece headed **`இன்பத் துளி!`**;
- scan 5 — heading **`கொலைக்களம்!`**;
- scan 10 — heading **`‘அஸ்தி’ கரையட்டும்!`**;
- scan 17 — heading **`பலியை நிறுத்துங்கள்!`**;
- scan 23 — heading **`விழலுக்கு நீர் இறைத்து...`**;
- scan 28 — heading **`சோதனை!`**;
- scan 34 — heading **`வீரமுழக்கம் செய்திடுவீர்!`**;
- scan 40 — final body page plus printer line.

These are **P0 heading witnesses only**. P1 must confirm every physical scan, exact start/end boundaries, printed-page behaviour, and whether `இன்பத் துளி!` is front matter or a numbered content unit. Do not create article assemblies from this preliminary list.

No printed contents page has been identified in the supplied 40 scans at P0.

## Physical-copy evidence observed at intake

The copy has substantial library/use evidence, especially in the front matter:

- scan 1: multiple library stamps, handwritten accession/date marks, heavy pen cancellation/marking, and a prominent paper crack/tear across the upper area;
- scan 2: circular library stamp, upper-right paper damage/tear, dark ink marks, and later handwriting/signature near the bottom;
- scan 3: library stamp/handwriting overlaps the upper area;
- later body scans show age wear / spotting to varying degrees.

Printed text and physical-copy marks must remain separate in page records.

## Gate status

- P0 — source intake / publication identification: **COMPLETE / PASS**
- P1 — metadata + canonical page map + contents/unit mapping: **NOT STARTED**
- P2 — page-level transcription: **NOT STARTED**
- P3 — article/unit assemblies: **NOT STARTED**
- P4 — source/completeness audit: **NOT STARTED**
- P5 — strict visual word/punctuation fidelity: **NOT STARTED**
- English translation: **NOT STARTED**
- current blockers at intake: **0**

## Source authority / non-regression

The supplied PDF scan is the controlling witness for this edition. Do not silently modernise, correct, normalise or reconstruct Tamil. Preserve separate source witnesses, old glyphs, punctuation, headings, names, numbers, and physical-copy evidence. OCR/parsed text may assist but is not authoritative.

## Exact next activity

**P1 — metadata + canonical page map + contents/unit mapping for all 40 scans.**

1. Re-resolve the controlling PDF and inspect all scans 1–40 in order.
2. Create `indexes/page-map.md` with one row per physical scan and only source-visible printed page numbers.
3. Create `indexes/contents.md` recording the absence/presence of a printed contents page and the source-visible unit-heading witnesses.
4. Confirm the exact span and status of `இன்பத் துளி!` and each of the six apparent main prose units.
5. Record cover/imprint/printer/source-witness distinctions without beginning lexical body transcription.
6. Update this README, `metadata/source.md`, root `HANDOVER.md`, and `docs/NEXT_CHAT_PROMPT.md`.
7. **STOP AFTER P1. Do not begin P2 transcription in the same activity.**
