# Office_Wizard_Sales_Analysis
I partnered with US-based office supply company Office Wizard to create an insightful Power BI dashboard for their new investor. The goal was to analyze 4 years of sales data and uncover the reasons behind low profits in 2017, despite high sales. This interactive dashboard provided actionable insights into key performance metrics and addressed critical business questions:
1. Yearly sales and profit trends.
2. Top-performing cities, states, and regions for sales and profit, and identification of low-performing areas.
3. Segments, categories, sub-categories, and products driving sales and profit.
4. The impact of discounts on loss-making products and identification of loss drivers.

## Data Preparation:
The dataset was thoroughly cleaned. Although, there were no duplicate values, incorrect values, or redundant rows. But there were some inconsistencies like 
1. Wrong formatting
2. Only 1 month of data for 2018 
3. Some unimportant columns like customer ID, product ID, postal code, and country. 
4. Outliers

So, I corrected the formats and removed all of the redundant columns. I also had to rows containing partial 2018 data. However, after a thorough inspection, I found the outliers to be important for the analysis. As a result, I kept them. 

## Feature Engineering
Firstly, I have added a new loss column as the profit column has some negative values so I added them inside this new loss column. This column helped me find the loss-making products. For the analysis, I have also added a few calculated columns. They are
1. Product_Price
2. Profit_Margin
3. Delivery_Time
4. Year and
5. Discount_Amount

They have helped me discover important insights from the dataset. 


## Power BI Dashboard

The dashboard features a clean, user-friendly design aligned with the company's branding. Each page uses a minimalist layout with a maximum of four visuals per page, supplemented by interactive buttons and slicers for seamless navigation and deeper analysis. The Power BI Dashboard has some key features. They are
1. Dynamic Buttons: Interactive buttons switch between sales and profit views, providing tailored insights.
2. Slicers: Enable filtering by year for granular analysis.
3. Performance Metrics: Cards displaying total sales, profits, and YoY growth metrics at a glance.
4. Theme Alignment: Customized design matching the company’s logo and brand identity.

### Page 1: Overview
![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/Port%201.jpg)

Focuses on yearly sales and profit trends, top regions, and growth metrics.

![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/Port%201.jpg)

Features a line chart, bar charts, slicer for year selection, and KPI cards for YoY growth and totals.

### Page 2: Products

![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/Port%203.jpg)

Highlights sales and profit trends by product category, sub-category, and segment.

![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/Port%204.jpg)

Includes pie charts, bar charts, and interactive buttons for detailed sales and profit views.

### Page 3: Profit and Loss Analysis

![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/port%205.jpg)

Examines the relationship between discounts and loss-making products, identifying categories and products with high losses.

![image alt](https://github.com/Anoy27/Office_Supply_Sales_Analysis/blob/916e625213afdeccdd6a49eab63faa7fdd3139d2/port%206.jpg)

Utilizes scatter plots, pie charts, and bar charts for a comprehensive analysis.



This project empowered the client to make informed decisions by presenting a clear, actionable story behind their sales and profit performance. The dashboard's intuitive interactivity and detailed insights impressed the stakeholders, including the investor.

## Insights & Recommendations:
The analysis uncovered critical factors impacting profitability:

### Excessive Discounts to Repeated Customers:
A significant number of repeated customers were receiving disproportionately high discounts. While these customers boosted low sales purchasing low price products, they led to significant profit erosion.

### Loss-Making Products:
Several products across specific categories and sub-categories consistently incurred losses, exacerbated by heavy discounting strategies.

### Seasonality Impact:
The business exhibits clear seasonality, with higher sales and profits concentrated in Q3 and Q4. The lower sales in Q1 and Q2 significantly impact overall profitability.

## Recommendations for Business Improvement:
Based on my analysis here are a few suggestions  
### Refine Discount Strategies: 
Introduce a balanced discounting policy to reward loyalty without compromising profit margins.
Focus on Product Profitability: Reassess pricing and sales strategies for loss-making products and consider discontinuing underperforming items.
### Address Seasonality:
Launch promotional campaigns or product bundles in Q1 and Q2 to drive demand during slower periods. Optimize inventory and resource allocation to prepare for peak sales in Q3 and Q4.
### Target High-Margin Segments:
Concentrate on high-margin products and regions to maximize returns.
### Operational Efficiency: 
Optimize inventory and supply chain strategies to reduce costs associated with underperforming regions and products.

By addressing these challenges and leveraging insights, the client gained a clearer understanding of their business performance and actionable strategies to improve profitability resulting in 2.5x more profit in the next quarter.
