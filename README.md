# Superstore Discount & Profitability Analysis

An Excel-based business analytics project examining the relationship between discounting, sales, demand, and profitability across product categories and regions using the Superstore dataset.

---

## Project Overview

Discounts are commonly used to stimulate sales and increase customer demand. However, higher discounts can also reduce margins and negatively affect profitability.

This project uses the Superstore dataset to investigate:

- How discount levels relate to profitability
- Whether higher discounts are associated with higher quantities sold
- How performance varies across product categories
- How profitability differs across geographic regions
- Which category-region combinations contribute positively or negatively to overall profit

The analysis was performed using Microsoft Excel, including PivotTables, calculated metrics, correlation analysis, and dashboard visualizations.

---

## Business Questions

1. What is the relationship between discount levels and profit?
2. Do higher discounts correspond to higher quantities sold?
3. Which product categories generate the most profit?
4. How does profitability vary across regions?
5. Which product category and region combinations generate losses?
6. What patterns can be observed between discounting and business performance?

---

## Tools & Techniques

Tool:
- Microsoft Excel

Techniques:
- Data cleaning and preparation
- PivotTables
- KPI analysis
- Correlation analysis
- Category-level analysis
- Regional analysis
- Discount-bucket analysis
- Profitability analysis
- Heatmap analysis
- Dashboard visualization

---

## Key Metrics

| Metric | Value |
|---|---:|
| Total Orders | 9,980 |
| Total Sales | $2.29M |
| Total Profit | $286.01K |
| Average Discount | 15.64% |
| Total Quantity Sold | 37,817 |
| Average Profit Margin | 12.01% |

---

## Key Findings

### Discount & Profitability

The correlation between discount and profit is approximately -0.219, indicating a negative relationship in the dataset.

Average profit also declines across several higher discount ranges, with the 41–50% discount range showing particularly low average profitability.

Correlation indicates association, not causation. This analysis does not establish that discounts alone cause changes in profit.

### Discount & Demand

The correlation between discount and quantity sold is approximately 0.009, indicating a very weak linear relationship.

Average quantity sold remains relatively similar across discount ranges, suggesting that larger discounts do not correspond to a substantial increase in quantity purchased within this dataset.

### Product Categories

Technology generates the highest total profit among the three major categories.

| Category | Total Profit |
|---|---:|
| Technology | $145.39K |
| Office Supplies | $122.25K |
| Furniture | $18.38K |

### Regional Performance

The West region records the highest total profit.

| Region | Total Profit |
|---|---:|
| West | $108.40K |
| East | $91.35K |
| South | $46.55K |
| Central | $39.71K |

The Central region also has the highest average discount among the four regions analyzed.

---

## Dashboard

The Excel workbook contains analysis covering:

- Overall business KPIs
- Discount vs. Profit
- Discount vs. Quantity
- Category performance
- Regional performance
- Category × Region profitability
- Scatterplot analysis

---

## Project Structure

superstore-discount-profit-analysis/
│
├── README.md
│
└── discount analysis.xlsx

---

## Dataset

The project uses the Superstore dataset for educational and analytical purposes.

The dataset contains information related to orders, customers, products, sales, discounts, quantities, profits, categories, and regions.

---

## Analytical Note

The findings presented in this project describe relationships observed in the dataset. Correlation analysis should not be interpreted as evidence of causal relationships.

This project is intended for educational and portfolio purposes.

---

## Author
Lamya Khan
