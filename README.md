# NSW Electricity Demand & Price Analysis (2020-2026)

Analysis of NSW electricity demand and spot price trends using real AEMO National Electricity Market (NEM) data, with insights for grid planning and infrastructure investment.

## Business Context
Transgrid operates the NSW and ACT high voltage transmission network. Understanding peak demand patterns and price volatility is critical for transmission infrastructure planning and investment decisions.

## Questions Answered
- How has NSW peak demand changed across January 2020-2026?
- What does the daily load profile look like and when are critical peak windows?
- How volatile are spot prices and when do grid stress events occur?
- What are the implications for transmission infrastructure planning?

## Data Source
AEMO Aggregated Price and Demand Data - NEM Historical (NSW1 region)
5-minute resolution, January data 2020-2026

## Tech Stack
- Python (Pandas, Matplotlib)
- AEMO NEM Data

## Key Findings
- Evening peak (17:00-20:00) is the most critical window for grid stability
- Significant year-to-year demand variation driven by temperature extremes
- Price spikes reveal periods of genuine grid stress and infrastructure gaps
- Trends directly inform Transgrid's long-term transmission investment planning

## Files
| File | Description |
|------|-------------|
| `notebook/nsw_electricity_analysis.ipynb` | Full analysis notebook |
| `data/PRICE_AND_DEMAND_YYYYMM_NSW1.csv` | AEMO NEM data files (2020-2026) |
| `outputs/` | Generated visualisations |