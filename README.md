# Largo (FL) Climate — Mini Capstone (Beginner)

**Question:** Which time-of-day windows offer the best thermal comfort in Largo, FL?

**KPIs v1**
1) % of hours with *apparent_temperature* ≥ 100 °F per month  
2) % of days with precipitation probability ≥ 60%  
3) % of hours in “comfort” by time block (72–90 °F and RH < 70%)

**Data**
- Source: Open-Meteo (no API key) · Timezone: America/New_York  
- Generated file: `data/largo_hourly.csv` (from Google Colab)

**Reproduce (Colab)**
1. Run the fetch cell (provided in the notebook).  
2. It generates `data/largo_hourly.csv` and `data/largo_raw.json`.  
3. Run the KPI cell to generate results:  
   - `data/kpi_hours_HI100_per_month.csv`  
   - `data/kpi_days_rain60.csv`  
   - `data/kpi_comfort_by_timeblock.csv`  
4. Run the plotting cell to generate charts in `figs/`:  
   - `kpi1_heatindex_line.png`  
   - `kpi3_comfort_pie.png`  
   - `temp_last7days.png`

**Structure**
data/ # CSV/JSON (raw + KPIs)
figs/ # Charts (PNG)
notebooks/ # Jupyter/Colab notebooks (EDA + KPIs)
src/ # Scripts (optional)
README.md # Project documentation

## Preliminary Results (August 2025)
**KPI1 — % of hours with Heat Index ≥100°F**
- July 2025: 20.0%
- August 2025: 11.4%

**KPI2 — % of days with rain probability ≥60%**
- Overall: 13.5%

**KPI3 — % of comfort hours by time block**
- Morning: 1.4%
- Afternoon: 0.5%
- Night: 3.8%

**Insights**
- July showed higher extreme heat (20%) than August (11.4%).
- Only 13.5% of days had high rain probability, indicating relatively few rainy days.
- Comfort hours were limited overall; nights (3.8%) slightly outperform mornings (1.4%) and afternoons (0.5%).
