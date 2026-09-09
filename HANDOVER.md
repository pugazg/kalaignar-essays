# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**

## Repository state

Publications **1–9 are RELEASE COMPLETE / FROZEN**.

Active Publication **10 — `மீசை முளைத்த வயதில்` — Tamil P0–P5 COMPLETE / PASS / FROZEN; English E0–E4 COMPLETE / PASS; Articles 1–22 are T0–T5 VERIFIED; 22/26 English articles verified; E5 Articles 23–26 is next.**

Source PDFs are never committed.

## Mandatory startup

1. fetch live `main` first and preserve newer durable work;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely;
3. read this root handover and `docs/NEXT_CHAT_PROMPT.md`;
4. read Publication 10 `TRANSLATION_PLAN.md`, `README.md`, `audit.md`, `metadata/source.md`;
5. read `translations/en/README.md`, `LEXICON.md`, `TRANSLATION_REVIEW.md`;
6. fetch every active Tamil article fresh and match its frozen blob before T0;
7. preserve Publications 1–9 and Publication 10's frozen Tamil layer unless new direct controlling-source evidence requires a formally documented reopening.

---

# Publication 10 — மீசை முளைத்த வயதில்

Workspace: `publications/meesai-mulaiththa-vayathil/`

## Frozen Tamil authority

- source `TVA_BOK_0065746_மீசை_முளைத்த_வயதில்.pdf`;
- SHA-256 `9054aa8ed82c68050b82ffe57d772c32fdcad0605f72d7983de490162669527d`;
- physical scans **146**;
- canonical pages **146/146 VERIFIED**;
- source-titled assemblies **26/26**;
- main-work pages **128/128**;
- frozen `pages/` tree `f7930b3696668cdbc2d692a284b49586d09a3372`;
- frozen `articles/` tree `b7593357dc5ba101362c7a303881bea4e63e9b68`;
- P3 audit `0c2045346b879c85b6e2c46150a4aab686323016`;
- final P4 report `2e085c2167c9dea409a13be4a7c980234e5a01df`;
- P4 corrections **207/207 propagated**;
- unresolved Tamil/source blockers **0**.

Permanent source-title readings remain `அகப்பை சித்தர்`, `தளிர்`, `மயிலிறகு`. P5 is **COMPLETE / PASS / TAMIL FROZEN**. English/tracker commits do not change this authority.

## English phase state

- E0–E4 — **COMPLETE / PASS**;
- T0/T1/T2/T3/T4/T5 — **22/26 PASS at every gate**;
- English body files — **22/26**;
- active English blockers — **0**;
- E5 Articles 23–26 — **NEXT**;
- E6/E7 — pending.

Article 1 remains the voice-calibration baseline, not a mechanical lexical template. Exact source `உடன்பிறப்பே` remains **`Udanpirappē`**; direct salutation **`Udanpirappē,`**.

## E4 — Articles 19–22 — COMPLETE / PASS

All four Tamil sources were fetched fresh and matched their frozen P5 blobs before T0. Frozen Tamil edits: **0**.

| # | Tamil | English | Final verified English blob |
|---:|---|---|---|
| 19 | `அருவி` | **Waterfall** | `ea8fc9a11f6420c95dcfbf64e2e31d1af18d9275` |
| 20 | `முறம்` | **Winnowing Tray** | `c8989508e445b99f396e9da0b844cdfa65d46efc` |
| 21 | `யாழ்` | **Yaazh** | `780c6b09d7a008eb197bdf5feacd4f0975b7ca8a` |
| 22 | `சிற்பி` | **The Sculptor** | `84a175942d395689c4c517eff69300adedffe740` |

E4 gate result:

- T0 **4/4 PASS**;
- T1 **4/4 complete**;
- T2 **4/4 PASS**, material body corrections **3**;
- T3 **4/4 PASS**, extra body corrections **1**;
- T4 **4/4 PASS**, body corrections **0**;
- T5 **4/4 VERIFIED**;
- omissions / added claims / unresolved source or terminology blockers **0/0/0**;
- source-boundary coverage **6/6, 5/5, 7/7, 12/12**.

E4 corrections that must not regress:

1. Article 20 source `கிளி கொண்டு` fear element restored as `men like you, gripped by fear...`; frozen Tamil remains unchanged.
2. Article 21 `தொட்டிமுத்தான்` → `touched and kissed`, not merely touched.
3. Article 22 `என் நெஞ்சில் நீ கிளம்பும்` → `until you rose in my heart`, not “fire rose”.
4. Article 22 T3 `சேரனும் நமது இனத்தவன்` → `the Chera too is of our race`, preserving direct source force.

`LEXICON.md` records **117** publication-specific decisions through Article 22. Durable E4 choices include **Waterfall**, **Winnowing Tray**, `Puram/Akam`, the `tamarind/tiger` wordplay, **Yaazh**, `Kaanal Vari`, `maapakam`, `Kalaivaanan`, `oppari`, `Chera domination`, and contextual handling of source-visible `சிற்பியின் விழாவில்`. Full gate/blob provenance is in `TRANSLATION_REVIEW.md`.

## E5 source set — Articles 23–26

| # | Tamil title | Frozen Tamil blob |
|---:|---|---|
| 23 | `சேவல் சண்டை` | `f489330920217021f2e3258ec7ddf8f260b171be` |
| 24 | `மடல்` | `9f8560b39ccbd6055f70398111e048b4ac49a9f3` |
| 25 | `ஆண்டு விழா` | `3e10a5db4c9726dc19113cb8375d6c6ecb218c52` |
| 26 | `மயிலிறகு` | `15906fcda69226b4fb42f73a8b242837a831e6c3` |

## Exact next activity — E5 Articles 23–26

1. fetch live `main` first;
2. re-read this handover, translation plan, English tracker/lexicon/review ledger and `ESSAY_TRANSLATION_GUIDE.md`;
3. fetch Articles 23–26 fresh and confirm each live Tamil blob matches the matrix above before T0;
4. process all four in source order independently through **T0→T1→T2→T3→T4→T5**;
5. derive terminology from each source; do not mechanically reuse earlier English when context differs;
6. update `LEXICON.md` and preserve review corrections/blob provenance in `TRANSLATION_REVIEW.md`;
7. synchronize all publication/root trackers and next prompt;
8. do **not** alter frozen Tamil;
9. after E5 all **26/26** should be T5 verified; then perform **E6 publication-wide English consistency review** before E7 release closeout.

---

# Publications 1–9 — RELEASE COMPLETE / FROZEN

Do not reopen them from stale prompts. Publication 9 remains frozen/released with E6/E7 PASS and blockers 0.
