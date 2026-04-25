# 📔 Project Reflections & Technical Growth
> *A journey through data, machine learning, climate science, and the pursuit of academic excellence (1990–2023).*

---

## 🌟 Overview
This document serves as a "Behind the Scenes" look at the **Global Compound Climate Risk Regimes** project. Beyond the code and the graphs, this is a record of the challenges I overcame and the professional skills I built during the research process.

---

## 📊 Dataset Deep-Dive
Understanding the data was the most critical part of this research. I worked with multi-dimensional datasets to identify compound risks.


### 🗺️ ECMWF ERA5 Climate Reanalysis
From the ERA5 monthly surface-level datasets, we have taken 6 variables: t2m, tcc, si10, tp, ssr, and avg_tprate. Here is the analysis of the dataset: 

t2m(2-meter temperature): It is used as the primary thermodynamic state variable to define compound climate risk. It is considered because human beings and all living beings mainly breathe in this region, it is used to track global warming trends, and most crops (like rice or wheat) exist within this 0–2 meter zone. Its unit is(k). 



tp(Total Precipitation): tp indicates the total amount of water on the Earth's surface because some places have a tropical monsoon or long-lasting rainfall or snowfall. Somewhere in the world, tp is inversely related to t2m. It is highly important to calculate the moisture-deficit component(the amount of water required to bring back the soil moisture) of MCSI(Multivariate Climate State Index).


tcc(Total Cloud Coverage): tcc has Daytime and night time effect. 
In Daytime - High tcc can reflect the solar radiation to space and helps the surface become cooler (It is called Albedo System). 

