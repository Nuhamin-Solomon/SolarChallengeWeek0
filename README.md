# SolarChallengeWeek0
Python-based solar energy analytics project featuring EDA, CI/CD, and Streamlit dashboard — 10 Academy Challenge.

Solar Radiation Data Analysis Project

Full Name: Nuhamin Solomon
Challenge Name: Week 0 – Solar Radiation Data Analysis
Submission Date: 14th November 2025

Overview

This project analyzes solar radiation datasets from Sierra Leone, Benin, and Togo. The goal is to evaluate data quality, understand environmental patterns, and prepare cleaned and standardized datasets for cross-country comparison. The project emphasizes reproducibility, automation readiness, and modular workflows suitable for future expansion.

Objectives

Ensure data quality by handling missing values, outliers, and timestamp inconsistencies.

Perform exploratory data analysis (EDA) to uncover temporal and environmental trends.

Standardize datasets for multi-country comparability.

Build a reproducible analysis workflow suitable for automation (CI/CD).

Prepare visualizations and insights to support renewable energy planning and decision-making.

Repository Structure
/solar-radiation-analysis
│
├── data/
│   ├── raw/             # Original datasets from Sierra Leone, Benin, Togo
│   └── clean/           # Cleaned and standardized datasets
│
├── notebooks/
│   ├── 01_data_profiling.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_analysis.ipynb
│   └── 04_export_and_summary.ipynb
│
├── scripts/
│   ├── data_cleaning.py
│   └── utils.py
│
├── README.md
└── requirements.txt

Tools & Libraries

Python 3.10+

pandas – data cleaning and manipulation

numpy – numerical computation

matplotlib & seaborn – visualization

scipy.stats – outlier detection

os & glob – file management

Jupyter Notebook – step-by-step exploration

Git/GitHub – version control

Implementation Overview

Environment Setup: Imported required libraries and configured the project.

Data Loading: Loaded datasets for all three countries and verified consistency.

Data Profiling: Generated descriptive statistics and checked for missing values or timestamp inconsistencies.

Data Cleaning: Applied median imputation for missing values and Z-score filtering to remove outliers.

Exploratory Data Analysis: Descriptive summaries of radiation, temperature, humidity, and wind patterns.

Correlation & Environmental Relationships: Analyzed relationships among irradiance variables, temperature, and humidity.

Exporting Clean Data: Cleaned and harmonized datasets exported for further analysis.

Current Status
Country	Data Cleaning	EDA (Descriptive)	Exported
Sierra Leone	✔ Completed	✔ Completed	✔ Completed
Benin	✔ Completed	✔ Completed	✔ Completed
Togo	✔ Completed	✔ Completed	✔ Completed
Next Steps

Integrate all cleaned datasets for cross-country comparison.

Develop interactive visualizations using Streamlit (optional bonus).

Prepare final report with complete charts, figures, and insights.

How to Run

Clone the repository:

git clone https://github.com/<your-username>/solar-radiation-analysis.git


Navigate to the project folder:

cd solar-radiation-analysis


Install required packages:

pip install -r requirements.txt


Open Jupyter Notebook and run notebooks step by step:

jupyter notebook

Notes

Cleaned datasets are located in /data/clean/.

All notebooks are modular and reproducible to allow for easy updates or extensions.
