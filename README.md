# dishwasher-check

Daily amazon.de price check for a shortlist of 9 dishwashers (60 cm, class A/B, cutlery drawer, fully integrated or under-counter).

- `prices.json`: the 9 models with their price history. A scheduled Claude Code cloud routine appends one entry per model per day (via Apify) and commits it, so `git log -p prices.json` shows every change.
- Baseline: prices as of 2026-11-14.
- This repo is public. Keep only product data here.
