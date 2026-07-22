# Retail Inventory & Performance Dashboard
A Power BI project using PostgreSQL, VS Code, Power Query, and DAX

![Dashboard Page 3](/images/retail_ss.png)


## Overview

This project analyzes retail product performance using a complete end‑to‑end data workflow.
I built a **PostgreSQL database**, created a **star schema**, performed data cleaning and transformations, and developed an **interactive Power BI dashboard** to visualize key retail metrics such as returns, inventory turnover, and markdown loss.

The final dashboard helps identify category‑level performance trends and operational inefficiencies.

## Tech Stack
- **PostgreSQL** — database storage, SQL queries, schema design

- **VS Code** — SQL editor for simulating data, performing calculations, and building the star schema

- **Power BI** — data visualization and dashboard development

- **Power Query** — data cleaning, shaping, and transformations

- **DAX** — custom measures for KPIs and calculations

## Data Modeling
I designed a star schema consisting of:

**Fact Table**: sales, returns, inventory turnover, markdown loss

**Dimension Tables**: product, category, season, size

This structure supports efficient slicing, filtering, and category‑level analysis in Power BI.

## Data Preparation
**PostgreSQL + VS Code**
- Imported offline datasets into PostgreSQL

- Cleaned and transformed raw data using SQL

- Simulated missing values and performed calculations

- Built the star schema (fact + dimension tables)

![sql](/images/stimulating_inventory_fash_sql.png)
*Example SQL script used to simulate inventory data and build the star schema.*

**Power Query**
- Additional cleaning inside Power BI

- Standardized category names

- Removed nulls and mismatches

- Ensured relationships matched the star schema

## Dashboard Features
The Power BI dashboard includes:

**KPIs**
- Total Returns

- Average Inventory Turnover

- Total Markdown Loss (USD)

**Visuals** 
- Returns by Category

- Inventory Turnover by Category

- Markdown Loss by Category

- Inventory Turnover vs. Markdown Loss (Scatter Plot)

**Slicers** 
- Category

- Season

- Size

*These slicers allow users to explore product performance interactively.*

## Insights
A few key findings from the dashboard:

- Certain categories drive significantly higher returns.

- Markdown loss is concentrated in specific product groups.

- Inventory turnover varies widely across categories, influencing markdown behavior.

- Categories with lower turnover tend to show higher markdown loss.
## Skills Demonstrated
- SQL data modeling

- Database design (PostgreSQL)

- Power Query transformations

- DAX measure creation

- Interactive dashboard design

- Retail analytics & KPI development

- End‑to‑end data pipeline creation