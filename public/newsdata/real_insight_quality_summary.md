# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.4`
- Average evolution roles: `1.5`
- Base report share: `0.0625`
- Multi-angle parents: `4`
- Weak parents: `6`
- Story count: `586`
- Source groups: `10`
- Content hash: `545ccf300cda83d3`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | British military says cargo ship reports being under attack in Red Sea off coast of Yemen | 3 | official_response, fact_update | NO | 0.6425487346782661 |
| 2 | Iran's supreme leader absent as senior officials attend ayatollah's funeral | 2 | official_response, fact_update | NO | 0.6522467197849984 |
| 3 | After a century, forgotten Punjabi soldiers finally recognised for WWI sacrifice | 2 | base_report, fact_update | NO | 0.6052599999999999 |
| 4 | ‘Very dangerous’ Super Typhoon barrels towards US Pacific islands with 280 kmph winds | 2 | regional_followup, official_response | NO | 0.6225800531183316 |
| 5 | Six killed in Mumbai as rains wreak havoc, disrupt travel | 2 | fact_update | YES | 0.6172599999999999 |
| 6 | Prestige Estates buys 50% stake in Advent Convention and Hotels International for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 7 | EasyJet shares rally 10% on potential $7.3 billion acquisition by Castlelake | 1 | fact_update | YES | 0.7226911614783158 |
| 8 | Prestige Estates acquires 50% stake in Mumbai commercial project for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Senco Gold shares soar 6% as Q1 business update highlights 60% revenue growth | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Shakti Pumps shares surge 8% on Rs 354 crore solar pump order from MSEDCL | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `18`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.4`
- Average evolution roles: `1.5`
- Base report share: `0.063`
- Multi-angle parents: `4`
- Top parent angles: `2`
- Top parent children: `3`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.4`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.6`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.4` / `>= 1.4`
- Base report share: `0.063` / `<= 0.55`
- Multi-angle parent count: `4` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `3` / `>= 2`
