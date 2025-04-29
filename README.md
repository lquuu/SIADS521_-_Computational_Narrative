# 🏃‍♀️ Assignment 4: Computational Narrative with Strava Data

### 📌 Project Overview
This project is a data science exploration of my professor's personal Strava activity data, using Python and interactive visualizations with Plotly. The aim was to clean and analyze GPS-based workout data, uncover trends across running and cycling sessions, and build compelling visual narratives with interactivity and clarity in mind.

### 🔐 Data Privacy Notice
The original activity data used in this project belongs to my professor and has not been included in this repository. I have also acquired the necessary permission from my professor to publish this project. All visualizations shown are either based on anonymized sample data or are provided as screenshots only. This ensures full protection of any personal or location-based information.

### 📊 Project Highlights
- ✅ Cleaned and structured raw Strava data exported from .fit files into tidy CSVs
- 📈 Created interactive line plots of speed over time with Plotly
- 🔍 Built scatterplots with trendlines to explore relationships between metrics such as distance, duration, and pace
- 🏷️ Programmatically classified activity sessions as Running or Cycling based on maximum speed
- 📸 Included screenshots of outputs in place of raw data to protect sensitive information

### 📊 Features & Visualizations
This project uses Plotly to create rich, interactive visualizations for exploring workout trends. Due to data privacy concerns, screenshots of the following visualizations are provided in the repository:
- **Data Cleaning**: Process and analyze raw Strava CSV exports to handle missing values, outliers, and inconsistent formats.
- **Line Plots**: Display heart rate over time for each workout, revealing trends in exercise intensity across multiple sessions (e.g., July to October). These plots help identify patterns, such as increasing or decreasing heart rate trends during rides. Leverages Plotly for dynamic, web-based visualizations with hover details and zoom functionality.
- **Scatterplots with Trendlines**: Show relationships between metrics, such as heart rate versus workout duration, with a regression line to indicate correlation strength. These plots highlight how intensity varies with ride length.
- **Histograms**: Visualize the frequency of heart rate zones across workouts, showing how often each zone (e.g., Fat-Burning, Aerobic, Cardio) was achieved. These plots help quantify the dominance of specific intensity levels in the dataset.
- **Violin Plots**: Illustrate the distribution of heart rate zones (e.g., Aerobic, Cardio, Fat-Burning) across workouts, showing the spread and density of heart rate values. These plots are useful for comparing workout intensity distributions over time (i.e., monthly basis).
- **Ridgeline Plots**: Display heart rate distributions for multiple time periods (e.g., monthly from July to October) in a stacked, overlapping format. These plots highlight shifts in heart rate zone patterns, such as a transition from Fat-Burning to Aerobic/Cardio zones across months.

### 🛠️ Tools and Technologies
- Python 3.8+
- Libraries: pandas, plotly, numpy
- Jupyter Notebooks
