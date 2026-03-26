# Arcane Pulse (Arcane Aura) Player Scorecard

This scorecard focuses on Arcane Aura intake, mitigation proxies, consumable usage, and **whether Arcane Aura likely triggered early Arcane Bomb detonations**.

## Scope / Filters

- Early Arcane Bomb trigger analysis uses bombs with delay < 12s (Overload -> Bomb).
- **Events within 2.0 seconds of pull end are excluded** from trigger/death attribution to avoid wipe-call/end-of-fight noise.
- Rows are sorted by **avg_aura_hit ascending** (low -> high).
- Trigger classification:
  - `confirmed`: carrier died at/near early det and last meaningful damage was Arcane Aura
  - `likely`: no explicit death line but aura spike immediately before very early det with no competing bomb hit

## Included Graphic

![Arcane Pulse Player Scorecard](./anomalus_pulse_scorecard.svg)

## Columns

- `aura_early_bomb_triggers`: number of early Arcane Bomb detonations linked to Arcane Aura on that carrier
- `triggers_confirmed` / `triggers_likely`: confidence split for those triggers
- `trigger_followups`: number of follow-up early bombs in same cascade after this trigger
- `trigger_cluster_bomb_deaths`: bomb deaths in the same triggered cluster
- `trigger_selfheal<=6.1s`: trigger events where carrier self-healed within prior 6.1s
- `trigger_consumable<=6.1s`: trigger events where Arcane Protection/Healthstone/Tea used within prior 6.1s
- `trigger_no_response<=6.1s`: trigger events with no self-heal and no listed consumable in prior 6.1s

| player | risk | avg_aura_hit | resist% | absorb% | zero_hit% | arcane_prot | healthstone | tea | aura_early_bomb_triggers | triggers_confirmed | triggers_likely | trigger_followups | trigger_cluster_bomb_deaths | trigger_selfheal<=6.1s | trigger_consumable<=6.1s | trigger_no_response<=6.1s |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Caub | 1 | 124.1 | 70.8% | 9.1% | 2.8% | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Ichabaddie | 0 | 124.6 | 68.6% | 17.0% | 8.8% | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Rokomito | 2 | 145.6 | 52.8% | 2.1% | 7.3% | 3 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Aerodian | 0 | 151.9 | 71.1% | 8.4% | 6.5% | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Gladriel | 0 | 156.3 | 59.2% | 6.5% | 12.4% | 2 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Zancoo | 0 | 156.8 | 69.7% | 30.5% | 15.9% | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Iriale | 0 | 160.7 | 72.8% | 27.4% | 25.9% | 4 | 2 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Dokuku | 1 | 161.0 | 59.8% | 2.9% | 19.0% | 1 | 3 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Lafi | 0 | 169.9 | 63.7% | 12.7% | 8.8% | 3 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Meatmuncher | 0 | 178.8 | 62.7% | 20.7% | 22.7% | 3 | 1 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Jorailin | 0 | 181.9 | 63.1% | 23.4% | 27.4% | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Axememore | 0 | 183.6 | 67.6% | 3.4% | 2.6% | 1 | 2 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Girthbone | 0 | 190.7 | 69.6% | 11.3% | 9.6% | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Gustovich | 0 | 191.5 | 59.6% | 19.2% | 17.9% | 2 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Snackermz | 0 | 195.2 | 65.0% | 6.4% | 9.6% | 2 | 3 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Ekureru | 2 | 201.6 | 62.8% | 0.0% | 0.0% | 0 | 3 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Naturetouch | 0 | 204.0 | 68.2% | 5.1% | 3.4% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Topsoon | 0 | 204.5 | 64.7% | 26.1% | 22.2% | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Mazgro | 0 | 208.0 | 65.3% | 4.6% | 2.6% | 2 | 2 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Makende | 2 | 214.2 | 49.9% | 5.1% | 2.9% | 2 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Mynie | 1 | 219.9 | 63.1% | 20.5% | 21.6% | 3 | 2 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Cinos | 1 | 229.1 | 60.3% | 5.0% | 4.6% | 2 | 1 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Voster | 1 | 231.4 | 62.8% | 11.4% | 9.6% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Lezner | 1 | 232.5 | 60.3% | 22.0% | 15.1% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Ambitious | 3 | 236.9 | 63.7% | 0.0% | 0.0% | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Druidcyy | 2 | 241.3 | 58.7% | 4.5% | 7.2% | 3 | 2 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Adalette | 1 | 243.5 | 61.5% | 7.2% | 5.9% | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Koukenbol | 1 | 248.3 | 61.1% | 5.5% | 5.6% | 3 | 1 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Stormstiker | 1 | 248.5 | 61.0% | 5.6% | 6.1% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Nawern | 3 | 250.4 | 61.0% | 4.0% | 5.2% | 3 | 1 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Midnas | 2 | 253.2 | 60.2% | 6.1% | 8.1% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Amends | 3 | 255.4 | 57.0% | 18.7% | 9.0% | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Lochien | 4 | 255.7 | 44.4% | 9.0% | 6.2% | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Totemhero | 3 | 275.7 | 56.4% | 6.7% | 7.7% | 2 | 1 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Sarys | 4 | 276.2 | 57.6% | 0.3% | 0.0% | 0 | 0 | 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Shangcheeze | 3 | 279.5 | 54.8% | 4.9% | 3.8% | 1 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Junoxz | 3 | 287.7 | 59.2% | 4.3% | 2.4% | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Obanion | 4 | 290.7 | 55.3% | 0.3% | 0.0% | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Coincidence | 3 | 299.2 | 52.9% | 5.4% | 5.5% | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Lopp | 4 | 335.1 | 50.1% | 13.4% | 12.3% | 3 | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
