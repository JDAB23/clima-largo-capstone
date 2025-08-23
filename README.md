# 🌤️ Largo Weather KPIs

This project analyzes and visualizes weather data for Largo (Florida), using data from the [Open-Meteo API](https://open-meteo.com) and interactive dashboards in Looker Studio.

---

## 📂 Data
- **Source**: Open-Meteo API  
- **Period covered**: last 5 weeks  
- **Key variables**: apparent temperature, humidity, heat index, rain probability  

---

## 📊 Main KPIs
1. % of hours with Heat Index ≥ 100°F per month  
2. Number of days with Rain Probability ≥ 60%  
3. Comfort windows (apparent temperature 68°F–82°F) by time of day  

---

## 📊 Results (Auto-generated snapshot)

**KPI1 — % of hours with Heat Index ≥100°F (by month)**  
See details in [`data/kpi_hours_HI100_per_month.csv`](data/kpi_hours_HI100_per_month.csv)

**KPI2 — % of days with rain probability ≥60% (overall)**  
See [`data/kpi_days_rain60.csv`](data/kpi_days_rain60.csv)

**KPI3 — % of comfort hours by time block**  
See details in [`data/kpi_comfort_by_timeblock.csv`](data/kpi_comfort_by_timeblock.csv)

### Chart Previews
![Heat Index per Month](figs/kpi1_heatindex_line.png)  
![Comfort by Time Block](figs/kpi3_comfort_bar.png)  
![Last 7 Days — Apparent Temperature](figs/temp_last7days.png)  

---

## 📈 Visualization Examples
![Heat Index Evolution](charts/heat_index_line.png)  
*Heat Index evolution per hour — last 5 weeks*

![Comfort Windows](charts/comfort_bars.png)  
*Comfort windows by time of day*

---

## 🌐 Interactive Dashboard
👉 [Largo Weather KPIs — Live Dashboard](https://lookerstudio.google.com/your-link-here)

---

## 🚀 Technologies
- Python (requests, pandas, matplotlib)  
- Google Colab  
- GitHub  
- Looker Studio  

---

## 👤 Author
Project by Daniel Acosta (https://www.linkedin.com/in/danyacosta)  

 
        
