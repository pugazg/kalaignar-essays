# NEXT CHAT PROMPT — ஆறுமாதக் கடுங்காவல் / P2R Batch R36 scans 191–205

Continue directly in `pugazg/kalaignar-essays`, branch `main`, active publication `publications/aaru-maatha-kadungkaaval/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Root `HANDOVER.md` and `publications/aaru-maatha-kadungkaaval/P2_REAUDIT_PROGRESS.md` are authoritative.

## Batch size

Per the user's latest instruction, process **15 physical scans in each iteration**.

## Controlling source

Primary source identity remains:
`TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்.pdf`

Use only:
`TVA_BOK_0064140_ஆறுமாதக்_கடுங்காவல்_part_001_pages_150-224.pdf`

Mapping: **extract page N = original physical scan N+149**.

Batch R36: extract pages **42–56** = original scans **191–205**.

No OCR, web copies, Wikisource, TVA web text, alternate editions, or contextual completion.

## Durable state after Batch R35

- P2 canonical coverage — **224/224**
- P2 — **222 verified / 2 needs-review** (source-obscured holds scans 18 and 198)
- P2R — **190/224 complete**
- re-audited scans — **1–190**
- historical-glyph correction-event count — **20**
- guessed readings — **0**

Batch R35:
- scans 176–178 — PASS / no canonical correction
- scan 179 — `பஞ்சண மீது` → **`பஞ்சணை மீது`**; historical `ணை` restored
- scans 180–188 — PASS / no canonical correction
- scan 189 — `இருக்கவேண்டு மென்பதற்காக` → **`இருக்கவேண்டுமென்பதற்காக`**; physical line wrap `இருக்கவேண்டு` + `மென்பதற்காக` rejoined lexically
- scan 190 — PASS; terminal `பாராட்டியிருக்க` preserved; scan 191 / extract page 42 was not opened
- ordinary source-fidelity corrections — **1**
- new historical-family correction events — **1**

## Mandatory line-wrap rule

A physical line break is **not** evidence of a lexical space or word boundary. Rejoin split lexical words from direct glyph continuity.

## Exact next activity

Process exactly original physical scans **191–205** using derivative extract pages **42–56**.

For every scan:
1. compare every printed word, numeral, punctuation mark, meaningful spacing and page-boundary fragment with the canonical record;
2. separate physical-copy marks / show-through from publication ink;
3. explicitly verify `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
4. make only direct source-supported corrections;
5. do not infer a lexical space from a physical line wrap;
6. record PASS / correction details in the page record and `P2_REAUDIT_PROGRESS.md`;
7. synchronize controls and commit.

Stop after original scan **205** / extract page **56**. Do not process scan 206 / extract page 57.
