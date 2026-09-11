# P1 Source Structure Review — ஆறுமாதக் கடுங்காவல்

Source artifact: `TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

## Gate result

**P1 — COMPLETE / PASS FOR THE SUPPLIED PDF ARTIFACT (150 / 150 physical pages visually inspected).**

This P1 result is intentionally scoped to the **actual attached PDF artifact currently available to the project**. It does **not** resolve the separate publication-level discrepancy that the user reports a 224-page complete source.

The user explicitly authorised proceeding with P1 without waiting for P0 SHA-256/page-count closure.

## Source facts used for this P1

- raw uploaded file size — **282,020,019 bytes**;
- backing PDF exposed to direct page rendering — **150 physical pages**;
- all physical pages **1–150** were rendered/inspected for structural classification;
- source PDF committed to repository — **No**;
- P0 SHA-256 — **still pending**;
- user-reported complete publication/PDF extent — **224 pages**, retained as unresolved external/source-completeness metadata.

## Structural map

| Physical scan(s) | P1 classification | Notes |
|---:|---|---|
| 1 | physical-copy / ownership-donation mark | non-publication physical-copy layer |
| 2 | title page | title / author / publisher witness |
| 3 | imprint / edition page | first-edition 1953 witness |
| 4 | publisher note | front matter |
| 5 | blank / reverse / show-through | no independent printed body block |
| 6–7 | dedication | `காணிக்கை` |
| 8 | illustrated front-matter page | `முரசு` witness |
| 9 | blank / reverse / show-through | front-matter separator |
| 10–66 | main text, continuous text-bearing run | first long body sequence |
| 67 | blank / reverse / show-through | clear structural separator |
| 68–106 | main text, continuous text-bearing run | second long body sequence |
| 107 | blank / reverse / show-through | clear structural separator |
| 108 | low-density nonblank intertitle / transition page | structurally distinct; exact wording belongs to P2 transcription |
| 109 | blank / reverse / show-through | clear separator after intertitle/transition |
| 110–150 | main text, continuous text-bearing run | final accessible body sequence |

## Exact blank/reverse pattern

The rendered images for scans **5, 9, 67, 107 and 109** share the same blank/reverse image signature and are treated as structural blank/reverse pages for P1.

## Front matter

Confirmed structural sequence:

1. physical-copy mark;
2. title;
3. imprint;
4. publisher note;
5. blank/reverse;
6–7. dedication;
8. illustrated front-matter page;
9. blank/reverse;
10. body begins.

No separate printed contents page is visible in scans **1–9**.

## Body structure

P1 identifies three long text-bearing body runs:

- **10–66**
- **68–106**
- **110–150**

These are separated by blank/reverse pages and one distinct intertitle/transition page at scan 108.

P1 does **not** invent article/chapter titles where exact wording has not yet been transcribed. Exact heading text, dates, place names and printed folio values are reserved for source-faithful P2 page records unless directly established at P1.

## Printed pagination

A single canonical printed-page offset/formula is **not asserted** in this P1 review.

Reason:

- this is an image-only historical scan;
- P1's purpose here is structural mapping;
- exact printed folio values must be read directly from each page rather than inferred from scan sequence;
- the supplied artifact also has an unresolved 150-vs-224 source-completeness discrepancy.

During P2, each page record must capture the printed page number where visibly present and leave suppressed folios null rather than infer them.

## Contents / index

- separate printed contents page in supplied scans 1–150 — **not found**;
- back-of-book index / contents — **not present within the supplied artifact boundary**;
- no claim is made about material outside the supplied 150-page artifact.

## Final supplied-artifact boundary

Scan **150** is a **text-bearing body page**, not an obvious blank, advertisement, colophon or back cover.

Therefore:

- scan 150 is the **end of the supplied PDF artifact**;
- it must **not** be described as the proven end of the complete 1953 publication;
- the user-reported 224-page extent remains an unresolved publication-level completeness issue.

## Historical Tamil glyph overlay

P1 is structural only.

P2 and P5 must follow `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

Every text-bearing page must explicitly check at least:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No historical glyph decoding was silently applied during P1.

## P1 conclusion

For the **supplied 150-page PDF artifact**:

- pages structurally inspected — **150 / 150**;
- unmapped physical pages — **0**;
- blank/reverse pages — **5**: scans 5, 9, 67, 107, 109;
- title/imprint/publisher/dedication/illustration front matter — **mapped**;
- main body runs — **mapped**;
- intertitle/transition at scan 108 — **mapped structurally**;
- source-artifact end — **scan 150**;
- P1 structural blockers within this artifact — **0**.

**P1 RESULT: PASS FOR SUPPLIED ARTIFACT.**

## Remaining source-completeness caveat

P0 remains open because SHA-256 is pending, and the user-reported **224-page** complete-source extent does not match the 150-page artifact available to this workflow.

This caveat does not invalidate the P1 map of the supplied artifact, but it prevents claiming that scans 1–150 constitute the entire historical publication.

## Exact next activity

Under the user's explicit override, proceed to **P2 page-level transcription of the supplied artifact**, beginning with the first controlled five-scan batch.

Recommended first P2 batch:

**scans 1–5**

For P2:
- create one canonical page record per physical scan;
- separate printed text from physical-copy marks;
- record printed folio only when visible;
- preserve punctuation/spacing/source spelling;
- apply the historical Tamil glyph gate on every text-bearing page;
- commit immediately after each five-scan batch;
- do not infer content outside the supplied artifact.
