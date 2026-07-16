# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.6`
- Base report share: `0.21052631578947367`
- Multi-angle parents: `4`
- Weak parents: `6`
- Story count: `733`
- Source groups: `10`
- Content hash: `7d7a2731981b41cf`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | NASA astronaut Anil Menon, two others reach International Space Station | 2 | base_report, fact_update | NO | 0.6994967197849983 |
| 2 | Revised US Russia sanctions bill lowers proposed tariffs on China, India | 2 | base_report, correction | NO | 0.6793933333333335 |
| 3 | Kota C-section victims demand kidney transplant in 48 hours, write to President | 2 | fact_update, reaction_public | NO | 0.6934967197849984 |
| 4 | Files relating to India’s largest nuclear power plant Kudankulam exposed in data breach - Reuters | 2 | official_response, investigative_detail | NO | 0.6392600000000002 |
| 5 | Swiggy Instamart and HPCL launch q-comm cylinder delivery | 2 | base_report | YES | 0.7012467197849983 |
| 6 | Indian missing after attack on ship off Oman coast is dead, family says - Reuters | 2 | fact_update | YES | 0.6950467197849983 |
| 7 | Cabinet Approves Mobile Phone Manufacturing Scheme With Rs. 62,500 Crore Budget to Scale Domestic Production | 2 | fact_update | YES | 0.6002266666666667 |
| 8 | Nepal court jails two former Ministers, 14 others | 2 | investigative_detail | YES | 0.6055800531183317 |
| 9 | Parliament approves Serhii Koretskyi amid cabinet shuffle | 2 | official_response | YES | 0.5075933333333333 |
| 10 | Issue 16% subscribed on day one so far, GMP suggests 12% listing pop | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `42`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.6`
- Base report share: `0.211`
- Multi-angle parents: `4`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Weak parent ratio** — actual `0.6`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.4` / `>= 1.4`
- Average evolution role count: `1.6` / `>= 1.6`
- Base report share: `0.211` / `<= 0.55`
- Multi-angle parent count: `4` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
