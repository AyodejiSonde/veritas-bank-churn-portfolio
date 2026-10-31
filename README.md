# Veritas Bank Customer Churn Analysis

## Overview

This project uses SQL Server and Power BI to explore customer churn across a banking dataset. It examines customer demographics, account characteristics and activity patterns to identify areas for further investigation and inform retention recommendations.

## Business Questions

- What proportion of customers have churned?
- How does churn vary across customer segments?
- How do account activity, product holdings and balances relate to churn?
- Which segments warrant further investigation?

## Tools and Methods

- **SQL Server:** data transformation, customer segmentation and exploratory analysis.
- **Power BI:** interactive dashboards, KPI reporting and visual analysis.

The analysis involved creating customer categories, comparing churned and retained customers, and developing report pages with filters for country, product holdings, credit score category and tenure.

## Dashboard Previews

### Customer Demographics

Summarises the customer population by age, country, credit score, activity status and product holdings.

![Customer demographics dashboard](Images/Veritas%20Customer%20Demography.png)

### Churn Analysis

Explores churn patterns across account and customer characteristics.

![Customer churn dashboard](Images/Veritas%20Churn%20Analysis.png)

## Headline Results

| Metric | Value |
|---|---:|
| Total customers | 10,000 |
| Countries represented | 3 |
| Churned customers | 1,385 |
| Overall churn rate | 13.85% |

The dashboard rounds the overall churn rate to 14%.

These results describe the analysed dataset. They do not demonstrate that a retention intervention reduced churn.

## Recommendations

- Investigate the customer journeys and service experiences associated with inactive accounts.
- Compare churn rates alongside customer counts to distinguish segment size from relative risk.
- Explore product usage and customer engagement before selecting retention interventions.
- Test proposed actions and measure their effect on subsequent retention.

## Interpretation Notes

Segment-level findings require further validation before drawing firm conclusions. In particular, balance categories and credit card status labels are being reviewed.

The analysis identifies associations rather than causes of churn.

## Public Portfolio Contents

This repository contains a project summary and aggregate dashboard screenshots. Source data and the Power BI workbook are not included.

## Author

Ayodeji Sonde
