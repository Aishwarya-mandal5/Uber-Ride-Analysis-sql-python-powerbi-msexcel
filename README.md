# Uber Ride Analysis

Analyse Uber ride data for 2016, identifying travel patterns, trip purposes, peak times, and usage categories to inform business decisions and operational improvements.

### Overview

This dashboard presents a detailed summary of Uber ride patterns, highlighting travel purposes, times, categories, and daily or monthly trends for comprehensive trip analysis. 
A complete analysis is performed in Python and SQL server studo and visualisation is created with Power BI and MS Excel.

### Business Problems Identified

- Variability in trip demand by day, month, and time requires dynamic resource planning and predictive modeling.
- Large proportions of trips without defined purpose hinder segmentation and tailored service offerings.
- Missed opportunities in the business travel segment due to low usage.
- Underutilized hours and seasonal dips point to inefficiency in fleet management and potential for promotional targeting.

### Data Set

Dataset was taken from kaggle.com
https://www.kaggle.com/datasets/ruchikakumbhar/uber-dataset

### Tools and Techniques

- Sql (Common Table Expression)
- Python (Pandas, Numpy, Matplot, Seaborn)
- Power BI (Interactive visualization)
- MS Excel (Pivot table, Charts, Filters)
- Github

### Data Cleaning and Preparation

- Extracted date and time from combined column START_DATETIME and END_DATETIME.
- Generated month and day column from START_DATE.
- Checked for missing values, duplicate rows, and unique values in each column.
- Filled missing values in the 'PURPOSE' column using forward fill method.
- Calculated the duration of each trip in minutes and added it as a new column.
- Created hour range in a separate column. 

### Key Metrics and Insights

- In 2016, 1155 trips covered a total distance of 12,200 miles with an average trip distance 10.57 miles and average duration of 23 minutes.
- The majority of trips are for unknown purposes, indicating the need for improved data collection and customer profiling.
- Business rides constitute a small share, revealing an opportunity to better target corporate clients and expand this market segment.
- Most rides occur on weekends and Fridays, with Friday being the busiest day, suggesting the importance of staffing and resource allocation during end-of-week peaks.
- December sees the highest trip volume, while May to September are relatively low, pointing to strong seasonal fluctuation that impacts demand forecasting.
- Analysis of daily and monthly trends shows predictable patterns; however, certain months and midweek periods experience dips, signaling possible periods for targeted promotions.
- The bulk of trips happen during afternoon hours, aligning with customer meal times and meetings, and lower travel in late nights and early mornings highlights specific gaps in coverage and service utilization.
- There is a mixture of business and personal trips, with personal travel making up the vast majority, providing direction on where to focus service differentiation.
<img width="796" height="452" alt="Uber Ride Analysis" src="https://github.com/user-attachments/assets/ff9b2c0e-0294-4667-b3d5-015f13e1037b" />

### How to Run the Project

1. Clone the repositary:
```bash
git clone https://github.com/Aishwarya-mandal5/Uber-Ride-Analysis-sql-python-powerbi-msexcel
```
2. 

### Recommendations

- Invest in better customer data gathering to reduce "unknown" purpose trips and enhance analytics.
- Develop specialized business packages and marketing campaigns to boost corporate ride share.
- Adjust operational resources to align with peak days, hours, and seasonal patterns.
- Launch targeted promotions during off-peak months and weekdays to increase trip volumes.
- Analyze feedback from low-demand periods to discover new opportunities and improve user experiences.

### Author

Aishwarya Mandal  
[Email](aishwaryamandal94@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/aishwarya-mandal-2a145915b/)
