# Sales & Customer Exploratory Dashboards (Tableau)

## Short Description
This project focuses on creating two interactive Tableau dashboards to analyze sales and customer performance for stakeholders, including sales managers and executives. The Sales Dashboard highlights year-over-year sales trends, product comparisons, and weekly sales insights, while the Customer Dashboard provides an overview of customer behavior, trends, and top contributors to company profits. Both dashboards feature dynamic filters, interactivity, and data flexibility to support better decision-making and stakeholder engagement.
Tableau: https://public.tableau.com/shared/NB72HWQTG?:display_count=n&:origin=viz_share_link

# **Project Overview**

## **Sales Dashboard | Requirements**

<img width="1194" alt="image" src="https://github.com/user-attachments/assets/36eed6c7-7b2e-4054-b567-1a5700677636" />

### Dashboard Purpose

The purpose of sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

### Key Requirements

**KPI Overview**

Display a summary of total sales, profits and quantity for the current year and the previous year.

**Sales Trends**

– Present the data for each KPI on a monthly basis for both the current year and the previous year.

– Identify months with highest and lowest sales and make them easy to recognize.

**Product Subcategory Comparison**

– Compare sales performance by different product subcategories for the current year and the previous year.

– Include a comparison of sales with profit.

**Weekly Trends for Sales & Profit**

– Present weekly sales and profit data for the current year.

– Display the average weekly values.

– Highlight weeks that are above and below the average to draw attention to sales & profit performance.

## **Customer Dashboard | Requirements**

<img width="1204" alt="image 1" src="https://github.com/user-attachments/assets/f8455e60-26c1-4db6-969c-0a9f8aa3f192" />

### Dashboard Purpose

The customer dashboard aims to provide an overview of customer data, trends and behaviors. It will help marketing teams and management to understand customer segments and improve customer satisfaction.

### Key Requirements

**KPI Overview**

Display a summary of total number of customers , total sales per customer and total number of orders for the current year and the previous year.

**Customer Trends**

– Present the data for each KPI on a monthly basis for both the current year and the previous year.

– Identify months with highest and lowest sales and make them easy to recognize.

**Customer Distribution by Number of Orders**

Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty and engagement.

**Top 10 Customers By Profit**

– Present the top 10 customers who have generated the highest profits for the company.

– Show additional information like rank, number of orders, current sales, current profit and the last order date.

## **Design & Interactivity Requirements**

**Dashboard Dynamic**

– The Dashboard should allow users to check historical data by offering them the flexibility to select any desired year.

<img width="1196" alt="image 2" src="https://github.com/user-attachments/assets/3f68edf3-49f9-4c7e-8cb1-39038fcef255" />

– Provide users with the ability to navigate between the dashboards easily.

<img width="245" alt="image 3" src="https://github.com/user-attachments/assets/80e58a06-8e12-4482-8114-465c99a96173" />

– Make the charts and graphs interactive, enabling users to filter data using the charts.

<img width="1194" alt="image 4" src="https://github.com/user-attachments/assets/41fcccbd-0073-4d73-a6c5-f622a5895ec6" />

**Data Filters**

Allow users to filter data by product information like category and subcategory and by location information like region, and state (Choose states from a **Map** that replaces a Text Filter)

<img width="1198" alt="image 5" src="https://github.com/user-attachments/assets/b03b5681-19e8-4dd3-a16d-1bdf0827dc1d" />


## Overview of Findings

This project created two interactive Tableau dashboards to analyze sales and customer performance. Key findings include:

* **Sales Growth:** Total sales for 2023 increased by 20.4% compared to the previous year.
* **Customer Growth:** The number of customers grew by 8.6%, with a 10.8% increase in sales per customer.
* **Product Performance:** Phones and Chairs were the top-performing product subcategories.
* **Customer Behavior:** The majority of customers placed 1 or 2 orders, with a few high-profit customers driving significant revenue.

**Insights Deep Dive**

**Category 1: Overall Sales Performance**

**Main Insight 1: Total Sales Growth**

* **Finding:** Total sales for 2023 were $733K, showing a 20.4% increase compared to the previous year.
* **Supporting Data:** The "Total Sales" tile displays $733K with "▲ 20.4% vs. PY."
* **Implication:** This indicates strong sales growth and positive business performance in 2023.

**Main Insight 2: Total Profit Growth**

* **Finding:** Total profit for 2023 was $93K, showing a 14.2% increase compared to the previous year.
* **Supporting Data:** The "Total Profit" tile displays $93K with "▲ 14.2% vs. PY."
* **Implication:** This indicates healthy profit growth, though slightly lower than sales growth, suggesting potential areas for margin improvement.

**Category 2: Sales and Profit Trends Over Time**

**Main Insight 1: Monthly Sales and Profit Patterns**

* **Finding:** Sales and profit show fluctuations throughout the year, with peaks and troughs indicating seasonal or event-driven variations.
* **Supporting Data:** The small line charts under "Total Sales," "Total Profit," and "Total Quantity" show monthly trends.
* **Implication:** This highlights the need for targeted strategies to capitalize on peak periods and mitigate low-performance months.

**Main Insight 2: Highest and Lowest Performing Months**

* **Finding:** The dashboard identifies the highest and lowest performing months for sales and profit.
* **Supporting Data:** The "Highest Month" and "Lowest Month" sections are present but lack specific month information.
* **Implication:** Understanding the best and worst months can help in optimizing resource allocation and promotional activities.

**Category 3: Sales and Profits by Subcategory**

**Main Insight 1: Top Performing Subcategories**

* **Finding:** Phones and Chairs are among the top-performing subcategories in terms of sales.
* **Supporting Data:** The "Sales & Profits by Subcategory" bar chart shows Phones and Chairs with the longest bars.
* **Implication:** These subcategories are key revenue drivers and should be prioritized for growth and investment.

**Main Insight 2: Profitability Variations**

* **Finding:** Some subcategories show profit losses, indicating potential issues with cost management or pricing strategies.
* **Supporting Data:** The "2023 Profit Loss" bar chart shows negative values for some subcategories.
* **Implication:** These subcategories require further investigation to identify and address the root causes of losses.

**Category 4: Customer Behavior and Profitability**

**Main Insight 1: Customer Distribution by Orders**

* **Finding:** The majority of customers placed 1 or 2 orders, with a significant drop in customers placing more orders.
* **Supporting Data:** The "Customer Distribution by Nr. of Orders" bar chart shows high counts for 1 and 2 orders, then a steep decline.
* **Implication:** This suggests a need to encourage repeat purchases and improve customer retention strategies.

**Main Insight 2: Top Customers by Profit**

* **Finding:** Raymond Buch is the top customer by profit, generating 7K profit from 14K sales over 16 months.
* **Supporting Data:** The "Top 10 Customers by Profit (2023)" table lists Raymond Buch as the top customer.
* **Implication:** Identifying and nurturing high-profit customers like Raymond Buch is crucial for maximizing revenue.

### Recommendations

Based on the insights above, we recommend the following actions:

* **Sales Strategy:** Focus on high-performing product subcategories and replicate their success across other categories.
* **Customer Engagement:** Implement loyalty programs for high-frequency customers to enhance retention.
* **Targeted Marketing:** Use customer segmentation to tailor marketing campaigns for top profit contributors.
* **Data-Driven Decisions:** Leverage dynamic filters and interactive dashboards for real-time decision-making.
* **Customer Retention:** Develop strategies to encourage repeat purchases and improve customer retention.
* **Profit Optimization:** Analyze profitability in relation to sales volume to optimize pricing and product strategies.

### Assumptions and Caveats

* **Assumption 1:** Data from internal databases is accurate and up-to-date.
* **Assumption 2:** The data reflects only the specified time period and may not be applicable to other periods.
* **Assumption 3:** External factors like market conditions may impact sales and customer behavior unpredictably.

### Tools and Technologies Used

* **Data Visualization:** Tableau
* **Data Sources:** Internal sales and customer databases
* **Interactivity:** Dynamic filters, interactive charts, and maps


