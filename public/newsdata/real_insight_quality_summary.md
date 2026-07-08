# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.5`
- Base report share: `0.25`
- Multi-angle parents: `2`
- Weak parents: `8`
- Story count: `606`
- Source groups: `9`
- Content hash: `128a9d41571456c3`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Trump says there will either be a deal with Iran or U.S. will ‘finish the job’ | 2 | base_report, official_response | NO | 0.6265800531183316 |
| 2 | India, Indonesia expand defence ties; New Delhi to supply BrahMos missiles | 3 | base_report, official_response | NO | 0.5517727761127958 |
| 3 | PM Modi conferred with Indonesia's highest honour ‘Bintang Adipurna' in Jakarta | 2 | official_response | YES | 0.61351 |
| 4 | Woman suspected of Monaco bomb attack found dead in Ukraine | 2 | fact_update | YES | 0.60616 |
| 5 | US accuses Iran of attacking 2 commercial ships; mulls action | 2 | base_report | YES | 0.6098300531183317 |
| 6 | FIFA World Cup drives prediction market to record high; sports volumes may hit $740 billion by 2030, says Binance Research | 1 | fact_update | YES | 0.7226911614783158 |
| 7 | Info Edge shares surge 11% after Q1FY27 billings rise 14% YoY | 1 | market_reaction | YES | 0.7226911614783158 |
| 8 | RITES shares soar 9% after bagging a $36 million locomotive supply order from South Africa | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Prestige Estates buys 50% stake in Advent Convention and Hotels International for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Cult.fit IPO: Fitness company files draft IPO papers to raise Rs 950 crore via fresh issue | 1 | market_reaction | YES | 0.7105244948116493 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.5`
- Base report share: `0.25`
- Multi-angle parents: `2`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.2`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.8`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.25` / `<= 0.55`
- Multi-angle parent count: `2` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
