# Adventure-Cycles-Financial-Data-Analysis
A project worked on using Power Bi and Tableau. Paper presented for conclusions.

AdventureWorks Cycle Presentation Paper

# INTRODUCTION
Adventure Works Cycles is a global manufacturer that supplies commercial markets in North
America, Europe, and Asia with metal and composite bicycles. Adventure Works Cycles
headquarters is located in Bothell, Washington with a total of 500 employees. Additionally,
across its market base, Adventure Works Cycles employs a number of regional sales teams.
Adventure Works Cycles recently acquired Importadores Neptuno, a small manufacturing facility
in Mexico. Several important supporting parts for the Adventure Works Cycles product range are
produced by Importadores Neptuno. For final product assembly, these subcomponents are
transported to the headquarters in Bothell. The touring bicycle product category was reduced to
being produced and distributed solely by Importadores Neptuno.
Now, Adventure Works Cycles wants to increase its market share. It wants to create and
implement an all-encompassing business intelligence solution that targets its top clients,
increases product availability, and lowers the cost of sales by cutting production costs.



# PROBLEM STATEMENT

We are looking to track core business KPIs like Gross Margin, Revenue, Profit and Returns and
also compare regional performance across territories, analyze performance and trending at the
product level and forecast future profits and use the data to identify the company's high value
customers.
Business Questions:
1. What is the company’s performance and trend year over year?
2. How did each product perform over the years?
3. What are the buying preferences and customers' profiles?


# Data Sources Gathering and Process of Preparing Dataset

In this project, The AdventureWorks Sales dataset was analyzed using Microsoft Power BI and
Tableau, The steps I took are as follows:
Step 1: Extracted Data from Kaggle
Step 2: Transformed Data
Step 3: Load Data
Step 4: Data Modeling
Step 5: Writing DAX Functions
Step 7: Dashboard Creation

First, cleaned up the data using Power BI, transformation table and made some required
transformations like:
- Removing Product Size (as there is numerical and categorical variable)
- Changing Name into Proper Case
- Combining Names into one column (Prefix + FirstName + LastName)

Then explored the relationships between tables keeping Sales and Returns as Data Tables and
connecting them to all the other lookup tables.
We then added a few additional columns using the data.
TABLE COLUMN
AW_Calendar Year, Start of Year, Start of Month
Month Name, Start of Week, Day
Name, Day_of_Week
Weekend
AW_Customer Income Level

Explored the data and created the maximum measures we could using DAX Functions in the data
This is a snapshot of my connected tables.
We explored some DAX(Data analysis Expressions). The model comprises the relationships and
data analysis expressions.

![image](https://user-images.githubusercontent.com/80241823/212252274-a63b4831-14a2-42d5-9767-27e2b10fdcfd.png)

Best practices considered while creating dashboards were:
➔ Making priorities apparent with size and location.
➔ Focusing on the essentials.
➔ Setting up metrics logically.
➔ Making it simple to use.
➔ Keep it uniform.
➔ Labeling things clearly


#INTERPRETATIONS

Figure 1. ![image](https://user-images.githubusercontent.com/80241823/212252529-a27a5572-941d-4bd9-9b5a-eb370764c450.png)

Below are the KPIs depicting the numbers for Gross Margin, Profit, Revenue, Orders and
Returns. For tracking core business KPIs like Gross Margin, Profit and Returns below is alo the
Goal to compare the performance of each factor to see if there is an increase or decreasing trend.
Monthly Gross Margin is at a dip when compared to last month by 58.26% which needs more
concentration on.

Monthly Profits on a margin line can improve forward needs a little eye on.
Monthly Revenue has been doing good but has scope to improve more in coming months.
Monthly Orders are less by 19, need to verify which are the orders that are performing low.
Monthly Returns is better compared to last month., the returns have reduced by 3.

Figure 2. ![image](https://user-images.githubusercontent.com/80241823/212252654-70e67982-bdea-4eee-9134-c4b52e87823b.png)

We used the gauge feature in PowerBI to visually see the difference between the current status in
orders, revenue, and return. Company wanted to see if there was a 10% increase in Orders,
Revenue and Target. The below visual shows that the Order has 236 orders left to reach the
target. Revenue is less by $0.12M and good improvement in the returns by a reduced number of
20.

Figure 3. ![image](https://user-images.githubusercontent.com/80241823/212252833-0acf6a00-174a-43db-96aa-ae4c21d0ce90.png)

In the illustrations below, we decide to use a bar graph to display the top products by gross
margin, orders, and returns. We believe the bar graph was the best way to represent this
categorical data. Below are the Top Performing Products in Gross Margin, Orders and Returns.

Figure 4. ![image](https://user-images.githubusercontent.com/80241823/212252890-46394d74-62f2-408a-be36-db7d7e588522.png)

For the gross margin from 2015 to 2017 we used a line graph to display the trend over the years.
There is a positive trend as shown below which is a positive sign, but the company has had dips
in its performance which needs a cautious look into it for further falls. We included the forecast
feature to predict the gross margin for the upcoming year.

To display the distribution of the gross margin by category, we used a donut chart. Accessories
have been the majority taking 42.28% of the total categories.
We used a treemap to display the gross margin by country so that viewers may capture the
distribution between the countries. Picture shows that the below countries have been doing
equally well in their performance with Canada, France, USA, UK being at the top of the table.

Figure 5:![image](https://user-images.githubusercontent.com/80241823/212252907-c526b0c5-a89b-4788-917d-dd85d606d57b.png)

To display the categorical data of the education level of the customers we used the pie chart.
To help us and the viewers identify the income levels of the customers we used a bar chart.
In our analysis we were able to identify the different occupations that purchased products. We
further broke down the data into male vs females in each occupation. The stacked bar chart
allowed us to best show this data.

Orders were most frequently placed by people with average incomes, and fewest by people with
very high incomes.
In a similar vein, when compared to the Clerical and Manual category, professionals are placing
higher orders. Nearly equal numbers of men and women work as professionals placing orders.
For a year, Mr. Dalton Perez's order of 26 was the largest of any customer.
When comparing Education Level, customers with only a partial high school diploma made up
the least percentage of customers, at 56.35%, along with those with bachelor's degrees and some
college.

Figure 6 : ![image](https://user-images.githubusercontent.com/80241823/212253006-6398ebd8-bbba-454d-b3e5-8343c0bc46c2.png)

In the figure below, we used a bar chart to display that the 30 oz Water Bottle had the highest
order count. It was higher than Mountain Bottle Cage, which had the lowest order count.﻿
In Product Performance Across Years, Mountain Bikes did exceptionally well in the year 2015,
but has been under performing in later years.

Figure 7 : ![image](https://user-images.githubusercontent.com/80241823/212253050-fefa47f7-ffd9-4c0a-8ece-13cf1ee5a635.png)

As mentioned in Figure 7, we used a bar chart to display our categorical data from the
highest to lowest value.
Mountain Bikes are on the top of the list in profitable products. Comparing where Racing
Socks have been the least profitable product.

Figure 8:![image](https://user-images.githubusercontent.com/80241823/212253080-96998b38-ceee-473a-9a4b-e32172a35c20.png)

To display the profit of each country by category we used the stacked bar chart. We found this
chart to be the best chart to display the data for each category.
All the countries have been in a proper competition, and it is just by few points that each
country's performance is differing.

Figure 9:![image](https://user-images.githubusercontent.com/80241823/212253097-dbffa25f-b240-4cd6-a0bf-fc74907e59c6.png)

In order to identify the product that was frequently returned, we used a bar chart that organized
the data from the highest to lowest value. We included the count above each product to determine
which item was frequently returned, the 30 oz water bottle.
Out of 25164 Orders, 1809 have been returned, which is 7% of total orders which is acceptable.

Figure 10: ![image](https://user-images.githubusercontent.com/80241823/212253124-e86ee51e-1955-4d97-a607-876b77e85322.png)

In the top illustration for the “Total Order vs Total Returns” we used a line and clustered column
chart to best display the data. This chart allowed us to compare two measures in one visual. We
can visually see the number of orders and returns from 2015-2017.
Total Orders vs Total Returns shows that With the increase in Total Orders , Returns also have an
extensive increase.

In the bottom illustration labeled “Total Returns by Categories” we used an area chart to display
the magnitude of the total number of returns for each category.
Image Total Returns by Category shows that, Accessories are the highest products returned


# FINDINGS AND CONCLUSION

According to the descriptive analysis we performed on the AdventureWorks Cycle dataset, we
found the following results:
GROSS MARGIN

★ There was a steady increase in gross margin from 2015 to 2017. ( Figure 11. The chart
below is from Tableau)

★ Canada was the top performing country compared to the US, France, Germany, Australia,
and United Kingdom.

★ The accessories category has the highest gross margin.

# PRODUCT PERFORMANCE

★ There are 293 different products altogether across 4 different product categories and 37
different subcategories.

★ A total of 25K orders have been placed over the last three years from all regions, and the
30 oz water bottle came in first place in terms of demand.

★ In comparison to other regions, Australia had the most orders

★ The mountain bike was the best-performing product in terms of profit, and the
Long-Sleeve Logo Jersey in size M was the worst-performing of the 292 other products.
Bikes have produced the biggest profits out of the four categories.

★ The United States accounted for 29.56% of TotalProfit.Bikes had the highest average
TotalProfit, followed by Accessories and Clothing.

★ The 30 oz water bottle had the largest returns and was also the product with the highest
orders, therefore the corporation needs to put more focus on it going forward.

★ When compared to the period prior to July 2016, the overall number of orders and returns
climbed higher.

★ TotalOrders had the most interesting recent trend and started trending up on Thursday,
September 1, 2016, rising by 36.86% (578) in 9 months.

★ TotalReturns for Accessories started trending up on Saturday, October 1, 2016, rising by
19.51% (16) in 8 months.

# CUSTOMER ANALYSIS

★ Average income earners were the highest in numbers to place orders and the least were
from the category of very high income earners.

★ Similarly the professionals are placing high orders when compared to the Clerical and
Manual category. The male and female ratio is almost equal in number in professionals
placing order.

★ Mr. Dalton Perez was the customer with the highest order of 26 for a year.

★ When comparing Education Level 56.35% comprised of customers with Bachelors and
Partial College

★ Customers with partial high school were the least comprised.


#RECOMMENDATIONS

Based on our analysis, we recommend AdventureWorks to improve the quality of the 30 oz.
water bottle. We noticed that this specified product was the most frequently bought product, but
also the product with the highest returns.
In addition, out of all of the different occupations, clerical and manual labor customers were the
bottom two.We also recommend increasing customer concentrating on the clerical and manual
labor customers. We recommend increasing marketing tools and coming up with customized
products to promote the purchases for the particular customer base.

# Data Dictionary

DATA TABLE VARIABLES DEFINITION

AW_Calendar Date Format: 1/1/2015

Describes the date format of the data from 2015-2017

AW_Calendar Weekend Categorises date into Weekday and Weekend

AW_Customer_Lookup Customer Name First Name Last Name

Describes the names of the customers who purchased
products

AW_Customer_Lookup Gender Male/Female

AW_Customer_Lookup Income Level Categorised Annual income into different buckets
(Income >= 150,000 - Very High, Income >= 100,000 -
High, Income >= 50,000 - Average, Income < 50,000 -
Low)

AW_Customer_Lookup Occupation Clerical, Management, Manual, Professional, Skilled
Manual.

AW_Product_Lookup Product Name There are in total 293 Products.

AW_Product_Lookup Product Cost Costs that are incurred to create a product that is intended
for sale to customers.

AW_Product_Lookup Product Price Product Price is the process of determining the
quantitative value of a product based on both internal and
external factors.

AW_Product_Lookup AvgRetailPrice AvgRetailPrice is the average of all the Product Prices.

AW_Product_Lookup ProductModels ProductModels is the count of all the Models in a
product.

AW_Product_Categories Category Name Product are categorized into 4 groups
Bikes, Components, Clothing, Accessories

AW_Product_Subcategories
Subcategory Name Product further categorized into Subcategories. There are 37 Subcategories in total.

AW_Returns ReturnDate Date when the product was returned.

AW_Returns %ofTotalReturns Percentage of all the Returns.

AW_Returns ReturnRate Percentage of returns happened

AW_Returns QuantityReturned Summation of all the return quantity.

AW_Returns TotalReturns Count of all the returns.

AW_Sales OrderDate The date on which this Decision and Order becomes final
and effective.

AW_Sales StockDate The day an investor places the buy order in the market or
on an exchange.

AW_Sales ALLOrders All Orders together.

AW_Sales %ofALLOrders Percentage of all orders placed

AW_Sales Gross Margin Gross margin is the amount of money a company has left
after subtracting all direct costs of producing or purchasing the goods or services it sells. The higher the
gross margin, the more money the company is able to contribute to its indirect costs and other expenses like
interest.

AW_Sales OrderTarget Adding 10% of the previous month's order to establish a Target to see if we have met them.

AW_Sales ReturnTarget Adding 10% of the previous month's returns to establish a Target to see if we have a lesser number than before.

AW_Sales RevenueTarget Adding 10% of the previous month's revenue to establish a Target to see if we have met them.

AW_Sales PreviousMonthGrossMargin Calculating Previous months Gross Margin for
comparison.

AW_Sales PreviousMonthProfit Calculating Previous months Profit For comparison

AW_Sales PreviousMonthReturns Calculating Previous months Returns for comparison

AW_Sales PreviousMonthRevenue Calculating Previous months Revenue for comparison

AW_Sales PreviousMonthOrder Calculating Previous months Order for comparison

AW_Sales TotalCost The sum of all costs incurred by a firm in producing a
certain level of output.

AW_Sales TotalOrders All the orders placed.

AW_Sales TotalProfit Total Profit is how much money is left over after
factoring in all of your business expenses.

AW_Sales TotalRevenue The amount of money a company brings in from selling
its goods and services

AW_Sales WeekendOrders The number of Orders placed on weekends

AW_Sales YTD Revenue The amount of money an individual has earned from Jan.
1 to the current date

AW_Territories_Lookup Region A region is a specific area that has common features. A region may have common natural or artificial features. A region can be based on language, government, religion,
type of flora and fauna or climate.

AW_Territories_Lookup Country A nation with its own government, occupying a particular territory

AW_Territories_Lookup Continent Africa, Antarctica, Asia, Australia, Europe, North
America, South America


# REFERENCES

Data set

https://www.kaggle.com/datasets/ukveteran/adventure-works?select=AdventureWorks_Customer
s.csv.

#Presentation link

https://www.canva.com/design/DAFUNHlGrVY/wsSBID9MB_aQQb8JlBhd7A/view?utm_cont
ent=DAFUNHlGrVY&utm_campaign=designshare&utm_medium=link&utm_source=publishsh
arelink
