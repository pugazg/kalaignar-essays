# Source audit — குடும்பத்தின் நல்விளக்கு

## Scope

Controlling source: `TVA_BOK_0065602_குடும்பத்தின்_நல்விளக்கு.pdf`  
Recorded source SHA-256: `1c3389ec76507b0c6f2ae294a4523633e81084d570a1443c7b730ac899e15971`  
Physical scans: **16**  
Article assemblies: **1**

This ledger records **P4 — source audit / completeness review**. P5 strict visual word/punctuation fidelity is still pending.

The supplied PDF scan remains the controlling witness. The corrected verified P2 page records remain the lexical/source layer for P4 assembly reconciliation.

## P4 — source completeness / assembly consistency — PASS

### Physical-source accounting

Every physical scan is represented exactly once and in source reading order:

`1 → 2 → 3 → 4 → 5 → 6 → 7 → 8 → 9 → 10 → 11 → 12 → 13 → 14 → 15 → 16`

| Unit | Physical scans | P4 result |
|---|---:|---|
| front cover | 1 | **PASS** |
| title page | 2 | **PASS** |
| author portrait | 3 | **PASS** |
| article `குடும்பத்தின் நல்விளக்கு` | 4–13 | **PASS** |
| blank/show-through leaf | 14 | **PASS / non-body** |
| family illustration | 15 | **PASS / non-body** |
| back cover | 16 | **PASS** |

- physical page records present: **16 / 16**;
- page records in canonical order: **16 / 16**;
- unrepresented physical scans: **0**;
- duplicate scan records: **0**;
- printed contents page: **ABSENT / CONFIRMED**;
- article units: **1 / 1**;
- article boundary: **scans 4–13 CONFIRMED**;
- visible printed numerals remain **2–9 on scans 5–12 only**; inferred `1` / `10`: **0**.

### Front/end-matter reconciliation

- scan 1 cover identity agrees with README/source metadata: **PASS**;
- scan 2 title/author/departmental publication line agrees with metadata: **PASS**;
- scan 3 is portrait-only with no printed caption: **PASS**;
- scan 14 is non-body blank/show-through and follows the scan-13 end rule: **PASS**;
- scan 15 is a non-body full-page family illustration with no printed caption: **PASS**;
- scan 16 carries the departmental publication and printer lines recorded in metadata: **PASS**;
- library marks, handwriting, foxing and show-through remain outside printed-text layers: **PASS**.

### Article assembly reconciliation

Canonical assembly: `articles/01-kudumbaththin-nalvilakku.md`.

- mapped body scans present once each: **10 / 10 PASS**;
- source-page comments for scans 4–13: **10 / 10 PASS**;
- scan-to-scan continuations: **9 / 9 PASS**;
- opening heading: **PASS**;
- scan-13 closing rule: **PASS**;
- corrected P2 lexical readings propagated into assembly: **PASS**;
- body omissions: **0**;
- duplicated body text: **0**;
- page-order errors: **0**;
- editorial/audit/physical-copy notes copied into article body: **0**.

### P4 correction

P4 found **one assembly-layer placement defect**: the scan-7 printed footnote `* தமிழ்நாடு குடும்ப நலத்துறையின் வெளியீடான “சமுதாயக்கடமை”.` had been preserved but was positioned after scan-8 body text in the initial P3 assembly.

Correction applied during P4:

- **before:** footnote content appeared after the scan-8 first body paragraph;
- **after:** footnote is attached to scan 7, immediately before the scan-8 page-boundary comment, matching the page record/source-page association;
- lexical footnote content changed: **0**;
- page-layer files changed by this correction: **0**.

Corrected assembly blob after P4: `f33d195f0952c1888510eb75e9c9b72e1fc9d6f0`.

### Corrected P2 authority retained

The prior post-P2 old-glyph/user-review batch remains authoritative. In particular, retain the approved source readings including:

- `பிரச்சனையாக`;
- `படைவீரர்களை`;
- scan-6 `முறைகளை`, `பொறுப்பிலே`, `இந்து மார்க்கத்திலே`;
- scan-7 `கொள்கைகளை`, `மூர்த்தன்யமாக`;
- scan-8 `தாயாரையும்`, `எடுத்தும்`, `நம்பிக்கைகளிலிருந்தெல்லாம்`;
- scan-9 `குறைந்தது`, `நாடாளுமன்றத்திலே`, `கேட்டுக்கொண்டிருக்கிறோம்`, `என்கின்ற`;
- scan-10 `விளைவுகளைத்`, `பயனை`, `தடுக்கப்பட்டாக`, `பதினாறு` twice, `பொருளை` twice, `நிலைமை`, `மக்களுக்குத்`, `இவைகளை`;
- scan-11 `நாலைந்து` twice;
- scan-12 `தகப்பனாரும்`, `நிறைவேற்றாத`, `அவல் வாங்கிச் சாப்பிட்டு`;
- scan-13 `ஆலாய்ப்`, `கயிலையங்கிரியில்`, `இந்து மதத்திலே`.

The user explicitly retained `சிந்தித்துச்` on scan 5 and `ஒருபுறத்திலே` on scan 9 unchanged.

## P4 result

**P4 SOURCE / COMPLETENESS AUDIT: COMPLETE / PASS.**

- physical scans reconciled: **16 / 16**;
- page records reconciled: **16 / 16**;
- article assemblies reconciled: **1 / 1**;
- assembly page comments: **10 / 10**;
- continuation checks: **9 / 9**;
- P4 corrections: **1 placement-only correction**;
- unresolved completeness blockers: **0**;
- P5 strict visual fidelity: **NOT STARTED**.

## Exact next activity

Execute **P5 — strict visual word-by-word / punctuation-by-punctuation fidelity review over all 16 physical scans**.

1. Re-resolve the controlling PDF.
2. Recheck every physical scan 1–16 directly against its page record.
3. Recheck every visible word, punctuation mark, quotation mark, number, heading, paragraph boundary and continuation.
4. Preserve multiple source witnesses independently and do not normalise old Tamil glyphs from context.
5. Record every P5 correction with old reading → source-visible reading provenance.
6. Propagate genuine corrections to page records, article assembly, indexes and durable documentation.
7. Create `VISUAL_TEXT_FIDELITY_REVIEW.md`.
8. If clean after propagation, mark P5 COMPLETE / PASS and freeze the Tamil archival layer.
9. **STOP AFTER P5. Do not begin English translation in the same activity.**
