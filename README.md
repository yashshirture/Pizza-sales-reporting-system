# 🍕 Pizza Sales Reporting System (Excel + SQL)

## 🧩 Problem  
Raw pizza sales data contained inconsistent date formats, missing fields, and duplicate order records.  
Using this data directly would lead to wrong revenue totals, misleading trends, and incorrect business decisions.

## 🎯 Objective  
Create a clean, repeatable reporting pipeline that converts messy sales data into reliable, business-ready metrics while preventing silent calculation errors.

## 🚨 Data Issues Identified  
- Duplicate order IDs  
- Missing quantities and prices  
- Inconsistent date formats  
- Category mismatches  
- Totals not matching raw records  

## 🛠️ Approach  
1. Separated raw data from clean working layers  
2. Standardized dates, categories, and numeric fields  
3. Built validation checks for:  
   - Duplicate orders  
   - Missing values  
   - Revenue mismatches  
4. Used **SQL** to:  
   - Aggregate orders  
   - Validate totals  
   - Cross-check business metrics  
5. Built structured Excel summaries for reporting  
6. Designed dashboards for revenue and demand trends  

## 🛡️ Validation & Control Logic  
- Order count checks between raw and clean layers  
- Revenue reconciliation between SQL and Excel outputs  
- Null and duplicate detection rules  
- Sanity checks for daily and monthly totals  

Any mismatch is flagged before reporting.

## 📊 Output  
- Clean transactional dataset  
- Revenue and order trend reports  
- Business-ready dashboard for performance tracking  

## 💡 Why This Matters  
Sales data is often trusted blindly—and that’s dangerous.  
This system is built to:

- Assume data can be wrong  
- Catch errors early  
- Prevent silent misreporting  
- Protect business decisions  

The goal is not charts.  
The goal is **reliable numbers**.

## 🧰 Tools Used  
- **MS Excel** – Cleaning, Validation, Structured Reporting  
- **SQL** – Aggregation, Reconciliation, Metric Validation  
