# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.3`
- Average evolution roles: `1.5`
- Base report share: `0.25`
- Multi-angle parents: `3`
- Weak parents: `7`
- Story count: `438`
- Source groups: `10`
- Content hash: `1dcef2cf5c14cf3f`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Iran's supreme leader absent as senior officials attend ayatollah's funeral | 2 | official_response, fact_update | NO | 0.6522467197849984 |
| 2 | British military says cargo ship reports being under attack in Red Sea off coast of Yemen | 3 | official_response, fact_update | NO | 0.5745916683316485 |
| 3 | ‘Very dangerous’ Super Typhoon barrels towards US Pacific islands with 280 kmph winds | 2 | regional_followup, official_response | NO | 0.5665933333333333 |
| 4 | 'We are heroic people with heroic spirit': Donald Trump marks America's 250th Independence Day | 2 | base_report | YES | 0.6165800531183316 |
| 5 | Performer calls for Trump's death at funeral for Iran's late supreme leader | 2 | base_report | YES | 0.5956600000000001 |
| 6 | Senco Gold shares soar 6% as Q1 business update highlights 60% revenue growth | 1 | fact_update | YES | 0.7226911614783158 |
| 7 | Shakti Pumps shares surge 8% on Rs 354 crore solar pump order from MSEDCL | 1 | fact_update | YES | 0.7226911614783158 |
| 8 | Vedanta, TCS among 5 stocks with the highest dividend yield. Check details | 1 | market_reaction | YES | 0.7226911614783158 |
| 9 | South Korea's SK Hynix slides over 5% ahead of $29 billion Wall Street debut | 1 | fact_update | YES | 0.7096244948116492 |
| 10 | Foxconn Q2 revenue jumps nearly 40% on AI demand, beats estimates | 1 | market_reaction | YES | 0.7096244948116492 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.3`
- Average evolution roles: `1.5`
- Base report share: `0.25`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.3`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.7`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.25` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
