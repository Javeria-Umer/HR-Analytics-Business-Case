# HR Analytics Report - Atlas Labs

## Objective
The primary goal of this HR Analytics Report is to provide actionable insights to Atlas Labs by analyzing Human Resources data. By examining employee demographics, performance metrics, and attrition rates, the report aims to identify areas for improvement and develop effective strategies to enhance employee retention and satisfaction.

## Table of Contents
1. [Data Transformation](#data-transformation)
2. [Building the Data Model](#building-the-data-model)
3. [Writing DAX Measures](#writing-dax-measures)
4. [Measures Table](#measures-table)
5. [Overview Page](#overview-page)
6. [Demographics Page](#demographics-page)
7. [Performance Tracker Page](#performance-tracker-page)
8. [Attrition Page](#attrition-page)
9. [Navigator Bar](#navigator-bar)
10. [Published Report on Power BI](#published-report-on-power-bi)

## 1. Data Transformation<a name="data-transformation"></a>
**Description**: 
The data transformation phase involves extracting HR data from various sources such as database. Using Power Query Editor in Power BI, cleaned and transformed the raw data to ensure its accuracy and consistency. This includes tasks such as renaming columns, adjusting data types, and combining first and last name columns etc.

## 2. Building the Data Model<a name="building-the-data-model"></a>
**Description**: 
Building the data model is a crucial step in the analysis process. Design the data model in Power BI by identifying key entities such as employees, departments, and performance metrics. Created dimension tables for entities and fact tables for performance metrics, establishing relationships between them to form a star schema. This structured approach facilitates efficient analysis and visualization of HR data.

![Data Model Page](link_to_data_model_screenshot)

## 3. Writing DAX Measures<a name="writing-dax-measures"></a>
**Description**: 
Data Analysis Expressions (DAX) is a powerful formula language used in Power BI for creating calculated measures. In this phase, have writen DAX formulas to derive meaningful insights from the HR data. Calculate various metrics such as attrition rate, average salary, and performance ratings using DAX functions and expressions. These calculated measures provide valuable insights into employee trends and help in making data-driven decisions.

## 4. Measures Table<a name="measures-table"></a>
**Description**: 
To organize and document the calculated measures, we add a Measures table to the data model in Power BI. This table serves as a reference for all the calculated metrics created using DAX. Each measure is listed along with a description of its calculation logic, providing clarity and transparency in the analysis process. The Measures table enhances the usability of the report and facilitates collaboration among team members.

## 5. Overview Page<a name="overview-page"></a>
**Description**: 
The Overview Page provides a high-level summary of key HR metrics and trends. It includes visual representations such as card visuals, stacked column and pie charts to present information on total employees, active employees, inactive employees, attrition rate, total employees by job role and department, active employees by department, and employee hiring trends. This page serves as a dashboard for stakeholders to quickly grasp the current state of HR metrics.

![Overview Page](https://github.com/Javeria-Umer/HR-Analytics-Business-Case/blob/main/Overview.png?raw=true)

## 6. Demographics Page<a name="demographics-page"></a>
**Description**: 
The Demographics Page delves into employee demographics, providing insights into various characteristics such as age, marital status, and gender. It includes visualizations such as slicers, card visuals, stacked bar chart, clustered bar chart, line and stacked column chart and donut chart to showcase the distribution of employees across different demographic categories. This page helps in understanding the composition of the workforce and identifying demographic trends.

![Demographics Page](link_to_demographics_screenshot)

## 7. Performance Tracker Page<a name="performance-tracker-page"></a>
**Description**: 
The Performance Tracker Page focuses on tracking employee performance metrics over time. It includes visualizations such as slicers, card visuals, and line charts to display metrics like environment satisfaction, job satisfaction, relationship satisfaction, work-life balance satisfaction, self-rating, and manager rating. This page allows stakeholders to monitor performance trends and identify areas for improvement.

![Performance Tracker Page](link_to_performance_tracker_screenshot)

## 8. Attrition Page<a name="attrition-page"></a>
**Description**: 
The Attrition Page analyzes factors contributing to attrition rates within the organization. It includes visualizations such as card visuals, stacked bar charts, line chart and stacked column chart to display attrition rates based on factors such as overtime requirement, tenure, job role, department, and travel frequency. This page provides insights into attrition patterns and helps in developing strategies to mitigate attrition.

![Attrition Page](link_to_attrition_screenshot)

## 9. Navigator Bar<a name="navigator-bar"></a>
**Description**: 
The Navigator Bar is a user interface element that provides navigation buttons for each page of the report. It allows users to easily navigate between different sections of the report, enhancing the overall user experience and accessibility.

## 10. Published Report on Power BI<a name="published-report-on-power-bi"></a>
**Description**: 
The HR Analytics Report has been published on Power BI for broader accessibility. You can access the published report by following this [link](https://app.powerbi.com/groups/23c82551-299f-4b59-a21a-9ee026b1fb87/reports/2d24b827-58d0-48ac-a7d6-b214369bc3d8/ReportSectionf5ae3d2766c172605c07?experience=power-bi). Feel free to explore the interactive visualizations and gain valuable insights into HR metrics.
