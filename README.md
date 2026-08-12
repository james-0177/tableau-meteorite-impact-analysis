# Falling from the Sky: A Global Meteorite Impact Analysis

![Dashboard Overview](/assets/dashboard_preview.png)

## 📌 Executive Summary
An interactive 8-tab Tableau analytical application exploring the spatial, temporal, and mass distributions of over 45,000 recorded meteorite impact landings worldwide. This project highlights geospatial data modeling, logarithmic statistical normalization, and historical time-series analysis.

👉 **[View the Live Interactive Dashboard on Tableau Public](https://public.tableau.com/views/JamesPinkston_A7FinalProject/Goal1-GlobalDistribution?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🛠️ Data Architecture & Methodology
* **Data Source:** NASA Open Data Portal & The Meteoritical Society (45,000+ observations, 860 CE – 2013 CE). -> [DATASET](https://www.kaggle.com/datasets/sujaykapadnis/meteorites-dataset?select=meteorites.csv)
* **Mass Distribution Normalization:** Raw meteorite masses span multiple orders of magnitude (from <1g to 60,000,000g). Applied a $\log_{10}(\text{Mass})$ transformation to eliminate extreme right-skewness and visualize frequency distribution cleanly.
* **Geospatial Mapping:** Utilized Tableau’s native spatial mapping and coordinate plotting to visualize global landing density, isolate coastal/desert recovery zones, and map the top 10 largest historic impacts.
* **Temporal Trend Analysis:** Mapped annual landing counts across a 1,000+ year timeline to isolate discovery/reporting bias vs. physical impact frequency.

---

## 📊 Core Research Questions Addressed
1. **Global Spatial Distribution:** What is the overall global distribution of meteorite impacts (by year)? Where have the largest meteorites impacted globally (by mass)?
2. **Mass Profiling:** How are the masses of meteorites distributed globally (using a $\log_{10}$ logarithmic scale)?
3. **Time-Series Evolution:** How have meteorite impacts changed over time? Is there a relationship between mass of the meteorite and the year of impact?
4. **Global Distribution - Historical Top-10:** What are the top 10 largest meteorite impacts throughout history, and where did they impact?

---
