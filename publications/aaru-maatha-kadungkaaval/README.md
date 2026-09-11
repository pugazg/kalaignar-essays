# ஆறுமாதக் கடுங்காவல்

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling publication: **`ஆறுமாதக் கடுங்காவல்`**  
Expected complete source extent: **224 physical PDF pages**  
Current attached source payload: `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf` — currently exposed as **150 pages**  
Source PDF committed: **No**

## User-confirmed bibliographic identity

- தலைப்பு — **`ஆறுமாதக் கடுங்காவல்`**
- ஆசிரியர் — **`கலைஞர் மு. கருணாநிதி`**
- வெளியீடு — **`திராவிடப் பண்ணை`**
- பதிப்பு — **`முதல் பதிப்பு, 1953`**
- complete PDF/page extent — **224 pages**

User-supplied publication description:

> **ஆறு மாத காலம் சிறைத்தண்டனை பெற்ற கலைஞர், பாளையங்கோட்டை சிறைச்சாலையில் தனிக் கொட்டடியில் அடைக்கப்பட்டிருந்தார். அந்தக் காலத்தில் கலைஞர் அனுபவித்த சிறை வாழ்க்கை குறித்த நினைவுப் பதிவு இது.**

This description is retained as **user-supplied bibliographic/context metadata**. It is not silently inserted into the source transcription unless the same wording is directly found in the controlling scan.

## Current state

- Publication 12 — **ACTIVE**
- P0 source intake / publication identification — **IN PROGRESS**
- authoritative expected physical pages — **224**
- current accessible attachment pages — **150 / 224**
- current attached file size — **282020019 bytes**
- PDF type — **image-only scan / no usable parsed text layer**
- source title — **`ஆறுமாதக் கடுங்காவல்`**
- bibliographic author — **`கலைஞர் மு. கருணாநிதி`**
- title-page author line previously observed — **`மு. கருணாநிதி`**
- publisher — **`திராவிடப் பண்ணை`**
- edition — **`முதல் பதிப்பு, 1953`**
- source SHA-256 — **PENDING**
- P1 page/structure mapping — **BLOCKED for scans 151–224 until complete source is accessible**
- P2 page transcription — **NOT STARTED**
- P3 assemblies — **NOT STARTED**
- P4 source/completeness audit — **NOT STARTED**
- P5 strict visual fidelity — **NOT STARTED**
- English translation — **BLOCKED until Tamil is complete/frozen**

## Source-access discrepancy

The currently attached binary is exposed by the file service as **150 pages**, but the user confirms that the complete PDF/publication has **224 pages**.

Therefore:

- **224 pages is the authoritative expected source extent**;
- the current accessible 150-page payload must not be mistaken for the complete source;
- P0 cannot close against a 150-page file;
- P1 may inspect scans 1–150 provisionally, but a canonical 1–224 page map cannot close until scans 151–224 are accessible;
- no final source SHA-256 may be attached to the complete 224-page source until the complete file is available.

## Publication form

Treat this as a **single book-length prison memoir / chronological political narrative** unless the complete 224-page P1 mapping proves a different internal structure. The user-confirmed description identifies it as a recollection of Kalaignar's prison life during a six-month sentence, including solitary confinement at Palayamkottai prison.

## Historical Tamil glyph policy — mandatory

This 1953 edition uses older Tamil metal-type forms. All transcription must follow:

`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`

Core rule:

> **Read character identity, not modern visual resemblance.**

For every body page during P2/P5:

- inspect at enlarged/native resolution;
- explicitly check `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- encode only proven historical character identity in modern Unicode;
- preserve source spelling, grammar, vocabulary and punctuation;
- never global-replace;
- leave uncertain clusters `needs-review`.

## Confirmed opening observations from currently accessible scans

- scan 1 — later physical-copy/donation mark;
- scan 2 — title page;
- scan 3 — first-edition/imprint page;
- scan 4 — publisher note;
- scan 5 — near-blank reverse/show-through;
- scans 6–7 — `காணிக்கை` dedication;
- scan 8 — illustrated `முரசு` page;
- scan 9 — near-blank reverse/show-through;
- scan 10 — chronological narrative begins.

These are provisional P0 observations. Full publication structure must be mapped across **all 224 pages**.

## Exact next activity

**Resolve complete-source access first.**

1. make the complete **224-page PDF** accessible;
2. compute and record the exact SHA-256 and file size of that complete source;
3. close P0 only against the complete 224-page file;
4. perform P1 structural mapping across **scans 1–224**;
5. do not begin bulk P2 transcription until P1 is complete.
