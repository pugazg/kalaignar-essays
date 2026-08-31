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
Final verified English blob: **`4246c9f1e206d5703fe50297657bb0af2a8e57e6`**

Gate record:

- T1 close draft: **PASS**
- T2 bilingual fidelity: **PASS** — **11** documented fidelity corrections
- T3 Kalaignar voice: **PASS** — **7** meaning-neutral voice/cadence corrections
- T4 terminology / quotation / citation / source audit: **PASS** — **0** body corrections
- T5 final article verification: **PASS** — **0** body corrections
- unresolved Article 1 blockers: **0**

Article 1 is individually verified, but publication-level E6/E7 release freezing waits until all ten articles pass T5.

## Article 2 — `புரட்சி வளர்ந்த கதை` — T1–T2 COMPLETE / FIDELITY-REVIEWED

Frozen Tamil authority: `dda81363f512ee2f829c367ae929ce3610604fe9`  
English file: `publications/unarchchimaalai/translations/en/02-puratchi-valarntha-kathai.md`  
English title: **The Story of How the Revolution Grew**  
T1 English draft blob: `c036f2439874dacf6220e7da529e852cf28e223a`  
T2 fidelity-reviewed blob: **`ec61502524a073a45292202da71d8979b5d254b2`**

### T1 results

- complete close draft from scans 10–15: **PASS**
- scan comments 10–15: **retained / ordered**
- scan 11→12 `இரஷ்ய வரலாறு...` continuation: **retained**
- scan 13→14 `ரஸ்புடீனை / சுட்டுக்கொன்றது` continuation: **retained**
- dates/numbers and source questions/exclamations/repetition: **retained**
- frozen Tamil changed: **No**
- outside/web historical reconstruction or published translation imported: **No**

### T2 — COMPLETE / PASS

Article 2 advanced to `translation_status: fidelity-reviewed` after a complete clause-by-clause comparison across scans 10–15.

T2 made **10 documented fidelity corrections**:

1. `no refuge` → `there was no way out` for frozen `கதியிலை`;
2. removed T1's added `That is the victory festival!` and restored the scan-10 accumulation to end directly `—a victory festival!`;
3. `Tsar Nicholas` → **King Nicholas** for `நிக்கோலாஸ் மன்னன்`;
4. restored `புன் சிரிப்பு` as **faint smile**;
5. `struck Prince Sergius dead` → **beat Prince Sergius to death**;
6. scan-12 `Society spat...` → **The people spat...** for `ஜனசமுதாயம்`;
7. `price of knowledge` → **price of intelligence** for `அறிவு`;
8. `another killing` → **another murder** for `கொலை`;
9. removed T1's added imperative `Remember` from the scan 13→14 lion-cub/Rasputin continuation;
10. `ceremony of Tsar's abdication` → **Tsar-king's abdication ceremony** for `ஜார் அரசனின் முடிதுறப்பு வைபவம்`.

### Article 2 T2 terminology/source decisions

- title **The Story of How the Revolution Grew**: confirmed;
- `பாட்டாளி மக்கள்` → **proletarian people**: retained;
- quoted `பவிசு` → **pomp**: retained source-sensitively;
- `மதவாதி` → **religionist** / capitalist–religionist class: retained;
- frozen `இலெனின்` / `லெனின்` → one conventional **Lenin**, source variation documented;
- frozen `பீட்ரோகிராட்` / `பீட்ரோ கிரோடு` → one conventional **Petrograd**, source variation documented;
- `Mangaiyarkkarasi`, `Kulachchirai`, `kidukidu`, `Romanal`, `Chiranjeevi`, `God-ism`, `Dravidam`, `Self-Respect`: explicitly reviewed and retained without outside reconstruction;
- frozen scan-11 `மௌனமாகவே` remains controlling despite the P5 scan-appearing alternate;
- scan comments 10–15 and both cross-scan continuations: **PASS**;
- frozen Tamil changed: **No**;
- outside/web historical wording or published English translation imported: **No**;
- unresolved T2 blockers: **0**.

Detailed T1/T2 provenance: `publications/unarchchimaalai/translations/en/TRANSLATION_REVIEW.md`.

## English progress

- T0 setup: **PASS**
- T1 drafts: **2 / 10**
- T2 fidelity-reviewed: **2 / 10**
- T3 voice-reviewed: **1 / 10**
- T4 audited: **1 / 10**
- T5 verified: **1 / 10**
- E6: **NOT STARTED**
- E7: **NOT STARTED**
- unresolved translation blockers: **0**

---

# Exact next activity

Execute **Article 2 T3 — Kalaignar voice review** for `புரட்சி வளர்ந்த கதை` / **The Story of How the Revolution Grew** against frozen Tamil blob:

`dda81363f512ee2f829c367ae929ce3610604fe9`

T3 must:

1. preserve every T2 meaning/source decision and all source-sensitive treatments;
2. review the English as English against the frozen Tamil for directness, repetition, rhetorical questions, exclamations, violent imagery, ridicule, accumulative dashes, `No...` reversals and class-political force;
3. preserve `proletarian people`, `pomp`, `religionist`, `King Nicholas`, `Mangaiyarkkarasi`, `Kulachchirai`, `kidukidu`, `Romanal`, `Chiranjeevi`, `God-ism`, `Dravidam`, `Self-Respect`, and the T2 Lenin/Petrograd provenance unless a meaning-neutral cadence adjustment is needed around them;
4. retain scan comments 10–15 and the scan 11→12 / scan 13→14 continuations;
5. make only meaning-neutral voice/cadence corrections, not new fidelity reinterpretations;
6. advance to `translation_status: voice-reviewed` only if T3 passes;
7. update tracker, lexicon, review ledger, plan and this handover;
8. **stop before Article 2 T4 terminology / quotation / source audit**.

## Current blockers

**None.**