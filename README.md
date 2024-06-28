
# Sales Insights

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

##  Statement
Sales Manager:

Hi !

I hope you are doing well. We need to improve our internet sales reports and want to move from static reports to visual dashboards.

Essentially, we want to focus it on how much we have sold of what products, to which clients and how it has been over time.

Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also.

We measure our numbers against budget so I added that in a spreadsheet so we can compare our values against performance.

The budget is for 2024 and we usually look 2 years back in time when we do analysis of sales. Let me know if you need anything else!

Sales Manager

## Business Request & User Stories
The business request for this data analyst project was an executive sales report 
for sales managers. Based on the request that was made by the business we are 
following user stories were defined to fulfill delivery and ensure that 
acceptance criterions were maintained throughout the project.

Snapshot of Business Case :

![image](https://github.com/Sahil176076/Sales-Insights/assets/157201766/4c467baa-5a53-46a8-89cb-8e0d1186bf96)



# Steps followed 
# 1.Data Cleansing & Transformation By (SQL)
To create the necessary data model for doing analysis and fulfilling the business 
needs defined in the user stories the following tables were extracted using SQL
One data source (sales budgets) was provided in Excel format and was
connected to the data model in a later step of the process.
Below are the SQL statements for cleansing and transforming necessary data.

DIM_CALENDAR:

Snapshot :

![image](https://github.com/Sahil176076/Sales-Insights/assets/157201766/dea81835-58e8-4e0a-94e2-2c38f3abc0f2)

DIM_CUSTOMER:

Snapshot:

![image](https://github.com/Sahil176076/Sales-Insights/assets/157201766/e5d97227-b640-4fc8-9a2b-57436cdce1b8)

DIM_PRODUCT:

Snapshot:![image](https://github.com/Sahil176076/Sales-Insights/assets/157201766/9c8ceab7-5c3b-4a52-888e-271ab95cccd8)

DIM_INTERNET_SALE:

Snapshot:

![internate sale img](https://github.com/Sahil176076/Sales-Insights/assets/157201766/2dbf44d2-0862-4803-9e07-a64a7fdf51b6)

SALE BUDGET:

Excelsheet:[SalesBudget.xlsx](https://github.com/user-attachments/files/16024403/SalesBudget.xlsx)

# 2.DATA MODEL :
Below is a screenshot of the data model after cleansed and prepared tables 
were read into Power Bl.
This data model also shows how FACT, Budget has been connected to FACT 
Internet Sales and other necessary DIM tables

Snapshot:

![model img](https://github.com/Sahil176076/Sales-Insights/assets/157201766/f3b144ed-3fa7-451d-a341-319c4bcc0dce)

# 3.Sales Management Dashboard:
The finished sales management dashboard with one page with works as a 
dashboard and overview, with two other pages focused on combining tables for 
necessary details and visualizations to show sales over time, per customer and 
per product.

This dashboard indicates the the sales month-wise , year-wise , w.r.t customer and product , city-wise ; and gives the visualizations of sales at realtime  as asked by sales manager .

Snapshot :

![sales overview img](https://github.com/Sahil176076/Sales-Insights/assets/157201766/14e5b061-83e4-4d65-a6ab-bdd203c0d124)

Customer Dashboard indicates sales in terms of customer allocating from different cities or at different month and year.


Snapshot of Customer Dashboard :

![customer img](https://github.com/Sahil176076/Sales-Insights/assets/157201766/2df0a7e4-f587-4737-a4ab-b4beba1798ca)


Product Dashboard indicates sales in terms of product allocating from different cities or at different month and year.

Snapshot of Product Dashboard :

![product](https://github.com/Sahil176076/Sales-Insights/assets/157201766/3a93dc9e-cde2-4246-81ae-edbfb7daf54a)


# 4.Outcome:
As asked by the Sales Manager of different dashboard regarding the sales , i provided him three dashboard one of Overall Sales of his company , second is  Sales by product and third is Sales by customers.
These visualizations are made easy to use and can give clear visuals.



