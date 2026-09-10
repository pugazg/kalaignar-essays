# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**  
This is the **single authoritative project handover**.

## Repository state

Publications **1–10 are RELEASE COMPLETE / FROZEN**.  
Publication 11 **`பேசும் கலை வளர்ப்போம்` is ACTIVE — Tamil FROZEN; English translation phase ACTIVE**.

Do not reopen Publications 1–10 from stale prompts. Do not reopen Publication 11 Tamil without genuinely new source evidence. Source PDFs are never committed.

---

# Publication 11 — பேசும் கலை வளர்ப்போம்

Workspace: `publications/pesum-kalai-valarppom/`  
Controlling source: `TVA_BOK_0063826_பேசும்கலை_வளர்ப்போம்.pdf`

## Mandatory startup

Before any further English work, fetch/read fresh:

1. `ESSAY_TRANSLATION_GUIDE.md`;
2. `ESSAY_PROCESSING_GUIDE.md`;
3. `docs/FUTURE_WORK_GUIDELINES.md`;
4. this root `HANDOVER.md`;
5. `docs/NEXT_CHAT_PROMPT.md`;
6. publication `README.md`;
7. publication `TRANSLATION_PLAN.md`;
8. `translations/en/README.md`;
9. `translations/en/LEXICON.md`;
10. `translations/en/TRANSLATION_REVIEW.md`;
11. the exact frozen Tamil article and English article being reviewed.

## Controlling source / identity

- scan-1 cover/workspace form: **`பேசும் கலை வளர்ப்போம்`**;
- scan-3 title-page form: **`பேசும்கலை வளர்ப்போம்`**;
- publisher: **பாரதி பதிப்பகம்**;
- edition: **எட்டாம் பதிப்பு — செப்டம்பர் 1996**;
- physical scans: **82**, image-only;
- size: **105,698,402 bytes**;
- SHA-256: **`73972aca1b615a7cbe9d5fe4361d2312b9d4e47f9ee022b2450572807c88bbf7`**;
- source PDF committed: **No**.

## Tamil archival layer — COMPLETE / FROZEN

- P0–P5 — **COMPLETE / PASS**;
- canonical page records — **82/82 VERIFIED**;
- source-numbered assemblies — **19/19**;
- P5 strict visual fidelity — **82/82 PASS**;
- P5 corrections — **33/33 propagated**;
- unresolved Tamil discrepancies — **0**;
- Tamil archival layer — **FROZEN**.

Structural authority: scans **3–82 = printed pp.1–80**; source-numbered sections **1–19**; shared mid-page transitions `12,16,22,27,31,34,38,51,55,67,70,79`; no printed contents page or separate back-cover scan.

## English durable state

- E0 workspace/planning — **COMPLETE / PASS**;
- T0 source prerequisite — **19/19 PASS**;
- English body files — **1/19**;
- T1 close draft — **1/19**;
- T2 bilingual fidelity — **1/19**;
- T3 Kalaignar voice — **1/19**;
- T4 terminology / quotation / citation — **1/19**;
- T5 — **0/19**;
- unresolved English blockers — **0**;
- frozen Tamil edits during English work — **0**.

E0/T0 source baseline commit: **`3f64a17ecb18cf658cc281b17d9c34b5b3632d5a`**.

### Section 1 — T1 / T2 / T3 / T4 COMPLETE

Tamil authority:

- `publications/pesum-kalai-valarppom/articles/01-section-01.md`;
- scans **7–12 / printed pp.5–10**;
- frozen blob **`e5517b7cc344554d51af4092599059d481039c1e`**.

English:

- `publications/pesum-kalai-valarppom/translations/en/01-section-01.md`;
- T1 historical blob — `d36aec208ea15b970795a7717dd770d2d27251d8`;
- post-T2 blob — `d185b201c1113d99400d31579e773ae167cbb8a0`;
- post-T3 / post-T4 blob — **`bede85599ff634ef8ce7d6bd85aa6b9a9e035289`**;
- `translation_status` — **voice-reviewed**;
- T2 — **PASS after 6 corrections**;
- T3 — **PASS after 4 voice corrections**;
- T4 — **PASS with 0 English body corrections**;
- source-page comments — **6/6 retained**;
- T5 — **pending**.

T4 audit result:

- pre-existing Section 1 lexicon decisions — **11/11 PASS**;
- Section 1 T4-approved lexicon/proper-name/source-label decisions — **16** after adding five useful source-derived entries;
- publication title **Let Us Develop the Art of Speaking** — **T4 approved**;
- Bharathidasan quotation/attribution — **PASS / source-based**;
- Valluvar quotation/explanation/`Power of Speech` — **PASS / source-based**;
- imported published English quotation wording — **No**;
- `1970` — **PASS**;
- Hyde Park / source `(HydePark)` — **PASS**;
- `V. K. Krishna Menon` — **PASS**;
- `U.N. Assembly` — **PASS**, with no unsupported `General Assembly` expansion;
- source `உடன்பிறப்பே` occurrences in Section 1 — **0**;
- unresolved T4 issues — **0**;
- frozen Tamil edits — **0**.

T4 required no body correction, so its English input/output blob is the same `bede85599ff634ef8ce7d6bd85aa6b9a9e035289`. Correction provenance from T2/T3 and the T4 zero-correction audit are recorded in `translations/en/TRANSLATION_REVIEW.md`.

Permanent translation rule: exact source `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation **`Udanpirappē,`**, only where the exact Tamil form occurs. The source supplies numbered sections only; do **not** invent descriptive English section titles.

## Exact next activity — E1 / Section 1 T5 article verification

Re-fetch and require:

- frozen Tamil `articles/01-section-01.md` blob **`e5517b7cc344554d51af4092599059d481039c1e`**;
- current English `translations/en/01-section-01.md` blob **`bede85599ff634ef8ce7d6bd85aa6b9a9e035289`**.

Perform the final Section 1 verification gate:

1. reconcile T0, T1, T2, T3 and T4 provenance;
2. confirm English front matter points to the exact frozen Tamil authority and source span scans 7–12 / pp.5–10;
3. confirm `translation_status` is still `voice-reviewed` before T5;
4. confirm all six source-page comments remain present and ordered;
5. confirm T2 correction count **6**, T3 correction count **4**, T4 body correction count **0**;
6. confirm Section 1 lexicon/T4 decisions and quotations/source labels are synchronized;
7. confirm unresolved English blockers **0** and frozen Tamil edits **0**;
8. confirm no source-drift or status/documentation regression.

If every check passes, change only the English status as needed to `translation_status: "verified"`, record the resulting final verified English blob SHA in all dependent English/status records, and mark Section 1 T5 **PASS / calibration sequence COMPLETE**.

**Do not start Section 2 in the same activity.** After T5 closure, Section 2 T1 will become the next activity. Do not modify frozen Tamil.

---

# Frozen prior boundary — Publication 10

Publication 10 `மீசை முளைத்த வயதில்` remains **RELEASE COMPLETE / FROZEN**.