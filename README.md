<<<<<<< HEAD
# Air Quality Analysis in Dhaka

## Project Overview
This project analyzes air quality data from Dhaka between 2017 and 2023. It involves:
- Cleaning and preprocessing datasets.
- Exploring trends and seasonal patterns in AQI data.
- Visualizing data through various charts and heatmaps.
- Providing actionable insights into air quality trends.

## Citation information 

The data is cited from: 
AirNow. (2024). Data source: U.S. embassies and consulates. Retrieved December 01, 2024, from https://www.airnow.gov/international/us-embassies-and-consulates/#Bangladesh$Dhaka

## Features of the final dataset

| **Column Name**         | **Description**                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| DateTime                | Timestamp in hourly intervals (YYYY-MM-DD HH:MM:SS). Serves as the index.      |
| Site                    | Location where the measurements were recorded (e.g., Dhaka).                  |
| Parameter               | Air quality parameter measured (PM2.5 - Principal).                           |
| Year                    | Year of the measurement (e.g., 2017, 2023).                                   |
| Month                   | Month of the measurement (1–12).                                              |
| Day                     | Day of the month (1–31).                                                      |
| Hour                    | Hour of the day (0–23, in 24-hour format).                                    |
| NowCast Conc.           | Calculated NowCast concentration of PM2.5 in micrograms per cubic meter (μg/m³).|
| AQI                     | Air Quality Index value corresponding to PM2.5 concentration.                 |
| AQI Category            | AQI classification based on thresholds: "Good," "Moderate," "Unhealthy," etc. |
| Raw Conc.               | Unadjusted raw concentration of PM2.5 (μg/m³).                                |
| Conc. Unit              | Unit of concentration measurement (UG/M3: Micrograms per cubic meter).        |
| Duration                | Duration of measurement (fixed at 1 Hour).                                    |
| QC Name                 | Quality Control classification of the data point (e.g., "Valid").             |
| AQI_7Day_RollingAvg     | 7-day rolling average of AQI, calculated for trend smoothing (168 hours).     |

## Notebook Inlcudes:

- Merging and cleaning datasets for multiple years.
- Handling missing values, duplicates, and invalid data.
- Categorizing AQI into levels (Good, Moderate, Hazardous, etc.).
- Creating rolling averages and seasonal decomposition of AQI.
- Visualizations:
  - Correlation heatmaps.
  - AQI trends over time.
  - Scatter plots of concentration vs AQI.

### 2. MongoDB Queries Notebook:
This notebook demonstrates basic MongoDB queries, including:
- Connecting to a MongoDB database.
- Creating, reading, updating, and deleting documents (CRUD operations).
- Querying data using filters and aggregations.


## Explore some of the key visualizations of the project see:

[View Interactive Tableau Dashboard](https://public.tableau.com/views/TableauVisualizations_17343956476190/AverageAQIovertheyears?:showVizHome=no)


## Folder Structure
air-quality-analysis/
├── datasets/                # Datasets folder
├── images/                  # Images folder
├── notebooks/               # Jupyter Notebook                  
├── README.md
├── requirements.txt         # Dependencies
└── .gitignore

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/air-quality-analysis.git
   cd air-quality-analysis

2. Install dependencies:

pip install -r requirements.txt

3. Run the Jupyter notebook :)

jupyter notebook notebooks/air_quality_analysis.ipynb





For questions or feedback, contact: [shafi.hussain65@gmail.com]



=======
# Air_Quality_Analysis_Syed
This project analyzes air quality data from Dhaka between 2017 and 2023. It includes visualizations and key analysis. The code can be used for various functionality.
>>>>>>> 8eae6043a63d5721c04eb95b4aa8db36a0fe1af8
