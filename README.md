
# Philadelphia Police Stops – Exploratory Data Analysis (EDA) 🚔📊

This repository presents an Exploratory Data Analysis (EDA) of vehicle and pedestrian stops conducted by the Philadelphia Police Department from 2014 to 2018, using standardized data from the **[Stanford Open Policing Project (OPP)](https://openpolicing.stanford.edu/data/)**.

## 📁 Dataset

The dataset was extracted from the Open Policing Project and focuses on police stops in **Philadelphia from 2014 to 2018**. Each row represents a unique stop and contains information such as:

- `date`, `time`, `location` of the stop  
- `subject_age`, `subject_race`, `subject_sex`: demographics of the person stopped  
- `search_conducted`, `contraband_found`, `arrest_made`: stop outcomes  


## 🛠️ Tools and Libraries

- Python   
- `Pandas` for data manipulation  
- `NumPy` for numerical operations  
- `Matplotlib` and `Seaborn` for visualization  
- `Folium` and `GeoJSON` for geographical mapping  
- `Statsmodels` for seasonal decomposition of time series  

## 📌 EDA Objectives

- Import and preprocess the data using Pandas
- Perform initial data cleaning and transformation
- Generate descriptive statistics for key features
- Visualize stop distributions by race, gender, and year
- Identify trends over time in police practices
- Explore disparities in search and arrest outcomes
- Visualize stop density across Philadelphia using interactive maps


## 📊 Key Findings

- **Racial Disparities**: Black individuals were significantly overrepresented in the stop records across all outcomes (stops, searches, arrests, and contraband found), suggesting systemic racial bias in enforcement.
- **Age and Gender Patterns**: Young adults, especially males in their 20s and 30s, experienced the highest frequency of stops. Men, in general, were stopped, searched, and arrested far more often than women.
- **Geographic Hotspots**: District 24, particularly the Kensington area, emerged as the most heavily policed region, likely influenced by socio-economic and public health challenges. High-density areas and major roads (e.g., Market Street, Broad Street) also showed elevated stop activity.
- **Temporal Trends**: Stops peaked during the evening hours (17:00–21:00), especially on Fridays and Saturdays. Seasonal spikes were observed in spring months (March–May), likely due to increased mobility and enforcement operations.
- **Pedestrian vs. Vehicle Stops**: While vehicle stops were most frequent, pedestrian stops disproportionately targeted young men of color.
- **Outcome Effectiveness**: Most stops did not result in arrests or discovery of contraband, raising questions about the efficacy and justification of these tactics.

## 🗺️ Visual Highlights

- Time series plots showing seasonal trends in stop frequency
- Histograms and boxplots of age distributions by race and gender
- Interactive maps of stop density using Folium


## 💡 Conclusion

This project offers insight into the patterns and disparities in police stop data from Philadelphia. The combination of statistical analysis and geographical visualization reveals potential systemic biases and can support further public policy discussion and research on law enforcement practices.
