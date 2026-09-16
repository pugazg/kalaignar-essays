# P2 Transcription Progress — பெருமூச்சு

## Authority

- controlling source — `TVA_BOK_0064124_பெருமூச்சு.pdf`
- physical scans — **83**
- source SHA-256 — `18947f2deb1ece71b03b59c1e52d9f483a45baa5bf436ab2c3e89a48b5f2dc38`
- source pixels — **authoritative**
- user-supplied `perumoochu.md` — **generated baseline only / non-authoritative**
- OCR / web / alternate edition / remembered wording — **not authority**

## Historical Tamil rule

Root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is mandatory.

Minimum explicit audit families:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Read character identity from source pixels; do not modernize vocabulary, spelling, grammar or punctuation.

## Batch 001 — scans 1–23

**COMPLETE / PASS**

- records — **23/23**
- verified — **23**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- P2 cumulative — **23/83**

### Coverage

| Scans | Unit | Status |
|---:|---|---|
| 1–4 | cover / reverse / title / imprint | VERIFIED |
| 5–6 | `மூச்சினிடையே!` | VERIFIED |
| 7–10 | `பெருமூச்சு` | VERIFIED |
| 11–16 | `மாளிகை அமைத்திட வாரீர்!` | VERIFIED |
| 17–20 | `மந்திரிகள் குலை நடுக்கம்` | VERIFIED |
| 21–23 | `வாபஸ் வீரர்கள்!` | VERIFIED |

### Durable baseline-to-source findings

- scan 5 — `விடுகிறர்கள்` → **`விடுகிறார்கள்`**
- scan 6 — `தறிப்பாக` → **`குறிப்பாக`**
- scan 13 — `உறக்கக்` → **`உரக்கக்`**
- scan 17 — user-confirmed historical **`லை`** glyph: **`மந்திரிகள் குலை நடுக்கம்`**
- scan 21 — P1 `வாய்ஸ் வீரர்கள்!` → **`வாபஸ் வீரர்கள்!`**
- scan 22 — `புண்ய பூமியிலே` → **`புண்ணிய பூமியிலே`**

Physical-copy marks on scans 2–3 remain outside the canonical printed-text layer.

### Boundary checks within completed range

- 6→7 preface→Article 1 — **PASS**
- 10→11 Article 1→2 — **PASS**
- 16→17 Article 2→3 — **PASS**
- 20→21 Article 3→4 — **PASS**
- 23 closes Article 4 — **PASS**
- scan 24 is intentionally unopened in Batch 001.

## Batch 002 — scans 24–52

**COMPLETE / PASS — reconstructed closure summary**

- records — **29/29**
- verified — **29**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- cumulative after Batch 002 — **52/83**

### Coverage

| Scans | Unit | Status |
|---:|---|---|
| 24–36 | `பொது மக்களுக்குத் தனி எச்சரிக்கை` | VERIFIED |
| 37–40 | `சிறுவர்கள்` | VERIFIED |
| 41–48 | `“அஹிம்சா விலாசம்”` | VERIFIED |
| 49–52 | `திண்டிவனம் தீரர்காள்!` | VERIFIED |

### Closure / boundary authority

The current 29 canonical records are the post-repair records rebuilt from directly verified physical PDF boundaries. The authoritative repair commit is:

`ebe8b2146eef22ac203f8014367cb78dea2d4b76`

This summary restores the missing Batch-002 control entry; it does **not** alter canonical page text or recreate superseded heuristic segmentation.

## Batch 003 — scans 53–83

**COMPLETE / PASS**

- records — **31/31**
- verified — **31**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- P2 cumulative — **83/83**

### Coverage

| Scans | Unit | Status |
|---:|---|---|
| 53–56 | `சேவல் கூவுகிறது!` | VERIFIED |
| 57–62 | `மாடோட்டிகள்!` | VERIFIED |
| 63–70 | `தேர்தல் கோவலன்!` | VERIFIED |
| 71–76 | `சிந்தித்துணர்க! சீற்றமுறாதீர்!` | VERIFIED |
| 77–80 | `பூம்! பூம்! பூம்!` | VERIFIED |
| 81 | `கலைஞர் கருணாநிதியின் அரிய நூல்கள்` catalogue | VERIFIED |
| 82 | `அறிஞர்களின் அமுதத் துளிகள்` catalogue | VERIFIED |
| 83 | `புதிய வெளியீடுகள்!` catalogue / terminal scan | VERIFIED |

### Final P2 corrections / structural refinements

- `மந்திரிகள் குலை நடுக்கம்` — historical **`லை`** confirmed by user/source;
- `வாபஸ் வீரர்கள்!` — replaces retired P1 `வாய்ஸ் வீரர்கள்!`;
- `திண்டிவனம் தீரர்காள்!` — replaces retired P1 `திண்டிவனம் தீரர்கள்!`;
- `சேவல் கூவுகிறது!` — replaces retired P1 `சேலம் கூவுகிறது!`;
- `மாடோட்டிகள்!` — replaces retired P1 `மாட்டோட்டிகள்!`;
- `தேர்தல் கோவலன்!` — replaces retired P1 `தேர்தல் கோமாளி!`;
- `சிந்தித்துணர்க! சீற்றமுறாதீர்!` — replaces retired P1 `சிந்தித்தான்! சிரித்தான்!`.

### Physical-boundary repair

A P2 closure check found that scans **24–52** had initially been segmented heuristically from the generated baseline instead of by exact physical PDF boundaries.

All **29 records** in scans 24–52 were rebuilt against rendered source-pixel boundaries. The repaired set is authoritative from commit:

`ebe8b2146eef22ac203f8014367cb78dea2d4b76`

### Final P2 gate

**P2 COMPLETE / PASS — 83/83**

- canonical physical-scan records — **83/83**
- missing scans — **0**
- duplicate scans — **0**
- needs-review — **0**
- blocked — **0**
- guessed readings — **0**
- unresolved historical-glyph readings — **0**
- source PDF terminal boundary — **scan 83 VERIFIED**
- source PDF committed — **No**

## Downstream status

- P3 — **COMPLETE / PASS — 13/13**
- P4 — **COMPLETE / PASS**

## Exact next activity

**P5 — final strict visual text-fidelity pass over all 83 physical scans.**
