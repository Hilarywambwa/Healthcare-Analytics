# Healthcare Dashboard - Power BI (2024)

## Project Overview
This project is a **Power BI dashboard** designed to analyze and visualize healthcare data for patients admitted in 2024. The dashboard provides insights into patient demographics, medical conditions, billing, and hospital stay metrics, enabling stakeholders to make data-driven decisions in the healthcare domain. The dataset was sourced from an Excel file and transformed to focus on 2024 data, with interactive visualizations linked to slicers for dynamic filtering.

This portfolio project demonstrates proficiency in **data transformation**, **data modeling**, and **data visualization** using Power BI, along with an understanding of healthcare analytics.

## Dataset Description
Source : https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data
The dataset contains detailed information about patient admissions in a healthcare setting. Each row represents a unique patient admission, with the following columns:

- **Age**: Patient's age at admission (in years).
- **Gender**: Patient's gender ("Male" or "Female").
- **Blood Type**: Patient's blood type (e.g., "A+", "O-", etc.).
- **Medical Condition**: Primary diagnosis (e.g., "Diabetes," "Hypertension," "Asthma").
- **Date of Admission**: Date of patient admission.
- **Doctor**: Name of the attending doctor.
- **Hospital**: Name of the healthcare facility.
- **Insurance Provider**: Patient's insurance provider (e.g., "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," "Medicare").
- **Billing Amount**: Amount billed for healthcare services (floating-point number).
- **Room Number**: Room number assigned to the patient.
- **Admission Type**: Type of admission ("Emergency," "Elective," "Urgent").
- **Discharge Date**: Date of patient discharge.
- **Medication**: Medication prescribed/administered (e.g., "Aspirin," "Ibuprofen," "Penicillin").
- **Test Results**: Outcome of medical tests ("Normal," "Abnormal," "Inconclusive").

### Data Transformation
- **Filtered Data**: Retained only 2024 admission data.
- **Age Groups**: Created custom age groups using DAX:
  - Teenager: <20 years
  - Young Adult: 20–35 years
  - Adult: 36–60 years
  - Senior: >60 years
- **Data Types**: Ensured correct data types for all columns (e.g., dates, numbers, categories).
- **Calculated Columns**:
  - Length of Stay: Calculated as the difference between `Discharge Date` and `Date of Admission`.
- **Data Cleaning**: Handled missing or inconsistent values (if any) to ensure data integrity.

## Dashboard Features
The Power BI dashboard includes the following **KPIs** and **visualizations**, all linked to interactive slicers for filtering by **Age Group**, **Blood Type**, and **Gender**.

### KPIs
1. **Total Patients**: Total number of patients admitted in 2024.
2. **Total Billing Amount**: Sum of billing amounts for all admissions.
3. **Average Length of Stay**: Average duration of hospital stays (in days).
4. **Total Admissions**: Total number of admissions in 2024.

### Visualizations
1. **Clustered Bar Chart**: Number of patients per medical condition, highlighting prevalent conditions.
2. **Clustered Column Chart**: Average length of stay per medication, showing treatment duration trends.
3. **Doughnut Chart**: Distribution of test results ("Normal," "Abnormal," "Inconclusive").
4. **Treemap**: Percentage of billing amount by insurance provider, identifying key payers.
5. **Stacked Column Chart**: Admission type ("Emergency," "Elective," "Urgent") by month, showing seasonal patterns.
6. **Line Chart**: Number of admissions per month, tracking admission trends over time.

### Slicers
- **Age Group**: Filter by Teenager, Young Adult, Adult, or Senior.
- **Blood Type**: Filter by blood type categories (e.g., "A+", "O-").
- **Gender**: Filter by Male or Female.

## Tools and Technologies
- **Power BI Desktop**: For data transformation, modeling, and dashboard creation.
- **Excel**: Source dataset stored in an Excel file.
- **DAX**: Used for calculated columns (e.g., Length of Stay) and age group categorization.

Check it out

![image](https://github.com/user-attachments/assets/a12e2dca-8042-4a3d-a22b-983fae84766f)
