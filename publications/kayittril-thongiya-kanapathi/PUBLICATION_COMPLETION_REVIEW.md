# Publication completion review — கயிற்றில் தொங்கிய கணபதி

## Scope

Controlling source: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`  
Physical scans: **17**  
Recorded SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`

This record closes the Tamil archival gates through **P5**. The supplied scan remains the controlling source.

## Final completion gates

| Check | Result |
|---|---|
| Physical scans in controlling source | **17** |
| Physical page records | **17 / 17 PASS** |
| Every physical scan represented exactly once | **PASS** |
| Front matter boundary | **PASS — scans 1–5** |
| `பதிப்புரை` boundary | **PASS — scan 4** |
| Blank scan | **PASS — scan 5** |
| Article boundary | **PASS — scans 6–15** |
| Advertisements / promotional matter | **PASS — scans 16–17, outside article** |
| Scan 6 printed-page metadata | **PASS — no visible numeral; `printed_page: null`** |
| Scans 7–15 printed-page sequence | **PASS — 6–14** |
| Article assemblies | **1 / 1 PASS** |
| Article source range | **PASS — scans 6–15 only** |
| Page-boundary comments in assembly | **PASS — scans 6–15** |
| P4 source completeness / structure audit | **PASS** |
| P5 strict visual-text fidelity | **17 / 17 PASS** |
| Article strict-fidelity recheck | **1 / 1 PASS** |
| Outstanding `NEEDS-PIXEL-REVIEW` | **0** |
| Unresolved printed-text/body blockers | **0** |
| Source PDF committed to repository | **No** |

**FINAL TAMIL SOURCE RESULT: COMPLETE / FROZEN.**

Strict review record: [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md).

## Source-boundary result

The final publication model is:

- scans **1–3** — cover / title-publisher / imprint;
- scan **4** — `பதிப்புரை`;
- scan **5** — blank physical scan;
- scan **6** — article heading/opening, with **no visible printed page numeral**;
- scans **7–15** — article continuation through printed pages **6–14**;
- scan **15** — article conclusion, printed ending ornament, and lower physical-copy/library stamp;
- scans **16–17** — independent printed advertisements / promotional matter.

The article assembly is therefore **scans 6–15 only**.

## Retrospective correction provenance

Because earlier assistant glyph interpretations produced false corrections, all formally recorded assistant-origin corrections were re-audited before P5. The final source-backed record is:

- first pass `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டீர்களா!`** — scan 13 / printed p.12. Source line break: `தூக்குபோட்டுவிட்டீர்` + `களா!`. Only `1` → `!` is a genuine correction. Earlier assistant `தூக்குபோட்டுவிட்டார்களா!` was false and is withdrawn.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — scan 13 / printed p.12; source revalidated.
- interim `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — scan 12 / printed p.11; source revalidated.

The failed pre-P5 changes `ஓடித்` → `ஒடித்`, `அபாண்டங்களைச்` → `அபாண்டங்களச்`, `அவளைப்` → `அவனைப்`, and `சாவின் முனையிலே` → `சாவின் முன்னிலே` were reverted before P5 and remain withdrawn.

## Source-specific readings frozen after P5

The strict pass retained source-visible forms including:

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

These must not be modernised or replaced from contextual expectation.

## Article assembly result

Assembly: [`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

P5 rechecked the complete assembly against the page layer and scan boundaries:

- scans **6–15** only;
- all source-page comments retained;
- no front matter or advertisements imported;
- scan 6 remains unnumbered;
- all cross-page continuations agree;
- final wording remains `கணபதியின் கொலை இந்த உறுதியை திராவிடர்க்கு அளிக்குமாக /`;
- ending ornament and physical-copy stamp remain outside prose.

**Article 1: STRICT-FIDELITY PASS / FROZEN.**

## Downstream gate

Tamil translation prerequisite is now satisfied. English work may begin under `ESSAY_TRANSLATION_GUIDE.md`.

**Exact next activity:** execute **T0 — English translation source prerequisite / setup** for this publication: record the frozen Tamil article blob SHA, create the publication translation plan and English tracking/lexicon/review files, and do not begin T1 body translation until T0 setup is complete.