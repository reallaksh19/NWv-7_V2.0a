# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.15`
- Multi-angle parents: `5`
- Weak parents: `5`
- Story count: `603`
- Source groups: `10`
- Content hash: `653ba90394888fce`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Tehran targets Bahrain, Kuwait after US strikes and limits Iran's oil sales over ship attacks | 2 | fact_update, base_report | NO | 0.6834967197849984 |
| 2 | New U.S. attacks on Iran were absolutely necessary, NATO chief says | 2 | market_reaction, official_response | NO | 0.6732467197849983 |
| 3 | 'Lust for murder': German doctor who killed 15 patients gets life term; suspected in 76 more deaths | 2 | base_report, fact_update | NO | 0.61211 |
| 4 | Trump | 2 | official_response, base_report | NO | 0.58191 |
| 5 | 2 girls attacked with weapon at Germany school, teenager arrested | 2 | official_response, investigative_detail | NO | 0.58111 |
| 6 | Nuvama, Cushman & Wakefield-backed realty fund raises Rs 4,000 cr | 2 | fact_update | YES | 0.7666133864516651 |
| 7 | Trump says Iran ceasefire ‘over’ after fighting flares | 2 | official_response | YES | 0.6732467197849983 |
| 8 | India estimates 300 GW power demand next year, backs local clean-energy manufacturing | 2 | regional_followup | YES | 0.5952732802150018 |
| 9 | India news LIVE updates, 8 July 2026: Baruipur rape-murder accused shot dead in encounter, Mumbai airport near-miss as two Air India flights face off on runway, US hits 80 Iranian targets after Hormuz attacks - The Indian Express | 2 | fact_update | YES | 0.6135800531183317 |
| 10 | Trump's Board of Peace planning pilot humanitarian zone in Gaza, official says | 2 | official_response | YES | 0.5395933333333333 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.15`
- Multi-angle parents: `5`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.5` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.15` / `<= 0.55`
- Multi-angle parent count: `5` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.5` / `<= 0.5`
