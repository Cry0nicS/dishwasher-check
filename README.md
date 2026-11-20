# dishwasher-check

Daily amazon.de price check for a shortlist of 9 dishwashers (60 cm, class A/B, cutlery drawer, fully integrated or under-counter).

A second list, `lamps`, tracks 3 smart floor lamps (Govee, SwitchBot) with Black Friday target prices (`target_min`/`target_max`). Govee Floor Lamp 2 (H607C) is not listed on amazon.de yet and is not tracked.

Two more lists, `chargers` (3 multi-port USB-C chargers with PPS) and `cables` (3 cheap 5A e-marked USB-C cables), are tracked from 2026-11-17 to spot Black Friday drops. No targets; the report flags new lows.

A fifth list, `minipcs`, tracks 5 new mini PCs for Home Assistant (GMKtec G5 N97, AWOW AK10 N95, GMKtec G3 Ultra, GMKtec G11, Beelink S12 Pro N100) from 2026-11-20. No targets; the report flags new lows and any price at or below 220 EUR. Out-of-stock items get no price recorded.

- `prices.json`: the 9 models with their price history. A scheduled Claude Code cloud routine appends one entry per model per day (via Apify) and commits it, so `git log -p prices.json` shows every change.
- Baseline: prices as of 2026-11-14.
- This repo is public. Keep only product data here.
