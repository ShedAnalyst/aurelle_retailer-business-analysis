# Aurelle Retailer Business Analysis

## 📊 Project Overview
An analysis of a luxury retailer's sales performance across **2020–2025**, covering 
revenue, profit, product categories, brands, and return rates.

## 📁 Files in This Repository

| File | Type | Description |
|------|------|-------------|
| `excel_project_g4.xlsx` | Workbook | **Source of truth.** Contains the `Cleaned Data` sheet (transaction-level dataset with calculated fields), the `Analysis` sheet (pivot tables + YoY growth block), and the `Dashboard` sheet (charts). |
| `cleaned_data.csv` | Data | Snapshot export of the `Cleaned Data` sheet for **in-browser preview** — GitHub renders it as a searchable table. Read-only convenience copy. |
| `dashboard.png` | Image | Screenshot of the Excel dashboard, embedded above. |
| `retailer_analysis_presentation.pptx` | Slides | Summary deck of findings and recommendations. |
| `retailer_analysis_report.pdf` | Report | Full written report with methodology, findings, and recommendations. |

> 💡 The `.xlsx` file is the authoritative source. Pivot tables and charts do not 
> render on GitHub, so `dashboard.png` and `cleaned_data.csv` exist purely so 
> reviewers can evaluate the work without downloading anything.


## 🔍 Key Insights
- **Total Revenue:** ₦8.59B across 6 years, with **+22.9% growth in 2025** vs. 2024.
- **Top Category:** Handbags (2,154 units) — the largest product category by volume.
- **Top Brand:** Maison Aurelle (3,056 units sold).
- **Best-Selling Products:** Mini Shoulder Bag (587), Leather Tote (538), 
  Structured Satchel (518).
- **Highest Return Rate:** Ready-To-Wear (8.17%).
- **Overall Profit Margin:** 38.25%.

## 🛠️ Tools Used

- **Microsoft Excel** — data cleaning, calculated fields, PivotTables, PivotCharts, `GETPIVOTDATA`, dashboard assembly
- **PowerPoint** — summary presentation
- **Word / PDF** — written report
- **GitHub** — version control and publication

## 👥 Authors
Osakpolor Osagie

## 📌 How to Use This Repository

1. **Just want the findings?** Read `retailer_analysis_report.pdf`, or scroll up to *Key Insights*.
2. **Want the visuals?** Open `retailer_analysis_presentation.pptx`, or view `dashboard.png` above.
3. **Want to explore the data?** Click `cleaned_data.csv` — GitHub renders it as a table you can scan without downloading anything.
4. **Want to interrogate the analysis?** Download `excel_project_g4.xlsx`:
   - `Cleaned Data` — transaction-level dataset and all calculated columns
   - `Analysis` — the pivot tables and the `GETPIVOTDATA` YoY growth block
   - `Dashboard` — the charts shown in the preview
   - *Note: pivot tables may require a refresh (Data → Refresh All) on first open.*
