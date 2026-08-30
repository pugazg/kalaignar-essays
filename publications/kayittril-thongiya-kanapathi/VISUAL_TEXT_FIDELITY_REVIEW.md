# Visual text fidelity review — கயிற்றில் தொங்கிய கணபதி

## Purpose

This is the mandatory **P5 strict visual-text-fidelity pass** for Publication 2.

Controlling source: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`  
Physical scans: **17**  
Recorded SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`

The supplied scan remains the controlling source. The existing verified transcription was treated as the baseline. Because earlier assistant attempts had incorrectly reinterpreted old Tamil glyphs, this pass used a stricter rule: **no existing reading was changed unless clear character-level source pixels proved a discrepancy**. Semantic plausibility or a more familiar modern form was not accepted as evidence.

## Verdicts

- `FIDELITY-PASS` — the existing verified transcription agrees with the source for readable printed words, punctuation, headings/numbers, meaningful word boundaries and witness boundaries.
- `CORRECTED` — a clear source discrepancy was found and propagated.
- `NEEDS-PIXEL-REVIEW` — a source glyph or mark remains unresolved after enlargement/typeface comparison.

## Final result

| Scan | Section | Printed page | Verdict | High-value checks |
|---:|---|---:|---|---|
| 1 | front cover | — | **FIDELITY-PASS** | title `கயிற்றில் தொங்கிய கணபதி`; author `மு.கருணாநிதி`; physical-copy mark kept separate |
| 2 | title / publisher | — | **FIDELITY-PASS** | title; `மு. கருணாநிதி`; `எழுதியது`; `அறிவுப்பண்ணை`; address; two library stamps excluded from print text |
| 3 | imprint | — | **FIDELITY-PASS** | `ஜூலை 1949`; `விலை அணா 3.`; printer line |
| 4 | `பதிப்புரை` | — | **FIDELITY-PASS** | heading and compact source reading `கதியற்றவராய்-காப்பாரற்றநாதியற்றவராய்!` retained |
| 5 | blank | — | **FIDELITY-PASS** | no printed text / numeral |
| 6 | article opening | — | **FIDELITY-PASS** | no visible printed numeral; `உரைந்திருக்கும்` retained; continuation to scan 7 preserved |
| 7 | article | 6 | **FIDELITY-PASS** | `அடபாபமே!` retained; continuation to scan 8 preserved |
| 8 | article | 7 | **FIDELITY-PASS** | existing `அவளைப் பார்த்து` retained; quotation and paragraph boundary agree |
| 9 | article | 8 | **FIDELITY-PASS** | `பாராள பாரத புத்ரர்` retained; continuation to scan 10 preserved |
| 10 | article | 9 | **FIDELITY-PASS** | `கவலைப்பட வில்லை.` retained; quotation and continuation agree |
| 11 | article | 10 | **FIDELITY-PASS** | `நேரமில்லை`, `உற்சாகப் பண்பாடினார்.`, `தங்கந் தோண்டுமிடமாயிற்றே!` retained |
| 12 | article | 11 | **FIDELITY-PASS** | `சோறில்லை`, `நன்றுக`; enlarged punctuation recheck confirms `உரத்தகுரலில்,` |
| 13 | article | 12 | **FIDELITY-PASS** | enlarged line-break recheck confirms `தூக்குபோட்டுவிட்டீர்களா!`; `கொண்டிருக்கிறார்.` retained; `சாவின் முனையிலே`, `அவர்கட்கு`, `அக்கரை` retained |
| 14 | article | 13 | **FIDELITY-PASS** | scan-13 `கிளம்பி` → scan-14 `யிருக்குமா?` continuation preserved; body boundary agrees |
| 15 | article conclusion | 14 | **FIDELITY-PASS** | final `அளிக்குமாக /`; ending ornament and library stamp remain outside article prose |
| 16 | advertisement | — | **FIDELITY-PASS** | promotional titles/prices and `விற்பனைக் கழிவு 20%`; not article body |
| 17 | advertisement / back matter | — | **FIDELITY-PASS** | promotional titles/prices, `25 பர்சன்ட்`, address; not article body |

**Strict visual-text-fidelity progress: 17 / 17 physical scans COMPLETE.**  
**Article assemblies strict-rechecked: 1 / 1 COMPLETE.**  
**Outstanding `NEEDS-PIXEL-REVIEW` items: 0.**  
**P5 text corrections introduced in this pass: 0.**

## Retrospective correction audit carried into P5

Before this final P5 pass, the earlier assistant-origin correction history was re-opened because the user identified false glyph reinterpretations. P5 used the corrected baseline and reconfirmed it:

1. first-pass `தூக்குபோட்டுவிட்டீர்களா 1` — source line break is `தூக்குபோட்டுவிட்டீர்` + `களா!`, therefore the source-visible reading is **`தூக்குபோட்டுவிட்டீர்களா!`**. Only `1` → `!` is a genuine correction. The earlier assistant form `தூக்குபோட்டுவிட்டார்களா!` is false and remains withdrawn.
2. earlier `கொண்டிருக்கின்றார்.` → source-visible **`கொண்டிருக்கிறார்.`** — revalidated.
3. interim `உரத்தகுரலில்;` → source-visible **`உரத்தகுரலில்,`** — revalidated by enlarged punctuation comparison.

The failed pre-P5 assistant changes `ஓடித்` → `ஒடித்`, `அபாண்டங்களைச்` → `அபாண்டங்களச்`, `அவளைப்` → `அவனைப்`, and `சாவின் முனையிலே` → `சாவின் முன்னிலே` were already fully reverted before this pass and were **not** reintroduced.

## Source-specific readings that must not regress

P5 independently retained the existing source-witness readings, including:

- `உரைந்திருக்கும்`
- `அடபாபமே!`
- `கவலைப்பட வில்லை.`
- `நேரமில்லை`
- `சோறில்லை`
- `நன்றுக`
- `அவர்கட்கு`
- `அக்கரை`
- `தங்கந் தோண்டுமிடமாயிற்றே!`
- `நெருக்கடியில்(!)`
- `தூக்குபோட்டுவிட்டீர்களா!`
- `கொண்டிருக்கிறார்.`
- `உரத்தகுரலில்,`
- `சாவின் முனையிலே`
- final `அளிக்குமாக /`

A familiar modern-looking alternative must never replace these merely from context or glyph resemblance.

## Assembly recheck

Assembly: [`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

The complete article was rechecked after the 17-scan pass:

- source range remains **scans 6–15 only**;
- scan-boundary comments remain present from scan 6 through scan 15;
- scan 6 remains explicitly unnumbered;
- page-to-page continuations agree;
- `பதிப்புரை`, cover/title/imprint/blank matter and scans 16–17 advertisements remain outside the article body;
- scan-13 reading is `தூக்குபோட்டுவிட்டீர்களா!`;
- final article wording remains `கணபதியின் கொலை இந்த உறுதியை திராவிடர்க்கு அளிக்குமாக /`;
- printed ending ornament and library stamp are outside article prose.

**Article 1: FULL STRICT-FIDELITY PASS.**

## P5 gate result

**P5 RESULT: PASS.**

- 17 / 17 scans strict-reviewed
- 1 / 1 article assembly strict-rechecked
- unresolved printed-text readings: **0**
- unresolved source-boundary issues: **0**
- `NEEDS-PIXEL-REVIEW`: **0**

Publication 2's Tamil source layer is therefore eligible to be marked **COMPLETE / FROZEN**. Any future Tamil change requires explicit source-supported evidence and must reopen downstream English work if translation has begun.