# ShyFam_Daily_Income_-_Expenditure_Tracker_Onitiju
The ShyFam Daily Income and Expenditure Tracker collects household financial data using KoboToolbox and visualizes it in Power BI. It records daily income, spending, savings, and debt activities. Data is stored in Excel and transformed into interactive dashboards to monitor cash flow and support better financial decisions.

# Overview
The ShyFam Daily Income and Expenditure Tracker is a data-driven household financial monitoring system designed to collect, manage, and visualize daily financial transactions within a family.
The system uses KoboToolbox for real-time mobile data collection and Microsoft Power BI for data transformation, analysis, and interactive visualization.
This project demonstrates how digital data collection tools and business intelligence platforms can be integrated to monitor financial behavior, improve transparency, and support better household financial planning.

The tracker records:
Daily income

Household spending

Savings

Debt collection

Debt repayment

The data is automatically structured in Excel and connected to Power BI dashboards for analysis and decision-making

# Project Architecture

The workflow of the project is illustrated below:

KoboToolbox Mobile Form
       
        ▼
Data Export (Excel)
        
        ▼
Excel Data Cleaning & Structuring
        
        ▼
Power BI Data Model
        
        ▼
Interactive Dashboard & Insights

# Repository Structure

<img width="242" height="287" alt="image" src="https://github.com/user-attachments/assets/cd5d65e3-e4f1-423f-9dbf-228e85221558" />

# KoboToolbox Data Collection System

A structured KoboToolbox XLSForm was developed to capture household financial activities.

The form collects the following financial records:

**1. Income**

Captures daily income inflows including:

Item sales

Salary

Allowances

Refunds

Stipends

Gifts or honorarium

Key fields include:

Income source

Amount received

Currency

Income description

Person submitting record

**2. Spending**

Captures daily expenditures with detailed categorization.

Major spending categories include:

Housing and Utilities

Food and Groceries

Transportation

Health and Medical Care

Education and Childcare

Clothing

Personal Care

Communication and Technology

Entertainment and Leisure

Miscellaneous

Each category has multiple detailed subcategories such as:

Communication & Technology examples:

Airtime / recharge cards

Internet subscriptions

Streaming services

Mobile phones and devices

Cloud storage

IT services

**3. Savings**

Records financial savings activities including:

Regular savings

Emergency savings

Cooperative contributions

Investments

Pension contributions

**4. Debt Collection**

Tracks borrowed funds including:

Source of debt

Purpose of borrowing

Debt category

Debt purposes include:

Household needs

Business investment

Property acquisition

Financial management

**5. Debt Repayment**

Tracks repayment transactions including:

Amount repaid

Currency

Debt type

Data Validation Features in KoboToolbox

The form includes several built-in validation mechanisms:

Device-based user identification

Mandatory fields for financial transactions

Numeric constraints for financial values

Conditional logic based on record type

Geolocation capture for submissions

Daily submission validation

Form replacement mechanism for corrections

# Data Structure

Data collected from KoboToolbox is exported to Excel where additional structured fields are created.

**Key variables include:**

<img width="378" height="176" alt="image" src="https://github.com/user-attachments/assets/1bb1ab96-6d8a-49b5-a988-72bf4a5a9ae2" />

# Power BI Dashboard

The Power BI dashboard transforms raw data into actionable insights.

Key dashboard components include:

**Financial Summary Cards**

Displays totals for:

Income

Expenditure

Savings

Debt collected

Debt repaid

Balance at hand

**Monthly Income vs Spending**

A line and bar chart that shows:

Total income by month

Total spending by month

Spending trends

**Spending Category Analysis**

Breakdown of expenses across categories such as:

Housing

Personal spending

Household needs

Entertainment

**Income Source Analysis**

Shows income contributions from different sources such as:

Item sales

Salary

Refunds

Allowances

Stipends

**Currency Analysis**

A donut chart displays income distribution by currency:

Naira

GBP

USD

**Smart Insights**

Power BI generates automated insights such as:

Highest spending month

Spending distribution

Spending growth patterns

**Example:**

November recorded the highest spending at ₦3,557,094, representing 37.09% of total spending.

**Key Features of the System**

Real-time mobile data collection

Device-based user authentication

Automated financial categorization

Multi-currency support

Geographic tagging of submissions

Interactive financial dashboards

Monthly and category-based spending analysis

**Tools and Technologies**

<img width="399" height="120" alt="image" src="https://github.com/user-attachments/assets/821aa88c-8e05-4c5c-a6fe-4c1111521938" />

**Use Cases**

This system can be adapted for:

Household financial tracking

Personal finance analytics

Small business expense monitoring

**Financial literacy projects**

Community savings group monitoring

Future Improvements

Planned improvements include:

Automatic currency conversion API

Power BI data refresh automation

Mobile notification reminders for daily entry

Budget tracking module

Predictive spending analytics

# Author

**Olalekan Onitiju**

Data & Performance Analyst | Monitoring & Evaluation Specialist
