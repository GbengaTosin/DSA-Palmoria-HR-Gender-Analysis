# DSA-Palmoria-HR-Gender-Analysis
A Power BI HR analytics project for Palmoria Group, focused on uncovering gender inequality issues in workforce distribution, salary structure, and hiring trends across regions.


# 📊 DSA Palmoria HR Gender Inequality Analysis

> This Power BI project was developed as part of the Digital Skillup Africa (DSA) Data Analytics program to analyze HR data from the Palmoria Group, a manufacturing company in Nigeria. The project uncovers gender disparities in employment, compensation, and leadership roles across the company’s three regional operations.

## 📁 Project Overview

Palmoria Group recently faced public criticism due to allegations of gender inequality, following a viral headline: **“Palmoria, the Manufacturing Patriarchy”**. In response, the CHRO tasked a data analyst to investigate the company’s HR data for areas of gender bias.

As the analyst, I explored key indicators that could reveal issues in gender distribution, salary differences, hiring rates, and promotions — and provided actionable recommendations for management.

## 🔧 Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data modeling and relationships

## 🧼 Data Cleaning and Preparation

The dataset was preprocessed and cleaned before analysing to ensure accuracy and reliability. Key data cleaning steps included:

- **Handling Missing Gender**: Some employees did not disclose their gender. A generic label such as `"Unspecified"` was assigned to ensure data completeness while preserving neutrality.
- **Filtering Non-Active Employees**: Employees with no salary were assumed to have exited the organization. These records were excluded from the analysis to avoid skewing salary insights.
- **Removing Invalid Departments**: Rows with `NULL` department values were excluded, as they do not provide meaningful data for departmental-level analysis.
- **Standardizing Fields**:
  - Capitalization of gender and department names
  - Ensuring consistent region names across all records
- **Calculated Fields Created**:
  - Gender ratio by department and region
  - Average salary by gender
  - Gender distribution across job levels

## 📊 Exploratory Data Analysis (EDA)

An initial exploration of the cleaned dataset was performed to understand the structure, detect gaps, and spot early trends. This included:

- Gender counts and proportions across departments and regions
- Average salaries by gender and job level
- Hire and promotion history by gender
- Distribution of employees with unspecified gender

These insights guided the construction of Power BI dashboards and KPIs.

## 📈 Data Analysis

The final Power BI report was built using interactive visuals and DAX measures. It focuses on:

- **Gender Representation**: Percentage of men vs women across departments, job levels, and regions.
- **Salary Analysis**: Comparing average salaries between genders across departments.
- **Region Comparison**: Identifying regional variations in gender balance and pay equity.

## 📦 Data Source

The dataset was provided as part of the DSA (Digital Skillup Africa) program for educational purposes and is based on a fictional manufacturing company in Nigeria. All data has been anonymized and is safe for public presentation.

## Visual Preview

Here are some sample chart from my Excel analysis:

![Sales Chart](https://github.com/GbengaTosin/DSA-Palmoria-HR-Gender-Analysis/blob/main/Screenshot%202025-07-04%20181730.png)


