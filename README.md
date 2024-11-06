#HR Analytics Dashboard for Employee Working Preferences

![Dashboard](https://github.com/aravindp2024/HR_Data_Analytics/blob/main/Presence_Insights.png)


Project Overview

The primary goal of this project is to develop a comprehensive HR Analytics dashboard that provides the Human Resources department with insights into employee working preferences, specifically focusing on Work From Home (WFH) and Work From Office (WFO) patterns. This dashboard is designed to support HR in making data-driven decisions by analyzing factors such as WFH trends on specific days (e.g., Mondays), usage of sick leave, and other relevant metrics.

Key Steps in the Project

1. Data Extraction and Transformation (ETL)

Data Source: The raw data was sourced from Excel files containing three months of HR records.
Data Consolidation: Monthly data files were consolidated into a single dataset for unified analysis.
Data Cleaning and Transformation:
Redundancy Removal: Duplicates and redundant records were removed to ensure data quality.
Unnecessary Column Removal: Only essential columns were retained for analysis, reducing dataset size and complexity.
Data Restructuring: Certain rows were transposed into columns to enable easier analysis and align with the report’s requirements.

2. Measure Creation

Based on stakeholder requirements, several measures were created to capture key metrics:
Sick Leave Percentage (SL%): Calculates the proportion of employees on sick leave.
WFH Percentage (WFH%): Analyzes the percentage of employees who opt for WFH versus WFO.
WFH Count: Tracks the count of employees working from home, broken down by days of the week and other specified periods.
These measures were implemented in DAX (Data Analysis Expressions) to provide dynamic and accurate calculations based on the filtered dataset.

3. Dashboard Design and Implementation

Leveraged Power BI to design an interactive, user-friendly dashboard that visualizes working trends, allowing HR to:
Identify patterns in WFH/WFO preferences.
Understand the correlation between sick leave and WFH on specific days.
Gain insights into employee behavior that can inform HR policies and workplace strategies.

4. Final Output
The HR Analytics dashboard provides a detailed breakdown of working preferences, enabling HR to make informed decisions around work policies and identify areas where adjustments might support productivity and employee well-being.

Technologies Used

Data Storage: Excel
ETL Tool: Power Query in Power BI
Data Transformation: DAX in Power BI
Visualization: Power BI for dashboard development and interactivity


This project showcases the application of ETL processes, custom measure creation, and data visualization techniques to deliver actionable insights to stakeholders. The final dashboard equips the HR team with a detailed understanding of working preferences, facilitating data-driven policy adjustments.
