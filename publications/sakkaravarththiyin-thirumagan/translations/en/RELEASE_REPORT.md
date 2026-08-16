# English Release Report — சக்கரவர்த்தியின் திருமகன்

Release gate: **E7 — English release closeout**  
Release date: **2026-08-16**  
Repository: `pugazg/kalaignar-essays`  
Branch: `main`

## Result

**E7 PASSED. ENGLISH RELEASE GATE CLOSED.**

All 14 English article translations are present, remain `translation_status: "verified"`, point to the expected frozen Tamil article blob SHAs, and had already passed T0–T5 plus publication-wide E6 consistency review. No release blocker was found.

No English article body was changed during E7.

## Release prerequisites

| Check | Result |
|---|---|
| Tamil physical scan records | **83 / 83 COMPLETE** |
| Strict visual word/punctuation fidelity | **83 / 83 PASS** |
| Tamil article assemblies | **14 / 14 COMPLETE / FROZEN** |
| Unresolved Tamil fidelity items | **0** |
| English drafts | **14 / 14** |
| T2 fidelity-reviewed | **14 / 14** |
| T3 voice-reviewed | **14 / 14** |
| T4 audited | **14 / 14** |
| T5 verified | **14 / 14** |
| E6 cross-article consistency | **PASSED** |
| Unresolved translation questions | **0** |
| Source PDF in Git repository | **No** |
| E7 release blockers | **0** |

## Repository state reviewed for E7

E7 was performed against the current `main` repository state before closeout bookkeeping. The recursive Git tree reviewed had tree SHA:

`6c58bb60cf10c8a5a960503e4dc213d9dc54f700`

Release-facing records fetched fresh from `main` included:

| Record | Pre-E7 blob SHA |
|---|---|
| root `README.md` | `a9b6438d847c2ee31a5e5945d99f321d0d3417dc` |
| root `HANDOVER.md` | `f1eb9a8a9ee8249a93e7f8b370301be6c92a59ff` |
| publication `README.md` | `d81f01ca7c9e68cf9be8de7e66cad33bd2e28d75` |
| `TRANSLATION_PLAN.md` | `0f8670bde38f7e363413a9b520e50d66edd0f60f` |
| `PUBLICATION_COMPLETION_REVIEW.md` | `de905cf39551dc8b8661281f7d023b0037c5cba8` |
| `VISUAL_TEXT_FIDELITY_REVIEW.md` | `dc92c5d3281f2216d3a4860f37ed4e5f66714291` |
| `audit.md` | `10fc47586985f709f3eb8f0693eae5a85b4142f2` |
| `metadata/source.md` | `461c84e693fec1196f13d0a893293aa303bba576` |
| `indexes/contents.md` | `850bcaea8bc62095710dc8d0204236690928c804` |
| `indexes/page-map.md` | `0c118204611b3de8175d730a1e2d414796cb809f` |
| English tracker `README.md` | `ea4b3b80f4ce91b22e37f953afd2b3362d386327` |
| `LEXICON.md` | `0034a408fb2416b7a0f53ab08854215ff453636a` |
| `TRANSLATION_REVIEW.md` | `9e47ab521350d5dc108f447ab5a0b1067fe26085` |

The recursive tree contained **no `.pdf` file**. The controlling source PDF therefore remains outside GitHub as required.

## Released English article set

| # | English file | English blob SHA reviewed | Frozen Tamil source SHA | Status |
|---:|---|---|---|---|
| 1 | `01-sakkaravarththiyin-thirumagan.md` | `1def855ffd58c800b2bededc4ef0095681a936bc` | `47a5b1fd0b28827bb098dda419b5bf864e9f3866` | verified |
| 2 | `02-thegamum-unarvum.md` | `84270626abbb0beb43919544a3a9fdafd62bf9aa` | `bb9131b7856b528e527136be8f4f60dca2999850` | verified |
| 3 | `03-sathi-nirupikkappadugirathu.md` | `d2c9ebab803a7074fc6c69f423533f6c32e6e16f` | `903dbb0a2b74bc1ffa173469bfdb3dfa6ce9b4b4` | verified |
| 4 | `04-kamarajan-aadkonda-dasaratharajan.md` | `47ba28ed14ec73f770cefdc5682e0cf7baaa86ac` | `9151694c1c473fd4c225aa8076d086e01931bc1e` | verified |
| 5 | `05-paraththuvaja-aasramama-paris-nagarathu-para.md` | `860d4f0953f137e41680855e1ca46b76af742558` | `f0b527ed76e10072c5875f0998add33cf09e6647` | verified |
| 6 | `06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md` | `efd9b08800c06a4260cc1b3512009d4189920f08` | `07ae8741f3b06fa9208a6478ebabea87d53a93f5` | verified |
| 7 | `07-vibishanarukku-vidai-yalippom.md` | `a1cb852f4723c99ddfd9a6dcd77bff69a1b2487d` | `1ae5db95c88df7ccdbd74b180c4427f8ee81d022` | verified |
| 8 | `08-naadaanda-mannan-naathiyatru-seththaan.md` | `4be90cc80c901ac73740eec606e0c8544f2fc49c` | `87d10ed53e55fdf6a1eb60f86517cc245644a71a` | verified |
| 9 | `09-thanthai-maganum-tharumam-thavariyavargal.md` | `b0e1f3ff0f9dc5d8070a3fc4a649e7a33c7150f2` | `d8b6b6cba29bb35e70d2009ebccad4b64cfffa9d` | verified |
| 10 | `10-vishnu-avatharam-enbathum-ramanidam.md` | `2c0841ec267737733835f4c9b4ffe99723e96506` | `e7a2b2e1d3b703d672b0be7569440217ccb03d3e` | verified |
| 11 | `11-nadappathellam-narayanan-seyala.md` | `129837b71365c1f009e9b632cc562fd339936587` | `b324e995d580ee021577b998d193d005fa6446ad` | verified |
| 12 | `12-maarisanai-thuraththi-sendra-ramanidam.md` | `7abd8900e453639b1bb67aa0ccc704349b959610` | `01aae57b137bfb3d762c4cb6a62e149bfdb78edb` | verified |
| 13 | `13-thurogigal-santhippu.md` | `86251130d1d71b405e0233bfa8c95b373ff5862c` | `369c3f4e5030c5810e815d13692372ae73849837` | verified |
| 14 | `14-kaariyamaagum-varaiyil-kaalai-pidi.md` | `a398839edb1b739d93773568534215917e6d81cf` | `e97314ada6b52c671742bb1526ed70acd1a26411` | verified |

Every English file's front matter was re-fetched during E7 and checked against the current Tamil article blobs in `main`.

## Link and tracker checks

- all 14 English files listed by `translations/en/README.md` exist;
- all 14 linked Tamil `source_tamil` article files exist;
- all 14 English front-matter `source_tamil_blob_sha` values match the corresponding current frozen Tamil blobs;
- all 14 English front-matter statuses remain `verified`;
- the tracker, translation plan and review ledger agree on **14 / 14 T5**, **E6 PASSED**, **0 unresolved**, and **English translation COMPLETE**.

## Source-witness / non-regression checks

E7 reconfirmed that release records continue to preserve the publication's independent source witnesses and source-bearing exceptions rather than silently normalising them:

- Article 5 contents `பரத்துவாஜர் ஆஸ்ரமமா - பாரீஸ் நகரத்து ‘பாரா’?` vs heading `பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’?`;
- Article 10 contents/heading `விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்!` vs scan-63 body `விஷ்ணு அவதாரம் என்பதும் ராமனிடமே`;
- Article 14 contents `காரியமாகும் வரையில் காலைப் பிடி!` vs heading `காரியமாகும் வரையில் காலைப் பிடி !`;
- scan 83 remains a separate promotional Article 12 witness and does not overwrite Article 12 body text;
- scan 82 closes Article 14 at the printed ornament; the lower `விடுதலை` advertisement remains outside Article 14;
- strict scan-82 reading `வர்ணிக்கிறான்` remains frozen;
- Article 6 **Kakapattar** vs Article 11 **Kaga Pattar**, and Article 2 **Ramachandramurti** vs Article 14 **Ramachandra Murti**, remain intentional source-sensitive differences;
- publication-wide source `ஆச்சாரியார்` remains **Achariyar**, Article 7 explicit `இராஜாஜி` remains **Rajaji**, and Article 11 plural remains **the Achariyars**.

## Voice / translation release rule

The released English layer remains governed by:

> **Translate the language; do not neutralise the voice.**

E7 does not reopen verified prose for stylistic polishing. No release bookkeeping change may be used to soften Kalaignar's direct address, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, exclamations, physical imagery or wordplay.

## Blockers

**None.**

## Final release state

- Tamil archival layer: **COMPLETE / FROZEN**
- English article translations: **14 / 14 VERIFIED**
- E6: **PASSED**
- E7: **PASSED / COMPLETE**
- English translation: **COMPLETE**
- English release gate: **CLOSED**
- unresolved release or translation questions: **0**

The next project activity is **not** to reopen this publication. Keep `சக்கரவர்த்தியின் திருமகன்` frozen unless a genuine source-supported defect is discovered. The next normal archival activity is intake of the next supplied Kalaignar essay/article publication under the repository's P0 workflow.
