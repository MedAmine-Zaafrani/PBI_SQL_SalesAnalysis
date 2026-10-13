# Internet Sales Analysis: SQL + Power BI

A business analysis project that turns a Sales Manager's request into two interactive Power BI dashboards, tracking internet sales by customer, product and time, against budget.

**Tools:** SQL Server (AdventureWorksDW2019), Power Query, Power BI, DAX

![Sales Overview](images/sales_overview.png)

![Customer Details](images/customer_details.png)

## Business request

The Sales Manager wanted to move from static reports to visual dashboards showing what is sold, to which customers, and how sales evolve over time against budget. Each sales person works on different customers and products, so the dashboards had to be filterable. The request was formalised into 4 user stories with acceptance criteria (see `Business Demand`).

## What I did

- **Requirements analysis:** translated the business request into user stories and acceptance criteria.
- **Data cleansing and transformation (SQL):** wrote queries to extract, clean and transform the data into 3 dimension tables (Calendar, Customers, Products) and a sales fact table, and integrated the monthly budget from Excel.
- **Data modelling:** designed a star-schema model in Power BI.
- **KPIs and DAX:** defined sales, budget and variance measures.
- **Dashboards:** built 2 interactive pages, with slicers by year, month, city, category and product.

![Data model](images/data_model.png)

## Dashboards

**Sales Overview:** KPI card (sales vs budget), sales by product category, sales and budget by month, top 10 customers, top 10 products, and a map of sales by customer city.

**Customer Details:** sales and budget cards, monthly trend, top 10 customers, sales map, and a customer-by-month matrix for sales follow-up.

## Repository

```
Business Demand/              Business request and user stories
Cleansing & transformation/   SQL queries for the dimension and fact tables
images/                       Dashboard and data model screenshots
sales.pbix                    Power BI report
```

## Author

**Mohamed Amine Zaafrani**, Information Systems Engineering (Master's)
[LinkedIn](https://www.linkedin.com/in/mohamed-amine-zaafrani)
