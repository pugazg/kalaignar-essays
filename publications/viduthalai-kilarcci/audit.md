# Audit — விடுதலைக் கிளர்ச்சி

## Source intake

- source identity — **PASS**
- physical scans — **69/69**
- bytes — **101,127,153**
- SHA-256 — **`444ff76695154b5ee9d53f4647873fde72659a3d52a76aa833fdc502fb518809`**
- PDF version — **1.4**
- source pixels — **controlling authority**
- usable parsed text layer — **none**
- source PDF committed — **No**

## Classification / structure

**ESSAYS / ARTICLES — PASS**

- scans 1–3 — cover / reverse / imprint
- scans 4–7 — `வேங்கையை விரட்டும் படலம்`
- scans 8–68 — `விடுதலைக் கிளர்ச்சி`
- scan 69 — publisher catalogue
- body boundary checks — **PASS**

## Tamil archival gates

| Gate | State | Authority |
|---|---|---|
| P0 | COMPLETE / PASS | publication controls |
| P1 | COMPLETE / PASS — 69/69 | publication README / structure controls |
| P2 | COMPLETE / PASS — 69/69 VERIFIED | `P2_PROGRESS.md` |
| P3 | COMPLETE / PASS — 2/2 | `P3_PROGRESS.md` |
| P4 | COMPLETE / PASS | `P4_SOURCE_AUDIT.md` |
| P5 | COMPLETE / PASS — 69/69 STRICT-REVIEWED | `VISUAL_TEXT_FIDELITY_REVIEW.md` |

Tamil final state:

- canonical page records — **69/69 VERIFIED**
- article assemblies — **2/2 STRICT-REVIEWED / FROZEN**
- contributing article records — **65/65**
- unresolved fidelity discrepancies — **0**
- historical-glyph ambiguities — **0**
- guessed readings — **0**
- blockers — **0**

Frozen Tamil blobs:

1. `வேங்கையை விரட்டும் படலம்` — `c5be16582c2c3bb238cc1bf1ae47f8301173352f`
2. `விடுதலைக் கிளர்ச்சி` — `ec7b713d6516d75c1f36eb7e86f9ce5788d25036`

## English E0

**COMPLETE / PASS**

- translation identity — **project-created English translation**
- frozen Tamil pins — **2/2 PASS**
- translation order — **0 → 1**
- scans 1–3 and 69 excluded from English article bodies — **PASS**
- source comments expected — **65**
- Tamil changes during E0 — **0**
- blockers — **0**

## English Article 0 — T0–T5

**COMPLETE / PASS / VERIFIED**

- title — **The Chapter of Driving Away the Tiger**
- frozen Tamil blob — `c5be16582c2c3bb238cc1bf1ae47f8301173352f`
- T1 — `02b3f03c2f6b3c91d040064297645bbfb3659929`
- T2 — `535be98ee158f6b697591afd982aede24b46fc6e`
- T3 — `36aab78e955117f4fefe14759ca8dac46bac99a5`
- T4 — `7ee1a711aff55b99c1047f204cf837395f279077`
- T5 verified English — **`67c942bb8e1a631379834fe9757f5378085ccb58`**
- source comments — **4/4 PASS**
- unresolved choices — **0**

## English Article 1 — T0–T5

**COMPLETE / PASS / VERIFIED**

- title — **Liberation Uprising**
- frozen Tamil blob — `ec7b713d6516d75c1f36eb7e86f9ce5788d25036`
- T1 draft — **`f451f766b43eb83d525fec765c6d642a0018cfa2`**
- T2 body — **`9ac0bbebd5f11a5d881a96deb7695de252907a09`**
- T3 — **PASS / T2 retained**
- T4 — **PASS / T2 retained**
- T5 verified English — **`082954a6810dc88323aa1e4c0436523720754e55`**
- source comments — **61/61 PASS**
- translator/source notes — **2**
- omitted Tamil clauses after T2 — **0**
- added substantive English claims — **0**
- untranslated Tamil body leakage — **0** excluding metadata/comments
- Tamil source changes — **0**
- blockers — **0**

### Article-1 durable translation controls

- `எழுத்தாரமல்ல` → **garland of letters**;
- `விடுதலை விருத்தம்` → **liberation verse**;
- period hemisphere terminology retained in English;
- `முதல் கட்சி` → **foremost party**;
- `அனுமதியை` exposed through a translator note rather than silently normalized;
- `நெருக்கடி` → **Crisis** in the reviewed passage;
- `இரண்டாமிரம்` exposed through a translator note while repeated numerical sense remains **two thousand**;
- `வீணர்களின்` → **worthless fellows**;
- scan-68 `வேட்டு` cadence → **age of gunfire**;
- T3 / T4 introduced **0** further body changes.

## Publication English T0–T5 gate

- T0 — **2/2 PASS**
- T1 — **2/2 COMPLETE**
- T2 — **2/2 PASS**
- T3 — **2/2 PASS**
- T4 — **2/2 PASS**
- T5 — **2/2 VERIFIED**
- ordered source comments — **65/65 VERIFIED**
- unresolved translation choices — **0**
- Tamil drift — **0**
- blockers — **0**

## E6 publication-wide English consistency review

**COMPLETE / PASS**

Authority: `translations/en/E6_CONSISTENCY_REVIEW.md`.

- articles reviewed — **2/2**
- `Liberation Uprising / liberation uprising` treatment — **PASS**
- `Dravida / Dravida land / Dravidians / Dravida Nadu` treatment — **PASS**
- contextual adjectival **Dravidian movement / Dravidian society** — **PASS**
- movement / ideological vocabulary — **PASS**
- source epithets / literary / religious names — **PASS**
- **Indo China**, **Formosa**, **Kuomintang**, **Mao Tse-tung**, **Aung San** and other period/source forms — **PASS**
- title style / capitalization — **PASS**
- rhetorical punctuation / quotation style — **PASS**
- translator/source notes — **2/2 retained**
- source comments — **65/65 VERIFIED**
- frozen Tamil pins — **2/2 unchanged**
- English body corrections required — **0**
- post-E6 Article 0 English blob — **`67c942bb8e1a631379834fe9757f5378085ccb58`**
- post-E6 Article 1 English blob — **`082954a6810dc88323aa1e4c0436523720754e55`**
- unresolved consistency issues — **0**
- Tamil source changes during E6 — **0**
- blockers — **0**

## Next

**E7 English release closeout.**
