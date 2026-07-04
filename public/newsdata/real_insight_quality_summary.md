# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.4`
- Base report share: `0.05555555555555555`
- Multi-angle parents: `3`
- Weak parents: `7`
- Story count: `650`
- Source groups: `10`
- Content hash: `8c8f96caab61f517`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | IT Ministry to summon Meta officials over report on child sexual abuse advertisements on Instagram | 2 | investigative_detail, official_response | NO | 0.6714967197849984 |
| 2 | France reports 2,025 excess deaths amid Europe’s record-breaking heatwave - The Indian Express | 2 | market_reaction, fact_update | NO | 0.6456467197849983 |
| 3 | Prime Minister Modi to visit Indonesia, Australia, New Zealand for bilateral talks | 2 | base_report, official_response | NO | 0.5952732802150018 |
| 4 | Coal-fired power output in June rises to highest since November 2023 | 2 | fact_update | YES | 0.6742467197849984 |
| 5 | Monsoon session of Parliament from July 20 | 3 | fact_update | YES | 0.6331916683316486 |
| 6 | Overnight lines to pay respects to Khamenei | 2 | fact_update | YES | 0.6055800531183317 |
| 7 | Bihar Guv. Hasnain and MoS Margherita attend Ali Khamenei's funeral ceremony in Tehran | 2 | official_response | YES | 0.5513433333333333 |
| 8 | 10 crore mutual fund investors, Rs 150 lakh crore AUM: Inside AMFI's massive 2030 roadmap | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Yes Bank Q1 business update: Advances rise 18% to Rs 2.85 lakh crore, deposits up 14% | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | SBI Funds Management seeks Rs 2,000 crore in pre-IPO round | 1 | market_reaction | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `0`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.4`
- Base report share: `0.056`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.4`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.
- **Weak parent ratio** — actual `0.7`, required `<= 0.5`. Fix: Too many weak trees remain. Repair or demote weak trees after diversity repair.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.056` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
