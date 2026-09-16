# 🚲 Cyclistic Bike-Share Analysis

## 📊 Project Overview

This project analyzes 12 months of Cyclistic bike-share trip data to understand how **casual riders** and **annual members** use the bike-sharing service differently.

The analysis focuses on ride volume, ride duration, day-of-week patterns, and monthly trends to identify opportunities for improving customer engagement and encouraging casual riders to become annual members.

## 🎯 Business Task

The main objective is to understand:

- How ride volume differs between casual riders and annual members
- How ride duration differs between the two rider types
- Which days of the week have the highest riding activity
- How riding patterns change throughout the year
- What patterns could support membership marketing strategies

## 🛠️ Tools Used

- **Microsoft Excel**
- **Excel Power Query**
- **Excel Data Model**
- **PivotTables**
- **PivotCharts**
- **Conditional Formatting**

## 📁 Dataset

The analysis covers **12 months of bike-share trip data from September 2025 to August 2026**.

The 12 monthly datasets were combined using **Excel Power Query** and prepared for analysis.

The combined dataset contains approximately **6.1 million rides**. Because the dataset exceeds Excel's worksheet row limit, the full dataset was analyzed using the **Excel Data Model and PivotTables**.

The original raw datasets are not included in this repository because of their large file size.

## 📈 Key Findings

### Rider Type

| Rider Type | Number of Rides |
|---|---:|
| Annual Members | 3,955,617 |
| Casual Riders | 2,160,365 |
| **Total** | **6,115,982** |

Annual members generated the majority of rides during the analysis period.

### Ride Duration

| Rider Type | Average Ride Duration |
|---|---:|
| Annual Members | 11.98 minutes |
| Casual Riders | 17.87 minutes |
| **Overall** | **14.06 minutes** |

Casual riders had a longer average ride duration than annual members.

### Day-of-Week Patterns

Ride activity varied throughout the week.

Overall ride volume was highest toward the weekend, while casual riders showed relatively stronger weekend activity. Annual members maintained higher ride volumes across the week and showed stronger weekday activity.

### Seasonal Patterns

Monthly ride activity was lower during the winter months and increased during the warmer months, with higher activity during spring and summer.

## 💡 Business Insights

The analysis suggests that casual riders represent an important opportunity for membership growth.

Potential strategies could include:

- Promoting annual memberships to frequent casual riders
- Using weekend campaigns to target casual riders
- Highlighting the benefits of membership for regular riders
- Using seasonal campaigns during periods of higher riding activity

## 🔍 Analysis Process

1. Collected the monthly bike-share datasets
2. Combined the datasets using Excel Power Query
3. Cleaned and prepared the data
4. Converted ride duration into minutes
5. Created day-of-week fields
6. Loaded the data into the Excel Data Model
7. Created PivotTables and PivotCharts
8. Analyzed rider-type, daily, and monthly patterns
9. Built an interactive Excel dashboard
10. Documented the analysis and findings

## 📊 Dashboard

The interactive Excel dashboard summarizes the key findings from the analysis.

**Dashboard includes:**

- Total rides
- Member rides
- Casual rides
- Average ride duration
- Average duration by day and rider type
- Monthly ride trends by rider type

![Cyclistic Bike-Share Analysis Dashboard](Screenshots/cyclistic-dashboard.png)

## 📂 Project Structure

Cyclistic-Bike-Share-Analysis/

├── Dashboard/
│   └── Cyclistic_Portfolio_Dashboard.xlsx

├── Data/
│   └── README.md

├── Documentation/
│   └── Case_Study_Journal.docx

├── Screenshots/
│   └── cyclistic-dashboard.png

└── README.md

## 📌 Conclusion

The analysis shows clear differences in how casual riders and annual members use the bike-sharing service.

Annual members account for more rides overall, while casual riders have longer average rides. Ride activity also changes by day and season, with stronger overall activity during the warmer months.

These patterns can help inform strategies focused on customer engagement and converting casual riders into annual members.

## 👤 About This Project

This project was created as a **data analytics portfolio case study** to demonstrate practical skills in:

- Data cleaning
- Data transformation
- Exploratory data analysis
- Data visualization
- Business insight generation
- Excel Power Query
- Excel Data Model
- PivotTables and PivotCharts

The project demonstrates how raw bike-share data can be transformed into meaningful business insights using Excel-based data analytics.
