# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**LIVE `main` IS AUTHORITATIVE over copied prompts or older checkpoints.**

## Repository state

Publications **1–9 are RELEASE COMPLETE / FROZEN**.

Active Publication **10 — `மீசை முளைத்த வயதில்` — Tamil P0–P5 COMPLETE / PASS / FROZEN; English E0–E5 COMPLETE / PASS; Articles 1–26 are T0–T5 VERIFIED; 26/26 English articles verified; E6 publication-wide English consistency review is next.**

Source PDFs are never committed.

## Mandatory startup

1. fetch live `main` first and preserve newer durable work;
2. read `ESSAY_TRANSLATION_GUIDE.md` completely;
3. read this root handover and `docs/NEXT_CHAT_PROMPT.md`;
4. read Publication 10 `TRANSLATION_PLAN.md`, `README.md`, `audit.md`, `metadata/source.md`;
5. read `translations/en/README.md`, `LEXICON.md`, `TRANSLATION_REVIEW.md`;
6. preserve Publications 1–9 and Publication 10's frozen Tamil layer unless new direct controlling-source evidence requires a formally documented reopening.

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

- E0–E5 — **COMPLETE / PASS**;
- T0/T1/T2/T3/T4/T5 — **26/26 PASS at every gate**;
- English body files — **26/26**;
- active English blockers — **0**;
- E6 publication-wide consistency — **NEXT**;
- E7 release closeout — pending.

Article 1 remains the voice-calibration baseline, not a mechanical lexical template. Exact source `உடன்பிறப்பே` remains **`Udanpirappē`**; direct salutation **`Udanpirappē,`**. `LEXICON.md` records **153** source-derived publication decisions through Article 26.

## E5 — Articles 23–26 — COMPLETE / PASS

All four Tamil sources were fetched fresh and matched their frozen P5 blobs before T0. Frozen Tamil edits: **0**.

| # | Tamil | English | Final verified English blob |
|---:|---|---|---|
| 23 | `சேவல் சண்டை` | **Cockfight** | `fbede1e68f63d9eb0ee369dd56ae668dd7c617af` |
| 24 | `மடல்` | **Letter** | `9d66aa7a24d1c8725b7c9ae914eadca978a2530c` |
| 25 | `ஆண்டு விழா` | **Annual Festival** | `b46a0dd815a945c7bd56ab61cbc1adf757761917` |
| 26 | `மயிலிறகு` | **Peacock Feather** | `4862200f97ea4711fc134384fe70355d311a936a` |

E5 gate result:

- T0 **4/4 PASS**;
- T1 **4/4 complete**;
- T2 **4/4 PASS**, material body corrections **6**, all Article 26;
- T3 **4/4 PASS**, extra body corrections **0**;
- T4 **4/4 PASS**, source-restraint body corrections **2**, both Article 26;
- T5 **4/4 VERIFIED**;
- omissions / added claims / unresolved source or terminology blockers **0/0/0**;
- source-boundary coverage **8/8, 6/6, 7/7, 10/10**.

E5 corrections that must not regress:

1. Article 26 source `கண்புடை பட்டு` is retained conservatively as `kanpudai-pattu`; do not invent an outside expansion.
2. Article 26 `திருமய` element remains represented as `sacred intoxication` in the selfish-purpose phrase.
3. Article 26 `இடையிலாப் பெண்டிர்` remains **`Waistless women`**, preserving source hyperbole.
4. Article 26 `முறுமிவால் மோகத்தால்` remains **`Murmuring with desire`**, not the erroneous `murmuring tail of desire`.
5. Article 26 `மலர்ப்பதி` remains source-bearing **`Malarppathi`**.
6. Article 26 `காலை வந்தாள். காதல் உண்டார்.` remains **`Morning came. They feasted on love.`**
7. Article 26 body must not include editorial wording such as `source-bearing` around `kanpudai-pattu`.
8. Article 26 `உயிர் மதியா ஒளி விளக்கே` remains **`O lamp of light who counted life as nothing!`**, not `reason`.

Other durable E5 source handling:

- Article 23 `காதம்` = `kadam`; `துர் நீதான்` = `Dur Neethan`; iron/silver cage reversal preserved.
- Article 24 source performance labels remain transliterated (`kankoodu-vari`, `kaan-vari`, `ul-vari`, `puravari`, `kilar-vari`, `therchi-vari`, `kaatchi-vari`, `eduththukkol-vari`); quoted Madhavi/Silambu material is translated only from frozen Tamil.
- Article 25 preserves `எரி/எலி` as `aflame/rat`, `முத்தாரம்/முத்த ஆரம்` as `pearl garland/garland of kisses`, `dosham`, `poison-test`, and `war-drum`.
- Article 26 `கிண்ணாரக் கிழவன்`, `ஒதிய மரமே`, `ஐயப்பசி`, `சக்கைகள்` remain conservative source-bearing forms (`old kinnaara`, `old odhiya tree`, `aiyappasi`, `sakkais`); `யாயும் ஞாயும்...` is translated only from frozen Tamil.

Full E0–E5 gate/blob/correction provenance is in `translations/en/TRANSLATION_REVIEW.md`.

## Exact next activity — E6 publication-wide English consistency review

When the user says proceed/continue:

1. fetch live `main` first;
2. re-read this handover, `ESSAY_TRANSLATION_GUIDE.md`, `TRANSLATION_PLAN.md`, English `README.md`, `LEXICON.md`, and `TRANSLATION_REVIEW.md`;
3. review **all 26 verified English articles as one publication**, in source order;
4. check recurring names/epithets, `Aththaan`, ideological/cultural vocabulary, title style, source-specific transliterations, source literary labels, quotation handling, source-page comments, dialogue/verse conventions, and Kalaignar's directness;
5. specifically look for accidental cross-article smoothing or inconsistent English choices that conflict with the 153-entry living lexicon;
6. preserve every correction in the E6 review provenance and capture new final blobs for any changed article;
7. verify all 26 source comments remain present and ordered and all article source blob metadata remains frozen-source correct;
8. do **not** modify frozen Tamil;
9. mark E6 PASS only when publication-wide inconsistencies/blockers reach **0**;
10. after E6 PASS, **E7 release closeout** becomes next. Do not declare the English publication released during E6.

---

# Publications 1–9 — RELEASE COMPLETE / FROZEN

Do not reopen them from stale prompts. Publication 9 remains frozen/released with E6/E7 PASS and blockers 0.