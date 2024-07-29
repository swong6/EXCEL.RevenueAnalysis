# Go.com 1Q15 Profit Estimation Analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Data Preparation](#data-preparation)
4. [Analysis and Visualizations](#analysis-and-visualizations)
5. [Key Findings](#key-findings)
6. [Conclusion](#conclusion)
7. [Resources](#resources)

## Project Overview
Analyzed sales data for Go.com to estimate 1Q15 profit, identifying data irregularities and applying historical profit margins. Estimated a profit of $1.93M, showcasing skills in data analysis, anomaly detection, and statistical methods.

## Data Source
The data for this project was sourced from Go.com’s three websites:
- Cars.go.com
- Boats.go.com
- Planes.go.com

## Data Preparation
Data cleaning and transformation steps included:
- Removing duplicates
- Standardizing date formats
- Handling missing values

## Analysis and Visualizations

### Boats.go.com IQR Analysis
Identified outliers in the daily sales data for Boats.go.com by calculating the IQR (Interquartile Range). Removed duplicates and standardized the data.

![Boats IQR Analysis](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Baots%20IQR%20Analysis.png)

### Cars.go.com IQR Analysis
Performed a similar analysis for Cars.go.com. Found no significant outliers.
![Cars IQR Analysis](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Cars%20IQR%20Analysis.png)

### Planes.go.com IQR Analysis
Detected outliers in the Planes.go.com data and standardized the dataset.
![Planes IQR Analysis](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Planes%20IQR%20Analysis.png)

### Descriptive Analytics
Calculated descriptive statistics for each product line to understand data distribution and variance.
![Descriptive Analytics](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Descriptive%20Analytics.png)

### Profit Margin Analysis
Applied historical profit margins to estimate the profit for each product line.
![Profit Margin Analysis](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Profit%20Margin%20Analysis.png)

### Revenue and Profit by Quarter
Visualized quarterly revenue and profit trends to identify patterns and anomalies.
![Revenue and Profit by Quarter](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Revenue%20and%20Profit%20by%20Quarter.png)

### Weekly Revenue by Product Line
Analyzed weekly revenue trends for each product line to understand sales patterns.
![Weekly Revenue by Product Line](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Weekly%20Revenue%20by%20Product%20Line.png)

## Key Findings
- **Outliers**: Identified multiple outliers in Boats.go.com sales data, indicating unusual spikes and drops.
- **Missing Data**: Found 24 missing data points in February 2015 for Boats.go.com and filled a crucial missing data point for Q4 2014 in Planes.go.com.
- **Revenue Trends**: Consistent revenue growth across quarters for Cars.go.com, with significant revenue from Planes.go.com in specific periods.
- **Profit Margins**: Historical profit margins applied consistently across quarters provided a reliable basis for profit estimation.

## Conclusion
By employing observed and historical data, the estimated 1Q15 profit for Go.com is approximately $1,933,128. This analysis involved summing the daily revenues for each product line and applying historical profit margins from the past five quarters. Despite data irregularities, including outliers and missing data points, the dataset appeared reliable overall. Consistent profit margins across quarters provide confidence in the profit estimation, highlighting the importance of thorough data analysis and validation.

---

## Resources
- [Product Line Revenue Analysis](https://github.com/swong6/EXCEL.RevenueAnalysis/blob/main/Product_Line_Revenue_Analysis.xlsx)
