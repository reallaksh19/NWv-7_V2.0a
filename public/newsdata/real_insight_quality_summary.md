# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.7`
- Average evolution roles: `2`
- Base report share: `0.3333333333333333`
- Multi-angle parents: `8`
- Weak parents: `2`
- Story count: `670`
- Source groups: `9`
- Content hash: `5e72df5b08b3e179`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Tehran targets Bahrain, Kuwait after US strikes and limits Iran's oil sales over ship attacks | 2 | fact_update, base_report | NO | 0.6834967197849984 |
| 2 | New Zealand announces 57% tariff-free exports to India ahead of Modi visit | 2 | official_response, base_report | NO | 0.6265766666666668 |
| 3 | 'Lust for murder': German doctor who killed 15 patients gets life term; suspected in 76 more deaths | 2 | base_report, fact_update | NO | 0.61211 |
| 4 | Trump | 2 | official_response, base_report | NO | 0.60191 |
| 5 | 2 girls attacked with weapon at Germany school, teenager arrested | 2 | official_response, investigative_detail | NO | 0.60111 |
| 6 | India and Australia Deepen Defence Ties: What It Means for the Indo-Pacific / Above the Fold / 09.07.2026 | 3 | official_response, base_report | NO | 0.5765916683316485 |
| 7 | India, Australia to expand partnership in critical minerals, clean energy - The Economic Times | 2 | base_report, fact_update | NO | 0.5732433333333333 |
| 8 | How undercover agents and informants helped the FBI unravel Lawrence Bishnoi’s gang / Explained | 2 | base_report, expert_analysis | NO | 0.5545933333333333 |
| 9 | India estimates 300 GW power demand next year, backs local clean-energy manufacturing | 2 | regional_followup | YES | 0.6952467197849983 |
| 10 | Trump says Iran ceasefire ‘over’ after fighting flares | 2 | official_response | YES | 0.6732467197849983 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.7`
- Average evolution roles: `2`
- Base report share: `0.333`
- Multi-angle parents: `8`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.8` / `>= 1.4`
- Average evolution role count: `2` / `>= 1.6`
- Base report share: `0.333` / `<= 0.55`
- Multi-angle parent count: `8` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.2` / `<= 0.5`
