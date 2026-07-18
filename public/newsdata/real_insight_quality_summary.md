# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.9`
- Base report share: `0.047619047619047616`
- Multi-angle parents: `6`
- Weak parents: `4`
- Story count: `598`
- Source groups: `9`
- Content hash: `ac691992f02b8f74`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Vikram-1, country’s first private orbital-class rocket, successfully places tech payloads, postcards into orbit | 3 | market_reaction, investigative_detail, official_response | NO | 0.5989283316683515 |
| 2 | CJP founder Abhijit Dipke begins indefinite hunger strike after Wangchuk shifted to hospital | 3 | official_response, reaction_public | NO | 0.5987583349983152 |
| 3 | ISRO-SCTIMST sign pact for research in space medicine, Bioastronautics | 2 | official_response, base_report | NO | 0.60551 |
| 4 | US prosecutor says Justice Department made call to drop Gautam Adani case | 2 | expert_analysis, fact_update | NO | 0.6005899468816684 |
| 5 | Indian-origin woman jailed in UK for more than 2 years over Rs 2.8 crore Covid loan fraud | 2 | fact_update, investigative_detail | NO | 0.58631 |
| 6 | Vikram-1 Lifts Off Skyroot Launches India's First Private Rocket Into Orbit Successfully / News18 - News18 | 2 | investigative_detail, fact_update | NO | 0.5593433333333333 |
| 7 | A 7.3-magnitude earthquake hits Mexico-Guatemala border; no damage reported so far | 2 | official_response | YES | 0.6934967197849984 |
| 8 | Sonam Wangchuk’s wife breaks silence after Delhi Police shift him to hospital, warns authorities against brea - India.Com | 3 | official_response | YES | 0.6365487346782661 |
| 9 | Lohia Corp IPO opens on July 23: Here’s all you need to know | 1 | market_reaction | YES | 0.7226911614783158 |
| 10 | JK Cement Q1 profit drops 15.3% YoY to Rs 274.62 crore | 1 | fact_update | YES | 0.7226911614783158 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.9`
- Base report share: `0.048`
- Multi-angle parents: `6`
- Top parent angles: `3`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.7` / `>= 1.4`
- Average evolution role count: `1.9` / `>= 1.6`
- Base report share: `0.048` / `<= 0.55`
- Multi-angle parent count: `6` / `>= 1`
- Top parent angle count: `3` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0.4` / `<= 0.5`
