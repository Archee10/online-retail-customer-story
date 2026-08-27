# The Customers Who Disappear: Understanding Customer Loyalty and Churn in Online Retail

## Project Overview

Customer retention is one of the major challenges in online retail. A customer may purchase repeatedly for a period of time and then gradually disappear from the business.

This project investigates customer loyalty, inactivity, potential churn risk, and retention behaviour using the Online Retail transaction dataset.

Rather than looking only at overall sales, the project analyses customers at an individual level using purchase recency, purchase frequency, and historical revenue.

The analysis aims to answer four key questions:

1. How many customers have become inactive and how long have they been away?
2. How common are repeat purchases compared with one-time purchases?
3. Are high-value customers also becoming inactive?
4. What does customer cohort behaviour reveal about retention over time?

The final objective is to transform these findings into actionable customer-retention strategies.

---

## Story Hook

### The Customers Who Disappear

At first glance, customer loyalty appears relatively healthy: **72.39% of customers made repeat purchases**.

However, looking deeper reveals a more concerning pattern.

**40.83% of customers had not made a purchase for more than 180 days.**

Among the **1,176 high-value customers**, **208 (17.69%) were identified as at risk** based on prolonged inactivity.

These customers are associated with **£1,546,445.44 in historical revenue**.

The central story of this project is therefore not simply about customer churn. It is about identifying valuable customers before prolonged inactivity becomes permanent.

---

## Dataset

**Dataset:** Online Retail Dataset

The dataset contains transaction-level records from an online retail business.

### Main attributes

- `InvoiceNo` – Transaction/invoice identifier
- `StockCode` – Product identifier
- `Description` – Product description
- `Quantity` – Quantity purchased
- `InvoiceDate` – Date and time of transaction
- `UnitPrice` – Price per unit
- `CustomerID` – Customer identifier
- `Country` – Customer country
- `Revenue` – Transaction revenue derived during preprocessing

The cleaned dataset is stored in:

```text
data/processed/cleaned_retail.csv
