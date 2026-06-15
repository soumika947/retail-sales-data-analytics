# retail-sales-data-analytics
End-to-end data analytics project using MySQL and Python, featuring database normalization, business intelligence dashboards, customer segmentation, sales analysis, and strategic business insights.
Retail Sales Data Analytics Project
Project Overview

In this project, I worked on a retail sales dataset to apply database management and data analytics concepts. The main objective was to transform raw transactional data into a well-structured relational database and generate meaningful business insights through data visualization. This project helped me strengthen my skills in database normalization, SQL, Python, and business intelligence.

Objectives
- Normalize a denormalized retail dataset into an efficient relational database structure.
- Reduce data redundancy and improve database organization.
- Analyze sales, profit, customer, and regional performance data.
- Create visualizations that support business decision-making.
- Dataset Information

The dataset contains retail business transaction records, including:
- Order details and shipping information
- Customer information and market segments
- Product categories and sub-categories
- Regional and geographic data
- Sales, profit, discount, and quantity metrics
- Database Design

Initially, the dataset existed as a single table containing multiple attributes. To improve efficiency and maintain data integrity, I normalized the database into five related tables:
1. Customers
2. Locations
3. Products
4. Orders
5. Order Items

I also created relationships between these tables using primary and foreign keys to ensure consistency and optimize query performance.

Data Analysis and Visualizations
- Product Category Analysis: 
I analyzed sales and profit performance across product categories and found that the Technology category generated the highest sales revenue, while Office Supplies demonstrated more consistent profitability. These insights can support product portfolio and inventory decisions.

- Regional Performance Analysis: 
I compared sales and profit performance across different regions. The West region emerged as the strongest performer in terms of both revenue contribution and profit margin. The analysis also highlighted high-performing states such as California, New York, and Texas.

- Customer Segment Analysis: 
I evaluated customer behavior across different segments. The Consumer segment contributed the highest sales volume, while the Home Office segment showed the highest average order value. This analysis demonstrated the importance of targeted marketing strategies for different customer groups.

- Time-Series Analysis: 
I examined monthly sales and profit trends to identify seasonal patterns. The results revealed stronger performance during year-end periods and a positive relationship between sales growth and profitability.

Key Business Insights:
Through this analysis, I identified several valuable business insights:

- Technology products drive significant revenue growth.
- The West region represents a key market opportunity.
- Different customer segments require tailored business strategies.
- Seasonal sales trends can support forecasting and inventory planning.
- Sales and profit show a strong positive correlation.

Technologies Used:
1. MySQL
2. Python
3. Pandas
4. NumPy
5. Matplotlib
6. Seaborn
7. Plotly

Conclusion: 
This project allowed me to apply database normalization, SQL, data analysis, and data visualization techniques to solve real-world business problems. It strengthened my understanding of business intelligence and helped me develop practical skills in transforming raw data into actionable insights.
