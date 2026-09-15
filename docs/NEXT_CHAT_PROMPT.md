# NEXT CHAT PROMPT — ஆறுமாதக் கடுங்காவல் / P3 article assembly

Continue directly in `pugazg/kalaignar-essays`, branch `main`, active publication `publications/aaru-maatha-kadungkaaval/`. **LIVE MAIN IS AUTHORITATIVE.**

## Durable state

- P0 — **COMPLETE / PASS**
- P1 — **COMPLETE / PASS — 224/224 structurally mapped**
- P2 — **COMPLETE / PASS — 224/224 verified; 0 needs-review; 0 guessed readings**
- P2R — **COMPLETE — 224/224 physical scans re-audited**
- cumulative historical-glyph correction-event count — **20**
- guessed readings — **0**
- P3 — **NOT STARTED / NEXT**
- P4, P5 — **NOT STARTED**
- English — **BLOCKED until Tamil freezes**

Final P2R Batch R37 processed the user's requested remaining scans **206–224** / derivative extract pages **57–75**. Its only canonical correction was scan 209:

`என்ற இன நினைவுடன் படுப்போம்.` → **`என்ற இன்ப நினைவுடன் படுப்போம்.`**

After P2R, the user explicitly resolved the two former source-obscured holds:

- scan **18** — `ஆ[…]விடக்கூடிய` → **`ஆகிவிடக்கூடிய`**
- scan **198** — `அ[…]ந்தார்` → **`அடைந்தார்`**

P2 is therefore **COMPLETE / PASS — 224/224 verified**, with **0 needs-review** and **0 guessed readings**. Historical-glyph correction-event count remains **20**.

## Exact next activity — P3

Perform **article assembly / reading-copy construction**.

1. Read fresh:
   - `ESSAY_PROCESSING_GUIDE.md`
   - `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
   - `docs/FUTURE_WORK_GUIDELINES.md`
   - root `HANDOVER.md`
   - publication `README.md`
   - `indexes/page-map.md`
   - canonical page records required to establish boundaries.
2. Establish the source-supported assembly inventory and exact start/end boundaries before creating files. Do not infer article boundaries solely from printed folio sequence.
3. Create the P3 article assembly file(s) under `publications/aaru-maatha-kadungkaaval/articles/`.
4. Assemble only from canonical page records:
   - source wording must not change;
   - preserve source-supported headings;
   - preserve page order;
   - use the resolved canonical readings for scans 18 and 198; no unresolved `[…]` P2 hold remains;
   - page-boundary comments are allowed where useful;
   - editorial notes belong outside the article body.
5. Recheck the completed assembly against the canonical page sequence and synchronize `README.md`, `audit.md`, root `HANDOVER.md`, and `docs/NEXT_CHAT_PROMPT.md`.

Do **not** begin P4, P5 or English in the same iteration unless P3 is fully completed and the workflow controls explicitly authorize the next gate.
