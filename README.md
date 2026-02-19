# E-Commerce Revenue & Customer Analysis  
## Online Retail Sales Data

This project analyzes sales and revenue performance of an online retailer using transactional data. The purpose is to extract business insights related to:

- Revenue trend and seasonality  
- Country-level revenue contribution  
- Product performance  
- Customer segmentation and revenue concentration  
- Strategic business recommendations

---

## Dataset Overview

The dataset contains ~534,000 retail transactions from an online retailer, including:

- Invoice No, Date  
- Product Description  
- Quantity  
- Unit Price  
- Customer ID  
- Country

Key data quality characteristics:
- ~25% missing Customer IDs  
- Negative quantities represent product returns  
- Some duplicate and invalid price rows

---

## Section 2 — Data Cleaning & Preparation

Cleaning steps included:

1. Removing duplicates  
2. Removing price ≤ 0 rows  
3. Keeping negative quantities (returns) for net revenue calculation  
4. Converting `InvoiceDate` to datetime  
5. Creating `Revenue` = Quantity × Price

This ensures clean, business-ready data for analysis.

---

## Section 3 — Revenue Overview & Business Metrics

Key performance metrics:

- **Total Net Revenue:** ~9.75M  
- **Unique Transactions:** 23,796  
- **Units Sold:** ~5.57M  
- **Return Impact:** ~-894K (~9.17% of net revenue)  
- **Average Revenue per Transaction:** ~409.65  
- **Average Units per Transaction:** ~234.17

These metrics establish a financial baseline for the business.

---

## Section 4 — Monthly Revenue Trend Analysis

The monthly trend shows moderate stability early in the year, followed by strong **Q4 growth**, peaking in November. The December decline is due to incomplete data (dataset ends on Dec 9). Seasonal effects and holiday demand are evident.

---

## Section 5 — Country-Level Revenue Analysis

The UK contributes **84% of total revenue**, indicating heavy geographic dependency. Secondary markets such as Netherlands, EIRE, Germany, and France show moderate traction, but revenue drops sharply beyond the top few countries. This suggests strategic opportunity in international expansion.

---

## Section 6 — Product-Level Revenue Drivers

After excluding operational charges (e.g., `POSTAGE`, `DOTCOM POSTAGE`):

- **Top revenue product:** *REGENCY CAKESTAND 3 TIER*  
- Core products like *JUMBO BAG RED RETROSPOT* contribute strongly in both volume and revenue  
- Some high-volume products (e.g., *PAPER CRAFT, LITTLE BIRDIE*) do not generate top revenue

This section distinguishes revenue drivers from volume drivers for informed product strategy.

---

## Section 7 — Revenue Distribution & Customer Segmentation

Pareto analysis shows strong concentration: a small number of customers contribute most of the revenue, consistent with typical retail dynamics.

Customer segmentation reveals:

- Some customers transact frequently with high monetary value  
- A long tail of low-frequency, low-revenue customers

This supports targeted retention and loyalty strategies.

---

## Section 8 — Strategic Insights

1. Revenue is heavily concentrated among a small customer subset.  
2. High-value customers show both high frequency and high revenue.  
3. Long-tail customers represent lower but collectively significant revenue.  
4. Core products exhibit strong product-market fit.  
5. Geographic concentration poses both risk and opportunity.

---

## Section 9 — Strategic Recommendations

1. Implement loyalty programs for high-value customers.  
2. Promote top merchandise via bundling and cross-selling.  
3. Expand focus in secondary international markets.  
4. Design campaigns to convert mid-tier/long-tail customers into repeat buyers.

---

## Skills Demonstrated

- Data cleaning & feature engineering  
- Exploratory data analysis (EDA)  
- Aggregation & grouping  
- Time series analysis  
- Segmentation & Pareto distribution  
- Business storytelling

---

