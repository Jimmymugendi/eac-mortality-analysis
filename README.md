# EAC Mortality Analysis

This project presents a geospatial and temporal analysis of under-five and neonatal mortality rates across countries in the East African Community (EAC). The analysis leverages data visualization and mapping techniques in **R** and abit of **Python** to highlight regional disparities and trends over time.

## 📊 Project Objectives

- Visualize and compare **Under-Five Mortality Rate** and **Neonatal Mortality Rate** across EAC countries.
- Create **choropleth maps** using individual shapefiles to show the most recent data.
- Analyze **trends over time** for each mortality indicator.
- Identify countries with the **highest mortality rates** in the latest year.
  
## 🌍 Countries Included

- Burundi  
- Democratic Republic of the Congo  
- Kenya  
- Rwanda  
- Somalia  
- South Sudan  
- Uganda  
- United Republic of Tanzania

## 🛠️ Tools Used

- `R`, `ggplot2`, `sf`, `dplyr`, `viridis`
- GADM country shapefiles (Level 0 boundaries)
- Custom R functions for plotting and summarization

## 🔍 Insights

- Temporal plots reveal a general **decline in mortality** across most EAC countries.
- Choropleths highlight **geographic disparities**, with some countries persistently exhibiting higher rates.
- Identified the countries with the **highest current mortality burdens**, informing where targeted health interventions may be needed most.

## 🚀 How to Run

1. Clone the repo:
    ```bash
    git clone https://github.com/jimmymugendi/eac-mortality-analysis.git
    ```
2. Open `jimmy_Mugendi.RMD` in RStudio.
3. Ensure all dependencies are installed:
    ```r
    install.packages(c("sf", "tidyverse", "ggplot2", "viridis"))
    ```
4. Run the script to generate maps and plots.

## 🧠 Author

**Jimmy Mugendi**  
_Data Scientist analysing about health analytics and spatial modeling._

---

## 📄 License

MIT License
