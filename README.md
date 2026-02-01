# Global-Video-Game-Sales-Performance-Dashboard-Excel

## Dashboard Preview
<img width="1090" height="702" alt="image" src="https://github.com/user-attachments/assets/1729908a-258d-4662-b533-fca0cfd0b08f" />


## Dataset Description
The dataset contains historical global video game sales data, including game titles, platforms, genres, release years, and regional sales figures for North America, Europe, Japan, and the Rest of the World. It also includes total global sales for each game, enabling analysis of market trends, platform performance, genre popularity, and regional market contributions over time.

## Project Overview
This project analyses global video game sales data to understand key drivers of sales across platforms, genres, regions, and time. An interactive Excel dashboard was built to provide business insights and support data-driven decision-making.

## Business Question
What factors drive global video game sales across platforms, genres, regions, and time?

## Tools Used
- Microsoft Excel (Power Query, PivotTables, PivotCharts)
- Data Cleaning & Transformation
- Dashboard Design & Data Visualisation

## Data Cleaning & Preparation
-Null values: 272 missing values in the Year column. The dataset contained 272 missing values in the Year column. Since the year is critical for time-series analysis, these records were removed to avoid bias in trend insights. The missing values accounted for less than 2% of the dataset, so removal did not significantly affect the overall sales analysis.

-Data types: I changed the Sales and Year column to Number

-Data validation: To ensure data accuracy, I validated that Global Sales equalled the sum of regional sales (NA, EU, JP, Other). Minor discrepancies were observed due to rounding; however, no material inconsistencies were found. Global_Sales was retained as the authoritative metric, and a calculated check column was used for quality assurance.


## Dashboard Features
- KPI cards (Total Sales, Number of Games, Top Genre, Top Platform)
- Global sales trend analysis
- Top platforms and genres ranking
- Regional sales breakdown
- Key insights panel

## Key Insights
- Action is the top-selling genre globally
- PlayStation 2 is the highest-selling platform
- North America contributes nearly half of global video game sales
- Sales peaked around 2008–2009 before declining
- Regional genre preferences vary significantly

## Business Recommendations
- Prioritise Action and Shooter genres
- Invest in platform exclusives
- Tailor regional marketing strategies
- Diversify into digital and mobile platforms
- Use lifecycle forecasting for release planning


