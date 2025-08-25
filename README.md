# Introduction
This project 📊 analyzes Walmart’s weekly sales data from 2010 to 2012 to uncover key trends, patterns, and store performance insights. The main goal 🎯 was to understand how
sales varied over time ⏳, across different stores 🏬, and during holiday periods 🎉.
To achieve this, I downloaded the dataset in CSV format 📂, cleaned it using Excel 🧹 (handling missing values, fixing date formats, and ensuring data consistency), and then
built an interactive dashboard 📈. The dashboard includes multiple visualizations that highlight overall sales trends, store-level performance, the impact of holidays, and the
relationship between sales and temperature 🌡️.
🔗 Want to explore the project?  
- 📊 **Dashboard Preview (PDF):** [walmartSales2010to2012.pdf](walmartSales2010to2012.pdf)  
- 📑 **Dataset:** [walmartSales.xlsx](walmartSales.xlsx)
# Background
### The questions I wanted to answer through this project were:
1. How did Walmart’s weekly sales change between 2010 and 2012? Were there any noticeable trends or seasonal patterns?
2. Which stores had the highest and lowest average weekly sales? How consistent was performance across all 45 stores?
3. Which 10 stores contributed the most to overall sales during 2010–2012?
4. How much impact did holidays have on weekly sales compared to regular weeks?
5. Is there any relationship between changes in temperature and Walmart’s weekly sales?
# Tools I Used
- **📂 Kaggle:** Source of the Walmart sales dataset
- **📝 Excel:** Data cleaning, analysis, and dashboard creation
- **💻 GitHub:** Documentation and sharing the project
# The Analysis
The dashboard visualizations were built to address key questions about Walmart’s sales performance. Each chart was tailored to shed light on a specific dimension of the
data. But how exactly did I go about answering these questions?
## 1. How did Walmart’s weekly sales change between 2010 and 2012? Were there any noticeable trends or seasonal patterns?
In order to analyze Walmart’s overall weekly sales performance from 2010 to 2012, with the objective of identifying long-term trends, seasonal patterns, and notable sales peaks during specific periods such as holidays, I created a line chart in Excel. To build this chart, I imported the dataset into Excel, cleaned and formatted the `Date` and `Weekly_Sales` columns, aggregated sales by week to obtain the total weekly sales across all stores, and then inserted a line chart with dates on the X-axis and weekly sales on the Y-axis. Finally, I applied professional formatting, including titles, labels, and markers, to ensure clarity and highlight fluctuations in sales over time.
### Insights 
The line chart reveals that Walmart’s weekly sales between 2010 and 2012 were relatively stable overall, fluctuating mostly between $150M and $250M, with noticeable spikes occurring around the end of each year, which can be attributed to major holidays such as Thanksgiving and Christmas. These peaks indicate the strong influence of seasonal shopping periods on revenue, while the recurring dips after holiday weeks highlight the slowdown that typically follows. Apart from these seasonal surges, the trend shows consistent performance across the three years without any significant long-term upward or downward movement.

![firstLineChart](/assets/firstLineChart.png)

*This line chart represents Walmart’s weekly sales trend over time across all stores from 2010 to 2012.*
