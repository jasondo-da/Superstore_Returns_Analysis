# Superstore Returns Analysis Report

## Table of Contents

- [Project Introduction](#project-introduction)
    - [Superstore Returns Analysis](#superstore-returns-analysis)
- [Objective](#objective)
- [Analysis Outline](#analysis-outline)
- [Executive Summary](#executive-summary)
    - [Conclusion](#conclusion)
    - [Key Findings](#key-findings)

## Project Introduction

In this project, I am preparing a report for the CEO of the Superstore to help them understand the reasons behind the increase in customer order returns and offer possible ideas on how to reduce the volume of returned orders.

### Superstore Returns Analysis
Full Superstore Returns Analysis Tableau project link.

Link: [Superstore Returns Analysis](https://public.tableau.com/app/profile/jason.do5779/viz/Sprint4Project_16841181812540/SuperstoreReturnAnalysisStory)

## Objective

The CEO of Superstore is giving me the task of identifying which items are being returned, which customers are unsatisfied, and what is the primary cause of the increase in returned orders. The key focus areas include determining which markets are unsatisfied, which products are the most returned, which season is most prone to this issue, and what is the cause of the increase in returns.

## Analysis Outline

- Made the Returned field into a calculated field where the null values are 0 and the Yes values are 1.

- Built a heatmap showing the return rate state to find geographic concentrations of returned orders

![image](https://github.com/jasondo-da/Superstore_Returns_Analysis/assets/138195365/d04c18b0-05df-4af6-a008-cc09a268c152)

- Created a bar chart showing the return rate by product category and sub-category and compared the profitability of each product sub-category to find which returns are the most financially damaging

![image](https://github.com/jasondo-da/Superstore_Returns_Analysis/assets/138195365/c01328f7-21bb-498f-a8e9-f5c1b664605d)

- Searched for customers with the highest number of returns and ranked them from highest to lowest on a bar graph

- Recorded the return rate for each month to see if there is a seasonal effect on returned orders

- Displayed a scatterplot showing the correlation between total sales and total returns to see if there is a correlation between total sales and the number of returns

- Compiled all of the findings into a dashboard for quick access to all the information 

![image](https://github.com/jasondo-da/Superstore_Returns_Analysis/assets/138195365/7dee3b73-7e71-4d82-a66d-9494865e3360)

## Executive Summary

### Conclusion

In conclusion, the "tables" and "bookcases" sub-categories should be audited for any packaging or manufacturing defects since these two categories have relatively high return rates and are also the profit loss leaders of all sub-categories. Geographically, there also needs to be a logistics audit for stores in California, Oregon, Washington, and Utah since these states have the highest return rates when compared to other central and east coast states. 

### Key Findings

- West Coast stores show a significantly above-average number of returned orders and these stores should go through a logistics audit to see if there are any issues with the manufacturers and/or shipping methods and storage methods. 

- Tables and bookcases are the top significant loss leaders out of all sub-categories and those two sub-categories should be audited along the supply chain to see if any issues are damaging these product lines or if it is a manufacturing issue

