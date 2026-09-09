# மீசை முளைத்த வயதில்

**கலைஞர் மு. கருணாநிதி — source-first archival workspace**

Controlling source: `TVA_BOK_0065746_மீசை_முளைத்த வயதில்.pdf`  
Source PDF committed: **No**

## Tamil archival layer — COMPLETE / PASS / FROZEN

- source SHA-256: `9054aa8ed82c68050b82ffe57d772c32fdcad0605f72d7983de490162669527d`;
- physical scans: **146**;
- P1 map: **146 / 146 scans**, **26 / 26 source-titled units**;
- P2 canonical pages: **146 / 146 VERIFIED**;
- P3 assemblies: **26 / 26**, **128 / 128 main-work pages**, scans **18–145 contiguous**;
- P4 strict fidelity: **146 / 146**, **207 / 207 corrections propagated**, unresolved **0**;
- P5: **COMPLETE / PASS / TAMIL FROZEN**.

Frozen authorities:

- `pages/` tree: `f7930b3696668cdbc2d692a284b49586d09a3372`;
- `articles/` tree: `b7593357dc5ba101362c7a303881bea4e63e9b68`;
- P3 audit blob: `0c2045346b879c85b6e2c46150a4aab686323016`;
- final P4 report blob: `2e085c2167c9dea409a13be4a7c980234e5a01df`.

Permanent source-title readings remain `அகப்பை சித்தர்`, `தளிர்`, `மயிலிறகு`. Translation commits do not alter this frozen Tamil authority.

## English workflow

Authorities:

- `TRANSLATION_PLAN.md`;
- `translations/en/README.md`;
- `translations/en/LEXICON.md`;
- `translations/en/TRANSLATION_REVIEW.md`.

Current phase state:

- E0 — **COMPLETE / PASS**;
- E1 Article 1 — **COMPLETE / PASS**;
- E2 Articles 2–11 — **COMPLETE / PASS**;
- E3 Articles 12–18 — **COMPLETE / PASS**;
- English body files / T0 / T1 / T2 / T3 / T4 / T5: **18 / 26** at every gate;
- unresolved English blockers: **0**;
- frozen Tamil changes during E0–E3: **0**;
- E4 Articles 19–22 — **NEXT**.

## E3 verified authorities

| # | Tamil title | English title | Verified English blob |
|---:|---|---|---|
| 12 | `நாடக மேடை` | **The Stage** | `36f38f510204fa9292058ae98624a1eca1cb624d` |
| 13 | `புகழ்` | **Fame** | `beb8d5629d75ece3095d2f7e1108147d169306d1` |
| 14 | `பச்சைக்கிளி` | **Green Parrot** | `016cb942d8008959c1941cf9ac3c4f01adace78d` |
| 15 | `தமிழே` | **O Tamil!** | `9545a62a2f152173a65f0aa0903a105adfd8943c` |
| 16 | `தேனலைகள்` | **Honey Waves** | `ad18f1b34782d96164a2d9faa5b2402b0ffa4c00` |
| 17 | `தோழி` | **Friend** | `3f1bcc85fc85c54efb6fec6e28e3277b8304d166` |
| 18 | `மருதாணி` | **Henna** | `5b02e665a8b05b395c1d16927e74ca70306d5da6` |

E3 review totals:

- T0–T5: **7 / 7 PASS at every gate**;
- material T2 corrections: **5**;
- additional T3 corrections: **0**;
- additional T4 corrections: **0**;
- omissions / added claims / unresolved source or terminology blockers: **0**;
- source-boundary comments: **PASS**;
- closing bullets and Article 16 scene separators: **preserved**.

The living lexicon now records **92** publication-specific decisions through Article 18. Detailed review history and all intermediate/final blobs are in `translations/en/TRANSLATION_REVIEW.md`.

## Exact next activity

**E4 — Articles 19–22 (`அருவி`, `முறம்`, `யாழ்`, `சிற்பி`).** Re-fetch all four frozen Tamil assemblies from live `main`, confirm each blob before T0, then process each independently through **T0→T5** without modifying frozen Tamil.
