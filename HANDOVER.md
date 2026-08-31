# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover document. Update this file after every meaningful source, translation, review or release activity. Do not create competing handover files unless the user explicitly asks.**

## Mandatory startup for future continuation

Read completely before making changes:

1. [`ESSAY_PROCESSING_GUIDE.md`](ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](ESSAY_TRANSLATION_GUIDE.md)
3. [`docs/FUTURE_WORK_GUIDELINES.md`](docs/FUTURE_WORK_GUIDELINES.md)
4. this `HANDOVER.md`
5. [`docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md`](docs/FUTURE_PUBLICATION_HANDOVER_TEMPLATE.md) when activating a new publication
6. the active publication README/metadata/page map/fidelity/completion records
7. if translation is active: publication `TRANSLATION_PLAN.md`, English tracker, lexicon, review ledger and release report if present

For a brand-new work/chat window, use [`docs/START_NEW_ESSAY_WORK_PROMPT.md`](docs/START_NEW_ESSAY_WORK_PROMPT.md) with the controlling PDF attached.

## Permanent source rule

The supplied scan is the controlling source for the Tamil archival layer. Never silently modernise, correct, normalise, reconstruct or improve Tamil wording, spelling, punctuation, names, numbers, repetition, grammar or typographical forms. Separate physical-copy marks from printed text. **Source PDFs are never committed to this repository.**

## Old Tamil glyph rule

Existing source-verified Tamil is the baseline. Enlargement/cropping is a verification aid, not permission to invent a new reading. A plausible modern word is not evidence.

## Permanent English translation rule

> **Translate the language; do not neutralise the voice.**

English must retain Kalaignar's directness, commands, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, physical imagery, exclamations and wordplay. Do not academicise or soften him. Translation begins only from a frozen Tamil source.

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

Workspace: `publications/sakkaravarththiyin-thirumagan/`

- physical scans: **83**
- articles: **14**
- Tamil page records: **83 / 83 complete**
- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14 complete**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Publication-wide identity rule: source `ஆச்சாரியார்` → **Achariyar**; explicit source `இராஜாஜி` → **Rajaji**; source plural `ஆச்சாரியார்களுக்கு` → **the Achariyars**.

Detailed frozen state is in the publication README, fidelity/completion records and English release files. Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is discovered.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

Workspace: `publications/kayittril-thongiya-kanapathi/`

- publication date: **ஜூலை 1949**
- publisher: **அறிவுப்பண்ணை**
- physical scans: **17**
- Tamil page records: **17 / 17 verified**
- P4: **PASS**
- P5 strict visual fidelity: **17 / 17 PASS**
- assembly strict recheck: **1 / 1 PASS**
- Tamil source: **COMPLETE / FROZEN**
- English T0–T5: **PASS**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Frozen Tamil authority: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`.  
Verified English article blob: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`.

Detailed non-regression decisions and release provenance are in:

- `publications/kayittril-thongiya-kanapathi/PUBLICATION_COMPLETION_REVIEW.md`
- `publications/kayittril-thongiya-kanapathi/VISUAL_TEXT_FIDELITY_REVIEW.md`
- `publications/kayittril-thongiya-kanapathi/translations/en/RELEASE_REPORT.md`

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is discovered.

---

# Publication 3 — உணர்ச்சிமாலை — TAMIL SOURCE COMPLETE / FROZEN; ENGLISH T0 COMPLETE

Workspace: `publications/unarchchimaalai/`  
Supplied source: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`

## Source identity

- title-page witness: `உணர்ச்சிமாலை`
- cover title: `உணர்ச்சி` / `மாலை`
- author witnesses: `மு.கருணாநிதி` on cover; `மு. கருணாநிதி` on title page
- edition statement: **`முதற்பதிப்பு—1951`**
- publisher: **கருணாநிதி பதிப்பகம், சிந்தாதிரிப்பேட்டை, சென்னை-2.**
- type: **10-article collection / multi-article publication**
- physical scans: **50**
- source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`
- source file size: **79,471,633 bytes**
- source PDF committed: **No**
- printed contents page: **none**

## Publication-specific user instruction — controlling lexical rule

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features.**

Therefore:

- Gemini word tokens are the lexical baseline wherever supplied;
- scan controls punctuation, spacing, headings, paragraph/quotation/verse layout, boundaries and physical-copy evidence;
- scan/Gemini lexical disagreements are logged instead of silently changed;
- whole omitted source text may be recovered only under the user's explicit missing-paragraph/missing-text permission, with provenance.

This publication-specific rule overrides the repository's usual OCR-as-aid lexical practice for this publication only.

## Frozen physical/article structure

- scans **1–5**: front matter
- scans **6–9**: Article 1 — `உணர்ச்சி மாலை`
- scans **10–15**: Article 2 — `புரட்சி வளர்ந்த கதை`
- scans **16–18**: Article 3 — `போகிறான்;போகிறான்..!`
- scans **19–29**: Article 4 — `இராவணன் நம் பாட்டன்`
- scans **30–32**: Article 5 — `இங்கல்ல! இரஷ்யாவில்`
- scans **33–38**: Article 6 — `3, 57, 90.`
- scans **39–41**: Article 7 — `30-1-1948`
- scans **42–44**: Article 8 — `பத்தினியே உன்போல்...!`
- scans **45–47**: Article 9 — `அன்னை நாகம்மையார்!`
- scans **48–49**: Article 10 — `கவிதையல்ல - கண்ணீர்க்கடல் !`
- scan **50**: separate `மணமகள்` back-cover advertisement

Every article-opening scan is unnumbered. Scan 20 preserves only the visible page-position `1`; no unseen `19` is reconstructed.

Independent heading witnesses remain frozen:

- publication/title-page `உணர்ச்சிமாலை` vs Article 1 `உணர்ச்சி மாலை`;
- Article 3 `போகிறான்;போகிறான்..!`;
- Article 4 `இராவணன்` / `நம் பாட்டன்`;
- Article 8 `பத்தினியே` / `உன்போல்...!`;
- Article 10 `கவிதையல்ல -` / `கண்ணீர்க்கடல் !`.

## Tamil archival gates — FINAL

- P0 intake: **COMPLETE**
- P1 metadata + 50-scan page/boundary map: **COMPLETE**
- P2 page records: **COMPLETE — 50 / 50 verified**
- P3 article assemblies: **COMPLETE — 10 / 10**
- P4 source audit / completeness review: **PASS**
- P5 strict visual word/punctuation fidelity: **COMPLETE — 50 / 50 PASS**
- P5 article strict recheck: **10 / 10 PASS**
- P5 source-supported structural/punctuation/spacing/layout corrections propagated: **236**
- documented Gemini/source lexical conflicts retained: **18**
- outstanding `needs-review` / blocked fidelity items: **0**
- unresolved Tamil/body blockers: **0**
- **Tamil source: COMPLETE / FROZEN**

## P5 durable recoveries / non-regression

- scan 19 whole-page Gemini omission remains source-recovered with explicit provenance;
- scan 32 Gemini lexical/order sequence remains retained despite scan disagreement;
- scan 33/34 physical boundary is corrected: scan 33 ends at `சுய நலத்திற்காக`; scan 34 begins `சூதர்களை சுற்றி...`;
- scan 41 remains Article 7's end at `வரலாற்றை வீணாக்கிய`;
- scan 42 source-visible `பதில் இல்லை.` is recovered under the explicit missing-text permission;
- scan 43 `* * *` separator is restored;
- scan 48 Gemini `ப்ழச்சளை` remains retained;
- scan 49 Gemini placement of `விட்டாய்.` remains retained despite scan-order disagreement;
- scan 49 publication-source note/imprint remains outside Article 10; printer line is `அன்பன் அச்சகம், சென்னை-1.`;
- scan 50 `BALU` / `BROS` remains stacked advertisement text outside all articles.

The complete 18-item lexical conflict ledger is in `publications/unarchchimaalai/VISUAL_TEXT_FIDELITY_REVIEW.md`. These conflicts are not blockers under the user's current lexical rule and must not be silently normalised.

## Frozen Tamil article authorities for translation — T0 reverified

1. Article 1 — `c63837a9f7c02d6f3a18171a512d46788f66ad92`
2. Article 2 — `dda81363f512ee2f829c367ae929ce3610604fe9`
3. Article 3 — `92eb1a68d65f65dd71274e5e79f3209e63359d9a`
4. Article 4 — `006f2f75dbc3eea796170a29aee0befd162522e7`
5. Article 5 — `c8ac4d7c241832e07bbb24c5cee935588673f4ac`
6. Article 6 — `f3634a63bff94f5647dbbdfa7dfe9b1b0a2479d8`
7. Article 7 — `bac121257d24477bc3c7e8c65f4b3f7b8a419bad`
8. Article 8 — `2e57a4c7c53ae4354942b5e64c5a2c4a33f3be2f`
9. Article 9 — `4dd0bbc03f278c9bfc02b189b285a1891aa44d2d`
10. Article 10 — `f856664d86695237a23d0ffc0bef088d32a82fe9`

Any later Tamil correction reopens the affected frozen blob authority and downstream English gates.

## English T0 — COMPLETE / PASS

T0 was executed against live `main` after P5 closure.

Created:

- `publications/unarchchimaalai/TRANSLATION_PLAN.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

T0 results:

- frozen Tamil authorities verified against live `main`: **10 / 10 PASS**;
- translation order recorded: **Articles 1 → 10 in source order**;
- 18-item P5 Gemini/source conflict provenance carried into English review setup: **PASS**;
- scan 19 and scan 42 source-recovered frozen text carried into translation authority notes: **PASS**;
- English article bodies created: **0**;
- T1 drafts: **0 / 10**;
- T2 fidelity-reviewed: **0 / 10**;
- T3 voice-reviewed: **0 / 10**;
- T4 audited: **0 / 10**;
- T5 verified: **0 / 10**;
- unresolved T0 translation blockers: **0**.

No English title or article body is frozen at T0. Article 1 will establish the initial publication voice baseline and first live lexicon decisions.

## Final Tamil / translation setup records

- `publications/unarchchimaalai/README.md`
- `publications/unarchchimaalai/metadata/source.md`
- `publications/unarchchimaalai/indexes/page-map.md`
- `publications/unarchchimaalai/indexes/contents.md`
- `publications/unarchchimaalai/audit.md`
- `publications/unarchchimaalai/VISUAL_TEXT_FIDELITY_REVIEW.md`
- `publications/unarchchimaalai/PUBLICATION_COMPLETION_REVIEW.md`
- `publications/unarchchimaalai/TRANSLATION_PLAN.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

---

# Exact next activity

Execute **Article 1 T1 — complete close English draft for `உணர்ச்சி மாலை`** from frozen Tamil blob:

`c63837a9f7c02d6f3a18171a512d46788f66ad92`

T1 must:

1. translate the complete Article 1 paragraph by paragraph from the frozen Tamil assembly only;
2. preserve all embedded verse lineation and every source scan-boundary comment for scans 6–9;
3. establish a provisional English title and record initial living-lexicon decisions;
4. preserve Kalaignar's directness, repetitions, commands, rhetorical questions, praise and polemical force;
5. create `publications/unarchchimaalai/translations/en/01-unarchchi-maalai.md` with `translation_status: draft` and the exact frozen Tamil blob SHA;
6. update the English tracker, lexicon, review ledger, publication plan and this handover;
7. **stop before T2 bilingual fidelity review**.

## Current blockers

**None.**