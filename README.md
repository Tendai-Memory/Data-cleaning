# Sales Analysis
This project involves analyzing Global superstore dataset to uncover key trends related to sales					
performance, product demand, geographic distribution, and product returns. An interactive					
dashboard was created using Power BI to convert raw transactional data into actionable					
insights that support data-driven decision making within a retail environment.					
					
# Tools Employed					
- Excel - Data Cleaning & Analysis								
- [Download_here](https://docs.google.com/spreadsheets/d/1oE5Mab7KBvIfHK8WFMZ4jNFm_QeJDG_Wql4zsGghcDY/edit?usp=sharing)								
- SQL Server - Further Data Cleaning and Analysis								
- PowerBI - Creating Reports
- 							
# Major Metrics		
- Total Sales $12,46M
- Total Revenue: $1,47million					
- Total Orders: 26K				
- Average Sales per Customer 725,95
- Profit Ratio			
These KPIs offer a comprehensive overview of the business’s overall performance.
						
	### Data Cleaning/ Preparation					
						
	In the initial phase, we performed the following tasks.					
	1. Data loading and inspection					
	2. Handling missing values					
	3. Removed duplicates					
	4. Data cleaning and formatting					
						
	### Exploratory Data Analysis					
						
	EDA involved exploring the sales data to answer the following questions, such as:					
	-	What is the overall sales trend?				
	- What products are top sellers?					
	- What are the peak sales periods?					
	- Which regions are more profitable?					
	- What is the impact of discounts on profitability?
 - 			
	Interesting code/features worked on		
	- Excel		
	- Sales by region by category		
	- Profit by Category		
	- Sales by segment		
	- Sales by customer		
			
	```SQL
 %%sql		
	
SELECT 
    Discount,
    ROUND(AVG(Profit), 2) AS Avg_Profit,
    ROUND(SUM(Profit), 2) AS Total_Profit,
    COUNT(*) AS Number_of_Orders
FROM Orders
GROUP BY Discount
ORDER BY Discount;	
	```					
										
					
# Key Findings					
- Revenue Growth: Sales steadily increase throughout the year, with a marked rise in the final					
months, indicating seasonal patterns.					
- Top Products:Technology category indicates the most sales and profit.					
- Geographic Sales: Revenue is heavily concentrated in a few key countries, highlighting strong					
market presence in specific regions.					
- Discounts: The higher discount on products result in  huge losses					
					
# Business Recommendations					
- Develop inventory and marketing strategies tailored to seasonal peaks.					
- Promote high-performing products to maximize sales.					
- Increase marketing efforts and logistics support in regions with high revenue.					
- Track return trends to ensure product quality and maintain customer satisfaction.					
					
# Project Outcome					
This initiative demonstrates the power of data visualization in transforming raw retail data into					
strategic insights that can drive impactful business decisions.					
					
# Author:					
Tendai Mubvuta - ALX Data Analytics Graduate				
					
