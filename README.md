# Casablanca Rental Affordability Analysis

## Project Overview

This project uses Microsoft Power BI to analyze rental prices and affordability in Casablanca, Morocco.

**Research Question:** How affordable is renting in Casablanca for students and salaried workers, and how does affordability vary across neighborhoods?

The project combines 2026 rental listings from Mubawab, official historical rental data, and public-sector salary information from the Moroccan Ministry of Economy and Finance to explore rental prices and affordability scenarios.

## Dashboard Pages

### 1. Rental Market — 2026

Analyzes advertised rental prices across Casablanca neighborhoods, including monthly rent, rent per square meter, property characteristics, and neighborhood comparisons.

### 2. Rental Affordability

Explores student budget scenarios, rent-sharing options, and worker rent-to-income comparisons using a public-sector salary benchmark.

### 3. Historical Rent Trends — 2001–2022

Examines historical rental trends across four housing types using official data for the Casablanca-Settat region.

## Dataset Overview

### 2026 Rental Listings

- **Cleaned listings:** 333
- **Neighborhoods:** 11
- **Source:** Mubawab Maroc
- **Key variables:** Neighborhood, monthly rent, property area, number of rooms, bathrooms, property features, and rent per square meter.

The listings represent advertised asking prices rather than confirmed rental transactions.

### Historical Rental Dataset

- **Observations:** 88
- **Period:** 2001–2022
- **Housing types:** Villa, Standing Apartment, Economic Apartment, and Economic Lot House
- **Geographic coverage:** Casablanca-Settat region

### Public-Sector Salary Benchmark

The worker-affordability analysis uses figures from the Moroccan Ministry of Economy and Finance's *Rapport sur les Ressources Humaines — Projet de Loi de Finances 2026*.

The monthly net salary benchmarks used in the analysis are:

- Lower-scale benchmark: 5,925 MAD
- Middle-scale benchmark: 7,238 MAD
- Higher-scale benchmark: 12,484 MAD
- Overall average monthly net public-sector salary: 10,600 MAD

These figures provide a public-sector reference for the affordability analysis and do not represent the average salary of every worker in Casablanca.

## Data Sources

### 1. Rental Listings

**Source:** Mubawab Maroc

https://www.mubawab.ma/en

Used to collect rental listings for the 2026 rental-market analysis.

### 2. Historical Rental Data

**Source:** Moroccan Open Data Portal

**Dataset:** *Montants moyens des loyers — Région Casablanca-Settat*

https://data.gov.ma/data/fr/dataset/montants-moyens-des-loyers-region-casablanca-settat-2001-2019

**Producer:** MATNUHPV, Morocco's ministry responsible for national territory planning, urban planning, housing, and city policy.

**License:** Open Data Commons Open Database License (ODbL).

This dataset is used to analyze historical rental values by year and housing type across the Casablanca-Settat region.

### 3. Public-Sector Salary Data

**Source:** Moroccan Ministry of Economy and Finance

**Report:** *Rapport sur les Ressources Humaines — Projet de Loi de Finances 2026*

https://www.finances.gov.ma/Publication/db/2026/Rapport-Ressources-Humaines_Fr.pdf

Used to obtain the public-sector salary benchmarks for the worker-affordability analysis.

## Methodology

The project involved preparing rental and historical datasets, cleaning data using Microsoft Excel and Power Query, calculating rental indicators, developing affordability scenarios, and creating interactive Power BI visualizations.

Rent per square meter was calculated by dividing monthly rent by property area in square meters.

Student affordability was explored using illustrative monthly budgets of 2,000 MAD, 3,000 MAD, and 4,500 MAD, including rent-sharing scenarios.

Worker affordability was examined by comparing rental costs with public-sector salary benchmarks and evaluating rent-to-income ratios.

Historical rental values were compared across four housing types over the period 2001–2022.

## Key Findings

The historical analysis indicated that the simple average of the four housing-type averages was approximately 6.04K MAD in 2001 and 8.11K MAD in 2022.

Approximate changes in average rental values between 2001 and 2022 by housing type were:

- Economic Lot House: +79.8%
- Economic Apartment: +64.4%
- Standing Apartment: +41.6%
- Villa: +21.9%

These comparisons describe the historical values analyzed in this project. The simple average across the four housing-type averages is not weighted by property counts or market share.

The affordability analysis explores how rental costs can represent different financial burdens depending on the available budget, salary benchmark, neighborhood, and whether rent is shared.

## Assumptions and Limitations

- Rental listings represent advertised asking prices, which may differ from actual rental transaction prices.
- Online listings may not represent the entire rental market in Casablanca.
- Student budgets are illustrative scenarios rather than official estimates of student spending.
- Rent-sharing scenarios depend on the assumed number of people sharing a property.
- The salary benchmark represents public-sector salaries and may not reflect the earnings of all workers in Casablanca.
- The historical dataset covers the Casablanca-Settat region and differs in scope and methodology from the 2026 rental listings.
- Historical data and current rental listings should not be treated as a single continuous time series.
- Affordability results depend on the assumptions and thresholds used in the analysis.
- The analysis is descriptive and does not establish causal relationships.

## Tools and Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Cleaning and Preparation
- Data Analysis
- Data Visualization
- Interactive Dashboard Design

## Author

**Marwa Abdelkaoui**
