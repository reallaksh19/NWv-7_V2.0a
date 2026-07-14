# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.6`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.3684210526315789`
- Multi-angle parents: `6`
- Weak parents: `4`
- Story count: `581`
- Source groups: `10`
- Content hash: `0ff50ab0a6bb50c2`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Gold drops more than 1% as rising Middle East tensions add to rate-hike fears | 2 | base_report, market_reaction | NO | 0.714313386451665 |
| 2 | 12 districts in A.P. get new DMHOs | 2 | base_report, fact_update | NO | 0.6807467197849983 |
| 3 | Senator Lindsey Graham died of aortic tear, examiner says | 2 | base_report, official_response | NO | 0.6792467197849983 |
| 4 | It’s not over: fresh attacks and a crumbling ceasefire | 2 | base_report, official_response | NO | 0.60076 |
| 5 | Yastika century, seamers put India on the brink of historic win at Lord's | 2 | fact_update, base_report | NO | 0.5530933333333333 |
| 6 | Bodies of 15 Indian tourists killed in Vietnam boat accident flown home | 2 | fact_update, regional_followup | NO | 0.557226159813334 |
| 7 | Puravankara Q1 sales bookings up 28% to Rs 1,439 cr on higher volumes, price growth | 2 | fact_update | YES | 0.7566133864516651 |
| 8 | Supreme Court stays Madras High Court order banning cow slaughter in Tamil Nadu | 2 | official_response | YES | 0.58541 |
| 9 | BBL returns to Christmas Eve, Australia Day final | 2 | base_report | YES | 0.5630933333333333 |
| 10 | ICICI Prudential AMC shares gain 2% after Q1 net profit rises 23% to Rs 965 crore. Here’s what brokerages say | 1 | fact_update | YES | 0.7226911614783158 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.6`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.368`
- Multi-angle parents: `6`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.6` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.368` / `<= 0.55`
- Multi-angle parent count: `6` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.4` / `<= 0.5`
