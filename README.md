### Disclaimer: This project is intended as an analytical and technical exercise, not as a tool for real-world policing decisions.

# Homicide Clearance Analytics

This project looks at homicide case clearance patterns in the United States using publicly available data. The goal is to better understand which factors are associated with cases being cleared, and to build a complete end-to-end data science project that includes data cleaning, SQL analysis, visualization, machine learning, and a lightweight AWS pipeline.

I built this project to strengthen my skills in data science and analytics engineering, and to create a portfolio piece that reflects a full project lifecycle rather than a single notebook.

## Project Goal

The main question behind this project is:

**What factors are associated with homicide case clearance, and how do clearance patterns differ across cities, time periods, and victim demographics?**

This project is designed to show the full workflow:
- working with raw data
- cleaning and validating the data
- modeling it in SQL
- exploring patterns through analysis and visualization
- building a machine learning model
- using AWS tools to support a cloud-based analytics workflow

## Why This Project

I wanted to build something that goes beyond exploratory analysis and shows how I approach a real data project from beginning to end. That includes:
- defining the question clearly
- organizing the repo in a reproducible way
- documenting assumptions and limitations
- building analysis-ready datasets
- communicating results through both code and visuals

Although the subject matter is crime data, the broader focus of the project is on outcome analysis, data quality, responsible modeling, and clear communication.

## Dataset

This project uses publicly available homicide data.

Source:(https://www.murderdata.org/p/data-docs.html)

Planned data work includes:
- understanding the structure and grain of the dataset
- identifying missing values and inconsistencies
- creating a cleaned version for analysis
- documenting field definitions in a data dictionary

## Tech Stack

Planned tools for this project:
- **Python** for cleaning, analysis, and machine learning
- **SQL** for transformations and analytical queries
- **Tableau** for dashboarding and visual storytelling
- **AWS S3, Glue, and Athena** for a lightweight cloud analytics workflow
- **GitHub** for version control and project documentation

## Planned Workflow
This project will be completed in stages:

1. Project setup and scoping
- define the project question
- organize the repo
- document goals, assumptions, and deliverables

2. Data cleaning and validation
- inspect raw data
- handle missing or inconsistent values
- create a cleaned dataset for analysis
- build a data dictionary

3. SQL modeling and analysis
- load cleaned data into a SQL-friendly structure
- create staging and summary tables
- write analytical SQL queries to answer key questions

4. Visualization
- create charts and dashboards to show trends in clearance rates
- compare patterns across cities, years, and demographic groups
- build a Tableau dashboard for portfolio presentation

5. Machine learning
- define a target variable for case clearance
- build a baseline model
- evaluate model performance
- interpret results and discuss limitations

6. AWS workflow
- store raw and processed data in S3
- query cloud-hosted data with Athena
- use Glue Data Catalog to organize tables

## Planned Deliverables
By the end of the project, this repository will include:

- a cleaned and documented dataset
- SQL scripts for transformations and analysis
- exploratory data analysis notebooks
- a machine learning workflow
- a Tableau dashboard
- architecture and project documentation
- a lightweight AWS setup using S3, Glue, and Athena

## Research Questions
Some of the questions I plan to explore include:

- How do homicide clearance rates vary across cities?
- How have clearance rates changed over time?
- Are there noticeable differences across victim demographic groups?
- Which variables seem most associated with a case being cleared?
- How much predictive signal is available in the data, and what are the limitations of that signal?

## Ethics and Limitations
This project uses sensitive data and should be interpreted carefully.

Important limitations include:

- crime data can reflect reporting and collection biases
- missing or inconsistent records may affect findings
- patterns in the data should not be treated as causal
- predictive models in this space can easily be misused if presented without context

