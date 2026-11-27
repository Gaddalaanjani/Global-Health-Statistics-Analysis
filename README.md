# Global-Health-Statistics-Analysis

# Global Health Statistics – Data Analysis & Power BI Dashboard

## Project Overview
This project focuses on analyzing global healthcare statistics to identify disease trends, mortality rates, recovery rates, healthcare accessibility, and treatment costs across different countries and years.

The project demonstrates an end-to-end data analytics workflow using Excel, SQL, and Power BI.

## Tools & Technologies
- **Microsoft Excel:** Data cleaning, data validation, and preprocessing
- **MySQL:** Data querying and analysis
- **Power BI:** Interactive dashboards and data visualization
- **DAX:** KPI calculations and analytical measures

## Dataset Information
The dataset contains global health statistics covering:
- Countries and years
- Disease names and categories
- Prevalence, incidence, and mortality rates
- Age groups and gender
- Population affected
- Healthcare access
- Doctors and hospital beds
- Treatment types and costs
- Recovery rates and DALYs

## Project Workflow

### 1. Data Cleaning – Excel
- Inspected the dataset and column quality.
- Checked missing values and duplicate records.
- Standardized text values.
- Validated data types and numerical ranges.
- Investigated outliers and inconsistent records.

### 2. SQL Data Analysis – MySQL
- Retrieved and filtered healthcare records.
- Analyzed disease trends across countries.
- Compared mortality and recovery rates.
- Examined healthcare accessibility and treatment costs.

### 3. Power BI Dashboard Development
Created two interactive dashboard pages:

**Page 1 – Global Health Overview**
- Total records
- Total countries
- Total diseases
- Average mortality and recovery rates
- Disease prevalence comparisons
- Country-wise healthcare indicators
- Year-wise health trends

**Page 2 – Disease & Patient Analysis**
- Disease-wise mortality rates
- Age-group prevalence analysis
- Gender-wise recovery analysis
- Treatment type distribution
- Year-wise incidence trends
- Country and disease comparison matrix

## Key DAX Measures
Examples of measures used in the dashboard:

```dax
Total Records =
COUNTROWS('Global_Health_Cleaned')

Total Countries =
DISTINCTCOUNT('Global_Health_Cleaned'[Country])

Total Diseases =
DISTINCTCOUNT('Global_Health_Cleaned'[Disease Name])

Average Mortality =
AVERAGE('Global_Health_Cleaned'[Mortality Rate (%)])
```

## Dashboard Screenshots

Add your Power BI dashboard screenshots to the `Screenshots` folder, then display them here:

### Page 1 – Global Health Overview
![Global Health Overview](Screenshots/Dashboard_Page1.png)

### Page 2 – Disease & Patient Analysis
![Disease & Patient Analysis](Screenshots/Dashboard_Page2.png)

## Skills Demonstrated
- Data Cleaning
- Data Validation
- SQL Queries
- Exploratory Data Analysis
- DAX Measures
- KPI Development
- Data Visualization
- Dashboard Design
- Analytical Thinking

## Conclusion
This project demonstrates how healthcare data can be cleaned, analyzed, and transformed into interactive dashboards to explore global health patterns and support data-driven insights.
