# கலைஞர் கட்டுரைகள் / ஆய்வுக் கட்டுரைகள் — மின்னாக்கக் களஞ்சியம்

கலைஞர் மு. கருணாநிதியின் கட்டுரைகள், தொடர்கட்டுரைகள், சிறுநூல்கள் மற்றும் கட்டுரைத் தொகுப்புகளை source-first முறையில் Markdown வடிவில் பாதுகாக்கும் களஞ்சியம்.

## மூலக் கொள்கை

> **மூல ஸ்கேன் தான் controlling source. Markdown ஒரு பாதுகாப்பு அடுக்கு; திருத்தப்பட்ட புதிய பதிப்பு அல்ல.**

Source PDF files repository-யில் commit செய்யப்படாது. Source-visible wording மற்றும் source-witness வேறுபாடுகள் அமைதியாக modernise/normalise செய்யப்படக்கூடாது.

## Permanent workflow documents

- [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
- [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
- [`HANDOVER.md`](HANDOVER.md)
- [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)

## Publication status

### Publication 1 — சக்கரவர்த்தியின் திருமகன்

**COMPLETE / FROZEN / RELEASED** — Tamil strict fidelity **83/83 PASS**, English T0–T5 **14/14**, E6 PASS, E7 PASS, blockers 0.

### Publication 2 — கயிற்றில் தொங்கிய கணபதி

**COMPLETE / FROZEN / RELEASED** — Tamil P5 **17/17 PASS**, English release complete, blockers 0.

### Publication 3 — உணர்ச்சிமாலை

**COMPLETE / FROZEN / RELEASED** — Tamil P5 **50/50 PASS**, article recheck **10/10 PASS**, English T0–T5 **10/10**, E6 PASS, E7 PASS, blockers 0.

### Publication 4 — திராவிட சம்பத்து

**COMPLETE / FROZEN / RELEASED** — Tamil P0–P5 complete, English T0–T5 **2/2**, E6 PASS, E7 PASS, blockers 0.

Released English authorities:

- **Dravidian Wealth** — `10dca72882043db491fe8c6ad3f858bc4c9c584f`
- **Iyer Announces!** — `771094f9c2eaad4c56c6f9509db34adbd3fd97a5`

### Publication 5 — இன முழக்கம்

Workspace: [`publications/ina-muzhakkam/`](publications/ina-muzhakkam/)  
Controlling source: `TVA_BOK_0063958_இன_முழக்கம்.pdf`  
Physical scans: **50**  
Source SHA-256: `f57e4070051d7bc77ab78d5d393dbefbe47791efcc3203c594c5f3949ef0dfbf`

User-established lexical rule:

> **Keep the words. Correct only structural order, punctuation, spacing, paragraphing, headings, misplaced words and analogous layout issues; remove unwanted non-source/OCR words.**

Current gates:

- P0: **COMPLETE**
- P1: **COMPLETE**
- P2: **50 / 50 COMPLETE**
- P3: **6 / 6 COMPLETE**
- P4: **PASS / COMPLETE**
- P5: **IN PROGRESS**
- durable P5 page frontier: **scan 38 / 50**
- English: **NOT STARTED**
- blockers: **0**

### P5 page-by-page rule

The user has explicitly directed that the remainder of `இன முழக்கம்` P5 be performed **one physical scan per activity**. See [`P5_PAGE_BY_PAGE_POLICY.md`](publications/ina-muzhakkam/P5_PAGE_BY_PAGE_POLICY.md).

A `Proceed with next activity` request processes only the next unclosed scan, commits that page's result and directly affected assembly/provenance changes, then stops. No multi-page P5 batching is allowed for this work.

**Exact next activity: P5 scan 39 only.**

After scan 50, a separate P5 closeout will recheck all 6/6 assemblies, finish the fidelity report, record frozen Tamil blob SHAs and freeze Tamil before English translation begins.
