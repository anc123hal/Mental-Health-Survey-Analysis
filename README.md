# Mental-Health-Survey-Analysis

🧠 Mental Health in Tech Survey – EDA Project
This project analyzes data from the 2014 OSMI (Open Sourcing Mental Illness) survey to explore how mental health is perceived, treated, and influenced in the tech industry.

📌 Objective
To identify:

Demographic patterns related to mental health (age, gender)

Treatment-seeking behavior

Employer support and company culture

Impact of work type and company size on mental health

📊 Dataset

Format: CSV

Fields: Age, Gender, Country, Work Interference, Treatment, Remote Work, Company Size, etc.

🧼 Data Cleaning
Removed invalid ages (<18 or >65)

Standardized gender values

Dropped irrelevant columns (comments, Timestamp)

Converted categories to consistent lowercase for uniformity

📈 EDA Overview
10+ charts and plots created using Python (Seaborn, Matplotlib):

Age & Gender Distributions

Treatment rates by demographics

Family history influence

Company size & remote work analysis

Bivariate insights (e.g., Gender vs Treatment)

Stacked bar: Country vs Treatment

📌 Key Insights
Most participants are aged 25–35

Females and transgender individuals seek treatment more than males

Family history strongly predicts mental health treatment

Small companies often lack adequate mental health support

Remote work shows no strong effect on treatment-seeking behavior

🧩 Tools Used
Python

Pandas

Seaborn / Matplotlib

Jupyter Notebook

📁 Files in Repository
survey.csv – Original dataset

Mental_Health_EDA_Full.ipynb – Full EDA notebook

cleaned_survey.csv – Cleaned dataset

README.md – Project overview

📄 Author
Anchal Thakur
June 2025

