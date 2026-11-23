# dishwasher-check

Daily amazon.de price check for a shortlist of 5 dishwashers (60 cm, class A/B, cutlery drawer, fully integrated or under-counter), ranked as below.

| Rank | Model | Energy / 100 cycles | Noise (Silence) | Drying | Baskets & extras | Standout programs / buttons |
|---|---|---|---|---|---|---|
| 1 (Tie) | [Bosch SMV4ECX32E](https://www.amazon.de/dp/B0DMFPBDN7) (fully integrated) | A (54 kWh) | 42 dB (41 dB) | Auto-open + Heat Exchanger | Max Flex + Extra Clean Zone, InfoLight | Silence 50°C, 1h 65°C, SpeedPerfect+ |
| 1 (Tie) | [Bosch SMU4ECS32E](https://www.amazon.de/dp/B0DMFS9VGB) (under-counter, steel front) | A (54 kWh) | 42 dB (41 dB) | Auto-open + Heat Exchanger | Max Flex + Extra Clean Zone, Front Display | Silence 50°C, 1h 65°C, SpeedPerfect+ |
| 3 | [Bosch SMV4EVX08E](https://www.amazon.de/dp/B0DFQDYFXC) (fully integrated) | B (65 kWh) | 44 dB (43 dB) | Auto-open + Heat Exchanger | VarioFlex, InfoLight | Silence 50°C, 1h 65°C, Half Load |
| 4 | [Siemens SN63EX06VE](https://www.amazon.de/dp/B0DFMHBHWH) (fully integrated) | B (65 kWh) | 44 dB (no Silence button) | Auto-open + Heat Exchanger | varioFlex, infoLight | intensiveZone, Speed 45°C, 1h 65°C |
| 5 | [NEFF S155EVX04E](https://www.amazon.de/dp/B0DFHKVDTK) (fully integrated) | B (65 kWh) | 44 dB (Silence via app) | Auto-open + Heat Exchanger | Flex II (VarioFlex equiv.), InfoLight | Glass 40°C, Classic 60°C, Chef 70°C |

A second list, `chargers` (3 multi-port USB-C chargers with PPS plus the UGREEN Nexode Pro 160W 5-Port with Smart Display, added 2026-11-23), is tracked from 2026-11-17 to spot Black Friday drops. No targets; the report flags new lows.

A third list, `minipcs`, tracks 5 new mini PCs for Home Assistant (GMKtec G5 N97, AWOW AK10 N95, GMKtec G3 Ultra, GMKtec G11, Beelink S12 Pro N100) from 2026-11-20. No targets; the report flags new lows and any price at or below 220 EUR. Out-of-stock items get no price recorded.

A fourth list, `bookshelves`, tracks 2 open industrial bookshelves under 100 cm width (Bealife 98 cm, preferred; Tribesigns 70 cm) from 2026-11-21. No targets; the report flags new lows, and any drop on the Bealife is the one to highlight.

- `prices.json`: the 5 dishwashers with their price history. A scheduled Claude Code cloud routine appends one entry per model per day (via Apify) and commits it, so `git log -p prices.json` shows every change.
- Baseline: prices as of 2026-11-14.
- This repo is public. Keep only product data here.
