# English Release Report — மீசை முளைத்த வயதில்

Release gate: **E7 — English release closeout**  
Release date: **2026-09-09**  
Repository: `pugazg/kalaignar-essays`  
Branch: `main`

## Result

**E7 PASSED. ENGLISH RELEASE GATE CLOSED.**

All **26 / 26** English article translations are present, remain `translation_status: "verified"`, retain the expected frozen Tamil source provenance, and match the exact E6-reviewed English blob matrix. E6 had already passed publication-wide consistency with **0 article-body corrections / 0 blockers**. No release defect was found during E7.

No English article body and no frozen Tamil file was modified during E7.

## Release prerequisites

| Check | Result |
|---|---|
| Tamil physical scans | **146 / 146 COMPLETE** |
| Tamil canonical page records | **146 / 146 VERIFIED** |
| Tamil article assemblies | **26 / 26 COMPLETE / FROZEN** |
| P4 strict visual fidelity | **146 / 146 PASS** |
| P4 corrections propagated | **207 / 207** |
| Unresolved Tamil/source items | **0** |
| English article files | **26 / 26** |
| T0 source prerequisite | **26 / 26 PASS** |
| T1 close draft | **26 / 26 PASS** |
| T2 bilingual fidelity | **26 / 26 PASS** |
| T3 Kalaignar voice | **26 / 26 PASS** |
| T4 terminology / quotation / source audit | **26 / 26 PASS** |
| T5 article verification | **26 / 26 VERIFIED** |
| E6 publication-wide consistency | **PASSED** |
| E6 source-page comments | **128 / 128, scans 18–145 contiguous** |
| Unresolved English / consistency items | **0** |
| Source PDF in Git repository | **No** |
| E7 release blockers | **0** |

## Frozen Tamil authority

- controlling source: `TVA_BOK_0065746_மீசை_முளைத்த_வயதில்.pdf`;
- source SHA-256: `9054aa8ed82c68050b82ffe57d772c32fdcad0605f72d7983de490162669527d`;
- frozen `pages/` tree: `f7930b3696668cdbc2d692a284b49586d09a3372`;
- frozen `articles/` tree: `b7593357dc5ba101362c7a303881bea4e63e9b68`;
- P3 audit blob: `0c2045346b879c85b6e2c46150a4aab686323016`;
- final P4 report blob: `2e085c2167c9dea409a13be4a7c980234e5a01df`;
- P5 completion review blob: `595cf83b2045ee0bd2efd5297dc9f8a7f536b68a`.

The source scan pixels remain ultimate authority. English release status does not supersede or alter the frozen Tamil layer.

## Pre-E7 repository checkpoint

E7 release validation began against live `main`:

- commit: `e8a85cc825c3b328c178ba47bafdb5cc24ca714c`;
- recursive root tree: `d3a11526ee568a160a31f8a996b4953188859736`;
- Publication 10 tree: `f0aea788e0087bee867335f383a7735d3ea6bae8`.

Key pre-E7 release-facing records:

| Record | Blob SHA |
|---|---|
| root `README.md` | `6925623ff7ffbf744696d0ad17e21959ded53f3a` |
| root `HANDOVER.md` | `73d00df3ec268ecf10000bf3c7d96fbe687b5a5b` |
| publication `README.md` | `b2e10f43177b7b2348871b130936c8e95c97ac5d` |
| `TRANSLATION_PLAN.md` | `0507ed423fa4a3e342334d062a0dea5c9d9ceeda` |
| `PUBLICATION_COMPLETION_REVIEW.md` | `595cf83b2045ee0bd2efd5297dc9f8a7f536b68a` |
| `audit.md` | `62a1c8e451912e93958192cfa6d61c19a542a425` |
| `metadata/source.md` | `765b2f36c1477941062e9b631ae19f988e240c42` |
| English `README.md` | `a25c531d396b7a3774995074b4b8b640d7ee747e` |
| `LEXICON.md` | `ab6fc2ac15a0309c2ab1feb53cac03417d3fd660` |
| `TRANSLATION_REVIEW.md` | `12a0e605d0389789b1d1079dbe0e02acb32a7f0d` |
| `docs/NEXT_CHAT_PROMPT.md` | `90bf9c62c2eb51c51a5188ad007c1df706f10a2e` |

## Released English article set

The current English directory was fetched fresh during E7. Its 26 article blobs exactly equal the E6-reviewed matrix; because live `main` had not advanced since the E6 checkpoint, the already-E6-validated front matter and source-provenance bytes are unchanged.

| # | English file | English blob SHA | Frozen Tamil source blob | Status |
|---:|---|---|---|---|
| 1 | `01-piraiye.md` | `1d07e03ba84353b2da7c0a344d6ae61c3223caf0` | `5aa32af4f4ded784ee48ac7bebed2a4adbb8c73c` | verified |
| 2 | `02-adikkaatru.md` | `e93c9ad4d37c81f5bea9decfddd9274469428e52` | `bc0133b4c7d65a4976e22f514405f4edf9dab3ba` | verified |
| 3 | `03-karuppu-pen.md` | `de2296d28841cb0643d979cf36cbbe7dc2e9ea9f` | `83d5a163a94636df59e3e2b5c587ee4f1e4420ca` | verified |
| 4 | `04-kadale.md` | `e0f1f5dbf2caf125584134665a3284582d09ae20` | `703c95c656f8b7ff2536765fd8a8e04a0dac42e2` | verified |
| 5 | `05-aaru.md` | `584b98a34a78d32d53b895e16422fa63c8f66af1` | `c721c64678f1b9c715e9c22e6cbc99ffdfd10b23` | verified |
| 6 | `06-vaazhiya-vaikarai.md` | `0c2c529cc0f72a522c8c11852e5ba14a88a89f95` | `ad42510f051c48bba896a2c6d20c0994e120b762` | verified |
| 7 | `07-agappai-siththar.md` | `cdf0a9aef9edb2c77a7d32382c66aaddb8e6868b` | `9b092fc67bb2bf2cb94df94e31abfabf5067b149` | verified |
| 8 | `08-malaiye-vaazhi.md` | `2417a5aa1daa4154445c4229d79413a0fa830a76` | `bcd00b14b0fd8810acba3195759abf7c66c310f6` | verified |
| 9 | `09-thalir.md` | `74e3bc25b4a48d3a2b1b79c37cbf8ec00c3e5be8` | `a67fc770ac6416d39d92efbe4d111c2d95ea2cb6` | verified |
| 10 | `10-vinmeen.md` | `2a57db76a77edff3372434a6b52e9edabb0d56fe` | `4528ec19f5efe1d7ffb68064d2b016801f2941ca` | verified |
| 11 | `11-thanimai.md` | `21357b316923e311a4dd234ee550dcecbf95e035` | `e6aa86d8f1f01cc5cb536fb601e8908053a5d078` | verified |
| 12 | `12-naadaga-medai.md` | `36f38f510204fa9292058ae98624a1eca1cb624d` | `8c9f14ced50e28ce620cd6d1ff31d3a69ee21b3a` | verified |
| 13 | `13-pugazh.md` | `beb8d5629d75ece3095d2f7e1108147d169306d1` | `ff4bbf7aae731741239a09aa5612d55f944c275a` | verified |
| 14 | `14-pachchaikkili.md` | `016cb942d8008959c1941cf9ac3c4f01adace78d` | `41195b3b9fcf54ddc5f3df041479ca4ca91fcd0f` | verified |
| 15 | `15-tamizhe.md` | `9545a62a2f152173a65f0aa0903a105adfd8943c` | `907600b23474c7a7a4376fc6dac2dc0083d5178f` | verified |
| 16 | `16-thenalaigal.md` | `ad18f1b34782d96164a2d9faa5b2402b0ffa4c00` | `72ccb3b32df2df70ad9949caddd2b773b70705a6` | verified |
| 17 | `17-thozhi.md` | `3f1bcc85fc85c54efb6fec6e28e3277b8304d166` | `a51eb1efe05152c22c4395e8a84725df197c48b6` | verified |
| 18 | `18-maruthaani.md` | `5b02e665a8b05b395c1d16927e74ca70306d5da6` | `83d3f1ffc24edc85e2b3935d6d7f87f67258a9b6` | verified |
| 19 | `19-aruvi.md` | `ea8fc9a11f6420c95dcfbf64e2e31d1af18d9275` | `4c8cf8c296bab2fa08583efc7178eb4cc5310df6` | verified |
| 20 | `20-muram.md` | `c8989508e445b99f396e9da0b844cdfa65d46efc` | `94cb40674f515520dde75b20de55b5558c2bd5ed` | verified |
| 21 | `21-yaazh.md` | `780c6b09d7a008eb197bdf5feacd4f0975b7ca8a` | `bf2eea3e6f00893499f209ac631f60d2a4256d5f` | verified |
| 22 | `22-sirpi.md` | `84a175942d395689c4c517eff69300adedffe740` | `9319a924fc172d0b80107c8c4c18157ffee67b30` | verified |
| 23 | `23-seval-sandai.md` | `fbede1e68f63d9eb0ee369dd56ae668dd7c617af` | `f489330920217021f2e3258ec7ddf8f260b171be` | verified |
| 24 | `24-madal.md` | `9d66aa7a24d1c8725b7c9ae914eadca978a2530c` | `9f8560b39ccbd6055f70398111e048b4ac49a9f3` | verified |
| 25 | `25-aandu-vizha.md` | `b46a0dd815a945c7bd56ab61cbc1adf757761917` | `3e10a5db4c9726dc19113cb8375d6c6ecb218c52` | verified |
| 26 | `26-mayiliragu.md` | `4862200f97ea4711fc134384fe70355d311a936a` | `15906fcda69226b4fb42f73a8b242837a831e6c3` | verified |

## Link / tracker / provenance checks

E7 reconfirmed:

- all **26** English article files exist in `translations/en/`;
- the current 26 English blobs are byte-identical to the E6-reviewed set;
- therefore all 26 front matters retain `translation_status: "verified"` and the exact frozen `source_tamil_blob_sha` values already revalidated during E6;
- all 26 linked Tamil source files remain under the unchanged frozen `articles/` tree;
- `TRANSLATION_PLAN.md`, English `README.md`, `TRANSLATION_REVIEW.md`, publication `README.md`, `audit.md`, `metadata/source.md`, root `HANDOVER.md`, root `README.md` and `docs/NEXT_CHAT_PROMPT.md` all entered E7 agreeing on **26/26 T5, E6 PASS, 0 unresolved / 0 blockers**;
- the living lexicon remains **153** source-derived decisions.

## E6 release authority retained

E7 does not reopen verified prose for stylistic polishing. The following E6 results remain release authority:

- source-page comments **128/128**, scans **18–145 contiguous**, gaps/overlaps **0/0**;
- English numbering **01–26 contiguous**;
- metadata English title / H1 agreement **26/26**;
- closing `●` **26/26**;
- Article 16 internal `○` separators preserved;
- Article 25 final parenthetical stage direction preserved;
- E6 article-body corrections **0**;
- E6 lexicon changes **0**;
- E6 blockers **0**.

## Source-witness / non-regression checks

Release closeout intentionally preserves source-driven differences rather than mechanically unifying them:

- Article 1 `goddess of freedom` vs Article 3 `queen of freedom`;
- Article 17 `tiger-claw marriage pendant` vs Article 25 `golden marriage pendant of tiger claws`;
- Article 18 normal `Henna` vs `maruthani` only in the final `Maruthan / maruthani` sound-play;
- Article 19 `Muthamizhars` vs Article 26 source-visible `Muthamizhvar—Muthamizhars`;
- source-driven `Ponni` / `Kaveri` and `Chera` / `Cheran Senguttuvan` variants;
- Article 21 `Kaanal Vari`, Article 24 Madhavi/Silambu quotations, and Article 26 `யாயும் ஞாயும்...` remain translations only from the frozen Tamil witness;
- Article 26 remains frozen in English with `kanpudai-pattu`, `Waistless women`, `Murmuring with desire`, `Malarppathi`, `Morning came. They feasted on love.`, and `O lamp of light who counted life as nothing!`;
- unfamiliar source labels such as `old kinnaara`, `old odhiya tree`, `aiyappasi` and `sakkais` are not externally expanded.

Permanent repository rule remains: exact source `உடன்பிறப்பே` → **`Udanpirappē`**; direct salutation **`Udanpirappē,`**.

## Source PDF absence

The complete pre-E7 recursive tree `d3a11526ee568a160a31f8a996b4953188859736` was inspected for `.pdf` paths. **No `.pdf` file is present in the repository tree.** The controlling source PDF remains outside GitHub as required.

## E7 body changes

**None.**

E7 is release validation and bookkeeping only. No verified English article body, frozen Tamil article, or canonical page record was changed.

## Blockers

**None.**

## Final release state

- Tamil archival layer: **P0–P5 COMPLETE / PASS / FROZEN**;
- English article translations: **26 / 26 T0–T5 VERIFIED**;
- E6 publication-wide consistency: **PASSED**;
- E7 release closeout: **PASSED / COMPLETE**;
- English translation: **COMPLETE**;
- English release gate: **CLOSED**;
- unresolved Tamil/source questions: **0**;
- unresolved English/translation/release questions: **0**;
- release blockers: **0**.

Publication 10 `மீசை முளைத்த வயதில்` is now **RELEASE COMPLETE / FROZEN**. Keep it closed unless a genuine source-supported defect is discovered. Do not begin another publication unless separately authorised by the user/live roadmap.
