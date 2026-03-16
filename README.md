
# Unemployment Analysis with Python 📉

## 📌 Project Overview
This repository contains a comprehensive data analysis project focused on the **Unemployment Rate in India**. The study specifically investigates the sharp economic fluctuations caused by the **COVID-19 pandemic in 2020**, analyzing how different regions and sectors (Urban vs. Rural) were impacted.

## 🚀 Key Objectives
* Perform **Exploratory Data Analysis (EDA)** to identify seasonal trends.
* Visualize the **Lockdown Impact** using interactive time-series plots.
* Analyze the **Urban vs. Rural divide** in unemployment rates.
* Establish statistical correlations between various economic indicators.

## 🛠️ Technologies & Libraries
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Processing)
* **Visualization:** Plotly, Seaborn, Matplotlib (Interactive & Static Charts)
* **Platform:** Kaggle / Jupyter Notebook

## 📊 Key Insights
* **The Lockdown Spike:** A massive surge in unemployment was identified during April and May 2020, directly coinciding with the national lockdown.
* **Sector Volatility:** Urban areas showed higher vulnerability and slower recovery rates compared to Rural areas, where agriculture provided a stabilizing effect.
* **Regional Hotspots:** States such as Haryana and Tripura exhibited consistently higher stress levels throughout the study period.

## 📈 Visualizations Included
1.  **Correlation Heatmap:** Statistical relationships between economic variables.
2.  **Sunburst Chart:** Hierarchical view of unemployment across Regions and States.
3.  **Line Trends:** Timeline analysis of the COVID-19 impact.
4.  **Box & Violin Plots:** Distribution and outlier analysis for regional data.

## 📋 Dataset Description
| Column | Description |
| :--- | :--- |
| **States** | The specific state in India. |
| **Date** | The date of the recording. |
| **Estimated Unemployment Rate (%)** | Percentage of the labor force that is unemployed. |
| **Estimated Employed** | Number of people currently employed. |
| **Region** | The geographic region (North, South, etc.). |

## 🛠️ Data Preprocessing & Challenges
To ensure the accuracy of the analysis, the following technical steps were taken:
* **Handling Column Inconsistencies:** Standardized column names by removing leading/trailing whitespaces that often cause errors in data pipelines.
* **Datetime Transformation:** Converted raw date strings into Python `datetime` objects to allow for chronological time-series analysis of the COVID-19 impact.
* **Granular Filtering:** Segregated data into **Pre-Lockdown** and **Lockdown** periods to calculate a precise "Percentage Increase" in unemployment.
* **Categorical Cleaning:** Handled inconsistencies in the 'Frequency' column to accurately distinguish between **Urban** and **Rural** data points.

## 📌 Top 3 Analysis Takeaways
1. **The Peak Impact:** National unemployment peaked in **May 2020**, reaching values as high as 75% in specific states.
2. **Rural Cushion:** Rural unemployment rates were generally **4-8% lower** than Urban rates during the strict lockdown phase, likely due to sustained agricultural activity.
3. **Correlation:** A strong negative correlation exists between the **Unemployment Rate** and **Estimated Employed** counts, validating the data's integrity.

## 📂 Project Structure
* `Unemployment_Analysis.ipynb`: The complete Python source code.
* `Unemployment_Data.csv`: The raw dataset used for analysis.
* `README.md`: Documentation of findings and project details.

---

## ⚙️ How to Run
1. Clone this repository: `git clone https://github.com/your-username/Unemployment-analysis.git`
2. Install the required libraries:
   ```bash
   pip install pandas plotly seaborn matplotlib

---
