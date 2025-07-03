# Exploratory Rainfall Regression Project

This project explores historical precipitation data from weather stations in **South East Queensland**, focusing on stations with **110+ years** of continuous data. It uses spatial filtering, map-based visualisation, and exploratory analysis to understand long-term rainfall patterns.

## 📊 Project Goals
- Filter station metadata for long-term precipitation records
- Map weather stations with geospatial and elevation data
- Join station metadata with daily rainfall observations
- Summarise and visualise rainfall distributions by station

## 🛠️ Tools & Libraries
- R
- dplyr
- ggplot2
- ggmap (Stadia Maps API)

## 🗺️ Visual Outputs
- Elevation-colored station scatter plots
- Terrain maps with overlaid station markers
- Boxplots (standard and log-scaled) of rainfall distributions

## 📁 Files
- `Exploratory-Regression-Project.Rmd`: Cleaned and structured R Markdown report
- CSV files: `ghcnd_meta_data.csv`, `station_data.csv`
- `index.html`: Rendered project report (GitHub Pages)

## 🧠 Key Insights
- Only a small number of stations meet the 110-year data requirement
- One metadata elevation outlier (`-999`) was identified and removed
- Rainfall data is highly skewed; log-scaling improves interpretability

## 🔄 Reproducibility
To run this project:
1. Clone the repository
2. Add your Stadia Maps API key to `.Renviron`
3. Open the `.Rmd` file in RStudio
4. Knit to HTML to view results

---

Created as part of a data science portfolio project, demonstrating data wrangling, geospatial visualisation, and exploratory regression analysis.
