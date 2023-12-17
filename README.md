# Maven NorthWind-Traders challenge
A dashboard to help Northwind Traders' executives understand the company's performance 
# Introduction 
"For this challenge, I worked as a BI developer for Northwind Traders, a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world."
## Objectives
To build  a top-level KPI dashboard for the executive team.
The dashboard should focus on key areas such as
* Sales trends
* Product performance
* Key customers
* Shipping cost
# Data Source
The data was obtained from the Maven Analytics website. 
# Data preparation/cleaning
* The data was loaded into Power BI and it is a CSV file.
* The data has 7 different tables
* Not much cleaning was done for this data set.
* For the customer table; the first row was made as the headers
* For the order_details table; a new column was added for the price paid.
  This was calculated by using
  = ([unitprice] * [Quantity] * (1-[discount])
* Because the data is already cleaned, the relationship between the data was already formed. 



# Visualization
The visualization was done using Power Bi


<img width="684" alt="image" src="https://github.com/Imoniyi/NorthWind-Traders/assets/151396523/0ee3d9d0-57ba-4867-a7b5-1e0956f32ba6">

# Findings
* Between the years 2013-2015, a total revenue of £1.27milllion was made. The Northwind traders had 77 products and 830 orders were made within that year. A sum of £64,9400 was spent on shipping of the from 2013-2015 products. Northwind Traders had a total of 91 customers from 21 different countries in those years.
* The highest revenue was made in the month of April 2015. The lowest revenue was   made in the month of May 2015. 
* ﻿﻿At £110,277.305, QUICK(customer) had the highest Revenue and was 120.64% higher than HUNGO, which had the lowest Revenue at £49,979.905.
* Beverages accounted for 21.16% of Revenue which makes it the category that generates the most Revenue followed by 

# Recommendations
* For the sales trend, it is important to study it and understand why there is a decrease or increase in revenue in a specific period of time.
* Ensure that the products that get shipped out the most are never out of stock and the delivery is made on time.
* Customer feedback and surveys can help in knowing how to best serve your customers. They can also give their opinion on your products. 
* Incentives or discounts can be given to the top customers

  


