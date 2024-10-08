
# Data Analysis with Tableau

## Overview

This project focuses on analyzing the relationship between education, health, and economic indicators across various countries. Using data from The World Bank, this analysis is visualized in Tableau to uncover insights and answer key questions about how these factors interact.

## Steps of the Project

### 1. Data Sets, Sources Used, and Topic

**Data Sources:**

-   **Education Data Set:** Country name, year, government expenditure on education, government expenditure per student (primary), children out of school (primary).
-   **Health Data Set:** Country name, year, births attended by skilled health staff, infant mortality rate, immunization rate.
-   **GDP Data Set:** Country name, year, GDP, GDP per capita.

**Source:** All data sets were sourced from The World Bank Website.

**Topic:** Analyzing the relationship between education and health indicators, and how they relate to a country's economic conditions.

### 2. Data Preparation

Data preparation was done using Excel to ensure consistency and completeness before importing the data into Tableau:

-   **Replace Nulls:** Null values were replaced with zero values.
-   **Rename Columns:** Standardized the column names across data sets, especially for the year columns.
-   **Unpivot Columns:** Unpivoted year columns to create a single year column and a corresponding value column.
-   **Pivot Columns:** Pivoted the indicators column with the value column to align the data for analysis.

### 3. Key Questions

The analysis in Tableau addresses the following questions:

1.  **Education and Dropout Rates:**
    
    -   Is there a relationship between government expenditure on education and the number of students dropping out of school?
2.  **Immunization and Infant Mortality:**
    
    -   Does a country with a high immunization rate have a lower infant mortality rate?
3.  **Education Spending and School Dropouts:**
    
    -   In each year, does increased spending on education prevent students from leaving school?
4.  **Primary Education Expenditure and Skilled Birth Staff:**
    
    -   If a country increases expenditure per primary school student, does it also lead to a higher percentage of births attended by skilled health staff?
5.  **Skilled Staff at Birth and Infant Mortality:**
    
    -   Is there a relationship between the presence of skilled staff during birth and the infant mortality rate?

## Conclusion

This project provides a comprehensive analysis of global education, health, and economic indicators. Tableau is used to visualize the relationships between these factors, helping stakeholders gain insights into how improvements in one area (such as education) might affect others (such as health outcomes).
