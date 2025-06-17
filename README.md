---
date: "Monday June 16th, 2025"
---

# AI Job Market Analysis 2024-2025

## Project Overview

This project analyzes the United States [AI job market dataset in 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025). The analysis provides insights into compensation trends, required skills, and factors affecting salary variations in the AI field. The project aims to support STEAMe's mission as "The Engine for Workforce Transformation" by providing data-driven insights for job seekers, employers, training providers, and workforce intermediaries.

## Dataset

The dataset contains 724 AI and machine learning job listings in the United States with information on:
    - Job titles and roles
    - Salary information
    - Experience levels
    - Employment types
    - Required skills
    - Education requirements
    - Industry sectors
    - Company characteristics

## Analysis Structure

The analysis is divided into two main parts:

### 1. Descriptive Analysis

- Distribution of job titles and roles in the AI field
- Salary distributions across experience levels, industries, and job types
- Relationship between years of experience and compensation
- Impact of company size on salary offerings
- Variations in salary by employment type

### 2. Diagnostic Analysis

- Identification of high-value skills in the AI job market
- Calculation of salary premiums for specific skills
- Analysis of skill domain coverage and its impact on compensation
- Examination of how skill premiums vary across experience levels

## Key Findings

- Salary distributions vary significantly by job title, experience level, and industry
- Certain AI skills command substantial premiums in the job market
- Skill value changes throughout career progression from entry to executive levels
- Combinations of skills across different domains can significantly increase earning potential

## Files and Directories

- `2025-06-13-NB-1-Descriptive-Analysis.ipynb`: Notebook containing the descriptive analysis
- `2025-06-16-NB-2-Diagnostic-Analysis.ipynb`: Notebook containing the diagnostic analysis
- `data/`: Contains the AI job dataset
- `exports/`: Excel exports of key findings and transformed data

## Requirements

This project uses Python 3.12 with the following packages:
    - jupyterlab
    - matplotlib
    - numpy
    - openpyxl
    - pandas
    - plotly
    - scikit-learn
    - seaborn
    - statsmodels

## Setup and Installation

This project was set up using the `uv` package manager, a fast Python package installer and resolver. To get started:

1. Make sure you have Python 3.12+ installed

2. Install `uv` if you don't have it already:

   ```shell
   curl -sSf https://install.python-poetry.org | python3 -
   ```

3. Clone this repository

4. Create a virtual environment and install dependencies:

   ```shell
   uv venv
   uv pip install -e .
   ```

5. Start JupyterLab to explore the notebooks:

   ```shell
   jupyter lab
   ```

The `uv.lock` file ensures reproducible dependencies by locking all package versions.

## Connection to STEAMe's Mission

This analysis supports STEAMe's platform by:

1. Helping **learners** identify in-demand AI skills and promising career pathways
2. Enabling **employers** to benchmark compensation offerings and skill requirements
3. Guiding **learning providers** in developing curricula aligned with market demands
4. Supporting **workforce intermediaries** through data-driven insights
