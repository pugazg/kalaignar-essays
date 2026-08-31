# English Translation Plan — உணர்ச்சிமாலை

Publication: `உணர்ச்சிமாலை`  
Author: `மு. கருணாநிதி`  
Workspace: `publications/unarchchimaalai/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

> **Translate the language; do not neutralise the voice.**

## T0 source prerequisite — COMPLETE / PASS

- Tamil source: **COMPLETE / FROZEN**
- P5: **50 / 50 PASS**
- Tamil article assemblies: **10 / 10 strict-rechecked**
- unresolved Tamil/body blockers: **0**
- publication-specific lexical rule: Gemini word tokens remain frozen where supplied; documented scan/Gemini conflicts are not silently normalised.

## Frozen Tamil authorities

| # | Tamil title | Scans | Blob SHA |
|---:|---|---:|---|
| 1 | `உணர்ச்சி மாலை` | 6–9 | `c63837a9f7c02d6f3a18171a512d46788f66ad92` |
| 2 | `புரட்சி வளர்ந்த கதை` | 10–15 | `dda81363f512ee2f829c367ae929ce3610604fe9` |
| 3 | `போகிறான்;போகிறான்..!` | 16–18 | `92eb1a68d65f65dd71274e5e79f3209e63359d9a` |
| 4 | `இராவணன் நம் பாட்டன்` | 19–29 | `006f2f75dbc3eea796170a29aee0befd162522e7` |
| 5 | `இங்கல்ல! இரஷ்யாவில்` | 30–32 | `c8ac4d7c241832e07bbb24c5cee935588673f4ac` |
| 6 | `3, 57, 90.` | 33–38 | `f3634a63bff94f5647dbbdfa7dfe9b1b0a2479d8` |
| 7 | `30-1-1948` | 39–41 | `bac121257d24477bc3c7e8c65f4b3f7b8a419bad` |
| 8 | `பத்தினியே உன்போல்...!` | 42–44 | `2e57a4c7c53ae4354942b5e64c5a2c4a33f3be2f` |
| 9 | `அன்னை நாகம்மையார்!` | 45–47 | `4dd0bbc03f278c9bfc02b189b285a1891aa44d2d` |
| 10 | `கவிதையல்ல - கண்ணீர்க்கடல் !` | 48–49 | `f856664d86695237a23d0ffc0bef088d32a82fe9` |

## Article tracker

| # | Tamil title | Status | T0 | T1 | T2 | T3 | T4 | T5 |
|---:|---|---|---|---|---|---|---|---|
| 1 | உணர்ச்சி மாலை | `verified` | PASS | PASS | PASS | PASS | PASS | PASS |
| 2 | புரட்சி வளர்ந்த கதை | `verified` | PASS | PASS | PASS | PASS | PASS | PASS |
| 3 | போகிறான்;போகிறான்..! | `not-started` | PASS | — | — | — | — | — |
| 4 | இராவணன் நம் பாட்டன் | `not-started` | PASS | — | — | — | — | — |
| 5 | இங்கல்ல! இரஷ்யாவில் | `not-started` | PASS | — | — | — | — | — |
| 6 | 3, 57, 90. | `not-started` | PASS | — | — | — | — | — |
| 7 | 30-1-1948 | `not-started` | PASS | — | — | — | — | — |
| 8 | பத்தினியே உன்போல்...! | `not-started` | PASS | — | — | — | — | — |
| 9 | அன்னை நாகம்மையார்! | `not-started` | PASS | — | — | — | — | — |
| 10 | கவிதையல்ல - கண்ணீர்க்கடல் ! | `not-started` | PASS | — | — | — | — | — |

## Verified baseline

Article 1 final English blob: `4246c9f1e206d5703fe50297657bb0af2a8e57e6`.  
Article 2 final English blob: `f1599a8e7cae4ba749b9be2857705b152887f9f8`.

Article 2 T5 reconfirmed the complete T1–T4 chain, metadata, title, frozen Tamil SHA, scans 10–15, source-boundary comments, cross-scan continuations, dates/numbers, quotation boundaries, source-sensitive transliterations and T3 voice. T5 required **0 body corrections** and left **0 blockers**.

## Publication-specific cautions

1. Translate only from frozen Tamil assemblies.
2. Preserve the 18 documented P5 scan/Gemini lexical conflicts as upstream provenance; do not silently translate from alternate scan readings.
3. Article 4 scan 19 and Article 8 scan 42 contain frozen source-recovered text.
4. Article 8 scan 43 `* * *` and Article 10 verse lineation are structural source authority.
5. Article 10 excludes scan-49 publication-close matter and scan-50 advertisement.
6. Do not silently repair source-sensitive forms such as Article 10 `ப்ழச்சளை`.
7. Preserve questions, exclamations, repetition, direct address and page-boundary comments.

## Exact next activity

Execute **Article 3 T1 — complete close English draft for `போகிறான்;போகிறான்..!`** from frozen Tamil blob `92eb1a68d65f65dd71274e5e79f3209e63359d9a`, scans **16–18**. Translate the entire article paragraph by paragraph, retain scan comments and rhetorical structure, establish only terminology actually encountered, leave `translation_status: draft`, and **stop before T2**.