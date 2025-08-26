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

![firstLineChart](/assets/firstLineChartu.png)

*This line chart represents Walmart’s weekly sales trend over time across all stores from 2010 to 2012.*
## 2. Which stores had the highest and lowest average weekly sales? How consistent was performance across all 45 stores?
In order to assess which stores had the highest and lowest average weekly sales, I created a bar chart that compares the performance of all 45 Walmart stores. To build this
visualization in Excel, I first calculated the average weekly sales per store by grouping the data by `Store` and applying the average function to the `Weekly_Sales` column.
Once the averages were computed, I inserted a bar chart with the stores placed along the X-axis and their corresponding average weekly sales on the Y-axis. Finally, I
applied formatting adjustments such as sorting the bars in descending order, adding labels, and customizing the chart design to ensure clarity and readability.
### Insights
The chart highlights significant disparities in sales performance across the 45 Walmart stores. Stores such as 20, 4, and 14 consistently achieved the highest average weekly
sales, exceeding $2 million, while stores like 44 and 33 recorded the lowest averages, falling below $500,000. This suggests that a small group of top-performing stores
contributed disproportionately to overall sales, while several stores underperformed relative to the company average. The steep decline from the highest to the lowest bars
also indicates that store performance was not evenly distributed, pointing to potential differences in location, customer base, or operational factors.

![firstBarChart](/assets/qst2.png)

*This bar chart represents the average weekly sales for each Walmart store from 2010 to 2012, highlighting the highest and lowest performers across all 45 stores.*

## 3. Which 10 stores contributed the most to overall sales during 2010–2012?
In order to determine which 10 stores contributed the most to Walmart’s overall sales between 2010 and 2012, I created a clustered bar chart that highlights the total sales
of the top-performing stores. To construct this visualization in Excel, I first aggregated sales data by store and identified the top 10 based on their total sales volume
across the three-year period. I then grouped the results by year (2010, 2011, 2012) to allow for performance comparison over time. A clustered bar chart was inserted with
stores on the X-axis, sales on the Y-axis, and color-coded bars representing each year. Formatting enhancements such as axis titles, data grouping, and clear labeling were
applied to ensure readability and effective comparison.
### Insights
The chart reveals that a small group of stores consistently accounted for a significant share of Walmart’s total sales, with Stores 4, 14, and 20 emerging as the strongest
contributors, surpassing $100 million in multiple years. Performance generally peaked in 2011 across most of the top 10 stores before slightly declining in 2012, which may
suggest broader economic influences or shifts in consumer spending. Despite year-to-year fluctuations, the dominance of these stores underscores their importance in driving
overall revenue, highlighting how Walmart’s sales were heavily concentrated in a limited number of high-performing locations.

![secondBarChart](/assets/qst3.png)

*This bar chart represents the total sales generated by Walmart’s top 10 stores between 2010 and 2012, comparing their contributions across each year.*

## 4. How much impact did holidays have on weekly sales compared to regular weeks?
In order to assess the impact of holidays on sales performance, I created a comparative bar chart. The process began by isolating the `Weekly_Sales` figures and grouping
them according to the binary `Holiday_Flag` column. Using the `AVERAGEIFS` function, I calculated the mean sales value for all weeks flagged as holidays and, separately, for
all regular weeks. These two resulting values were then plotted on a Clustered Bar chart in Excel, with the holiday flag categories on the category axis and average sales
value on the value axis. The chart was formatted for clarity, with data labels added to each bar to display the precise average values and a distinct color applied to the
holiday week bar to facilitate immediate visual comparison against the baseline of non-holiday weeks.
### Insights
The chart provides a clear and significant insight: holiday weeks generate substantially higher sales than regular weeks. The data shows that the average weekly sales during
holiday periods is $1,122,887.89, compared to $1,026,467.26 for non-holiday weeks. This represents a positive sales lift of approximately $96,420.63, or about 9.4%, during
holidays. This finding underscores the critical importance of holiday-driven business strategies. It confirms that events like Black Friday, Thanksgiving, and Christmas are
major revenue drivers. For business operations, this insight mandates strategic planning, including ensuring optimal inventory levels, allocating sufficient staff, and
designing targeted marketing campaigns in the lead-up to these peak periods to maximize this predictable surge in consumer demand and capitalize on the increased spending
behavior.

![thirdBarChart](/assets/qst4.png)

*Comparative Analysis of Average Weekly Sales: Holiday vs. Non-Holiday Periods*
