# Data Analytics Portfolio | BoyCode Africa

[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

**A practical showcase of data analytics projects, technical exercises, and applied business intelligence developed through the BoyCode Africa Data Analytics Programme.**

Welcome to my Data Analytics Portfolio. This repository documents my learning journey, technical development, and practical application of data analytics concepts through projects involving Microsoft Excel, Power BI, and SQL.

My focus is on transforming raw data into structured, meaningful, and actionable information. Through practical business scenarios, I explore data cleaning, transformation, analysis, database management, data modelling, visualization, and business intelligence to solve problems and support evidence-based decision-making.

---

## Table of Contents

- [About the Portfolio](#about-the-portfolio)
- [Repository Structure](#repository-structure)
- [Projects](#projects)
  - [Microsoft Excel Projects](#1-microsoft-excel-projects)
  - [Power BI Projects](#2-power-bi-projects)
  - [SQL Projects](#3-sql-projects)
- [Technical Skills](#technical-skills-demonstrated)
- [Analytical Approach](#analytical-approach)
- [Learning Outcomes](#key-learning-outcomes)
- [Tools and Technologies](#tools-and-technologies)
- [About Me](#about-me)
- [Connect With Me](#connect-with-me)

---

## About the Portfolio

This repository contains practical assignments, analytical exercises, and capstone projects developed as part of my participation in the **BoyCode Africa Data Analytics Programme**.

The portfolio is organized around three major areas:

| Area | Primary Focus |
|---|---|
| Microsoft Excel | Data cleaning, transformation, analysis, calculations, Pivot Tables, and dashboards. |
| Power BI | Data transformation, relational data modelling, DAX calculations, and business intelligence visualization. |
| SQL | Relational database design, data integration, querying, joins, and analytical data preparation. |

Each project demonstrates different stages of the analytical process, from preparing raw datasets to extracting insights and communicating findings.

## Repository Structure

```text
boycode-data-analytics-portfolio/
│
├── EXCEL/
│   ├── EXCEL CAPSTONE PROJECT/
│   ├── EXERCISE/
│   └── The Tutor (Hotel Analysis).xlsx
│
├── POWER BI/
│   ├── EXERCISE/
│   └── [Capstone Project Files]
│
├── SQL/
│   └── [SQL Project Files]
│
└── README.md
```

---

## Projects

### 1. Microsoft Excel Projects

**Focus:** Data preparation, exploratory analysis, financial and operational performance analysis, and dashboard development.

#### Project 1: King's House – Sales and Profitability Performance Analysis

**Project Type:** E-commerce Business Analytics Capstone

**Business Context**

King's House is a simulated Nigerian e-commerce business. The objective was to investigate its sales and profitability performance, identify the factors influencing commercial outcomes, and provide management with actionable recommendations.

The analysis began with a raw dataset containing 1,812 transaction records, including intentional duplicates, missing values, and inconsistencies.

**Key Activities**

- Inspected and profiled the raw transaction dataset.
- Identified and removed duplicate records.
- Handled missing values and inconsistencies in critical financial fields.
- Standardized text entries across product categories, regions, and customer segments.
- Created structured Excel tables and documented data quality issues.
- Calculated revenue, cost, gross profit, and gross profit margin.
- Analysed monthly sales and profitability trends.
- Evaluated product and category performance.
- Examined regional and customer segment contributions.
- Investigated the relationship between discounting and profitability.
- Identified the top 10 high-opportunity products and bottom 10 underperforming products.

**Key Business Insights**

The analysis highlighted differences between revenue generation and actual profitability. Some products generated substantial sales but delivered weaker gross margins due to their associated costs.

It also demonstrated how aggressive discounting could increase sales volume while reducing profitability.

**Management Recommendations**

- Prioritize high-revenue, high-margin products.
- Investigate or reconsider persistently underperforming products.
- Introduce margin-based discount controls.
- Allocate commercial resources according to regional and customer segment performance.

**Tools:** Microsoft Excel, Excel Tables, Pivot Tables, Pivot Charts, XLOOKUP, SUMIFS, COUNTIFS, AVERAGEIFS, and conditional formatting.

#### Project 2: The Tutor – Hotel Operations and Revenue Analysis

**Project Type:** Hotel Analytics Capstone

**Business Context**

This project examined hotel reservations, guest behaviour, room utilization, revenue generation, and operational performance.

The objective was to identify opportunities to improve occupancy, optimize revenue streams, and strengthen hotel management decisions.

**Key Activities**

- Cleaned and standardized reservation and transactional records.
- Validated check-in and check-out dates.
- Calculated guest length of stay.
- Investigated missing values and inconsistencies.
- Analysed room revenue and ancillary revenue.
- Evaluated room categories and booking channels.
- Examined cancellation patterns and booking status.
- Investigated seasonal booking trends and occupancy patterns.
- Analysed guest segments and length-of-stay behaviour.

**Key Business Insights**

The analysis explored the revenue contributions of different room categories, the impact of booking cancellations, and the relationship between booking channels and operational efficiency.

It also identified opportunities to improve ancillary revenue through additional guest services and longer-stay packages.

**Management Recommendations**

- Adopt seasonal and demand-based room pricing.
- Strengthen cancellation and deposit policies.
- Encourage direct bookings.
- Introduce bundled accommodation and additional service packages.
- Develop corporate and extended-stay offers.

**Tools:** Microsoft Excel, XLOOKUP, INDEX/MATCH, IFS, SUMIFS, COUNTIFS, Pivot Tables, and data visualization.

#### Project 3: Excel Practical Exercises

This section contains practical exercises designed to strengthen foundational and intermediate Excel analytical skills.

**Areas Covered**

- Logical functions: IF, AND, OR, and IFS.
- Lookup functions: XLOOKUP and INDEX/MATCH.
- Text functions: TRIM, UPPER, and PROPER.
- Date functions and calculations.
- Conditional formatting and data validation.
- Duplicate identification and data cleaning.
- SUMIFS, COUNTIFS, and AVERAGEIFS.
- Pivot Tables and Pivot Charts.
- KPI calculations and dashboard development.
- Interactive reporting using slicers and timelines.

---

### 2. Power BI Projects

**Focus:** Data transformation, dimensional modelling, relational data architecture, DAX, and interactive business intelligence.

#### Project 1: King's House – Star Schema Data Modelling

**Project Type:** Power BI Data Modelling Assignment

**Project Objective**

This project focused on transforming a cleaned e-commerce dataset into a structured relational data model using the Star Schema architecture.

The objective was to reduce redundancy, establish appropriate relationships, and prepare the data for efficient reporting and analysis.

**Data Modelling Process**

The cleaned Excel dataset was imported into Power BI and transformed using Power Query Editor.

Four principal tables were developed:

| Table | Description |
|---|---|
| ORDERS | Central fact table containing transactional records, foreign keys, and numerical measures. |
| DCUSTOMER | Customer dimension containing Customer_ID and Customer_Segment. |
| DPRODUCT | Product dimension containing Category and Product. |
| CALENDAR | Dedicated date dimension containing Year, Quarter, Month Name, and Month Number. |

**Key Technical Activities**

- Imported and referenced the cleaned source dataset.
- Created dimension tables using Power Query references.
- Removed duplicate records from dimension tables.
- Developed a continuous calendar table using M-code and List.Dates.
- Created date hierarchies for temporal analysis.
- Separated descriptive attributes from transactional measures.
- Retained the necessary foreign keys in the central fact table.
- Established active one-to-many relationships.
- Optimized query loading by disabling load for the intermediate CLEAN query.
- Arranged the tables into a Star Schema architecture.

**Data Relationships**

- DCUSTOMER (1) → ORDERS (*)
- DPRODUCT (1) → ORDERS (*)
- CALENDAR (1) → ORDERS (*)

**Key Learning Outcomes**

This exercise strengthened my understanding of dimensional modelling, fact and dimension tables, primary and foreign keys, relationship cardinality, date dimensions, Power Query transformations, and data model optimization.

**Tools:** Microsoft Power BI Desktop, Power Query Editor, and Power Query M.

#### Project 2: Power BI Practical Exercises

This directory contains additional exercises focused on developing practical Power BI and data modelling capabilities.

**Areas Covered**

- Power Query data transformation.
- Query referencing and data preparation.
- Duplicate removal and data consolidation.
- M-code and custom date table generation.
- Fact and dimension table development.
- Star Schema architecture.
- Relationship cardinality and data integrity.
- Model View organization.
- Query loading and model optimization.

---

### 3. SQL Projects

**Focus:** Relational database management, SQL querying, data integration, and analytical data preparation.

#### Project 1: Toman Bike Share – End-to-End SQL and Power BI Analysis

**Project Type:** Business Intelligence and Data Analytics Capstone

**Business Context**

Toman Bike Share operates a bicycle rental service serving both casual and registered riders.

The objective was to evaluate business performance, understand customer demand patterns, investigate revenue and profitability, and provide recommendations to improve operational efficiency.

The analysis covered two operational years of historical bike-sharing data.

**Part A: SQL Database Design and Development**

A relational database named `toman_bike_share` was developed in MySQL.

The database included:

- `bike_share_yr_0`: Historical transactional data for the first operational year.
- `bike_share_yr_1`: Historical transactional data for the second operational year.
- `cost_table`: Pricing benchmarks, operational years, unit prices, and Cost of Goods Sold (COGS).

**SQL Techniques Applied**

- Database and table creation.
- Common Table Expressions (CTEs).
- UNION ALL for combining historical datasets.
- INNER JOIN and LEFT JOIN operations.
- Data integration and relational querying.
- Aggregation and analytical calculations.

A CTE was used to consolidate the two historical transaction tables into a unified dataset. The resulting records were integrated with the cost table using the operational year as the joining key.

**Part B: Power BI Integration and Analysis**

The consolidated SQL data was connected to Power BI Desktop for further modelling, calculations, and visualization.

A dedicated measures table was created to organize the DAX calculations.

Key measures included:

- Total Riders.
- Total Revenue.
- Total Profit.
- Profit Margin Percentage.

**Selected DAX Measures**

Total Riders:

```dax
Total Riders = SUM(TomanBikeData[riders])
```

Total Revenue:

```dax
Total Revenue =
SUMX(
    TomanBikeData,
    TomanBikeData[riders] * RELATED(cost_table[price])
)
```

Total Profit:

```dax
Total Profit =
SUMX(
    TomanBikeData,
    TomanBikeData[riders] *
    (TomanBikeData[price] - TomanBikeData[COGS])
)
```

Profit Margin:

```dax
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue], 0)
```

**Key Analytical Findings**

| Performance Indicator | Result |
|---|---:|
| Total Riders | 3,292,679 |
| Total Revenue | $15,187,365.21 |
| Total Profit | $10,448,578.93 |
| Profit Margin | 68.80% |

Additional insights included:

- **Hourly demand:** Rental activity peaked between 5:00 PM and 6:00 PM, with another significant morning peak around 8:00 AM.
- **Rider composition:** Registered riders accounted for the majority of rental activity, while casual riders showed stronger weekend and holiday activity.
- **Seasonality:** Demand was stronger during warmer and clearer weather conditions.
- **Pricing performance:** The analysis indicated that increased rental prices between the two operational years were accompanied by higher revenue without a corresponding decline in total demand.

**Management Recommendations**

- Rebalance bicycle availability around morning and evening commuting periods.
- Develop targeted conversion campaigns to turn casual riders into registered subscribers.
- Explore demand-based and seasonal pricing strategies.
- Schedule preventive maintenance during low-demand periods.
- Use historical demand patterns to improve operational planning.

**Tools:** MySQL, SQL, Common Table Expressions, UNION ALL, JOINs, Microsoft Power BI, and DAX.

---

## Technical Skills Demonstrated

| Skill Area | Technical Competencies |
|---|---|
| Data Cleaning | Duplicate removal, missing value handling, standardization, and data validation. |
| Data Analysis | Exploratory analysis, trend analysis, segmentation, and performance evaluation. |
| Excel | Advanced formulas, lookup functions, Pivot Tables, Pivot Charts, and dashboards. |
| SQL | Database creation, CTEs, UNION ALL, JOINs, and data integration. |
| Power Query | Data transformation, query referencing, M-code, and data preparation. |
| Data Modelling | Fact tables, dimension tables, Star Schema, and relational relationships. |
| DAX | Measures, aggregations, calculated metrics, and dynamic calculations. |
| Business Intelligence | KPI development, reporting, visualization, and management recommendations. |
| Analytical Communication | Translating findings into meaningful business insights and recommendations. |

## Analytical Approach

Across the projects, I followed a structured analytical workflow:

1. **Business Understanding:** Identify the business problem, analytical objectives, and questions that need to be answered.
2. **Data Inspection:** Examine available datasets, understand their structure, and identify potential quality issues.
3. **Data Cleaning and Preparation:** Resolve inconsistencies, handle missing values, remove duplicates, and validate records.
4. **Data Transformation and Modelling:** Organize data into appropriate structures for reliable analysis.
5. **Exploratory and Descriptive Analysis:** Investigate trends, relationships, patterns, and performance indicators.
6. **Visualization and Reporting:** Present findings through structured reports, dashboards, and analytical visuals.
7. **Insights and Recommendations:** Translate analytical results into practical recommendations that support decision-making.

## Key Learning Outcomes

- Understanding the importance of data quality and validation before analysis.
- Applying Excel functions to solve practical analytical problems.
- Designing relational databases and integrating data using SQL.
- Understanding dimensional modelling and Star Schema architecture.
- Building calculated measures using DAX.
- Connecting SQL databases to Power BI for reporting.
- Identifying business performance trends and operational gaps.
- Communicating analytical findings through actionable recommendations.

## Tools and Technologies

| Tool | Application |
|---|---|
| Microsoft Excel | Data cleaning, calculations, analysis, and dashboards. |
| Microsoft Power BI | Data transformation, modelling, DAX, and visualization. |
| MySQL | Relational database development and SQL querying. |
| Power Query | Data preparation and transformation. |
| DAX | Business calculations and analytical measures. |
| GitHub | Project version control, documentation, and portfolio management. |

## About Me

I am **Yakub Dhikrullahi Ishola**, an undergraduate Civil and Environmental Engineering student with a growing interest in Data Analytics, Data Science, and the application of technology to real-world problems.

My academic and technical background has strengthened my interest in analytical thinking, structured problem-solving, and evidence-based decision-making.

Through the BoyCode Africa Data Analytics Programme, I am developing practical competencies in Excel, Power BI, and SQL, with a particular interest in transforming data into insights that can improve business performance and support informed decisions.

I am committed to continuous learning, practical project development, and building the technical and analytical capabilities required to contribute meaningfully to the data industry.

## Connect With Me

- **GitHub:** [@yakub-analytics](https://github.com/yakub-analytics)
- **LinkedIn:** [Connect with me on LinkedIn](https://www.linkedin.com/in/yakub-dhikrullahi-18a645303?utm_source=share_via&utm_content=profile&utm_medium=member_android)
- **Portfolio Repository:** [BoyCode Data Analytics Portfolio](https://github.com/yakub-analytics/boycode-data-analytics-portfolio)

---

*This repository represents a learning process and project development journey. Projects, exercises, documentation, and technical competencies will continue to evolve as I gain more experience and work on additional analytical challenges.*

**Thank you for visiting my portfolio!**
