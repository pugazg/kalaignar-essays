# E6 Publication-wide English Consistency Review — சிந்தனையும் செயலும்

Publication: `publications/sinthanaiyum-seyalum/`  
Scope: all **50** verified English article files  
Authority: frozen/re-frozen Tamil assemblies + complete translation review/lexicon chain  
Result: **PASS**

## Gate rule

E6 is a consistency and fidelity review of already T5-verified English. It does **not** authorise normalising source-sensitive differences, importing external facts or published translations, or changing frozen Tamil to make English look uniform.

Every finding was classified as one of:

- **consistent**;
- **deliberate contextual/source-witness exception**;
- **correction required**.

## E6-A — Inventory / front matter / source pins

**PASS.**

- numbered English article files: **50 / 50**, exactly Articles 01–50;
- duplicate/missing article numbers: **0 / 0**;
- `translation_status: verified`: **50 / 50**;
- `publication`, article number, Tamil title, English title, `source_tamil`, source Tamil blob SHA, scan range, language and translation method: **PASS**;
- all **50 / 50** stored `source_tamil_blob_sha` values match the live frozen Tamil article blobs on `main`;
- Tamil authority remained unchanged.

### E6 metadata correction — Articles 1–10

E6 found one genuine cross-publication schema inconsistency: Articles **1–10** lacked the diplomatic `contents_title_ta` front-matter field that Articles 11–50 already carried.

The field was added to Articles 1–10 only. **No English body text, source comment, source pin, scan range, status or Tamil text was changed.**

| # | Added `contents_title_ta` | New English blob after E6 |
|---:|---|---|
| 1 | `பாசியும் - தூசியும்!` | `0429d9ca9fed6b869163581e8cd0510fa9d8328c` |
| 2 | `அதிக உயரம் தாண்டுவதற்கு` | `9faffb33e8408df5bc2f23de1bf6b5a23632dadd` |
| 3 | `என் பெயர் புரட்சி` | `4c742d02dc46d8da257cb93401b42ff9b8ea2990` |
| 4 | `குருகுலம்!` | `2caa98f16a51f7cb9e53519a40940284df52c3e8` |
| 5 | `ஜனநாயக நெறி` | `d0a2cfae2c5d06ab01cbcd08726bb0f1a1821589` |
| 6 | `வாக்குச் சீட்டின் வலிமை` | `40b57e1631aa4b6e402c97b43c7b0373e41b0232` |
| 7 | `சுயமரியாதைத் திருமணம்` | `a848575f1e0f8c9e7b30c0e5e2567bb9d30e0758` |
| 8 | `மனிதனின் மறுபக்கம்` | `38a315b2b1efa1dfaf051704b18aeddf663b81c0` |
| 9 | `விண்ணைத் தொட்டு மண்ணில் புதைவதோ?` | `6944524dabdc4a323916620766ca9d67995d01bf` |
| 10 | `மனிதனும் மறுபிறவியும்` | `95c87cb3ed7a7b5fdba69e59f687b612a3eb65f0` |

The additions deliberately preserve independent contents/heading witnesses. In particular:

- Article 3 contents `என் பெயர் புரட்சி` ≠ heading `என் பெயர் புரட்சி!`;
- Article 6 contents `வாக்குச் சீட்டின் வலிமை` ≠ heading `வாக்குச்சீட்டின் வலிமை`;
- Article 9 contents `விண்ணைத் தொட்டு மண்ணில் புதைவதோ?` ≠ heading `விண்ணைத் தொட்டு மண்ணில் புதைவதா?`.

Existing independent witness differences for Articles 11, 15, 19, 41 and 48 remain unchanged.

## E6-B — Ordered Tamil-source comments / scan continuity

**PASS.**

The completed T0–T5 review ledgers were reconciled publication-wide:

| Article range | Ordered source comments |
|---|---:|
| 1–16 | **60 / 60** |
| 17–21 | **20 / 20** |
| 22–26 | **19 / 19** |
| 27–36 | **42 / 42** |
| 37–50 | **67 / 67** |
| **Total** | **208 / 208** |

These **208** markers account for every body scan from **18 through 225** in order. No source marker was lost, duplicated or reordered by E6.

Cross-transfer boundaries remain intact:

- Article 25: Part 002 → Part 003;
- Article 38: Part 003 → Part 004;
- Article 49: Part 004 → Part 005.

The early-file variation in whether the first source marker appears immediately before or immediately after the H1 heading does not alter source order or traceability and is classified as a **consistent historical layout variation**, not a body correction.

## E6-C — `Udanpirapp` forms

**PASS.**

Permanent rule remains unchanged:

- exact `உடன்பிறப்பே` → **`Udanpirappē`**;
- direct salutation → **`Udanpirappē,`**;
- never flatten to brother/sister/sibling/Dear sibling/comrade.

Publication-wide source-bearing uses remain correctly distinguished:

- Articles 1 and 2: `Udanpirappē,`;
- Article 31: plural `Udanpirappugal`;
- Article 32: collective salutation `Kazhaga Udanpirappugalē!`;
- Article 47: plural `Udanpirappugal`.

No conflicting flattened rendering was introduced.

## E6-D — Terminology / names / source witnesses

**PASS.**

The full authority chain—`LEXICON_THROUGH_16.md`, `LEXICON_THROUGH_36.md`, current `LEXICON.md`, and all translation-review ledgers—was applied across the collection.

Recurring forms remain consistent where the source is consistent, while source-specific variants remain deliberately distinct. Examples protected by E6 include:

- `Ayya Periyar` / `Thanthai Periyar` according to the actual Tamil witness rather than forced homogenisation;
- `Pagutharivu` as a journal title versus common-noun `rationalism`;
- `Maanamigu / Maanbumigu` wordplay;
- `Naladiyar`, `Silappathikaram`, `Civaka Cintamani`, `Thirikadugam`, `Pathuppaattu`, `Ettuthogai`, `Pathinenkeezhkanakku`, `Nanmanikkadigai`;
- source-specific Mandela-era names rather than externally normalised biography;
- Article 44 source `Kannan`;
- Article 45 source `Valiyuruthal` and source-visible `Iraiyanar's Kural` title;
- Article 47 `thalagaani urai` as the deliberate source error contrasted with `thalaiyanai urai`;
- Article 48 `kevala porul` / source-supplied `Parabrahmam`;
- Article 49 `anthathi`, `villisai`, `madal`, and source-force `rape` for `கற்பழிக்க`.

No terminology body correction was required in E6.

## E6-E — Quotations / verse / lineation

**PASS.**

The T4 records and high-risk final-block files were rechecked for the publication-wide rule that embedded quotations are translations of the frozen Tamil witness, not imported published English versions.

Protected non-regression includes:

- Article 29's unusual frozen Kural witness;
- Article 35 four-line venpa;
- Article 36 literary fire passage and four-line final poem within the explicit anti-self-destruction argument;
- Article 37 classical verse lineation;
- Article 38 three Kurals;
- Article 40 Kural/commentary and four-line `widow` poem;
- Article 42 source-supplied English `Merchants of Death`;
- Article 45 `Iniyavai Narpathu` verse;
- Article 46 Bharathi/Bharathidasan passages;
- Article 47 Kannadasan verse blocks;
- Article 49 `Chidambara Anthathi` quotations, including restored `Sengattu Nangai`;
- Article 50 Periyar testament and Anna letter.

No quotation or verse body correction was required in E6.

## E6-F — Dates / numbers / source claims

**PASS.**

Dates, money, percentages, counts, measurements, political claims, historical claims, health/medical statements, scientific claims and news reports remain source claims rather than translator updates.

High-risk checks remained intact:

- Article 40 source 1989 property-right claim;
- Article 42 disaster/nuclear/scientific figures and source-name forms;
- Article 45 source title/chapter oddities;
- Article 46 all 2005 human-development/population statistics and the irregular frozen phrase `ஓர் என்பது ஆண்டுகளுக்குள்`, retained conservatively as **`within a certain span of years`** without inventing a number;
- Article 49 manuscript/date/source-history claims;
- Article 50 Periyar/Anna dates and historical narrative.

No Tamil source defect was discovered. Tamil changes in E6: **0**.

## E6-G — Voice / English / Markdown consistency

**PASS.**

Publication-wide review found the established English voice internally coherent with the permanent rule: **translate the language; do not neutralise the voice**.

Questions, imperatives, repetition, sarcasm, accusation, abrupt contrast, polemical vocabulary and concrete imagery remain article-specific rather than being flattened into academic prose.

No new substantive English-body omission, addition, external normalisation or consistency defect remained after the T0–T5 corrections already recorded in the historical ledgers.

E6 body-prose corrections: **0**.  
E6 metadata-only corrections: **10 files / Articles 1–10**.  
E6 Tamil changes: **0**.

## E6-H — Closure

- 50 / 50 verified English articles: **PASS**;
- live Tamil source pins 50 / 50: **PASS**;
- ordered source comments 208 / 208: **PASS**;
- permanent `Udanpirappē` rule: **PASS**;
- terminology/name/source-witness consistency: **PASS**;
- quotation/verse fidelity: **PASS**;
- dates/numbers/source-claim discipline: **PASS**;
- English voice/Markdown consistency: **PASS**;
- unresolved English blockers: **0**;
- unresolved Tamil/source blockers: **0**.

# E6 RESULT: PASS / COMPLETE

Article-level English translation remains **50 / 50 T5 VERIFIED**. Publication-wide E6 is now **PASS**.

**E7 release closeout has NOT been started.** It is the exact next activity and requires a separate user continuation.
