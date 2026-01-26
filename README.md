# ============================================================
# Project Title: ApexCare General Hospital – Exploratory Data Analysis
# ============================================================

# Project Overview
# ApexCare General Hospital generates large volumes of patient data daily,
# ranging from admission records to billing information and clinical test outcomes.
# To support data-driven decision-making, it is essential to understand patterns
# within this data, identify trends, and uncover insights that can improve
# operational efficiency and patient care.
#
# In this project, an Exploratory Data Analysis (EDA) is performed on a synthetic
# healthcare dataset that mirrors real-world hospital patient records.
# The analysis explores patient demographics, admission types, medical conditions,
# billing behavior, insurance providers, length of stay, and test outcomes using
# Python and data analysis libraries.

# ------------------------------------------------------------
# Project Objectives
# ------------------------------------------------------------
# By the end of this project, the analysis aims to:
# - Understand the structure and quality of the healthcare dataset
# - Analyze patient demographics (age, gender, blood type)
# - Explore admission patterns (Emergency, Elective, Urgent)
# - Examine medical conditions and their frequency
# - Analyze billing amounts across admission types and insurance providers
# - Calculate and study patient length of stay using admission and discharge dates
# - Investigate test result outcomes and their distribution
# - Generate visual insights to support hospital decision-making

# ------------------------------------------------------------
# Business Questions
# ------------------------------------------------------------
# - What are the most common admission types in the hospital?
# - Which medical conditions are most frequently treated?
# - How are billing amounts distributed across patients?
# - Which insurance providers are associated with higher or lower average billing amounts?
# - How long do patients typically stay in the hospital?
# - Are there unusually long or short hospital stays (outliers)?
# - What is the distribution of patient test results?

# ------------------------------------------------------------
# Dataset Description
# ------------------------------------------------------------
# The dataset contains synthetic hospital patient records including:
# - Patient demographics (Age, Gender, Blood Type)
# - Admission Type
# - Medical Condition
# - Date of Admission
# - Discharge Date
# - Length of Stay
# - Billing Amount
# - Insurance Provider
# - Test Results
#
# The raw dataset required cleaning and validation before analysis.

# ------------------------------------------------------------
# Data Cleaning Process
# ------------------------------------------------------------
# The following data cleaning steps were performed:
# 1. Converted admission and discharge date columns to datetime format
# 2. Calculated length of stay from admission and discharge dates
# 3. Identified negative length of stay values caused by date inconsistencies
# 4. Replaced invalid negative length of stay values with NaN
# 5. Checked for missing values and data consistency
# 6. Ensured numerical and categorical columns were correctly formatted

# ------------------------------------------------------------
# Analysis Steps
# ------------------------------------------------------------
# 1. Explored dataset structure and summary statistics
# 2. Analyzed patient demographics using histograms
# 3. Examined admission types using frequency counts and count plots
# 4. Analyzed medical conditions using value counts and bar charts
# 5. Explored billing amount distribution using histograms and KDE plots
# 6. Calculated average billing amount by insurance provider
# 7. Analyzed length of stay using boxplots to identify variability and outliers
# 8. Investigated test result outcomes using frequency analysis

# ------------------------------------------------------------
# Visualizations
# ------------------------------------------------------------
# The following visualizations were created:
# - Histogram: Age Distribution of Patients
# - Count Plot: Distribution of Admission Types
# - Bar Chart: Most Common Medical Conditions
# - Histogram + KDE: Billing Amount Distribution
# - Boxplot: Length of Stay Distribution

# ------------------------------------------------------------
# Key Insights
# ------------------------------------------------------------
# - Emergency admissions occur more frequently than elective admissions,
#   indicating a high demand for urgent care services.
# - Certain medical conditions appear more frequently, highlighting areas
#   requiring focused medical resources.
# - Billing amounts show a skewed distribution with a small number of high-cost cases.
# - Average billing amounts vary by insurance provider, supporting informed
#   insurance partnership decisions.
# - Most patients have short to moderate hospital stays, with a few outliers
#   representing unusually long admissions.
# - Test result distributions provide insights into patient health outcomes.

# ------------------------------------------------------------
# Tools Used
# ------------------------------------------------------------
# - Python
# - Pandas
# - NumPy
# - Matplotlib
# - Seaborn
# - Jupyter Notebook

# ------------------------------------------------------------
# Author
# ------------------------------------------------------------
# Name: Tomisin
# Role: Data Analyst
