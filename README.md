# Module_End_Assignment_1_Excel
Healthcare Analysis and Insights
# Healthcare Data Analysis Assignment Using Excel

## 1. Assignment Overview

This assignment focuses on cleaning, transforming, analyzing, and visualizing healthcare data using Microsoft Excel and Power Query.

The dataset contains patient details, medical examination results, and hospitalization information. The aim is to combine these datasets and analyze the relationships between patients' health conditions, age, and healthcare charges.

## 2. Tools and Techniques Used

- **Microsoft Excel** – Data analysis, calculations, and visualization
- **Power Query** – Data cleaning and transformation
- **VLOOKUP** – Combining data from multiple tables using Customer ID
- **PivotTables** – Summarizing and analyzing healthcare data
- **PivotCharts** – Visualizing analysis results
- **KPI Cards and Slicers** – Presenting key metrics and enabling interactive filtering

## 3. Data Cleaning and Transformation

The following data preparation tasks were performed:

- Handled missing and invalid values using appropriate replacement methods.
- Standardized text values and corrected data types.
- Trimmed and cleaned text columns to remove unwanted spaces and characters.
- Split customer names into First Name, Title, and Last Name.
- Replaced `No major surgery` with `0` in the NumberOfMajorSurgeries column.
- Created **Weight Status** categories using BMI values:
  - Underweight
  - Normal Weight
  - Overweight
  - Obesity
- Created **Diabetes Status** categories using HBA1C values:
  - Normal
  - Prediabetes
  - Diabetes
- Combined year, month, and date into a Date of Birth column.
- Calculated patient age as of 8 June 2023.
- Formatted healthcare charges as currency.
- Combined Customer Names, Medical Examinations, and Hospitalization Details using Customer ID and VLOOKUP into a new sheet called Healthcare.

## 4. Data Analysis and Visualization

PivotTables and charts were created to answer the following questions:

1. **Cancer History and Smoking Status:** Analyzed the distribution of cancer history among smokers and non-smokers using pie or doughnut charts.
2. **Transplant History:** Compared the total number of major surgeries and average HBA1C between patients with and without a history of transplants.
3. **Weight Status and Diabetes Status:** Compared total healthcare charges across different weight and diabetes categories.
4. **Hospital Tier and State:** Compared average healthcare charges for hospital tiers across different states.
5. **Age, BMI, and HBA1C:** Explored how BMI and HBA1C vary across different age groups.
6. **Age and Healthcare Charges:** Examined how total healthcare charges vary by patient age.

## 5. Interactive Dashboard

An interactive dashboard was created to present key findings in a clear and organized format.

The dashboard includes:

- KPI cards highlighting important healthcare metrics.
- Charts representing the results of the six analysis questions.
- A **Weight Status** slicer for filtering data by weight category.
- A **Diabetes Status** slicer for filtering data by diabetes category.

## 6. Conclusion

This assignment provided practical experience in data cleaning, data transformation, data analysis, and visualization using Excel and Power Query. It demonstrated how multiple datasets can be combined and analyzed to identify patterns in patient health information and healthcare charges.
The dashboard brings the key analysis results together in one place and supports interactive exploration of the data.
<img width="1862" height="661" alt="Screenshot 2026-10-14 213653" src="https://github.com/user-attachments/assets/6aed0a7e-0ca3-4179-9889-b812e8a54eaa" />
