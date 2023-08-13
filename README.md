# Analytics_Projects-Portfolio

# Project 1 - Datamart Building and Hierarchy based Sales Data Analysis

## Business Case:
In this Project you need to work with the data of many companies which deals with variety of products. You task is to extract the data from main database using SSIS and create staging area then create DataMart in SQL Server. You should track KPI for Sale, creates creative Charts showing sales by month and year, analyse high value customers and products level trends.
Also, you should be able to drilldown to product and customer levels for further details. Your report should have comparison of Actual values verses Budge values of Sales.

## Key steps followed during the project are follows:
1. Staging Area of Datawarehouse has been created using SSIS and then all raw data has been imported to SQL Server.
2. In SQL Server CORE Layer has been created for Dimension and Fact tables using Stored Procedures.
3. Star Schema has been generated from these tables.
4. Views has been generated from Core Layer.
5. Power BI Dashboard containing Executive Dashboard, Customer and Product Level Dashboards has been created using views of the Core Layer Data.

## Key Insights derived:
1.	Revenue for the whole year is 547M. 
2.	Geshirrspüler has the highest Revenue from 2019-2023.
3.	Metra has the highest Revenue from 2019-2023.
4.	Customer Corporate Express Deutschland has the highest Revenue of 547 M from 2019-2023.
5.	VL-Gebiet Müller is the Sales Manager having the highest Revenue for all years.
6.	Donut Chart for Revenue verses sales plan by sales channel shows that Kaüfhauser has highest Revenue from 2019-2023.


## Result and conclusion from Dashboard:

1.	Revenue data for all products hierarchies from year 2019 to 2023 and Revenue Plan data from 2021-2023
2.	Revenue Plan Card shows the predicted Revenue for selected year from 2021-2023. Then we can compare Revenue and predicted Revenue from both cards.
3.	We can combine month and year slicer with other charts to filter the product and customer with highest sale value as per year and month. 
4.	We can a compare actual and budget sales values for Products as well as Customers for all 3 Hierarchy levels from the Product and Customer Matrix.
5.	We can also compare actual and budget sales values for Top Products as well as Top Customers.
6.	From the Guage chart we can get to know the difference between budget value and actual sales value for particular customer. 
7.	The Guage Chart shows the min value as 0 and maximum value is double of Revenue whereas call value is the actual Revenue from 2019-2023 and Target value is the Budget Revenue (Revenue plan) from 2021-2023.
8.	Hiding slicer panel contains distribution channel slicer which helps to filter the sales values of customers and products. 

## Icons and Logos:
Descriptive Icons have been used to move from one page to another like product, customer, map and executive dashboard. The slicer logo has been used to hide the distribution channel slicer to save space on page. 

## Product and Customer Hierarchy Pages:
Product and Customer hierarchy pages contain more detailed information about customers and products. From the executive dashboard page or Product, we can drill through to the product hierarchy page to see more details about products whereas from customer page we can drill through to customer hierarchy page to see more details of customers.

## Technical Tools used: 
SQL Server management Studio, Visual Studio and Power BI Desktop, 

## Techniques / Skills used:
SQL Server - SQL Server Integration Services, ETL, Datamart, Stored Procedures, Views
Power BI – DAX, Data modelling, Data visualisation.


### Overview of Executive Dashboard
![](Executive-Dashboard.jpg)

### Overview of Product Dashboard
![](Produkt-Dashboard.jpg)

### Overview of Kunden Dashboard 
![](Kunden-Dashboard.jpg)

### Overview of Map Level 
![](Map.jpg)

### Overview of Produkt Hierarchy Level 
![](Produkthierarchie.jpg)

### Overview of Kunden Hierarchy Level 
![](Kundenhierarchie.jpg)



# Project 2 - Personal Financial Tracker Analysis

## Business Problem and Context:
Create the Personal Finance Tracker which will help to maintain and control the financial expenses. The purpose of this project is to provide financial literacy at early age as well as embed analytics in daily life.

## Data Source:
The raw data of average expenses of year 2022 from India created in Excel.

## Procedure followed: 
1.	Raw data has been created in Excel and then imported to Power BI. 
2.	ETL has been performed on data using Power BI and then clean data has been used further to create Dashboard in Power BI.

## Key Insights Derived:
1.	From the Report KPI's we help us to get insights about the net worth, the accuracy of spending pattern, status of saving targets, the best and worst financial months as per expense and savings.
2.	slicer helps to filter data as per year and month.
3.	Line chart helps to know whether money is saved or spent in comparison to whatever earned.
4.	Tree maps tell us the money spent in different sections as well as its percentage.
5.	Bar charts tells us about the percentage of money saved section wise.


## Result and conclusion from Dashboard:
1.	Highest income is in year 2020 and its value is 593K INR with 17 % total savings (99 K INR)
2.	Maximum spending is on House Rent which is around 37 % and maximum money of around 87 % has been saved in mutual funds. 
3.	Saving % in year 2020 is greater than all-time saving % whereas spending % is lower than all-time spending %.
4.	highest Saving of 27% has been achieved in year 2018.
5.	Line chart shows that till year 2020 saving target id good but then it again lowers.
6.	Saving % decreases from 2018 -2020 whereas it again rises from 2020-2021 and expenses % shows reverse pattern.

## Technical Tools used: 
Excel, Power BI Desktop

## Techniques / Skills used:
7.	Power BI - Data visualisation, DAX, power Query Editor.

### Overview of the Executive Dashboard
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Persönliche_Finanzen_Tracker_Dashboard.jpg)

### Tooltips 
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-1.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-2.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-3.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-4.jpg)


# Project 3 - AdventureWorks Bike Company Data Analysis ()

## Business Problem: 
You've just been hired as a business intelligence analyst by AdventureWorks, a fictional global manufacturing company that produces cycling equipment and accessories. And your role is to help the management team track their KPI’s, things like sales, revenue, profit and returns, compare performance across regions, analyse product-level trends, and identify high-value customers.
But all you've been given is a folder of raw CSV files, which contain information about transaction and return records, products, customers, and sales territories.

## Objective achieved: 
Used Power BI desktop to connect and transform that raw data, built a relational data model, created calculated columns and measures with DAX, and finally, designed an interactive dashboard to help visualize and analyse that data.

## Key Steps followed in Project:
1. Built the executive summary view which contains high level KPI’s (revenue, profit, orders, return rate) , weekly revenue trending chart, cool interactive elements like sliders to zoom in on specific time periods, custom tool tips and a completely custom filter pane.
2. I have Used things like parameters for what if analysis. In this case, how does it change to the price, impact a metric like total profit.
3. I Explored field parameters to make these charts more interactive and dynamic for  end users.
4. I drilled into Power BI's mapping and geospatial tools and also built a customer-level view to drill into performance at the individual customer level and break down different customer profiles and segments.
5. This entire report has been built completely from scratch with nothing but a folder of raw CSV files.

## Key Insights derived:
1. KPI’s for revenue, average daily rates, total nights, average discounts and required parking spaces help to get an overview of the hotel data.
2. Date, hotel and country slicer help to filter the data as needed and KPI’s is changed.
3. A line chart helps to compare the sales development of both hotels for a certain period.
4. The matrix shows an overview of the sales data and the required parking spaces, which helps us to solve our business problem related to the size of the parking lot. The lines highlighted in blue show the highest values.

## Result and Conclusion from the dashboard:
1. Hotel revenue increases from 2018 to 2020. The highest revenue is in 2019 from 2018 to 2020 and its value is $26.63 million for both hotels and all countries. Among both hotels, the 2019 value is highest for the city hotel and is $7.19 million for all countries.
2. Since the parking percentage is stagnant, we don't have many clues to decide whether we should build a parking lot or not.
3. The Adr increases from 2018-2020. The highest average daily rate is in 2019 between 2018 and 2020 and its value is $119.86 million for both hotels and all countries. For both hotels, the average daily rate is also highest for the city hotel in 2020, valued at $123.02 million for all countries.

   
# Project 4 - HR Analytics Excel 

## Business Problem:
You are working as data Analyst and need to provide interactive and dynamic report using Excel to HR of the company demonstrating the employment information. HR want to know the total no of active employees and employees who are leaving jobs by gender, education, job role, department, age group and marital status so that company can get insights about employment situation. HR also want to know how many employees are satisfies by work.

## Key Insights derived:
1.	This dashboard is completely interactive and dynamic.
2.	HR department can get insights on how the companies are performing with respect to educational fields, departments and gender.
3.	Mainly this dashboard is focused on attrition which are the employees who are leaving the company. KPI’s gives the overall performance of the company and overall idea about HR Department.
4.	It illustrates how many employees are leaving the company by age, gender, marital status and job role.
5.	We have Slicers like educational field, department and gender by which we can filter visuals and operate dashboard dynamically and data has been changed as per selected educational field, department and gender.
6.	On the top right we have job satisfaction rating which is given by small Donut chart.
7.	Small Donut charts and shapes has been used to show the total employees by gender.
8.	Pie chart helps to know the department wise attrition.
9.	Tree map shows Attrition by job role with its percentage.
10.	Education wise attribution has been shown by Bar Chart whereas attrition by group has been demonstrated by column or frequency chart.
11.	The idea about attrition amongst divorced, single and married employees has been shown by funnel chart.

## Result and conclusion from Dashboard:
1.	Overall active employees for all departments and educational field are 1233 and attrition rate of employees is 16 % with Job Satisfactory rating of 2.6 out of 4. Total number of employees has 1.5 times more males than females with max attrition by bachelors and laboratory technicians. Young employees of R&D department show highest attribution (56.12%). Among the age and marital status highest attrition from employees who are single and having age of 25-34 years. 
2.	Educational filed wise technical degree employees contains 100 active employees and has the highest attrition rate of 24 % but it is         opposite to job satisfactory rating of 3.9 out of 4. Most of employees leaving jobs from this field are single males which are between age   group of 25-34 having bachelor’s degree and job role of research scientist. Highest attrition (62.5%) has been seen in R & D Department in     this educational field.
3.	Employees with Educational filed of marketing are least satisfied with rating of 1.8 out of 4.
4.	Department wise Sales has the highest attrition rate of 21 % whereas R & D has lowest attrition rate of 14 %.

## Technical Tools used: 
MS Excel, MS Power Point.

## Techniques / Skills used:
Power Query Editor, Data visualisation (KPI’s, Slicer, charts and graphs)



# Project 5 – Historical Hotel data Analysis

## Business Problem:
Develop a database to analyse and visualise Hotel Booking Data then build a dashboard using power BI to present to your stakeholders. Dashboard should show the Trends of Revenues, Average daily rates per night, Average discount and required car parking spaces. You need to answer whether hotel revenue and Average daily rate is growing by year and should we increase our parking lot size.

## Data Source:
Historical Hotel data from 2018-2020.

## Key Insights derived:
1.	KPI’s for Revenue, Average daily rates, total nights, average discount and required car spaces helps to get the overview of hotel data. 
2.	Date, hotel type and country Slicers helps to filter the data as per requirement and KPI’s also gets modified.
3.	Line chart helps to compare the sales trend of both hotels for particular duration.
4.	Matrix shows the overview of Revenue data, required parking spaces which helps to decide our business problem related to parking lot size. The blue marked lines show the highest value row.

## Result and conclusion from Dashboard:
1.	The hotel revenue increases from 2018-2020. The highest Revenue is in 2019 among 2018-2020 and its value is $26.63 M for both hotels and all countries. Among both hotels it’s also highest in 2019 for city hotel and has value of 7.19 M $ for all countries.
2.	As parking percentile is stagnant so we don’t have lot of evidence to determine whether we should build a parking lot or not.
3.	The Adr increases from 2018- 2020. The highest Average daily rate is in 2019 among 2018-2020 and its value is $119.86 M for both hotels and  all countries. Among both hotels Average daily rate is also highest in 2020 for city hotel and has value of $123.02 M for all countries.

## Key Steps followed in Project:
1. Build a Database 
2. Analyse and Retrieve Data with SQL (Develop a SQL Query) 
3. Connect Power BI to a Database 
4. Visualize Data in Power BI
5. Summarise our findings

## Technical Tools used: 
SQL Server management Studio, Power BI Desktop.

## Techniques/Skills used:
SQL Server, Power BI, Data visualisation, DAX, Power Query.


# Project 6 - Global Superstore Sales Data Analysis ()

## Business Problem: 
Perform ETL on Global Superstor_2016 dataset present in csv files by importing into Power BI. Create an Interactive dashboard to track KPI’s of sales, quantity sold, Delivery Days and Products Returned, compare sales by segments and market, analyse high value customers and product level trends.

## Data Source:
 Open source Global Superstor_2016 database.

## Key Insights Derived: 
1. Sales amount, quantity of items sold, average no of delivery days required, and number of orders returns has been calculated using KPI’s.
2. Slicers helps to filter the data as per year.
3. The is suitability of region for the product selling of products has been shown by Map which can help to enhance our business if needed.
4. Pie chart tells us the sales value and its percentage by segment
5. Donut chart provides sales details as per market.
6. Top N filter option in combination with Bar charts helps to find the top 10 customers, top 10 Products having highest profit and highest loss values.

## Result and Conclusion from Dashboard:
1. Sale as well as quantity sold increases from 2012 -2015 with lowest in 2012 and highest in 2015
2. Overall highest Sales has value of $ 12.64 M and Quantity sold as 178 K among all years. The Highest value of sale ($ 4.3 M) is in 2015 and      highest sold Quantity as 60.62 K. 
3. In 2015, Consumer segment has highest sale ($ 2.14 M) which is approximately half of total sales in that year. Asia Pacific is the biggest       market for sale ($1.37 M) having 31.93 % of total sales.
4. Tamara Chand is the highest selling customer among 2012-2015 and in 2015.
5. Motorola smart phone full size has the highest profit in 2015 and Cannon imageCLASS 2200 Advance Copier has the highest profit among 2012        -2015.
6. highest loss having product is the Bewis computer table fully assembled in 2015 as well as among 2012 -2015.

## Key Steps followed in Project:
1. Connecting Database with Power BI Desktop. 
2. Analysing the tables and relations. 
3. Data Cleaning using Power Query Editor with DAX (Data Analysis Expressions). 
4. Developing an Interactive BI Dashboard / Report.

## Technical Tools used: 
Excel, Power BI Desktop.

## Techniques / Skills used:
Power BI - Data visualisation, DAX, Power Query Editor.

