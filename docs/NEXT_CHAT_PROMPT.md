# NEXT CHAT PROMPT — பேசும் கலை வளர்ப்போம் / P4 source-completeness audit

Continue in `pugazg/kalaignar-essays`, branch `main`, active publication:

`publications/pesum-kalai-valarppom/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Root `HANDOVER.md` is the **single authoritative project handover**. Preserve Publications 1–10 as RELEASE COMPLETE / FROZEN.

## Controlling source

`TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`

- SHA-256: `73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`
- size: `105698402` bytes
- physical scans: **82**
- image-only
- source PDF must **not** be committed

The supplied scan is controlling authority. OCR/parsed text is not authority. Never silently modernise, correct, normalize or reconstruct Tamil.

## Durable gate state

- P0 — **COMPLETE / PASS**;
- P1 — **COMPLETE / PASS**;
- P2 — **COMPLETE / PASS — 82 of 82 VERIFIED**;
- P3 — **COMPLETE / PASS — 19 of 19 assemblies**;
- P4 — **NOT STARTED / NEXT**;
- P5 — **NOT STARTED**;
- English — **NOT STARTED / BLOCKED until Tamil freeze**;
- unresolved Tamil/source/assembly blockers entering P4 — **0**.

P3 assembly set:

- `articles/01-section-01.md` through `articles/19-section-19.md`;
- numbering/order **01–19 contiguous**;
- main-work source coverage **scans 7–82 / pp.5–80**;
- missing / unexpected extra assemblies **0 / 0**;
- detailed gate: `P3_ASSEMBLY_AUDIT.md`.

## Structural facts that must not regress

- scans 1–2 outside printed pagination;
- scans 3–82 = pp.1–80, `printed page = scan - 2`;
- source-numbered sections **1–19**;
- shared mid-page transitions: `12,16,22,27,31,34,38,51,55,67,70,79`;
- top-of-page section openings: `7,42,45,48,59,64,75`;
- suppressed/inferred folios: `3,4,5,6,7,42,45,48,59,64,75`;
- no printed contents page;
- no separate back-cover scan;
- scan 5 is physical-copy handwriting with **no printed publication text**.

## Source-witness distinctions / non-regression readings

- scan 1 cover: `பேசும் கலை வளர்ப்போம்`;
- scan 3 title page: `பேசும்கலை வளர்ப்போம்`;
- scan 6 `பதிப்புரை` date: `15—7—81`;
- scan 13 source correction: `வீடுதான்`;
- scan 74 source correction: `ஒரே வரியிலே` / `ஒரு வரிக்கு மேல்`;
- scan 81 `முழுவாழ்வு வாழ` → scan 82 `விடாமல் நம்மிடமிருந்து பறித்துக்கொண்டு விட்டது.`;
- preserve `(Mannerism)`, `மேனரிசம்`, `தவிர்க்கவொண்ணாத`, `ஷம்சுதீன்`, `நாலுகால்`, `கி. ஆ. பெ. விசுவநாதம்`, `காயிதே மில்லத்`, `தேனினுமினிய`, `நாற்பத்தி ஆறு`, `1962-ல்`, `நாஞ்சில் கி. மனோகரன்`, `“வாலிபப் பெரியார்”`, `எ.வி.பி. ஆசைத்தம்பி`, `என். வி. நடராசனார்` without normalization.

## Mandatory startup

Read completely before P4 work:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `docs/FUTURE_WORK_GUIDELINES.md`
3. root `HANDOVER.md`
4. this prompt
5. publication `README.md`
6. `metadata/source.md`
7. `indexes/contents.md`
8. `indexes/page-map.md`
9. `audit.md`
10. `P3_ASSEMBLY_AUDIT.md`
11. canonical page records and the 19 assemblies as required by the reconciliation

## Exact next activity — P4

Perform the **source audit / completeness review** in one coherent pass.

1. reconcile source identity/edition/scan count/checksum and the two distinct title witnesses;
2. confirm all **82 physical scans** have one canonical page record and no missing/duplicate scan record;
3. confirm all **19 source-numbered assemblies** exist, remain `source-complete`, and match the canonical section map;
4. reconcile each section start/end and all 12 shared transition scans against `indexes/contents.md` and `indexes/page-map.md`;
5. check that shared transition text is neither duplicated nor omitted between adjacent assemblies;
6. verify front matter, scan-5 handwriting, stamps and other physical-copy evidence remain outside printed reading text;
7. verify suppressed/inferred folios are never presented as directly printed numerals;
8. verify correction provenance and propagation, especially scan 13 `வீடுதான்` and scan 74 `வரியிலே` / `வரிக்கு`;
9. create/update a dedicated P4 completion-review record and record any old reading → corrected source-supported reading if a discrepancy is found;
10. synchronize `audit.md`, publication README, metadata/indexes as needed, root README, root `HANDOVER.md`, and this prompt only after P4 passes;
11. **do not begin P5 strict visual fidelity or English in the same step unless separately authorized**.

P4 is a source/completeness reconciliation gate. P5 is the later publication-wide direct word-by-word / punctuation-by-punctuation visual pass over all physical scans.
