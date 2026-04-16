Delhi Air Quality Analysis (January 2023)
📊 Project Overview
A comprehensive data analysis of hourly air quality measurements in Delhi during January 2023. This project examines pollution patterns, pollutant relationships, and temporal trends to uncover the severity of Delhi's winter air crisis.

📁 Dataset
Source: Hourly AQI measurements for January 2023

Time Period: January 1–24, 2023 (561 hourly records)

Pollutants Measured: CO, NO, NO₂, O₃, SO₂, PM2.5, PM10, NH₃

🔍 Key Analyses Performed
1. Temporal Pollution Patterns
Hourly AQI trends – Peak pollution occurs at 3 PM (avg AQI: 449)

AQI category distribution – 63.6% Severe, 32.6% Very Poor

Worst day – January 1st, with multiple hours at AQI 500

2. Pollutant Behavior Analysis
Distribution analysis – PM2.5 shows right-skewed distribution (mean > median)

Correlation study – Strong linear relationship between PM2.5 and PM10 (r = 0.98)

Outlier detection – SO₂ and NH₃ show most extreme spikes (skewness > 3)

3. Visualizations Created
Line chart: AQI trend over time

Bar charts: Category distribution & hourly patterns

Box plots: Pollutant spread comparison

Scatter plot: PM2.5 vs PM10 correlation

Histogram: PM2.5 distribution

Pie chart: Time percentage per AQI category

📈 Key Findings
Metric	Value
Average AQI	412.73 (Severe)
Hours in Severe/Very Poor	96.2%
Best hour (avg)	8 AM (341 AQI)
Worst hour (avg)	3 PM (449 AQI)
PM2.5 avg	358.26 µg/m³
PM2.5 median	301.17 µg/m³
PM2.5-PM10 correlation	0.98
🛠️ Tools & Libraries Used
Python 3.x

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Scikit-learn – Scaling for box plots
💡 Key Insights
No safe hours – Even the "best" hour (8 AM) averaged 341 AQI (Very Poor)

PM2.5 concentration is 24× WHO safe limit (358 vs 15 µg/m³)

PM10 reduction would automatically reduce PM2.5 (high correlation)

Afternoon peak suggests traffic + secondary pollutant formation

🚀 How to Run
Clone repository

Install dependencies: pip install pandas numpy matplotlib seaborn scikit-learn

Run Jupyter notebook: jupyter notebook AQI_Analysis_Delhi_January_2023.ipynb
 Conclusion
Delhi's January air quality represents a public health emergency with 96% of hours in Severe/Very Poor categories. These findings support urgent policy interventions including vehicle restrictions, school closures, and public health advisories.
