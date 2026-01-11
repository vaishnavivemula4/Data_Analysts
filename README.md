-->Project Overview
This project provides a comprehensive analysis of employee attrition and performance. By building a full data pipeline—from cleaning raw data in Python to querying in SQL and visualizing in Power BI—I have identified key factors that lead to employee turnover and provided actionable business recommendations.

-->Tech Stack
Python (Pandas): Data cleaning and exploratory analysis.

SQL (PostgreSQL): Data transformation and structured storage.

Power BI: Interactive dashboarding and visualization.

Microsoft PowerPoint: Stakeholder communication and reporting.

-->File Guide
To make it easy to navigate my work, here is what each file represents:

hr_analysis_report.pdf: Start Here. This is the final executive report containing the dashboard and key findings.

HR_Attrition_Analysis.ipynb: The Jupyter Notebook showing my Python ETL and data cleaning process.

hr_analysis_queries.sql: The SQL script used to manage the data in PostgreSQL.

hr_analysis_performance_insights.pptx: The presentation deck used to explain insights to business leaders.

data.csv: The raw HR dataset used for this project.

-->Business Insights
Attrition Awareness: Identified a company-wide attrition rate of 51%.

High-Risk Roles: The Production Technician role and specific locations (Zone A/B) show significantly higher exit rates.

Performance Correlation: Analysis shows that employees with lower engagement scores are at a much higher risk of leaving.

-->How to Run Locally
Note: This project uses local database connections and file paths (Windows-based).

Clone the repository.

Load data.csv into your SQL environment using hr_analysis_queries.sql.

Update the database credentials in HR_Attrition_Analysis.ipynb to match your local PostgreSQL setup.

Open the PDF report to view the Power BI design.

-->License
This project is licensed under the MIT License.
