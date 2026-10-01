# CKD Risk Analytics & Dashboard

**Excel · Data Analytics · Statistical Analysis · Regression**

## Project Overview

This project analyses a **250-patient chronic kidney disease (CKD) dataset** in the context of a hospital renal unit. The work combines an interactive Excel dashboard with descriptive statistics, probability analysis, hypothesis testing, correlation analysis, and multiple regression.

The objective was to identify patterns associated with CKD risk, communicate them visually, and translate the analysis into practical insights for a healthcare decision-making context.

## Dashboard

The Excel dashboard was designed to make CKD risk patterns easy to explore across patient characteristics and clinical indicators.

Core visuals included:

- CKD risk-category proportions
- Average CKD risk score by residence and diabetes status
- Average blood pressure by CKD risk category
- Physical activity versus CKD risk
- Serum creatinine and blood urea analysis
- Age, red blood cell count, and haemoglobin indicators

Interactive slicers were used for variables including:

- Residence
- Diabetes Mellitus
- Hypertension
- Alcohol Intake
- Physical Activity
- CKD Risk Category

## Analytical Methods

The project extended beyond dashboarding into statistical analysis using Excel.

Methods included:

- Descriptive statistics
- Probability analysis
- Confidence intervals
- Hypothesis testing
- Correlation analysis
- Scatterplots
- Multiple linear regression
- Dummy variables for categorical predictors
- Multicollinearity review
- Iterative removal of non-significant predictors
- Prediction and confidence intervals

## Selected Findings

### Physical Activity

Average CKD Risk Score differed across physical-activity groups:

| Activity Level | Mean CKD Risk Score | Standard Deviation |
| --- | ---: | ---: |
| Active | 58.98 | 17.81 |
| Inactive | 54.08 | 15.00 |
| Typical | 59.59 | 19.36 |

### Residence

Hypothesis testing found average CKD Risk Scores above 50 for both residence groups in the dataset:

- **Rural:** mean 56.49, *t* = 4.18, *p* < 0.001
- **Urban:** mean 59.68, *t* = 5.99, *p* < 0.001

### Regression

The final multiple-regression model explained approximately **76% of the variation in CKD Risk Score** (**R² ≈ 0.76; adjusted R² ≈ 0.75**).

Selected model results included:

- Diabetes: coefficient ≈ **+10.40**, *p* < 0.001
- Hypertension: coefficient ≈ **+8.94**, *p* < 0.001
- Packed Cell Volume: coefficient ≈ **+0.33**, *p* = 0.038
- Red Blood Cell Count: coefficient ≈ **−1.82**, *p* = 0.001
- Haemoglobin: coefficient ≈ **−2.81**, *p* = 0.020
- Serum Creatinine and Blood Urea were also positive and statistically significant predictors in the analysis

Age, Blood Pressure, Blood Sugar, and White Blood Cell Count were not statistically significant in the final model.

## CKD Risk Categories

The dashboard grouped CKD Risk Score into the following categories:

- **Low:** below 20
- **Moderate:** 21–49
- **High:** 50–74
- **Very High:** above 75

## Repository Structure

```text
ckd-risk-analytics-dashboard/
├── README.md
├── analysis_summary.md
└── key_results.csv
```

## Skills Demonstrated

**Excel · Dashboard Design · Data Visualisation · PivotTables · Slicers · Descriptive Statistics · Hypothesis Testing · Correlation · Multiple Regression · Data Interpretation · Business Analytics**

## Project Context

This portfolio case study consolidates work completed in **MIS171** at Deakin University. University submission identifiers and personal details have been excluded from this public repository.
