# Placement-Eligibility-App
A Streamlit web application for analyzing campus placement data with dynamic eligibility filtering and SQL-based data insights.

Features:
1. Login Page: Basic login functionality to access the system.

2. About Page: Brief description of the project.

3. Student Eligibility Page:
   Dynamic filter to find eligible students based on:
      Minimum Problems Solved,
      Minimum Mock Interview Score,
      Maximum Age,
      Minimum Mini Project Completed,
      Minimum Assessments Completed,

4. Data Insights Page:

10 custom SQL queries executed on the database.

Visual insights (bar plots, pie charts, scatter plots, histograms) using Matplotlib.

Real-time display of query results in tables.

5. Datasets (SQLite Database)
Students_Table — Basic details of students.

Programming_Table — Programming skill-related data.

Soft_Skills_Table — Scores on various soft skills.

Placements_Table — Placement details and outcomes.

Using Faker, random library the datasets are created.

6. Technologies Used
Python 3

Streamlit — Web App development

SQLite3 — Lightweight relational database

Pandas — Data handling

Matplotlib — Visualizations

