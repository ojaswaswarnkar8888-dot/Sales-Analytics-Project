# Sales-Analytics-Project
End-to-end Sales Analytics project using SQL, Excel, and Power BI.
An end-to-end sales analytics build on 5,000 orders spanning **Jan 2025 – Jun 2026**: data cleaning, SQL analysis, a 23-sheet analytics workbook, and a Power BI–style executive dashboard.

![Sales Analytics Dashboard](https://www.genspark.ai/api/files/s/ksGyQDRN)

---

## 🎯 Headline Results

| KPI | Value |
|---|---|
| Total Revenue | ₹62.56 Cr |
| Total Profit | ₹18.73 Cr |
| Profit Margin | 29.94% |
| Total Orders | 5,000 |
| Unique Customers | 3,813 |
| Avg Order Value | ₹1,25,111 |
| Total Units Sold | 27,726 |
| Top Product | Notebook (₹10.72 Cr) |
| Top Category | Electronics (₹21.30 Cr) |
| Top Region | North (₹23.95 Cr) |
| Top Salesperson | Neha (₹13.14 Cr) |
| Best Month / Season | March 2026 / Spring |
| Loss-making Orders | 0 |

---

## 🗂️ Project Structure

```
sales_project/
├── Sales_Analytics_Dataset_5000_Rows.xlsx   # raw dataset
├── Sales_Data_Cleaned.xlsx / .csv           # cleaned + enriched (Month/Quarter/Season/Margin)
├── 02_clean.py                              # data cleaning
├── 03_analyze.py                            # core analysis
├── 04_sql_analysis.py                       # SQL query runner
├── 05_dashboard.py                          # dashboard/chart generation
├── analytics_workbook.xlsx                  # 23-sheet workbook, all 12 analysis areas
├── sql_results.md / .xlsx                   # 40 queries + outputs
├── sales_analytics_queries.sql              # MySQL-dialect SQL script
├── business_insights.md                     # insights + recommendations
├── dashboard.png + chart_*.png              # Power BI-ready visuals
└── README.md
```

---

## 🛠️ Tech Stack

- **Python** — pandas, matplotlib/seaborn for cleaning and analysis
- **SQL** (MySQL dialect) — 40 analytical queries
- **Excel** — 23-sheet analytics workbook
- **Power BI** — dashboard layout (rebuild steps below)

---

## 🔍 Analysis Areas Covered

Revenue & profit trends · regional performance · category & product mix · salesperson ranking · payment mode split · discount-vs-profit relationship · category margins · top customers · day-of-week & seasonal patterns · customer retention windows · loss-order audit · order value distribution.

---

## 🧠 Key Business Recommendations

1. **Double down on North + Notebook** — the strongest revenue engine in the portfolio.
2. **Cut discounts on low-margin SKUs** — discount depth correlates negatively with profit; the profit-maximizing discount level is 0%.
3. **Re-engage at-risk, profitable customers** — target anyone with no purchase in 180+ days.
4. **Boost the East region** — lowest revenue, biggest untapped upside; launch a Q3 2026 campaign.
5. **Promote the hidden gems** — high-margin, low-volume SKUs are under-marketed.
6. **Coach up the lowest-margin salesperson** — replicate Neha's playbook (#1 in both revenue and profit).
7. **Plan inventory around seasonality** — build buffers ahead of March / spring peaks, trim them in slow months.
8. **Launch a loyalty programme** — repeat customers already drive a disproportionate share of profit.

---

## 🔨 Rebuilding the Power BI Dashboard

1. Import `Sales_Data_Cleaned.csv`.
2. Set data types (Date, numeric).
3. Add slicers on `Year`, `Quarter`, `Region`, `Category`, `Payment_Mode`.
4. Recreate the visuals shown in `dashboard.png` — every visual has a matching validation sheet in `analytics_workbook.xlsx`.

---

## 📥 Deliverables

| # | File | Description |
|---|---|---|
| 1 | `Sales_Data_Cleaned.xlsx` | Cleaned dataset, 5,000 × 23 columns |
| 2 | `analytics_workbook.xlsx` | 23-sheet workbook covering all 12 analysis areas |
| 3 | `sql_results.xlsx` | 40 SQL query results |
| 4 | `sales_analytics_queries.sql` | Raw MySQL-dialect SQL script |
| 5 | `business_insights.md` | Insights & recommendations |
| 6 | `dashboard.png` | Executive dashboard |
| 7 | `Sales_Analytics_Executive_Summary.pptx` | Slide deck version |
| 8 | `Sales_Analytics_Stakeholder_Report.pdf` | Stakeholder handoff report |

---

## 📄 License

This project is shared for portfolio purposes. Adapt freely with attribution.

---

*Reference date: 2026-07-20*

