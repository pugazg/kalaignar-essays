# கயிற்றில் தொங்கிய கணபதி

**ஆசிரியர்:** மு. கருணாநிதி  
**Source-visible publication date:** ஜூலை 1949  
**வெளியீடு:** அறிவுப்பண்ணை  
**Source PDF:** repository-க்கு வெளியே பாதுகாக்கப்படுகிறது.

இந்த supplied scan ஒரு **standalone single-article pamphlet / சிறுநூல்**. Source scan-இல் title/front matter, `பதிப்புரை`, ஒரு தொடர்ச்சியான கட்டுரை, பின்னணி விளம்பரப் பக்கங்கள் உள்ளன; printed contents page இல்லை.

## Source identity

- Source filename: `TVA_BOK_0064013_கயிற்றில்_தொங்கிய_கணபதி.pdf`
- physical scans: **17**
- source SHA-256: `927d05fb27a2545d6732acd9bf8bde04dba2d22546d171b502703a773b40f45a`
- source file size: **26,750,146 bytes**
- source PDF committed to repository: **No**
- Gemini first-pass OCR: **comparison aid only; not authority**

## Source authority

> **மூல ஸ்கேன் தான் controlling source.**

Existing source-verified Tamil is the baseline. Old Tamil glyphs, spelling, punctuation, word boundaries, names, numbers and unusual forms must not be changed merely because another reading looks more familiar. A change requires clear character-level source evidence. Physical-copy/library marks remain outside printed text.

## Tamil archival gates

- P0 source intake / identification: **COMPLETE**
- P1 metadata + full page map / boundaries: **COMPLETE**
- P2 page-level transcription: **COMPLETE — 17 / 17 verified**
- P3 article assembly: **COMPLETE — 1 / 1**
- P4 source completeness / structure audit: **COMPLETE / PASS**
- P5 strict visual word/punctuation fidelity: **COMPLETE — 17 / 17 PASS**
- article strict-fidelity recheck: **COMPLETE — 1 / 1 PASS**
- unresolved `NEEDS-PIXEL-REVIEW`: **0**
- unresolved body/source blockers: **0**
- **Tamil source: COMPLETE / FROZEN**

Detailed records:

- [`indexes/page-map.md`](indexes/page-map.md)
- [`metadata/source.md`](metadata/source.md)
- [`PUBLICATION_COMPLETION_REVIEW.md`](PUBLICATION_COMPLETION_REVIEW.md)
- [`VISUAL_TEXT_FIDELITY_REVIEW.md`](VISUAL_TEXT_FIDELITY_REVIEW.md)
- [`articles/01-kayittril-thongiya-kanapathi.md`](articles/01-kayittril-thongiya-kanapathi.md)

## Final physical structure

- scans **1–5**: front matter; scan 4 `பதிப்புரை`; scan 5 blank
- scan **6**: article opening; **no visible printed numeral**
- scans **7–15**: printed pages **6–14**
- scans **6–15**: single article
- scan **15**: article conclusion, ending ornament, physical-copy stamp below
- scans **16–17**: separate advertisements / promotional witnesses
- printed contents page: **none**

The archive does not infer a visible page 5 for scan 6.

## Retrospective correction provenance

A targeted recheck of earlier assistant-origin corrections found one false correction and revalidated the other two formal P2 corrections:

- first pass `தூக்குபோட்டுவிட்டீர்களா 1` → **`தூக்குபோட்டுவிட்டீர்களா!`** — scan 13 / printed p.12. The source line break is `தூக்குபோட்டுவிட்டீர்` + `களா!`; only the final OCR-like `1` needed correction to `!`. Earlier assistant `தூக்குபோட்டுவிட்டார்களா!` was wrong and is withdrawn.
- `கொண்டிருக்கின்றார்.` → **`கொண்டிருக்கிறார்.`** — scan 13 / printed p.12; source revalidated.
- interim `உரத்தகுரலில்;` → **`உரத்தகுரலில்,`** — scan 12 / printed p.11; source revalidated.

Failed pre-P5 assistant changes `ஓடித்` → `ஒடித்`, `அபாண்டங்களைச்` → `அபாண்டங்களச்`, `அவளைப்` → `அவனைப்`, and `சாவின் முனையிலே` → `சாவின் முன்னிலே` were reverted and remain withdrawn.

## Frozen source-specific readings

The P5 strict pass retains, among others:

`உரைந்திருக்கும்`, `அடபாபமே!`, `கவலைப்பட வில்லை.`, `நேரமில்லை`, `சோறில்லை`, `நன்றுக`, `அவர்கட்கு`, `அக்கரை`, `தங்கந் தோண்டுமிடமாயிற்றே!`, `நெருக்கடியில்(!)`, `தூக்குபோட்டுவிட்டீர்களா!`, `கொண்டிருக்கிறார்.`, `உரத்தகுரலில்,`, `சாவின் முனையிலே`, and final `அளிக்குமாக /`.

## P5 result

P5 reopened all **17 physical scans** and rechecked the existing verified transcription as the baseline. No new textual correction was introduced during the final strict pass. The complete article assembly was then rechecked against scans **6–15** and passed.

**P5 RESULT: PASS — Tamil source frozen.**

## Exact next activity

Execute **T0 — English translation source prerequisite / setup** under `ESSAY_TRANSLATION_GUIDE.md`:

1. record the frozen Tamil article blob SHA;
2. create `TRANSLATION_PLAN.md`;
3. create `translations/en/README.md`, `LEXICON.md`, and `TRANSLATION_REVIEW.md`;
4. register Article 1 as `not-started` with the frozen Tamil assembly as translation authority;
5. do not begin T1 body translation until T0 setup is complete.