# EV Charging Station Optimization in Connecticut

## Overview
This project analyzes and optimizes the placement of electric vehicle (EV) charging stations in Connecticut using **Geospatial Data Science** and **Machine Learning**. The study integrates spatial datasets, clustering algorithms, and predictive modeling to guide sustainable infrastructure planning.

## Objectives
- Map the current EV charging station distribution.
- Identify demand clusters using spatial data.
- Predict future charging needs with machine learning models.
- Recommend optimal station placement for accessibility and coverage.

## Repository Structure
```
EV-Charging-Station-Optimization/
│
├── data/                      # Dataset(s) used in the analysis
├── notebooks/                 # Jupyter Notebook with exploratory and model workflows
├── src/                       # Python scripts for automation and modeling
├── reports/                   # Presentation slides and related documents
└── README.md
```

## Methodology
1. **Data Preprocessing:** Clean and filter spatial data of existing EV stations.  
2. **Exploratory Analysis:** Visualize geographic and demographic distribution.  
3. **Clustering (DBSCAN):** Identify underserved or high-demand zones.  
4. **Modeling (Random Forest):** Predict optimal station density and future needs.  
5. **Visualization:** Produce thematic maps for insights and planning.

## Key Results
- Uneven infrastructure distribution with urban bias.
- DBSCAN revealed new high-demand clusters along major transport corridors.
- Random Forest accurately estimated charger needs across counties.
- Strategic recommendations for highway and residential coverage balance.

## Technologies Used
- Python (pandas, numpy, scikit-learn, matplotlib, geopandas)
- Jupyter Notebook
- Geospatial libraries (folium, shapely)
- Machine Learning: DBSCAN, Random Forest
- Data Visualization and Mapping

## Author
**Muhammad Iqbal**  
📧 [iqbal.envsci@gmail.com](mailto:iqbal.envsci@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/muhammad-iqbal92) | [GitHub](https://github.com/muhammadiqbal92)

---
*This project was developed as part of a Data Science assignment to demonstrate spatial machine learning for sustainable transportation planning.*
