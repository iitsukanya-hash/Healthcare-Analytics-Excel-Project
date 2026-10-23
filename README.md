# Healthcare Analytics Dashboard (Microsoft Excel)

An interactive Excel dashboard that analyses 9,976 patient records across admissions, medical conditions, billing, insurance and length of stay.

## Business Questions

- Which medical conditions are most common?
- Which admission type has the highest volume?
- Which conditions have the highest average billing?
- How long do patients stay, by admission type?
- Which insurance providers cover the most patients?
- How do conditions differ by gender?

## Data

- **9,976 patient records, 18 columns** (including 3 engineered columns), admissions from Oct 2018 to Oct 2023.
- Fields: patient demographics, medical condition, medication, test result, doctor, hospital, room, insurance provider, billing amount, admission type, admission and discharge dates.
- Billing amounts are shown in rupees (₹) in the dashboard.

## Data Preparation

- Checked for missing values and duplicate records (no duplicates remain).
- Standardised Admission Type labels (for example `Emer` to `Emergency`).
- Converted date columns to date format and billing to numeric.
- Engineered columns: **Length of Stay** (discharge minus admission date), **Admission Month and Year**, and **Age Group** (Young, Middle, Old).

## Dashboard

KPI cards (total patients, total billing, average billing), admission trends, condition distribution, billing by condition and admission type, insurance distribution, length of stay and gender analysis, with interactive Slicers. Built with Pivot Tables, Pivot Charts, Slicers and conditional formatting.

## Key Findings (verified against the workbook)

| Metric | Result |
|---|---|
| Total patients | 9,976 |
| Total billing | ₹233.3 M (average ₹23,389 per patient) |
| Most common condition | Hypertension, 2,150 patients (21.6%) |
| Highest average billing | Cancer, about ₹38,867 |
| Largest admission type | Emergency, 3,578 (35.9%) |
| Average length of stay | Emergency 15.6 days, Urgent 15.4, Elective 10.0 |
| Largest insurer by patients | Medicare, 2,421 (24.3%) |

- **Gender:** Hypertension is more common in male patients (61%), while Obesity (62%) and Diabetes (58%) are more common in female patients.
- **Trend:** Yearly admissions were stable at about 2,000 a year from 2019 to 2022 (peak 2021 with 2,060). 2018 (3 months) and 2023 (10 months) are partial years, so their lower counts are not a true decline.

## Suggested Follow-ups

- Review cost drivers for cancer treatment, which has the highest average bill.
- Study why Emergency and Urgent stays are 5 to 6 days longer than Elective stays.
- Examine hypertension patients by age group for prevention planning.

## Limitations

- Dataset appears to be a public sample dataset, not hospital records; results illustrate the analysis method.
- Findings are descriptive. They show patterns, not causes.

## Files

| File | Description |
|---|---|
| `Health care data analysis_100626.xlsx` | Dashboard, pivot tables and cleaned data |
| `HEALTHCARE ANALYTICS DASHBOARD PROJECT REPORT.docx` | Written project report |

## Demo

[Project walkthrough on YouTube](https://www.youtube.com/watch?v=fUkHNTxduBg&t=1s)

## Author

**Sukanya Saha** | [LinkedIn](https://www.linkedin.com/in/sukanya-saha-921a20295) | [Portfolio](https://sukanya-portfolio-rust.vercel.app/)
