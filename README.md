# Adventureworks Business Analytics

## Author
- Name: Moses Chen
- Email: yuhsin.moses.chen@gmail.com

## Project Detail
This project can be divided into three main parts. First, various tables are preprocessed in the power query editor. This table includes both **fact table**, including sales/return, and **dimensional table**, including calendar/product name/customers. In this stage, data quality has been inspected, and missing values/ anomalies have been fixed. All the necessary data management tasks, such as pivoting, merging, appending, or creating new columns, have been carried out.   

Second, the relational data model was built up in the following form. This is based on the logical relationship between tables. Also, we can easily observe the data flow starting from the top of the graph to the ground.
![image](https://github.com/user-attachments/assets/51e48fc4-ddfa-476f-a8ff-4779513b8526)

Third, there are many DAX languages that have been written, including Measures and Column calculations. These are the preparations for the insightful visualization report. Next, in the report, there are four pages, from the general result to details.
In the general dashboard, you can see clear KPI,s such as profit, revenue, best-selling category, revenue trend, etc. Also with the icon on the left-hand side to direct to other pages.
![image](https://github.com/user-attachments/assets/43bf07fb-268e-4b5c-9893-d5278322651f)

In the next page, you can see the world map. Based on the size of a dot, you can know the selling performance. Once you hover the mouse on those dots, you will see more information about that location.
![image](https://github.com/user-attachments/assets/b5b82995-7d98-45bd-afcb-16a63b0f628f)

Next, we can use **drill through** from the product in the general dashboard to the product detail dashboard. Here, first, I compared last month's performance with the previous month's result, which was multiplied by 1.1. Below, you can also see the parameter
dragging bar, which is for visualizing the profit change based on the price adjustment. Last, you can also see the specific product's cost, profit, return, revenue and return rate in the graph with the filter on the left-hand side.
![image](https://github.com/user-attachments/assets/b9413c84-114f-4659-b880-225296d261f4)

In the next dashboard, we dive into the customer details. There, we can see the trend of the customer change, the income level of the customer, and the customer's occupation. Furthermore, we can also know the top customer, his/her order and the revenue we earn from them.
There are also slicers to drill into details in different years.
![image](https://github.com/user-attachments/assets/7e937979-1fe3-4121-a7e3-b0e7993a9dae)

This report is made for a different audience, from managers to colleagues. There are very general KPIs but also detailed customer or product information.

## Note
The project is my personal learning result from Maven Analytics Courses. The content would/should not be used for any business reason. It is only for a showcase for personal power BI skills.
