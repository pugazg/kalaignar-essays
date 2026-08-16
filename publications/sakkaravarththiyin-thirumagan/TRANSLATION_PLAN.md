# English Translation Plan — சக்கரவர்த்தியின் திருமகன்

Publication: `சக்கரவர்த்தியின் திருமகன்`  
Author: `கலைஞர் மு. கருணாநிதி`  
Workspace: `publications/sakkaravarththiyin-thirumagan/`  
Target language: **English**

Permanent translation policy: [`../../ESSAY_TRANSLATION_GUIDE.md`](../../ESSAY_TRANSLATION_GUIDE.md)

## 1. Translation objective

Translate all **14 articles** into English while retaining Kalaignar's language as far as English allows: his direct address, sarcasm, rhetorical questions, repetitions, abrupt turns, exclamations, polemical labels, imagery, challenges to the reader, and argumentative rhythm.

This is not a summary, adaptation, scholarly paraphrase or modern rewrite.

The English should read naturally enough to be understood, but it must not become neutral, polite or academic at the cost of Kalaignar's voice.

## 2. Source prerequisite — PASSED

The translation phase is permitted to begin because the Tamil source layer has already passed both archival gates:

- physical scans source-recorded: **83 / 83**
- strict word-by-word visual fidelity: **83 / 83**
- Tamil article assemblies: **14 / 14**
- article assemblies strict-rechecked: **14 / 14**
- unresolved `NEEDS-PIXEL-REVIEW`: **0**

The English translation source is therefore the strict-reviewed Tamil article assembly in `articles/`.

## 3. Translation workspace

English files will live under:

```text
publications/sakkaravarththiyin-thirumagan/
  translations/
    en/
      README.md
      LEXICON.md
      TRANSLATION_REVIEW.md
      01-sakkaravarththiyin-thirumagan.md
      02-thegamum-unarvum.md
      03-sathi-nirupikkappadugirathu.md
      04-kamarajan-aadkonda-dasaratharajan.md
      05-paraththuvaja-aasramama-paris-nagarathu-para.md
      06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md
      07-vibishanarukku-vidai-yalippom.md
      08-naadaanda-mannan-naathiyatru-seththaan.md
      09-thanthai-maganum-tharumam-thavariyavargal.md
      10-vishnu-avatharam-enbathum-ramanidam.md
      11-nadappathellam-narayanan-seyala.md
      12-maarisanai-thuraththi-sendra-ramanidam.md
      13-thurogigal-santhippu.md
      14-kaariyamaagum-varaiyil-kaalai-pidi.md
```

English filenames mirror the Tamil article filenames so source/translation pairing remains obvious.

## 4. Article order

Translate in printed/source order. Do not skip ahead merely because a later article is shorter.

| Article | Tamil title | Tamil source | Translation status |
|---:|---|---|---|
| 1 | சக்கரவர்த்தியின் திருமகன் | `articles/01-sakkaravarththiyin-thirumagan.md` | `not-started` |
| 2 | தேகமும் உணர்வும் | `articles/02-thegamum-unarvum.md` | `not-started` |
| 3 | சதி நிரூபிக்கப்படுகிறது | `articles/03-sathi-nirupikkappadugirathu.md` | `not-started` |
| 4 | காமராஜன் ஆட்கொண்ட தசரதராஜன்! | `articles/04-kamarajan-aadkonda-dasaratharajan.md` | `not-started` |
| 5 | பரத்துவாஜா ஆஸ்ரமமா - பாரிஸ் நகரத்து ‘பாரா’? | `articles/05-paraththuvaja-aasramama-paris-nagarathu-para.md` | `not-started` |
| 6 | இராமன் காட்டேகியது ஏன்? ரிஷியின் சாபமா? கைகேயி கோபமா? | `articles/06-iraman-kaattegiyathu-en-rishiyin-saabama-kaikeyi-kobama.md` | `not-started` |
| 7 | விபீஷணருக்கு விடை யளிப்போம்! | `articles/07-vibishanarukku-vidai-yalippom.md` | `not-started` |
| 8 | நாடாண்ட மன்னன் நாதியற்று செத்தான் | `articles/08-naadaanda-mannan-naathiyatru-seththaan.md` | `not-started` |
| 9 | தந்தை மகனும் தருமம் தவறியவர்கள்! | `articles/09-thanthai-maganum-tharumam-thavariyavargal.md` | `not-started` |
| 10 | விஷ்ணு அவதாரம் எனப்படும் ராமனிடம்! | `articles/10-vishnu-avatharam-enbathum-ramanidam.md` | `not-started` |
| 11 | நடப்பதெல்லாம் நாராயணன் செயலா? | `articles/11-nadappathellam-narayanan-seyala.md` | `not-started` |
| 12 | மாரீசனைத் துரத்திச் சென்ற ராமனிடம் | `articles/12-maarisanai-thuraththi-sendra-ramanidam.md` | `not-started` |
| 13 | துரோகிகள் சந்திப்பு! | `articles/13-thurogigal-santhippu.md` | `not-started` |
| 14 | காரியமாகும் வரையில் காலைப் பிடி ! | `articles/14-kaariyamaagum-varaiyil-kaalai-pidi.md` | `not-started` |

## 5. Work unit — one article at a time

The default unit is **one complete article**.

For each article:

1. fetch the current Tamil assembly and record its blob SHA;
2. read the complete Tamil article before drafting its English title/body;
3. add/update difficult recurring terms in `translations/en/LEXICON.md`;
4. complete T1 close translation;
5. perform T2 bilingual fidelity review;
6. perform T3 Kalaignar-voice review;
7. perform T4 terminology / quotation / citation audit;
8. record corrections in `TRANSLATION_REVIEW.md`;
9. mark the article `verified` only after all gates pass;
10. update root `HANDOVER.md` before ending the activity.

For Article 1, use a deliberately slower first cycle because it establishes the English voice baseline for the remaining 13 articles.

## 6. Article 1 as the calibration article

Article 1 contains several features that must establish the permanent English style:

- repeated direct instructions to the reader such as `படியுங்கள்!`;
- Kalaignar's recurring `ஆச்சாரியார்` label;
- quoted passages from `கல்கி`;
- contradiction as a repeated argumentative device;
- sarcasm and direct ridicule;
- Aryan/Dravidian terminology;
- emphatic repetition;
- dates and publication citations;
- shifts between quotation, narration and direct challenge.

Article 1 will therefore be translated and reviewed before any later article is drafted. Its terminology and voice decisions become the starting baseline, but later source context may still require documented variants.

## 7. Retaining Kalaignar's voice — publication-specific priorities

This publication is strongly polemical. The English must preserve that character.

### Direct reader-address

Tamil imperatives such as `படியுங்கள்!`, `பாருங்கள்!`, and `கேளுங்கள்!` must remain direct English imperatives rather than becoming phrases such as `the reader may note`.

### Repetition

If Kalaignar repeats a word to mock, hammer home or intensify a point, keep the repetition. Do not edit it away as redundancy.

### Sarcasm and ridicule

Where the Tamil is mocking, the English should also be recognisably mocking. Do not convert sarcasm into neutral exposition.

### Epithets

`ஆச்சாரியார்` will not be silently replaced by a modern identifying name. The English layer will preserve the author's chosen referential label, normally as `Acharya`, unless the source itself uses a different name/label in that passage.

### Ideological vocabulary

Terms such as `ஆரியர்`, `திராவிடர்`, `பகுத்தறிவு`, and other recurring ideological vocabulary must retain their historical/polemical function. Decisions will be logged in the living lexicon.

### Quotations

Quoted `கல்கி` passages will be translated as quotations, with source dates/citations preserved. They will not be reconciled with another edition or external English rendering.

### Strong language

Insults, accusations and loaded comparisons will not be softened for modern English politeness.

## 8. Titles

Do not pre-translate all 14 titles mechanically at planning time.

For each article, choose its English title only after reading the complete Tamil article so that wordplay, irony and the article's argument can inform the rendering.

The translation file will preserve both:

- `title_ta` — exact Tamil assembly title;
- `title_en` — reviewed English title.

Question marks and exclamation marks that are rhetorically part of the title should remain rhetorically visible in English.

## 9. Page traceability

The English body will retain comments corresponding to Tamil source page boundaries:

```html
<!-- Tamil source: scan 9 / printed 7 -->
```

This gives a paragraph/page audit trail without duplicating the Tamil text in the English file.

## 10. Translation review record

`translations/en/TRANSLATION_REVIEW.md` will record, article by article:

- Tamil source blob SHA used;
- T1 draft state;
- T2 completeness/fidelity findings;
- T3 voice findings;
- T4 terminology/quotation/citation findings;
- corrections introduced during review;
- final status;
- unresolved choices, if any.

No article with an unresolved meaning-level question may be marked `verified`.

## 11. Living lexicon

`translations/en/LEXICON.md` begins as a controlled blank ledger and will be filled from Article 1 onward.

It should capture recurring choices, not merely proper names. Priority items include:

- `ஆச்சாரியார்` and other author-chosen labels;
- `ஆரியர்` / `திராவிடர்` vocabulary;
- `பகுத்தறிவு` and related ideological terms;
- recurring epic names and titles;
- compounds whose English can easily lose ridicule or force;
- periodical/publication names;
- intentionally contextual variants.

## 12. Publication-level final consistency pass

After Articles 1–14 are individually verified, do **not** immediately declare the English publication complete.

Perform a final cross-article review covering:

1. recurring names and epithets;
2. ideological terminology;
3. repeated rhetorical phrases;
4. treatment of `Kalki`, `Murasoli` and other publication references;
5. epic-name spelling;
6. quotation style;
7. title style;
8. preservation of rhetorical questions and imperatives;
9. accidental softening or academicisation;
10. completeness of all source page-boundary comments;
11. all 14 English files present;
12. all 14 review records closed.

Only after this may the publication status become **English translation complete**.

## 13. Planned phase sequence

### Phase E0 — setup

- permanent translation guide
- this publication translation plan
- English status tracker
- living lexicon
- review ledger
- root handover converted to active translation phase

### Phase E1 — Article 1 calibration

Translate Article 1 and complete T1–T4. Establish initial voice and lexicon decisions.

### Phase E2 — Articles 2–4

Translate in order, one article at a time, applying and refining the Article 1 baseline.

### Phase E3 — Articles 5–8

Continue one article at a time with full review gates.

### Phase E4 — Articles 9–11

Continue one article at a time with full review gates.

### Phase E5 — Articles 12–14

Complete the final three article translations and individual reviews.

### Phase E6 — publication consistency review

Run the 14-article terminology, voice, completeness and citation consistency pass.

### Phase E7 — English release closeout

- mark 14/14 English translations verified;
- close `TRANSLATION_REVIEW.md`;
- update publication/root README status;
- update the single root `HANDOVER.md`;
- declare English translation complete only if no unresolved item remains.

## 14. Progress at plan creation

- Phase E0: **IN PROGRESS / setup being created**
- English article drafts: **0 / 14**
- English articles verified: **0 / 14**
- final cross-article review: **not started**

## 15. Exact next translation activity

After the E0 documents are committed, begin **Article 1 — `சக்கரவர்த்தியின் திருமகன்`**.

Read its full strict-reviewed Tamil assembly first, bootstrap the lexicon from actual translation decisions, then create the complete English draft while preserving the source page-boundary comments. Do not begin Article 2 until Article 1 has passed its fidelity and Kalaignar-voice reviews.
