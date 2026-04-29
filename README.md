# Socioeconomic and Behavioral Determinants of Oral Health Analysis of NHANES 2013–2018 Data

Project Overview :
This capstone project examines how socioeconomic and behavioral factors influence oral health disparities among U.S. adults using nationally representative data from the National Health and Nutrition Examination Survey (NHANES) 2013–2018.
The study quantifies the independent impact of income, education, and smoking on:
Untreated dental caries (binary outcome)
Number of missing teeth (count outcome)

Research Objective :
To evaluate the association between socioeconomic status and oral health outcomes while adjusting for demographic and insurance-related confounders.

Data Source
Dataset: NHANES 2013–2018
Sample Size: ~25,000 U.S. adults (≥18 years)
Three survey cycles merged using participant identifier (SEQN)
Sampling weights applied according to NCHS analytic guidelines
Official source: CDC National Center for Health Statistics

Methodology
Data Preparation :
* Harmonized variables across three NHANES cycles
* Recoded categorical variables for consistency
* Applied sampling weights for national representativeness
* Handled missing values via listwise deletion (<5% missingness)

Statistical Analysis
Descriptive statistics :
* χ² tests (categorical comparisons)
* t-tests (continuous comparisons)
* Multivariable logistic regression (untreated caries)
* Multivariable linear regression (missing teeth)
* Adjusted for: Age, sex, Race/ethnicity, Dental insurance

Key Findings
Descriptive Results :
* Untreated caries prevalence:
* 34% among low-income adults
* 15% among high-income adults
* Missing teeth more prevalent among individuals with lower education and current smokers.

Regression Results :
* Predictor	Odds Ratio (95% CI)	p-value
* Income-to-poverty ratio ↑	0.74 (0.61–0.89)	0.002
* Education (College vs HS)	0.69 (0.55–0.86)	0.004
* Current smoker	1.95 (1.60–2.38)	< 0.001

Model explanatory power: R² ≈ 0.28
Interpretation:
Higher income and education are protective factors, while smoking nearly doubles the odds of poor oral health outcomes.

Public Health Implications
Findings reinforce that social and behavioral determinants significantly influence oral health disparities.
Policy relevance includes:
* Expanding preventive dental coverage
* Integrating smoking cessation into community health programs
* Targeting interventions toward socioeconomically vulnerable populations
