# Visual text fidelity review — உணர்ச்சிமாலை

## Status

**P5 — IN PROGRESS**

- physical scans visually reviewed: **50 / 50**
- page records with identified source-supported structural corrections propagated: **complete**
- article-assembly propagation/recheck: **pending**
- English translation: **not started**

This publication follows the user-established lexical rule:

> **Retain the words as in Gemini. Correct only indentation, punctuation, spaces, missing paragraphs, headings, and analogous structural/formatting features.**

Accordingly, this P5 pass does not silently replace Gemini lexical tokens merely because the controlling scan appears to show another word/form.

## Scope and method

Controlling source: `TVA_BOK_0063821_உணர்ச்சிமாலை.pdf`  
Physical scans: **50**  
Source SHA-256: `d2d45de049505218fd612bf71949135e34ecb317ffb5d003dfe59a3a0608461d`

All 50 physical scans were visually rechecked, including:

- scans 1–5 front matter;
- scans 6–49 all ten article units;
- scan 49 publication-source note and printer imprint;
- scan 50 separate `மணமகள்` back-cover advertisement.

The pass rechecked visible punctuation, spacing, quotation marks, headings, dates/numbers, paragraph/verse layout, cross-page continuation, article/non-body boundaries and physical-copy marks.

## Page-layer correction result

The visual pass identified **236 source-supported structural/punctuation/spacing/layout corrections** in the working page layer. Those permitted corrections have now been propagated to the affected `pages/*.md` records.

Important P5 structural recoveries include:

- scan 33/34 physical page boundary corrected: scan 33 now ends at `சுய நலத்திற்காக`, with `சூதர்களை சுற்றி...` beginning scan 34;
- scan 42 source-visible `பதில் இல்லை.` restored under the user's explicit missing-paragraph/missing-text permission and labelled as source-recovered rather than Gemini-derived;
- scan 43 source-visible `* * *` separator restored;
- scan 49 printer imprint spacing restored to `அன்பன் அச்சகம், சென்னை-1.`;
- scan 50 `BALU` / `BROS` restored as stacked lines;
- all source/non-body boundaries remain intact.

## Gemini/source lexical conflict ledger — retained, not silently changed

The strict visual pass records the following **18** lexical/order conflicts. These remain deliberately unresolved in the canonical wording under the user's Gemini-baseline rule:

1. scan 2 — Gemini/repo `கருணாநிதி பதிப்பகம்` vs scan-appearing `கருணநிதி பதிப்பகம்`;
2. scan 2 — Gemini `சிந்தாதிரிபேட்டை` vs scan-appearing `சிந்தாதிரிப்பேட்டை`;
3. scan 11 — Gemini `மௌனமாகவே` vs scan-appearing `மெளனமாகவே`;
4. scan 26 — Gemini `போதுமென்` vs scan-appearing `போதுமென`;
5. scan 30 — Gemini `பீடத்தில்` vs scan-appearing `பீடத்திலே`;
6. scan 31 — Gemini `திரும்பினார்` vs scan-appearing `திரும்பினர்`;
7. scan 33 — Gemini `எழுதினான்` vs scan-appearing `எழுதினை`;
8. scan 35 — Gemini `சம்மாதிக்காத` vs scan-appearing `சம்மதிக்காத`;
9. scan 38 — Gemini `ஒரியண்டல்` vs scan-appearing `ஓரியண்டல்`;
10. scan 39 — Gemini `ஒடி` vs scan-appearing `ஓடி`;
11. scan 39 — Gemini `சோக பூகம்.` locus vs visibly different/longer source continuation;
12. scan 39 — Gemini `சுக்குநூறாக்கம்` vs source-visible additional lexical continuation after that token;
13. scan 41 — Gemini `ஒய்வதற்கு` vs scan-appearing `ஓய்வதற்கு`;
14. scan 41 — Gemini/order `நாள் 30-1-1948... ஆமாம்... வரலாற்றை வீணாக்கிய` vs different scan layout/order;
15. scan 42 — Gemini `அனுக்ரகம்` vs scan-appearing `அனுக்கிரகம்`;
16. scan 43 — Gemini `அழ்காக` vs scan-appearing `அழகாக`;
17. scan 44 — Gemini `ஓருருவாகிப்` vs scan-appearing `ஒருருவாகிப்`;
18. scan 49 — Gemini `எங்கனம்` vs scan-appearing `எங்ஙனம்`.

Existing durable conflicts remain in force, including scan 32's Gemini word/order sequence, scan 48 `ப்ழச்சளை`, and scan 49 placement of `விட்டாய்.`.

## Non-regression boundaries

- publication `உணர்ச்சிமாலை` remains distinct from Article 1 `உணர்ச்சி மாலை`;
- scan 20 still records only the visible printed-page mark `1`, never an inferred `19`;
- scan 19 source-recovered Gemini omission remains explicitly traceable;
- scan 41 Article 7 terminal Gemini/order witness remains preserved;
- scan 49 publication-source note/imprint remains outside Article 10 body;
- scan 50 remains outside every article assembly;
- no English translation has been started.

## Remaining P5 closure work

Before P5 can be marked PASS:

1. propagate the corrected page-layer punctuation/spacing/layout into all ten `articles/*.md` assemblies;
2. preserve every scan-boundary comment and the corrected scan 33/34 boundary;
3. include scan 42 source-recovered `பதில் இல்லை.` and scan 43 separator in Article 8;
4. recheck all ten assemblies against the now-corrected page layer;
5. confirm the 18 lexical conflicts remain unchanged;
6. update publication README, source metadata, audit record and root `HANDOVER.md` with final P5 result.

**Do not begin English translation before this closure is complete.**
