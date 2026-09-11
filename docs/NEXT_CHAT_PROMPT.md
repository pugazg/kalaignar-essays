# NEXT CHAT PROMPT — ஆறுமாதக் கடுங்காவல் / P2 scans 1–5

Continue directly in `pugazg/kalaignar-essays`, branch `main`, active publication:

`publications/aaru-maatha-kadungkaaval/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Root `HANDOVER.md` is the single authoritative handover. Publications **1–11 are RELEASE COMPLETE / FROZEN**.

## Durable state

- P0 — **IN PROGRESS**
  - raw file size — **282020019 bytes**
  - SHA-256 — **PENDING**
  - user-reported complete extent — **224 pages**
  - supplied artifact exposed for archival work — **150 pages**
  - source-completeness discrepancy — **OPEN**
- P1 — **COMPLETE / PASS FOR SUPPLIED 150-PAGE PDF ARTIFACT**
- P1 map — **150/150 structurally inspected**
- P2–P5 — **NOT STARTED**
- English — **BLOCKED**

P1 authority:

`publications/aaru-maatha-kadungkaaval/P1_SOURCE_STRUCTURE_REVIEW.md`

## Supplied-artifact P1 structure

- 1 — physical-copy mark
- 2 — title page
- 3 — imprint / first-edition page
- 4 — publisher note
- 5 — blank/reverse
- 6–7 — `காணிக்கை`
- 8 — illustrated `முரசு` page
- 9 — blank/reverse
- 10–66 — main text
- 67 — blank/reverse
- 68–106 — main text
- 107 — blank/reverse
- 108 — intertitle/transition
- 109 — blank/reverse
- 110–150 — main text

Scan 150 is the end of the supplied artifact only; do not call it proven publication end.

## Mandatory startup

Read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. this prompt
6. publication `README.md`
7. `metadata/source.md`
8. `indexes/page-map.md`
9. `P1_SOURCE_STRUCTURE_REVIEW.md`
10. `audit.md`

## Exact next activity — P2 scans 1–5

Process **exactly scans 1–5 as one batch**.

For each scan:

- visually inspect the whole page;
- create one canonical Markdown page record;
- preserve printed text exactly;
- keep physical-copy marks in a separate layer;
- record visible printed folio only; suppressed folio = null;
- apply historical-glyph decoding where Tamil text appears;
- do not normalize spelling/punctuation/spacing;
- unresolved reading -> `needs-review`, never guess.

After the five scans:
- synchronize controls;
- commit immediately;
- report correction/hold counts;
- set next batch to **scans 6–10**;
- stop before scan 6 unless explicitly asked to continue.

Do not resolve the open 150-vs-224 publication completeness discrepancy by inference.
