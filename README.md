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

 ## Preliminary Results

**KPI1 — % of hours with Heat Index ≥100°F**
month
2025-07-01    25.0
2025-08-01    11.1

**KPI2 — % of days with rain probability ≥60%**
Overall: 10.8%

**KPI3 — % of comfort hours by time block**
time_block
morning      5.4
afternoon    0.9
night        8.6

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

 
        
