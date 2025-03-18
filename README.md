🚲 Yulu Bike-Sharing Demand Analysis
📌 Overview
This project provides an in-depth analysis of a bike-sharing dataset to explore how external factors like weather conditions, seasons, holidays, and working days influence the demand for bike rentals. By applying statistical analysis and creating visualizations, the project uncovers key insights that can help optimize resource management in a bike-sharing system.

📊 Objectives
Analyze the distribution of bike rentals across different conditions.
Identify patterns and relationships between external factors and bike demand.
Perform hypothesis testing to validate significant differences in rental demand.
Provide actionable insights for business decisions.
🛠 Tools & Libraries
Python for data analysis and visualization
Pandas for data manipulation
Seaborn and Matplotlib for data visualization
SciPy for statistical hypothesis testing
📂 Dataset
The dataset consists of 10,886 observations and contains the following key features:

datetime: Timestamp of bike rental
season: Season (Spring, Summer, Fall, Winter)
holiday: Whether it was a holiday or not
workingday: Whether it was a working day or not
weather: Weather condition (Clear, Mist, Light Snow/Rain)
temp: Actual temperature (°C)
atemp: Perceived temperature (°C)
humidity: Humidity percentage
windspeed: Wind speed (km/h)
casual: Number of casual users
registered: Number of registered users
count: Total number of bike rentals
🔎 Key Analyses Performed
Data Cleaning: Handled missing values, formatted date-time, and converted categorical variables.
Exploratory Data Analysis (EDA): Visualized trends using scatter plots, bar charts, and heatmaps.
Outlier Detection: Applied the IQR method to detect and handle outliers.
Correlation Analysis: Generated a heatmap to analyze correlations.
Hypothesis Testing:
T-Test: Compared bike rentals on weekdays vs weekends.
Kruskal-Wallis Test: Assessed demand differences across weather and seasons.
Chi-Square Test: Checked the relationship between weather conditions and seasons.
📈 Key Insights
Significant differences in bike rentals were observed across seasons, with Fall having the highest demand.
Weather conditions had a strong impact on bike rentals, with clear weather leading to more rentals.
No significant difference in rentals between weekdays and weekends was observed.
🚀 Conclusion
The project highlights how external factors influence bike-sharing demand. These insights can aid stakeholders in:

Optimizing bike availability during high-demand seasons.
Implementing dynamic pricing based on weather forecasts.
Enhancing service management by anticipating user demand.
