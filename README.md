# Revenue Health Dashboard
## ↪️Project background:
This project was inspired from my previous role as an Associate consultant. During that time me and my manager used to work together to present a **monthly** report to Leadership containing details about upcoming revenue. 
It used to take us weeks to prepare the excel files, cross checking with other department heads about missing data, formatting, cross checking etc. The whole process was entirely manual. Ofcourse at that time, I was not aware about Powerbi. When
I started learning this tool, I made up my mind that this would be my first project!

*<h4>Disclaimer: The dataset used in this project generated synthetically to mimic an IT solutions company. Which have several on going projects, Upcoming projects in the pipeline. Revenue recognition accross different months according to variying SOW's. Please give credit if you're going to reuse the dataset. Thanks in advance! I Appreciate you stopping by here!!</h4>*

## 📚Table of Contents:
[Dashboard Video Demo](#dashboard-video-demo)
|**No.**  |**Section**|
|:-: | :------------ | 
|1.   |  [Business Problem](#business-problem)                              |
|2.   |  [Existing Environment](#existing-environment)                              |
|3.   |  [Technical Requirements](#technical-requirements)                              |
|4.   |  [Highlight Features](#highlight-features)                              |
|5.   |  [Future scope of the Dashboard](#future-scope-of-the-dashboard)                              |
## 📌Business Problem
Deltagrab is a fast-growing IT solutions company with operations across multiple countries and a workforce exceeding 400 employees. Its service portfolio ranges from HR & payroll automation to SaaS-based products and enterprise-grade cloud hosting solutions.
Despite the company’s expanding footprint, all revenue tracking, consolidation, and reporting were handled manually by one of the founding members. This included:
- managing revenue streams across different service lines
- monitoring country-wise performance
- reconciling recurring SaaS subscriptions
- tracking cloud service usage and billing cycles
- preparing financial summaries for leadership

This approach worked only because a single, experienced founder maintained complete visibility and control over the financial data.
However, with this key individual recently exiting the company to pursue a new opportunity, Deltagrab now faces a critical challenge:
There is no centralized, automated, or scalable system to track revenue across countries, business units, and service categories.
This has resulted in:
- fragmented data scattered across emails, spreadsheets, and internal systems
- delays in monthly revenue reporting
- no single version of truth for leadership
- risk of miscalculations or missed revenue
- difficulty forecasting trends or assessing performance
- inability to take quick, data-driven decisions

To ensure business continuity and long-term stability, Deltagrab urgently needs a centralized, automated revenue analytics solution that provides complete visibility of the company’s financial performance — regardless of personnel changes.
## 🏢Existing Environment
Deltagrab’s revenue reporting environment is entirely manual and heavily dependent on scattered data practices. Revenue information from different countries, service lines, and products is collected through spreadsheets, emails, and ad-hoc exports from internal systems. There is no centralized platform to unify or validate these numbers.
A small team within the Business Solutions division is currently responsible for compiling monthly revenue reports. Due to the lack of automation, they spend significant time:
- extracting financial data from various systems
- merging spreadsheets from multiple departments
- manually cleaning inconsistencies
- resolving missing or duplicated entries
- reconciling numbers across countries and business units

Because the reporting is built on manual processes and individual knowledge, Deltagrab’s leadership lacks reliable, timely visibility into overall performance — making strategic decisions slower and riskier.
## 🧰Technical Requirements
Deltagrab plans to move all revenue data from scattered Excel files into a centralized internal system that will serve as the single source of truth. Power BI will later connect to this system to create one unified executive report for the CEO and Head of Operations. Regional heads must only see their own region’s data, while the CEO should have access to everything, requiring proper Row-Level Security (RLS). As a pilot, the company will first validate all calculations and KPIs using the existing Excel data before transitioning to the internal platform.

Key Points:
- Centralized internal database for all revenue data
- Power BI connection to the new system
- One consolidated leadership report
- RLS: regional heads limited, CEO full access
- Pilot testing using current Excel sheets
## ✨Highlight Features

### 1. Guage Chart
Shows how much of the FY revenue target has been achieved vs. goal.
### 2. Projections Summary Cards
Displays revenue expected This Year, Next 3 Months, and Current Month.
### 3. Monthly Revenue Trend (Recognized vs Projected)
A Dynamic bar chart showing month-wise revenue for the current financial year, including both recognized and projected, which changes relative to the current month!

![Guage Chart](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Dashboard%20Overview%20-%20Gif.gif)

## 🚀Future scope of the Dashboard


