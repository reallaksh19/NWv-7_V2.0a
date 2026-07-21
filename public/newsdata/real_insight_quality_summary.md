# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.1`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.3`
- Base report share: `0.06666666666666667`
- Multi-angle parents: `1`
- Weak parents: `9`
- Story count: `587`
- Source groups: `9`
- Content hash: `eabfb6c765210864`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Hamas names Khalil al-Hayya as new overall leader | 2 | base_report, fact_update | NO | 0.6112599999999999 |
| 2 | Meghna Infracon Infrastructure expects Rs 300cr revenue from new commercial project | 2 | fact_update | YES | 0.760613386451665 |
| 3 | Rupee weakens to two-month low as oil climbs; state-run banks cushion | 2 | market_reaction | YES | 0.6742467197849984 |
| 4 | India's 'Cockroach' movement supporters clash with Delhi police - 朝日新聞 | 2 | official_response | YES | 0.5712433333333332 |
| 5 | Four Indians killed, one injured in attack on ship leaving Ukraine’s Odessa; MEA condemns attack | 2 | fact_update | YES | 0.5163566135483351 |
| 6 | Bajaj Auto Q1 Results: Cons PAT surges 46% YoY to Rs 3,226 crore; revenue zooms 65% | 1 | fact_update | YES | 0.7226911614783158 |
| 7 | Coal India subsidiary CMPDI shares climb 7% after Q1FY27 profit surges 54% YoY | 1 | market_reaction | YES | 0.7226911614783158 |
| 8 | Mrs Bectors Food shares surge 30% in 4 days after Sunil Singhania's Abakkus acquires 1% stake. Do you own? | 1 | market_reaction | YES | 0.7226911614783158 |
| 9 | MTAR Technologies falls 5%, extends 4-day slide to 20% | 1 | market_reaction | YES | 0.7226911614783158 |
| 10 | UltraTech Cement shares gain 2% after Q1 results. Why Nuvama, other brokerages raised target? | 1 | market_reaction | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.1`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.3`
- Base report share: `0.067`
- Multi-angle parents: `1`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.1`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.3`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.9`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.067` / `<= 0.55`
- Multi-angle parent count: `1` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
