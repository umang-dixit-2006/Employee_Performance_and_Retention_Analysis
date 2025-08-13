# Employee Performance and Retention Analysis

## Overview
This project analyzes employee data to predict performance and retention trends using probability, statistics, machine learning, and deep learning. The workflow is divided into four phases: data collection & EDA, predictive modeling, deep learning, and reporting.

## Approach & Methodology

### Phase 1: Data Collection & Exploratory Data Analysis (EDA)
- Loaded and cleaned the dataset (`employee_data.csv`).
- Handled missing values, removed duplicates, and standardized data entries.
- Performed descriptive statistics and visualized relationships using pairplots, heatmaps, and boxplots.

### Phase 2: Predictive Modeling
- Engineered features and encoded categorical variables.
- Built a Random Forest Classifier to predict employee attrition.
- Built a Linear Regression model to predict employee performance scores.
- Evaluated models using accuracy, precision, recall, F1-score, R², and MSE.

### Phase 3: Deep Learning
- Developed neural network models using TensorFlow/Keras for both regression (performance prediction) and classification (attrition prediction).
- Compared deep learning results with traditional machine learning models.

### Phase 4: Reporting & Insights
- Summarized key findings and provided actionable recommendations.
- Visualized trends such as performance over years, department-wise attrition, and salary vs. performance.

## Analysis Process
1. **Data Preprocessing:** Cleaned and prepared the data for analysis.
2. **EDA:** Explored data distributions, relationships, and outliers.
3. **Statistical Analysis:** Calculated probabilities, applied Bayes' theorem, and performed hypothesis testing.
4. **Modeling:** Built and evaluated machine learning and deep learning models.
5. **Reporting:** Generated visualizations and summarized insights.

## Key Findings
- Departments with lower average performance scores have higher attrition rates.
- Employees with lower salaries are more likely to leave.
- Longer tenure is correlated with higher performance scores.
- Deep learning models provided comparable or improved predictive accuracy over traditional models.

## Recommendations
- Implement targeted retention programs for at-risk departments.
- Review salaries for lower-paid high performers.
- Establish mentorship programs for new hires.

## How to Run
1. Install required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn tensorflow`
2. Open the notebook and run each cell sequentially.
3. Review the outputs and visualizations for insights.

## Files
- `Employee_analysis.ipynb`: Main analysis notebook.
- `employee_data.csv`: Employee dataset.
- `README.md`: Project documentation and summary.

---

**Author:** Umang Dixit

**Date:** 13 August 2025
