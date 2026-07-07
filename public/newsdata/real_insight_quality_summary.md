# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.2`
- Average evolution roles: `1.3`
- Base report share: `0.15384615384615385`
- Multi-angle parents: `2`
- Weak parents: `8`
- Story count: `561`
- Source groups: `10`
- Content hash: `604733c46aa70d0a`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | After a century, forgotten Punjabi soldiers finally recognised for WWI sacrifice | 2 | base_report, fact_update | NO | 0.6732467197849983 |
| 2 | Super Typhoon Bavi strikes US Pacific islands with pummeling winds | 2 | base_report, official_response | NO | 0.6292600000000002 |
| 3 | Six killed in Mumbai as rains wreak havoc, disrupt travel | 2 | fact_update | YES | 0.6172599999999999 |
| 4 | Prestige Estates buys 50% stake in Advent Convention and Hotels International for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 5 | EasyJet shares rally 10% on potential $7.3 billion acquisition by Castlelake | 1 | fact_update | YES | 0.7226911614783158 |
| 6 | Prestige Estates acquires 50% stake in Mumbai commercial project for Rs 504 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 7 | Senco Gold shares soar 6% as Q1 business update highlights 60% revenue growth | 1 | fact_update | YES | 0.7226911614783158 |
| 8 | Shakti Pumps shares surge 8% on Rs 354 crore solar pump order from MSEDCL | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Oberoi Realty records bookings of over ₹8,000 crore in its Gurugram luxury project | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | EasyJet shares reveal deal risk as $7.3 billion takeover advances | 1 | market_reaction | YES | 0.7096244948116492 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.2`
- Average evolution roles: `1.3`
- Base report share: `0.154`
- Multi-angle parents: `2`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.2`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.2`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.3`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.8`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.154` / `<= 0.55`
- Multi-angle parent count: `2` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
