# NCR Minimum-Wage Grocery Basket Optimizer

## Problem Statement
I want to answer: "What is the lowest-cost combination of commonly available NCR grocery items that meets a single adult's daily nutrient requirements (per FNRI's Philippine Dietary Reference Intakes), and what percentage of the NCR minimum wage does that basket consume?"

## Audience
This project is for a single, minimum-wage-earning adult in NCR who wants to know whether their income can realistically cover nutritionally adequate food — and if not, by how much it falls short.

## KPI or Key Metric
The main metric I want to track is **% of NCR minimum wage required to afford a nutritionally-adequate grocery basket** (basket cost ÷ minimum wage × 100).

## Likely Data Source
I will explore:
- **PSA OpenSTAT Retail Prices** (https://openstat.psa.gov.ph/Database/Prices/Retail-Prices) — for grocery item prices, sourced from PSA's Retail Price Survey.
- **FNRI Philippine Dietary Reference Intakes (PDRI)** (https://www.fnri.dost.gov.ph/index.php/tools-and-standard/philippine-dietary-reference-intakes-pdri) — for the official nutrient requirement targets a basket must meet.

These two sources will need to be combined: prices give the cost side, PDRI gives the nutritional constraint side. I expect to also need a Philippine Food Composition Table to map grocery items to their nutrient content, which I'll source in a later milestone.

## Possible Final Dashboard
The dashboard should help the audience quickly see whether a minimum-wage income can cover a nutritionally adequate basket of food, what the actual cost gap (in pesos and in % of wage) looks like, and — eventually — which specific nutrients are hardest to afford so cheaper substitutions can be suggested.

## Future Directions
Once the core analysis above is working, I plan to extend it to:
- Comparing the nutrient-adequate basket cost across multiple regions, not just NCR.
- Breaking down the affordability gap by individual nutrient (e.g., iron, protein, calcium) instead of just total cost.
- Tracking how the cost-vs-wage gap has changed over the past 5 years.
