# Walmart_Data_Analysis (Interactive Dashboard Creation using MS Excel)

## Project Objectives 
This analysis aims to uncover in-depth insights into sales, profitability, and performance trends across product categories, geographic regions, and time periods. By leveraging metrics such as total sales, profit margins, and order efficiency, it identifies high-performing products, regions, and seasonal sales patterns while exploring the dynamics between sales quantities and revenue. These findings will inform strategic decisions in inventory management, marketing, pricing, and resource allocation, driving optimized operations and enhanced profitability.

## Dataset used	
-	Download Walmart_Data.xlsx

## Questions
  - **Sales Performance by Category:** What are the total sales for each product category? Which categories perform best?
  - **Profitability by Geography:** Which geographic regions yield the highest profits?
  - **Sales Trend Analysis:** How have monthly sales changed over time? Are there specific months or seasons with higher sales?
  - **Top Products by Sales:** What are the top-selling products based on total sales?
  - **Order Processing Time:** What is the average processing time from order date to ship date? Is it consistent across different categories?
  - **High-Volume Customers:** Which customers (based on EmailID) place the most orders or generate the most revenue?
  - **Quantity Sold by Product:** What is the total quantity sold for each product, and how does this correlate with revenue?
  - **Profit Margin Analysis:** Which product categories or specific products have the highest profit margins?
  - **Order Frequency by Geography:** How many orders are placed from each geographic region, and what is the average order size?
  - **Profit Trends Over Time:** How has the total profit changed over time? Are there periods where profitability fluctuates?

## Process
  - **Objective Definition:** Clearly define the goals of the analysis, such as understanding sales trends, profit margins, and operational inefficiencies.

  - **Data Familiarization:** Review the dataset to understand its structure, key variables (e.g., Product Name, Sales, Profit, Region, Order Date, Ship Date), and any potential issues 
                              like missing values or inconsistencies.

  - **Data Cleaning:**
      Remove duplicates and handle missing values.
      Standardize formats for dates, geographic names, and numerical values.

  - **Feature Engineering:**
      Add calculated fields, such as Profit Margin (Profit / Sales) and Order Delay (Ship Date - Order Date).
      Extract new variables, such as Month and Year from order dates for trend analysis.

  - **Descriptive Analysis:**
      Calculate summary statistics like total sales, average profit margin, and total quantities sold

  - **Trend Analysis:**
      Analyze monthly and yearly trends in sales and profits using line charts and PivotTables.

  - **Correlation Analysis:**
      Use scatter plots and correlation coefficients to explore relationships (e.g., Quantity vs. Revenue).

  - **Category Analysis:**
      Use PivotTables to determine top-performing categories, regions, and products by sales and profit margins.

  - **Data Visualization**
      Create clear and intuitive visuals to highlight key findings:
        •	Bar Charts: Show sales and profit by product category and geographic region.
        •	Line Charts: Display monthly sales and profit trends.
        •	Scatter Plots: Visualize correlations between quantity sold and revenue.
        •	Pie Charts: Represent the proportion of revenue and profit by category.

  - **Insights Generation**
        •	Sales Performance: Identify high-performing and low-performing categories, regions, and products.
        •	Profitability: Highlight products and regions with high and low profit margins.
        •	Operational Issues: Uncover delays in shipping and their potential causes.

  - **Recommendations**
      Based on the analysis, provide actionable recommendations to:
        •	Focus on high-margin products and regions.
        •	Address operational inefficiencies, such as shipping delays.
        •	Optimize pricing strategies for high-volume, low-revenue products.

  - **Reporting**
      Compile findings into a structured report, including:
        •	Objectives and methodology.
        •	Key insights and visualizations.
        •	Actionable recommendations for stakeholders.
    
    ## Dashboard
       https://github.com/NaveenBS22/Walmart_Data_Analysis-/blob/main/Walmart_Dashboard.png?raw=true

    ## Project Insight 
      - **Top-Selling Categories:** Chairs, Phones, and Tables contributed ₹101,781, ₹98,684, and ₹84,755 respectively, accounting for over 30% of total sales.
      - **Regional Sales:** California and Washington regions drove 84% of total profits, with California contributing 58% alone. In contrast, regions like Colorado, Arizona, and Oregon 
                        showed negative profits, indicating the need for focused interventions.
      - **High-Margin Products:** Envelopes (46%), Paper (45%), and Labels (45%) showed exceptional profitability, highlighting opportunities for targeted promotions.
      - **Loss-Making Products:** Machines (-1%) and Bookcases (-5%) represent cost-heavy categories that may require sourcing or pricing adjustments.
      - **Shipping Delays:** The average shipping time was 4 days but extended to 5–7 days during peak holiday periods due to high order volumes and supply chain constraints.
      - **Seasonal Peaks:** November and December saw the highest sales, aligning with holiday shopping trends, while March and September also showed above-average performance.
      - **Quantity vs. Revenue:** Weak positive correlation (0.26) suggests revenue isn’t solely dependent on volume, as high-value products like Copiers (₹565/unit) outperformed high- 
        quantity items like Binders (₹15/unit).

## Conclusion 
      This analysis explores Walmart's sales, profits, and operations, highlighting top-performing products like Chairs and Phones, with high-margin items such as Envelopes offering            strong profitability. California and Washington lead in sales, while underperforming regions need attention. Shipping delays, particularly during peak periods, point to operational       inefficiencies. Recommendations include focusing on high-margin products, optimizing inventory, and improving logistics to enhance profitability and growth.




