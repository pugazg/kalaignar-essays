# Future Publication Handover Template — Kalaignar Essays / Articles

This is a **template for updating the repository root `HANDOVER.md` when a new publication becomes active**.

> **Do not create a second live handover from this template.** The repository must continue to have one authoritative live handover: [`../HANDOVER.md`](../HANDOVER.md).

Copy/adapt the relevant sections below into the root handover and keep them current after every meaningful activity.

---

# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, transcription, fidelity, translation or release activity.**

## Mandatory startup

Read completely before making changes:

1. [`ESSAY_PROCESSING_GUIDE.md`](../ESSAY_PROCESSING_GUIDE.md)
2. [`ESSAY_TRANSLATION_GUIDE.md`](../ESSAY_TRANSLATION_GUIDE.md) if translation is in scope
3. [`docs/FUTURE_WORK_GUIDELINES.md`](FUTURE_WORK_GUIDELINES.md)
4. root `HANDOVER.md`
5. active publication `README.md`
6. active publication `metadata/source.md`
7. active publication `indexes/page-map.md`
8. active publication fidelity/review records relevant to the current phase
9. if translating: `TRANSLATION_PLAN.md`, English tracker, lexicon and translation-review ledger

Always inspect the current repository state on `main` before changing files.

## Active publication

Workspace: `publications/<publication-slug>/`  
Supplied source: `<source-filename.pdf>`

- source title as printed: `<...>`
- author as printed: `<...>`
- physical scans: `<count>`
- source SHA-256: `<sha256>`
- file size: `<bytes/MB>`
- edition / publisher / year visible in scan: `<...>`
- printed contents / article count: `<...>`
- source PDF committed to repository: **No**

## Source authority

The supplied scan is the controlling witness for this edition.

Never silently modernise, correct, normalise, reconstruct or improve the Tamil. Preserve source-visible wording, spelling, punctuation, names, numbers, repetitions, paragraphing and unusual grammatical/typographical forms. Separate physical-copy marks from printed text.

OCR and parsed text may assist, but are not authoritative.

## Publication structure

- metadata source record: `<path>`
- contents index: `<path or n/a>`
- page map: `<path>`
- page records directory: `<path>`
- article assemblies directory: `<path>`
- translation workspace: `<path or not yet created>`

## Tamil archival status

- physical page records: **<x> / <total>**
- article assemblies: **<x> / <total>**
- direct page verification: **<x> / <total>**
- strict visual word/punctuation pass: **<x> / <total>**
- unresolved `NEEDS-PIXEL-REVIEW`: **<count>**
- blocked body readings: **<count>**
- Tamil archival phase: **<ACTIVE / COMPLETE / FROZEN>**

## Article/page progress

| Unit | Source span | Status | Notes |
|---|---|---|---|
| `<article/page range>` | `<scan / printed pages>` | `<status>` | `<important note>` |

## Source-witness distinctions that must not regress

Record every meaningful distinction between independent source witnesses, for example:

- contents title vs article heading;
- article body vs back-cover/promotional excerpt;
- printed errata vs body witness;
- advertisement/excerpt vs article body;
- alternate spelling/punctuation in separate source locations.

Use concrete forms:

- contents witness: `<exact source form>`
- heading witness: `<exact source form>`
- rule: **preserve separately; never normalise one from the other**

## High-value source readings already verified

Record difficult readings that future sessions must not casually “fix”:

- `<scan/page>` — `<source-visible reading>`
- `<scan/page>` — `<source-visible reading>`

## Corrections made during review

Keep provenance:

- `<old reading>` → **`<source-visible corrected reading>`** — `<scan/page and reason>`

Do not hide corrections once made.

## English translation status

If translation has not begun:

- English translation: **NOT STARTED**
- prerequisite: complete/freeze Tamil source first

If active:

- translation plan: `<path>`
- drafts: **<x> / <total>**
- T2 fidelity-reviewed: **<x> / <total>**
- T3 voice-reviewed: **<x> / <total>**
- T4 audited: **<x> / <total>**
- T5 verified: **<x> / <total>**
- E6 publication consistency review: **<status>**
- E7 release closeout: **<status>**
- unresolved translation questions: **<count>**

## Permanent translation rule

> **Translate the language; do not neutralise the voice.**

Retain Kalaignar's commands, direct address, rhetorical questions, repetition, sarcasm, ridicule, polemical labels, exclamations, physical imagery and wordplay. Do not turn the prose into detached academic English.

## Publication-specific identity / terminology decisions

Do not import identity decisions mechanically from older publications.

Record only decisions established for the active publication:

- `<Tamil source label>` → **`<English form>`** — `<referent / reason / source>`
- `<term>` → **`<preferred English>`** — `<context>`
- source-label switches: `<...>`
- plural/singular distinctions: `<...>`

## Non-regression translation decisions

Record article-specific decisions that must remain stable during later review:

### Article / unit <n>
- title: `<Tamil>` → **`<English>`**
- source Tamil SHA: `<blob sha>`
- key terms: `<...>`
- wordplay: `<...>`
- quotation/source anomaly: `<...>`
- voice decision: `<...>`

## Current blockers / unresolved questions

- **None**

or list explicitly:

- `<issue>` — `<what evidence is needed>`

Never conceal an unresolved issue by marking a gate complete.

## Exact next activity

**<One concrete activity, with source span / article / gate and expected completion clearly stated.>**

Examples:

- `Strict-review scans 31–45 word by word, propagate any corrections into article assemblies and update the fidelity ledger.`
- `Translate Article 4 from the current strict-reviewed Tamil SHA, complete T1–T5, then update lexicon/review/tracker/handover.`
- `Run E6 across all English articles; do not mark English complete until the publication-wide consistency gate passes.`

## Rules for the next session

1. Fetch/read the current root handover first.
2. Fetch the active source records fresh from `main`.
3. Execute the exact next activity rather than restarting completed work.
4. Do not modify frozen source text without source-supported evidence.
5. Propagate corrections to dependent records.
6. Update this handover before ending the activity.

---

## Template maintenance rule

If the project workflow evolves in a reusable way, update:

1. `ESSAY_PROCESSING_GUIDE.md` or `ESSAY_TRANSLATION_GUIDE.md` first;
2. `docs/FUTURE_WORK_GUIDELINES.md` if the operational sequence changes;
3. this template so future publications inherit the improved workflow;
4. root `HANDOVER.md` with the concrete current project state.
