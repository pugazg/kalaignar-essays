# Next Chat Prompt — Kalaignar Essays / Articles

Use this file only as a convenience handoff. **Live `main` and the root `HANDOVER.md` are authoritative.**

## Current durable boundary

The previously active publication:

`publications/unarchchimaalai/` — **உணர்ச்சிமாலை**

is now **COMPLETE / FROZEN / RELEASED in both Tamil and English**.

### LIVE MAIN IS AUTHORITATIVE

Fetch live `main` **first**. The last confirmed live HEAD immediately before this continuation prompt was synchronized was:

`209552cc84f749e314e159dfcbd11a8445388cec` — `Close Unarchchimaalai E7 handover`

If `main` has advanced beyond that checkpoint, preserve the newer durable state. **Do not reset, overwrite, repeat or reopen later completed work merely because this prompt contains an older checkpoint.**

Before every write, re-fetch the target file and current live state as needed. Work directly on `main`.

## Mandatory startup

Before making any repository change, read completely:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. `HANDOVER.md`
5. this `docs/NEXT_CHAT_PROMPT.md`

For a genuinely new supplied work, also read and follow:

6. `docs/START_NEW_ESSAY_WORK_PROMPT.md`

For any existing publication, read its publication-specific README, metadata, fidelity/completion records and translation records before changing it.

## உணர்ச்சிமாலை — final release state

Tamil archival layer:

- physical scans: **50**
- P2: **50 / 50 verified**
- P3 assemblies: **10 / 10**
- P4: **PASS**
- P5 strict visual fidelity: **50 / 50 PASS**
- structural/punctuation/spacing/layout corrections propagated: **236**
- documented Gemini/source lexical conflicts retained: **18**
- Tamil blockers: **0**
- status: **COMPLETE / FROZEN**

English:

- T0: **PASS**
- T1–T5: **10 / 10 complete / verified**
- E6 publication-wide consistency review: **PASS**
- E7 English release closeout: **PASS / RELEASE COMPLETE**
- E6/E7 English body corrections: **0**
- E6/E7 frozen Tamil changes: **0**
- source/fidelity defects discovered: **0**
- gates reopened: **No**
- release blockers: **0**
- status: **COMPLETE / RELEASED / FROZEN**

Final English article blobs remain:

1. `4246c9f1e206d5703fe50297657bb0af2a8e57e6`
2. `f1599a8e7cae4ba749b9be2857705b152887f9f8`
3. `1134185bc21478775419adb3560b110c001d2b75`
4. `03ac3b0fc25f38a4b56c352f53bf73915b1f33fb`
5. `c689ff90f08d389a5e7ebc4849c30d58dfe81766`
6. `cf9187b40bc1bc64806a1df84e45c884b1b8d9a8`
7. `6cfb28e2d83ba84ee2daa54606561479b61498b0`
8. `6b12e6b3cc09b6de402998bb3824e7a98808f885`
9. `204ffed012f4bd91b3077065f031d6b2db747854`
10. `cee8ea3c33495615ffc988a1875d71e40f8224a3`

## உணர்ச்சிமாலை non-regression

Do not reopen or homogenise the released publication absent a genuine source-supported or release-blocking defect.

Permanent publication-specific rules include:

- Gemini lexical tokens remain the frozen Tamil lexical baseline wherever supplied; scan/Gemini lexical disagreements remain documented rather than silently substituted;
- English authority remains the frozen Tamil assemblies;
- preserve `Dravidam` / `Dravidians` / `Dravidian` according to immediate source form;
- preserve Article 4 `Kambar` / `Kamban` source-form distinction;
- preserve Gandhi source-label variants;
- preserve `Brahmin` forms separately from source-bearing `Parppanar` forms, with `Vediyars` separate;
- preserve `Vaidheegam` / contextual `Vaidheega`, `Harijan` / `Arijan`, `Oriental College` / frozen `Oriyantal College`, and Article 9 name/honorific variants;
- preserve source-bearing epic forms and unexplained transliterations, including frozen raw `ப்ழச்சளை`;
- preserve scan 32's frozen irregular order, Article 7's deliberately incomplete ending, scan 42 `No answer.`, scan 43 `* * *`, frozen scan 49 `You left.` placement, and scan 49/50 exclusions.

> **Translate the language; do not neutralise the voice.**

## Exact next project activity

There is **no remaining activity for `உணர்ச்சிமாலை`**.

For the next project activity, wait for the user to supply or explicitly identify the next Kalaignar essay/article publication, then perform new-work intake under `docs/START_NEW_ESSAY_WORK_PROMPT.md` and the permanent guides.

Do **not** start a new publication from memory or guesswork without supplied/identified source material.

## Fresh-window execution rule

When the user says **“Proceed with next activity”**, fetch live `main`, read `HANDOVER.md`, and execute the exact next recorded activity. If no new source/work has been supplied, report that the previous publication is release-complete and that the next step is source intake rather than reopening completed work.