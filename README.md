# Falling from the Sky: A Global Meteorite Impact Analysis

![Dashboard Overview]()

## 📌 Executive Summary
An interactive 8-tab Tableau analytical application exploring the spatial, temporal, and mass distributions of over 45,000 recorded meteorite impact landings worldwide. This project highlights geospatial data modeling, logarithmic statistical normalization, and historical time-series analysis.

👉 **[View the Live Interactive Dashboard on Tableau Public](https://public.tableau.com/views/JamesPinkston_A7FinalProject/Goal1-GlobalDistribution?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🛠️ Data Architecture & Methodology
* **Data Source:** NASA Open Data Portal & The Meteoritical Society (45,000+ observations, 860 CE – 2013 CE).
* **Mass Distribution Normalization:** Raw meteorite masses span multiple orders of magnitude (from <1g to 60,000,000g). Applied a $\log_{10}(\text{Mass})$ transformation to eliminate extreme right-skewness and visualize frequency distribution cleanly.
* **Geospatial Mapping:** Utilized Tableau’s native spatial mapping and coordinate plotting to visualize global landing density, isolate coastal/desert recovery zones, and map the top 10 largest historic impacts.
* **Temporal Trend Analysis:** Mapped annual landing counts across a 1,000+ year timeline to isolate discovery/reporting bias vs. physical impact frequency.

---

## 📊 Core Research Questions Addressed
1. **Global Spatial Distribution:** Where are recorded meteorite impacts clustered worldwide?
2. **Mass Profiling:** How are payload masses distributed on a $\log_{10}$ logarithmic scale?
3. **Historical Top-10:** Where did the largest recorded payloads impact (e.g., Cape York 1818, Campo del Cielo 1575, Gibeon 1836)?
4. **Time-Series Evolution:** Why does the recorded landing volume spike exponentially after 1950? (Isolating search effort/technology from atmospheric frequency).

---

## 💾 Repository Structure
