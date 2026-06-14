# 🏥 Healthcare Analytics Dashboard Using Microsoft Excel

## 📌 Project Overview

This project presents an interactive Healthcare Analytics Dashboard developed using Microsoft Excel to transform raw patient healthcare data into meaningful insights. The dashboard helps healthcare administrators analyze patient admissions, medical conditions, billing trends, insurance utilization, hospitalization patterns, and overall hospital performance through data-driven visualizations.

---

## 🎯 Business Problem

Healthcare organizations manage thousands of patient records containing information related to admissions, treatments, insurance providers, billing amounts, and hospital stays. Analyzing this data manually is challenging and may not provide actionable insights.

This dashboard was developed to answer key business questions such as:

- Which medical conditions are most common?
- Which admission type contributes the highest patient volume?
- Which diseases generate the highest treatment costs?
- How long do patients stay in hospitals on average?
- Which insurance providers are most frequently used?
- How do healthcare patterns vary across genders?

---

## 📊 Dataset Information

- Total Records: **9,976**
- Total Features: **18**

### Patient Information
- Name
- Age
- Gender
- Blood Type

### Medical Information
- Medical Condition
- Medication
- Test Result

### Hospital Information
- Doctor
- Hospital
- Room Number

### Financial Information
- Billing Amount
- Insurance Provider

### Admission Information
- Admission Type
- Admission Date
- Discharge Date

---

## 🧹 Data Cleaning & Preparation

### Missing Value Handling
- Checked for missing values in critical fields.
- Ensured data completeness for analysis.

### Duplicate Removal
- Identified and removed duplicate patient records.

### Data Standardization
- Standardized Admission Type values.
  - Emer → Emergency
- Standardized Blood Group values.
  - A Positive → A+
  - O Positive → O+
  - AB Negative → AB-
  - etc.

### Data Formatting
- Converted date columns into proper date format.
- Validated billing amounts as numeric values.

---

## ⚙️ Feature Engineering

### Length of Stay
Calculated using:

Length of Stay = Discharge Date - Admission Date

Purpose:
- Analyze hospitalization duration
- Resource utilization tracking

### Admission Month
Extracted from Admission Date for monthly trend analysis.

### Admission Year
Created to analyze yearly admission patterns.

### Age Group Categorization
Patients categorized into:
- Young
- Middle
- Old

---

## 📈 Dashboard Features

- KPI Cards
- Interactive Slicers
- Admission Trend Analysis
- Medical Condition Analysis
- Billing Analysis
- Insurance Provider Insights
- Length of Stay Monitoring
- Gender-Based Healthcare Analysis
- Yearly Admission Trends

---

## 🔍 Key Insights

- Hypertension is the most prevalent medical condition.
- Cancer patients incur the highest average medical bills.
- Emergency admissions contribute the highest patient volume.
- Emergency and Urgent admissions have longer hospital stays.
- Admissions increased steadily from 2019 to 2022 before slightly declining in 2023.
- Hypertension and Obesity are more common among male patients.
- Insurance utilization is distributed across multiple providers.

---

## 💡 Recommendations

- Prioritize hypertension prevention programs.
- Improve cost management strategies for cancer treatment.
- Increase emergency care resources.
- Reduce patient stay duration through efficient discharge planning.
- Expand preventive healthcare and early screening initiatives.

---

## 📈 Business Impact

This dashboard helps healthcare organizations:

- Improve decision-making
- Optimize resource allocation
- Enhance patient care management
- Monitor healthcare costs
- Identify healthcare trends quickly
- Support strategic planning

---

## 🛠 Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- KPI Cards


## 👨‍💻 Author sukanya saha

**PhD Research Scholar, CSIR-IICT** 
MSC in Chemistry, IIT Madras
Aspiring Data Scientist | Data Analyst  
Python | SQL | Excel | Power BI | Machine Learning
