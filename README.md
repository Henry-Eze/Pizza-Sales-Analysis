# Pizza-Sales-Analysis

## Table of Contents
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Cutting-Edge Analytical Tools](#cutting-edge-analytical-tools)
- [Data Cleaning](#data-cleaning)
- [Empirical Data Analysis](#empirical-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)


### Introduction
This project serves as a detailed exploration of the sales performance, providing insightful data and critical assessments of strategies and areas for improvement. By analyzing various aspects of the sales data, I seek to identify patterns, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![Dashboard](Power BI comprehensive overview)
!![Screenshot (31)](https://github.com/Henry-Eze/Pizza-Sales-Analysis/assets/150622562/8c7136ae-8206-4047-8bb6-149af63c2f01)



### Data Sources
This project strength lies not only in the diversity of the data sources “Pizza Sales Data.xlsx” but also in the skill of synthesizing this multi-layered information into actionable reports. It’s evidence to the commitment in leveraging the power of data to innovate, plan, and derive meaningful outcomes in shaping the future.

### Cutting-edge analytical tools
- Excel - Data extraction format
- Power Query Editor – Cleaning of data
- Power BI – Data visualization link to download Power BI app for an interactive overview
  - [Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494?…)
- Power BI DAX - To perform mathematical calculation.

### Data Cleaning
Cleaning sales data is critical for accurate analysis. Here's a general process for cleaning sales data:
-	Remove duplicates and non-needed columns and rows.
-	Empty cell
-	Handle missing values like null, na, NAN.
- Check for data integrity.
- Merge and split data.

### Empirical Data Analysis
Exploratory Data Analysis (EDA) is an approach to analyzing datasets to summarize their main characteristics, often employing visual methods. Its a primary goal is to understand the data, discover patterns by answering some of the questions below:
- What pizza types are the most and the least popular?
- Which pizza types and sizes are the most popular?
- Which pizzas contribute the most to the revenue?
- What are the peak times for orders during the day and which day of the week are the most orders placed?
  [Dashboard](Quarterly Sales Overview)
  ![Screenshot (32)](https://github.com/Henry-Eze/Pizza-Sales-Analysis/assets/150622562/3667e1ab-0713-44c8-ac82-4747c17940c4)


### Data Analysis
In DAX (Data Analysis Expressions), several metrics and calculations can be performed to determine revenue by month, week, day of the week and hours of the day.
```DAX
Revenue = [Total Order]*Order_Details[Unit Price]
Unit Price = RELATED(Pizzas[price])
```

 ### Findings
-	It can be deduced that the most popular pizza is the Classic Deluxe Pizza while the least popular pizza is the Brie Carre Pizza.
-	Also, in terms of revenue, the Thai Chicken Pizza type generated the most revenue while the Brie Carre Pizza type generated the least revenue. Understanding their success factors can inform marketing strategies or inventory management.
-	From the result, it can be inferred that the month of July produced the highest revenue for pizzas with approximately $73K in sales. Meanwhile the month of September and October generated the least revenue and sales.
-	It is safe to conclude that Friday has the highest sales while Sunday has the least number of pizzas sold. It should also be noted that all the pizzas category namely, Classic, Supreme, Veggie and Chicken sold the most pizzas on Fridays.

### Recommendations
After analyzing the pizza sales datasets, here are some recommendations that could enhance sales and optimize operations:
-	Menu optimization: Analyze the most popular pizza types, ingredients and toppings.
-	Consider introducing new offerings or seasonal specials based on customer preferences. 
-	Online Ordering: Ensure a user-friendly online ordering platform or app. Simplify the ordering process, offer customization options, and provide incentives for online orders to encourage digital sales.
-	Customer feedback and reviews: Act on customer feedbacks to improve service. Encourage post order reviews and ratings and use this feedback to address issues or make necessary menu/service adjustments.
-	Targeted Marketing: Segment customers based on ordering habits (frequency, order size, preferred toppings). Use targeted marketing campaigns via email or social media to offer personalized deals and increase engagement.
-	Staff Shifts: I also recommend scheduling more of the staff to the rush hours between 12.00pm – 5.00pm for timely delivery of customer orders, improve customer experience and expectations.
