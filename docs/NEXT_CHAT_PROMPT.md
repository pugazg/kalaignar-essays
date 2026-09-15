# NEXT CHAT PROMPT — துடிக்கும் இளமை / P5 strict visual-text-fidelity pass

Continue directly in `pugazg/kalaignar-essays`, branch `main`. **LIVE MAIN IS AUTHORITATIVE.**

## Publication 12 — frozen

`publications/aaru-maatha-kadungkaaval/` remains **RELEASE COMPLETE / FROZEN**.

Do not reopen it merely for stylistic polishing.

## Publication 13 — active

Workspace:

`publications/thudikkum-ilamai/`

Controlling source:

`TVA_BOK_0063985_துடிக்கும்_இளமை.pdf`

Source identity:

- physical scans — **33**
- bytes — **50,703,452**
- SHA-256 — **`309042a481db1d198d331b1c16f11ea7acce5ad0cc4ab78ee53c2a702e0ecb11`**
- source authority — **rendered scan pixels**
- source PDF committed — **No**

Printed identity:

- title — **`துடிக்கும் இளமை`**
- author — **`மு. கருணாநிதி`**
- publisher — **`K. R. நாராயணன்`**
- price — **`ஆறணா`** — user-confirmed; do not regress to `ஆறணை`
- edition — **`முதற் பதிப்பு`**
- edition date — **`16—12—'51`**
- printer — **`ஸ்ரீ மகள் அச்சகம், சென்னை-1`**

## Durable gate state

- P0 — **PASS**
- P1 — **PASS — 33/33**
- P2 — **PASS — 33/33**
- P3 — **PASS — 4/4**
- P4 — **COMPLETE / PASS**
- P5 — **NOT STARTED**
- English — **BLOCKED until Tamil P5 / frozen**

P4 authority:

`publications/thudikkum-ilamai/P4_SOURCE_AUDIT.md`

P4 totals:

- source coverage — **33/33**
- front matter — **4/4**
- article body — **25/25**
- advertisements/promotional matter — **4/4**
- article assemblies — **4/4**
- missing / duplicate scan records — **0 / 0**
- article-range defects — **0**
- advertisement leakage — **0**
- physical-copy-mark contamination — **0**
- propagation defects — **0**
- unresolved blockers — **0**

## Canonical article authorities

1. `articles/01-thudikkum-ilamai.md` — scans **5–12**
2. `articles/02-annamalaikku-arogara.md` — scans **13–19**
3. `articles/03-poompuhar.md` — scans **20–24**
4. `articles/04-vetri-vilakku.md` — scans **25–29**

## Exact activity — P5

Perform the final strict visual-text-fidelity pass over **all 33 physical scans in one go** unless tool limits force durable sub-batches.

For every physical scan:

- compare the rendered source pixels against the canonical P2 page record word-by-word;
- verify punctuation, meaningful spacing, headings, numerals, prices, date punctuation, quotation marks and page-end fragments;
- re-run historical Tamil glyph identity checks where relevant;
- preserve physical-copy stamps / handwriting outside the printed-text layer;
- do not use OCR, web, Wikisource, Tamil Digital Library text or alternate editions;
- do not modernize spelling, grammar or punctuation;
- never guess;
- record every canonical correction found;
- propagate any body correction to the corresponding P3 article assembly;
- revalidate affected page-boundary joins after any correction.

Mandatory durable readings that must not regress:

- scan 2 price — **`ஆறணா`**
- scan 3 date — **`16—12—'51`**
- scan 4 — **`எழுச்சியூட்டும் எழுத்தோவியங்களே`**
- scan 9 — **`விந்தை`**
- scan 10 — **`உ.வே.சாமிநாத அய்யர்`**
- scan 13 title — **`அண்ணாமலைக்கு அரோகரா!`**
- scan 27 — **`அரசாங்கம்`**
- retired `ஆறணை` and `அண்ணனுக்கு அரசா!` remain correction-history only.

After the visual pass:

- create a durable P5 visual-fidelity report;
- update P2 page records for any corrections;
- propagate corrections to P3 article assemblies;
- recheck all **4/4** article assemblies;
- update publication `README.md`, `audit.md`, root `HANDOVER.md`, and this prompt;
- if and only if all 33 scans pass with no unresolved discrepancies, mark Tamil **VISUAL-TEXT-FIDELITY COMPLETE / FROZEN**.

Expected closeout:

- P5 physical scans — **33/33 PASS**
- article assemblies — **4/4 revalidated**
- unresolved fidelity discrepancies — **0**
- blockers — **0**
- Tamil archival layer — **FROZEN**

Only after that may the English translation workflow begin.
