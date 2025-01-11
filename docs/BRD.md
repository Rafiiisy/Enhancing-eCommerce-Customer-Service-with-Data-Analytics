# Business Requirement Document (BRD)
## 1. Executive Summary
Project Name: Enhancing eCommerce Customer Service with Data Analytics
Prepared By: M. Rafi Syafrinaldi
Date: 30-12-2024
Version: 1.0

### Overview:
This project focuses on analyzing customer satisfaction (CSAT) to identify key drivers, trends, and areas for improvement in customer service processes. Insights will be used to enhance operational efficiency and improve CSAT scores.

## 2. Project Objectives
- Analyze historical customer service data to uncover trends and insights.
- Identify the key factors affecting CSAT scores.
- Monitor customer service performance through an interactive dashboard.
- Provide actionable recommendations to improve customer service processes.

## 3. Business Need
### Current Challenges:

- Declining CSAT scores across specific product categories and shifts.
- Delays in responding to customer issues and completing surveys.
- Lack of real-time monitoring and reporting of customer service metrics.

### Opportunities:

- Improve customer satisfaction by addressing bottlenecks.
- Provide supervisors and managers with tools to monitor and enhance team performance.
- Automate insights for real-time decision-making.

## 4. Scope
### In-Scope:

Data cleaning, transformation, and analysis of historical customer service data.
Development of KPIs, including:
Average CSAT scores by Agent_name, Product_category, and Agent Shift.
Resolution time and survey delay trends.
Creation of a dynamic dashboard for performance monitoring.
Out-of-Scope:

Predictive modeling or forecasting.
Implementation of new customer service tools.

## 5. Stakeholders
Customer Service Agents: Need insights to improve individual performance.
Supervisors: Require detailed metrics to monitor teams.
Managers: Use dashboards to identify trends and allocate resources.
Data Analysts: Responsible for maintaining dashboards and data pipelines.

## 6. Functional Requirements
### Data Requirements:

Analyze the following columns:
- CSAT Score: Primary metric for satisfaction.
- connected_handling_time: Time spent handling issues.
- Resolution Time: Difference between Issue_reported at and issue_responded.
- Survey Delay: Time lag between issue_responded and Survey_response_Date.
- Aggregate data by:
Agent_name
Product_category
Agent Shift

### Dashboard Features:
KPIs:
Average CSAT Score.
Top agents based on CSAT.
Trends in Resolution Time and Survey Delay.
Filters:
By Agent Shift, Product_category, and Customer_City.

### Visualizations:
Bar charts for agent performance.
Line charts for CSAT trends over time.

## 7. Non-Functional Requirements
Scalability: Dashboard should handle large datasets and integrate with new data sources.
Performance: Dashboard refresh should occur within 30 seconds of updates.
Accessibility: Must be accessible to supervisors and managers on desktop and mobile devices.

## 8. Assumptions
Data is accurate and complete.
Agents consistently record issue resolution times and survey responses.
Stakeholders will have access to Google Looker Studio/Tableau for dashboard use.

## 9. Constraints
Dataset availability: Historical data only; no live streaming.
Time: The project must be completed within 3 weeks.
Budget: Free tools (Google Looker Studio, Python) must be used.

## 10. Key Metrics
CSAT Score: Customer satisfaction score.
Resolution Time: Time taken to resolve issues.
Survey Delay: Time between issue resolution and survey completion.
Agent Performance: CSAT score per agent, shift, and product category.

## 11. Deliverables
Cleaned and transformed dataset.
SQL queries for key metrics.
Interactive dashboard in Google Looker Studio/Tableau.
BRD and other documentation (ERD, Process Flow Diagram).

## 12. Risks
Data Quality: Missing or incomplete data may affect analysis.
Stakeholder Buy-in: Delay in stakeholder feedback could slow progress.
Technical Limitations: Dashboard tool limitations (e.g., refresh rates).