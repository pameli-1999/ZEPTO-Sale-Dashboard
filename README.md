# ZEPTO-Sale-Dashboard
Project summary : This Power BI project provides a comprehensive analysis of Zepto's business performance, focusing on sales trends, inventory distribution, and customer satisfaction metrics. By leveraging interactive dashboards, custom KPIs, and advanced DAX calculations, the report identifies key insights to support data-driven decision-making and improve overall operational efficiency.
Key DAX Measures: 
Total Sales = SUM(Sales[Revenue])
Avg Sales = AVERAGE(Sales[Revenue])
YoY Growth = DIVIDE([This Year Sales] - [Last Year Sales], [Last Year Sales])
Inventory Turnover = DIVIDE([Cost of Goods Sold], [Average Inventory])
Distinct Item Count = DISTINCTCOUNT(Sales[ItemID])
