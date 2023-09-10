# Business Insight

# Project Overview
AtliQ Hardware has grown rapidly in recent years, and they have decided to implement data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data-driven decisions. This project hopes to give answers to the questions of stakeholders in terms of all the aspects like finance, sales, marketing, and supply chain.

# Tech stacks
1. SQL
2. Power BI desktop

3. Excel

4. DAX language

5. DAX Studio (Optimizing the report)
6. Project chart file

# PowerBI techniques Learnt
What are all the questions that should be asked before starting the project?

Creating calculated columns

creating measures using the DAX language

Data modeling

Using Bookmarks to switch between two visuals

Page navigation with buttons

Using the divide function to prevent zero division errors

creating data table using m language

Dynamic titles based on the applied filters

Using KPI indicators

Conditional formatting of the values in visuals using icons or background color

Data validation techniques

PowerBi services

Publishing reports to PowerBi services

Setting up a personal gateway to set up the auto-refresh of data

PowerBi App creation

Collaboration, workspace, and access permissions in PowerBi services

And more 😅

# Business Vocubalry 

Gross price

Pre-invoice deductions

Post-Invoice deductions

Net Invoice sale

Gross Margin

Net sales

Net profit

COGC - cost of goods sold

YTD - Year-to-Date

YTG - Year to Go

Direct

Retailer

Distributors

Consumer

# Company’s background


AltiQ Hardware is a company that has grown vastly in recent years, and opened business all over the globe. It is a company that sells, computers and computer accessories through three mediums/channel


Retailers

Direct

Distributors

Recently the company has faced an unforeseen loss by opening a store in America based on surveys, intuition, and some Excel analysis also the company’s competitors has a handful of analytics team to perform analysis and make data-driven decision. So, the AltiQ hardware has no other option other than building its analytics team for data-driven insights and decisions in the future to survive better in the industry.


Project kick-off session, where you should get clear of what and why this project is and all other questions you have with regards to the project


# Questions to ask before starting with the dashboard

1. What is the objective of building this PowerBi dashboard?

2. In what terms the success of this project will be measured?

3. What will be the deadline for the project?

4. Do the stakeholders expect a preview before the actual release?

5. What are all the hopes stakeholders have out of this project?

6. What are all the fears the stakeholders have in terms of building this dashboard?

7. Who will be using this dashboard and for what purpose?

8. What are all expectations the stakeholders have, by the completion of this project?

9. What can go wrong while building this project?

10. What are all the resources/ data needed to build this dashboard?

11. Are there any inputs from stakeholders in terms of design and views of the dashboard?

After the project kick-off meetings, the data engineering team has given the data as per the request of the data analytics team, Let’s explore them.


# Dataset Understanding.

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get a good understanding of what are data available.


Dimension table: It will have static data like details of customers and products


Fact table: It will have the data about the transactions


gdb041:

dim_customer

27 distinct markets (ex India, USA, Spain)

75 distinct customers throughout the market

2 types of platforms

Brick & Motors - Physical/offline store

E-commerce - Online Store (Amazon, Flipkart)

Three channels

Retailer

Direct

Distributors

dim_market

27 distinct markets (ex India, USA, Spain)

7 sub-zones

4 regions

APAC

EU

nan

LATAM

dim_product

Divisions

P & A

Peripherals

Accessories

PC

Notebook

Desktop

N & S

Networking

Storage

There are 14 different categories, Like Internal HDD, keyboard

There are different variants available for the same product

fact_forecast_monthly

This table is used to forecast the customer’s needs in advance, which can help in

Higher customer satisfaction

Reduced cost in warehouses for storage purposes

The table is denormalized by the data engineering team, as it is a data warehouse that is aimed to be used for analytical work.

All the dates of the month will be replaced by the start date of the month

It will have all the column names and in the end, it will have the forecast quantity needed by the customer

fact_sales_monthly

This table is more or less is same as the fact_forecase_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056

freight_cost

This table has details of travel cost and other cost for each market with fiscal year

gross_price

Has the details of gross prices with product code

manufacturing_cost

Has the details of manufacturing cost with product code with year

Pre_invoice_dedutions

Has the details of pre-invoice deductions percentage for each customer with year

Post_invoice_deductions

Post invoice deductions and other deductions details

# Importing data into PowerBi

As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

# Data Model

Data modeling plays a vital role and is considered the basement of the report. All the visuals will be built upon the data model.

Poor data modeling affects the overall performance of the report.

Following Good practices of data modeling is a must. Refer to this page to get to know the good practices of https://addendanalytics.com/blog/data-modelling-best-practices/

In this project, we have followed the Snowfall data modeling method.

![image](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/15ffa727-aa56-4e26-9e61-512d2ab23ea0)

# Dashboard designing
Based on the mock-ups received as a requirement, the team will start designing the visuals and create measurements as and when required

# Home view
In-Home view, all the views button will be available. Users will land on a specific view page by clicking the button

Info

Finance View

Sales View

Marketing View

Supply chain View

Executive View

Products

Support

# Overall Report

![image](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/a4911daa-8d67-497b-8b9a-ecd2eb0629d4)

# Finance  View

![Finance](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/f70c4e92-bb95-4c68-a38b-f3fc6ab156c2)

# Sales View

![Sales](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/d7aa03d4-ad92-4c03-a982-56be35ce16d2)

# Marketing View

![Marketing](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/9189e07a-27fe-417b-84ae-a24756fc7eb0)

# Supply Chain View

![Supply Chain](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/d7922a66-ab3f-45a3-89bb-0b04cf1b7de7)

# Executive View

![Executive View](https://github.com/Godaradeep1/Business-Report-360/assets/70376242/261c995b-3200-4121-a973-70339131f7b2)










