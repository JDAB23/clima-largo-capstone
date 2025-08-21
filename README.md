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

**Structure**
