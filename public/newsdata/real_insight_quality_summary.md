# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.6`
- Base report share: `0.35294117647058826`
- Multi-angle parents: `2`
- Weak parents: `8`
- Story count: `562`
- Source groups: `10`
- Content hash: `7afdbdfa7f4a1de7`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | After a century, forgotten Punjabi soldiers finally recognised for WWI sacrifice | 2 | base_report, fact_update | NO | 0.6732467197849983 |
| 2 | Trump says there will either be a deal with Iran or U.S. will ‘finish the job’ | 2 | base_report, official_response | NO | 0.5385933333333333 |
| 3 | Russian strikes kill at least 26 in Kyiv region on eve of NATO summit | 3 | fact_update | YES | 0.6982906546249833 |
| 4 | China test fires missile into Pacific, sparks alarm | 2 | base_report | YES | 0.6694800531183316 |
| 5 | US accuses Iran of attacking 2 commercial ships; mulls action | 2 | base_report | YES | 0.6538300531183316 |
| 6 | Six killed in Mumbai as rains wreak havoc, disrupt travel | 2 | fact_update | YES | 0.6172599999999999 |
| 7 | RITES shares soar 9% after bagging a $36 million locomotive supply order from South Africa | 1 | fact_update | YES | 0.7226911614783158 |
| 8 | Prestige Estates buys 50% stake in Advent Convention and Hotels International for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | EasyJet shares rally 10% on potential $7.3 billion acquisition by Castlelake | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Prestige Estates acquires 50% stake in Mumbai commercial project for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `18`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.6`
- Base report share: `0.353`
- Multi-angle parents: `2`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.2`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Weak parent ratio** — actual `0.8`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average evolution role count: `1.6` / `>= 1.6`
- Base report share: `0.353` / `<= 0.55`
- Multi-angle parent count: `2` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
