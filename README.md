# Retention Framework Insights

## Project Overview
This project analyzes user engagement and retention patterns for a local company in Tecumseh, Ontario.  
The goal is to understand how users move through their learning journey, identify drop-off points, and provide actionable insights to improve retention and engagement.

The data was sourced from Halight via AWS Athena.

## Contents
1. [Group Information](#group-information)
2. [Project Name](#project-name)
3. [Project Purpose](#project-purpose)
4. [Business Benefits](#business-benefits)
5. [Appendix](#appendix)
   - [Preliminary Dashboard in Power BI](#1-preliminary-dashboard-in-power-bi)
   - [RCS dataset](#2-rcs-dataset)
   - [Exploratory Data Analysis (EDA)](#3-exploratory-data-analysis-eda)
   - [Business Case and Project Charter](#4-business-case-and-project-charter)
   - [Machine Learning Predictions](#5-machine-learning-predictions)

## Group Information:
- **Project Sponsor**: Sean Bridgeman
- **Project Coordinator**: Prof. Manjari Maheshwari 
- **Core Team Members (5-person team):**
    - Eddie Morgan (Team Lead)
    - Diego Moreno
    - Sofia Alfaro
    - Pamela Gatica
    - Yazan Al Shash

## Objectives
- Identify user drop-off points (attrition analysis)
- Understand engagement behavior over time
- Forecast future engagement trends
- Support data-driven decision-making

## Business Value
- Improve user retention through targeted strategies  
- Enable data-driven product decisions  
- Automate reporting and reduce manual analysis  
- Identify growth opportunities through user behavior patterns  

## Dataset
This project uses two main datasets extracted from AWS Athena:
1. rcs_lifetime_stats_by_month_v
   - Used for:
      - Exploratory Data Analysis (EDA)
      - Machine Learning models
      - Initial Power BI dashboard
   - Key Metrics:
      - Average daily engagement score
      - Total lifetimes
      - Online users
      - Monthly trends
        
2. rcs_historic_users_v
   - User-level historical dataset
   - Used for advanced analytics and final dashboards
   - Applied in:
      - Attrition Analysis --> Identifying user drop-off behavior
      - What-If Analysis --> Simulating retention improvements
      - Cohort Analysis --> Tracking user retention over time
    
## Data Strategy

The project follows a layered approach:

- Aggregated data (rcs_lifetime_stats_by_month_v)
   - Used for high-level trends, forecasting, and modeling
- User-level data (rcs_historic_users_v)
   - Used for deep behavioral analysis and retention insights

This combination allows both macro-level insights and granular user analysis, improving the overall quality of the findings.

## Appendix:
The deliverables for our Capstone Project are listed down below:

### 1. _**Preliminary Dashboard in Power BI**_
   - Displays insights about user engagement metrics, such as:
      - Online users (Current Month vs Last Month and Last Year)
      - Average Daily Engagement Score over time
      - Total & Average Lifetimes per User

### 2. **_Exploratory Data Analysis (EDA)_**
   - Identified patterns and relationships in user behavior  
   - Detected outliers and engagement trends  
   - Prepared data for machine learning models  

### 3. **_Business Case and Project Charter_**
   - This section outlines the purpose, justification, and structure of the project.
   - It defines the problem being addressed, project objectives, expected benefits, constraints, and risks.
   - It also establishes the project scope, key stakeholders, and high-level plan that will guide the development process.
  
### 4. **_Machine Learning Predictions_**
   - In this section, we apply three machine learning techniques to classify engagement levels (high vs. low) and to forecast engagement trends for 2026 using historical data.
   - The models and techniques used include:
        - Seasonal Naive Forecasting for projecting future engagement trends
        - K-Means Clustering for identifying engagement patterns
        - Logistic Regression for predicting high and low engagement

### 5. **_Power BI Dashboards_**
**[View / Download Dashboard][https://app.powerbi.com/links/PmzuyMfD2r?ctid=c986676f-9b39-4d08-b4f8-a668e0e8c6a5&pbi_source=linkShare&bookmarkGuid=b1fd4ac0-96f4-4573-9bcb-ba9c6bed2a52]**
   - Dashboard Features:
      - **Attrition Analysis** → Identifies where users drop off  
      - **What-If Analysis** → Simulates retention scenarios  
      - **Cohort Analysis** → Tracks user retention over time  
   - **Engagement Metrics**:
     - Online users (MoM / YoY)
     - Average daily engagement score
     - User lifetime metrics  
