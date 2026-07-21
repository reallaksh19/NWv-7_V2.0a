# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.6`
- Base report share: `0.1111111111111111`
- Multi-angle parents: `3`
- Weak parents: `7`
- Story count: `756`
- Source groups: `10`
- Content hash: `c91aebb49a2fe6b0`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Rahul, Priyanka, Akhilesh detained during protest outside PM Modi’s residence | 3 | official_response, reaction_public | NO | 0.6673495401839085 |
| 2 | Hamas names Khalil al-Hayya as new overall leader | 2 | base_report, fact_update | NO | 0.6112599999999999 |
| 3 | US army veteran carrying 'ICE off our streets' sign sets fire outside NYC federal building | 2 | base_report, official_response | NO | 0.5852600000000001 |
| 4 | Meghna Infracon Infrastructure expects Rs 300cr revenue from new commercial project | 2 | fact_update | YES | 0.760613386451665 |
| 5 | London Stock Exchange to launch round-the-clock trading next year | 2 | market_reaction | YES | 0.721413386451665 |
| 6 | Four Indians killed, one injured in attack on ship leaving Ukraine’s Odessa; MEA condemns attack | 2 | fact_update | YES | 0.6403300531183316 |
| 7 | India’s youth-led 'cockroach movement' clashes with police in New Delhi - Reuters | 2 | official_response | YES | 0.5723433333333332 |
| 8 | IHCL Q1 Results: Profit rises 18% YoY to Rs 390 crore, total income up 15% | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Bandhan Bank Q1 profit jumps 35% as provisions decline sharply | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Adani Total Gas Q1 Results: Profit falls 14% YoY to Rs 142 crore, revenue jumps 27% | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `18`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.6`
- Base report share: `0.111`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `3`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Weak parent ratio** — actual `0.7`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average evolution role count: `1.6` / `>= 1.6`
- Base report share: `0.111` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `3` / `>= 2`
