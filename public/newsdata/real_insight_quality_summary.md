# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.1`
- Average temporal tiers: `1.4`
- Average evolution roles: `1.2`
- Base report share: `0.07142857142857142`
- Multi-angle parents: `1`
- Weak parents: `9`
- Story count: `576`
- Source groups: `10`
- Content hash: `0480318b397378e0`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Hamas names Khalil al-Hayya as new overall leader | 2 | base_report, fact_update | NO | 0.6112599999999999 |
| 2 | Meghna Infracon Infrastructure expects Rs 300cr revenue from new commercial project | 2 | fact_update | YES | 0.760613386451665 |
| 3 | Rupee weakens to two-month low as oil climbs; state-run banks cushion | 2 | market_reaction | YES | 0.6742467197849984 |
| 4 | India's 'Cockroach' movement supporters clash with Delhi police - 朝日新聞 | 2 | official_response | YES | 0.6392300531183316 |
| 5 | UltraTech Cement shares gain 2% after Q1 results. Why Nuvama, other brokerages raised target? | 1 | market_reaction | YES | 0.7226911614783158 |
| 6 | Paytm shares gain 3% after Q1 results. What are Goldman Sachs, Citi and CLSA saying? | 1 | market_reaction | YES | 0.7226911614783158 |
| 7 | India's private banks draw thinner margins on tepid credit growth | 1 | market_reaction | YES | 0.7226911614783158 |
| 8 | UltraTech Cement net up 17% on strong realisation, India Cements turnaround | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Indian banks mobilise $20.7 billion under RBI's special incentive window | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Som Distilleries shares jump 14% as ace investor Prashant Jain buys 25 lakh shares in Q1. What is he seeing? | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.1`
- Average temporal tiers: `1.4`
- Average evolution roles: `1.2`
- Base report share: `0.071`
- Multi-angle parents: `1`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.1`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.4`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.2`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.9`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.071` / `<= 0.55`
- Multi-angle parent count: `1` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
