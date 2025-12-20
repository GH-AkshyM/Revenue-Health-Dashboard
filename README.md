# Revenue Health Dashboard
## ↪️Project background:
During my time as an Associate Consultant, I regularly worked on leadership revenue reports, which meant dealing with multiple Excel files, manual consolidation, and constant coordination with different teams.

Once I started learning Power BI, it completely changed my perspective. I saw how automation, data modeling, and governed reporting could transform that experience — not just by saving time, but by improving accuracy, visibility, and decision-making. That realization is what led me to build this dashboard.

*<h4>Disclaimer: The dataset used in this project is fully anonymized and synthetically transformed.
All identifiers, dates, and financial values were altered or randomized to ensure no real organizational data is exposed.
The project only simulates real business scenarios. Thanks in advance! I appreciate you stopping by here!!</h4>*

## 📚Table of Contents:

|**No.**  |**Section**|
|:-: | :------------ | 
|1.   |  [Business Problem](#business-problem)                              |
|2.   |  [Existing Environment](#existing-environment)                              |
|3.   |  [Technical Requirements](#technical-requirements)                              |
|4.   |  [Highlight Features](#highlight-features)                              |
|5.   |  [Future scope of the Dashboard](#future-scope-of-the-dashboard)                              |

## 📌Business Problem
Deltagrab is a fast-growing IT solutions company with operations across multiple countries and a workforce of over 400 employees. Its portfolio includes HR & payroll automation, SaaS products, and enterprise-grade cloud hosting services.

Like many rapidly growing organizations, revenue reporting evolved organically over time. Leadership relied on spreadsheets, manual consolidation, and team knowledge to track performance across countries, service lines, and subscription models. This approach worked effectively for several years because it provided flexibility and familiarity to the people managing it.

However, as the company continued to scale and key responsibilities began transitioning across roles, the need for a centralized, automated revenue analytics system became clear. Without a unified platform, the team faced:

- fragmented data across different files and sources

- delays in preparing consolidated monthly reports

- challenges in maintaining a single, trusted version of revenue numbers

- difficulty forecasting trends proactively

- slower decision-making due to limited real-time visibility

**To support continued growth and ensure business continuity, Deltagrab required a modern, automated revenue dashboard that could provide leadership with reliable, timely financial insights.**

[(Back to top)](#table-of-contents)

## 🏢Existing Environment
Deltagrab’s revenue reporting process was built gradually as the company expanded, relying primarily on spreadsheets, internal files, and cross-team coordination. Revenue data from different regions, business units, and subscription models was collected and consolidated manually.

A dedicated team within the Business Solutions division managed this process efficiently, but as reporting needs grew, the workload increased significantly. Much of the effort went into:

- gathering financial inputs from multiple sources

- standardizing formats

- resolving inconsistencies

- consolidating figures across countries and service lines

While the process worked, it required considerable effort and time each month. Moving toward an automated, governed Power BI solution offered the opportunity to reduce repetitive work, improve accuracy, and give leadership real-time visibility—without relying heavily on manual effort.

[(Back to top)](#table-of-contents)

## 🧰Technical Requirements
Deltagrab plans to move all revenue data from scattered Excel files into a centralized internal system that will serve as the single source of truth. Power BI will later connect to this system to create one unified executive report for the CEO and Head of Operations. Regional heads must only see their own region’s data, while the CEO should have access to everything, requiring proper Row-Level Security (RLS). As a pilot, the company will first validate all calculations and KPIs using the existing Excel data before transitioning to the internal platform.

Key Points:
- Centralized internal database for all revenue data
- Power BI connection to the new system
- One consolidated leadership report
- **RLS: regional heads limited, CEO full access**
- Pilot testing using current Excel sheets
  
[(Back to top)](#table-of-contents)

## ✨Highlight Features

### 1. Guage Chart:
Shows how much of the FY revenue target has been achieved vs. the goal set by the Leadership.
### 2. Projections Summary Cards:
Displays revenue expected This Year, Next 3 Months, and Current Month.
### 3. Monthly Revenue Trend (Recognized vs Projected):
A Dynamic bar chart showing month-wise revenue for the current financial year, including both recognized and projected, which changes relative to the current month!

![Overview](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Dashboard%20Overview%20-%20Gif.gif)

### 1. Dynamic Column Chart:
A Dynamic column chart showing the revenue split across each chapters. Selecting a country slicer quickly shows the respective revenue breakdown!

### 2. A pie chart:
A pie chart showing the contribution of Revenue from each commercial models.

### 3. A dedicated Forecast button:
By clicking this button the end user can easily switch to the forecasting view where a complete breakdown of Revenue between each projects with respect to Prev, Current, Next and Month after Next! The leadership can quickly identify the Drop or increase in revenue and prepare proactively! One key use-case is when the Leadership can have an AHM with the project managers and get their input as to why there is drop/increase in revenue. 

- From the input of PM's the leadership can identify the root cause of the drop/increase in revenue. It might be due to An employee being de-allocated or according the SOW there is no revenue being recognized for the particular month or if the project hasnt been renewed etc...

![Forecast View](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Forecast%20View.gif)

### 1. Matrix View:
A matrix table visual showing the top 10 biggest clients as per revenue.
### 2. Classic Bar chart:
For visualizing the revenue between all the financial years. Key Highlight: Dynamic titles (using parameters).
### 3. Decomposition Tree:
For ad hoc exploration into the projects of each regions. With an addition drill through button which quickly takes the user into a dedicated page to get a comprehensive view about all the project details.


![Detail View](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Detail%20View.gif)

[(Back to top)](#table-of-contents)

## ⭐ Important Feature 1:
*Side Note: Most portfolios take a simple one-page Excel or CSV dataset and create a few visuals and call it a day. But real end-to-end Power BI development goes far beyond building dashboards. It involves data modelling, security, access control, refresh strategy, governance, and understanding how the report will be shared and consumed.*

*Designing a reliable analytics solution isn’t just about visuals—it requires the skills, training and discipline to handle the full BI lifecycle. Only a properly trained Power BI professional can deliver a secure, scalable, and business-ready reporting system.*

### Row Level Security:

One report. One source of truth.
Multiple roles — each seeing only what they should.
No duplicated reports, no redundancy, no confusion.

![Row Level Security](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Row%20Level%20Security.gif)
## ⭐ Important Feature 2:

### Mobile Optimized view:
Most Operations and Leadership teams aren’t sitting at their desks all day — they’re meeting clients, handling escalations, and managing teams on the move. A mobile-optimized Power BI view gives them instant access to revenue insights right at their fingertips, without needing to open a laptop or navigate heavy dashboards.

<img src="https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/Screenshots/Mobile%20Optimized%20View.gif" width="300"/>

[(Back to top)](#table-of-contents)

## 🚀Future scope of the Dashboard

This pilot version is just the starting point, and there’s a lot of room for the dashboard to grow. In future releases:

- **Add Employee-Level Details:**
Bringing in employee data will help the company see who is allocated to which project, how workload is distributed, and how much revenue each person is contributing. This makes planning and resource allocation far more accurate.

- **Integrate CFO/Expense Data**
Connecting revenue with operational expenses will allow Leadership to finally see profitability, not just revenue. This means instantly spotting projects that are performing well vs. ones that are losing money.

- **Extend Role-Based Views**
Additional RLS-driven pages can be created for Finance, Delivery, HR, or Sales, giving each team a version of the dashboard that fits their needs.

[(Back to top)](#table-of-contents)

## You can explore the report [here](https://github.com/GH-AkshyM/Revenue-Health-Dashboard/blob/main/PBIX%20file/Revenue%20Health%20Dashboard.pbix). Download and open using Power BI Desktop. 


## Check out some of my other works: 
- 🧠 **[HR Attrition Analytics with Dataflow Gen2](https://github.com/GH-AkshyM/Hr-Attrition-Analytics-Dashboard)** – A Clean Minimalistic look into Attrition Analytics with Insights Hard-coded.  
- 📈 **[Sentiment Analysis Using BERT](https://github.com/GH-AkshyM/Sentiment-Analysis-using-BERT)** – Using SQL and Python pre-trained models for analysing customer reviews.
- 🔄 **[E-commerce Cohort Analytics Dashboard with Lakehouse on MS Fabric](https://github.com/GH-AkshyM/Cohort-Analytics-Dashboard-with-Lakehouse-on-MS-Fabric/tree/main)** – Cohort-based retention and revenue analytics using DirectQuery.  
