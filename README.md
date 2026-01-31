# Amtrak DBMS & Data Analytics Project

This project delivers an end-to-end database management and data analytics solution built on Amtrak operational data. It integrates relational database design, SQL development, and Tableau-based visualization to support analysis across key operational dimensions such as ridership, guest rewards, staffing, and on-time performance (OTP).

## Project Structure

### DBMS Component

Includes the complete SQL-based backend implementation:

- **`DDL.sql`** – Defines the database schema and table structures.
- **`DML.sql`** – Contains analytical and business-oriented SQL queries.
- **`Inserts.sql`** – Loads the database with cleaned and structured Amtrak data from multiple sources.

### Documentation and Deliverables

- **`Design.docx`** – Details the ER diagram, normalization process, and schema design justification.
- **`Report.docx`** – Comprehensive project documentation covering business context, data sources, and analytical approach.
- **`Slides.pptx`** – Executive-style presentation summarizing the project and visual outputs for stakeholders.

### Tableau Dashboard

- **`Tableau_Dashboard.twb`** – An interactive Tableau dashboard showcasing state-level KPIs, route performance metrics, and guest rewards trends.

## Project Overview

- **Business Objective**: Enhance Amtrak’s operational effectiveness and customer engagement through structured data management and analysis.
- **Data Sources**: Compiled from Amtrak state fact sheets (2021–2023), route guides, and publicly available route information.
- **Analytical Use Cases**:
  - Ranking cities and states by ridership and guest rewards growth
  - Assessing route-level on-time performance
  - Developing operational efficiency metrics using staffing and punctuality data
  - Supporting planning decisions related to infrastructure and loyalty programs

## Tools & Technologies

- **SQL Server** for relational database development
- **Tableau** for interactive data visualization
- **Excel** for preliminary data cleaning and preparation
- **Microsoft Word & PowerPoint** for documentation and presentations

## How to Run the Project

1. Execute `DDL.sql` to create the database schema.
2. Run `Inserts.sql` to load data into the database.
3. Use `DML.sql` to perform analysis and generate results.
4. Open the Tableau workbook to explore interactive dashboards.

## References

- [Amtrak State Fact Sheets](https://www.amtrak.com/about-amtrak/amtrak-facts/state-fact-sheets.html)
- [Amtrak Route Details](https://amtrakguide.com/routes/)
