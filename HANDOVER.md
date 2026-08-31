# Kalaignar Essays / Articles — Project Handover

Repository: `pugazg/kalaignar-essays`  
Branch: `main`

**This is the single authoritative project handover. Update it after every meaningful source, translation, review or release activity.**

## Mandatory startup

Read completely before changing anything:

1. `ESSAY_PROCESSING_GUIDE.md`
2. `ESSAY_TRANSLATION_GUIDE.md`
3. `docs/FUTURE_WORK_GUIDELINES.md`
4. this `HANDOVER.md`
5. active publication README / metadata / fidelity / completion records
6. when translation is active: `TRANSLATION_PLAN.md`, English tracker, lexicon and review ledger

Source PDFs are never committed. English translation follows the permanent rule: **Translate the language; do not neutralise the voice.**

---

# Publication 1 — சக்கரவர்த்தியின் திருமகன் — RELEASE COMPLETE / FROZEN

- strict Tamil fidelity: **83 / 83 PASS**
- Tamil assemblies: **14 / 14 complete**
- English T0–T5: **14 / 14 complete**
- E6: **PASS**
- E7: **PASS / RELEASE COMPLETE**
- unresolved blockers: **0**

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is found.

---

# Publication 2 — கயிற்றில் தொங்கிய கணபதி — RELEASE COMPLETE / FROZEN

- Tamil page records: **17 / 17 verified**
- P5 strict visual fidelity: **17 / 17 PASS**
- Tamil source: **COMPLETE / FROZEN**
- frozen Tamil authority: `b7c6d02cd7bc041318693306b8658e18c3f8fa5b`
- verified English article blob: `bf01a5d6da90e8caf6c491ed43f46cbb5e9491ba`
- English release: **COMPLETE**
- unresolved blockers: **0**

Do not reopen for stylistic polishing unless a genuine source-supported or release-blocking defect is found.

---

# Publication 3 — உணர்ச்சிமாலை — TAMIL FROZEN / ENGLISH ACTIVE

Workspace: `publications/unarchchimaalai/`

## Publication-specific lexical rule

For this publication only, the user established that Gemini word tokens are the Tamil lexical baseline wherever supplied. Scan/Gemini disagreements are documented rather than silently substituted. English translates the **frozen Tamil assemblies**, not an alternate scan reading.

## Tamil archival state — COMPLETE / FROZEN

- physical scans: **50**
- P2 page records: **50 / 50 verified**
- P3 assemblies: **10 / 10**
- P4: **PASS**
- P5 strict visual fidelity: **50 / 50 PASS**
- article strict recheck: **10 / 10 PASS**
- P5 structural/punctuation/spacing/layout corrections: **236 propagated**
- documented Gemini/source lexical conflicts retained: **18**
- unresolved Tamil blockers: **0**

Durable non-regression includes scan-19 source recovery, frozen scan-32 word/order sequence, corrected scan-33/34 boundary, Article 7 ending on scan 41, recovered scan-42 `பதில் இல்லை.`, scan-43 `* * *`, frozen scan-48 `ப்ழச்சளை`, frozen scan-49 `விட்டாய்.` placement, scan-49 publication-close matter outside Article 10, and scan-50 advertisement outside all articles.

## Frozen Tamil translation authorities

1. `c63837a9f7c02d6f3a18171a512d46788f66ad92`
2. `dda81363f512ee2f829c367ae929ce3610604fe9`
3. `92eb1a68d65f65dd71274e5e79f3209e63359d9a`
4. `006f2f75dbc3eea796170a29aee0befd162522e7`
5. `c8ac4d7c241832e07bbb24c5cee935588673f4ac`
6. `f3634a63bff94f5647dbbdfa7dfe9b1b0a2479d8`
7. `bac121257d24477bc3c7e8c65f4b3f7b8a419bad`
8. `2e57a4c7c53ae4354942b5e64c5a2c4a33f3be2f`
9. `4dd0bbc03f278c9bfc02b189b285a1891aa44d2d`
10. `f856664d86695237a23d0ffc0bef088d32a82fe9`

Any later Tamil correction reopens affected English gates.

## English setup — T0 COMPLETE / PASS

Active files:

- `publications/unarchchimaalai/TRANSLATION_PLAN.md`
- `publications/unarchchimaalai/translations/en/README.md`
- `publications/unarchchimaalai/translations/en/LEXICON.md`
- `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`

## Article 1 — `உணர்ச்சி மாலை` — T0–T5 COMPLETE / VERIFIED

Frozen Tamil authority: `c63837a9f7c02d6f3a18171a512d46788f66ad92`  
English file: `publications/unarchchimaalai/translations/en/01-unarchchi-maalai.md`  
English title: **Garland of Emotion**  
Final verified English blob: `4246c9f1e206d5703fe50297657bb0af2a8e57e6`

- T1: **PASS**
- T2: **PASS** — 11 fidelity corrections
- T3: **PASS** — 7 meaning-neutral voice/cadence corrections
- T4: **PASS** — 0 body corrections
- T5: **PASS** — 0 body corrections
- unresolved Article 1 blockers: **0**

Article 1 is individually verified, but publication-level E6/E7 release freezing waits until all ten articles pass T5.

## Article 2 — `புரட்சி வளர்ந்த கதை` — T1–T4 COMPLETE / T4-AUDITED

Frozen Tamil authority: `dda81363f512ee2f829c367ae929ce3610604fe9`  
English file: `publications/unarchchimaalai/translations/en/02-puratchi-valarntha-kathai.md`  
English title: **The Story of How the Revolution Grew**  
T1 draft blob: `c036f2439874dacf6220e7da529e852cf28e223a`  
T2 fidelity-reviewed blob: `ec61502524a073a45292202da71d8979b5d254b2`  
T3 voice-reviewed / T4-audited blob: **`cff1840ab297a00b933390ee41207afd9709e9b8`**

### T2 — COMPLETE / PASS

T2 made **10 documented fidelity corrections** and confirmed the Article 2 terminology/source-sensitive set, including `proletarian people`, `pomp`, `religionist`, `King Nicholas`, one English `Lenin` / `Petrograd` across frozen Tamil source-form variants, and retained `Mangaiyarkkarasi`, `Kulachchirai`, `kidukidu`, `Romanal`, `Chiranjeevi`, `God-ism`, `Dravidam`, `Self-Respect` without outside historical reconstruction.

### T3 — COMPLETE / PASS

T3 made **10 meaning-neutral voice/cadence corrections** while preserving every T2 meaning/source decision. It strengthened the opening capitalist-class strangling image, the parallel jubilant-festival / throttled-lords sentence, Lenin's corpse-enthronement / warrior-dance image, the police `stood on their heads` idiom, the personified gallows / faint-smile action, the Rasputin/scorpion cadence, `The Tsar himself set out!`, the emergency-session directness, Lenin's rallying of workers' strength, and the final `No...` reversal.

### T4 — COMPLETE / PASS

T4 audited the unchanged T3 candidate against the frozen Tamil article, page records for scans 10–15, the living lexicon and translation guide.

- terminology / proper names: **PASS**
- source-sensitive transliterations: **PASS**
- quotation/source-bearing boundaries: **PASS**
- dates / numbers: **PASS**
- scan comments 10–15: **PASS / ordered**
- scan 11→12 continuation: **PASS**
- scan 13→14 `ரஸ்புடீனை / சுட்டுக்கொன்றது` continuation: **PASS**
- frozen scan-11 `மௌனமாகவே` authority: **unchanged**
- frozen Tamil changed: **No**
- outside/web historical reconstruction, translator citation or published English wording imported: **No**
- T4 body corrections: **0**
- unresolved T4 blockers: **0**

Article 2 therefore remains `translation_status: voice-reviewed` until T5. Its T4-audited English blob is unchanged at `cff1840ab297a00b933390ee41207afd9709e9b8`.

### Article 2 T4 non-regression

- title **The Story of How the Revolution Grew**: PASS
- `May Day`, `proletarian people`, `capitalist class`: PASS
- `King Nicholas`, `Prince Sergius`, `Tsar`, `Duma`, `Lenin`, `Petrograd`, `Rasputin`, `Tannenberg`, `Kerensky`: PASS
- `Bolshevik Party`, `Bolshevik forces`, `Soviet government`, `Provisional Government`: PASS
- `pomp`, `religionist`, `Mangaiyarkkarasi`, `Kulachchirai`, `kidukidu`, `Romanal`, `Chiranjeevi`, `God-ism`, `Dravidam`, `Self-Respect`: PASS / retained
- quoted gallows speech, `Duma`, `kidukidu`, `Shoot them down!`, `Tsar-king's abdication ceremony`, `Pyre! Pyre!`: PASS
- dates 1905, 1906, 1907, 1912, 1914, 1915, 1916, March 8 1917 and November 7 1917: PASS
- five-year Duma reference and both eight-month references: PASS

## English progress

- T0 setup: **PASS**
- T1 drafts: **2 / 10**
- T2 fidelity-reviewed: **2 / 10**
- T3 voice-reviewed: **2 / 10**
- T4 audited: **2 / 10**
- T5 verified: **1 / 10**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- unresolved translation blockers: **0**

---

# Exact next activity

Execute **Article 2 T5 — final article verification** for `புரட்சி வளர்ந்த கதை` / **The Story of How the Revolution Grew** against:

- frozen Tamil blob: `dda81363f512ee2f829c367ae929ce3610604fe9`
- T4-audited English blob: `cff1840ab297a00b933390ee41207afd9709e9b8`
- source scans: **10–15**

T5 must:

1. reconfirm the complete T1–T4 chain and that all recorded corrections/audits are reflected in the current English candidate;
2. verify metadata, title, source Tamil SHA and source scan/printed-page fields;
3. reconfirm scan comments 10–15 and the scan 11→12 / scan 13→14 continuations;
4. reconfirm terminology, quotation/source-bearing forms, dates/numbers and T3 voice non-regression;
5. confirm there are no unresolved fidelity, voice, terminology, quotation, citation or source blockers;
6. mark Article 2 `translation_status: verified` only if the complete chain passes;
7. record the final verified English blob SHA and synchronize tracker, lexicon, review ledger, plan and this handover;
8. **do not begin Article 3 in the same activity**.

## Current blockers

**None.**