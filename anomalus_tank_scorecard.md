# Anomalus Tank Scorecard (Per Pull SVGs)

Tanks analyzed: **Caub, Ichabaddie, Ekureru, Zancoo, Aerodian**

Metric notes:
- `Length spent tanking` uses contiguous windows of direct boss tank engagement events (landed hits + avoided hits) with a max 8s gap.
- `Max stacks` uses highest observed `Manabound Strikes` stack value.
- Damage is split into **physical** (auto attacks) and **arcane** (`Arcane Claws`).
- `hits_avoided` = dodge + parry + miss + resist (full resist events only).

## Overall table (reference)

| tank | length_tanking | max_stacks | physical_total | physical_avg | physical_max | physical_min | physical_hits | arcane_total | arcane_avg | arcane_max | arcane_min | arcane_hits | total_damage_taken | hits_avoided | dodge | parry | miss | resist |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Caub | 01:30.60 | 16 | 47644 | 992.6 | 1924 | 0 | 48 | 58812 | 1014.0 | 3178 | 0 | 58 | 106456 | 10 | 7 | 0 | 3 | 0 |
| Ichabaddie | 01:40.05 | 14 | 53786 | 1311.9 | 13254 | 302 | 41 | 60902 | 1015.0 | 2231 | 491 | 60 | 114688 | 21 | 11 | 5 | 5 | 0 |
| Ekureru | 01:40.13 | 14 | 26934 | 690.6 | 7245 | 0 | 39 | 53980 | 963.9 | 2616 | 223 | 56 | 80914 | 18 | 10 | 4 | 4 | 0 |
| Zancoo | 00:35.99 | 7 | 15913 | 1136.6 | 7995 | 426 | 14 | 11705 | 557.4 | 1181 | 113 | 21 | 27618 | 8 | 3 | 2 | 3 | 0 |
| Aerodian | 00:37.57 | 10 | 17748 | 806.7 | 1255 | 634 | 22 | 25322 | 844.1 | 2700 | 0 | 30 | 43070 | 8 | 1 | 2 | 5 | 0 |

## Pull 1 (Wipe)

![Anomalus Tank Scorecard Pull 1](./anomalus_tank_scorecard_pull1.svg)

| tank | length_tanking | max_stacks | physical_total | physical_avg | physical_max | physical_min | physical_hits | arcane_total | arcane_avg | arcane_max | arcane_min | arcane_hits | total_damage_taken | hits_avoided | dodge | parry | miss | resist |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Caub | 00:32.13 | 14 | 17863 | 1116.4 | 1924 | 832 | 16 | 18636 | 887.4 | 2062 | 0 | 21 | 36499 | 5 | 4 | 0 | 1 | 0 |
| Ichabaddie | 00:26.54 | 14 | 19045 | 1269.7 | 8590 | 566 | 15 | 11658 | 777.2 | 1381 | 558 | 15 | 30703 | 1 | 1 | 0 | 0 | 0 |
| Ekureru | 00:25.85 | 12 | 5672 | 472.7 | 735 | 0 | 12 | 13239 | 827.4 | 1477 | 453 | 16 | 18911 | 4 | 2 | 1 | 1 | 0 |
| Zancoo | 00:15.60 | 5 | 3558 | 711.6 | 901 | 584 | 5 | 5243 | 582.6 | 781 | 438 | 9 | 8801 | 4 | 2 | 2 | 0 | 0 |
| Aerodian | 00:18.16 | 9 | 7353 | 817.0 | 1255 | 634 | 9 | 11325 | 871.2 | 2700 | 0 | 13 | 18678 | 4 | 0 | 1 | 3 | 0 |

## Pull 2 (Wipe)

![Anomalus Tank Scorecard Pull 2](./anomalus_tank_scorecard_pull2.svg)

| tank | length_tanking | max_stacks | physical_total | physical_avg | physical_max | physical_min | physical_hits | arcane_total | arcane_avg | arcane_max | arcane_min | arcane_hits | total_damage_taken | hits_avoided | dodge | parry | miss | resist |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Caub | 00:29.15 | 16 | 15268 | 954.2 | 1609 | 777 | 16 | 20895 | 1229.1 | 3178 | 598 | 17 | 36163 | 1 | 1 | 0 | 0 | 0 |
| Ichabaddie | 00:44.49 | 12 | 23717 | 1824.4 | 13254 | 629 | 13 | 31220 | 1200.8 | 2231 | 513 | 26 | 54937 | 14 | 6 | 4 | 4 | 0 |
| Ekureru | 00:48.41 | 14 | 14913 | 994.2 | 7245 | 265 | 15 | 24717 | 1029.9 | 2447 | 394 | 24 | 39630 | 10 | 7 | 2 | 1 | 0 |
| Zancoo | 00:06.15 | 0 | 7995 | 7995.0 | 7995 | 7995 | 1 | 901 | 450.5 | 788 | 113 | 2 | 8896 | 2 | 0 | 0 | 2 | 0 |
| Aerodian | 00:02.31 | 2 | 2332 | 777.3 | 845 | 642 | 3 | 4162 | 1040.5 | 1181 | 619 | 4 | 6494 | 1 | 0 | 0 | 1 | 0 |

## Pull 3 (Kill)

![Anomalus Tank Scorecard Pull 3](./anomalus_tank_scorecard_pull3.svg)

| tank | length_tanking | max_stacks | physical_total | physical_avg | physical_max | physical_min | physical_hits | arcane_total | arcane_avg | arcane_max | arcane_min | arcane_hits | total_damage_taken | hits_avoided | dodge | parry | miss | resist |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Caub | 00:29.31 | 16 | 14513 | 907.1 | 1422 | 0 | 16 | 19281 | 964.0 | 2031 | 577 | 20 | 33794 | 4 | 2 | 0 | 2 | 0 |
| Ichabaddie | 00:29.02 | 13 | 11024 | 848.0 | 1572 | 302 | 13 | 18024 | 948.6 | 1753 | 491 | 19 | 29048 | 6 | 4 | 1 | 1 | 0 |
| Ekureru | 00:25.87 | 12 | 6349 | 529.1 | 855 | 0 | 12 | 16024 | 1001.5 | 2616 | 223 | 16 | 22373 | 4 | 1 | 1 | 2 | 0 |
| Zancoo | 00:14.24 | 7 | 4360 | 545.0 | 777 | 426 | 8 | 5561 | 556.1 | 1181 | 406 | 10 | 9921 | 2 | 1 | 0 | 1 | 0 |
| Aerodian | 00:17.09 | 10 | 8063 | 806.3 | 1014 | 727 | 10 | 9835 | 756.5 | 1715 | 0 | 13 | 17898 | 3 | 1 | 1 | 1 | 0 |

