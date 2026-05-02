# Retail Performance Analysis — Product & Regional Insights

> **Skills demonstrated:** Business intelligence, profitability analysis, customer segmentation (RFM), Excel-based dashboarding, executive communication.

---

## Overview

End-to-end retail analytics project examining ₹1.49Cr in sales across product categories and geographies. The analysis surfaces margin inefficiencies, identifies high-value customer segments, and flags actionable opportunities for revenue and profitability improvement.

---

## Dataset

- **Tool:** Microsoft Excel
- **Scope:** Multi-region retail business — 8,399 orders, 214,777 units sold, 1,106 customers
- **Dimensions analyzed:** Product category, sub-category, region, sales manager, customer segment (RFM-based)

---

## Part 1 — Product Category Analysis

### What was asked
Which product categories and sub-categories are driving profit — and which are destroying it?

### Key findings

**Technology** is the star performer: 40.1% revenue share with the highest margin at 14.8%. Every Technology sub-category is profitable, with Telephones (16.8%) and Copiers & Fax (14.8%) leading.

**Furniture** is the biggest risk: despite being the second-largest revenue category (34.7% share, ₹51.8L), it delivers only 2.3% margin. Tables (-5.2%) and Bookcases (-4.1%) are actively loss-making — dragging down Chairs and Office Furnishings which are otherwise healthy at 8.5% and 14.4%.

**Office Supplies** has a split personality: Labels (35.1%), Binders (30.1%), and Envelopes (27.7%) are among the best performers company-wide. Scissors (-9.6%), Rubber Bands (-0.7%), and Storage (0.6%) are near-zero or negative.

### Sub-category margin ranking

| Sub-category | Margin % | Flag |
|---|---|---|
| Labels | 35.1% | ✅ Invest |
| Binders & Accessories | 30.1% | ✅ Invest |
| Envelopes | 27.7% | ✅ Invest |
| Telephones & Communication | 16.8% | ✅ Invest |
| Copiers & Fax | 14.8% | ✅ Healthy |
| Office Furnishings | 14.4% | ✅ Healthy |
| Office Machines | 14.2% | ✅ Healthy |
| Appliances | 13.2% | ✅ Healthy |
| Computer Peripherals | 11.8% | ✅ Healthy |
| Paper | 10.1% | ✅ Healthy |
| Chairs & Chairmats | 8.5% | ✅ Healthy |
| Pens & Art Supplies | 4.5% | ⚠️ Monitor |
| Storage & Organization | 0.6% | ⚠️ Review |
| Rubber Bands | -0.7% | 🔴 Loss-making |
| Bookcases | -4.1% | 🔴 Loss-making |
| Tables | -5.2% | 🔴 Loss-making |
| Scissors, Rulers & Trimmers | -9.6% | 🔴 Loss-making |

### Recommendations
- Reprice or discontinue Tables and Bookcases — their combined losses offset significant gains elsewhere
- Increase investment in Labels, Binders, and Envelopes — high margin with relatively low order volume suggesting untapped upside
- Audit Scissors and Storage for cost reduction before considering discontinuation

---

## Part 2 — Regional & Customer Segment Analysis

### What was asked
How does performance vary across regions and managers? Where is customer value concentrated — and where is it at risk?

### Regional overview

| Region | Manager | Revenue (₹) | Profit (₹) | Margin % | Customers | Rev/Customer (₹) |
|---|---|---|---|---|---|---|
| Central | Chris | 4,699,167 | 481,891 | 10.3% | 330 | 14,240 |
| East | Erin | 3,416,466 | 317,852 | 9.3% | 281 | 12,158 |
| South | Sam | 3,150,219 | 422,507 | **13.4%** | 234 | 13,462 |
| West | Unknown | 3,649,748 | 299,518 | **8.2%** | 261 | 13,984 |

### Key findings

**South is the efficiency leader.** Lowest revenue, second-highest absolute profit — Sam's region delivers the best margin (13.4% vs 10.2% company average), likely driven by better product mix or lower discounting.

**West has a margin problem.** Second-highest revenue but worst margin at 8.2% — working harder for less. The absence of a named manager is also a flag worth investigating for accountability gaps.

**Central leads on revenue per customer (₹14,240)** — highest customer value and strongest absolute revenue. The most important region to defend.

**East lags on both dimensions** — lowest revenue per customer (₹12,158) and below-average margin. Needs a focused strategy review.

### Customer segment breakdown (RFM-based)

| Segment | Total Revenue (₹) | Revenue Share |
|---|---|---|
| Champions | 5,465,496 | 36.6% |
| Loyal Customers | 5,290,176 | 35.5% |
| Potential Loyalists | 2,846,335 | 19.1% |
| At Risk | 1,021,826 | 6.9% |
| Lost | 291,757 | 2.0% |

Champions and Loyal Customers together account for **72% of total revenue** — healthy top-customer concentration. However, **₹13.1L sits in At Risk and Lost segments**, representing real recovery opportunity, particularly in Central where At Risk exposure is highest (₹3.8L).

### Recommendations
- Prioritize retention programs for At Risk customers in Central — highest absolute exposure
- Investigate West's cost structure and discounting behavior to close the margin gap
- Replicate South's product/pricing mix across regions as an efficiency benchmark
- Assign a named manager to West — accountability gaps often correlate with performance gaps

---

## Files

| File | Description |
|---|---|
| `Varsha_Baisane_Retail_Analytics.xlsx` | Full dataset and analysis workbook |

---

*Retail Analytics & Business Intelligence*
