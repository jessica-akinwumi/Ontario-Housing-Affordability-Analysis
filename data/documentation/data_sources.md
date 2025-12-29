# Data Sources Documentation

This project uses publicly available Canadian datasets to analyze housing affordability trends across Ontario. All data sources are reputable government or public institutions.

---

## 1. Housing Prices Data

**Source:** Canada Mortgage and Housing Corporation (CMHC)  
**Dataset:** Housing Market Information – Residential Prices by CMA  
**Geographic Level:** Census Metropolitan Area (CMA)  
**Time Coverage:** 2010–2024  
**Frequency:** Annual  

**Key Variables:**
- CMA Name
- Year
- Median Residential Sale Price
- Average Residential Sale Price (where available)

**Purpose in Analysis:**  
Used to track housing price trends across Ontario regions and calculate affordability metrics.

---

## 2. Household Income Data

**Source:** Statistics Canada  
**Table:** 11-10-0190-01 – Median total income by economic family type  
**Geographic Level:** Census Metropolitan Area (CMA)  
**Time Coverage:** 2010–2024  
**Frequency:** Annual  

**Key Variables:**
- CMA Name
- Year
- Median Total Household Income (Before Tax)

**Purpose in Analysis:**  
Used to compare income growth against housing prices and calculate price-to-income and affordability ratios.

---

## 3. Interest Rate Data

**Source:** Bank of Canada  
**Dataset:** Policy Interest Rate / 5-Year Fixed Mortgage Rate  
**Geographic Level:** National  
**Time Coverage:** 2010–2024  
**Frequency:** Annual Average  

**Key Variables:**
- Year
- Interest Rate (%)

**Purpose in Analysis:**  
Used to estimate mortgage payments and assess the impact of interest rate changes on housing affordability.

---

## Notes & Limitations
- CMA-level data availability varies slightly by year.
- Housing prices represent market-level trends and may not capture neighbourhood-level variation.
- Mortgage estimates are simplified and do not account for down payment size, taxes, or insurance.

