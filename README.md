# 🚲 **Yulu Bike-Sharing Demand Analysis**

## 📌 **Overview**  
This project provides an in-depth analysis of a bike-sharing dataset to explore how external factors like **weather conditions**, **seasons**, **holidays**, and **working days** influence the demand for bike rentals. By applying **statistical analysis** and creating visualizations, the project uncovers key insights that can help optimize resource management in a bike-sharing system.  

---

## ❗ **Problem Statement**  
The objective of this project is to analyze the factors that influence bike rental demand. By understanding patterns in demand, stakeholders can make data-driven decisions to:  
- **Optimize bike distribution**  
- **Adjust pricing strategies**  
- **Improve service availability**  

---

## 📊 **Objectives**  
- ✅ Analyze the distribution of bike rentals across different conditions.  
- ✅ Identify patterns and relationships between external factors and bike demand.  
- ✅ Perform hypothesis testing to validate significant differences in rental demand.  
- ✅ Provide actionable insights for business decisions.  

---

## 🛠 **Tools & Libraries**  
- **Python** for data analysis and visualization  
- **Pandas** for data manipulation  
- **Seaborn** and **Matplotlib** for data visualization  
- **SciPy** for statistical hypothesis testing  

---

## 📂 **Dataset**  
The dataset consists of **10,886 observations** and contains the following key features:  

- **`datetime`**: Timestamp of bike rental  
- **`season`**: Season (Spring, Summer, Fall, Winter)  
- **`holiday`**: Indicates whether it was a holiday or not  
- **`workingday`**: Specifies if it was a working day or not  
- **`weather`**: Describes weather conditions (Clear, Mist, Light Snow/Rain)  
- **`temp`**: Recorded temperature in Celsius  
- **`atemp`**: "Feels like" temperature in Celsius  
- **`humidity`**: Humidity percentage  
- **`windspeed`**: Wind speed in km/h  
- **`casual`**: Number of casual users (non-registered users)  
- **`registered`**: Number of registered users  
- **`count`**: Total number of bike rentals  

---

## 🧹 **Data Cleaning**  
- Converted `datetime` to a proper format.  
- Categorized columns like **season**, **holiday**, **workingday**, and **weather**.  
- Checked for missing values and handled outliers using the **IQR method**.  

---

## 📊 **Exploratory Data Analysis (EDA)**  
- Visualized numerical features using **histograms** and **scatter plots** to identify patterns.  
- Used **box plots** to detect outliers and understand the distribution of bike rentals.  
- Examined categorical variables using **bar charts** and **pie charts**.  

---

## 📈 **Statistical Analysis & Hypothesis Testing**  
Several hypothesis tests were performed:  

1. **Weekday vs. Weekend Rentals**  
    - **T-Test**: Determined if there is a significant difference in bike rentals between weekdays and weekends.  

2. **Weather Conditions & Bike Demand**  
    - **Kruskal-Wallis Test**: Assessed if the demand for bikes varies significantly across different weather conditions.  

3. **Seasons & Bike Demand**  
    - **Kruskal-Wallis Test**: Verified significant differences in bike rentals across seasons.  

4. **Weather vs. Seasons**  
    - **Chi-Square Test**: Evaluated if weather conditions are distributed differently across seasons.  

---

## 💡 **Key Insights**  
- **Seasons and weather conditions** significantly impact the demand for bike rentals.  
- Bike demand remains **consistent on weekdays and weekends** with no major difference.  
- **Clear weather** conditions lead to the highest number of bike rentals, while adverse weather reduces demand.  
- Spring and summer show **higher demand** compared to other seasons.  

---

## 🚀 **Conclusion**  
This analysis highlights how external factors influence bike rental patterns. The insights can be applied to:  
- Improve bike availability based on seasonal demand.  
- Optimize resource allocation.  
- Plan preventive measures for weather-based fluctuations.  









