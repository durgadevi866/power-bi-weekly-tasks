# Week 5 – Power BI Healthcare Data Transformation

## Overview
Week 5 focused on cleaning, transforming, and modelling the healthcare dataset using Power BI Power Query.

## Work Completed
- Cleaned categorical text fields using Trim and Clean.
- Standardized the Name column using Capitalize Each Word.
- Created an Age Group using a Conditional Column.
- Created the Billing table.
- Created the Dim_patient table and Patient ID.
- Created the Dim_Admission table and Admission ID.
- Merged Billing with Dim_patient using a Left Outer join.
- Merged Billing with the healthcare_dataset.
- Merged Billing with Dim_Admission.
- Created the final Billing table.
- Created relationships using Patient ID and Admission ID.
- Disabled the original healthcare_dataset from model loading.

## Final Data Model
The final Power BI model contains:
- Dim_patient
- Dim_Admission
- Billing

## Files
- `Week-5-Power-BI-Report.pdf` – Week 5 report with screenshots and explanations.
- `Week-5-Healthcare-PowerBI.pbix` – Power BI project file.
- `README.md` – Project documentation.

## Conclusion
The healthcare dataset was successfully cleaned, transformed, and organized into a structured Power BI data model. The final model is prepared for further analysis and dashboard development.
