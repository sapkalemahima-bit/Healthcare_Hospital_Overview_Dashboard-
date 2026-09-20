# Healthcare Analytics Dashboard | Power BI

**50K Patients | ₹1.28bn Revenue | ₹25.56K Avg Billing**

### Overview
Built interactive healthcare dashboard from 50K cleaned records (from 59K raw) to analyze hospital performance, billing, patient demographics and admission trends.

### Data Cleaning: 59K -> 50K
- Excel: Removed duplicates, fixed spelling like 'abnromal', created Age Groups (13-18 Teen, 19-30 Young Adult, 31-50 Adult, 51-64 Middle Age, 65-75 Senior, 76+ elderly )
- Power Query: Removed null billing, invalid dates, formatted billing to ₹
- Kept 10 analytical columns, removed PII columns like Patient Name, Doctor Name, Room No.

### Dashboard 1: Hospital Overview Dashboard
- **KPIs:** 50K Total Patients | ₹1.28bn (₹127.77 Cr) Total Revenue | ₹25.56K Avg Billing
- **Patient Distribution by Age Group, Gender and Medical Condition:** Arthritis, Asthma, Cancer, Diabetes across 5 age groups with Female/Male split. Adult (31-50) has highest count.
- **Sum of Billing by Hospital and Gender:** Top 10 hospitals - Johnson PLC, LLC Smith, Ltd Smith, Smith PLC etc. with Gender breakdown.
- **Hospital-wise Billing (A-Z):** Matrix with Female ₹63.73Cr, Male ₹64.04Cr, Total ₹127.77Cr
- **Slicer:** Hospital dropdown

### Dashboard 2: Admission and Treatment Analysis Dashboard
- **Billing by Admission Type and Test Result:** Elective, Urgent, Emergency vs Abnormal, Inconclusive, Normal - almost equal distribution (~₹140M each)
- **Patient Admission Trend (Monthly) by Gender:** Line chart Jan-Dec, stable trend around 2000-2100 patients per month, dip in Feb
- **Test Result Distribution:** Abnormal 33.64% (869K), Normal 33.19% (858K), Inconclusive 33.17% (857K) - balanced
- **Slicers:** Admission Type buttons + Date of Admission dropdown

### Key Insights
1. Adult group 31-50 is highest patient base across all conditions
2. Revenue equally split between Female and Male, and across admission types
3. Test results are balanced, no major skew
4. Monthly admissions stable, slight drop in February

### Tools
Excel (Cleaning, IF formulas) | Power BI (Power Query, DAX, KPI Cards, Matrix, Slicers)

### Files
`healthcare 50K final.pbix` | `healthcare 50K final.xlsx` | Screenshots

### Demo
Live via Power BI Desktop screen share