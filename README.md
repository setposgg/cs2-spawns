# CS2 spawns

Competitive and extra spawn positions for seven Counter-Strike 2 maps, with diagrams, console commands, JSON and CSV.

![Mirage numbered T and CT spawns](maps/mirage.svg)

## Use in game

Load a map on a local practice server and run `sv_cheats 1` in the console.
Paste a command from the tables below to TP to that spawn.
The optional `setang` part sets the direction you face when you spawn.
Short ticks on the diagrams show that direction; linked numbers open available lineups.
Filled circles are competitive positions. Muted boxes E1, E2 mean extra 1, extra 2 for that side; dashed boxes are disabled 2v2 entities.
Commands marked `entity-origin-unsettled` start at the entity origin: the player drops to the floor. Wait until grounded before using that position.

<!-- generated:maps -->
### Mirage

[Mirage on setpos.gg](https://setpos.gg/mirage) · CSV: [all](csv/mirage.csv), [competitive](csv/competitive/mirage.csv), [extras](csv/non-competitive/mirage.csv)

15 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos 1296 -352 -167.96875` | `setpos 1296 -352 -167.96875; setang 0 227 0` | [Open](https://setpos.gg/mirage/t1) |
| T spawn 2 | `setpos 1216 -307 -164.814819` | `setpos 1216 -307 -164.814819; setang 0 270 0` | [Open](https://setpos.gg/mirage/t2) |
| T spawn 3 | `setpos 1136 -256 -164.836548` | `setpos 1136 -256 -164.836548; setang 0 270 0` | — |
| T spawn 4 | `setpos 1216 -211 -163.96875` | `setpos 1216 -211 -163.96875; setang 0 270 0` | [Open](https://setpos.gg/mirage/t4) |
| T spawn 5 | `setpos 1136 -160 -164.430542` | `setpos 1136 -160 -164.430542; setang 0 270 0` | — |
| T spawn 6 | `setpos 1216 -115 -163.96875` | `setpos 1216 -115 -163.96875; setang 0 90 0` | [Open](https://setpos.gg/mirage/t6) |
| T spawn 7 | `setpos 1136 -64 -164.499146` | `setpos 1136 -64 -164.499146; setang 0 90 0` | — |
| T spawn 8 | `setpos 1216 -16 -163.96875` | `setpos 1216 -16 -163.96875; setang 0 90 0` | [Open](https://setpos.gg/mirage/t8) |
| T spawn 9 | `setpos 1136 32 -164.788452` | `setpos 1136 32 -164.788452; setang 0 90 0` | [Open](https://setpos.gg/mirage/t9) |
| T spawn 10 | `setpos 1296 32 -167.96875` | `setpos 1296 32 -167.96875; setang 0 141 0` | [Open](https://setpos.gg/mirage/t10) |
| CT spawn 1 | `setpos -1656 -1800 -267.206421` | `setpos -1656 -1800 -267.206421; setang 0 94 0` | — |
| CT spawn 2 | `setpos -1776 -1800 -263.96875` | `setpos -1776 -1800 -263.96875; setang 0 36 0` | — |
| CT spawn 3 | `setpos -1720 -1896 -267.602295` | `setpos -1720 -1896 -267.602295; setang 0 50 0` | — |
| CT spawn 4 | `setpos -1656 -1976 -267.458313` | `setpos -1656 -1976 -267.458313; setang 0 299 0` | — |
| CT spawn 5 | `setpos -1776 -1976 -263.96875` | `setpos -1776 -1976 -263.96875; setang 0 331 0` | [Open](https://setpos.gg/mirage/ct5) |

<details>
<summary>18 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos 1376 -304 -144` | `setpos 1376 -304 -144; setang 0 227 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 2 | `setpos 1296 -256 -144` | `setpos 1296 -256 -144; setang 0 227 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 3 | `setpos 1376 -208 -144` | `setpos 1376 -208 -144; setang 0 227 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 4 | `setpos 1296 -160 -144` | `setpos 1296 -160 -144; setang 0 227 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 5 | `setpos 1376 -112 -144` | `setpos 1376 -112 -144; setang 0 141 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 6 | `setpos 1296 -64 -144` | `setpos 1296 -64 -144; setang 0 141 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 7 | `setpos 1376 -16 -144` | `setpos 1376 -16 -144; setang 0 141 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos -1552 -1808 -240` | `setpos -1552 -1808 -240; setang 0 116 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 2 | `setpos -1552 -1968 -240` | `setpos -1552 -1968 -240; setang 0 288 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 3 | `setpos -1598 -1732 -240` | `setpos -1598 -1732 -240; setang 0 106 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 4 | `setpos -1608 -1888 -240` | `setpos -1608 -1888 -240; setang 0 306 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 5 | `setpos -1632 -2072 -240` | `setpos -1632 -2072 -240; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos -1830 -1896 -240` | `setpos -1830 -1896 -240; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos -1902 -1816 -240` | `setpos -1902 -1816 -240; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 8 | `setpos -1902 -1976 -240` | `setpos -1902 -1976 -240; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 9 | `setpos -1976 -1812 -272` | `setpos -1976 -1812 -272; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 10 | `setpos -1957 -1898 -262` | `setpos -1957 -1898 -262; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 11 | `setpos -1972 -1988 -264` | `setpos -1972 -1988 -264; setang 0 0 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Dust II

[Dust II on setpos.gg](https://setpos.gg/dust2) · CSV: [all](csv/dust2.csv), [competitive](csv/competitive/dust2.csv), [extras](csv/non-competitive/dust2.csv)

![Dust II numbered T and CT spawns](maps/dust2.svg)

20 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos -1181 -754 120.181252` | `setpos -1181 -754 120.181252; setang 0 42 0` | [Open](https://setpos.gg/dust2/t1) |
| T spawn 2 | `setpos -1141 -808 116.685989` | `setpos -1141 -808 116.685989; setang 0 112 0` | — |
| T spawn 3 | `setpos -1076 -843 116.789474` | `setpos -1076 -843 116.789474; setang 0 133.5 0` | [Open](https://setpos.gg/dust2/t3) |
| T spawn 4 | `setpos -1015 -808 116.082619` | `setpos -1015 -808 116.082619; setang 0 183 0` | — |
| T spawn 5 | `setpos -980 -754 120.181267` | `setpos -980 -754 120.181267; setang 0 212.5 0` | — |
| T spawn 6 | `setpos -857.506531 -738.361328 122.089119` | `setpos -857.506531 -738.361328 122.089119; setang 0 37 0` | — |
| T spawn 7 | `setpos -822.365173 -795.64209 117.264` | `setpos -822.365173 -795.64209 117.264; setang 0 107 0` | — |
| T spawn 8 | `setpos -760.662964 -836.174011 117.071777` | `setpos -760.662964 -836.174011 117.071777; setang 0 128.5 0` | — |
| T spawn 9 | `setpos -696.844604 -806.623718 116.708214` | `setpos -696.844604 -806.623718 116.708214; setang 0 178 0` | — |
| T spawn 10 | `setpos -657.271362 -755.879639 119.884018` | `setpos -657.271362 -755.879639 119.884018; setang 0 207.5 0` | — |
| T spawn 11 | `setpos -533 -754 113.848991` | `setpos -533 -754 113.848991; setang 0 42 0` | [Open](https://setpos.gg/dust2/t11) |
| T spawn 12 | `setpos -493 -808 108.563377` | `setpos -493 -808 108.563377; setang 0 112 0` | [Open](https://setpos.gg/dust2/t12) |
| T spawn 13 | `setpos -428 -843 95.29628` | `setpos -428 -843 95.29628; setang 0 133.5 0` | [Open](https://setpos.gg/dust2/t13) |
| T spawn 14 | `setpos -367 -808 83.744965` | `setpos -367 -808 83.744965; setang 0 183 0` | [Open](https://setpos.gg/dust2/t14) |
| T spawn 15 | `setpos -332 -754 78.877106` | `setpos -332 -754 78.877106; setang 0 212.5 0` | [Open](https://setpos.gg/dust2/t15) |
| CT spawn 1 | `setpos 351.39212 2352.942383 -120.474915` | `setpos 351.39212 2352.942383 -120.474915; setang 0 202.5 0` | [Open](https://setpos.gg/dust2/ct1) |
| CT spawn 2 | `setpos 334.368744 2433.733643 -120.362549` | `setpos 334.368744 2433.733643 -120.362549; setang 0 230 0` | [Open](https://setpos.gg/dust2/ct2) |
| CT spawn 3 | `setpos 258.159393 2480.553711 -121.07666` | `setpos 258.159393 2480.553711 -121.07666; setang 0 292.5 0` | [Open](https://setpos.gg/dust2/ct3) |
| CT spawn 4 | `setpos 182.249908 2439.011719 -120.96875` | `setpos 182.249908 2439.011719 -120.96875; setang 0 356 0` | [Open](https://setpos.gg/dust2/ct4) |
| CT spawn 5 | `setpos 160.122742 2369.67627 -119.918701` | `setpos 160.122742 2369.67627 -119.918701; setang 0 24 0` | [Open](https://setpos.gg/dust2/ct5) |

<details>
<summary>10 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| CT extra 1 | `setpos 454.834656 2099.009033 -109` | `setpos 454.834656 2099.009033 -109; setang 0 129 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 2 | `setpos 421.494202 2288.092285 -109` | `setpos 421.494202 2288.092285 -109; setang 0 307.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 3 | `setpos 382.134918 2102.437012 -109` | `setpos 382.134918 2102.437012 -109; setang 0 101 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 4 | `setpos 347.861938 2250.738525 -109` | `setpos 347.861938 2250.738525 -109; setang 0 335 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 5 | `setpos 322.361481 2165.008057 -109` | `setpos 322.361481 2165.008057 -109; setang 0 37.500004 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos 264.453705 2210.391602 -109` | `setpos 264.453705 2210.391602 -109; setang 0 202.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos 217.633453 2134.182129 -109` | `setpos 217.633453 2134.182129 -109; setang 0 139.999985 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 8 | `setpos 222.911575 2286.301025 -109` | `setpos 222.911575 2286.301025 -109; setang 0 266 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 9 | `setpos 153.576233 2308.428223 -109` | `setpos 153.576233 2308.428223 -109; setang 0 294 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 10 | `setpos 136.842346 2117.158936 -109` | `setpos 136.842346 2117.158936 -109; setang 0 112.499985 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Anubis

[Anubis on setpos.gg](https://setpos.gg/anubis) · CSV: [all](csv/anubis.csv), [competitive](csv/competitive/anubis.csv), [extras](csv/non-competitive/anubis.csv)

![Anubis numbered T and CT spawns](maps/anubis.svg)

16 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos -416 -1608 2.03125` | `setpos -416 -1608 2.03125; setang 0 150 0` | [Open](https://setpos.gg/anubis/t1) |
| T spawn 2 | `setpos -416 -1696 2.03125` | `setpos -416 -1696 2.03125; setang 0 135 0` | [Open](https://setpos.gg/anubis/t2) |
| T spawn 3 | `setpos -384 -1552 -11.96875` | `setpos -384 -1552 -11.96875; setang 0 165 0` | [Open](https://setpos.gg/anubis/t3) |
| T spawn 4 | `setpos -328 -1528 -11.96875` | `setpos -328 -1528 -11.96875; setang 0 150 0` | [Open](https://setpos.gg/anubis/t4) |
| T spawn 5 | `setpos -304 -1608 -11.96875` | `setpos -304 -1608 -11.96875; setang 0 135 0` | [Open](https://setpos.gg/anubis/t5) |
| T spawn 6 | `setpos -264 -1560 -11.96875` | `setpos -264 -1560 -11.96875; setang 0 90 0` | [Open](https://setpos.gg/anubis/t6) |
| T spawn 7 | `setpos -234 -1503.079956 -11.96875` | `setpos -234 -1503.079956 -11.96875; setang 0 45 0` | [Open](https://setpos.gg/anubis/t7) |
| T spawn 8 | `setpos -192 -1608 -11.96875` | `setpos -192 -1608 -11.96875; setang 0 90 0` | [Open](https://setpos.gg/anubis/t8) |
| T spawn 9 | `setpos -154 -1503.079956 -11.96875` | `setpos -154 -1503.079956 -11.96875; setang 0 30 0` | [Open](https://setpos.gg/anubis/t9) |
| T spawn 10 | `setpos -144 -1568 -11.96875` | `setpos -144 -1568 -11.96875; setang 0 60 0` | [Open](https://setpos.gg/anubis/t10) |
| T spawn 11 | `setpos -128.004028 -1632 -0.960938` | `setpos -128.004028 -1632 -0.960938; setang 0 45 0` | [Open](https://setpos.gg/anubis/t11) |
| CT spawn 1 | `setpos -360 2120 16.056593` | `setpos -360 2120 16.056593; setang 0 225 0` | — |
| CT spawn 2 | `setpos -400 2192 25.031252` | `setpos -400 2192 25.031252; setang 0 240 0` | [Open](https://setpos.gg/anubis/ct2) |
| CT spawn 3 | `setpos -476 2216 25.031252` | `setpos -476 2216 25.031252; setang 0 270 0` | [Open](https://setpos.gg/anubis/ct3) |
| CT spawn 4 | `setpos -560 2192 25.031252` | `setpos -560 2192 25.031252; setang 0 285 0` | [Open](https://setpos.gg/anubis/ct4) |
| CT spawn 5 | `setpos -608 2120 16.056595` | `setpos -608 2120 16.056595; setang 0 315 0` | [Open](https://setpos.gg/anubis/ct5) |

<details>
<summary>16 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos -352 -1640 16` | `setpos -352 -1640 16; setang 0 120 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 2 | `setpos -352 -1696 16` | `setpos -352 -1696 16; setang 0 120 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 3 | `setpos -248 -1632 16` | `setpos -248 -1632 16; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 4 | `setpos -240 -1696 16` | `setpos -240 -1696 16; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 5 | `setpos -176 -1696 16` | `setpos -176 -1696 16; setang 0 45 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos -192 2336 32` | `setpos -192 2336 32; setang 0 225 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 2 | `setpos -212 2184 32` | `setpos -212 2184 32; setang 0 195 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 3 | `setpos -240 2268 32` | `setpos -240 2268 32; setang 0 240 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 4 | `setpos -284 2176 32` | `setpos -284 2176 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 5 | `setpos -292 2328 32` | `setpos -292 2328 32; setang 0 330 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos -340 2216 32` | `setpos -340 2216 32; setang 0 255 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos -360 2288 32` | `setpos -360 2288 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 8 | `setpos -432 2268 32` | `setpos -432 2268 32; setang 0 255 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 9 | `setpos -576 2252 32` | `setpos -576 2252 32; setang 0 345 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 10 | `setpos -628 2208 32` | `setpos -628 2208 32; setang 0 345 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 11 | `setpos -672 2152 32` | `setpos -672 2152 32; setang 0 315 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Inferno

[Inferno on setpos.gg](https://setpos.gg/inferno) · CSV: [all](csv/inferno.csv), [competitive](csv/competitive/inferno.csv), [extras](csv/non-competitive/inferno.csv)

![Inferno numbered T and CT spawns](maps/inferno.svg)

11 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos -1520.060059 430.890991 -63.96875` | `setpos -1520.060059 430.890991 -63.96875; setang 0 267 0` | — |
| T spawn 2 | `setpos -1586.52002 440.790009 -63.96875` | `setpos -1586.52002 440.790009 -63.96875; setang 0 337 0` | — |
| T spawn 3 | `setpos -1657.22998 419.576996 -63.96875` | `setpos -1657.22998 419.576996 -63.96875; setang 0 358.5 0` | — |
| T spawn 4 | `setpos -1675.619995 351.695007 -63.96875` | `setpos -1675.619995 351.695007 -63.96875; setang 0 48 0` | — |
| T spawn 5 | `setpos -1662.180054 288.761993 -63.96875` | `setpos -1662.180054 288.761993 -63.96875; setang 0 77.5 0` | — |
| CT spawn 1 | `setpos 2292.060059 2027.689941 135.956955` | `setpos 2292.060059 2027.689941 135.956955; setang 0 70 0` | [Open](https://setpos.gg/inferno/ct1) |
| CT spawn 2 | `setpos 2353 1977 135.518875` | `setpos 2353 1977 135.518875; setang 0 97.5 0` | [Open](https://setpos.gg/inferno/ct2) |
| CT spawn 3 | `setpos 2397 2079 132.767548` | `setpos 2397 2079 132.767548; setang 0 135 0` | [Open](https://setpos.gg/inferno/ct3) |
| CT spawn 4 | `setpos 2472.349854 2005.969971 134.505051` | `setpos 2472.349854 2005.969971 134.505051; setang 0 160 0` | [Open](https://setpos.gg/inferno/ct4) |
| CT spawn 5 | `setpos 2493 2090 132.551376` | `setpos 2493 2090 132.551376; setang 0 223.5 0` | [Open](https://setpos.gg/inferno/ct5) |
| CT spawn 6 | `setpos 2456.830078 2153.159912 132.077179` | `setpos 2456.830078 2153.159912 132.077179; setang 0 251.5 0` | [Open](https://setpos.gg/inferno/ct6) |

<details>
<summary>29 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos 592 606 128` | `setpos 592 606 128; setang 0 0 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 2 | `setpos 591.698975 545 128` | `setpos 591.698975 545 128; setang 0 0 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 3 | `setpos 509 605 128` | `setpos 509 605 128; setang 0 0 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 4 | `setpos 508.699005 544 128` | `setpos 508.699005 544 128; setang 0 0 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 5 | `setpos -1491 490 -46` | `setpos -1491 490 -46; setang 0 222 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 6 | `setpos -1533 745 -24` | `setpos -1533 745 -24; setang 0 292 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 7 | `setpos -1518 624 -24` | `setpos -1518 624 -24; setang 0 222 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 8 | `setpos -1531 544 -46` | `setpos -1531 544 -46; setang 0 292 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 9 | `setpos -1603 768 -24` | `setpos -1603 768 -24; setang 0 313.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 10 | `setpos -1579 673 -40` | `setpos -1579 673 -40; setang 0 284.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 11 | `setpos -1596 579 -46` | `setpos -1596 579 -46; setang 0 313.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 12 | `setpos -1650 718 -24` | `setpos -1650 718 -24; setang 0 3 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 13 | `setpos -1649 641 -24` | `setpos -1649 641 -24; setang 0 32.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 14 | `setpos -1657 544 -46` | `setpos -1657 544 -46; setang 0 3 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 15 | `setpos -1668 489 -46` | `setpos -1668 489 -46; setang 0 32.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos 2272 608 160` | `setpos 2272 608 160; setang 0 180.000015 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 2 | `setpos 2336 608 160` | `setpos 2336 608 160; setang 0 180.000015 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 3 | `setpos 2272 672 160` | `setpos 2272 672 160; setang 0 180.000015 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 4 | `setpos 2336 672 160` | `setpos 2336 672 160; setang 0 180.000015 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 5 | `setpos 2342.830078 1792.109985 140.843002` | `setpos 2342.830078 1792.109985 140.843002; setang 0 100 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos 2270 1831 140.843002` | `setpos 2270 1831 140.843002; setang 0 72.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos 2417 1824 140.843002` | `setpos 2417 1824 140.843002; setang 0 162.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 8 | `setpos 2438 1900 140.843002` | `setpos 2438 1900 140.843002; setang 0 226 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 9 | `setpos 2420.98999 1965.77002 140.843002` | `setpos 2420.98999 1965.77002 140.843002; setang 0 254 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 10 | `setpos 2374.469971 2171.850098 140.843002` | `setpos 2374.469971 2171.850098 140.843002; setang 0 108.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 11 | `setpos 2296.679932 2199.540039 140.843002` | `setpos 2296.679932 2199.540039 140.843002; setang 0 81 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 12 | `setpos 2479.320068 2213.470215 140.843002` | `setpos 2479.320068 2213.470215 140.843002; setang 0 171 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 13 | `setpos 2483.560059 2299.900146 140.843002` | `setpos 2483.560059 2299.900146 140.843002; setang 0 234.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 14 | `setpos 2436 2355 140.843002` | `setpos 2436 2355 140.843002; setang 0 262.5 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Ancient

[Ancient on setpos.gg](https://setpos.gg/ancient) · CSV: [all](csv/ancient.csv), [competitive](csv/competitive/ancient.csv), [extras](csv/non-competitive/ancient.csv)

![Ancient numbered T and CT spawns](maps/ancient.svg)

10 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos -584 -2288 -162.422363` | `setpos -584 -2288 -162.422363; setang 0 90 0` | [Open](https://setpos.gg/ancient/t1) |
| T spawn 2 | `setpos -520 -2224 -163.255737` | `setpos -520 -2224 -163.255737; setang 0 90 0` | [Open](https://setpos.gg/ancient/t2) |
| T spawn 3 | `setpos -456 -2288 -163.255737` | `setpos -456 -2288 -163.255737; setang 0 90 0` | [Open](https://setpos.gg/ancient/t3) |
| T spawn 4 | `setpos -392 -2224 -163.255737` | `setpos -392 -2224 -163.255737; setang 0 90 0` | [Open](https://setpos.gg/ancient/t4) |
| T spawn 5 | `setpos -328 -2288 -163.255737` | `setpos -328 -2288 -163.255737; setang 0 90 0` | [Open](https://setpos.gg/ancient/t5) |
| CT spawn 1 | `setpos -192 1696 26.053045` | `setpos -192 1696 26.053045; setang 0 270 0` | [Open](https://setpos.gg/ancient/ct1) |
| CT spawn 2 | `setpos -256 1728 25.602571` | `setpos -256 1728 25.602571; setang 0 270 0` | [Open](https://setpos.gg/ancient/ct2) |
| CT spawn 3 | `setpos -352 1728 28.813293` | `setpos -352 1728 28.813293; setang 0 270 0` | [Open](https://setpos.gg/ancient/ct3) |
| CT spawn 4 | `setpos -448 1728 30.739708` | `setpos -448 1728 30.739708; setang 0 270 0` | [Open](https://setpos.gg/ancient/ct4) |
| CT spawn 5 | `setpos -512 1696 26.837196` | `setpos -512 1696 26.837196; setang 0 270 0` | [Open](https://setpos.gg/ancient/ct5) |

<details>
<summary>14 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos -552 -2384 -156` | `setpos -552 -2384 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 2 | `setpos -520 -2320 -156` | `setpos -520 -2320 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 3 | `setpos -456 -2384 -156` | `setpos -456 -2384 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 4 | `setpos -456 -2448 -156` | `setpos -456 -2448 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 5 | `setpos -392 -2320 -156` | `setpos -392 -2320 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 6 | `setpos -360 -2384 -156` | `setpos -360 -2384 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 7 | `setpos -296 -2352 -156` | `setpos -296 -2352 -156; setang 0 90 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos -224 1632 32` | `setpos -224 1632 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 2 | `setpos -288 1568 32` | `setpos -288 1568 32; setang 0 270 0` | 2 | Yes | Entity origin; drops to floor |
| CT extra 3 | `setpos -288 1664 32` | `setpos -288 1664 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 4 | `setpos -352 1632 32` | `setpos -352 1632 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 5 | `setpos -416 1568 32` | `setpos -416 1568 32; setang 0 270 0` | 2 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos -416 1664 32` | `setpos -416 1664 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos -480 1632 32` | `setpos -480 1632 32; setang 0 270 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Nuke

[Nuke on setpos.gg](https://setpos.gg/nuke) · CSV: [all](csv/nuke.csv), [competitive](csv/competitive/nuke.csv), [extras](csv/non-competitive/nuke.csv)

![Nuke numbered T and CT spawns](maps/nuke.svg)

13 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos -1947.01001 -965.109985 -415.96875` | `setpos -1947.01001 -965.109985 -415.96875; setang 0 312 0` | [Open](https://setpos.gg/nuke/t1) |
| T spawn 2 | `setpos -1878 -980 -415.96875` | `setpos -1878 -980 -415.96875; setang 0 294 0` | — |
| T spawn 3 | `setpos -1808 -1025 -415.96875` | `setpos -1808 -1025 -415.96875; setang 0 329 0` | [Open](https://setpos.gg/nuke/t3) |
| T spawn 4 | `setpos -1929 -1025 -415.96875` | `setpos -1929 -1025 -415.96875; setang 0 3 0` | [Open](https://setpos.gg/nuke/t4) |
| T spawn 5 | `setpos -1874 -1076 -415.96875` | `setpos -1874 -1076 -415.96875; setang 0 336 0` | [Open](https://setpos.gg/nuke/t5) |
| T spawn 6 | `setpos -1808 -1089 -415.96875` | `setpos -1808 -1089 -415.96875; setang 0 340 0` | [Open](https://setpos.gg/nuke/t6) |
| T spawn 7 | `setpos -1947.01001 -1102.109985 -415.96875` | `setpos -1947.01001 -1102.109985 -415.96875; setang 0 74.5 0` | [Open](https://setpos.gg/nuke/t7) |
| T spawn 8 | `setpos -1832 -1160 -415.96875` | `setpos -1832 -1160 -415.96875; setang 0 40 0` | [Open](https://setpos.gg/nuke/t8) |
| CT spawn 1 | `setpos 2512 -504 -343.367126` | `setpos 2512 -504 -343.367126; setang 0 145 0` | — |
| CT spawn 2 | `setpos 2584 -504 -351.96875` | `setpos 2584 -504 -351.96875; setang 0 161 0` | — |
| CT spawn 3 | `setpos 2552 -424 -351.96875` | `setpos 2552 -424 -351.96875; setang 0 207.5 0` | — |
| CT spawn 4 | `setpos 2504 -344 -351.96875` | `setpos 2504 -344 -351.96875; setang 0 271 0` | — |
| CT spawn 5 | `setpos 2585 -344 -351.96875` | `setpos 2585 -344 -351.96875; setang 0 200.5 0` | — |

<details>
<summary>27 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos 1554.979492 -2116.267822 -616` | `setpos 1554.979492 -2116.267822 -616; setang 0 90 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 2 | `setpos 1555.979492 -2199.267822 -616` | `setpos 1555.979492 -2199.267822 -616; setang 0 90 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 3 | `setpos 1493.979492 -2115.966797 -616` | `setpos 1493.979492 -2115.966797 -616; setang 0 90 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 4 | `setpos 1494.979492 -2198.966797 -616` | `setpos 1494.979492 -2198.966797 -616; setang 0 90 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| T extra 5 | `setpos -2001.01001 -973.109985 -400.634003` | `setpos -2001.01001 -973.109985 -400.634003; setang 0 22 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 6 | `setpos -2001.01001 -1099.109985 -400.634003` | `setpos -2001.01001 -1099.109985 -400.634003; setang 0 55.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 7 | `setpos -2036.01001 -1038.109985 -400.634003` | `setpos -2036.01001 -1038.109985 -400.634003; setang 0 15 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 8 | `setpos -2072 -960 -400.634003` | `setpos -2072 -960 -400.634003; setang 0 312 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 9 | `setpos -2072 -1097 -400.634003` | `setpos -2072 -1097 -400.634003; setang 0 58 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 10 | `setpos -2097 -1033 -400.634003` | `setpos -2097 -1033 -400.634003; setang 0 8.5 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 11 | `setpos -2134 -968 -400.634003` | `setpos -2134 -968 -400.634003; setang 0 22 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 12 | `setpos -2134 -1094 -400.634003` | `setpos -2134 -1094 -400.634003; setang 0 36.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos 748.059814 71.994751 -404` | `setpos 748.059814 71.994751 -404; setang 0 90.000038 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 2 | `setpos 748.059814 135.994751 -404` | `setpos 748.059814 135.994751 -404; setang 0 90.000038 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 3 | `setpos 812.059814 71.994751 -404` | `setpos 812.059814 71.994751 -404; setang 0 90.000038 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 4 | `setpos 812.059814 135.994751 -404` | `setpos 812.059814 135.994751 -404; setang 0 90.000038 0` | 0 | No (2v2 group) | Entity origin; drops to floor |
| CT extra 5 | `setpos 2280 -496 -335` | `setpos 2280 -496 -335; setang 0 117.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 6 | `setpos 2280 -336 -335` | `setpos 2280 -336 -335; setang 0 242.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 7 | `setpos 2343 -488 -335` | `setpos 2343 -488 -335; setang 0 145 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 8 | `setpos 2323 -411 -335` | `setpos 2323 -411 -335; setang 0 181 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 9 | `setpos 2351 -352 -335` | `setpos 2351 -352 -335; setang 0 230 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 10 | `setpos 2399 -440 -335` | `setpos 2399 -440 -335; setang 0 194.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 11 | `setpos 2440 -496 -335` | `setpos 2440 -496 -335; setang 0 117.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 12 | `setpos 2430.850098 -370.582001 -335` | `setpos 2430.850098 -370.582001 -335; setang 0 218.5 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 13 | `setpos 2664 -496 -335` | `setpos 2664 -496 -335; setang 0 178 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 14 | `setpos 2656 -360 -335` | `setpos 2656 -360 -335; setang 0 204 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 15 | `setpos 2704 -416 -335` | `setpos 2704 -416 -335; setang 0 207.5 0` | 1 | Yes | Entity origin; drops to floor |

</details>

### Cache

[Cache on setpos.gg](https://setpos.gg/cache) · CSV: [all](csv/cache.csv), [competitive](csv/competitive/cache.csv), [extras](csv/non-competitive/cache.csv)

![Cache numbered T and CT spawns](maps/cache.svg)

15 competitive positions.

| Spawn | setpos | setpos + setang | Page |
| --- | --- | --- | --- |
| T spawn 1 | `setpos 2995.893555 -168 1608.031372` | `setpos 2995.893555 -168 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t1) |
| T spawn 2 | `setpos 3094.268555 -152.582214 1608.031494` | `setpos 3094.268555 -152.582214 1608.031494; setang 0 182 0` | [Open](https://setpos.gg/cache/t2) |
| T spawn 3 | `setpos 3171.643555 -100.832214 1608.03125` | `setpos 3171.643555 -100.832214 1608.03125; setang 0 182 0` | [Open](https://setpos.gg/cache/t3) |
| T spawn 4 | `setpos 2949.018555 -47.000008 1608.031372` | `setpos 2949.018555 -47.000008 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t4) |
| T spawn 5 | `setpos 3041.768555 -21.082214 1608.031372` | `setpos 3041.768555 -21.082214 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t5) |
| T spawn 6 | `setpos 3162.143555 -5.000008 1608.031372` | `setpos 3162.143555 -5.000008 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t6) |
| T spawn 7 | `setpos 2916.768555 69.417786 1608.031372` | `setpos 2916.768555 69.417786 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t7) |
| T spawn 8 | `setpos 3037.893555 66.667786 1608.031372` | `setpos 3037.893555 66.667786 1608.031372; setang 0 182 0` | [Open](https://setpos.gg/cache/t8) |
| T spawn 9 | `setpos 3077.768555 135.917786 1616.03125` | `setpos 3077.768555 135.917786 1616.03125; setang 0 182 0` | [Open](https://setpos.gg/cache/t9) |
| T spawn 10 | `setpos 2922.518555 165.667786 1616.030273` | `setpos 2922.518555 165.667786 1616.030273; setang 0 182 0` | [Open](https://setpos.gg/cache/t10) |
| CT spawn 1 | `setpos -1400.283203 706.819336 1614.03125` | `setpos -1400.283203 706.819336 1614.03125; setang 0 270 0` | [Open](https://setpos.gg/cache/ct1) |
| CT spawn 2 | `setpos -1488.283203 706.819336 1614.03125` | `setpos -1488.283203 706.819336 1614.03125; setang 0 270 0` | [Open](https://setpos.gg/cache/ct2) |
| CT spawn 3 | `setpos -1524.283203 794.819336 1614.03125` | `setpos -1524.283203 794.819336 1614.03125; setang 0 270 0` | [Open](https://setpos.gg/cache/ct3) |
| CT spawn 4 | `setpos -1400.283203 874.819336 1614.03125` | `setpos -1400.283203 874.819336 1614.03125; setang 0 270 0` | [Open](https://setpos.gg/cache/ct4) |
| CT spawn 5 | `setpos -1488.283203 874.819336 1614.03125` | `setpos -1488.283203 874.819336 1614.03125; setang 0 270 0` | [Open](https://setpos.gg/cache/ct5) |

<details>
<summary>17 non-competitive positions</summary>

| Spawn | setpos | setpos + setang | Priority | Enabled | Height |
| --- | --- | --- | ---: | --- | --- |
| T extra 1 | `setpos 3257.643555 7.999992 1628` | `setpos 3257.643555 7.999992 1628; setang 0 182 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 2 | `setpos 3151.143555 62.292786 1628` | `setpos 3151.143555 62.292786 1628; setang 0 182 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 3 | `setpos 3224.393555 147.542786 1628` | `setpos 3224.393555 147.542786 1628; setang 0 182 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 4 | `setpos 3019.268555 225.417786 1616.030273` | `setpos 3019.268555 225.417786 1616.030273; setang 0 182 0` | 1 | Yes | Measured feet |
| T extra 5 | `setpos 3190.518555 251.667786 1628` | `setpos 3190.518555 251.667786 1628; setang 0 182 0` | 1 | Yes | Entity origin; drops to floor |
| T extra 6 | `setpos 3078.643555 309.542786 1628` | `setpos 3078.643555 309.542786 1628; setang 0 182 0` | 1 | Yes | Entity origin; drops to floor |
| CT extra 1 | `setpos -1448.283203 618.819336 1614.03125` | `setpos -1448.283203 618.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 2 | `setpos -1600.283203 618.819336 1614.03125` | `setpos -1600.283203 618.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 3 | `setpos -1560.283203 706.819336 1614.03125` | `setpos -1560.283203 706.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 4 | `setpos -1648.283203 706.819336 1614.03125` | `setpos -1648.283203 706.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 5 | `setpos -1448.283203 794.819336 1614.03125` | `setpos -1448.283203 794.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 6 | `setpos -1600.283203 794.819336 1614.03125` | `setpos -1600.283203 794.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 7 | `setpos -1560.283203 874.819336 1614.03125` | `setpos -1560.283203 874.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 8 | `setpos -1648.283203 874.819336 1614.03125` | `setpos -1648.283203 874.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 9 | `setpos -1448.283203 954.819336 1614.03125` | `setpos -1448.283203 954.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 10 | `setpos -1524.283203 970.819336 1614.03125` | `setpos -1524.283203 970.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |
| CT extra 11 | `setpos -1600.283203 954.819336 1614.03125` | `setpos -1600.283203 954.819336 1614.03125; setang 0 270 0` | 1 | Yes | Measured feet |

</details>
<!-- /generated:maps -->

## Data

Choose an export; all three use `{ "schemaVersion": 2, "spawns": [...] }` with the same fields:

| Positions | JSON | Per-map CSV |
| --- | --- | --- |
| All entities | [spawns.json](spawns.json) | `csv/<map>.csv` |
| Competitive | [spawns-competitive.json](spawns-competitive.json) | `csv/competitive/<map>.csv` |
| Non-competitive | [spawns-non-competitive.json](spawns-non-competitive.json) | `csv/non-competitive/<map>.csv` |

The CSV folders preserve the existing all-spawns paths and let you choose a subset without filtering records. Nulls are empty in CSV. `maps/<map>.svg` has the diagrams.
[angle-evidence.json](angle-evidence.json) records every entity, its map archive hash, and the competitive demo checks.

| Field | Meaning |
| --- | --- |
| `map`, `side`, `label` | Map slug, `t` / `ct`, and a competitive or extra spawn label. |
| `competitive` | Whether the entity belongs to the enabled five-player priority selection below. |
| `hammerId` | Entity ID within this map build. |
| `priority`, `enabled`, `targetname` | Authored priority tier, initial enabled state, and entity group name (empty if unnamed). |
| `x`, `y`, `z` | World position: measured player feet when available, otherwise the entity origin. No eye-height offset. |
| `zStatus` | `observed-feet` (5v5 demo measurement), `published-lineup-feet` (published command), or `entity-origin-unsettled` (player drops to floor; settled feet height unknown). |
| `pitch`, `yaw` | Spawn facing in degrees, from demo checks or authored entity angles. |
| `angleStatus` | `runtime-verified` (matching first-tick pro-demo sample), `map-entity` (authored angles), or `unverified` (angles and combined command are null). |
| `setpos` | Position command, up to six decimals like setpos.gg. |
| `setposSetang` | Position and facing command. |
| `url` | Published competitive spawn page, or `null`; extras have no numbered site page. |

Positions come from player feet observed in 5v5 demos, published lineup commands, and map entity origins. Twelve Cache extras match feet measurements in the older observed registry by side and x/y; their heights are retained. Unmeasured entity heights are never replaced with guessed floor heights. Angles for extras come directly from the entity's full pitch/yaw/roll and have status `map-entity`.

### Priority and modes

The installed-map audit (Steam build 25947352, 2026-10-15) selects competitive entities by side: enabled only, ascending priority tiers until at least five positions fit, retaining the whole final tier. Every competitive entity here is priority 0. This is a pool of possible positions, not a claim that every position is occupied in each 5v5 round.

The enabled extras are lower-preference tiers: priority 1 on all seven maps, plus priority 2 for Ancient CT. They provide capacity beyond the five-player pool, relevant to larger lobbies such as Casual. The evidence establishes their priority and enabled state; it does not contain Casual runtime samples or verify a particular mode's player limit.

Inferno and Nuke also each contain eight initially disabled priority-0 entities named `[PR#]spawnpoints.2v2`. We include them as extras and keep their group and enabled state explicit. The map-authored name identifies a 2v2 group; these are not enabled overflow positions, and the audit does not establish current Wingman availability. Commands can still TP to their coordinates on a practice server.

<!-- generated:coverage -->
231 entities: 100 competitive and 131 non-competitive (16 disabled 2v2 entities). 97 directions were checked against the first tick after spawning in pro demos; 134 use authored map angles. 112 positions have measured feet heights; 119 use entity origins and drop to the floor.
<!-- /generated:coverage -->

## Numbering

Each side starts at 1 and follows [setpos.gg](https://setpos.gg).
Face the team's general exit: count left to right across a wide spawn, or front to back through a deep one.
Ties go front first across, left first back. All diagrams are north-up.
Competitive labels are unchanged. Extras form a separate group per side, starting at `T extra 1` / `CT extra 1`, using that same spatial convention and the competitive team's exit heading. Enabled and disabled extras share this sequence; separate diagram panels keep distant 2v2 groups readable.

## Credit

Use it for anything. Credit [Spawn data by setpos.gg](https://setpos.gg) is all we ask.
The licence stays CC BY 4.0. As licensor, we waive the requirements to link the licence and list changes.

In game, the [setpos.gg practice maps](https://setpos.gg/workshop) let you TP to any spawn and show the lineups from it. The diagrams use [cs2-minimaps](https://github.com/setposgg/cs2-minimaps).

Counter-Strike 2 is a trademark of Valve Corporation. Not affiliated with Valve.
