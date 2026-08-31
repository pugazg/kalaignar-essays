# Source audit — உணர்ச்சிமாலை

## Scope

Controlling source: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`  
Recorded source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`  
Physical scans: **50**  
Article assemblies: **10**

This record closes **P4 — source audit / completeness review** for the publication. P4 audits the ten P3 article assemblies against the already verified P2 page layer. It does **not** perform the separate P5 word-by-word / punctuation-by-punctuation scan recheck.

## Audit method

P4 was executed against live `main` after P3.

- pre-P4 live HEAD: `23ba3a6b5a0a918f276eedc1f630faf146db2d4c` — `Complete Unarchchimaalai P3 article assemblies`;
- P2 → P3 comparison confirms that no `publications/unarchchimaalai/pages/` record changed during P3; P3 added the ten article assemblies and updated documentation only;
- every article metadata scan range was checked against `indexes/page-map.md` / `indexes/contents.md`;
- every physical scan-boundary comment in each assembly was checked for completeness and order;
- assembly starts, cross-page continuations and conclusions were checked against the mapped verified page records;
- the publication-specific Gemini lexical baseline was not reopened or normalised during P4.

## Article-by-article completeness audit

| Article | Mapped scans | Assembly boundary comments | Body/order result | P4 result |
|---:|---:|---|---|---|
| 1 — `உணர்ச்சி மாலை` | 6–9 | 6, 7, 8, 9 | every mapped page-body segment present once, in order | **PASS** |
| 2 — `புரட்சி வளர்ந்த கதை` | 10–15 | 10, 11, 12, 13, 14, 15 | every mapped page-body segment present once, in order | **PASS** |
| 3 — `போகிறான்;போகிறான்..!` | 16–18 | 16, 17, 18 | every mapped page-body segment present once, in order | **PASS** |
| 4 — `இராவணன் நம் பாட்டன்` | 19–29 | 19 through 29 | every mapped page-body segment present once, in order; scan-19 recovery provenance retained | **PASS** |
| 5 — `இங்கல்ல! இரஷ்யாவில்` | 30–32 | 30, 31, 32 | every mapped page-body segment present once, in order; scan-32 Gemini order retained | **PASS** |
| 6 — `3, 57, 90.` | 33–38 | 33, 34, 35, 36, 37, 38 | every mapped page-body segment present once, in order | **PASS** |
| 7 — `30-1-1948` | 39–41 | 39, 40, 41 | every mapped page-body segment present once, in order; terminal source witness preserved | **PASS** |
| 8 — `பத்தினியே உன்போல்...!` | 42–44 | 42, 43, 44 | every mapped page-body segment present once, in order | **PASS** |
| 9 — `அன்னை நாகம்மையார்!` | 45–47 | 45, 46, 47 | every mapped page-body segment present once, in order | **PASS** |
| 10 — `கவிதையல்ல - கண்ணீர்க்கடல் !` | 48–49 | 48, 49 | every mapped article-body segment present once, in order; publication-close matter excluded | **PASS** |

**Article assembly result: 10 / 10 PASS.**

## Boundary and non-regression checks

The following durable P2/P3 decisions were rechecked and remain unchanged:

- publication/title-page `உணர்ச்சிமாலை` remains distinct from Article 1 heading `உணர்ச்சி மாலை`;
- Article 3 heading remains `போகிறான்;போகிறான்..!`;
- Article 4 heading remains physically represented as `இராவணன்` / `நம் பாட்டன்`;
- Article 8 heading remains physically represented as `பத்தினியே` / `உன்போல்...!`;
- Article 10 heading remains physically represented as `கவிதையல்ல -` / `கண்ணீர்க்கடல் !`;
- every article-opening scan remains unnumbered in assembly metadata; scan 20 retains only the visible page-position witness `1` and never an inferred `19`;
- scan 19 remains explicitly marked `source-recovered Gemini omission`; its recovered three-paragraph body is present once before scan 20;
- scan 32 retains the Gemini sequence `அறிவு, நாட்டில் அடுப்பங்கரை இந் எதிரிகளின் நிஜுலினா...`; no lexical reordering was introduced during assembly or P4;
- Article 7 still ends on scan 41 with `வரலாற்றை வீணாக்கிய`; scan 42 is not pulled into Article 7;
- scan 48 retains Gemini `ப்ழச்சளை` under the user-established lexical-baseline rule;
- scan 49 retains Gemini placement `ஓய்ந்தனவா உனைத்தின்று! விட்டாய்.` despite the separately logged scan-order disagreement;
- non-source OCR artefacts previously excluded from the page layer were not reintroduced into any article assembly.

## Publication-close / advertisement exclusion audit

### Scan 49

The verified page record contains two distinct layers below the Article 10 conclusion:

- parenthetical publication-source note referring to `முரசொலி` / `மாலைமணி`;
- printer/imprint line `அன்பன் அச்சகம், சென்னை -1.`

Both remain **outside** `articles/10-kavithaiyalla-kannirkkadal.md`. Article 10 ends after `வீழ்ந்திடுவோம்.` and carries an explicit exclusion comment.

### Scan 50

Scan 50 is the separate `மணமகள்` back-cover advertisement (`எனெஸ்கே பிலிம்ஸாரின்` / `மணமகள்` / `BALU BROS`). It is not mapped to an article and is absent from all ten article assemblies.

## P4 discrepancy ledger

- missing mapped page-body segments: **0**
- duplicate mapped page-body segments: **0**
- out-of-order page-body segments: **0**
- missing / misordered page-boundary comments: **0**
- article start/end boundary defects: **0**
- P2 lexical/order conflicts accidentally normalised during P3: **0**
- publication-close or advertisement leakage into article body: **0**
- Tamil body edits made during P4: **0**

## P4 result

**P4 SOURCE AUDIT / COMPLETENESS REVIEW: PASS.**

The P2 verified page layer and P3 ten-article assembly layer are structurally consistent and complete for the mapped article bodies. This closes the source-completeness gate only; it does **not** close the strict visual fidelity gate.

## Exact next activity

Execute **P5 — strict visual word/punctuation fidelity pass** across all **50 physical scans**, including front matter, all article pages, scan-49 publication-close matter and scan-50 advertisement.

P5 must follow both the permanent scan-first guide and the publication-specific user instruction:

- recheck every visible word boundary, punctuation mark, quotation mark, heading, date, number, paragraph continuation and non-body boundary against the scan;
- preserve the user-established Gemini lexical baseline wherever it applies;
- do not silently replace known Gemini/source lexical conflicts; record any lexical conflict for user decision;
- propagate only user-authorised/source-supported structural corrections to page records and dependent assemblies;
- create/update the publication-level strict-fidelity review record before declaring the Tamil layer fidelity-complete;
- do not begin English translation until the P5 gate is explicitly closed.
