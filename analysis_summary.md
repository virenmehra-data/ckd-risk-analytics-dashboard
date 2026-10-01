# Analysis Summary

## Dataset

The analysis used a dataset containing **250 patient records** from a renal-unit case study. The project focused on a CKD Risk Score together with demographic, behavioural, and clinical variables.

## Dashboard Design

The dashboard was built in Excel to support quick exploration of CKD risk patterns. It combined charts, conditional formatting, PivotTables, and slicers so that users could compare risk across different patient groups.

The dashboard included:

- CKD risk-category proportions
- Average CKD Risk Score by residence and diabetes status
- Average blood pressure by risk category
- Physical activity versus CKD risk
- Serum creatinine and blood urea comparison
- Age, red blood cell count, or haemoglobin indicators

Slicers supported filtering by Residence, Diabetes Mellitus, Hypertension, Alcohol Intake, Physical Activity, and CKD Risk Category.

## Statistical Analysis

The project then extended the dashboard analysis using:

1. Descriptive statistics to summarise central tendency and spread.
2. Probability analysis to examine CKD Risk Score ranges.
3. Hypothesis testing to compare observed means with specified benchmarks.
4. Correlation analysis and scatterplots to identify relationships between continuous variables.
5. Multiple regression to estimate how clinical and categorical predictors were associated with CKD Risk Score.

Categorical variables were converted to dummy variables where required. Multicollinearity and statistical significance were reviewed, and non-significant predictors were removed iteratively when refining the regression model.

## Regression Interpretation

The final model explained approximately **76% of the variation in CKD Risk Score**, with an adjusted R-squared of approximately **0.75**.

Diabetes and hypertension were among the strongest categorical predictors in the final model. Serum creatinine and blood urea were positive and statistically significant clinical predictors. Packed Cell Volume, Red Blood Cell Count, and Haemoglobin also remained significant.

The analysis treated these outputs as statistical relationships within the supplied educational dataset, not as clinical diagnostic rules.

## Portfolio Presentation

This repository is a reformatted portfolio version of the original coursework. Personal identifiers, student details, and university submission material are intentionally excluded.
