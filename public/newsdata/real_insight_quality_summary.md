# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.8`
- Base report share: `0.10526315789473684`
- Multi-angle parents: `5`
- Weak parents: `5`
- Story count: `756`
- Source groups: `10`
- Content hash: `0869fbd10f261a2f`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | ‘Boat flipped in three minutes,’ recounts Vietnam crash survivor upon arrival in Chennai | 2 | official_response, regional_followup | NO | 0.6943967197849983 |
| 2 | TVS Emerald inks Joint Development Agreement for four-acre land parcel in Noombal | 2 | base_report, fact_update | NO | 0.693213386451665 |
| 3 | Hyderabad native dies in U.S. skydiving accident | 2 | market_reaction, official_response | NO | 0.6705800531183317 |
| 4 | E Jean Carroll receives $5.6 million in sexual abuse case after years-long legal battle with Trump | 2 | fact_update, official_response | NO | 0.6243266666666667 |
| 5 | India beat England in historic first women's test at Lord's - Reuters | 2 | regional_followup, base_report | NO | 0.5563433333333333 |
| 6 | Puravankara Q1 sales bookings up 28% to Rs 1,439 cr on higher volumes, price growth | 2 | fact_update | YES | 0.7566133864516651 |
| 7 | Amended RPwD Act to include persons internally injured by acid ingestion, Centre tells Supreme Court | 2 | correction | YES | 0.60551 |
| 8 | MEA summons Iranian deputy envoy, after Indian national killed in attack on ship | 3 | fact_update | YES | 0.5805916683316485 |
| 9 | Anand Rathi Share Q1 results: Profit rises 71% to Rs 39 crore before one-time charge | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Equirus, Money Grow Asset, Amaltas, 7 others deliver up to 14% returns in June | 1 | regional_followup | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `52`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.8`
- Base report share: `0.105`
- Multi-angle parents: `5`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.5` / `>= 1.4`
- Average evolution role count: `1.8` / `>= 1.6`
- Base report share: `0.105` / `<= 0.55`
- Multi-angle parent count: `5` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.5` / `<= 0.5`
