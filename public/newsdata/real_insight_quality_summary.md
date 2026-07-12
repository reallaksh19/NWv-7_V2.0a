# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.7`
- Base report share: `0.2`
- Multi-angle parents: `4`
- Weak parents: `6`
- Story count: `504`
- Source groups: `10`
- Content hash: `e5adbde89346f325`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Trump administration subpoenas New York Times journalists over Air Force One reporting | 2 | base_report, investigative_detail | NO | 0.6601766666666666 |
| 2 | US Democrat Ro Khanna says he was detained by armed Israeli settlers | 3 | official_response, base_report | NO | 0.5995606512950195 |
| 3 | It's a mystery who launched latest strikes against Iran | 2 | fact_update, official_response | NO | 0.6243300531183317 |
| 4 | PM Modi tours New Zealand sports innovation showcase | 2 | fact_update, official_response | NO | 0.6002928264800007 |
| 5 | Boat carrying Indians capsizes in Vietnam; search under way | 3 | fact_update | YES | 0.5701583349983151 |
| 6 | No, I am in Dublin: PwC worker remotely works from India; lies when confronted, accuses boss of bullying | 2 | base_report | YES | 0.6075800531183317 |
| 7 | China evacuates over 1 million as Typhoon Bavi brings winds and rain | 2 | fact_update | YES | 0.5457266666666667 |
| 8 | At least two killed in Toronto street festival shooting | 2 | fact_update | YES | 0.5492732802150018 |
| 9 | SIF AUM jumps 29% to Rs 17,858 crore in June; inflows surge 171% MoM | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | DMart Q1 results: Cons PAT up 11% to Rs 860 crore, revenue rises to Rs 18,795 crore | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `42`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.7`
- Base report share: `0.2`
- Multi-angle parents: `4`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.6`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Weak parent ratio** — actual `0.6`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.4` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.2` / `<= 0.55`
- Multi-angle parent count: `4` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
