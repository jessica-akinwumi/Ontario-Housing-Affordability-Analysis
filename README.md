# Ontario Housing Affordability Analysis & Forecasting

##  Project Overview
Housing affordability has become one of the most pressing socio-economic challenges facing residents across Ontario. Rising home prices, increasing interest rates, and slower income growth have made it difficult for many households to access stable and affordable housing.

This project is an **end-to-end data analysis** examining housing affordability trends across Ontario. Using publicly available datasets, the analysis explores how housing costs compare to household incomes over time and across regions, identifies areas experiencing the fastest affordability decline, and highlights implications for residents and policymakers.

The project demonstrates the ability to transform raw public data into clear, actionable insights using **Python, SQL, and data visualization tools**.

---
## Objectives
The main goals of this project are to:
* **Analyze** housing affordability trends across Ontario regions.
* **Compare** housing prices to household income levels.
* **Identify** the least and most affordable regions over time.
* **Track** changes in affordability and cost burdens.
* **Present** insights in a clear, policy-relevant, and data-driven way.

##  Project Scope 

###  Geographic Boundaries
* **Primary Focus:** Ontario, Canada.
* **Regional Breakdown:** Analysis will focus on major **Census Metropolitan Areas (CMAs)**:
    * Greater Toronto Area (GTA)
    * Ottawa-Gatineau (Ontario side)
    * Hamilton
    * Kitchener-Cambridge-Waterloo
    * London & Windsor

###  Temporal Scope
* **Timeline:** 2010 – 2024.
* **Frequency:** Annual data points to highlight long-term structural shifts versus short-term market shocks (e.g., COVID-19 and 2023 rate hikes).

### Data Definitions
* **Housing:** Median Sales Price (All residential types).
* **Income:** Median Total Household Income (Before-tax).
* **Affordability Metric:** The "Affordability Ratio" ($Price / Income$) and "Mortgage Debt Service Ratio" (estimated monthly payment as a % of monthly income).
---

## Tools & Technologies
This project uses a modern analytics stack aligned with public-sector data roles:

| Tool | Purpose |
| :--- | :--- |
| **Python** (Pandas, Numpy) | Data cleaning, transformation, and feature engineering |
| **SQL** | Data storage, aggregation, trend analysis, and ranking |
| **Power BI / Excel** | Interactive dashboards and visual storytelling |
| **GitHub** | Version control and project documentation |

---

## Project Structure
```text
Ontario-Housing-Affordability-Analysis
│
├── data/        # Raw and cleaned datasets (CMHC, Statistics Canada)
├── notebooks/   # Python notebooks for data cleaning and analysis
├── sql/         # SQL schemas and analytical queries
├── dashboard/   # Power BI or Excel dashboard files
├── visuals/     # Charts, screenshots, and exported visuals
├── README.md    # Project documentation
└── LICENSE# Ontario-Housing-Affordability-Analysis
An end-to-end data analysis project examining housing affordability trends across Ontario using Python, SQL, and Power BI.

---

## Data Sources
The analysis is based on trusted Canadian public datasets, including:
* **Canada Mortgage and Housing Corporation (CMHC)**
* **Statistics Canada**
* **Bank of Canada** (Interest rate data)

**Key Data Points:** Median home prices, Household income levels, Mortgage rates, and Regional housing trends.

---

## Methodology

### 1️Data Cleaning & Preparation (Python)
* Standardized region and municipality names.
* Converted price and income fields to numeric formats.
* Handled missing and inconsistent values.
* **Engineered key metrics:** Affordability Ratio, Price-to-Income Index, and Estimated Monthly Mortgage Cost.

###  Data Analysis (SQL)
* Loaded cleaned data into a SQL database.
* Aggregated affordability metrics by region and year.
* Ranked regions by affordability and identified fastest-rising housing markets.
* Analyzed income vs. housing cost gaps over time.

###  Visualization & Dashboarding
Built an interactive dashboard to display:
* Regional affordability trends and income vs. housing cost comparisons.
* Key KPIs: Median price, income, and affordability index.
* Enabled filtering by region, year, and housing type.

---

##  Key Insights (Summary)
* **Declining Affordability:** Housing affordability has declined across most Ontario regions over the past decade.
* **Price vs. Income:** Price growth has significantly outpaced income growth in major urban centers.
* **Regional Pressure:** Some regions are experiencing rapid affordability deterioration despite moderate income gains.
* **Interest Rates:** Rising interest rates significantly increase monthly mortgage burdens for new buyers.

---

##  Policy Relevance
This project aligns with Ontario public-sector priorities:
* Housing affordability and access.
* Economic inequality and evidence-based decision making.
* The findings support housing policy discussions and targeted interventions.

---

##  Future Enhancements
* **Forecasting:** Using time-series models to predict future affordability trends.
* **Rentals:** Incorporating rental market data for a full housing picture.
* **Demographics:** Adding segmentation by age or household type.

---

##  About the Author
**Jessica Akinwumi** *Aspiring Data Analyst with a focus on public-sector analytics and housing policy.*

