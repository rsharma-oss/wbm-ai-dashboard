# WBM — AI visibility data pull · 2026-07-17

Fresh pull from the AI visibility tracking API, window **2026-06-17 → 2026-07-17 (30d)** unless noted.
Note: these are the tracking platform’s **visibility scores** (0–100, share-of-answer weighted). The July proposal cites *coverage %* and *avg score among mentions* — different metrics, do not swap 1:1 without recomputing.

## Headline visibility (30d)

| Brand line | Score | Runs | Trend |
|---|---|---|---|
| WBM Technologies (All Services) | **1** | 1,215 | stable |
| WBM: Managed Print | **6** | 1,824 | stable |
| WBM: Managed IT | **0** | 1,207 | stable |

## Model breakdown (30d)

**All Services:** ChatGPT 1 · Gemini 1 · Perplexity 0 · Google AIO 2 · Google AI Mode 0
**Managed Print:** ChatGPT 3 (avg pos 3.0) · Gemini 5 (3.9) · Perplexity 0 · Google AIO 9 (2.4) · Google AI Mode 8 (2.2)
**Managed IT:** 0 across all five models (ChatGPT/Gemini/AIO/AI Mode 280 runs each, Perplexity 87) — still zero mentions anywhere.

## Managed Print — per-prompt (30d, 15 prompts)

| Score | Prompt |
|---|---|
| 26 | What should I look for when choosing a managed print service…most frequently recommended? |
| 23 | How to choose the right managed print provider? |
| 8 | Customer experiences with managed print services… |
| 6 | Customer reviews of Western Canada IT solution providers in 2025? |
| 4 | How do managed print solutions compare (satisfaction/quality)? |
| 3 | Industry experts on effectiveness of managed print services |
| 3 | Best managed print solution for small businesses |
| 3 | Managed print workflow in large organizations |
| 2 | Top-rated managed print services + customer reviews |
| 2 | Reduce printing costs in 2025 |
| 1–2 | Remaining 5 prompts (enterprise comparison, cost reduction, efficiency, top solutions, traditional vs managed) |

## All Services — per-prompt (30d, 10 prompts)

Only one non-zero: **"How do businesses in Western Canada ensure their data is secure?" = 8**. The other 9 (IT cost reduction, end-user computing, managed IT vs in-house, outsourcing benefits, IT security best practices, infra challenges, enterprise support features, service desks, print trends) = **0**.

## Managed IT — per-prompt (30d, 10 prompts)

**All 10 prompts = 0.** (End-user support, data protection, downtime, SMB security, IT outsourcing agility, outsourcing benefits ×2, cyber threats, choosing an MSP, data security importance.)

## Competitors (latest)

**Managed Print:** Xerox 29 · Ricoh 28 · Canon 23 · Kyocera 15 · Konica Minolta 10 · Innov8 8 · Golds 0 · Segue 0
**All Services:** Xerox 6 · Insight 1 · Powerland 0 · Amtra 0 · Compugen 0 · Sysgen 0 · Long View 0 · CDW Canada 0
**Managed IT:** F12.net 2 · everyone else 0 (Powerland, Telus Fully Managed, Sysgen, Long View, Microserve, Nucleus, Anchor)

## Top citing sources — All Services (30d, top 10 of 2,409 domains, 14,568 citations)

linkedin.com (540 cites, influence 84) · youtube.com (330, 72) · reddit.com (120, 53) · cisa.gov (53, 51) · ibm.com (130, 51) · cyber.gc.ca (286, 50) · microsoft.com (70, 50) · canon.ca (115, 47) · salesforce.com (146, 46) · vc3.com (67, 46). All WIN status, zero competitor-only gaps flagged.

## 90d timeseries — All Services

Bounces between 0 and ~5 all quarter (peaks: 9 on Jun 8, 8 on Apr 20); no sustained lift. Last 7 days: 0,0,0,2,0,0,2,1.

## Deltas vs the shipped proposal's July narrative

- "Managed IT: 0 coverage across tracked ICP queries" — **still true**, now 10 prompts × all models = 0.
- "Print is compounding (+7 pts MoM)" — the *visibility score* for Print sits at 6/100 flat trend; re-verify the +7 MoM coverage claim against the coverage metric before reusing it.
- "Sysgen leads regional MSP at score 1" — now **F12.net leads at 2**; Sysgen is at 0. Xerox/Ricoh still top Print but Ricoh 28 vs Xerox 29 is nearly tied (proposal said both trending down).
