# OBJECTIVE AND VISUALISATION

✅Total sales and Profit:


![TOTAL SALES AND PROFIT](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/7043670f-64f8-40ff-ba08-986e78c037f8)


✅Total sales per product:


![SALES BY PRODUCT](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/c76b9c6a-cc6d-43e1-9d34-1a7bc0dd6bce)


✅Average sales per each product category:


![AVERAGE SALE BY SUB CATEGORY](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/37947349-138c-49c5-96a1-9308b1d02cdb)


✅ Date Filter for relationship with time:


![FILTER OVER DATE AND PERIOD](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/59144e3d-ab7f-45d3-b878-c17382bfbbed)


✅Maximum delivery time & Minimum delivery time:


![DELIVERY DAYS](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/25d97543-bc89-4b71-8ad3-a7e1d31a0ca7)


✅what is the overall trend in sales over time:


![SALES TREND OVER TIME](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/7d6ee463-022d-4031-80bd-a96f1e9ecaff)


✅What is the distribution of sales per order? 


![SALES BY ORDER ](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/79fb7a0d-cfe8-4ccb-8846-f7cb3e2b7436)


✅Can you identify any outliers in sales_per_order?


![AVERAGE SALE OVER DISCOUNT](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/b7a6e031-22cc-44ca-82dd-017ece0cc86d)


✅How does order item discount affect both sales per order and profit per order? 


![SALES OVER DISCOUNT](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/e53c848e-bb7a-4241-bbad-182194381582)


✅Different shipping types impact the delivery status of orders? 


![SALES BY SEGMENT](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/a5ae5180-f5d4-4d64-b5bc-47858d6e06f4)


✅Are there any customer regions or countries that stand out in terms of sales or profit performance?


![TOTAL SALE BY REGION](https://github.com/S-ahmed75/DATA_ANALYST/assets/41890981/a3891ea0-c9bc-4168-afa4-e60c4a94b68c)


# Data Cleaning and Data Processing

•	The data was in 12 CSVs and directly loaded to POWER BI

•	I deleted duplicate columns containing same order ids.

•	Converted the revenue column as dollar exchange.

•	Extracted the duration of shipment as days.

•	Extracted the minimum and maximum days of shipment.

•	Created new formula for distribution of sales.

•	Extracted names of days, months, quarter number.

NOTE:

I did not delete rows with nulls, I only filtered them out. After the model was transformed and loaded. I sorted the date via different columns to study the data patterns. I discovered that some of the ride durations were negative so we filtered those ones out.

# Insights and Recommendations

# Insights
 
•  Sales Performance: The company has sold a total of $2.29 million in the past month, which is a significant increase from the previous month.

•  Profit: The total profit for the throughout period is $286.40k. 

•  Top Selling Segments: Consumer and Home Office are the top-selling segments, accounting for 50.70 million and 30.67 million respectively, out of the total sales of $2.29 million. 

•  Top Selling Products: Canon Copier Machine and Electric Punch Binding Machine are the top-selling products. 

•  Sales Trend: The sales trend appears to be positive, but it is stay low or nothing in third quarter whereas there much demanding in fourth quarter.

# Specific Recommendations

•	The casual consumer has more than half of total sales which can be targeted to achieve more sales.

•	On shipment mode Standard class is more acceptable by end user rather than other mode. We need to improve delivery standards on this category.

•	Smaller product which has no impact on sales can be removed.

# General Recommendations

•	In general marketing efforts should be focused June and December as that are the end of corporate year for most of the companies.

•	We can start maintenance services charges for high price product like copier machine, video conferring unit, and so on.

•	North America appears to be the strongest performing region. We can decrease marketing budget in this region and invest others to boost sales in all.

•	We can discuss over reducing the maximum time of delivery for better client satisfaction.


# Major Learnings

•	Some operations are O(n^2), so we need to delay these steps till after the data model is ready. For e.g. Sorting and Deleting rows with blanks, nulls etc. Meaning that once the index has been assigned to rows it is a compute-heavy task to delete unwanted rows and then refresh the index for every row deleted.

•	Documenting the steps of your work is more important than doing the work once and forgetting what you did the last time.



