# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.6`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.22727272727272727`
- Multi-angle parents: `6`
- Weak parents: `4`
- Story count: `581`
- Source groups: `10`
- Content hash: `2477b243737c96c0`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Senator Lindsey Graham died of aortic tear, examiner says | 3 | base_report, official_response | NO | 0.6552273179616862 |
| 2 | Why US, EU and 13 nations are backing 2016 South China Sea ruling against Beijing's claims | 3 | fact_update, official_response | NO | 0.6732477209716007 |
| 3 | Toll up at 9 as last body recovered; official dubs incident 'act of God' - The Hindu | 2 | fact_update, official_response | NO | 0.6504967197849982 |
| 4 | Ex-MP H. Hanumanthappa passes away | 2 | base_report, official_response | NO | 0.6274820680115993 |
| 5 | India crush England to claim historic victory in the first women's Test at Lord's | 2 | base_report, regional_followup | NO | 0.5630933333333333 |
| 6 | Yastika century, seamers put India on the brink of historic win at Lord's | 2 | fact_update, base_report | NO | 0.5530933333333333 |
| 7 | Puravankara Q1 sales bookings up 28% to Rs 1,439 cr on higher volumes, price growth | 2 | fact_update | YES | 0.7286266666666668 |
| 8 | US strikes Iran after Strait of Hormuz ship attack; Tehran hits Gulf states | 2 | regional_followup | YES | 0.6814967197849984 |
| 9 | At least two killed in Toronto street festival shooting | 2 | fact_update | YES | 0.6292600000000002 |
| 10 | Supreme Court stays Madras HC order directing ban on cow slaughter in Tamil Nadu | 2 | official_response | YES | 0.59341 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.6`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.227`
- Multi-angle parents: `6`
- Top parent angles: `2`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.6` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.227` / `<= 0.55`
- Multi-angle parent count: `6` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0.4` / `<= 0.5`
