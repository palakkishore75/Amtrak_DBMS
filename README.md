
# Amtrak DBMS & Analytics Project  
**Brand:** TerpTrak Solutions  

This repository contains an end-to-end **Database Management Systems (DBMS) and analytics project** built on Amtrak operational data. The project focuses on structured data modeling, SQL-based analysis, and Tableau visualization to support operational efficiency, customer engagement, and performance monitoring.

---

## Repository Structure

```text
├── LICENSE
├── Project_DDL.sql
├── Project_DDL.sql.pdf
├── Project_DML.sql
├── Project_DML.sql.pdf
├── Project_Design.docx.pdf
├── Project_Report.docx.pdf
├── Project_Slides.pptx.pdf
├── Project_twb.twb
└── README.md
```

---

## Project Description

This project was developed as part of a **Database Management Systems** course and simulates a real-world consulting engagement with Amtrak. It integrates:

* Conceptual, logical, and physical database design
* Relational schema implementation in SQL Server
* Analytical SQL queries addressing business questions
* Interactive Tableau dashboards for stakeholder reporting

The underlying data is sourced from **Amtrak State Fact Sheets (2021–2023)** and related public route information, consolidated and cleaned prior to database ingestion.

---

## Database Design

### Conceptual & Logical Design

* ER modeling covering **State, Station, Route, Ridership, Budget, Procurement, OTP, Employee, and Rewards**
* Clearly defined relationships, constraints, and business rules
* Normalized relational schema to reduce redundancy and enforce data integrity

Detailed documentation is available in:

* **`Project_Design.docx.pdf`**

### Physical Design

* Implemented using **SQL Server**
* Primary and foreign key constraints
* Cascading updates and controlled deletes based on business rules

Relevant files:

* **`Project_DDL.sql`** – Table creation and constraints
* **`Project_DDL.sql.pdf`** – PDF reference version

---

## Data Processing & Analysis

* Initial data provided in Excel format and restructured to match the relational schema
* Data imported using SQL Server’s *Import Flat File* utility
* Analytical queries written to answer key operational and performance questions

Relevant files:

* **`Project_DML.sql`** – Business and analytical SQL queries
* **`Project_DML.sql.pdf`** – PDF reference version

---

## Business Questions Addressed

The SQL and Tableau analysis focuses on the following themes:

1. **Ridership Growth vs. Budget & Procurement**
   Compare top and bottom stations by ridership growth and assess alignment with spending.

2. **Ridership vs. Rewards Participation**
   Identify states where ridership outpaces rewards enrollment and analyze year-over-year gaps.

3. **On-Time Performance (OTP) Analysis**
   Examine the lowest-performing routes and evaluate trends by route type and frequency.

4. **Stations with Declining Ridership**
   Detect stations with post-2022 ridership drops and analyze historical patterns.

---

## Insights & Findings

### Ridership, Budget, and Procurement

* Higher spending does **not consistently translate** into higher ridership growth.
* Some high-budget stations show limited growth, indicating potential inefficiencies.
* Stations with strong growth but moderate spending highlight opportunities for targeted investment.

### Rewards Program Adoption

* Large-population states exhibit the **widest gap** between ridership and rewards participation.
* Rewards enrollment growth lags behind ridership growth, suggesting underutilized loyalty potential.

### On-Time Performance (OTP)

* Long-distance routes tend to have lower OTP due to cumulative delays across multiple stops.
* Daily commuter routes show gradual improvement over time.
* Several routes experienced OTP decline from FY21 to FY23, indicating systemic scheduling or operational challenges.

### Declining Ridership Stations

* A subset of stations saw ridership decline from FY22 to FY23 despite earlier post-COVID recovery.
* Patterns suggest normalization of travel behavior and localized operational constraints rather than network-wide issues.

---

## Tableau Dashboard

An interactive Tableau dashboard was built to visualize:

* Ridership trends by station and state
* Rewards participation gaps
* Route-level OTP performance
* Stations with declining ridership

File:

* **`Project_twb.twb`**

---

## Documentation & Presentation

* **`Project_Report.docx.pdf`** – Full analytical report with methodology, queries, visualizations, and conclusions
* **`Project_Slides.pptx.pdf`** – Executive-style presentation summarizing findings for stakeholders

---

## Tools & Technologies

* **SQL Server** – Database implementation and analytics
* **Tableau** – Interactive visualization and dashboards
* **Excel** – Initial data consolidation and cleaning
* **Microsoft Word & PowerPoint** – Documentation and reporting

---

## How to Use

1. Run **`Project_DDL.sql`** to create the database schema.
2. Load data as described in the report documentation.
3. Execute **`Project_DML.sql`** to reproduce analytical results.
4. Open **`Project_twb.twb`** in Tableau to explore dashboards.

---

## References

* Amtrak State Fact Sheets (2021–2023):
  [https://www.amtrak.com/about-amtrak/amtrak-facts/state-fact-sheets.html](https://www.amtrak.com/about-amtrak/amtrak-facts/state-fact-sheets.html)

---

