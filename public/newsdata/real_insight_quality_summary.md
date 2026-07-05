# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.7`
- Base report share: `0.3333333333333333`
- Multi-angle parents: `5`
- Weak parents: `5`
- Story count: `503`
- Source groups: `10`
- Content hash: `1d5f296c14768f66`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | How Washington DC marked America 250 | 2 | base_report, market_reaction | NO | 0.6732467197849983 |
| 2 | Ninth edition of The Hindu Home Expo commences at LuLu Mall | 2 | fact_update, base_report | NO | 0.6265800531183316 |
| 3 | British military says cargo ship reports being under attack in Red Sea off coast of Yemen | 3 | official_response, fact_update | NO | 0.5545916683316485 |
| 4 | Iran's supreme leader absent as senior officials attend ayatollah's funeral | 2 | official_response, fact_update | NO | 0.56426 |
| 5 | ‘Very dangerous’ Super Typhoon barrels towards US Pacific islands with 280 kmph winds | 2 | regional_followup, official_response | NO | 0.5465933333333333 |
| 6 | Performer calls for Trump's death at funeral for Iran's late supreme leader | 2 | base_report | YES | 0.5636732802150018 |
| 7 | 'We are heroic people with heroic spirit': Donald Trump marks America's 250th Independence Day | 2 | base_report | YES | 0.5285933333333332 |
| 8 | 10 crore mutual fund investors, Rs 150 lakh crore AUM: Inside AMFI's massive 2030 roadmap | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Yes Bank Q1 business update: Advances rise 18% to Rs 2.85 lakh crore, deposits up 14% | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | SBI Funds Management seeks Rs 2,000 crore in pre-IPO round | 1 | market_reaction | YES | 0.7226911614783158 |

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
- Average evolution roles: `1.7`
- Base report share: `0.333`
- Multi-angle parents: `5`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.5` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.333` / `<= 0.55`
- Multi-angle parent count: `5` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.5` / `<= 0.5`
