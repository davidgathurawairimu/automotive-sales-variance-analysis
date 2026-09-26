# automotive-sales-variance-analysis
# Automotive Dealership Sales & Variance Analysis

**Data Analytics Portfolio Project | Excel + Python**

This project analyzes automotive dealership sales performance across Kenya, focusing on whether a stable topline revenue figure hides important branch-level and financing-level variation.

> **Data note:** This case study uses a simulated automotive sales dataset. The transaction-level dataset is not included yet.

## Business Question

Is dealership sales performance stable across the year, and are there branch-level or financing-type issues management should know about beyond the topline revenue figure?

## Dataset

- 15 dealerships across Kenya
- Approximately 2,500 transactions
- 4 quarters
- 5 financing types: Cash, Bank Loan, Dealer Financing, Lease, SACCO Loan
- Fields include sale ID, vehicle ID, customer ID, dealership ID, sale date, sale price, discount percentage, financing type, salesperson, and customer satisfaction

## Analytical Approach

### Excel
- PivotTables
- PivotCharts
- Slicers
- Quarterly revenue analysis
- Dealership and financing-type drill-down
- Variance analysis against the fleet average
- Data-quality/anomaly verification

### Python
- pandas
- NumPy
- Faker
- Synthetic dataset generation

## Key Findings

### 1. Stable topline revenue hides branch-level volatility

Quarterly revenue remained within approximately 4% of the average, ranging from **KES 2.29B to KES 2.38B**. However, two dealerships experienced **36–45% quarter-to-quarter swings** within the same stable overall total.

### 2. DLR-0007 shows a persistent performance issue

DLR-0007 finished the year **23% below the 15-branch average** and remained below average in every quarter.

### 3. Some extreme movements require data verification

DLR-0013's SACCO Loan revenue and DLR-0008's Dealer Financing revenue each fell by more than **85% in Q4**. These observations were flagged for data verification before being treated as genuine business trends.

## Analytical Flow

**Total Revenue → Quarterly Trend → Dealership Variance → Financing Mix → Anomaly Verification**

The main analytical lesson is that an apparently stable aggregate KPI does not necessarily mean stable operational performance.

## Skills Demonstrated

Data cleaning and preparation · Exploratory data analysis · Trend analysis · Variance analysis · Anomaly identification · Data-quality verification · Excel PivotTables · Excel PivotCharts · Python · pandas · NumPy · Synthetic data generation · Business reporting

## Tools

**Excel · Python · pandas · NumPy · Faker**

## Portfolio Context

This project forms part of my Data Analytics & Business Intelligence portfolio and complements my practical consulting experience in automotive fabrication.
