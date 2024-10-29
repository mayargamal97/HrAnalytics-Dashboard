# HR Analytics Dashboard

## Table of Contents

- [About the Dashboard](#about-the-dashboard)
- [Dashboard Pages](#dashboard-pages)
- [Key Features](#key-features)


## About the Dashboard

The **HR Analytics Dashboard** is a Power BI dashboard designed to provide insights into human resources metrics. This dashboard helps organizations analyze key HR indicators like employee demographics, attrition rates, departmental performance, and more. It is intended for HR teams and business leaders who want to make data-informed decisions about their workforce.

## Dashboard Pages

### 1. Overview
The **Overview** page provides a high-level summary of the workforce. Key metrics displayed include:
- Total number of employees
- Active and inactive employee counts
- Overall attrition rate
- A snapshot of departmental distribution

![Screenshot (122)](https://github.com/user-attachments/assets/cbf1fcc1-4a4f-4ed9-97cc-ea8fe3400f90)


### 2. Demographics
The **Demographics** page offers insights into the makeup of the workforce. Visuals on this page show:
- Age distribution across employees
- Gender breakdown
- Marital status statistics
- Average salary distribution by ethnicity, providing a snapshot of diversity in the organization
  
![Screenshot (123)](https://github.com/user-attachments/assets/56012143-fb29-4312-b6d7-903621093478)

### 3. Attrition Rate
The **Attrition Rate** page focuses on understanding employee turnover. It includes metrics such as:
- Attrition by department to identify high-turnover areas
- Job role-based attrition rates, allowing HR to assess risk in specific roles
- Attrition segmented by experience level to see trends related to tenure
  
![Screenshot (124)](https://github.com/user-attachments/assets/16b86ea8-51d0-4e0d-bbe1-8082121f5af9)

### 4. Performance Tracker 
The **Performance Tracker** page (if applicable) allows users to monitor employee performance over time. This page may include:
- Trends in employee performance by department
- KPIs related to productivity and performance ratings
- Visual comparisons of high-performing and under-performing departments

![Screenshot (125)](https://github.com/user-attachments/assets/f1c80b16-3742-4a6a-b62b-d20e616204b9)

## Data Modeling

The data model for this dashboard is structured to facilitate efficient data retrieval and analysis. Key entities and relationships include:
- **Employee Table**: Contains employee demographic information, job roles, and salary details.
- **Department Table**: Holds data on various departments within the organization, allowing for department-level analysis.
- **Performance Table** (if applicable): Stores performance ratings and productivity metrics over time.
- **Attrition Table**: Captures historical data on employee attrition, including reasons for leaving and duration of employment.

![Screenshot (136)](https://github.com/user-attachments/assets/86465c0d-98fb-4259-be65-6749194afe3b)

The model is designed to support relationships between entities to allow seamless filtering and aggregation across different dashboard pages.

## Key Features

- **Dynamic Filters**: Each page includes filters for drilling down into specific categories such as department, job role, or demographic characteristics.
- **Interactive Visualizations**: Each visual allows users to interact and filter data to gain insights quickly.
- **Comprehensive Metrics**: Key metrics are covered across different pages to provide a holistic view of HR data.


*This dashboard project is designed to provide a detailed analysis of HR metrics, empowering organizations to leverage data in their HR decision-making processes.*

