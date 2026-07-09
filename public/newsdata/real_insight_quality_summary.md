# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `B`
- Parents: `10`
- Average angles: `1.9`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.8`
- Base report share: `0.38095238095238093`
- Multi-angle parents: `9`
- Weak parents: `1`
- Story count: `661`
- Source groups: `10`
- Content hash: `68316ae1e8c59b09`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Tehran targets Bahrain, Kuwait after US strikes and limits Iran's oil sales over ship attacks | 2 | fact_update, base_report | NO | 0.6834967197849984 |
| 2 | New U.S. attacks on Iran were absolutely necessary, NATO chief says | 2 | market_reaction, official_response | NO | 0.6732467197849983 |
| 3 | US charges puts gangsters Lawrence Bishnoi and Goldy Brar at centre of transnational murder, stops short of accusing India | 3 | base_report, official_response | NO | 0.619081054304934 |
| 4 | 'Lust for murder': German doctor who killed 15 patients gets life term; suspected in 76 more deaths | 2 | base_report, fact_update | NO | 0.61211 |
| 5 | Trump | 2 | official_response, base_report | NO | 0.60191 |
| 6 | 2 girls attacked with weapon at Germany school, teenager arrested | 2 | official_response, investigative_detail | NO | 0.60111 |
| 7 | New Zealand announces 57% tariff-free exports to India ahead of Modi visit | 2 | official_response, base_report | NO | 0.5945899468816684 |
| 8 | India, Australia to expand partnership in critical minerals, clean energy - The Economic Times | 2 | base_report, fact_update | NO | 0.5732433333333333 |
| 9 | India, Australia unveil new defence declaration to deepen Indo-Pacific cooperation | 2 | official_response, base_report | NO | 0.5485933333333333 |
| 10 | Nuvama, Cushman & Wakefield-backed realty fund raises Rs 4,000 cr | 2 | fact_update | YES | 0.7666133864516651 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `B`
- Score: `76`
- Parents: `10`
- Average angles: `1.9`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.8`
- Base report share: `0.381`
- Multi-angle parents: `9`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `B` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.9` / `>= 1.4`
- Average evolution role count: `1.8` / `>= 1.6`
- Base report share: `0.381` / `<= 0.55`
- Multi-angle parent count: `9` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.1` / `<= 0.5`
