# Employee-Attrition

![image](https://github.com/user-attachments/assets/ce656d41-7f55-4f07-a9e7-5078fd1cf2aa)

## Project Overview

The goal of this project is to analyze employee attrition data to understand the factors contributing to employee turnover and to develop a predictive model that can identify employees who are likely to leave the company. This will help the organization implement effective strategies to reduce attrition and improve employee retention.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Overview](#data-overview)
- [Setup Instructions](#setup-instructions)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Feature Importance](#feature-importance)
- [Conclusions and Strategies](#conclusions-and-strategies)

  
## Data Overview

The dataset includes various features related to employee demographics, job roles, satisfaction levels, and other work-related attributes. Key features include:
- `Attrition`: Whether the employee left the company (Yes/No)
- `Age`
- `MonthlyIncome`
- `JobLevel`
- `TotalWorkingYears`
- `YearsAtCompany`
- Categorical features like `BusinessTravel`, `Department`, `Gender`, `JobRole`, etc.


### Prerequisites

- Python 3.6+
- Jupyter Notebook or Jupyter Lab
- Required Python packages (listed in `requirements.txt`)

### Exploratory Data Analysis (EDA)
The EDA process involves data cleaning, preprocessing, and visualization to understand the data distribution and relationships between features. Key steps include:

      * Data Cleaning and Preprocessing: Handling missing values and encoding categorical variables.
      * Univariate Analysis: Visualizing distributions of individual features.
      * Bivariate Analysis: Exploring relationships between features and attrition.
      * Correlation Analysis: Examining correlations between numerical features using a heatmap.

### Example visualizations:

      * Attrition Distribution
      * Age Distribution
      * Monthly Income Distribution
      * Attrition vs. Monthly Income (Boxplot)
      * Attrition vs. Age (Boxplot)
      * Attrition vs. Job Role (Countplot)
      * Correlation Heatmap

### Model Building
We use a "Random Forest Classifier" to build a predictive model for employee attrition. Key steps include:

      * Splitting the data into training and testing sets.
      * Training the Random Forest model on the training data.
      * Evaluating model performance using accuracy, precision, recall, F1-score, and the confusion matrix.
      * Feature Importance
                  - Monthly Income
                  - OverTime
                  - Age
                  - JobLevel
                  - TotalWorkingYears

### Conclusions and Strategies:-
Based on the EDA and model results, we propose the following strategies to reduce attrition:

          * Improve Compensation: Ensure competitive salaries, especially for roles with high attrition.
          * Enhance Work-Life Balance: Address OverTime issues by promoting a balanced workload.
          * Career Development: Provide clear career progression and professional development opportunities.
          * Job Role-Specific Interventions: Conduct deeper investigations for roles with high attrition rates.
          * Employee Engagement: Increase engagement through feedback and recognition programs.
          * Onboarding and Training: Strengthen onboarding programs and provide ongoing training.
