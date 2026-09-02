# Next Chat Prompt — Kalaignar Essays / இன முழக்கம்

Use this file only as a convenience handoff. **Live `main` and root `HANDOVER.md` are authoritative.**

Continue directly in:

`pugazg/kalaignar-essays`

Branch: `main`

Active publication:

`publications/ina-muzhakkam/` — **இன முழக்கம்**

Controlling source:

`TVA_BOK_0063958_இன_முழக்கம்.pdf`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. The last confirmed durable state before this prompt synchronization includes:

`03c3ab85a69fbabde663f1189bd83c71a4e720fa` — `Record Ina Muzhakkam Visayar placement correction in handover`

If `main` has advanced, preserve the newer durable state. **Do not reset, overwrite, repeat or reopen later completed work merely because this prompt records an older checkpoint.**

Before every write, re-fetch the target file and current live state as needed. Work directly on `main`.

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. root `HANDOVER.md`
5. this `docs/NEXT_CHAT_PROMPT.md`
6. `publications/ina-muzhakkam/README.md`
7. `publications/ina-muzhakkam/metadata/source.md`
8. `publications/ina-muzhakkam/indexes/contents.md`
9. `publications/ina-muzhakkam/indexes/page-map.md`
10. `publications/ina-muzhakkam/STRUCTURAL_REASSEMBLY_REVIEW.md`
11. all staging files under `publications/ina-muzhakkam/transcription-intake/`, including `USER_CORRECTIONS.md`

## Publication-specific user rule

The user supplied the complete word-to-word transcription and explicitly instructed:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Treat the user transcription as the lexical baseline during structural/P2 transfer. The scan controls structure and physical evidence. Do **not** silently change a word because the scan appears to carry another spelling; document such a lexical witness issue for later fidelity handling.

## Durable intake state

- source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`
- physical scans: **50**
- first edition: **செப்டம்பர் 1951**
- publisher: **முன்னேற்றப் பண்ணை, சென்னை**
- P0: **COMPLETE**
- P1 metadata / contents / physical page map: **COMPLETE**
- supplied 50-scan structural transcription reassembly: **COMPLETE / STAGING**
- P2 canonical page records: **0 / 50**
- P3 assemblies: **0 / 6**
- P4: **NOT STARTED**
- P5: **NOT STARTED**
- English translation: **NOT STARTED**
- blockers: **0**

Printed contents witness:

1. `இன முழக்கம்` — 4
2. `சொர்க்க லோகத்தில்` — 13
3. `முரசறைவாய்` — 24
4. `பழிக்குப் பழி` — 29
5. `ஆரியம் பேசுகிறது` — 37
6. `கவிதைகள்` — 40

Important structural decisions already established:

- non-source stamps/handwriting/OCR garbage excluded from printed text;
- edition/date/price belong to scan 3;
- source speaker labels and ornaments restored in `இன முழக்கம்`;
- **scan 10 `விசயர்` correction:** it is a misplaced supplied word, not noise. Retain it after `கர்வத்தால் கனத்துப்போன கனக`, yielding `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`; the earlier removal decision is superseded;
- scan-22 trailing `2` removed;
- scan-24 and scan-37 promotional matter kept outside article bodies;
- `பழிக்குப் பழி` final lines belong on scan 37, not scan 36;
- scan 40 is poetry introductory/review matter;
- `வா!` begins scan 43;
- `யோசித்துப் பார்!` begins scan 44;
- poetry lineation is restored in the staging transcription;
- scan 50 is a catalogue/advertisement unit.

## EXACT NEXT ACTIVITY

Create and directly verify **P2 canonical page records for scans 1–25**.

For each scan:

1. inspect the controlling PDF directly;
2. create one `pages/` Markdown record;
3. separate `# அச்சு உரை` from `## அச்சு அல்லாத / physical-copy marks`;
4. preserve the user lexical baseline while carrying forward the established structural corrections and `USER_CORRECTIONS.md` overrides;
5. on scan 10, preserve the exact corrected sequence `கர்வத்தால் கனத்துப்போன கனக விசயர் தலைகளில்...`;
6. record a printed page numeral only when directly visible;
7. record page-to-page continuation and article/promotion boundaries in audit notes;
8. update page-map/README/root handover after the batch;
9. **stop after scans 1–25 P2** — do not begin P3 assemblies in the same activity.

Publications 1–4 remain **COMPLETE / FROZEN / RELEASED** and must not be reopened absent a genuine source-supported or release-blocking defect.