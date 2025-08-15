# Employee_Retention_Analysis

## Objective
This project analyzes employee attrition in a fictional organization to uncover drivers of turnover and provide actionable strategies for improving retention.

## Dataset
- **Total records**: 1,470 employees
- **Features**:
  - Demographic: `Age`, `Gender`, `MaritalStatus`
  - Job Information: `JobRole`, `MonthlyIncome`, `OverTime`, `JobSatisfaction`, `YearsAtCompany`
  - Target: `Attrition` (Yes/No)

## Project Workflow

## Overview:
**1. Data Cleaning** – Removed irrelevant columns, handled missing values, converted categorical features.
**2. Exploratory Data Analysis (EDA)** – Explored attrition rates and feature relationships (e.g., OverTime, JobSatisfaction).
**3. Predictive Modeling** – Built a logistic regression model and evaluated performance (accuracy, recall, F1-score).
**4. Recommendations** – Designed strategies to reduce attrition based on insights.

### 1. Data Cleaning
- Removed irrelevant columns (e.g., `EmployeeNumber`).
- Converted categorical variables (e.g., `OverTime`, `JobRole`) to factors.
- Checked for and handled any missing values.

### 2. Exploratory Data Analysis (EDA)
- Examined overall attrition rate and key feature distributions.
- Explored relationships between `Attrition` and features such as `OverTime`, `JobSatisfaction`, and `MonthlyIncome`.
- Visualized feature correlations using heatmaps.

### 3. Predictive Modeling
- Built a logistic regression model to identify significant predictors of attrition.
- Evaluated the model using metrics such as accuracy, recall, and F1-score.

### 4. Key Insights
- **OverTime:** Employees with frequent overtime were significantly more likely to leave.
- **Job Satisfaction:** Low satisfaction strongly predicted attrition.
- **Monthly Income:** Higher-income employees showed greater stability.
- **Tenure:** Employees with longer years at the company were less likely to churn.

## Model Performance
- **Accuracy**: 84.32%
- **Recall (Attrition = Yes)**: 99.18%
- **F1-Score**: 53.11%
- **Top Predictors**:
  - `OverTime`
  - `JobSatisfaction`
  - `YearsWithCurrManager`
 
## Visualizations
**Attrition Distribution** 
**Attrition by OverTime** 
**Monthly Income Distribution by Attrition** 
**Correlation Heatmap** 

## Business Impact
Findings highlight that reducing overtime, improving job satisfaction, and supporting newer employees could materially reduce attrition rates, leading to cost savings in recruitment and training.

## Future Work
- Address class imbalance using SMOTE / class weighting.
- Test advanced models (Random Forest, Gradient Boosting) for improved predictive performance.

## Recommendations
- **Reduce Overtime:** Introduce policies to limit excessive overtime and offer flexible schedules.
- **Enhance Job Satisfaction:** Conduct surveys to identify employee concerns and improve workplace conditions.
- **Focus on Retaining Newer Employees:** Provide targeted support for employees with shorter tenure.

## How to Run
1. Clone this repository:
   
   git clone https://github.com/jenniferzag/Employee_Retention_Analysis.git

2. Install necessary R packages:
   install.packages(c("tidyverse", "caret", "ggplot2", "corrplot"))
   
3. Open EmployeeRetentionAnalysis.Rmd in RStudio.
  
4. Knit the file to reproduce the analysis and visualizations.

## Acklowledgements
- Dataset sourced from Kaggle.
- Libraries used: tidyverse, caret, ggplot2, corrplot.

## Contact
For questions or feedback, reach out via GitHub issues or email at [jennifer_zammyr@hotmail.com].
   
