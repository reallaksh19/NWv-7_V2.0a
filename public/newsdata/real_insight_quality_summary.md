# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.7`
- Base report share: `0.2777777777777778`
- Multi-angle parents: `2`
- Weak parents: `8`
- Story count: `666`
- Source groups: `9`
- Content hash: `7570af08ce9e5109`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Report | 2 | market_reaction, investigative_detail | NO | 0.6852467197849983 |
| 2 | Trump says there will either be a deal with Iran or U.S. will ‘finish the job’ | 2 | base_report, official_response | NO | 0.6265800531183316 |
| 3 | Russian strikes kill at least 26 in Kyiv region on eve of NATO summit | 3 | fact_update | YES | 0.6942477209716008 |
| 4 | PM Modi conferred with Indonesia's highest honour ‘Bintang Adipurna' in Jakarta | 2 | official_response | YES | 0.61351 |
| 5 | China test fires missile into Pacific, sparks alarm | 2 | base_report | YES | 0.6254800531183317 |
| 6 | US accuses Iran of attacking 2 commercial ships; mulls action | 2 | base_report | YES | 0.6098300531183317 |
| 7 | Woman suspected of Monaco bomb attack found dead in Ukraine | 2 | fact_update | YES | 0.58616 |
| 8 | FIFA World Cup drives prediction market to record high; sports volumes may hit $740 billion by 2030, says Binance Research | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Info Edge shares surge 11% after Q1FY27 billings rise 14% YoY | 1 | market_reaction | YES | 0.7226911614783158 |
| 10 | RITES shares soar 9% after bagging a $36 million locomotive supply order from South Africa | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `18`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.7`
- Base report share: `0.278`
- Multi-angle parents: `2`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.2`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.6`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Weak parent ratio** — actual `0.8`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.278` / `<= 0.55`
- Multi-angle parent count: `2` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
