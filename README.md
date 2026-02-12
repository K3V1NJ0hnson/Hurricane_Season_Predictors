## Hurricane Predictor: Geospatial Analysis of Atlantic Landfalls
A climate data science project analyzing global environmental variables to identify the strongest indicators of hurricane landfalls in North America.

## 🎯 Project Objective
The goal of this project was to determine if specific environmental factors—such as sunspot activity, sea surface temperatures, and regional bands—could reliably predict the frequency of hurricane landfalls.

## 📊 The Dataset
Source: NOAA National Centers for Environmental Information (NCEI)

Features: Sunspot counts, Sea Surface Temperatures (SST), and geospatial storm coordinates.

Scope: Long-term historical data preprocessed for time-series and spatial analysis.

## 🛠️ Technical Stack
Core Tools: Python (Pandas, NumPy)

Geospatial Analysis: GeoPandas, xarray

Data Visualization: Matplotlib, Seaborn

Techniques: Feature Engineering, Exploratory Data Analysis (EDA), Latitude/Longitude Region Banding.

## 🏗️ Methodology
Data Preprocessing & Engineering: Cleaned raw NOAA climate files and engineered new features from longitudinal/latitudinal coordinates.

Region Banding: Created distinct geographical "Region Bands" based on latitude and longitude to isolate the Main Development Region (MDR) of the Atlantic.

Variable Testing: Evaluated four primary variables:

Sea Surface Temperature (SST)

Sunspot Activity Count

Regional Atmospheric Pressure

Humidity Levels

Visualizations: Generated heatmaps and spatial plots to correlate environmental spikes with landfall frequency.

## 📈 Key Findings & Conclusion
After performing a correlation analysis across the variables:

The Winner: Main Development Region (MDR) Temperature was the strongest indicator of hurricane landfalls.

Other Factors: While sunspot counts were analyzed, they showed significantly less correlation compared to regional ocean temperatures.

Final Insight: Warming temperatures in specific geographical bands are a high-confidence precursor to increased hurricane activity.

## 🧪 Future Improvements
[ ] Integrate Machine Learning (Random Forest or LSTM) to build a predictive model.

[ ] Incorporate El Niño Southern Oscillation (ENSO) data for higher accuracy.

[ ] Deploy a dynamic dashboard using Streamlit to visualize historical storm paths.
