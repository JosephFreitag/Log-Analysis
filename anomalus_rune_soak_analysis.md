# Arcane Rune Soak Analysis (Arcane Dampening vs Unstable Magic)

## Mechanic Identification (from logs)

- **Bomb post-detonation soak debuff:** `Arcane Dampening` (e.g., `Shangcheeze is afflicted by Arcane Dampening (1)`).
- **Rune/ground-zone damage event:** `Unstable Magic` from `Unstable Magic Zone` casts.
- Practical interpretation: players with `Arcane Dampening` are the intended rune soakers; `Unstable Magic` hits without Dampening are likely unsafe exposures.

## Included Graphic

![Rune Soak Per-Player Graph](./anomalus_rune_soak_scorecard.svg)

## Scope

- Arcane Bomb casts detected: **51**
- Bomb casts where carrier survived detonation window: **39** (players: **18**)
- Players meeting requested graph criteria (bombed + survived + soaked): **15**

## Per-Player Soak Damage Summary (qualified players)

| player | bomb_survived | soaked_hits_with_damp | avg_with_damp | max_with_damp | hits_without_damp | avg_without_damp | max_without_damp |
|---|---:|---:|---:|---:|---:|---:|---:|
| Dokuku | 3 | 2 | 6129.0 | 10006 | 0 | 0.0 | 0 |
| Jorailin | 1 | 1 | 3753.0 | 3753 | 0 | 0.0 | 0 |
| Mazgro | 3 | 3 | 3210.7 | 4128 | 0 | 0.0 | 0 |
| Shangcheeze | 1 | 1 | 2751.0 | 2751 | 0 | 0.0 | 0 |
| Cinos | 2 | 2 | 2502.0 | 2504 | 1 | 37515.0 | 37515 |
| Druidcyy | 1 | 3 | 2123.0 | 2503 | 0 | 0.0 | 0 |
| Caub | 3 | 4 | 1877.2 | 2503 | 0 | 0.0 | 0 |
| Gustovich | 2 | 2 | 1876.0 | 2501 | 1 | 25001.0 | 25001 |
| Lafi | 2 | 2 | 1876.0 | 2501 | 0 | 0.0 | 0 |
| Axememore | 3 | 4 | 1722.2 | 2755 | 0 | 0.0 | 0 |
| Rokomito | 4 | 9 | 1488.4 | 2504 | 1 | 7507.0 | 7507 |
| Snackermz | 1 | 2 | 1337.0 | 2502 | 0 | 0.0 | 0 |
| Ichabaddie | 3 | 6 | 1089.3 | 1916 | 0 | 0.0 | 0 |
| Meatmuncher | 2 | 1 | 851.0 | 851 | 0 | 0.0 | 0 |
| Gladriel | 3 | 4 | 781.2 | 1395 | 0 | 0.0 | 0 |

## Flagged: Unstable Magic hits while **not** having Arcane Dampening (qualified players)

| player | with_damp_avg | without_damp_avg | without_damp_max | without/with ratio | note |
|---|---:|---:|---:|---:|---|
| Cinos | 2502.0 | 37515.0 | 37515 | 14.99x | High unprotected rune damage signal |
| Gustovich | 1876.0 | 25001.0 | 25001 | 13.33x | High unprotected rune damage signal |
| Rokomito | 1488.4 | 7507.0 | 7507 | 5.04x | High unprotected rune damage signal |

## Additional high no-Dampening Unstable Magic exposures (all players)

| player | qualified_graph_player | no_damp_hits | no_damp_avg | no_damp_max | no_damp_total |
|---|---:|---:|---:|---:|---:|
| Cinos | yes | 1 | 37515.0 | 37515 | 37515 |
| Gustovich | yes | 1 | 25001.0 | 25001 | 25001 |
| Zancoo | no | 1 | 12504.0 | 12504 | 12504 |
| Ekureru | no | 1 | 11260.0 | 11260 | 11260 |
| Makende | no | 2 | 10016.5 | 10018 | 20033 |
| Lochien | no | 2 | 10003.0 | 10006 | 20006 |
| Rokomito | yes | 1 | 7507.0 | 7507 | 7507 |

Interpretation: very large no-Dampening hits (often 7.5k-37.5k in this log) are consistent with rune/zone exposure without the intended soak debuff.

