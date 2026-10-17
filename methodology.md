# Methodology — Casablanca Rental Affordability Analysis

## 1. Research Objective

The objective of this project is to analyze rental prices in Casablanca, explore affordability for students and salaried workers, and examine historical rental trends across different housing types.

The analysis combines current rental listings, official historical rental data, and a public-sector salary benchmark to provide a broader understanding of rental affordability.

## 2. Data Sources

### 2.1 Rental Listings

**Source:** Mubawab Maroc

https://www.mubawab.ma/en

The listings were used to construct a 2026 snapshot of the Casablanca rental market. The cleaned dataset contains 333 listings across 11 neighborhoods.

### 2.2 Historical Rental Data

**Source:** Moroccan Open Data Portal

https://data.gov.ma/data/fr/dataset/montants-moyens-des-loyers-region-casablanca-settat-2001-2019

The dataset describes average rental amounts in the Casablanca-Settat region from 2001 to 2022. The analysis contains 88 observations covering four housing types: Villa, Standing Apartment, Economic Apartment, and Economic Lot House.

### 2.3 Public-Sector Salary Benchmark

**Source:** Moroccan Ministry of Economy and Finance

**Report:** *Rapport sur les Ressources Humaines — Projet de Loi de Finances 2026*

https://www.finances.gov.ma/Publication/db/2026/Rapport-Ressources-Humaines_Fr.pdf

The salary benchmarks used in the analysis are 5,925 MAD, 7,238 MAD, 12,484 MAD, and an overall average monthly net public-sector salary of 10,600 MAD.

## 3. Data Preparation

The rental listings were prepared using Microsoft Excel and Power Query. The resulting dataset includes neighborhood, monthly rent, property area, number of rooms, bathrooms, property features, source information, and rent per square meter.

The historical dataset was organized to support comparisons by year and housing type.

## 4. Rental Indicators

### 4.1 Rent per Square Meter

Rent per square meter was calculated by dividing monthly rent by property area.

**Rent per square meter = Monthly rent ÷ Property area**

The resulting value is expressed in MAD per square meter.

### 4.2 Rent-to-Income Ratio

The rent-to-income ratio measures the share of monthly income required to cover rent.

**Rent-to-income ratio (%) = Monthly rent ÷ Monthly income × 100**

### 4.3 Rent Sharing

For rent-sharing scenarios, the assumed rent per person is calculated by dividing total monthly rent by the number of people sharing the property.

**Rent per person = Monthly rent ÷ Number of people sharing**

## 5. Student Affordability Analysis

The analysis uses three illustrative monthly student budgets:

- Low budget: 2,000 MAD.
- Medium budget: 3,000 MAD.
- High budget: 4,500 MAD.

Two-person and three-person rent-sharing scenarios are considered where applicable.

These budget amounts are assumptions for analytical comparison and are not official estimates of average student spending.

## 6. Worker Affordability Analysis

The worker-affordability analysis uses an overall average monthly net public-sector salary benchmark of 10,600 MAD, alongside additional salary benchmarks of 5,925 MAD, 7,238 MAD, and 12,484 MAD.

Rental costs are compared with the selected salary benchmarks to explore the proportion of income required for rent. These figures represent public-sector salary benchmarks, not the average earnings of all workers in Casablanca.

## 7. Historical Rental Analysis

The historical analysis compares rental values from 2001 to 2022 across four housing types:

- Villa.
- Standing Apartment.
- Economic Apartment.
- Economic Lot House.

The simple average of the four housing-type averages was approximately 6.04K MAD in 2001 and 8.11K MAD in 2022.

Approximate changes between 2001 and 2022 were:

- Economic Lot House: +79.8%.
- Economic Apartment: +64.4%.
- Standing Apartment: +41.6%.
- Villa: +21.9%.

The average across the four housing-type averages is not weighted by property counts or market share.

## 8. Power BI Dashboard Development

The report is organized into three pages:

1. **Rental Market:** Analysis of 2026 asking-rent listings and neighborhood comparisons.
2. **Rental Affordability:** Student budget scenarios, rent sharing, and worker rent-to-income comparisons.
3. **Historical Trends:** Historical rental values by housing type from 2001 to 2022.

The dashboard uses KPI cards, charts, filters, and page navigation to present the analysis interactively.

## 9. Limitations

- Advertised asking rents may differ from actual rental transaction prices.
- Online listings may have uneven coverage across neighborhoods.
- Student budgets and rent-sharing scenarios are illustrative assumptions.
- The salary benchmark represents the public sector rather than the entire workforce.
- The historical dataset covers the Casablanca-Settat region, while the rental listings represent a 2026 snapshot of the Casablanca market.
- The datasets differ in scope and methodology and should not be treated as one continuous time series.
- The analysis is descriptive and does not establish causal relationships.