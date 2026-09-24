# Exploring Employee Outcomes Using PERMANOVA

## Overview

This project examines how employee demographic and workplace characteristics are associated with multiple job-related outcomes using a nonparametric multivariate statistical framework.

The analysis investigates employee attributes including attrition status, business travel, department, gender, and marital status in relation to:

- Job satisfaction
- Monthly income
- Performance rating
- Work-life balance

Because the outcome variables did not satisfy normality assumptions, Permutational Multivariate Analysis of Variance (PERMANOVA) was used as the primary multivariate approach.

## Dataset

The dataset contains **1,029 employee records and 35 variables** describing employee demographics, workplace characteristics, compensation, satisfaction, performance, and tenure.

### Predictor Variables

- Attrition status
- Business travel frequency
- Department
- Gender
- Marital status

### Outcome Variables

- Job satisfaction
- Monthly income
- Performance rating
- Work-life balance

## Research Questions

The primary research question was:

**How are employee attributes such as attrition status, department, and business travel associated with job satisfaction, monthly income, performance rating, and work-life balance?**

Additional analyses examined:

1. Gender differences in job satisfaction and work-life balance.
2. Differences in performance and job satisfaction across business-travel categories.
3. Departmental differences in job satisfaction and performance.
4. Relationships between attrition status, monthly income, and job satisfaction.

## Statistical Methods

The analysis included:

- Exploratory data analysis
- Shapiro-Wilk normality tests
- Box's M test
- Correlation analysis
- PERMANOVA
- Kruskal-Wallis tests
- Wilcoxon rank-sum tests
- Pairwise comparisons
- Data visualization

PERMANOVA was selected because the dependent variables showed substantial departures from normality.

## Key Results

### Multivariate Analysis

The employee characteristics included in the PERMANOVA were collectively associated with the multivariate employee outcomes.

The model explained approximately **3.78% of the variation** in the combined outcomes and was statistically significant (**p < 0.001**).

The relatively small R² indicates that substantial variation in employee outcomes remains unexplained by the predictors considered in this analysis.

### Gender

No statistically significant differences were detected by gender for:

- Job satisfaction
- Work-life balance

### Business Travel

Business-travel frequency was not significantly associated with:

- Performance rating
- Job satisfaction

### Department

The analyses did not identify statistically significant departmental differences in job satisfaction.

### Attrition

Attrition status was significantly associated with both:

- **Monthly income (p < 0.001)**
- **Job satisfaction (p = 0.0015)**

Employees who left and employees who remained with the organization therefore differed significantly on these outcomes in this dataset.

These findings represent statistical associations and should not be interpreted as evidence that income or job satisfaction caused employee attrition.

## Skills Demonstrated

This project demonstrates experience with:

- R
- Multivariate statistical analysis
- PERMANOVA
- Nonparametric statistical methods
- Kruskal-Wallis testing
- Wilcoxon rank-sum testing
- Statistical assumption assessment
- Correlation analysis
- Data visualization
- Employee and organizational data analysis
- Statistical interpretation and reporting

## Repository Contents

- `Employee_Outcomes_PERMANOVA_Report.pdf` — Complete project report containing the methodology, analysis, results, visualizations, and conclusions.
- `README.md` — Summary of the project and key findings.

## Author

**Selorm Buaka**  
Department of Applied Statistics & Research Methods  
University of Northern Colorado

## Note

This project was conducted as an academic statistical analysis. Results describe associations observed in the analyzed dataset and should not be interpreted as causal relationships.
